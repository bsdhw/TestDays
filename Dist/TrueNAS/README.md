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

Total: 69

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Supermicro    | X10SLL-F                    | Server      | [d08cceec12](https://bsd-hardware.info/?probe=d08cceec12) | Feb 11, 2024 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17f70cfb67](https://bsd-hardware.info/?probe=17f70cfb67) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bed6c30cd](https://bsd-hardware.info/?probe=1bed6c30cd) | Nov 22, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [05925afd0a](https://bsd-hardware.info/?probe=05925afd0a) | Jun 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [74d372e7a4](https://bsd-hardware.info/?probe=74d372e7a4) | Jun 19, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [41b04a4c81](https://bsd-hardware.info/?probe=41b04a4c81) | Jan 11, 2023 |
| Supermicro    | X11DPi-N                    | Server      | [1f1f11fc1a](https://bsd-hardware.info/?probe=1f1f11fc1a) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
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
| TrueNAS 12.2-p2  | 9         | 16.07%  |
| TrueNAS 12.2-p6  | 8         | 14.29%  |
| TrueNAS 12.2-p9  | 6         | 10.71%  |
| TrueNAS 12.2-p12 | 6         | 10.71%  |
| TrueNAS 12.2-RC3 | 4         | 7.14%   |
| TrueNAS 12.2-p11 | 4         | 7.14%   |
| TrueNAS 12.2-p10 | 4         | 7.14%   |
| TrueNAS 13.1-p9  | 3         | 5.36%   |
| TrueNAS 13.1-p7  | 2         | 3.57%   |
| TrueNAS 13.1-p2  | 2         | 3.57%   |
| TrueNAS 13.1     | 2         | 3.57%   |
| TrueNAS 12.3-p7  | 1         | 1.79%   |
| TrueNAS 12.3-p2  | 1         | 1.79%   |
| TrueNAS 12.3-p1  | 1         | 1.79%   |
| TrueNAS 12.2-p3  | 1         | 1.79%   |
| TrueNAS 12.2-p14 | 1         | 1.79%   |
| TrueNAS 12.2     | 1         | 1.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TrueNAS | 51        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 47        | 92.16%  |
| helloDesktop | 3         | 5.88%   |
| TWM          | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 50        | 98.04%  |
| X11     | 1         | 1.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 51        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 49        | 96.08%  |
| C     | 2         | 3.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 29        | 56.86%  |
| EFI  | 22        | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 46        | 90.2%   |
| XXX     | 3         | 5.88%   |
| Unknown | 2         | 3.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 51        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Supermicro          | 12        | 23.53%  |
| Unknown             | 10        | 19.61%  |
| Gigabyte Technology | 6         | 11.76%  |
| Dell                | 6         | 11.76%  |
| ASUSTek Computer    | 5         | 9.8%    |
| ASRock              | 5         | 9.8%    |
| Hewlett-Packard     | 4         | 7.84%   |
| Lenovo              | 2         | 3.92%   |
| TYAN Computer       | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 10        | 19.61%  |
| Supermicro X10SLH-F/X10SLM+-F       | 2         | 3.92%   |
| Dell PowerEdge R720xd               | 2         | 3.92%   |
| TYAN S5512                          | 1         | 1.96%   |
| Supermicro X9SPV-F/LN4F             | 1         | 1.96%   |
| Supermicro X9SCL/X9SCM              | 1         | 1.96%   |
| Supermicro X9SCI/X9SCA              | 1         | 1.96%   |
| Supermicro X9DRD-7LN4F              | 1         | 1.96%   |
| Supermicro X8STi                    | 1         | 1.96%   |
| Supermicro X11DPi-N(T)              | 1         | 1.96%   |
| Supermicro X10SLM-F                 | 1         | 1.96%   |
| Supermicro X10SAE                   | 1         | 1.96%   |
| Supermicro SwyxExpress              | 1         | 1.96%   |
| Supermicro ReadyDATA 5200           | 1         | 1.96%   |
| Lenovo ThinkCentre M73 10AXS01800   | 1         | 1.96%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1         | 1.96%   |
| HP ProLiant ML150 G6                | 1         | 1.96%   |
| HP ProLiant ML10 v2                 | 1         | 1.96%   |
| HP ProLiant MicroServer Gen8        | 1         | 1.96%   |
| HP Compaq Elite 8300 SFF            | 1         | 1.96%   |
| Gigabyte H97-D3H                    | 1         | 1.96%   |
| Gigabyte H610M H DDR4               | 1         | 1.96%   |
| Gigabyte GA-A75-UD4H                | 1         | 1.96%   |
| Gigabyte B550I AORUS PRO AX         | 1         | 1.96%   |
| Gigabyte B450M DS3H                 | 1         | 1.96%   |
| Gigabyte 990FXA-UD3                 | 1         | 1.96%   |
| Dell PowerEdge T310                 | 1         | 1.96%   |
| Dell PowerEdge T110 II              | 1         | 1.96%   |
| Dell PowerEdge 2950                 | 1         | 1.96%   |
| Dell OptiPlex 790                   | 1         | 1.96%   |
| ASUS TUF Z270 MARK 2                | 1         | 1.96%   |
| ASUS P10S-I Series                  | 1         | 1.96%   |
| ASUS M5A99X EVO R2.0                | 1         | 1.96%   |
| ASUS M5A78L-M/USB3                  | 1         | 1.96%   |
| ASUS M5A78L-M PLUS/USB3             | 1         | 1.96%   |
| ASRock X570M Pro4                   | 1         | 1.96%   |
| ASRock N3150M                       | 1         | 1.96%   |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1         | 1.96%   |
| ASRock C2750D4I                     | 1         | 1.96%   |
| ASRock B560M Pro4/ac                | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 10        | 19.61%  |
| Dell PowerEdge                  | 5         | 9.8%    |
| HP ProLiant                     | 3         | 5.88%   |
| Supermicro X10SLH-F             | 2         | 3.92%   |
| ASUS M5A78L-M                   | 2         | 3.92%   |
| TYAN S5512                      | 1         | 1.96%   |
| Supermicro X9SPV-F              | 1         | 1.96%   |
| Supermicro X9SCL                | 1         | 1.96%   |
| Supermicro X9SCI                | 1         | 1.96%   |
| Supermicro X9DRD-7LN4F          | 1         | 1.96%   |
| Supermicro X8STi                | 1         | 1.96%   |
| Supermicro X11DPi-N(T)          | 1         | 1.96%   |
| Supermicro X10SLM-F             | 1         | 1.96%   |
| Supermicro X10SAE               | 1         | 1.96%   |
| Supermicro SwyxExpress          | 1         | 1.96%   |
| Supermicro ReadyDATA            | 1         | 1.96%   |
| Lenovo ThinkCentre              | 1         | 1.96%   |
| Lenovo 70AQ0009UX               | 1         | 1.96%   |
| HP Compaq                       | 1         | 1.96%   |
| Gigabyte H97-D3H                | 1         | 1.96%   |
| Gigabyte H610M                  | 1         | 1.96%   |
| Gigabyte GA-A75-UD4H            | 1         | 1.96%   |
| Gigabyte B550I                  | 1         | 1.96%   |
| Gigabyte B450M                  | 1         | 1.96%   |
| Gigabyte 990FXA-UD3             | 1         | 1.96%   |
| Dell OptiPlex                   | 1         | 1.96%   |
| ASUS TUF                        | 1         | 1.96%   |
| ASUS P10S-I                     | 1         | 1.96%   |
| ASUS M5A99X                     | 1         | 1.96%   |
| ASRock X570M                    | 1         | 1.96%   |
| ASRock N3150M                   | 1         | 1.96%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1         | 1.96%   |
| ASRock C2750D4I                 | 1         | 1.96%   |
| ASRock B560M                    | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 19.61%  |
| 2018    | 6         | 11.76%  |
| 2014    | 6         | 11.76%  |
| 2019    | 5         | 9.8%    |
| 2020    | 4         | 7.84%   |
| 2012    | 4         | 7.84%   |
| 2011    | 4         | 7.84%   |
| 2016    | 3         | 5.88%   |
| 2013    | 2         | 3.92%   |
| 2010    | 2         | 3.92%   |
| 2023    | 1         | 1.96%   |
| 2021    | 1         | 1.96%   |
| 2017    | 1         | 1.96%   |
| 2015    | 1         | 1.96%   |
| 2009    | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 40        | 78.43%  |
| Server  | 11        | 21.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 16        | 31.37%  |
| 16.01-24.0  | 14        | 27.45%  |
| 8.01-16.0   | 8         | 15.69%  |
| 24.01-32.0  | 6         | 11.76%  |
| 64.01-256.0 | 6         | 11.76%  |
| 4.01-8.0    | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 18        | 35.29%  |
| 1.01-2.0   | 12        | 23.53%  |
| 2.01-3.0   | 5         | 9.8%    |
| 0.01-0.5   | 4         | 7.84%   |
| 4.01-8.0   | 3         | 5.88%   |
| 24.01-32.0 | 3         | 5.88%   |
| 16.01-24.0 | 2         | 3.92%   |
| 8.01-16.0  | 2         | 3.92%   |
| 32.01-64.0 | 1         | 1.96%   |
| 3.01-4.0   | 1         | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 10        | 18.87%  |
| 3      | 7         | 13.21%  |
| 4      | 6         | 11.32%  |
| 9      | 5         | 9.43%   |
| 14     | 3         | 5.66%   |
| 17     | 2         | 3.77%   |
| 11     | 2         | 3.77%   |
| 7      | 2         | 3.77%   |
| 6      | 2         | 3.77%   |
| 5      | 2         | 3.77%   |
| 2      | 2         | 3.77%   |
| 1      | 2         | 3.77%   |
| 27     | 1         | 1.89%   |
| 21     | 1         | 1.89%   |
| 19     | 1         | 1.89%   |
| 16     | 1         | 1.89%   |
| 15     | 1         | 1.89%   |
| 12     | 1         | 1.89%   |
| 10     | 1         | 1.89%   |
| 8      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 88.68%  |
| Yes       | 6         | 11.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 96.08%  |
| Yes       | 2         | 3.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 96.08%  |
| Yes       | 2         | 3.92%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 21.57%  |
| Germany     | 7         | 13.73%  |
| Australia   | 5         | 9.8%    |
| France      | 4         | 7.84%   |
| Thailand    | 3         | 5.88%   |
| Romania     | 3         | 5.88%   |
| Greece      | 3         | 5.88%   |
| Switzerland | 2         | 3.92%   |
| Czechia     | 2         | 3.92%   |
| Canada      | 2         | 3.92%   |
| Brazil      | 2         | 3.92%   |
| Spain       | 1         | 1.96%   |
| Russia      | 1         | 1.96%   |
| Norway      | 1         | 1.96%   |
| Nicaragua   | 1         | 1.96%   |
| Estonia     | 1         | 1.96%   |
| Belgium     | 1         | 1.96%   |
| Austria     | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Melbourne         | 3         | 5.45%   |
| Springfield       | 2         | 3.64%   |
| Lüneburg         | 2         | 3.64%   |
| Huenfelden        | 2         | 3.64%   |
| Brno              | 2         | 3.64%   |
| Bangkok           | 2         | 3.64%   |
| Athens            | 2         | 3.64%   |
| Apahida           | 2         | 3.64%   |
| Yverdon-les-Bains | 1         | 1.82%   |
| Willisau          | 1         | 1.82%   |
| Tartu             | 1         | 1.82%   |
| Tamm              | 1         | 1.82%   |
| Sydney            | 1         | 1.82%   |
| St Petersburg     | 1         | 1.82%   |
| Skiptvet          | 1         | 1.82%   |
| SÃ£o Paulo      | 1         | 1.82%   |
| Raleigh           | 1         | 1.82%   |
| Perth             | 1         | 1.82%   |
| Perry Hall        | 1         | 1.82%   |
| Paris             | 1         | 1.82%   |
| Ougree            | 1         | 1.82%   |
| Northville        | 1         | 1.82%   |
| Managua           | 1         | 1.82%   |
| Ludwigsburg       | 1         | 1.82%   |
| Lubbock           | 1         | 1.82%   |
| Khlong Luang      | 1         | 1.82%   |
| Kennedale         | 1         | 1.82%   |
| JundiaГ­        | 1         | 1.82%   |
| Jundiaí          | 1         | 1.82%   |
| JundiaÃ­        | 1         | 1.82%   |
| JaraguÃ¡ do Sul | 1         | 1.82%   |
| Hendersonville    | 1         | 1.82%   |
| Genas             | 1         | 1.82%   |
| Gatineau          | 1         | 1.82%   |
| Galatista         | 1         | 1.82%   |
| Fontaine-le-Comte | 1         | 1.82%   |
| Fayetteville      | 1         | 1.82%   |
| Falkenstein       | 1         | 1.82%   |
| East Granby       | 1         | 1.82%   |
| Dresden           | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 112    | 19.23%  |
| WDC                 | 19        | 89     | 18.27%  |
| Samsung Electronics | 10        | 14     | 9.62%   |
| Hitachi             | 10        | 42     | 9.62%   |
| Toshiba             | 8         | 16     | 7.69%   |
| Intel               | 8         | 16     | 7.69%   |
| Crucial             | 6         | 8      | 5.77%   |
| Kingston            | 5         | 11     | 4.81%   |
| SanDisk             | 3         | 3      | 2.88%   |
| HPT                 | 2         | 31     | 1.92%   |
| HGST                | 2         | 13     | 1.92%   |
| Hewlett-Packard     | 2         | 8      | 1.92%   |
| WD MediaMax         | 1         | 3      | 0.96%   |
| Transcend           | 1         | 1      | 0.96%   |
| SPCC                | 1         | 1      | 0.96%   |
| PNY                 | 1         | 1      | 0.96%   |
| Patriot             | 1         | 2      | 0.96%   |
| Mushkin             | 1         | 1      | 0.96%   |
| China               | 1         | 1      | 0.96%   |
| Apacer              | 1         | 1      | 0.96%   |
| AMD                 | 1         | 2      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| WDC WD40EFRX-68N32N0 4TB        | 5         | 2.54%   |
| WDC WD30EFRX-68EUZN0 3TB        | 4         | 2.03%   |
| Samsung SSD 860 EVO 250GB       | 4         | 2.03%   |
| WDC WD40EFRX-68WT0N0 4TB        | 3         | 1.52%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3         | 1.52%   |
| WDC WD60EFRX-68MYMN1 6TB        | 2         | 1.02%   |
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 1.02%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2         | 1.02%   |
| WDC WD20EFRX-68AX9N0 2TB        | 2         | 1.02%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 1.02%   |
| Seagate ST4000DM000-1F2168 4TB  | 2         | 1.02%   |
| Seagate ST2000DM001-1ER164 2TB  | 2         | 1.02%   |
| Kingston SA400S37120G 120GB     | 2         | 1.02%   |
| Intel SSDSC2BB120G4 120GB       | 2         | 1.02%   |
| Intel SSDSA2CW080G3 80GB        | 2         | 1.02%   |
| HPT DISK 0_9 3TB                | 2         | 1.02%   |
| HPT DISK 0_8 3TB                | 2         | 1.02%   |
| HPT DISK 0_7 1TB                | 2         | 1.02%   |
| HPT DISK 0_6 1TB                | 2         | 1.02%   |
| HPT DISK 0_5 1TB                | 2         | 1.02%   |
| HPT DISK 0_4 1TB                | 2         | 1.02%   |
| HPT DISK 0_3 1TB                | 2         | 1.02%   |
| HPT DISK 0_2 1TB                | 2         | 1.02%   |
| HPT DISK 0_14 3TB               | 2         | 1.02%   |
| HPT DISK 0_13 2TB               | 2         | 1.02%   |
| HPT DISK 0_12 1TB               | 2         | 1.02%   |
| HPT DISK 0_11 1TB               | 2         | 1.02%   |
| HPT DISK 0_10 1TB               | 2         | 1.02%   |
| HPT DISK 0_1 1TB                | 2         | 1.02%   |
| HPT DISK 0_0 4TB                | 2         | 1.02%   |
| Hitachi HUA722020ALA331 2TB     | 2         | 1.02%   |
| Hitachi HDS723020BLA642 2TB     | 2         | 1.02%   |
| Hitachi HDS722020ALA330 2TB     | 2         | 1.02%   |
| Hitachi H7230AS60SUN3.0T 3TB    | 2         | 1.02%   |
| Crucial M4-CT064M4SSD2 64GB     | 2         | 1.02%   |
| WDC WD80EFAX-68LHPN0 8TB        | 1         | 0.51%   |
| WDC WD8004FRYZ-01VAEB0 8TB      | 1         | 0.51%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1         | 0.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1         | 0.51%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 112    | 31.25%  |
| WDC                 | 19        | 88     | 29.69%  |
| Hitachi             | 9         | 40     | 14.06%  |
| Toshiba             | 8         | 14     | 12.5%   |
| HPT                 | 2         | 31     | 3.13%   |
| HGST                | 2         | 13     | 3.13%   |
| Hewlett-Packard     | 2         | 8      | 3.13%   |
| WD MediaMax         | 1         | 3      | 1.56%   |
| Samsung Electronics | 1         | 3      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 22.22%  |
| Intel               | 6         | 14     | 16.67%  |
| Kingston            | 5         | 9      | 13.89%  |
| Crucial             | 4         | 6      | 11.11%  |
| SanDisk             | 3         | 3      | 8.33%   |
| WDC                 | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| Toshiba             | 1         | 2      | 2.78%   |
| SPCC                | 1         | 1      | 2.78%   |
| PNY                 | 1         | 1      | 2.78%   |
| Mushkin             | 1         | 1      | 2.78%   |
| Hitachi             | 1         | 2      | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| Apacer              | 1         | 1      | 2.78%   |
| AMD                 | 1         | 2      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 312    | 51.32%  |
| SSD  | 30        | 55     | 39.47%  |
| NVMe | 7         | 9      | 9.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 367    | 85.11%  |
| NVMe | 7         | 9      | 14.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 85     | 34.78%  |
| 1.01-2.0   | 15        | 57     | 16.3%   |
| 2.01-3.0   | 14        | 80     | 15.22%  |
| 3.01-4.0   | 11        | 61     | 11.96%  |
| 0.51-1.0   | 10        | 51     | 10.87%  |
| 4.01-10.0  | 7         | 29     | 7.61%   |
| 10.01-20.0 | 3         | 4      | 3.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 23.08%  |
| 101-250        | 11        | 21.15%  |
| 251-500        | 9         | 17.31%  |
| 51-100         | 6         | 11.54%  |
| 21-50          | 4         | 7.69%   |
| More than 3000 | 3         | 5.77%   |
| 501-1000       | 3         | 5.77%   |
| Unknown        | 3         | 5.77%   |
| 2001-3000      | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 46        | 90.2%   |
| Unknown | 3         | 5.88%   |
| 251-500 | 1         | 1.96%   |
| 21-50   | 1         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 5      | 6.9%    |
| Hitachi HDS723020BLA642 2TB     | 2         | 2      | 6.9%    |
| WDC WD60EFRX-68MYMN1 6TB        | 1         | 1      | 3.45%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1         | 1      | 3.45%   |
| WDC WD30PURX-64P6ZY0 3TB        | 1         | 1      | 3.45%   |
| WDC WD30EZRX-00MMMB0 3TB        | 1         | 2      | 3.45%   |
| WDC WD20EFRX-68AX9N0 2TB        | 1         | 1      | 3.45%   |
| WDC WD2000FYYZ 2TB              | 1         | 2      | 3.45%   |
| WDC WD10PURX-64E5EY0 1TB        | 1         | 1      | 3.45%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1         | 1      | 3.45%   |
| WD MediaMax WL2000GSA6454 2TB   | 1         | 3      | 3.45%   |
| Toshiba HDWD130 3TB             | 1         | 2      | 3.45%   |
| Seagate ST980310AS 80GB         | 1         | 1      | 3.45%   |
| Seagate ST9320325AS 320GB       | 1         | 1      | 3.45%   |
| Seagate ST4000DM000-1F2168 4TB  | 1         | 1      | 3.45%   |
| Seagate ST3320311CS 320GB       | 1         | 2      | 3.45%   |
| Seagate ST31500341AS 1.5TB      | 1         | 1      | 3.45%   |
| Seagate ST3000VN007-2E4166 3TB  | 1         | 1      | 3.45%   |
| Seagate ST3000NM0033-9ZM178 3TB | 1         | 7      | 3.45%   |
| Seagate ST2000NM0033-9ZM175 2TB | 1         | 1      | 3.45%   |
| Seagate ST2000DL003-9VT166 2TB  | 1         | 1      | 3.45%   |
| Seagate ST2000DL001-9VT156 2TB  | 1         | 1      | 3.45%   |
| Seagate ST1000VM002-1SD102 1TB  | 1         | 2      | 3.45%   |
| Seagate ST1000DM003-1CH162 1TB  | 1         | 1      | 3.45%   |
| Intel SSDSC2BA200G3T 200GB      | 1         | 1      | 3.45%   |
| Hitachi HTS725032A9A364 320GB   | 1         | 1      | 3.45%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 7         | 20     | 38.89%  |
| WDC         | 5         | 15     | 27.78%  |
| Hitachi     | 3         | 4      | 16.67%  |
| WD MediaMax | 1         | 3      | 5.56%   |
| Toshiba     | 1         | 2      | 5.56%   |
| Intel       | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 7         | 20     | 41.18%  |
| WDC         | 5         | 15     | 29.41%  |
| Hitachi     | 3         | 4      | 17.65%  |
| WD MediaMax | 1         | 3      | 5.88%   |
| Toshiba     | 1         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 44     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 41        | 295    | 73.21%  |
| Malfunc  | 12        | 45     | 21.43%  |
| Detected | 3         | 36     | 5.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 40.4%   |
| Broadcom / LSI              | 17        | 17.17%  |
| AMD                         | 10        | 10.1%   |
| Marvell Technology Group    | 9         | 9.09%   |
| ASMedia Technology          | 4         | 4.04%   |
| Silicon Image               | 2         | 2.02%   |
| Samsung Electronics         | 2         | 2.02%   |
| Micron/Crucial Technology   | 2         | 2.02%   |
| Kingston Technology Company | 2         | 2.02%   |
| JMicron Technology          | 2         | 2.02%   |
| HighPoint Technologies      | 2         | 2.02%   |
| Hewlett-Packard             | 2         | 2.02%   |
| Silicon Motion              | 1         | 1.01%   |
| QLogic                      | 1         | 1.01%   |
| MAXIO Technology (Hangzhou) | 1         | 1.01%   |
| Dell                        | 1         | 1.01%   |
| Areca Technology            | 1         | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 14        | 12.07%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 7.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 5.17%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 4         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.45%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 3         | 2.59%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 3         | 2.59%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 3         | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.72%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2         | 1.72%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 2         | 1.72%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.72%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.72%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 1.72%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 1.72%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 2         | 1.72%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 2         | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 1.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.72%   |
| HighPoint RocketRAID 2760 SAS Controller                                         | 2         | 1.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.86%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.86%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.86%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                      | 1         | 0.86%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.86%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 0.86%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 1         | 0.86%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                  | 1         | 0.86%   |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                             | 1         | 0.86%   |
| Intel SATA Controller [RAID Mode]                                                | 1         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.86%   |
| Intel PCIe Data Center SSD                                                       | 1         | 0.86%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.86%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 43        | 45.74%  |
| RAID | 15        | 15.96%  |
| SAS  | 11        | 11.7%   |
| NVMe | 10        | 10.64%  |
| IDE  | 10        | 10.64%  |
| SCSI | 5         | 5.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 80.39%  |
| AMD    | 10        | 19.61%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 3         | 5.88%   |
| Intel Xeon Silver 4108 CPU @ 1.80GHz   | 2         | 3.92%   |
| Intel Xeon CPU E5504 @ 2.00GHz         | 2         | 3.92%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 2         | 3.92%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2         | 3.92%   |
| Intel Atom CPU C2750 @ 2.40GHz         | 2         | 3.92%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2         | 3.92%   |
| Intel Xeon E-2224 CPU @ 3.40GHz        | 1         | 1.96%   |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1         | 1.96%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 1.96%   |
| Intel Xeon CPU E5506 @ 2.13GHz         | 1         | 1.96%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1         | 1.96%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 1         | 1.96%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz     | 1         | 1.96%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz    | 1         | 1.96%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz    | 1         | 1.96%   |
| Intel Xeon CPU D-1518 @ 2.20GHz        | 1         | 1.96%   |
| Intel Xeon CPU 5160 @ 3.00GHz          | 1         | 1.96%   |
| Intel Pentium CPU G860 @ 3.00GHz       | 1         | 1.96%   |
| Intel Core i7-3555LE CPU @ 2.50GHz     | 1         | 1.96%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1         | 1.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1         | 1.96%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1         | 1.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1         | 1.96%   |
| Intel Core i5-2500S CPU @ 2.70GH       | 1         | 1.96%   |
| Intel Core i3-4330 CPU @ 3.50GHz       | 1         | 1.96%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1         | 1.96%   |
| Intel Celeron G6900T                   | 1         | 1.96%   |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1         | 1.96%   |
| Intel Celeron CPU G1610T @ 2.30GHz     | 1         | 1.96%   |
| AMD Ryzen 7 1800X Eight-Core Processor | 1         | 1.96%   |
| AMD FX-8350 Eight-Core Processor       | 1         | 1.96%   |
| AMD FX-8320E Eight-Core Processor      | 1         | 1.96%   |
| AMD FX-8300 Eight-Core Processor       | 1         | 1.96%   |
| AMD FX-6300 Six-Core Processor         | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon        | 23        | 45.1%   |
| Intel Core i5     | 6         | 11.76%  |
| AMD FX            | 4         | 7.84%   |
| Intel Celeron     | 3         | 5.88%   |
| Intel Xeon Silver | 2         | 3.92%   |
| Intel Core i7     | 2         | 3.92%   |
| Intel Core i3     | 2         | 3.92%   |
| Intel Atom        | 2         | 3.92%   |
| AMD Ryzen 5       | 2         | 3.92%   |
| AMD A8            | 2         | 3.92%   |
| Intel Pentium     | 1         | 1.96%   |
| AMD Ryzen 7       | 1         | 1.96%   |
| AMD E1            | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 27        | 52.94%  |
| 8       | 8         | 15.69%  |
| 2       | 7         | 13.73%  |
| 16      | 5         | 9.8%    |
| 12      | 2         | 3.92%   |
| 6       | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 84.31%  |
| 2      | 8         | 15.69%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 35        | 68.63%  |
| 2       | 15        | 29.41%  |
| Unknown | 1         | 1.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 10        | 19.61%  |
| IvyBridge   | 7         | 13.73%  |
| SandyBridge | 6         | 11.76%  |
| Piledriver  | 5         | 9.8%    |
| Nehalem     | 5         | 9.8%    |
| KabyLake    | 4         | 7.84%   |
| Silvermont  | 3         | 5.88%   |
| Zen 2       | 2         | 3.92%   |
| Skylake     | 2         | 3.92%   |
| Zen         | 1         | 1.96%   |
| K10 Llano   | 1         | 1.96%   |
| Jaguar      | 1         | 1.96%   |
| Core        | 1         | 1.96%   |
| CometLake   | 1         | 1.96%   |
| Broadwell   | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Matrox Electronics Systems | 15        | 29.41%  |
| Intel                      | 13        | 25.49%  |
| ASPEED Technology          | 11        | 21.57%  |
| AMD                        | 9         | 17.65%  |
| Nvidia                     | 3         | 5.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 21.57%  |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 8         | 15.69%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 3.92%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 3.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 3.92%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 3.92%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 3.92%   |
| Intel HD Graphics 630                                                                    | 2         | 3.92%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 3.92%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 3.92%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.96%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.96%   |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                                | 1         | 1.96%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 1.96%   |
| AMD Oland GL [FirePro W2100]                                                             | 1         | 1.96%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.96%   |
| AMD ES1000                                                                               | 1         | 1.96%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Matrox     | 15        | 29.41%  |
| 1 x Intel      | 12        | 23.53%  |
| 1 x ASPEED     | 11        | 21.57%  |
| 1 x AMD        | 9         | 17.65%  |
| 1 x Nvidia     | 2         | 3.92%   |
| Other          | 1         | 1.96%   |
| Intel + Nvidia | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 50        | 98.04%  |
| Unknown | 1         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 100%    |

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
| 0     | 51        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 61.4%   |
| Realtek Semiconductor | 12        | 21.05%  |
| Broadcom              | 8         | 14.04%  |
| QLogic                | 1         | 1.75%   |
| Aquantia              | 1         | 1.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 10        | 12.99%  |
| Intel I210 Gigabit Network Connection                                          | 8         | 10.39%  |
| Intel I350 Gigabit Network Connection                                          | 7         | 9.09%   |
| Intel 82574L Gigabit Network Connection                                        | 6         | 7.79%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 6.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 4         | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.19%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 3         | 3.9%    |
| Intel Ethernet Connection X722 for 1GbE                                        | 2         | 2.6%    |
| Intel Ethernet Connection I217-V                                               | 2         | 2.6%    |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 2.6%    |
| Intel 82576 Gigabit Network Connection                                         | 2         | 2.6%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 2         | 2.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 1.3%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.3%    |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 1.3%    |
| Intel Wi-Fi 6 AX200                                                            | 1         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 1.3%    |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.3%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 1.3%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1         | 1.3%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 1.3%    |
| Intel 82580 Gigabit Network Connection                                         | 1         | 1.3%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 1.3%    |
| Intel 82571EB Gigabit Ethernet Controller                                      | 1         | 1.3%    |
| Intel 82541PI Gigabit Ethernet Controller                                      | 1         | 1.3%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 1         | 1.3%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                 | 1         | 1.3%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 1.3%    |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                        | 1         | 1.3%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.3%    |

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
| Intel                 | 34        | 60.71%  |
| Realtek Semiconductor | 12        | 21.43%  |
| Broadcom              | 8         | 14.29%  |
| QLogic                | 1         | 1.79%   |
| Aquantia              | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 10        | 13.33%  |
| Intel I210 Gigabit Network Connection                                          | 8         | 10.67%  |
| Intel I350 Gigabit Network Connection                                          | 7         | 9.33%   |
| Intel 82574L Gigabit Network Connection                                        | 6         | 8%      |
| Intel Ethernet Connection I217-LM                                              | 5         | 6.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 4         | 5.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 3         | 4%      |
| Intel Ethernet Connection X722 for 1GbE                                        | 2         | 2.67%   |
| Intel Ethernet Connection I217-V                                               | 2         | 2.67%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 2.67%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 2.67%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 2         | 2.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.33%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.33%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 1.33%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1         | 1.33%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 1.33%   |
| Intel 82580 Gigabit Network Connection                                         | 1         | 1.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 1.33%   |
| Intel 82571EB Gigabit Ethernet Controller                                      | 1         | 1.33%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 1         | 1.33%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 1         | 1.33%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                 | 1         | 1.33%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 1.33%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 1.33%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                        | 1         | 1.33%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 96.23%  |
| WiFi     | 2         | 3.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 100%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 15        | 29.41%  |
| 1     | 15        | 29.41%  |
| 4     | 10        | 19.61%  |
| 6     | 4         | 7.84%   |
| 5     | 4         | 7.84%   |
| 3     | 3         | 5.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

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
| AMD    | 7         | 50%     |
| Intel  | 5         | 35.71%  |
| Nvidia | 2         | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 14.29%  |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 14.29%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 9.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 9.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 9.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 9.52%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1         | 4.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1         | 4.76%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 4.76%   |
| AMD FCH Azalia Controller                                                         | 1         | 4.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 4.76%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 23.53%  |
| Kingston            | 9         | 17.65%  |
| Unknown             | 6         | 11.76%  |
| SK hynix            | 5         | 9.8%    |
| Micron Technology   | 5         | 9.8%    |
| Crucial             | 4         | 7.84%   |
| Corsair             | 3         | 5.88%   |
| Transcend           | 2         | 3.92%   |
| Toshiba             | 1         | 1.96%   |
| Team                | 1         | 1.96%   |
| PNY                 | 1         | 1.96%   |
| Patriot             | 1         | 1.96%   |
| Hewlett-Packard     | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s            | 2         | 3.57%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3                  | 2         | 3.57%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.79%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                | 1         | 1.79%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                      | 1         | 1.79%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                     | 1         | 1.79%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1         | 1.79%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 1.79%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 1.79%   |
| Toshiba RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s        | 1         | 1.79%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s              | 1         | 1.79%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 1.79%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 1.79%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 1.79%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.79%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s        | 1         | 1.79%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.79%   |
| Samsung RAM M395T5750EZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.79%   |
| Samsung RAM M395T5750CZ4-CE61 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.79%   |
| Samsung RAM M393B2K70CM0-CF8 16384MB DIMM DDR3 1066MT/s     | 1         | 1.79%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s     | 1         | 1.79%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s      | 1         | 1.79%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.79%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.79%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s      | 1         | 1.79%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 2133MT/s         | 1         | 1.79%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s         | 1         | 1.79%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s         | 1         | 1.79%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s      | 1         | 1.79%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s        | 1         | 1.79%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s      | 1         | 1.79%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1400MT/s             | 1         | 1.79%   |
| Kingston RAM 99U5403-195.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.79%   |
| Kingston RAM 99U5403-083.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.79%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s       | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 29        | 70.73%  |
| DDR4    | 8         | 19.51%  |
| Unknown | 3         | 7.32%   |
| DDR2    | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 39        | 95.12%  |
| SODIMM  | 1         | 2.44%   |
| FB-DIMM | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 64%     |
| 4096  | 8         | 16%     |
| 16384 | 6         | 12%     |
| 2048  | 4         | 8%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 16        | 36.36%  |
| 1333  | 11        | 25%     |
| 1066  | 3         | 6.82%   |
| 3200  | 2         | 4.55%   |
| 3000  | 2         | 4.55%   |
| 2133  | 2         | 4.55%   |
| 800   | 2         | 4.55%   |
| 667   | 2         | 4.55%   |
| 2667  | 1         | 2.27%   |
| 2666  | 1         | 2.27%   |
| 2400  | 1         | 2.27%   |
| 1400  | 1         | 2.27%   |

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
| 0     | 26        | 50.98%  |
| 2     | 11        | 21.57%  |
| 1     | 7         | 13.73%  |
| 3     | 4         | 7.84%   |
| 4     | 2         | 3.92%   |
| 5     | 1         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 18        | 47.37%  |
| Sound                    | 12        | 31.58%  |
| Firewire controller      | 3         | 7.89%   |
| Net/wireless             | 2         | 5.26%   |
| Bluetooth                | 2         | 5.26%   |
| Storage/raid             | 1         | 2.63%   |

