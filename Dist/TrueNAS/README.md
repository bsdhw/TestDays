TrueNAS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for TrueNAS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/TrueNAS/Desktop/README.md) and [notebooks](/Dist/TrueNAS/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 53

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| TrueNAS 12.2-p2  | 9         | 21.95%  |
| TrueNAS 12.2-p6  | 8         | 19.51%  |
| TrueNAS 12.2-p9  | 6         | 14.63%  |
| TrueNAS 12.2-RC3 | 4         | 9.76%   |
| TrueNAS 12.2-p12 | 4         | 9.76%   |
| TrueNAS 12.2-p11 | 4         | 9.76%   |
| TrueNAS 12.2-p10 | 3         | 7.32%   |
| TrueNAS 12.3-p1  | 1         | 2.44%   |
| TrueNAS 12.2-p3  | 1         | 2.44%   |
| TrueNAS 12.2     | 1         | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TrueNAS | 36        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 33        | 91.67%  |
| helloDesktop | 2         | 5.56%   |
| TWM          | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 35        | 97.22%  |
| X11     | 1         | 2.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 36        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 36        | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 23        | 63.89%  |
| EFI  | 13        | 36.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 33        | 91.67%  |
| XXX     | 2         | 5.56%   |
| Unknown | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 36        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Supermicro          | 8         | 22.22%  |
| Unknown             | 6         | 16.67%  |
| Dell                | 5         | 13.89%  |
| ASUSTek Computer    | 5         | 13.89%  |
| Gigabyte Technology | 4         | 11.11%  |
| Hewlett-Packard     | 3         | 8.33%   |
| ASRock              | 3         | 8.33%   |
| TYAN Computer       | 1         | 2.78%   |
| Lenovo              | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 16.67%  |
| Dell PowerEdge R720xd               | 2         | 5.56%   |
| TYAN S5512                          | 1         | 2.78%   |
| Supermicro X9SPV-F/LN4F             | 1         | 2.78%   |
| Supermicro X9SCL/X9SCM              | 1         | 2.78%   |
| Supermicro X9DRD-7LN4F              | 1         | 2.78%   |
| Supermicro X8STi                    | 1         | 2.78%   |
| Supermicro X10SLM-F                 | 1         | 2.78%   |
| Supermicro X10SLH-F/X10SLM+-F       | 1         | 2.78%   |
| Supermicro X10SAE                   | 1         | 2.78%   |
| Supermicro ReadyDATA 5200           | 1         | 2.78%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1         | 2.78%   |
| HP ProLiant ML150 G6                | 1         | 2.78%   |
| HP ProLiant MicroServer Gen8        | 1         | 2.78%   |
| HP Compaq Elite 8300 SFF            | 1         | 2.78%   |
| Gigabyte H97-D3H                    | 1         | 2.78%   |
| Gigabyte GA-A75-UD4H                | 1         | 2.78%   |
| Gigabyte B550I AORUS PRO AX         | 1         | 2.78%   |
| Gigabyte B450M DS3H                 | 1         | 2.78%   |
| Dell PowerEdge T310                 | 1         | 2.78%   |
| Dell PowerEdge T110 II              | 1         | 2.78%   |
| Dell PowerEdge 2950                 | 1         | 2.78%   |
| ASUS TUF Z270 MARK 2                | 1         | 2.78%   |
| ASUS P10S-I Series                  | 1         | 2.78%   |
| ASUS M5A99X EVO R2.0                | 1         | 2.78%   |
| ASUS M5A78L-M/USB3                  | 1         | 2.78%   |
| ASUS M5A78L-M PLUS/USB3             | 1         | 2.78%   |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1         | 2.78%   |
| ASRock C2750D4I                     | 1         | 2.78%   |
| ASRock B560M Pro4/ac                | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 6         | 16.67%  |
| Dell PowerEdge                  | 5         | 13.89%  |
| HP ProLiant                     | 2         | 5.56%   |
| ASUS M5A78L-M                   | 2         | 5.56%   |
| TYAN S5512                      | 1         | 2.78%   |
| Supermicro X9SPV-F              | 1         | 2.78%   |
| Supermicro X9SCL                | 1         | 2.78%   |
| Supermicro X9DRD-7LN4F          | 1         | 2.78%   |
| Supermicro X8STi                | 1         | 2.78%   |
| Supermicro X10SLM-F             | 1         | 2.78%   |
| Supermicro X10SLH-F             | 1         | 2.78%   |
| Supermicro X10SAE               | 1         | 2.78%   |
| Supermicro ReadyDATA            | 1         | 2.78%   |
| Lenovo 70AQ0009UX               | 1         | 2.78%   |
| HP Compaq                       | 1         | 2.78%   |
| Gigabyte H97-D3H                | 1         | 2.78%   |
| Gigabyte GA-A75-UD4H            | 1         | 2.78%   |
| Gigabyte B550I                  | 1         | 2.78%   |
| Gigabyte B450M                  | 1         | 2.78%   |
| ASUS TUF                        | 1         | 2.78%   |
| ASUS P10S-I                     | 1         | 2.78%   |
| ASUS M5A99X                     | 1         | 2.78%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1         | 2.78%   |
| ASRock C2750D4I                 | 1         | 2.78%   |
| ASRock B560M                    | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 6         | 16.67%  |
| Unknown | 6         | 16.67%  |
| 2018    | 4         | 11.11%  |
| 2019    | 3         | 8.33%   |
| 2016    | 3         | 8.33%   |
| 2012    | 3         | 8.33%   |
| 2020    | 2         | 5.56%   |
| 2013    | 2         | 5.56%   |
| 2011    | 2         | 5.56%   |
| 2010    | 2         | 5.56%   |
| 2021    | 1         | 2.78%   |
| 2017    | 1         | 2.78%   |
| 2009    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 28        | 77.78%  |
| Server  | 8         | 22.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 12        | 33.33%  |
| 16.01-24.0  | 9         | 25%     |
| 24.01-32.0  | 5         | 13.89%  |
| 64.01-256.0 | 5         | 13.89%  |
| 8.01-16.0   | 4         | 11.11%  |
| 4.01-8.0    | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 12        | 33.33%  |
| 1.01-2.0   | 11        | 30.56%  |
| 2.01-3.0   | 4         | 11.11%  |
| 16.01-24.0 | 2         | 5.56%   |
| 0.01-0.5   | 2         | 5.56%   |
| 4.01-8.0   | 1         | 2.78%   |
| 32.01-64.0 | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |
| 24.01-32.0 | 1         | 2.78%   |
| 8.01-16.0  | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 6         | 16.22%  |
| 3      | 5         | 13.51%  |
| 14     | 3         | 8.11%   |
| 9      | 3         | 8.11%   |
| 4      | 3         | 8.11%   |
| 17     | 2         | 5.41%   |
| 6      | 2         | 5.41%   |
| 5      | 2         | 5.41%   |
| 2      | 2         | 5.41%   |
| 27     | 1         | 2.7%    |
| 21     | 1         | 2.7%    |
| 19     | 1         | 2.7%    |
| 15     | 1         | 2.7%    |
| 12     | 1         | 2.7%    |
| 11     | 1         | 2.7%    |
| 10     | 1         | 2.7%    |
| 8      | 1         | 2.7%    |
| 7      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 86.49%  |
| Yes       | 5         | 13.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 94.44%  |
| Yes       | 2         | 5.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 94.44%  |
| Yes       | 2         | 5.56%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 30.56%  |
| Germany     | 4         | 11.11%  |
| Greece      | 3         | 8.33%   |
| Australia   | 3         | 8.33%   |
| Thailand    | 2         | 5.56%   |
| Czechia     | 2         | 5.56%   |
| Canada      | 2         | 5.56%   |
| Brazil      | 2         | 5.56%   |
| Switzerland | 1         | 2.78%   |
| Spain       | 1         | 2.78%   |
| Norway      | 1         | 2.78%   |
| Nicaragua   | 1         | 2.78%   |
| France      | 1         | 2.78%   |
| Estonia     | 1         | 2.78%   |
| Belgium     | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Springfield          | 2         | 5%      |
| Melbourne            | 2         | 5%      |
| Lüneburg            | 2         | 5%      |
| Brno                 | 2         | 5%      |
| Bangkok              | 2         | 5%      |
| Athens               | 2         | 5%      |
| Yverdon-les-Bains    | 1         | 2.5%    |
| Tartu                | 1         | 2.5%    |
| Tamm                 | 1         | 2.5%    |
| Sydney               | 1         | 2.5%    |
| Skiptvet             | 1         | 2.5%    |
| SÃ£o Paulo         | 1         | 2.5%    |
| Raleigh              | 1         | 2.5%    |
| Perry Hall           | 1         | 2.5%    |
| Ougree               | 1         | 2.5%    |
| Northville           | 1         | 2.5%    |
| Managua              | 1         | 2.5%    |
| Lubbock              | 1         | 2.5%    |
| Kennedale            | 1         | 2.5%    |
| JundiaГ­           | 1         | 2.5%    |
| Jundiaí             | 1         | 2.5%    |
| JundiaÃ­           | 1         | 2.5%    |
| JaraguÃ¡ do Sul    | 1         | 2.5%    |
| Hendersonville       | 1         | 2.5%    |
| Gatineau             | 1         | 2.5%    |
| Galatista            | 1         | 2.5%    |
| Fontaine-le-Comte    | 1         | 2.5%    |
| Fayetteville         | 1         | 2.5%    |
| East Granby          | 1         | 2.5%    |
| Dresden              | 1         | 2.5%    |
| Clare                | 1         | 2.5%    |
| Campo Limpo Paulista | 1         | 2.5%    |
| Calgary              | 1         | 2.5%    |
| Algete               | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 82     | 21.52%  |
| Seagate             | 17        | 107    | 21.52%  |
| Samsung Electronics | 6         | 10     | 7.59%   |
| Intel               | 6         | 14     | 7.59%   |
| Hitachi             | 6         | 22     | 7.59%   |
| Toshiba             | 5         | 8      | 6.33%   |
| Kingston            | 4         | 9      | 5.06%   |
| Crucial             | 4         | 5      | 5.06%   |
| SanDisk             | 3         | 3      | 3.8%    |
| Hewlett-Packard     | 2         | 8      | 2.53%   |
| WD MediaMax         | 1         | 3      | 1.27%   |
| Transcend           | 1         | 1      | 1.27%   |
| SPCC                | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| Mushkin             | 1         | 1      | 1.27%   |
| HPT                 | 1         | 16     | 1.27%   |
| HGST                | 1         | 10     | 1.27%   |
| Apacer              | 1         | 1      | 1.27%   |
| AMD                 | 1         | 2      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| WDC WD40EFRX-68N32N0 4TB            | 5         | 3.29%   |
| WDC WD30EFRX-68EUZN0 3TB            | 4         | 2.63%   |
| WDC WD40EFRX-68WT0N0 4TB            | 3         | 1.97%   |
| Samsung SSD 860 EVO 250GB           | 3         | 1.97%   |
| WDC WD60EFRX-68MYMN1 6TB            | 2         | 1.32%   |
| WDC WD30EFRX-68AX9N0 3TB            | 2         | 1.32%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2         | 1.32%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2         | 1.32%   |
| WDC WD20EFRX-68AX9N0 2TB            | 2         | 1.32%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 1.32%   |
| Seagate ST4000DM000-1F2168 4TB      | 2         | 1.32%   |
| Seagate ST2000DM001-1ER164 2TB      | 2         | 1.32%   |
| Kingston SA400S37120G 120GB         | 2         | 1.32%   |
| Intel SSDSC2BB120G4 120GB           | 2         | 1.32%   |
| Hitachi HUA722020ALA331 2TB         | 2         | 1.32%   |
| WDC WD8004FRYZ-01VAEB0 8TB          | 1         | 0.66%   |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 0.66%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 0.66%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 0.66%   |
| WDC WD4003FFBX-68MU3N0 4TB          | 1         | 0.66%   |
| WDC WD30PURX-64P6ZY0 3TB            | 1         | 0.66%   |
| WDC WD30EZRX-00MMMB0 3TB            | 1         | 0.66%   |
| WDC WD30EFRX-68N32N0 3TB            | 1         | 0.66%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1         | 0.66%   |
| WDC WD3001FFSX-68JNUN0 3TB          | 1         | 0.66%   |
| WDC WD3000F9YZ-09N20L1 3TB          | 1         | 0.66%   |
| WDC WD3000F9YZ-09N20L0 3TB          | 1         | 0.66%   |
| WDC WD2002FFSX-68PF8N0 2TB          | 1         | 0.66%   |
| WDC WD2000FYYZ 2TB                  | 1         | 0.66%   |
| WDC WD120EDAZ-11F3RA0 12TB          | 1         | 0.66%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 0.66%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.66%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 0.66%   |
| WDC WD10EURX-61C57Y0 1TB            | 1         | 0.66%   |
| WDC WD100EMAZ-00WJTA0 10TB          | 1         | 0.66%   |
| WD MediaMax WL2000GSA6454 2TB       | 1         | 0.66%   |
| Transcend TS64GSSD370S 64GB         | 1         | 0.66%   |
| Toshiba THNSNX032GTNT M.2 2242 32GB | 1         | 0.66%   |
| Toshiba THNSNX032GTNT 32GB          | 1         | 0.66%   |
| Toshiba MG03ACA200 2TB              | 1         | 0.66%   |
| Toshiba HDWN180 8TB                 | 1         | 0.66%   |
| Toshiba HDWD130 3TB                 | 1         | 0.66%   |
| Toshiba DT01ACA300 3TB              | 1         | 0.66%   |
| Toshiba DT01ACA100 1TB              | 1         | 0.66%   |
| SPCC SPCCSolidStateDisk 256GB       | 1         | 0.66%   |
| Seagate ST980310AS 80GB             | 1         | 0.66%   |
| Seagate ST9320421AS 320GB           | 1         | 0.66%   |
| Seagate ST9320325AS 320GB           | 1         | 0.66%   |
| Seagate ST8000VN0022-2EL112 8TB     | 1         | 0.66%   |
| Seagate ST6000NM0104 6TB            | 1         | 0.66%   |
| Seagate ST6000NM0074 6TB            | 1         | 0.66%   |
| Seagate ST500DL001 HD503HI 500GB    | 1         | 0.66%   |
| Seagate ST4000VN008-2DR166 4TB      | 1         | 0.66%   |
| Seagate ST4000DM005-2DP166 4TB      | 1         | 0.66%   |
| Seagate ST4000DM004-2CV104 4TB      | 1         | 0.66%   |
| Seagate ST3320311CS 320GB           | 1         | 0.66%   |
| Seagate ST32000542AS 2TB            | 1         | 0.66%   |
| Seagate ST31500341AS 1.5TB          | 1         | 0.66%   |
| Seagate ST300MM0026 304GB           | 1         | 0.66%   |
| Seagate ST300MM0006 304GB           | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 82     | 33.33%  |
| Seagate             | 17        | 107    | 33.33%  |
| Hitachi             | 6         | 22     | 11.76%  |
| Toshiba             | 5         | 6      | 9.8%    |
| Hewlett-Packard     | 2         | 8      | 3.92%   |
| WD MediaMax         | 1         | 3      | 1.96%   |
| Samsung Electronics | 1         | 3      | 1.96%   |
| HPT                 | 1         | 16     | 1.96%   |
| HGST                | 1         | 10     | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 20%     |
| Kingston            | 4         | 7      | 16%     |
| Intel               | 4         | 12     | 16%     |
| SanDisk             | 3         | 3      | 12%     |
| Crucial             | 2         | 3      | 8%      |
| Transcend           | 1         | 1      | 4%      |
| Toshiba             | 1         | 2      | 4%      |
| SPCC                | 1         | 1      | 4%      |
| PNY                 | 1         | 1      | 4%      |
| Mushkin             | 1         | 1      | 4%      |
| Apacer              | 1         | 1      | 4%      |
| AMD                 | 1         | 2      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 257    | 54.55%  |
| SSD  | 20        | 41     | 36.36%  |
| NVMe | 5         | 6      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 298    | 85.71%  |
| NVMe | 5         | 6      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 68     | 33.33%  |
| 1.01-2.0   | 12        | 50     | 17.39%  |
| 2.01-3.0   | 11        | 64     | 15.94%  |
| 3.01-4.0   | 10        | 60     | 14.49%  |
| 4.01-10.0  | 6         | 24     | 8.7%    |
| 0.51-1.0   | 5         | 28     | 7.25%   |
| 10.01-20.0 | 2         | 4      | 2.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 32.43%  |
| 101-250        | 8         | 21.62%  |
| 251-500        | 6         | 16.22%  |
| 21-50          | 4         | 10.81%  |
| 51-100         | 3         | 8.11%   |
| Unknown        | 2         | 5.41%   |
| More than 3000 | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 34        | 94.44%  |
| Unknown | 2         | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 5      | 7.41%   |
| WDC WD60EFRX-68MYMN1 6TB        | 1         | 1      | 3.7%    |
| WDC WD5000AAKX-00U6AA0 500GB    | 1         | 1      | 3.7%    |
| WDC WD30PURX-64P6ZY0 3TB        | 1         | 1      | 3.7%    |
| WDC WD30EZRX-00MMMB0 3TB        | 1         | 2      | 3.7%    |
| WDC WD20EFRX-68AX9N0 2TB        | 1         | 1      | 3.7%    |
| WDC WD2000FYYZ 2TB              | 1         | 2      | 3.7%    |
| WDC WD10PURX-64E5EY0 1TB        | 1         | 1      | 3.7%    |
| WDC WD10EZEX-00RKKA0 1TB        | 1         | 1      | 3.7%    |
| WD MediaMax WL2000GSA6454 2TB   | 1         | 3      | 3.7%    |
| Toshiba HDWD130 3TB             | 1         | 2      | 3.7%    |
| Seagate ST980310AS 80GB         | 1         | 1      | 3.7%    |
| Seagate ST9320325AS 320GB       | 1         | 1      | 3.7%    |
| Seagate ST4000DM000-1F2168 4TB  | 1         | 1      | 3.7%    |
| Seagate ST3320311CS 320GB       | 1         | 2      | 3.7%    |
| Seagate ST31500341AS 1.5TB      | 1         | 1      | 3.7%    |
| Seagate ST3000VN007-2E4166 3TB  | 1         | 1      | 3.7%    |
| Seagate ST3000NM0033-9ZM178 3TB | 1         | 7      | 3.7%    |
| Seagate ST2000NM0033-9ZM175 2TB | 1         | 1      | 3.7%    |
| Seagate ST2000DL003-9VT166 2TB  | 1         | 1      | 3.7%    |
| Seagate ST2000DL001-9VT156 2TB  | 1         | 1      | 3.7%    |
| Seagate ST1000VM002-1SD102 1TB  | 1         | 2      | 3.7%    |
| Intel SSDSC2BA200G3T 200GB      | 1         | 1      | 3.7%    |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 3.7%    |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 3.7%    |
| Hitachi HDS723020BLA642 2TB     | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 19     | 37.5%   |
| WDC         | 5         | 15     | 31.25%  |
| Hitachi     | 2         | 3      | 12.5%   |
| WD MediaMax | 1         | 3      | 6.25%   |
| Toshiba     | 1         | 2      | 6.25%   |
| Intel       | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 19     | 40%     |
| WDC         | 5         | 15     | 33.33%  |
| Hitachi     | 2         | 3      | 13.33%  |
| WD MediaMax | 1         | 3      | 6.67%   |
| Toshiba     | 1         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 42     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 30        | 240    | 71.43%  |
| Malfunc  | 10        | 43     | 23.81%  |
| Detected | 2         | 21     | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 28        | 38.89%  |
| Broadcom / LSI              | 13        | 18.06%  |
| AMD                         | 7         | 9.72%   |
| Marvell Technology Group    | 6         | 8.33%   |
| ASMedia Technology          | 3         | 4.17%   |
| Silicon Image               | 2         | 2.78%   |
| Micron/Crucial Technology   | 2         | 2.78%   |
| Kingston Technology Company | 2         | 2.78%   |
| JMicron Technology          | 2         | 2.78%   |
| Hewlett-Packard             | 2         | 2.78%   |
| Silicon Motion              | 1         | 1.39%   |
| QLogic                      | 1         | 1.39%   |
| HighPoint Technologies      | 1         | 1.39%   |
| Dell                        | 1         | 1.39%   |
| Areca Technology            | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 11        | 13.25%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 6.02%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 4         | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 3.61%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 3.61%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2         | 2.41%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 2.41%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 2.41%   |
| JMicron JMB58x AHCI SATA controller                                            | 2         | 2.41%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 2         | 2.41%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2         | 2.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 2.41%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 2.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.41%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 2         | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 2.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 2.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.2%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 1.2%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.2%    |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                    | 1         | 1.2%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.2%    |
| Intel PCIe Data Center SSD                                                     | 1         | 1.2%    |
| Intel NVMe Optane Memory Series                                                | 1         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.2%    |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 1.2%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 1.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.2%    |
| Intel 631xESB/632xESB IDE Controller                                           | 1         | 1.2%    |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1         | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.2%    |
| HighPoint RocketRAID 2760 SAS Controller                                       | 1         | 1.2%    |
| HP Smart Array G6 controllers                                                  | 1         | 1.2%    |
| HP Smart Array Controller                                                      | 1         | 1.2%    |
| Dell PowerEdge Expandable RAID controller 5                                    | 1         | 1.2%    |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller          | 1         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 1.2%    |
| AMD FCH IDE Controller                                                         | 1         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.2%    |
| Unknown                                                                        | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 29        | 43.94%  |
| RAID | 11        | 16.67%  |
| SAS  | 10        | 15.15%  |
| NVMe | 7         | 10.61%  |
| IDE  | 7         | 10.61%  |
| SCSI | 2         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 80.56%  |
| AMD    | 7         | 19.44%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Xeon CPU E5504 @ 2.00GHz           | 2         | 5.56%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 2         | 5.56%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 2         | 5.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 2         | 5.56%   |
| Intel Atom CPU C2750 @ 2.40GHz           | 2         | 5.56%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 2.78%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 2.78%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 2.78%   |
| Intel Xeon CPU E5506 @ 2.13GHz           | 1         | 2.78%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz       | 1         | 2.78%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz       | 1         | 2.78%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz       | 1         | 2.78%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz      | 1         | 2.78%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 1         | 2.78%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz      | 1         | 2.78%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1         | 2.78%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 1         | 2.78%   |
| Intel Xeon CPU 5160 @ 3.00GHz            | 1         | 2.78%   |
| Intel Core i7-3555LE CPU @ 2.50GHz       | 1         | 2.78%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 2.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 1         | 2.78%   |
| Intel Core i3-4330 CPU @ 3.50GHz         | 1         | 2.78%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 1         | 2.78%   |
| Intel Celeron CPU G1610T @ 2.30GHz       | 1         | 2.78%   |
| AMD Ryzen 7 1800X Eight-Core Processor   | 1         | 2.78%   |
| AMD Ryzen 5 3600 6-Core Processor        | 1         | 2.78%   |
| AMD FX-8320E Eight-Core Processor        | 1         | 2.78%   |
| AMD FX-8300 Eight-Core Processor         | 1         | 2.78%   |
| AMD FX-6300 Six-Core Processor           | 1         | 2.78%   |
| AMD E1-2500 APU with Radeon HD Graphics  | 1         | 2.78%   |
| AMD A8-3870 APU with Radeon HD Graphics  | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Intel Xeon    | 19        | 52.78%  |
| Intel Core i5 | 4         | 11.11%  |
| AMD FX        | 3         | 8.33%   |
| Intel Core i3 | 2         | 5.56%   |
| Intel Atom    | 2         | 5.56%   |
| Intel Core i7 | 1         | 2.78%   |
| Intel Celeron | 1         | 2.78%   |
| AMD Ryzen 7   | 1         | 2.78%   |
| AMD Ryzen 5   | 1         | 2.78%   |
| AMD E1        | 1         | 2.78%   |
| AMD A8        | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 19        | 52.78%  |
| 8       | 7         | 19.44%  |
| 2       | 4         | 11.11%  |
| 16      | 3         | 8.33%   |
| 12      | 1         | 2.78%   |
| 6       | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 83.33%  |
| 2      | 6         | 16.67%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 26        | 72.22%  |
| 2       | 9         | 25%     |
| Unknown | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 6         | 16.67%  |
| Haswell     | 6         | 16.67%  |
| Nehalem     | 5         | 13.89%  |
| KabyLake    | 4         | 11.11%  |
| SandyBridge | 3         | 8.33%   |
| Piledriver  | 3         | 8.33%   |
| Silvermont  | 2         | 5.56%   |
| Zen 2       | 1         | 2.78%   |
| Zen         | 1         | 2.78%   |
| K10 Llano   | 1         | 2.78%   |
| Jaguar      | 1         | 2.78%   |
| Core        | 1         | 2.78%   |
| CometLake   | 1         | 2.78%   |
| Broadwell   | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Matrox Electronics Systems | 13        | 37.14%  |
| Intel                      | 7         | 20%     |
| ASPEED Technology          | 7         | 20%     |
| AMD                        | 7         | 20%     |
| Nvidia                     | 1         | 2.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems MGA G200eW WPCM450                               | 7         | 20%     |
| ASPEED Technology ASPEED Graphics Family                                    | 7         | 20%     |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 5.71%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 5.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 5.71%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 2         | 5.71%   |
| Intel HD Graphics 630                                                       | 2         | 5.71%   |
| AMD RS780L [Radeon 3000]                                                    | 2         | 5.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 2.86%   |
| Matrox Electronics Systems MGA G200eH3                                      | 1         | 2.86%   |
| Matrox Electronics Systems MGA G200EH                                       | 1         | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 2.86%   |
| AMD Sumo [Radeon HD 6550D]                                                  | 1         | 2.86%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1         | 2.86%   |
| AMD ES1000                                                                  | 1         | 2.86%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1         | 2.86%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Matrox | 13        | 36.11%  |
| 1 x Intel  | 7         | 19.44%  |
| 1 x ASPEED | 7         | 19.44%  |
| 1 x AMD    | 7         | 19.44%  |
| Other      | 1         | 2.78%   |
| 1 x Nvidia | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 35        | 97.22%  |
| Unknown | 1         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 100%    |

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

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 36        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 63.41%  |
| Realtek Semiconductor | 7         | 17.07%  |
| Broadcom              | 7         | 17.07%  |
| QLogic                | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 6         | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 9.26%   |
| Intel I350 Gigabit Network Connection                                         | 4         | 7.41%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 7.41%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 7.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 5.56%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.7%    |
| Intel 82576 Gigabit Network Connection                                        | 2         | 3.7%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 3.7%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 3.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.85%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.85%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.85%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.85%   |
| Intel Ethernet Connection I217-V                                              | 1         | 1.85%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.85%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.85%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.85%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.85%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.85%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.85%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.85%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.85%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.85%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200            | 1         | 50%     |
| Intel Tiger Lake PCH CNVi WiFi | 1         | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 62.5%   |
| Realtek Semiconductor | 7         | 17.5%   |
| Broadcom              | 7         | 17.5%   |
| QLogic                | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel I210 Gigabit Network Connection                                         | 6         | 11.54%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 9.62%   |
| Intel I350 Gigabit Network Connection                                         | 4         | 7.69%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 7.69%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 7.69%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 5.77%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2         | 3.85%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 3.85%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 3.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 3.85%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.92%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.92%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.92%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.92%   |
| Intel Ethernet Connection I217-V                                              | 1         | 1.92%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.92%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.92%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.92%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.92%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.92%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.92%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.92%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.92%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 94.74%  |
| WiFi     | 2         | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 36        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 12        | 33.33%  |
| 1     | 9         | 25%     |
| 4     | 6         | 16.67%  |
| 6     | 4         | 11.11%  |
| 5     | 4         | 11.11%  |
| 3     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 50%     |
| Intel AX200 Bluetooth                          | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 5         | 50%     |
| Intel  | 4         | 40%     |
| Nvidia | 1         | 10%     |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2         | 13.33%  |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 13.33%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 6.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1         | 6.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 6.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 6.67%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 6.67%   |
| AMD FCH Azalia Controller                                                         | 1         | 6.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 6.67%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 6.67%   |
| Unknown                                                                           | 1         | 6.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25.64%  |
| Kingston            | 6         | 15.38%  |
| Unknown             | 5         | 12.82%  |
| Micron Technology   | 5         | 12.82%  |
| SK Hynix            | 4         | 10.26%  |
| Corsair             | 2         | 5.13%   |
| Transcend           | 1         | 2.56%   |
| Toshiba             | 1         | 2.56%   |
| Team                | 1         | 2.56%   |
| PNY                 | 1         | 2.56%   |
| Patriot             | 1         | 2.56%   |
| Hewlett-Packard     | 1         | 2.56%   |
| Crucial             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                | 1         | 2.33%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1         | 2.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 2.33%   |
| Transcend RAM TS1GLK72V6H 8192MB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s     | 1         | 2.33%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s              | 1         | 2.33%   |
| SK Hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 2.33%   |
| SK Hynix RAM HMT41GU7BFR8A-PB 8192MB DIMM DDR3 1600MT/s     | 1         | 2.33%   |
| SK Hynix RAM HMT351R7CFR8A-H9 4096MB DIMM DDR3 800MT/s      | 1         | 2.33%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 2.33%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 2.33%   |
| Samsung RAM M395T5750EZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1         | 2.33%   |
| Samsung RAM M395T5750CZ4-CE61 2048MB FB-DIMM DDR2 667MT/s   | 1         | 2.33%   |
| Samsung RAM M393B2K70CM0-CF8 16384MB DIMM DDR3 1066MT/s     | 1         | 2.33%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s     | 1         | 2.33%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s      | 1         | 2.33%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 2.33%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s       | 1         | 2.33%   |
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s      | 1         | 2.33%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s      | 1         | 2.33%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s         | 1         | 2.33%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s         | 1         | 2.33%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s      | 1         | 2.33%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s        | 1         | 2.33%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s      | 1         | 2.33%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Kingston RAM 9965684-012.A00G 8192MB DIMM DDR4 2400MT/s     | 1         | 2.33%   |
| Kingston RAM 9965527-026.A00LF 8192MB DIMM DDR3 1333MT/s    | 1         | 2.33%   |
| Kingston RAM 9965525-140.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 2.33%   |
| Kingston RAM 9965525-054.A00LF 4096MB DIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Kingston RAM 9965525-037.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 2.33%   |
| Kingston RAM 9965516-057.A00LF 8192MB DIMM DDR3 1066MT/s    | 1         | 2.33%   |
| HP RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 2.33%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s      | 1         | 2.33%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Corsair RAM CMD16GX4M2B3000C15 8192MB DIMM DDR4 2133MT/s    | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 70%     |
| DDR4    | 5         | 16.67%  |
| Unknown | 3         | 10%     |
| DDR2    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 29        | 96.67%  |
| FB-DIMM | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 23        | 60.53%  |
| 4096  | 7         | 18.42%  |
| 16384 | 4         | 10.53%  |
| 2048  | 4         | 10.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 34.38%  |
| 1333  | 9         | 28.13%  |
| 1066  | 3         | 9.38%   |
| 2133  | 2         | 6.25%   |
| 800   | 2         | 6.25%   |
| 667   | 2         | 6.25%   |
| 3200  | 1         | 3.13%   |
| 2667  | 1         | 3.13%   |
| 2400  | 1         | 3.13%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 50%     |
| 2     | 8         | 22.22%  |
| 1     | 5         | 13.89%  |
| 3     | 3         | 8.33%   |
| 5     | 1         | 2.78%   |
| 4     | 1         | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 13        | 46.43%  |
| Sound                    | 9         | 32.14%  |
| Net/wireless             | 2         | 7.14%   |
| Firewire controller      | 2         | 7.14%   |
| Bluetooth                | 2         | 7.14%   |
