MyBee - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MyBee.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MyBee/Desktop/README.md) and [notebooks](/Dist/MyBee/Notebook/README.md).

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

Total: 45

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME H310M-R R2.0       | Desktop     | [ebaca4d176](https://bsd-hardware.info/?probe=ebaca4d176) | Apr 23, 2024 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [ddfaad8bed](https://bsd-hardware.info/?probe=ddfaad8bed) | Apr 07, 2024 |
| Lenovo        | V15 G3 IAP 82TT          | Notebook    | [202a277c32](https://bsd-hardware.info/?probe=202a277c32) | Mar 29, 2024 |
| Unknown       | Unknown                  | Desktop     | [80f34deedc](https://bsd-hardware.info/?probe=80f34deedc) | Jan 29, 2024 |
| Unknown       | Unknown                  | Desktop     | [18168c211d](https://bsd-hardware.info/?probe=18168c211d) | Jan 29, 2024 |
| Gigabyte      | GA-970A-D3               | Desktop     | [6aeb253575](https://bsd-hardware.info/?probe=6aeb253575) | Jan 25, 2024 |
| Gigabyte      | GA-970A-D3               | Desktop     | [838906ef1b](https://bsd-hardware.info/?probe=838906ef1b) | Jan 21, 2024 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Intel         | S5520UR E22554-752       | Server      | [8e20922890](https://bsd-hardware.info/?probe=8e20922890) | Oct 20, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [c07dd3b911](https://bsd-hardware.info/?probe=c07dd3b911) | Oct 09, 2023 |
| Intel         | S5520UR E22554-752       | Server      | [ab0b5c4d36](https://bsd-hardware.info/?probe=ab0b5c4d36) | Sep 27, 2023 |
| Intel         | S5520UR E22554-753       | Server      | [4094543b6f](https://bsd-hardware.info/?probe=4094543b6f) | Sep 25, 2023 |
| ASUSTek       | P9D-MV Series            | Server      | [bccf02e740](https://bsd-hardware.info/?probe=bccf02e740) | Sep 25, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5 | Desktop     | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
| ASUSTek       | P6X58D PREMIUM           | Desktop     | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| Intel         | S3210SH FRU Ver          | Server      | [b4112bd797](https://bsd-hardware.info/?probe=b4112bd797) | Jul 24, 2023 |
| Insyde        | Purley                   | Server      | [c6ffd34b07](https://bsd-hardware.info/?probe=c6ffd34b07) | Jun 21, 2023 |
| ASRockRack    | X570D4U-2L2T             | Desktop     | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| Gigabyte      | H77N-WIFI                | Desktop     | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF         | Desktop     | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| ASUSTek       | P8Z77-V PREMIUM          | Desktop     | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0             | Desktop     | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                  | Desktop     | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Gigabyte      | A320M-H-CF               | Desktop     | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| HP            | EliteBook 8540w          | Notebook    | [0063369c40](https://bsd-hardware.info/?probe=0063369c40) | Jul 30, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Acer          | RS880M05                 | Desktop     | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Supermicro    | H8DGU                    | Server      | [172bfe70b5](https://bsd-hardware.info/?probe=172bfe70b5) | Jul 14, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [7cdaeb28fa](https://bsd-hardware.info/?probe=7cdaeb28fa) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4    | Desktop     | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB        | Desktop     | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| Supermicro    | X10SRi-FB                | Server      | [0e21a1eeb0](https://bsd-hardware.info/?probe=0e21a1eeb0) | May 27, 2022 |
| ASRockRack    | E3C242D4U2-2T            | Desktop     | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| MyBee 13.2         | 7         | 19.44%  |
| MyBee 13.1         | 7         | 19.44%  |
| MyBee 14.0-p2      | 4         | 11.11%  |
| MyBee 14.0-BETA2   | 3         | 8.33%   |
| MyBee 13.1-p7      | 3         | 8.33%   |
| MyBee 14.0-CURRENT | 2         | 5.56%   |
| MyBee 13.1-p1      | 2         | 5.56%   |
| MyBee 14.0-BETA5   | 1         | 2.78%   |
| MyBee 14.0-BETA3   | 1         | 2.78%   |
| MyBee 14.0         | 1         | 2.78%   |
| MyBee 13.2-RC5     | 1         | 2.78%   |
| MyBee 13.2-RC4     | 1         | 2.78%   |
| MyBee 13.2-RC2     | 1         | 2.78%   |
| MyBee 13.1-p5      | 1         | 2.78%   |
| MyBee 13.1-p3      | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| MyBee | 31        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 30        | 96.77%  |
| KDE5    | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 30        | 96.77%  |
| X11     | 1         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 31        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 29        | 93.55%  |
| C     | 2         | 6.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 31        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 30        | 96.77%  |
| Ufs  | 1         | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 31        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 5         | 16.13%  |
| Intel               | 4         | 12.9%   |
| Gigabyte Technology | 4         | 12.9%   |
| Supermicro          | 2         | 6.45%   |
| MSI                 | 2         | 6.45%   |
| Fujitsu             | 2         | 6.45%   |
| ASRockRack          | 2         | 6.45%   |
| ASRock              | 2         | 6.45%   |
| Unknown             | 2         | 6.45%   |
| Lenovo              | 1         | 3.23%   |
| Insyde              | 1         | 3.23%   |
| IceWhale Technology | 1         | 3.23%   |
| Huanan              | 1         | 3.23%   |
| Hewlett-Packard     | 1         | 3.23%   |
| Acer                | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel S5520UR                    | 3         | 9.68%   |
| MSI MS-7D46                      | 2         | 6.45%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 2         | 6.45%   |
| ASUS PRIME B550-PLUS             | 2         | 6.45%   |
| Unknown                          | 2         | 6.45%   |
| Supermicro Super Server          | 1         | 3.23%   |
| Supermicro H8DGU                 | 1         | 3.23%   |
| Lenovo V15 G3 IAP 82TT           | 1         | 3.23%   |
| Intel S3210SH                    | 1         | 3.23%   |
| Insyde Purley                    | 1         | 3.23%   |
| IceWhale ZimaBoard 832 ZMB       | 1         | 3.23%   |
| Huanan X99-QD4 V1.0              | 1         | 3.23%   |
| HP EliteBook 8540w               | 1         | 3.23%   |
| Gigabyte Z170-HD3 DDR3           | 1         | 3.23%   |
| Gigabyte H77N-WIFI               | 1         | 3.23%   |
| Gigabyte GA-970A-D3              | 1         | 3.23%   |
| Gigabyte A320M-H                 | 1         | 3.23%   |
| ASUS PRIME H310M-R R2.0          | 1         | 3.23%   |
| ASUS P8Z77-V PREMIUM             | 1         | 3.23%   |
| ASUS P6X58D PREMIUM              | 1         | 3.23%   |
| ASRockRack X570D4U-2L2T          | 1         | 3.23%   |
| ASRockRack X470D4U2-2T           | 1         | 3.23%   |
| ASRock Z690 Phantom Gaming 4/D5  | 1         | 3.23%   |
| ASRock X570 Phantom Gaming 4     | 1         | 3.23%   |
| Acer Veriton M430                | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Intel S5520UR           | 3         | 9.68%   |
| ASUS PRIME              | 3         | 9.68%   |
| MSI MS-7D46             | 2         | 6.45%   |
| Fujitsu D3401-H2        | 2         | 6.45%   |
| Unknown                 | 2         | 6.45%   |
| Supermicro Super        | 1         | 3.23%   |
| Supermicro H8DGU        | 1         | 3.23%   |
| Lenovo V15              | 1         | 3.23%   |
| Intel S3210SH           | 1         | 3.23%   |
| Insyde Purley           | 1         | 3.23%   |
| IceWhale ZimaBoard      | 1         | 3.23%   |
| Huanan X99-QD4          | 1         | 3.23%   |
| HP EliteBook            | 1         | 3.23%   |
| Gigabyte Z170-HD3       | 1         | 3.23%   |
| Gigabyte H77N-WIFI      | 1         | 3.23%   |
| Gigabyte GA-970A-D3     | 1         | 3.23%   |
| Gigabyte A320M-H        | 1         | 3.23%   |
| ASUS P8Z77-V            | 1         | 3.23%   |
| ASUS P6X58D             | 1         | 3.23%   |
| ASRockRack X570D4U-2L2T | 1         | 3.23%   |
| ASRockRack X470D4U2-2T  | 1         | 3.23%   |
| ASRock Z690             | 1         | 3.23%   |
| ASRock X570             | 1         | 3.23%   |
| Acer Veriton            | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 5         | 16.13%  |
| 2020 | 4         | 12.9%   |
| 2018 | 3         | 9.68%   |
| 2017 | 3         | 9.68%   |
| 2019 | 2         | 6.45%   |
| 2014 | 2         | 6.45%   |
| 2013 | 2         | 6.45%   |
| 2012 | 2         | 6.45%   |
| 2011 | 2         | 6.45%   |
| 2010 | 2         | 6.45%   |
| 2023 | 1         | 3.23%   |
| 2021 | 1         | 3.23%   |
| 2015 | 1         | 3.23%   |
| 2009 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 22        | 70.97%  |
| Server   | 7         | 22.58%  |
| Notebook | 2         | 6.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 12        | 38.71%  |
| 8.01-16.0       | 9         | 29.03%  |
| 32.01-64.0      | 3         | 9.68%   |
| 16.01-24.0      | 3         | 9.68%   |
| More than 256.0 | 1         | 3.23%   |
| 4.01-8.0        | 1         | 3.23%   |
| 3.01-4.0        | 1         | 3.23%   |
| 24.01-32.0      | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 12        | 38.71%  |
| 4.01-8.0   | 5         | 16.13%  |
| 1.01-2.0   | 5         | 16.13%  |
| 2.01-3.0   | 4         | 12.9%   |
| 16.01-24.0 | 3         | 9.68%   |
| 8.01-16.0  | 1         | 3.23%   |
| 0.01-0.5   | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 11        | 32.35%  |
| 2      | 10        | 29.41%  |
| 0      | 5         | 14.71%  |
| 3      | 3         | 8.82%   |
| 5      | 2         | 5.88%   |
| 4      | 2         | 5.88%   |
| 6      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 80.65%  |
| Yes       | 6         | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Russia   | 23        | 74.19%  |
| Germany  | 3         | 9.68%   |
| USA      | 1         | 3.23%   |
| Iceland  | 1         | 3.23%   |
| Finland  | 1         | 3.23%   |
| Canada   | 1         | 3.23%   |
| Bulgaria | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| St Petersburg       | 10        | 32.26%  |
| Moscow              | 6         | 19.35%  |
| Khabarovsk          | 2         | 6.45%   |
| Vladivostok         | 1         | 3.23%   |
| Ulan-Ude            | 1         | 3.23%   |
| Sofia               | 1         | 3.23%   |
| Rostov-on-Don       | 1         | 3.23%   |
| Reykjavik           | 1         | 3.23%   |
| Remscheid           | 1         | 3.23%   |
| Naberezhnyye Chelny | 1         | 3.23%   |
| Montreal            | 1         | 3.23%   |
| Limburg an der Lahn | 1         | 3.23%   |
| Irkutsk             | 1         | 3.23%   |
| Helsinki            | 1         | 3.23%   |
| Falkenstein         | 1         | 3.23%   |
| Clearwater          | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 18     | 20.59%  |
| Toshiba             | 6         | 18     | 17.65%  |
| Samsung Electronics | 4         | 6      | 11.76%  |
| Kingston            | 4         | 7      | 11.76%  |
| WDC                 | 3         | 3      | 8.82%   |
| KingSpec            | 2         | 2      | 5.88%   |
| Intel               | 2         | 3      | 5.88%   |
| Silicon Motion      | 1         | 2      | 2.94%   |
| Phison              | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 2      | 2.94%   |
| HGST                | 1         | 2      | 2.94%   |
| GOODRAM             | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 2      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MG07ACA12TE 12TB         | 2         | 5.88%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 5.88%   |
| Samsung SSD 980 1TB              | 2         | 5.88%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 2.94%   |
| WDC WD30EJRX-89AKWY0 3TB         | 1         | 2.94%   |
| WDC WD2500AAKS-22VSA0 250GB      | 1         | 2.94%   |
| Toshiba MG06ACA800E 8TB          | 1         | 2.94%   |
| Toshiba KXG50ZNV512G 512GB       | 1         | 2.94%   |
| Toshiba HDWD110 1TB              | 1         | 2.94%   |
| Toshiba DT01ACA100 1TB           | 1         | 2.94%   |
| Silicon Motion PCIe SSD 256GB    | 1         | 2.94%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 2.94%   |
| Seagate ST500DM002-1SB10A 500GB  | 1         | 2.94%   |
| Seagate ST2000DM008-2UB102 2TB   | 1         | 2.94%   |
| Seagate ST1000NM0033-9ZM173 1TB  | 1         | 2.94%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 2.94%   |
| Samsung SSD 970 EVO Plus 1TB     | 1         | 2.94%   |
| Samsung SSD 870 EVO 1TB          | 1         | 2.94%   |
| Phison PCIe SSD 250GB            | 1         | 2.94%   |
| Micron 1100_MTFDDAK512TBN 512GB  | 1         | 2.94%   |
| Kingston SNV425S2128GB           | 1         | 2.94%   |
| Kingston SA400S37480G 480GB      | 1         | 2.94%   |
| Kingston SA400S37240G 240GB      | 1         | 2.94%   |
| Kingston SA400S37120G 120GB      | 1         | 2.94%   |
| KingSpec P3-256 256GB            | 1         | 2.94%   |
| KingSpec MT-1TB                  | 1         | 2.94%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 2.94%   |
| Intel SSDPE2MX450G7 450GB        | 1         | 2.94%   |
| HGST HUS726T4TALA6L1 4TB         | 1         | 2.94%   |
| GOODRAM SSDPR-PX500-256-80 256GB | 1         | 2.94%   |
| A-DATA SX8200PNP 1TB             | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 18     | 46.67%  |
| Toshiba | 5         | 16     | 33.33%  |
| WDC     | 2         | 2      | 13.33%  |
| HGST    | 1         | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 7      | 44.44%  |
| KingSpec            | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Micron Technology   | 1         | 2      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 38     | 42.42%  |
| NVMe | 10        | 15     | 30.3%   |
| SSD  | 9         | 14     | 27.27%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 52     | 68.75%  |
| NVMe | 10        | 15     | 31.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 12     | 37.5%   |
| 0.51-1.0   | 8         | 20     | 33.33%  |
| 10.01-20.0 | 2         | 10     | 8.33%   |
| 1.01-2.0   | 2         | 3      | 8.33%   |
| 3.01-4.0   | 1         | 2      | 4.17%   |
| 2.01-3.0   | 1         | 1      | 4.17%   |
| 4.01-10.0  | 1         | 4      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 11        | 33.33%  |
| More than 3000 | 6         | 18.18%  |
| 251-500        | 6         | 18.18%  |
| 101-250        | 6         | 18.18%  |
| 1001-2000      | 2         | 6.06%   |
| 21-50          | 1         | 3.03%   |
| 2001-3000      | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 29        | 93.55%  |
| More than 3000 | 2         | 6.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 2      | 50%     |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 50%     |
| Micron Technology   | 1         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 4      | 100%    |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 26        | 63     | 92.86%  |
| Malfunc | 2         | 4      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 21        | 46.67%  |
| AMD                      | 9         | 20%     |
| Broadcom / LSI           | 4         | 8.89%   |
| Samsung Electronics      | 3         | 6.67%   |
| Silicon Motion           | 2         | 4.44%   |
| Toshiba                  | 1         | 2.22%   |
| Phison Electronics       | 1         | 2.22%   |
| Micron Technology        | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| ASMedia Technology       | 1         | 2.22%   |
| ADATA Technology         | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 5.88%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 3         | 5.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 3         | 5.88%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                  | 3         | 5.88%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 5.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 3.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 3.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 2         | 3.92%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 3.92%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 1.96%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 1.96%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                   | 1         | 1.96%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 1.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.96%   |
| Intel SSD 660P Series                                                         | 1         | 1.96%   |
| Intel PCIe Data Center SSD                                                    | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.96%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 1         | 1.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1         | 1.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 1         | 1.96%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 1.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1         | 1.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1         | 1.96%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1         | 1.96%   |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 1.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1         | 1.96%   |
| AMD FCH SATA Controller D                                                     | 1         | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                        | 1         | 1.96%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 62.22%  |
| NVMe | 11        | 24.44%  |
| RAID | 4         | 8.89%   |
| IDE  | 2         | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 70.97%  |
| AMD    | 9         | 29.03%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon CPU E5645 @ 2.40GHz              | 3         | 9.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 6.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 6.45%   |
| Intel 12th Gen Core i5-12400                | 2         | 6.45%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2         | 6.45%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 6.45%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz         | 1         | 3.23%   |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz         | 1         | 3.23%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 3.23%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 3.23%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 3.23%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 3.23%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1         | 3.23%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1         | 3.23%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 3.23%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 3.23%   |
| Intel 12th Gen Core i9-12900K               | 1         | 3.23%   |
| Intel 12th Gen Core i3-1215U                | 1         | 3.23%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 3.23%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1         | 3.23%   |
| AMD Phenom II X6 1045T Processor            | 1         | 3.23%   |
| AMD Opteron Processor 6176                  | 1         | 3.23%   |
| AMD FX-4100 Quad-Core Processor             | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 7         | 22.58%  |
| Intel Xeon              | 5         | 16.13%  |
| Other                   | 4         | 12.9%   |
| AMD Ryzen 5             | 3         | 9.68%   |
| Intel Core i5           | 2         | 6.45%   |
| AMD Ryzen 5 PRO         | 2         | 6.45%   |
| Intel Xeon Gold         | 1         | 3.23%   |
| Intel Pentium Dual-Core | 1         | 3.23%   |
| Intel Pentium           | 1         | 3.23%   |
| Intel Celeron           | 1         | 3.23%   |
| AMD Ryzen 9             | 1         | 3.23%   |
| AMD Phenom II X6        | 1         | 3.23%   |
| AMD Opteron             | 1         | 3.23%   |
| AMD FX                  | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 10        | 32.26%  |
| 12     | 8         | 25.81%  |
| 6      | 5         | 16.13%  |
| 24     | 2         | 6.45%   |
| 8      | 2         | 6.45%   |
| 2      | 2         | 6.45%   |
| 32     | 1         | 3.23%   |
| 18     | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 83.87%  |
| 2      | 5         | 16.13%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 51.61%  |
| 1      | 15        | 48.39%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KabyLake   | 5         | 16.13%  |
| Westmere   | 4         | 12.9%   |
| Unknown    | 4         | 12.9%   |
| Zen 2      | 3         | 9.68%   |
| Zen 3      | 2         | 6.45%   |
| K10        | 2         | 6.45%   |
| IvyBridge  | 2         | 6.45%   |
| Broadwell  | 2         | 6.45%   |
| Zen+       | 1         | 3.23%   |
| Skylake    | 1         | 3.23%   |
| Silvermont | 1         | 3.23%   |
| Penryn     | 1         | 3.23%   |
| Nehalem    | 1         | 3.23%   |
| Goldmont   | 1         | 3.23%   |
| Bulldozer  | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 11        | 35.48%  |
| Nvidia                     | 6         | 19.35%  |
| Matrox Electronics Systems | 5         | 16.13%  |
| AMD                        | 5         | 16.13%  |
| ASPEED Technology          | 4         | 12.9%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 4         | 12.9%   |
| ASPEED Technology ASPEED Graphics Family                             | 4         | 12.9%   |
| Intel HD Graphics 630                                                | 3         | 9.68%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                            | 2         | 6.45%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 2         | 6.45%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 3.23%   |
| Nvidia GK208B [GeForce GT 730]                                       | 1         | 3.23%   |
| Nvidia GK208B [GeForce GT 710]                                       | 1         | 3.23%   |
| Nvidia GK107GL [Quadro K600]                                         | 1         | 3.23%   |
| Nvidia GF119 [GeForce GT 610]                                        | 1         | 3.23%   |
| Nvidia G96C [GeForce 9500 GT]                                        | 1         | 3.23%   |
| Matrox Electronics Systems MGA G200eW WPCM450                        | 1         | 3.23%   |
| Intel UHD Graphics 620                                               | 1         | 3.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1         | 3.23%   |
| Intel HD Graphics 500                                                | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 3.23%   |
| Intel AlderLake-S GT1                                                | 1         | 3.23%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                              | 1         | 3.23%   |
| AMD RS880 [Radeon HD 4250]                                           | 1         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 3.23%   |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                        | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 11        | 35.48%  |
| 1 x Nvidia | 6         | 19.35%  |
| 1 x Matrox | 5         | 16.13%  |
| 1 x AMD    | 5         | 16.13%  |
| 1 x ASPEED | 4         | 12.9%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 31        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 96.77%  |
| 1.01-2.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Dell   | 1         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell LCD Monitor U2715H 2560x1440 | 1         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 2560x1440 (QHD) | 1         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 1         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 96.77%  |
| 1     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 21        | 52.5%   |
| Realtek Semiconductor    | 14        | 35%     |
| American Megatrends      | 2         | 5%      |
| Qualcomm Atheros         | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |
| Broadcom                 | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13        | 27.66%  |
| Intel Ethernet Connection (17) I219-V                                  | 3         | 6.38%   |
| Intel 82575EB Gigabit Network Connection                               | 3         | 6.38%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 4.26%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 4.26%   |
| Intel Ethernet Controller X550                                         | 2         | 4.26%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 4.26%   |
| American Megatrends Virtual Ethernet                                   | 2         | 4.26%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 2.13%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 2.13%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1         | 2.13%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 2.13%   |
| Intel Ethernet Connection (3) I219-LM                                  | 1         | 2.13%   |
| Intel Centrino Wireless-N 2230                                         | 1         | 2.13%   |
| Intel Centrino Advanced-N 6200                                         | 1         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 2.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1         | 2.13%   |
| Intel 82583V Gigabit Network Connection                                | 1         | 2.13%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.13%   |
| Intel 82576 Gigabit Network Connection                                 | 1         | 2.13%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.13%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 2.13%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 2.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 1         | 2.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 3         | 50%     |
| Realtek Semiconductor | 1         | 16.67%  |
| Qualcomm Atheros      | 1         | 16.67%  |
| Broadcom              | 1         | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek RTL8188EE Wireless Network Adapter       | 1         | 16.67%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter | 1         | 16.67%  |
| Intel Centrino Wireless-N 2230                   | 1         | 16.67%  |
| Intel Centrino Advanced-N 6200                   | 1         | 16.67%  |
| Intel Alder Lake-P PCH CNVi WiFi                 | 1         | 16.67%  |
| Broadcom BCM43224 802.11a/b/g/n                  | 1         | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 51.43%  |
| Realtek Semiconductor    | 14        | 40%     |
| American Megatrends      | 2         | 5.71%   |
| Marvell Technology Group | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13        | 31.71%  |
| Intel Ethernet Connection (17) I219-V                                  | 3         | 7.32%   |
| Intel 82575EB Gigabit Network Connection                               | 3         | 7.32%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 4.88%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 4.88%   |
| Intel Ethernet Controller X550                                         | 2         | 4.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 4.88%   |
| American Megatrends Virtual Ethernet                                   | 2         | 4.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1         | 2.44%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 2.44%   |
| Intel Ethernet Connection (3) I219-LM                                  | 1         | 2.44%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1         | 2.44%   |
| Intel 82583V Gigabit Network Connection                                | 1         | 2.44%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.44%   |
| Intel 82576 Gigabit Network Connection                                 | 1         | 2.44%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.44%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 2.44%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 83.78%  |
| WiFi     | 6         | 16.22%  |

Used Controller
---------------

Currently used network controller

Zero info for selected period =(

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 31        | 100%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 84.38%  |
| Yes  | 5         | 15.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 2         | 50%     |
| Hewlett-Packard         | 1         | 25%     |
| Cambridge Silicon Radio | 1         | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 25%     |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 12        | 46.15%  |
| AMD    | 9         | 34.62%  |
| Nvidia | 5         | 19.23%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 10%     |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 10%     |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 10%     |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 6.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 6.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 6.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 3.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 3.33%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 3.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 3.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 3.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 3.33%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 3.33%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 3.33%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston                                | 8         | 25.81%  |
| Samsung Electronics                     | 6         | 19.35%  |
| Crucial                                 | 4         | 12.9%   |
| SK hynix                                | 3         | 9.68%   |
| Silicon Power Computer & Communications | 2         | 6.45%   |
| Micron Technology                       | 2         | 6.45%   |
| Unknown (ABCD)                          | 1         | 3.23%   |
| Unknown                                 | 1         | 3.23%   |
| Ramaxel Technology                      | 1         | 3.23%   |
| Patriot                                 | 1         | 3.23%   |
| A-DATA Technology                       | 1         | 3.23%   |
| Unknown                                 | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s            | 2         | 5%      |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM 1866MT/s              | 2         | 5%      |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM 1866MT/s              | 2         | 5%      |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM 1600MT/s              | 2         | 5%      |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s        | 2         | 5%      |
| Crucial RAM CT16G4DFD824A.C16FHD 16GB DIMM DDR4 2400MT/s     | 2         | 5%      |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1         | 2.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1         | 2.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 2.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 2.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 2.5%    |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 2933MT/s         | 1         | 2.5%    |
| Samsung RAM Module 32GB DIMM DDR4 2133MT/s                   | 1         | 2.5%    |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                     | 1         | 2.5%    |
| Samsung RAM M393B2G70DB0-YK0 16GB DIMM DDR3 1600MT/s         | 1         | 2.5%    |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s         | 1         | 2.5%    |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s         | 1         | 2.5%    |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s         | 1         | 2.5%    |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s    | 1         | 2.5%    |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Micron RAM 36KSF2G72PZ-1G6N1 16GB DIMM 1600MT/s              | 1         | 2.5%    |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM 1600MT/s              | 1         | 2.5%    |
| Micron RAM 36KDYS1G72PZ-1G4M1 8GB DIMM DDR3 1333MT/s         | 1         | 2.5%    |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 2.5%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1         | 2.5%    |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s      | 1         | 2.5%    |
| Kingston RAM 9905782-018.A00G 32GB DIMM DDR5 4800MT/s        | 1         | 2.5%    |
| Kingston RAM 9905702-082.B00G 8GB DIMM DDR4 2666MT/s         | 1         | 2.5%    |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 2.5%    |
| Crucial RAM CT32G4DFD832A.M16FF 32GB DIMM DDR4 3200MT/s      | 1         | 2.5%    |
| Crucial RAM CT32G4DFD832A.C16FF 32GB DIMM DDR4 3200MT/s      | 1         | 2.5%    |
| Crucial RAM CT32G4DFD8266.C16FB 32GB DIMM DDR4 2666MT/s      | 1         | 2.5%    |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| Unknown                                                      | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 16        | 53.33%  |
| DDR3    | 9         | 30%     |
| Unknown | 2         | 6.67%   |
| LPDDR4  | 1         | 3.33%   |
| DDR5    | 1         | 3.33%   |
| DDR2    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 27        | 87.1%   |
| SODIMM       | 3         | 9.68%   |
| Row Of Chips | 1         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 10        | 32.26%  |
| 8192  | 8         | 25.81%  |
| 32768 | 6         | 19.35%  |
| 4096  | 4         | 12.9%   |
| 2048  | 3         | 9.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 7         | 21.88%  |
| 2400  | 5         | 15.63%  |
| 1600  | 5         | 15.63%  |
| 1333  | 4         | 12.5%   |
| 2666  | 2         | 6.25%   |
| 1866  | 2         | 6.25%   |
| 4800  | 1         | 3.13%   |
| 2933  | 1         | 3.13%   |
| 2667  | 1         | 3.13%   |
| 2133  | 1         | 3.13%   |
| 1066  | 1         | 3.13%   |
| 800   | 1         | 3.13%   |
| 400   | 1         | 3.13%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Syntek         | 1         | 33.33%  |
| Silicon Motion | 1         | 33.33%  |
| Pixart Imaging | 1         | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Syntek Integrated Camera            | 1         | 33.33%  |
| Silicon Motion 300k Pixel Camera    | 1         | 33.33%  |
| Pixart Imaging PAC731x Trust Webcam | 1         | 33.33%  |

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
| 0     | 17        | 54.84%  |
| 1     | 9         | 29.03%  |
| 2     | 5         | 16.13%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 14        | 82.35%  |
| Net/ethernet             | 1         | 5.88%   |
| Firewire controller      | 1         | 5.88%   |
| Bluetooth                | 1         | 5.88%   |

