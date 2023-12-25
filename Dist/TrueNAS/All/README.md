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

Total: 68

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| TrueNAS 12.2-p2  | 9         | 16.36%  |
| TrueNAS 12.2-p6  | 8         | 14.55%  |
| TrueNAS 12.2-p9  | 6         | 10.91%  |
| TrueNAS 12.2-p12 | 6         | 10.91%  |
| TrueNAS 12.2-RC3 | 4         | 7.27%   |
| TrueNAS 12.2-p11 | 4         | 7.27%   |
| TrueNAS 12.2-p10 | 4         | 7.27%   |
| TrueNAS 13.1-p9  | 2         | 3.64%   |
| TrueNAS 13.1-p7  | 2         | 3.64%   |
| TrueNAS 13.1-p2  | 2         | 3.64%   |
| TrueNAS 13.1     | 2         | 3.64%   |
| TrueNAS 12.3-p7  | 1         | 1.82%   |
| TrueNAS 12.3-p2  | 1         | 1.82%   |
| TrueNAS 12.3-p1  | 1         | 1.82%   |
| TrueNAS 12.2-p3  | 1         | 1.82%   |
| TrueNAS 12.2-p14 | 1         | 1.82%   |
| TrueNAS 12.2     | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TrueNAS | 50        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 46        | 92%     |
| helloDesktop | 3         | 6%      |
| TWM          | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 49        | 98%     |
| X11     | 1         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 50        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 48        | 96%     |
| C     | 2         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 28        | 56%     |
| EFI  | 22        | 44%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 45        | 90%     |
| XXX     | 3         | 6%      |
| Unknown | 2         | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 50        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Supermicro          | 11        | 22%     |
| Unknown             | 10        | 20%     |
| Gigabyte Technology | 6         | 12%     |
| Dell                | 6         | 12%     |
| ASUSTek Computer    | 5         | 10%     |
| ASRock              | 5         | 10%     |
| Hewlett-Packard     | 4         | 8%      |
| Lenovo              | 2         | 4%      |
| TYAN Computer       | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 10        | 20%     |
| Supermicro X10SLH-F/X10SLM+-F       | 2         | 4%      |
| Dell PowerEdge R720xd               | 2         | 4%      |
| TYAN S5512                          | 1         | 2%      |
| Supermicro X9SPV-F/LN4F             | 1         | 2%      |
| Supermicro X9SCL/X9SCM              | 1         | 2%      |
| Supermicro X9SCI/X9SCA              | 1         | 2%      |
| Supermicro X9DRD-7LN4F              | 1         | 2%      |
| Supermicro X8STi                    | 1         | 2%      |
| Supermicro X11DPi-N(T)              | 1         | 2%      |
| Supermicro X10SLM-F                 | 1         | 2%      |
| Supermicro X10SAE                   | 1         | 2%      |
| Supermicro ReadyDATA 5200           | 1         | 2%      |
| Lenovo ThinkCentre M73 10AXS01800   | 1         | 2%      |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1         | 2%      |
| HP ProLiant ML150 G6                | 1         | 2%      |
| HP ProLiant ML10 v2                 | 1         | 2%      |
| HP ProLiant MicroServer Gen8        | 1         | 2%      |
| HP Compaq Elite 8300 SFF            | 1         | 2%      |
| Gigabyte H97-D3H                    | 1         | 2%      |
| Gigabyte H610M H DDR4               | 1         | 2%      |
| Gigabyte GA-A75-UD4H                | 1         | 2%      |
| Gigabyte B550I AORUS PRO AX         | 1         | 2%      |
| Gigabyte B450M DS3H                 | 1         | 2%      |
| Gigabyte 990FXA-UD3                 | 1         | 2%      |
| Dell PowerEdge T310                 | 1         | 2%      |
| Dell PowerEdge T110 II              | 1         | 2%      |
| Dell PowerEdge 2950                 | 1         | 2%      |
| Dell OptiPlex 790                   | 1         | 2%      |
| ASUS TUF Z270 MARK 2                | 1         | 2%      |
| ASUS P10S-I Series                  | 1         | 2%      |
| ASUS M5A99X EVO R2.0                | 1         | 2%      |
| ASUS M5A78L-M/USB3                  | 1         | 2%      |
| ASUS M5A78L-M PLUS/USB3             | 1         | 2%      |
| ASRock X570M Pro4                   | 1         | 2%      |
| ASRock N3150M                       | 1         | 2%      |
| ASRock FREENAS-MINI-XL-24TB-IXN     | 1         | 2%      |
| ASRock C2750D4I                     | 1         | 2%      |
| ASRock B560M Pro4/ac                | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 10        | 20%     |
| Dell PowerEdge                  | 5         | 10%     |
| HP ProLiant                     | 3         | 6%      |
| Supermicro X10SLH-F             | 2         | 4%      |
| ASUS M5A78L-M                   | 2         | 4%      |
| TYAN S5512                      | 1         | 2%      |
| Supermicro X9SPV-F              | 1         | 2%      |
| Supermicro X9SCL                | 1         | 2%      |
| Supermicro X9SCI                | 1         | 2%      |
| Supermicro X9DRD-7LN4F          | 1         | 2%      |
| Supermicro X8STi                | 1         | 2%      |
| Supermicro X11DPi-N(T)          | 1         | 2%      |
| Supermicro X10SLM-F             | 1         | 2%      |
| Supermicro X10SAE               | 1         | 2%      |
| Supermicro ReadyDATA            | 1         | 2%      |
| Lenovo ThinkCentre              | 1         | 2%      |
| Lenovo 70AQ0009UX               | 1         | 2%      |
| HP Compaq                       | 1         | 2%      |
| Gigabyte H97-D3H                | 1         | 2%      |
| Gigabyte H610M                  | 1         | 2%      |
| Gigabyte GA-A75-UD4H            | 1         | 2%      |
| Gigabyte B550I                  | 1         | 2%      |
| Gigabyte B450M                  | 1         | 2%      |
| Gigabyte 990FXA-UD3             | 1         | 2%      |
| Dell OptiPlex                   | 1         | 2%      |
| ASUS TUF                        | 1         | 2%      |
| ASUS P10S-I                     | 1         | 2%      |
| ASUS M5A99X                     | 1         | 2%      |
| ASRock X570M                    | 1         | 2%      |
| ASRock N3150M                   | 1         | 2%      |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1         | 2%      |
| ASRock C2750D4I                 | 1         | 2%      |
| ASRock B560M                    | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 20%     |
| 2018    | 6         | 12%     |
| 2014    | 6         | 12%     |
| 2019    | 5         | 10%     |
| 2016    | 4         | 8%      |
| 2012    | 4         | 8%      |
| 2011    | 4         | 8%      |
| 2020    | 3         | 6%      |
| 2013    | 2         | 4%      |
| 2010    | 2         | 4%      |
| 2023    | 1         | 2%      |
| 2021    | 1         | 2%      |
| 2017    | 1         | 2%      |
| 2009    | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 40        | 80%     |
| Server  | 10        | 20%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 16        | 32%     |
| 16.01-24.0  | 13        | 26%     |
| 8.01-16.0   | 8         | 16%     |
| 24.01-32.0  | 6         | 12%     |
| 64.01-256.0 | 6         | 12%     |
| 4.01-8.0    | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 17        | 34%     |
| 1.01-2.0   | 12        | 24%     |
| 2.01-3.0   | 5         | 10%     |
| 0.01-0.5   | 4         | 8%      |
| 4.01-8.0   | 3         | 6%      |
| 24.01-32.0 | 3         | 6%      |
| 16.01-24.0 | 2         | 4%      |
| 8.01-16.0  | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |
| 3.01-4.0   | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 10        | 19.23%  |
| 3      | 7         | 13.46%  |
| 4      | 6         | 11.54%  |
| 9      | 4         | 7.69%   |
| 14     | 3         | 5.77%   |
| 17     | 2         | 3.85%   |
| 11     | 2         | 3.85%   |
| 7      | 2         | 3.85%   |
| 6      | 2         | 3.85%   |
| 5      | 2         | 3.85%   |
| 2      | 2         | 3.85%   |
| 1      | 2         | 3.85%   |
| 27     | 1         | 1.92%   |
| 21     | 1         | 1.92%   |
| 19     | 1         | 1.92%   |
| 16     | 1         | 1.92%   |
| 15     | 1         | 1.92%   |
| 12     | 1         | 1.92%   |
| 10     | 1         | 1.92%   |
| 8      | 1         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 88.46%  |
| Yes       | 6         | 11.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 96%     |
| Yes       | 2         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 96%     |
| Yes       | 2         | 4%      |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 11        | 22%     |
| Germany     | 6         | 12%     |
| Australia   | 5         | 10%     |
| France      | 4         | 8%      |
| Thailand    | 3         | 6%      |
| Romania     | 3         | 6%      |
| Greece      | 3         | 6%      |
| Switzerland | 2         | 4%      |
| Czechia     | 2         | 4%      |
| Canada      | 2         | 4%      |
| Brazil      | 2         | 4%      |
| Spain       | 1         | 2%      |
| Russia      | 1         | 2%      |
| Norway      | 1         | 2%      |
| Nicaragua   | 1         | 2%      |
| Estonia     | 1         | 2%      |
| Belgium     | 1         | 2%      |
| Austria     | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Melbourne         | 3         | 5.56%   |
| Springfield       | 2         | 3.7%    |
| Lüneburg         | 2         | 3.7%    |
| Brno              | 2         | 3.7%    |
| Bangkok           | 2         | 3.7%    |
| Athens            | 2         | 3.7%    |
| Apahida           | 2         | 3.7%    |
| Yverdon-les-Bains | 1         | 1.85%   |
| Willisau          | 1         | 1.85%   |
| Tartu             | 1         | 1.85%   |
| Tamm              | 1         | 1.85%   |
| Sydney            | 1         | 1.85%   |
| St Petersburg     | 1         | 1.85%   |
| Skiptvet          | 1         | 1.85%   |
| SÃ£o Paulo      | 1         | 1.85%   |
| Raleigh           | 1         | 1.85%   |
| Perth             | 1         | 1.85%   |
| Perry Hall        | 1         | 1.85%   |
| Paris             | 1         | 1.85%   |
| Ougree            | 1         | 1.85%   |
| Northville        | 1         | 1.85%   |
| Managua           | 1         | 1.85%   |
| Ludwigsburg       | 1         | 1.85%   |
| Lubbock           | 1         | 1.85%   |
| Khlong Luang      | 1         | 1.85%   |
| Kennedale         | 1         | 1.85%   |
| JundiaГ­        | 1         | 1.85%   |
| Jundiaí          | 1         | 1.85%   |
| JundiaÃ­        | 1         | 1.85%   |
| JaraguÃ¡ do Sul | 1         | 1.85%   |
| Huenfelden        | 1         | 1.85%   |
| Hendersonville    | 1         | 1.85%   |
| Genas             | 1         | 1.85%   |
| Gatineau          | 1         | 1.85%   |
| Galatista         | 1         | 1.85%   |
| Fontaine-le-Comte | 1         | 1.85%   |
| Fayetteville      | 1         | 1.85%   |
| Falkenstein       | 1         | 1.85%   |
| East Granby       | 1         | 1.85%   |
| Dresden           | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 112    | 19.61%  |
| WDC                 | 19        | 89     | 18.63%  |
| Samsung Electronics | 10        | 14     | 9.8%    |
| Hitachi             | 9         | 34     | 8.82%   |
| Toshiba             | 8         | 16     | 7.84%   |
| Intel               | 7         | 15     | 6.86%   |
| Crucial             | 6         | 8      | 5.88%   |
| Kingston            | 5         | 11     | 4.9%    |
| SanDisk             | 3         | 3      | 2.94%   |
| HPT                 | 2         | 31     | 1.96%   |
| HGST                | 2         | 13     | 1.96%   |
| Hewlett-Packard     | 2         | 8      | 1.96%   |
| WD MediaMax         | 1         | 3      | 0.98%   |
| Transcend           | 1         | 1      | 0.98%   |
| SPCC                | 1         | 1      | 0.98%   |
| PNY                 | 1         | 1      | 0.98%   |
| Patriot             | 1         | 2      | 0.98%   |
| Mushkin             | 1         | 1      | 0.98%   |
| China               | 1         | 1      | 0.98%   |
| Apacer              | 1         | 1      | 0.98%   |
| AMD                 | 1         | 2      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| WDC WD40EFRX-68N32N0 4TB        | 5         | 2.56%   |
| WDC WD30EFRX-68EUZN0 3TB        | 4         | 2.05%   |
| Samsung SSD 860 EVO 250GB       | 4         | 2.05%   |
| WDC WD40EFRX-68WT0N0 4TB        | 3         | 1.54%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3         | 1.54%   |
| WDC WD60EFRX-68MYMN1 6TB        | 2         | 1.03%   |
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 1.03%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2         | 1.03%   |
| WDC WD20EFRX-68AX9N0 2TB        | 2         | 1.03%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 1.03%   |
| Seagate ST4000DM000-1F2168 4TB  | 2         | 1.03%   |
| Seagate ST2000DM001-1ER164 2TB  | 2         | 1.03%   |
| Kingston SA400S37120G 120GB     | 2         | 1.03%   |
| Intel SSDSC2BB120G4 120GB       | 2         | 1.03%   |
| HPT DISK 0_9 3TB                | 2         | 1.03%   |
| HPT DISK 0_8 3TB                | 2         | 1.03%   |
| HPT DISK 0_7 1TB                | 2         | 1.03%   |
| HPT DISK 0_6 1TB                | 2         | 1.03%   |
| HPT DISK 0_5 1TB                | 2         | 1.03%   |
| HPT DISK 0_4 1TB                | 2         | 1.03%   |
| HPT DISK 0_3 1TB                | 2         | 1.03%   |
| HPT DISK 0_2 1TB                | 2         | 1.03%   |
| HPT DISK 0_14 3TB               | 2         | 1.03%   |
| HPT DISK 0_13 2TB               | 2         | 1.03%   |
| HPT DISK 0_12 1TB               | 2         | 1.03%   |
| HPT DISK 0_11 1TB               | 2         | 1.03%   |
| HPT DISK 0_10 1TB               | 2         | 1.03%   |
| HPT DISK 0_1 1TB                | 2         | 1.03%   |
| HPT DISK 0_0 4TB                | 2         | 1.03%   |
| Hitachi HUA722020ALA331 2TB     | 2         | 1.03%   |
| Hitachi HDS723020BLA642 2TB     | 2         | 1.03%   |
| Hitachi HDS722020ALA330 2TB     | 2         | 1.03%   |
| Crucial M4-CT064M4SSD2 64GB     | 2         | 1.03%   |
| WDC WD80EFAX-68LHPN0 8TB        | 1         | 0.51%   |
| WDC WD8004FRYZ-01VAEB0 8TB      | 1         | 0.51%   |
| WDC WD5000LPLX-08ZNTT0 500GB    | 1         | 0.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 1         | 0.51%   |
| WDC WD5000AAKX-00U6AA0 500GB    | 1         | 0.51%   |
| WDC WD4003FFBX-68MU3N0 4TB      | 1         | 0.51%   |
| WDC WD30PURX-64P6ZY0 3TB        | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 112    | 31.75%  |
| WDC                 | 19        | 88     | 30.16%  |
| Toshiba             | 8         | 14     | 12.7%   |
| Hitachi             | 8         | 32     | 12.7%   |
| HPT                 | 2         | 31     | 3.17%   |
| HGST                | 2         | 13     | 3.17%   |
| Hewlett-Packard     | 2         | 8      | 3.17%   |
| WD MediaMax         | 1         | 3      | 1.59%   |
| Samsung Electronics | 1         | 3      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 22.86%  |
| Kingston            | 5         | 9      | 14.29%  |
| Intel               | 5         | 13     | 14.29%  |
| Crucial             | 4         | 6      | 11.43%  |
| SanDisk             | 3         | 3      | 8.57%   |
| WDC                 | 1         | 1      | 2.86%   |
| Transcend           | 1         | 1      | 2.86%   |
| Toshiba             | 1         | 2      | 2.86%   |
| SPCC                | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Mushkin             | 1         | 1      | 2.86%   |
| Hitachi             | 1         | 2      | 2.86%   |
| China               | 1         | 1      | 2.86%   |
| Apacer              | 1         | 1      | 2.86%   |
| AMD                 | 1         | 2      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 304    | 51.35%  |
| SSD  | 29        | 54     | 39.19%  |
| NVMe | 7         | 9      | 9.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 358    | 84.78%  |
| NVMe | 7         | 9      | 15.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 79     | 34.44%  |
| 1.01-2.0   | 15        | 57     | 16.67%  |
| 2.01-3.0   | 13        | 72     | 14.44%  |
| 3.01-4.0   | 11        | 61     | 12.22%  |
| 0.51-1.0   | 10        | 56     | 11.11%  |
| 4.01-10.0  | 7         | 29     | 7.78%   |
| 10.01-20.0 | 3         | 4      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 23.53%  |
| 101-250        | 11        | 21.57%  |
| 251-500        | 9         | 17.65%  |
| 51-100         | 5         | 9.8%    |
| 21-50          | 4         | 7.84%   |
| More than 3000 | 3         | 5.88%   |
| 501-1000       | 3         | 5.88%   |
| Unknown        | 3         | 5.88%   |
| 2001-3000      | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 45        | 90%     |
| Unknown | 3         | 6%      |
| 251-500 | 1         | 2%      |
| 21-50   | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 40        | 286    | 72.73%  |
| Malfunc  | 12        | 45     | 21.82%  |
| Detected | 3         | 36     | 5.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 40.21%  |
| Broadcom / LSI              | 16        | 16.49%  |
| AMD                         | 10        | 10.31%  |
| Marvell Technology Group    | 9         | 9.28%   |
| ASMedia Technology          | 4         | 4.12%   |
| Silicon Image               | 2         | 2.06%   |
| Samsung Electronics         | 2         | 2.06%   |
| Micron/Crucial Technology   | 2         | 2.06%   |
| Kingston Technology Company | 2         | 2.06%   |
| JMicron Technology          | 2         | 2.06%   |
| HighPoint Technologies      | 2         | 2.06%   |
| Hewlett-Packard             | 2         | 2.06%   |
| Silicon Motion              | 1         | 1.03%   |
| QLogic                      | 1         | 1.03%   |
| MAXIO Technology (Hangzhou) | 1         | 1.03%   |
| Dell                        | 1         | 1.03%   |
| Areca Technology            | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 13        | 11.4%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 5.26%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 4         | 3.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 3.51%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 3         | 2.63%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 3         | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.75%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 2         | 1.75%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                         | 2         | 1.75%   |
| JMicron JMB58x AHCI SATA controller                                              | 2         | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.75%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 1.75%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 1.75%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 2         | 1.75%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 2         | 1.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 1.75%   |
| HighPoint RocketRAID 2760 SAS Controller                                         | 2         | 1.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.88%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1         | 0.88%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.88%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                      | 1         | 0.88%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 0.88%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 1         | 0.88%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                  | 1         | 0.88%   |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                             | 1         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.88%   |
| Intel PCIe Data Center SSD                                                       | 1         | 0.88%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.88%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.88%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 42        | 45.65%  |
| RAID | 15        | 16.3%   |
| SAS  | 11        | 11.96%  |
| NVMe | 10        | 10.87%  |
| IDE  | 10        | 10.87%  |
| SCSI | 4         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 80%     |
| AMD    | 10        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon Silver 4108 CPU @ 1.80GHz   | 2         | 4%      |
| Intel Xeon CPU E5504 @ 2.00GHz         | 2         | 4%      |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 2         | 4%      |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 2         | 4%      |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2         | 4%      |
| Intel Atom CPU C2750 @ 2.40GHz         | 2         | 4%      |
| AMD Ryzen 5 3600 6-Core Processor      | 2         | 4%      |
| Intel Xeon E-2224 CPU @ 3.40GHz        | 1         | 2%      |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1         | 2%      |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 2%      |
| Intel Xeon CPU E5506 @ 2.13GHz         | 1         | 2%      |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1         | 2%      |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 1         | 2%      |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz     | 1         | 2%      |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz    | 1         | 2%      |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz    | 1         | 2%      |
| Intel Xeon CPU D-1518 @ 2.20GHz        | 1         | 2%      |
| Intel Xeon CPU 5160 @ 3.00GHz          | 1         | 2%      |
| Intel Pentium CPU G860 @ 3.00GHz       | 1         | 2%      |
| Intel Core i7-3555LE CPU @ 2.50GHz     | 1         | 2%      |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1         | 2%      |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1         | 2%      |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1         | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1         | 2%      |
| Intel Core i5-2500S CPU @ 2.70GH       | 1         | 2%      |
| Intel Core i3-4330 CPU @ 3.50GHz       | 1         | 2%      |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1         | 2%      |
| Intel Celeron G6900T                   | 1         | 2%      |
| Intel Celeron CPU N3150 @ 1.60GHz      | 1         | 2%      |
| Intel Celeron CPU G1610T @ 2.30GHz     | 1         | 2%      |
| AMD Ryzen 7 1800X Eight-Core Processor | 1         | 2%      |
| AMD FX-8350 Eight-Core Processor       | 1         | 2%      |
| AMD FX-8320E Eight-Core Processor      | 1         | 2%      |
| AMD FX-8300 Eight-Core Processor       | 1         | 2%      |
| AMD FX-6300 Six-Core Processor         | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon        | 22        | 44%     |
| Intel Core i5     | 6         | 12%     |
| AMD FX            | 4         | 8%      |
| Intel Celeron     | 3         | 6%      |
| Intel Xeon Silver | 2         | 4%      |
| Intel Core i7     | 2         | 4%      |
| Intel Core i3     | 2         | 4%      |
| Intel Atom        | 2         | 4%      |
| AMD Ryzen 5       | 2         | 4%      |
| AMD A8            | 2         | 4%      |
| Intel Pentium     | 1         | 2%      |
| AMD Ryzen 7       | 1         | 2%      |
| AMD E1            | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 26        | 52%     |
| 8       | 8         | 16%     |
| 2       | 7         | 14%     |
| 16      | 5         | 10%     |
| 12      | 2         | 4%      |
| 6       | 1         | 2%      |
| Unknown | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 84%     |
| 2      | 8         | 16%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 34        | 68%     |
| 2       | 15        | 30%     |
| Unknown | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 9         | 18%     |
| IvyBridge   | 7         | 14%     |
| SandyBridge | 6         | 12%     |
| Piledriver  | 5         | 10%     |
| Nehalem     | 5         | 10%     |
| KabyLake    | 4         | 8%      |
| Silvermont  | 3         | 6%      |
| Zen 2       | 2         | 4%      |
| Skylake     | 2         | 4%      |
| Zen         | 1         | 2%      |
| K10 Llano   | 1         | 2%      |
| Jaguar      | 1         | 2%      |
| Core        | 1         | 2%      |
| CometLake   | 1         | 2%      |
| Broadwell   | 1         | 2%      |
| Unknown     | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Matrox Electronics Systems | 15        | 30%     |
| Intel                      | 13        | 26%     |
| ASPEED Technology          | 10        | 20%     |
| AMD                        | 9         | 18%     |
| Nvidia                     | 3         | 6%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 10        | 20%     |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 8         | 16%     |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 6%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 4%      |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 4%      |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 4%      |
| Matrox Electronics Systems G200eR2                                                       | 2         | 4%      |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 4%      |
| Intel HD Graphics 630                                                                    | 2         | 4%      |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 4%      |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 4%      |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 2%      |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2%      |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                                | 1         | 2%      |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 2%      |
| AMD Oland GL [FirePro W2100]                                                             | 1         | 2%      |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 2%      |
| AMD ES1000                                                                               | 1         | 2%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Matrox     | 15        | 30%     |
| 1 x Intel      | 12        | 24%     |
| 1 x ASPEED     | 10        | 20%     |
| 1 x AMD        | 9         | 18%     |
| 1 x Nvidia     | 2         | 4%      |
| Other          | 1         | 2%      |
| Intel + Nvidia | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 49        | 98%     |
| Unknown | 1         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 100%    |

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
| 0     | 50        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 60.71%  |
| Realtek Semiconductor | 12        | 21.43%  |
| Broadcom              | 8         | 14.29%  |
| QLogic                | 1         | 1.79%   |
| Aquantia              | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 13.51%  |
| Intel I350 Gigabit Network Connection                                         | 7         | 9.46%   |
| Intel I210 Gigabit Network Connection                                         | 7         | 9.46%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 8.11%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 5.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 4.05%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 4.05%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 2.7%    |
| Intel Ethernet Connection I217-V                                              | 2         | 2.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 2.7%    |
| Intel 82576 Gigabit Network Connection                                        | 2         | 2.7%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 2.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.35%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.35%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1         | 1.35%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.35%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.35%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.35%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.35%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.35%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.35%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.35%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.35%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.35%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.35%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.35%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.35%   |

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
| Intel                 | 33        | 60%     |
| Realtek Semiconductor | 12        | 21.82%  |
| Broadcom              | 8         | 14.55%  |
| QLogic                | 1         | 1.82%   |
| Aquantia              | 1         | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 10        | 13.89%  |
| Intel I350 Gigabit Network Connection                                         | 7         | 9.72%   |
| Intel I210 Gigabit Network Connection                                         | 7         | 9.72%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 8.33%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 5.56%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 4.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3         | 4.17%   |
| Intel Ethernet Connection X722 for 1GbE                                       | 2         | 2.78%   |
| Intel Ethernet Connection I217-V                                              | 2         | 2.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 2.78%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 2.78%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 2.78%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 1.39%   |
| QLogic cLOM8214 1/10GbE Controller                                            | 1         | 1.39%   |
| Intel I211 Gigabit Network Connection                                         | 1         | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 1.39%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 1         | 1.39%   |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 1.39%   |
| Intel 82580 Gigabit Network Connection                                        | 1         | 1.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.39%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 1.39%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1         | 1.39%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 1         | 1.39%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 1.39%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 1.39%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1         | 1.39%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.39%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 96.15%  |
| WiFi     | 2         | 3.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 15        | 30%     |
| 1     | 15        | 30%     |
| 4     | 9         | 18%     |
| 6     | 4         | 8%      |
| 5     | 4         | 8%      |
| 3     | 3         | 6%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 100%    |

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
| AMD    | 7         | 50%     |
| Intel  | 5         | 35.71%  |
| Nvidia | 2         | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


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

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 24%     |
| Kingston            | 9         | 18%     |
| Unknown             | 6         | 12%     |
| SK hynix            | 5         | 10%     |
| Micron Technology   | 5         | 10%     |
| Crucial             | 4         | 8%      |
| Corsair             | 3         | 6%      |
| Transcend           | 1         | 2%      |
| Toshiba             | 1         | 2%      |
| Team                | 1         | 2%      |
| PNY                 | 1         | 2%      |
| Patriot             | 1         | 2%      |
| Hewlett-Packard     | 1         | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s         | 2         | 3.64%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                | 1         | 1.82%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                     | 1         | 1.82%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 1.82%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 1.82%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Toshiba RAM 9965525-138.A00LF 8192MB DIMM DDR3 1600MT/s     | 1         | 1.82%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s              | 1         | 1.82%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 1.82%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 1.82%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 1.82%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.82%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s        | 1         | 1.82%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.82%   |
| Samsung RAM M395T5750EZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.82%   |
| Samsung RAM M395T5750CZ4-CE61 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.82%   |
| Samsung RAM M393B2K70CM0-CF8 16384MB DIMM DDR3 1066MT/s     | 1         | 1.82%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s     | 1         | 1.82%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s      | 1         | 1.82%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.82%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.82%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s      | 1         | 1.82%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Samsung RAM M391B1G73BH0-YH9 8192MB DIMM DDR3 1333MT/s      | 1         | 1.82%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 2133MT/s         | 1         | 1.82%   |
| Patriot RAM PSD416G26662 16384MB DIMM DDR4 2667MT/s         | 1         | 1.82%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s         | 1         | 1.82%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8192MB DIMM DDR3 1333MT/s      | 1         | 1.82%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s        | 1         | 1.82%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s      | 1         | 1.82%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1400MT/s             | 1         | 1.82%   |
| Kingston RAM 99U5403-195.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.82%   |
| Kingston RAM 99U5403-083.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.82%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s       | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 70%     |
| DDR4    | 8         | 20%     |
| Unknown | 3         | 7.5%    |
| DDR2    | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 38        | 95%     |
| SODIMM  | 1         | 2.5%    |
| FB-DIMM | 1         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 63.27%  |
| 4096  | 8         | 16.33%  |
| 16384 | 6         | 12.24%  |
| 2048  | 4         | 8.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 15        | 34.88%  |
| 1333  | 11        | 25.58%  |
| 1066  | 3         | 6.98%   |
| 3200  | 2         | 4.65%   |
| 3000  | 2         | 4.65%   |
| 2133  | 2         | 4.65%   |
| 800   | 2         | 4.65%   |
| 667   | 2         | 4.65%   |
| 2667  | 1         | 2.33%   |
| 2666  | 1         | 2.33%   |
| 2400  | 1         | 2.33%   |
| 1400  | 1         | 2.33%   |

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
| 0     | 25        | 50%     |
| 2     | 11        | 22%     |
| 1     | 7         | 14%     |
| 3     | 4         | 8%      |
| 4     | 2         | 4%      |
| 5     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 18        | 47.37%  |
| Sound                    | 12        | 31.58%  |
| Firewire controller      | 3         | 7.89%   |
| Net/wireless             | 2         | 5.26%   |
| Bluetooth                | 2         | 5.26%   |
| Storage/raid             | 1         | 2.63%   |

