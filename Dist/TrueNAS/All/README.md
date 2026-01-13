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

Total: 80

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | ProLiant MicroServer        | Desktop     | [925d4b2cda](https://bsd-hardware.info/?probe=925d4b2cda) | Dec 09, 2025 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [8ef6cd3f7e](https://bsd-hardware.info/?probe=8ef6cd3f7e) | Jun 05, 2025 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [01be58b7ca](https://bsd-hardware.info/?probe=01be58b7ca) | Jun 04, 2025 |
| HP            | 158A                        | Desktop     | [f1106566c5](https://bsd-hardware.info/?probe=f1106566c5) | May 18, 2025 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [3b5e5eeea4](https://bsd-hardware.info/?probe=3b5e5eeea4) | Dec 25, 2024 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [96d3e0ca79](https://bsd-hardware.info/?probe=96d3e0ca79) | Dec 20, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [497b67a38e](https://bsd-hardware.info/?probe=497b67a38e) | Nov 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [8413a82b26](https://bsd-hardware.info/?probe=8413a82b26) | Nov 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [89007fbfac](https://bsd-hardware.info/?probe=89007fbfac) | Aug 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [bc07108ffa](https://bsd-hardware.info/?probe=bc07108ffa) | Jul 21, 2024 |
| ASUSTek       | P8H67-I                     | Desktop     | [70e83653e3](https://bsd-hardware.info/?probe=70e83653e3) | Mar 23, 2024 |
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| TrueNAS 13.1-p9       | 9         | 13.64%  |
| TrueNAS 12.2-p2       | 9         | 13.64%  |
| TrueNAS 12.2-p6       | 8         | 12.12%  |
| TrueNAS 12.2-p9       | 6         | 9.09%   |
| TrueNAS 12.2-p12      | 6         | 9.09%   |
| TrueNAS 12.2-RC3      | 4         | 6.06%   |
| TrueNAS 12.2-p11      | 4         | 6.06%   |
| TrueNAS 12.2-p10      | 4         | 6.06%   |
| TrueNAS 13.1-p7       | 2         | 3.03%   |
| TrueNAS 13.1-p2       | 2         | 3.03%   |
| TrueNAS 13.1          | 2         | 3.03%   |
| TrueNAS 25.01-R14.2p3 | 1         | 1.52%   |
| TrueNAS 13.4-p5       | 1         | 1.52%   |
| TrueNAS 13.3-p4       | 1         | 1.52%   |
| TrueNAS 13.3          | 1         | 1.52%   |
| TrueNAS 12.3-p7       | 1         | 1.52%   |
| TrueNAS 12.3-p2       | 1         | 1.52%   |
| TrueNAS 12.3-p1       | 1         | 1.52%   |
| TrueNAS 12.2-p3       | 1         | 1.52%   |
| TrueNAS 12.2-p14      | 1         | 1.52%   |
| TrueNAS 12.2          | 1         | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TrueNAS | 61        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 61        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 56        | 91.8%   |
| helloDesktop | 3         | 4.92%   |
| TWM          | 1         | 1.64%   |
| MATE         | 1         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 59        | 96.72%  |
| X11     | 2         | 3.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 60        | 98.36%  |
| LightDM | 1         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 55        | 90.16%  |
| C     | 5         | 8.2%    |
| de_DE | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 32        | 52.46%  |
| EFI  | 29        | 47.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 56        | 91.8%   |
| XXX     | 3         | 4.92%   |
| Unknown | 2         | 3.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 61        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 13        | 21.31%  |
| Supermicro          | 12        | 19.67%  |
| ASUSTek Computer    | 8         | 13.11%  |
| Gigabyte Technology | 7         | 11.48%  |
| Hewlett-Packard     | 6         | 9.84%   |
| Dell                | 6         | 9.84%   |
| ASRock              | 5         | 8.2%    |
| Lenovo              | 2         | 3.28%   |
| TYAN Computer       | 1         | 1.64%   |
| Intel               | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 13        | 21.31%  |
| Supermicro X10SLH-F/X10SLM+-F       | 2         | 3.28%   |
| Dell PowerEdge R720xd               | 2         | 3.28%   |
| TYAN S5512                          | 1         | 1.64%   |
| Supermicro X9SPV-F/LN4F             | 1         | 1.64%   |
| Supermicro X9SCL/X9SCM              | 1         | 1.64%   |
| Supermicro X9SCI/X9SCA              | 1         | 1.64%   |
| Supermicro X9DRD-7LN4F              | 1         | 1.64%   |
| Supermicro X8STi                    | 1         | 1.64%   |
| Supermicro X11DPi-N(T)              | 1         | 1.64%   |
| Supermicro X10SLM-F                 | 1         | 1.64%   |
| Supermicro X10SAE                   | 1         | 1.64%   |
| Supermicro SwyxExpress              | 1         | 1.64%   |
| Supermicro ReadyDATA 5200           | 1         | 1.64%   |
| Lenovo ThinkCentre M73 10AXS01800   | 1         | 1.64%   |
| Lenovo 70AQ0009UX ThinkServer TS440 | 1         | 1.64%   |
| Intel NUC6CAYH                      | 1         | 1.64%   |
| HP Z620 Workstation                 | 1         | 1.64%   |
| HP ProLiant ML150 G6                | 1         | 1.64%   |
| HP ProLiant ML10 v2                 | 1         | 1.64%   |
| HP ProLiant MicroServer Gen8        | 1         | 1.64%   |
| HP ProLiant MicroServer             | 1         | 1.64%   |
| HP Compaq Elite 8300 SFF            | 1         | 1.64%   |
| Gigabyte Z77X-UP4 TH                | 1         | 1.64%   |
| Gigabyte H97-D3H                    | 1         | 1.64%   |
| Gigabyte H610M H DDR4               | 1         | 1.64%   |
| Gigabyte GA-A75-UD4H                | 1         | 1.64%   |
| Gigabyte B550I AORUS PRO AX         | 1         | 1.64%   |
| Gigabyte B450M DS3H                 | 1         | 1.64%   |
| Gigabyte 990FXA-UD3                 | 1         | 1.64%   |
| Dell PowerEdge T310                 | 1         | 1.64%   |
| Dell PowerEdge T110 II              | 1         | 1.64%   |
| Dell PowerEdge 2950                 | 1         | 1.64%   |
| Dell OptiPlex 790                   | 1         | 1.64%   |
| ASUS TUF Z270 MARK 2                | 1         | 1.64%   |
| ASUS ROG CROSSHAIR VI HERO          | 1         | 1.64%   |
| ASUS P8H67-I                        | 1         | 1.64%   |
| ASUS P10S-I Series                  | 1         | 1.64%   |
| ASUS M5A99X EVO R2.0                | 1         | 1.64%   |
| ASUS M5A99X EVO                     | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 13        | 21.31%  |
| Dell PowerEdge                  | 5         | 8.2%    |
| HP ProLiant                     | 4         | 6.56%   |
| Supermicro X10SLH-F             | 2         | 3.28%   |
| ASUS M5A99X                     | 2         | 3.28%   |
| ASUS M5A78L-M                   | 2         | 3.28%   |
| TYAN S5512                      | 1         | 1.64%   |
| Supermicro X9SPV-F              | 1         | 1.64%   |
| Supermicro X9SCL                | 1         | 1.64%   |
| Supermicro X9SCI                | 1         | 1.64%   |
| Supermicro X9DRD-7LN4F          | 1         | 1.64%   |
| Supermicro X8STi                | 1         | 1.64%   |
| Supermicro X11DPi-N(T)          | 1         | 1.64%   |
| Supermicro X10SLM-F             | 1         | 1.64%   |
| Supermicro X10SAE               | 1         | 1.64%   |
| Supermicro SwyxExpress          | 1         | 1.64%   |
| Supermicro ReadyDATA            | 1         | 1.64%   |
| Lenovo ThinkCentre              | 1         | 1.64%   |
| Lenovo 70AQ0009UX               | 1         | 1.64%   |
| Intel NUC6CAYH                  | 1         | 1.64%   |
| HP Z620                         | 1         | 1.64%   |
| HP Compaq                       | 1         | 1.64%   |
| Gigabyte Z77X-UP4               | 1         | 1.64%   |
| Gigabyte H97-D3H                | 1         | 1.64%   |
| Gigabyte H610M                  | 1         | 1.64%   |
| Gigabyte GA-A75-UD4H            | 1         | 1.64%   |
| Gigabyte B550I                  | 1         | 1.64%   |
| Gigabyte B450M                  | 1         | 1.64%   |
| Gigabyte 990FXA-UD3             | 1         | 1.64%   |
| Dell OptiPlex                   | 1         | 1.64%   |
| ASUS TUF                        | 1         | 1.64%   |
| ASUS ROG                        | 1         | 1.64%   |
| ASUS P8H67-I                    | 1         | 1.64%   |
| ASUS P10S-I                     | 1         | 1.64%   |
| ASRock X570M                    | 1         | 1.64%   |
| ASRock N3150M                   | 1         | 1.64%   |
| ASRock FREENAS-MINI-XL-24TB-IXN | 1         | 1.64%   |
| ASRock C2750D4I                 | 1         | 1.64%   |
| ASRock B560M                    | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 12        | 19.67%  |
| 2011    | 7         | 11.48%  |
| 2018    | 6         | 9.84%   |
| 2012    | 6         | 9.84%   |
| 2020    | 5         | 8.2%    |
| 2014    | 5         | 8.2%    |
| 2019    | 4         | 6.56%   |
| 2016    | 3         | 4.92%   |
| 2013    | 3         | 4.92%   |
| 2015    | 2         | 3.28%   |
| 2010    | 2         | 3.28%   |
| 2024    | 1         | 1.64%   |
| 2023    | 1         | 1.64%   |
| 2022    | 1         | 1.64%   |
| 2021    | 1         | 1.64%   |
| 2017    | 1         | 1.64%   |
| 2009    | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Desktop | 49        | 80.33%  |
| Server  | 11        | 18.03%  |
| Mini pc | 1         | 1.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 21        | 34.43%  |
| 16.01-24.0  | 16        | 26.23%  |
| 8.01-16.0   | 11        | 18.03%  |
| 24.01-32.0  | 6         | 9.84%   |
| 64.01-256.0 | 6         | 9.84%   |
| 4.01-8.0    | 1         | 1.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 21        | 34.43%  |
| 1.01-2.0   | 13        | 21.31%  |
| 0.01-0.5   | 7         | 11.48%  |
| 2.01-3.0   | 5         | 8.2%    |
| 4.01-8.0   | 4         | 6.56%   |
| 24.01-32.0 | 4         | 6.56%   |
| 3.01-4.0   | 2         | 3.28%   |
| 16.01-24.0 | 2         | 3.28%   |
| 8.01-16.0  | 2         | 3.28%   |
| 32.01-64.0 | 1         | 1.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 12        | 19.05%  |
| 3      | 8         | 12.7%   |
| 4      | 6         | 9.52%   |
| 9      | 5         | 7.94%   |
| 1      | 5         | 7.94%   |
| 6      | 4         | 6.35%   |
| 5      | 4         | 6.35%   |
| 14     | 3         | 4.76%   |
| 17     | 2         | 3.17%   |
| 11     | 2         | 3.17%   |
| 7      | 2         | 3.17%   |
| 2      | 2         | 3.17%   |
| 27     | 1         | 1.59%   |
| 21     | 1         | 1.59%   |
| 19     | 1         | 1.59%   |
| 16     | 1         | 1.59%   |
| 15     | 1         | 1.59%   |
| 12     | 1         | 1.59%   |
| 10     | 1         | 1.59%   |
| 8      | 1         | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 87.3%   |
| Yes       | 8         | 12.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 93.44%  |
| Yes       | 4         | 6.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 93.44%  |
| Yes       | 4         | 6.56%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 26.23%  |
| Germany     | 9         | 14.75%  |
| France      | 5         | 8.2%    |
| Australia   | 5         | 8.2%    |
| Thailand    | 3         | 4.92%   |
| Romania     | 3         | 4.92%   |
| Greece      | 3         | 4.92%   |
| Switzerland | 2         | 3.28%   |
| Czechia     | 2         | 3.28%   |
| Canada      | 2         | 3.28%   |
| Brazil      | 2         | 3.28%   |
| Spain       | 1         | 1.64%   |
| Russia      | 1         | 1.64%   |
| Norway      | 1         | 1.64%   |
| Nicaragua   | 1         | 1.64%   |
| New Zealand | 1         | 1.64%   |
| Hungary     | 1         | 1.64%   |
| Estonia     | 1         | 1.64%   |
| Belgium     | 1         | 1.64%   |
| Austria     | 1         | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Taylor            | 3         | 4.62%   |
| Melbourne         | 3         | 4.62%   |
| Springfield       | 2         | 3.08%   |
| Lüneburg         | 2         | 3.08%   |
| Huenfelden        | 2         | 3.08%   |
| Brno              | 2         | 3.08%   |
| Bangkok           | 2         | 3.08%   |
| Athens            | 2         | 3.08%   |
| Apahida           | 2         | 3.08%   |
| Yverdon-les-Bains | 1         | 1.54%   |
| Willisau          | 1         | 1.54%   |
| Tartu             | 1         | 1.54%   |
| Tamm              | 1         | 1.54%   |
| Sydney            | 1         | 1.54%   |
| St Petersburg     | 1         | 1.54%   |
| Skiptvet          | 1         | 1.54%   |
| Seattle           | 1         | 1.54%   |
| SÃ£o Paulo      | 1         | 1.54%   |
| Raleigh           | 1         | 1.54%   |
| Perth             | 1         | 1.54%   |
| Perry Hall        | 1         | 1.54%   |
| Paris             | 1         | 1.54%   |
| Ougree            | 1         | 1.54%   |
| Northville        | 1         | 1.54%   |
| Managua           | 1         | 1.54%   |
| Ludwigsburg       | 1         | 1.54%   |
| Lubbock           | 1         | 1.54%   |
| Le Mesnil-Amelot  | 1         | 1.54%   |
| Landshut          | 1         | 1.54%   |
| Konstanz          | 1         | 1.54%   |
| Khlong Luang      | 1         | 1.54%   |
| Kennedale         | 1         | 1.54%   |
| JundiaГ­        | 1         | 1.54%   |
| Jundiaí          | 1         | 1.54%   |
| JundiaÃ­        | 1         | 1.54%   |
| JaraguÃ¡ do Sul | 1         | 1.54%   |
| Hendersonville    | 1         | 1.54%   |
| Hamilton          | 1         | 1.54%   |
| Genas             | 1         | 1.54%   |
| Gatineau          | 1         | 1.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 117    | 18.64%  |
| WDC                 | 20        | 93     | 16.95%  |
| Samsung Electronics | 13        | 20     | 11.02%  |
| Hitachi             | 10        | 42     | 8.47%   |
| Toshiba             | 8         | 16     | 6.78%   |
| Intel               | 8         | 16     | 6.78%   |
| Kingston            | 7         | 15     | 5.93%   |
| Crucial             | 7         | 9      | 5.93%   |
| SanDisk             | 5         | 5      | 4.24%   |
| HGST                | 3         | 17     | 2.54%   |
| HPT                 | 2         | 31     | 1.69%   |
| Hewlett-Packard     | 2         | 8      | 1.69%   |
| WD MediaMax         | 1         | 3      | 0.85%   |
| Transcend           | 1         | 1      | 0.85%   |
| SPCC                | 1         | 1      | 0.85%   |
| PNY                 | 1         | 1      | 0.85%   |
| Patriot             | 1         | 2      | 0.85%   |
| Netac               | 1         | 1      | 0.85%   |
| Mushkin             | 1         | 1      | 0.85%   |
| Fanxiang            | 1         | 1      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| Apacer              | 1         | 1      | 0.85%   |
| AMD                 | 1         | 2      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| WDC WD40EFRX-68N32N0 4TB        | 5         | 2.35%   |
| WDC WD30EFRX-68EUZN0 3TB        | 4         | 1.88%   |
| Samsung SSD 860 EVO 250GB       | 4         | 1.88%   |
| WDC WD40EFRX-68WT0N0 4TB        | 3         | 1.41%   |
| WDC WD20EFRX-68EUZN0 1TB        | 3         | 1.41%   |
| Seagate ST4000DM000-1F2168 4TB  | 3         | 1.41%   |
| SanDisk SDSSDA120G 120GB        | 3         | 1.41%   |
| Kingston SA400S37120G 120GB     | 3         | 1.41%   |
| WDC WD60EFRX-68MYMN1 6TB        | 2         | 0.94%   |
| WDC WD30EFRX-68AX9N0 3TB        | 2         | 0.94%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2         | 0.94%   |
| WDC WD20EFRX-68AX9N0 2TB        | 2         | 0.94%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 0.94%   |
| Seagate ST4000DM005-2DP166 4TB  | 2         | 0.94%   |
| Seagate ST2000DM001-1ER164 2TB  | 2         | 0.94%   |
| Samsung HD204UI 2TB             | 2         | 0.94%   |
| Intel SSDSC2BB120G4 120GB       | 2         | 0.94%   |
| Intel SSDSA2CW080G3 80GB        | 2         | 0.94%   |
| HPT DISK 0_9 3TB                | 2         | 0.94%   |
| HPT DISK 0_8 3TB                | 2         | 0.94%   |
| HPT DISK 0_7 1TB                | 2         | 0.94%   |
| HPT DISK 0_6 1TB                | 2         | 0.94%   |
| HPT DISK 0_5 1TB                | 2         | 0.94%   |
| HPT DISK 0_4 1TB                | 2         | 0.94%   |
| HPT DISK 0_3 1TB                | 2         | 0.94%   |
| HPT DISK 0_2 1TB                | 2         | 0.94%   |
| HPT DISK 0_14 3TB               | 2         | 0.94%   |
| HPT DISK 0_13 2TB               | 2         | 0.94%   |
| HPT DISK 0_12 1TB               | 2         | 0.94%   |
| HPT DISK 0_11 1TB               | 2         | 0.94%   |
| HPT DISK 0_10 1TB               | 2         | 0.94%   |
| HPT DISK 0_1 1TB                | 2         | 0.94%   |
| HPT DISK 0_0 4TB                | 2         | 0.94%   |
| Hitachi HUA722020ALA331 2TB     | 2         | 0.94%   |
| Hitachi HDS723020BLA642 2TB     | 2         | 0.94%   |
| Hitachi HDS722020ALA330 2TB     | 2         | 0.94%   |
| Hitachi H7230AS60SUN3.0T 3TB    | 2         | 0.94%   |
| Crucial M4-CT064M4SSD2 64GB     | 2         | 0.94%   |
| WDC WD80EFAX-68LHPN0 8TB        | 1         | 0.47%   |
| WDC WD8004FRYZ-01VAEB0 8TB      | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 117    | 31.88%  |
| WDC                 | 20        | 92     | 28.99%  |
| Hitachi             | 9         | 40     | 13.04%  |
| Toshiba             | 8         | 14     | 11.59%  |
| HGST                | 3         | 17     | 4.35%   |
| Samsung Electronics | 2         | 7      | 2.9%    |
| HPT                 | 2         | 31     | 2.9%    |
| Hewlett-Packard     | 2         | 8      | 2.9%    |
| WD MediaMax         | 1         | 3      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 11     | 21.43%  |
| Kingston            | 7         | 13     | 16.67%  |
| Intel               | 6         | 14     | 14.29%  |
| SanDisk             | 5         | 5      | 11.9%   |
| Crucial             | 5         | 7      | 11.9%   |
| WDC                 | 1         | 1      | 2.38%   |
| Transcend           | 1         | 1      | 2.38%   |
| Toshiba             | 1         | 2      | 2.38%   |
| SPCC                | 1         | 1      | 2.38%   |
| PNY                 | 1         | 1      | 2.38%   |
| Mushkin             | 1         | 1      | 2.38%   |
| Hitachi             | 1         | 2      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| Apacer              | 1         | 1      | 2.38%   |
| AMD                 | 1         | 2      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 329    | 49.44%  |
| SSD  | 36        | 63     | 40.45%  |
| NVMe | 9         | 12     | 10.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 392    | 83.93%  |
| NVMe | 9         | 12     | 16.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 92     | 35.58%  |
| 1.01-2.0   | 16        | 60     | 15.38%  |
| 2.01-3.0   | 14        | 80     | 13.46%  |
| 0.51-1.0   | 13        | 57     | 12.5%   |
| 3.01-4.0   | 12        | 64     | 11.54%  |
| 4.01-10.0  | 7         | 29     | 6.73%   |
| 10.01-20.0 | 5         | 10     | 4.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 22.58%  |
| 101-250        | 13        | 20.97%  |
| 251-500        | 9         | 14.52%  |
| 51-100         | 9         | 14.52%  |
| 21-50          | 5         | 8.06%   |
| More than 3000 | 4         | 6.45%   |
| 501-1000       | 4         | 6.45%   |
| Unknown        | 3         | 4.84%   |
| 2001-3000      | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 56        | 91.8%   |
| Unknown | 3         | 4.92%   |
| 251-500 | 1         | 1.64%   |
| 21-50   | 1         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68AX9N0 3TB              | 2         | 5      | 6.67%   |
| Hitachi HDS723020BLA642 2TB           | 2         | 2      | 6.67%   |
| WDC WD60EFRX-68MYMN1 6TB              | 1         | 1      | 3.33%   |
| WDC WD5000AAKX-00U6AA0 500GB          | 1         | 1      | 3.33%   |
| WDC WD30PURX-64P6ZY0 3TB              | 1         | 1      | 3.33%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 2      | 3.33%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 3.33%   |
| WDC WD2000FYYZ 2TB                    | 1         | 2      | 3.33%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 1      | 3.33%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 3.33%   |
| WD MediaMax WL2000GSA6454 2TB         | 1         | 3      | 3.33%   |
| Toshiba HDWD130 3TB                   | 1         | 2      | 3.33%   |
| Seagate ST980310AS 80GB               | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 3.33%   |
| Seagate ST4000DM000-1F2168 4TB        | 1         | 1      | 3.33%   |
| Seagate ST3320311CS 320GB             | 1         | 2      | 3.33%   |
| Seagate ST31500341AS 1.5TB            | 1         | 1      | 3.33%   |
| Seagate ST3000VN007-2E4166 3TB        | 1         | 1      | 3.33%   |
| Seagate ST3000NM0033-9ZM178 3TB       | 1         | 7      | 3.33%   |
| Seagate ST2000NM0033-9ZM175 2TB       | 1         | 1      | 3.33%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 3.33%   |
| Seagate ST2000DL001-9VT156 2TB        | 1         | 1      | 3.33%   |
| Seagate ST1000VM002-1SD102 1TB        | 1         | 2      | 3.33%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 840 EVO 120GB | 1         | 1      | 3.33%   |
| Intel SSDSC2BA200G3T 200GB            | 1         | 1      | 3.33%   |
| Hitachi HTS725032A9A364 320GB         | 1         | 1      | 3.33%   |
| Hitachi HTS723232A7A364 320GB         | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 20     | 36.84%  |
| WDC                 | 5         | 15     | 26.32%  |
| Hitachi             | 3         | 4      | 15.79%  |
| WD MediaMax         | 1         | 3      | 5.26%   |
| Toshiba             | 1         | 2      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |

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
| HDD  | 12        | 44     | 85.71%  |
| SSD  | 2         | 2      | 14.29%  |

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
| Works    | 48        | 322    | 75%     |
| Malfunc  | 13        | 46     | 20.31%  |
| Detected | 3         | 36     | 4.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 45        | 38.79%  |
| Broadcom / LSI              | 17        | 14.66%  |
| AMD                         | 14        | 12.07%  |
| Marvell Technology Group    | 10        | 8.62%   |
| ASMedia Technology          | 6         | 5.17%   |
| JMicron Technology          | 4         | 3.45%   |
| Samsung Electronics         | 3         | 2.59%   |
| Silicon Image               | 2         | 1.72%   |
| Micron/Crucial Technology   | 2         | 1.72%   |
| Kingston Technology Company | 2         | 1.72%   |
| HighPoint Technologies      | 2         | 1.72%   |
| Hewlett-Packard             | 2         | 1.72%   |
| Silicon Motion              | 1         | 0.86%   |
| Realtek Semiconductor       | 1         | 0.86%   |
| QLogic                      | 1         | 0.86%   |
| Netac Technology            | 1         | 0.86%   |
| MAXIO Technology (Hangzhou) | 1         | 0.86%   |
| Dell                        | 1         | 0.86%   |
| Areca Technology            | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 14        | 10.22%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 5.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 4.38%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 5         | 3.65%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 3.65%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 2.92%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 2.19%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                            | 3         | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.46%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 2         | 1.46%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 2         | 1.46%   |
| JMicron JMB58x AHCI SATA controller                                            | 2         | 1.46%   |
| JMicron JMB362 SATA Controller                                                 | 2         | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.46%   |
| Intel SATA Controller [RAID Mode]                                              | 2         | 1.46%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 1.46%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 2         | 1.46%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                               | 2         | 1.46%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                               | 2         | 1.46%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.46%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2         | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.46%   |
| HighPoint RocketRAID 2760 SAS Controller                                       | 2         | 1.46%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.73%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.73%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.73%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 0.73%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                    | 1         | 0.73%   |
| Netac NV3000 NVMe SSD (DRAM-less)                                              | 1         | 0.73%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.73%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 0.73%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                | 1         | 0.73%   |
| Marvell Group 88SE9125 PCIe SATA 6.0 Gb/s controller                           | 1         | 0.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.73%   |
| Intel PCIe Data Center SSD                                                     | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 52        | 46.85%  |
| RAID | 15        | 13.51%  |
| IDE  | 14        | 12.61%  |
| SAS  | 13        | 11.71%  |
| NVMe | 12        | 10.81%  |
| SCSI | 5         | 4.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 77.05%  |
| AMD    | 14        | 22.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 3         | 4.92%   |
| Intel Xeon Silver 4108 CPU @ 1.80GHz   | 2         | 3.28%   |
| Intel Xeon CPU E5504 @ 2.00GHz         | 2         | 3.28%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 2         | 3.28%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 2         | 3.28%   |
| Intel Atom CPU C2750 @ 2.40GHz         | 2         | 3.28%   |
| AMD Ryzen 7 1800X Eight-Core Processor | 2         | 3.28%   |
| AMD Ryzen 5 3600 6-Core Processor      | 2         | 3.28%   |
| AMD FX-8150 Eight-Core Processor       | 2         | 3.28%   |
| Intel Xeon E-2224 CPU @ 3.40GHz        | 1         | 1.64%   |
| Intel Xeon CPU X3450 @ 2.67GHz         | 1         | 1.64%   |
| Intel Xeon CPU X3430 @ 2.40GHz         | 1         | 1.64%   |
| Intel Xeon CPU E5506 @ 2.13GHz         | 1         | 1.64%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz     | 1         | 1.64%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz     | 1         | 1.64%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz     | 1         | 1.64%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1225 v6 @ 3.30GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz    | 1         | 1.64%   |
| Intel Xeon CPU E3-1225 V2 @ 3.20GHz    | 1         | 1.64%   |
| Intel Xeon CPU D-1518 @ 2.20GHz        | 1         | 1.64%   |
| Intel Xeon CPU 5160 @ 3.00GHz          | 1         | 1.64%   |
| Intel Pentium CPU G860 @ 3.00GHz       | 1         | 1.64%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 1         | 1.64%   |
| Intel Core i7-3555LE CPU @ 2.50GHz     | 1         | 1.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1         | 1.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1         | 1.64%   |
| Intel Core i5-4570T CPU @ 2.90GHz      | 1         | 1.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1         | 1.64%   |
| Intel Core i5-2500T CPU @ 2.30GHz      | 1         | 1.64%   |
| Intel Core i5-2500S CPU @ 2.70GH       | 1         | 1.64%   |
| Intel Core i3-4330 CPU @ 3.50GHz       | 1         | 1.64%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1         | 1.64%   |
| Intel Celeron N5105 @ 2.00GHz          | 1         | 1.64%   |
| Intel Celeron N4505 @ 2.00GHz          | 1         | 1.64%   |
| Intel Celeron G6900T                   | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Xeon        | 24        | 39.34%  |
| Intel Core i5     | 7         | 11.48%  |
| Intel Celeron     | 6         | 9.84%   |
| AMD FX            | 6         | 9.84%   |
| Intel Core i7     | 3         | 4.92%   |
| Intel Xeon Silver | 2         | 3.28%   |
| Intel Core i3     | 2         | 3.28%   |
| Intel Atom        | 2         | 3.28%   |
| AMD Ryzen 7       | 2         | 3.28%   |
| AMD Ryzen 5       | 2         | 3.28%   |
| AMD A8            | 2         | 3.28%   |
| Intel Pentium     | 1         | 1.64%   |
| AMD Turion II Neo | 1         | 1.64%   |
| AMD E1            | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 31        | 50.82%  |
| 8       | 11        | 18.03%  |
| 2       | 9         | 14.75%  |
| 16      | 5         | 8.2%    |
| 12      | 2         | 3.28%   |
| 6       | 2         | 3.28%   |
| Unknown | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 86.89%  |
| 2      | 8         | 13.11%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 42        | 68.85%  |
| 2       | 18        | 29.51%  |
| Unknown | 1         | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Haswell     | 10        | 16.39%  |
| IvyBridge   | 9         | 14.75%  |
| SandyBridge | 7         | 11.48%  |
| Piledriver  | 5         | 8.2%    |
| Nehalem     | 5         | 8.2%    |
| KabyLake    | 4         | 6.56%   |
| Silvermont  | 3         | 4.92%   |
| Unknown     | 3         | 4.92%   |
| Zen 2       | 2         | 3.28%   |
| Zen         | 2         | 3.28%   |
| Skylake     | 2         | 3.28%   |
| Bulldozer   | 2         | 3.28%   |
| K10 Llano   | 1         | 1.64%   |
| K10         | 1         | 1.64%   |
| Jaguar      | 1         | 1.64%   |
| Goldmont    | 1         | 1.64%   |
| Core        | 1         | 1.64%   |
| CometLake   | 1         | 1.64%   |
| Broadwell   | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 18        | 29.51%  |
| Matrox Electronics Systems | 15        | 24.59%  |
| ASPEED Technology          | 12        | 19.67%  |
| AMD                        | 11        | 18.03%  |
| Nvidia                     | 5         | 8.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 19.67%  |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 8         | 13.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 4.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 3.28%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 3.28%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 3.28%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 3.28%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 3.28%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 2         | 3.28%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 3.28%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 3.28%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 3.28%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 3.28%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.64%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 1.64%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 1         | 1.64%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.64%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 1         | 1.64%   |
| Intel Alder Lake-S GT1 [UHD Graphics 710]                                                | 1         | 1.64%   |
| AMD Sumo [Radeon HD 6550D]                                                               | 1         | 1.64%   |
| AMD Oland GL [FirePro W2100]                                                             | 1         | 1.64%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.64%   |
| AMD ES1000                                                                               | 1         | 1.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 27.87%  |
| 1 x Matrox     | 15        | 24.59%  |
| 1 x ASPEED     | 12        | 19.67%  |
| 1 x AMD        | 11        | 18.03%  |
| 1 x Nvidia     | 4         | 6.56%   |
| Other          | 1         | 1.64%   |
| Intel + Nvidia | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 59        | 96.72%  |
| Proprietary | 1         | 1.64%   |
| Unknown     | 1         | 1.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 98.36%  |
| 7.01-8.0   | 1         | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| BenQ   | 1         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| BenQ LCD Monitor ZOWIE XL LCD 1920x1080 | 1         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 1         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 1         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 60        | 98.36%  |
| 1     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 57.14%  |
| Realtek Semiconductor | 17        | 24.29%  |
| Broadcom              | 10        | 14.29%  |
| QLogic                | 1         | 1.43%   |
| Emulex                | 1         | 1.43%   |
| Aquantia              | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 15        | 16.3%   |
| Intel I210 Gigabit Network Connection                                                         | 8         | 8.7%    |
| Intel I350 Gigabit Network Connection                                                         | 7         | 7.61%   |
| Intel 82574L Gigabit Network Connection                                                       | 7         | 7.61%   |
| Intel Ethernet Connection I217-LM                                                             | 5         | 5.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5         | 5.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                                          | 4         | 4.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                                              | 3         | 3.26%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                              | 3         | 3.26%   |
| Intel I211 Gigabit Network Connection                                                         | 2         | 2.17%   |
| Intel Ethernet Controller I225-V                                                              | 2         | 2.17%   |
| Intel Ethernet Connection X722 for 1GbE                                                       | 2         | 2.17%   |
| Intel Ethernet Connection I217-V                                                              | 2         | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2         | 2.17%   |
| Intel 82576 Gigabit Network Connection                                                        | 2         | 2.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1         | 1.09%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.09%   |
| QLogic cLOM8214 1/10GbE Controller                                                            | 1         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 1.09%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                                 | 1         | 1.09%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                                              | 1         | 1.09%   |
| Intel Ethernet Connection (11) I219-V                                                         | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 1.09%   |
| Intel 82580 Gigabit Network Connection                                                        | 1         | 1.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)                 | 1         | 1.09%   |
| Intel 82571EB Gigabit Ethernet Controller                                                     | 1         | 1.09%   |
| Intel 82541PI Gigabit Ethernet Controller                                                     | 1         | 1.09%   |
| Emulex OneConnect OCe10100/OCe10102 Series 10 GbE                                             | 1         | 1.09%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                                            | 1         | 1.09%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                                | 1         | 1.09%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                | 1         | 1.09%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                                | 1         | 1.09%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                                       | 1         | 1.09%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                              | 1         | 1.09%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]                | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 3         | 75%     |
| Realtek Semiconductor | 1         | 25%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 25%     |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 25%     |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1         | 25%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 25%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 55.88%  |
| Realtek Semiconductor | 17        | 25%     |
| Broadcom              | 10        | 14.71%  |
| QLogic                | 1         | 1.47%   |
| Emulex                | 1         | 1.47%   |
| Aquantia              | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 15        | 17.05%  |
| Intel I210 Gigabit Network Connection                                          | 8         | 9.09%   |
| Intel I350 Gigabit Network Connection                                          | 7         | 7.95%   |
| Intel 82574L Gigabit Network Connection                                        | 7         | 7.95%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 5.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 4         | 4.55%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                               | 3         | 3.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 3         | 3.41%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 2.27%   |
| Intel Ethernet Controller I225-V                                               | 2         | 2.27%   |
| Intel Ethernet Connection X722 for 1GbE                                        | 2         | 2.27%   |
| Intel Ethernet Connection I217-V                                               | 2         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 2.27%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 2.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.14%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 1.14%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1         | 1.14%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                               | 1         | 1.14%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 1.14%   |
| Intel 82580 Gigabit Network Connection                                         | 1         | 1.14%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 1         | 1.14%   |
| Intel 82571EB Gigabit Ethernet Controller                                      | 1         | 1.14%   |
| Intel 82541PI Gigabit Ethernet Controller                                      | 1         | 1.14%   |
| Emulex OneConnect OCe10100/OCe10102 Series 10 GbE                              | 1         | 1.14%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 1         | 1.14%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                 | 1         | 1.14%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 1.14%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1         | 1.14%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                        | 1         | 1.14%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 1.14%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 93.85%  |
| WiFi     | 4         | 6.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 32.79%  |
| 2     | 18        | 29.51%  |
| 4     | 10        | 16.39%  |
| 5     | 5         | 8.2%    |
| 6     | 4         | 6.56%   |
| 3     | 4         | 6.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 3         | 75%     |
| ASUSTek Computer | 1         | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Wireless-AC 3168 Bluetooth               | 1         | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 25%     |
| Intel AX200 Bluetooth                          | 1         | 25%     |
| ASUS Qualcomm Bluetooth 4.1                    | 1         | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 10        | 45.45%  |
| AMD                | 8         | 36.36%  |
| Nvidia             | 3         | 13.64%  |
| Focusrite-Novation | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 10%     |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3         | 10%     |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 10%     |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2         | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2         | 6.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 6.67%   |
| Nvidia GP104 High Definition Audio Controller                                     | 1         | 3.33%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1         | 3.33%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 3.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1         | 3.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1         | 3.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1         | 3.33%   |
| Focusrite-Novation Focusrite Scarlett 2i2                                         | 1         | 3.33%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1         | 3.33%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 3.33%   |
| AMD FCH Azalia Controller                                                         | 1         | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 3.33%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 19.35%  |
| Kingston            | 11        | 17.74%  |
| Unknown             | 9         | 14.52%  |
| SK hynix            | 7         | 11.29%  |
| Crucial             | 6         | 9.68%   |
| Micron Technology   | 5         | 8.06%   |
| Corsair             | 4         | 6.45%   |
| Transcend           | 2         | 3.23%   |
| Toshiba             | 1         | 1.61%   |
| Team                | 1         | 1.61%   |
| PNY                 | 1         | 1.61%   |
| Patriot             | 1         | 1.61%   |
| Hewlett-Packard     | 1         | 1.61%   |
| G.Skill             | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s            | 2         | 2.9%    |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s         | 2         | 2.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                   | 1         | 1.45%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.45%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                | 1         | 1.45%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                      | 1         | 1.45%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                     | 1         | 1.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 1         | 1.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1         | 1.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                | 1         | 1.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                     | 1         | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 1.45%   |
| Toshiba RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s        | 1         | 1.45%   |
| Team RAM Vulcan-2400 8192MB DIMM DDR3 1333MT/s              | 1         | 1.45%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 1.45%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 1.45%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 1.45%   |
| SK hynix RAM HMT351R7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 1.45%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 1         | 1.45%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s        | 1         | 1.45%   |
| Samsung RAM Module 8192MB DIMM DDR3 1600MT/s                | 1         | 1.45%   |
| Samsung RAM M395T5750EZ4-CE66 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.45%   |
| Samsung RAM M395T5750CZ4-CE61 2048MB FB-DIMM DDR2 667MT/s   | 1         | 1.45%   |
| Samsung RAM M393B2K70CM0-CF8 16384MB DIMM DDR3 1066MT/s     | 1         | 1.45%   |
| Samsung RAM M393B2G70BH0-CH9 16384MB DIMM DDR3 1066MT/s     | 1         | 1.45%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s      | 1         | 1.45%   |
| Samsung RAM M393B1K70DH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.45%   |
| Samsung RAM M393B1K70DH0-CH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.45%   |
| Samsung RAM M393B1G70QH0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 1.45%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1600MT/s         | 1         | 1.45%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 1.45%   |
| Samsung RAM M391B1G73BH0-YH9 8GB DIMM DDR3 1333MT/s         | 1         | 1.45%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 2133MT/s         | 1         | 1.45%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s            | 1         | 1.45%   |
| Micron RAM F7251U64F9333G 4096MB DIMM DDR3 1333MT/s         | 1         | 1.45%   |
| Micron RAM 18KSF1G72AZ-1G6P1 8GB DIMM DDR3 1600MT/s         | 1         | 1.45%   |
| Micron RAM 18KSF1G72AZ-1G4E1 8GB DIMM DDR3 1333MT/s         | 1         | 1.45%   |
| Micron RAM 18JSF25672PDZ1G4F1 2GB DIMM DDR3 1333MT/s        | 1         | 1.45%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s      | 1         | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 34        | 69.39%  |
| DDR4    | 10        | 20.41%  |
| Unknown | 4         | 8.16%   |
| DDR2    | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 45        | 91.84%  |
| SODIMM  | 3         | 6.12%   |
| FB-DIMM | 1         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 61.02%  |
| 4096  | 12        | 20.34%  |
| 16384 | 7         | 11.86%  |
| 2048  | 4         | 6.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 33.96%  |
| 1333  | 14        | 26.42%  |
| 1066  | 4         | 7.55%   |
| 3200  | 2         | 3.77%   |
| 3000  | 2         | 3.77%   |
| 2666  | 2         | 3.77%   |
| 2400  | 2         | 3.77%   |
| 2133  | 2         | 3.77%   |
| 800   | 2         | 3.77%   |
| 667   | 2         | 3.77%   |
| 2667  | 1         | 1.89%   |
| 1866  | 1         | 1.89%   |
| 1400  | 1         | 1.89%   |

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
| 0     | 29        | 47.54%  |
| 2     | 14        | 22.95%  |
| 1     | 8         | 13.11%  |
| 3     | 6         | 9.84%   |
| 4     | 3         | 4.92%   |
| 5     | 1         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 23        | 42.59%  |
| Sound                    | 17        | 31.48%  |
| Firewire controller      | 5         | 9.26%   |
| Net/wireless             | 4         | 7.41%   |
| Bluetooth                | 4         | 7.41%   |
| Storage/raid             | 1         | 1.85%   |

