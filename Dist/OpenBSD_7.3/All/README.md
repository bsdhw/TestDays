OpenBSD 7.3 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.3/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.3/Notebook/README.md).

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

Total: 53

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | G41MT-S2                    | Desktop     | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | Notebook    | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Notebook    | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | Desktop     | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | Notebook    | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| HP            | 0A60h                       | Desktop     | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | Notebook    | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | Notebook    | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | Notebook    | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | Desktop     | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | Notebook    | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |
| Elpitech      | ET101-A1                    | Desktop     | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 35        | 81.4%   |
| i386  | 6         | 13.95%  |
| arm64 | 2         | 4.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 36        | 83.72%  |
| GNOME        | 5         | 11.63%  |
| XFCE         | 1         | 2.33%   |
| MATE         | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 35        | 81.4%   |
| Console | 8         | 18.6%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 43        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 86.05%  |
| en_US   | 3         | 6.98%   |
| ru_RU   | 1         | 2.33%   |
| es_ES   | 1         | 2.33%   |
| C       | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 22        | 51.16%  |
| EFI  | 21        | 48.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 43        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 23        | 53.49%  |
| GPT  | 20        | 46.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 20        | 46.51%  |
| ASUSTek Computer               | 6         | 13.95%  |
| PC Engines                     | 2         | 4.65%   |
| Panasonic                      | 2         | 4.65%   |
| Matsushita Electric Industrial | 2         | 4.65%   |
| Hewlett-Packard                | 2         | 4.65%   |
| Gigabyte Technology            | 2         | 4.65%   |
| VIA Technologies               | 1         | 2.33%   |
| Toshiba                        | 1         | 2.33%   |
| Tactus                         | 1         | 2.33%   |
| Fujitsu                        | 1         | 2.33%   |
| Elpitech                       | 1         | 2.33%   |
| Apple                          | 1         | 2.33%   |
| Unknown                        | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| PC Engines APU2                             | 2         | 4.65%   |
| VIA VT82C597                                | 1         | 2.33%   |
| Toshiba NB250                               | 1         | 2.33%   |
| Tactus GeoFlex 110                          | 1         | 2.33%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.33%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.33%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.33%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.33%   |
| Lenovo V14 G2 ITL 82NM                      | 1         | 2.33%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 2.33%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 2.33%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 2.33%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 2.33%   |
| Lenovo ThinkPad X220 429043U                | 1         | 2.33%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 2.33%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 2.33%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 2.33%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 2.33%   |
| Lenovo ThinkPad T500 205663G                | 1         | 2.33%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 2.33%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 2.33%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 2.33%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.33%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2.33%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.33%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 2.33%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 2.33%   |
| Lenovo G570 20079                           | 1         | 2.33%   |
| HP Pavilion Notebook                        | 1         | 2.33%   |
| HP Compaq dc5700 Microtower                 | 1         | 2.33%   |
| Gigabyte G41MT-S2                           | 1         | 2.33%   |
| Gigabyte B250M-Gaming 3                     | 1         | 2.33%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.33%   |
| Elpitech ET101-A1                           | 1         | 2.33%   |
| ASUS TUF Gaming B550-PLUS                   | 1         | 2.33%   |
| ASUS PRIME B650-PLUS                        | 1         | 2.33%   |
| ASUS PRIME B460M-A                          | 1         | 2.33%   |
| ASUS P10S-I Series                          | 1         | 2.33%   |
| ASUS M3A78-EMH HDMI                         | 1         | 2.33%   |
| ASUS 1000HE                                 | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 18        | 41.86%  |
| PC Engines APU2                             | 2         | 4.65%   |
| ASUS PRIME                                  | 2         | 4.65%   |
| VIA VT82C597                                | 1         | 2.33%   |
| Toshiba NB250                               | 1         | 2.33%   |
| Tactus GeoFlex                              | 1         | 2.33%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.33%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.33%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.33%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.33%   |
| Lenovo V14                                  | 1         | 2.33%   |
| Lenovo G570                                 | 1         | 2.33%   |
| HP Pavilion                                 | 1         | 2.33%   |
| HP Compaq                                   | 1         | 2.33%   |
| Gigabyte G41MT-S2                           | 1         | 2.33%   |
| Gigabyte B250M-Gaming                       | 1         | 2.33%   |
| Fujitsu LIFEBOOK                            | 1         | 2.33%   |
| Elpitech ET101-A1                           | 1         | 2.33%   |
| ASUS TUF                                    | 1         | 2.33%   |
| ASUS P10S-I                                 | 1         | 2.33%   |
| ASUS M3A78-EMH                              | 1         | 2.33%   |
| ASUS 1000HE                                 | 1         | 2.33%   |
| Apple MacPro1                               | 1         | 2.33%   |
| Unknown                                     | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 13.95%  |
| 2011    | 5         | 11.63%  |
| 2022    | 3         | 6.98%   |
| 2018    | 3         | 6.98%   |
| 2016    | 3         | 6.98%   |
| 2015    | 3         | 6.98%   |
| 2012    | 3         | 6.98%   |
| 2023    | 2         | 4.65%   |
| 2021    | 2         | 4.65%   |
| 2019    | 2         | 4.65%   |
| 2007    | 2         | 4.65%   |
| 2006    | 2         | 4.65%   |
| Unknown | 2         | 4.65%   |
| 2020    | 1         | 2.33%   |
| 2017    | 1         | 2.33%   |
| 2013    | 1         | 2.33%   |
| 2009    | 1         | 2.33%   |
| 2002    | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 29        | 67.44%  |
| Desktop  | 14        | 32.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 95.35%  |
| Yes  | 2         | 4.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 14        | 31.82%  |
| 4.01-8.0    | 11        | 25%     |
| 3.01-4.0    | 6         | 13.64%  |
| 32.01-64.0  | 2         | 4.55%   |
| 2.01-3.0    | 2         | 4.55%   |
| 64.01-256.0 | 2         | 4.55%   |
| 16.01-24.0  | 2         | 4.55%   |
| 0.51-1.0    | 2         | 4.55%   |
| 24.01-32.0  | 1         | 2.27%   |
| 1.01-2.0    | 1         | 2.27%   |
| 0.01-0.5    | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 34        | 79.07%  |
| 0        | 4         | 9.3%    |
| 1.01-2.0 | 2         | 4.65%   |
| 0.51-1.0 | 2         | 4.65%   |
| 4.01-8.0 | 1         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 62.79%  |
| 2      | 8         | 18.6%   |
| 3      | 5         | 11.63%  |
| 8      | 1         | 2.33%   |
| 6      | 1         | 2.33%   |
| 0      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 90.7%   |
| No        | 4         | 9.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 67.44%  |
| No        | 14        | 32.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 51.16%  |
| No        | 21        | 48.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Canada   | 14        | 32.56%  |
| Russia   | 6         | 13.95%  |
| Brazil   | 5         | 11.63%  |
| Germany  | 4         | 9.3%    |
| Uruguay  | 3         | 6.98%   |
| Spain    | 2         | 4.65%   |
| Romania  | 2         | 4.65%   |
| Mexico   | 2         | 4.65%   |
| USA      | 1         | 2.33%   |
| Ukraine  | 1         | 2.33%   |
| Poland   | 1         | 2.33%   |
| Italy    | 1         | 2.33%   |
| Colombia | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Saint-Laurent    | 14        | 32.56%  |
| Blumenau         | 5         | 11.63%  |
| Montevideo       | 3         | 6.98%   |
| St Petersburg    | 2         | 4.65%   |
| Puebla City      | 2         | 4.65%   |
| Nuremberg        | 2         | 4.65%   |
| Moscow           | 2         | 4.65%   |
| Swilcza          | 1         | 2.33%   |
| Sun Prairie      | 1         | 2.33%   |
| Podolsk          | 1         | 2.33%   |
| Oltenita         | 1         | 2.33%   |
| Navalcarnero     | 1         | 2.33%   |
| Montería        | 1         | 2.33%   |
| Monheim am Rhein | 1         | 2.33%   |
| Milan            | 1         | 2.33%   |
| Lübeck          | 1         | 2.33%   |
| Krasnodar        | 1         | 2.33%   |
| Brovary          | 1         | 2.33%   |
| Brasov           | 1         | 2.33%   |
| Barcelona        | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 10        | 13     | 17.86%  |
| Samsung Electronics | 8         | 13     | 14.29%  |
| WDC                 | 7         | 7      | 12.5%   |
| Kingston            | 5         | 5      | 8.93%   |
| Hitachi             | 5         | 5      | 8.93%   |
| Seagate             | 4         | 5      | 7.14%   |
| SanDisk             | 4         | 6      | 7.14%   |
| OPENBSD             | 2         | 2      | 3.57%   |
| Crucial             | 2         | 3      | 3.57%   |
| Apacer              | 2         | 2      | 3.57%   |
| A-DATA Technology   | 2         | 2      | 3.57%   |
| Verbatim            | 1         | 1      | 1.79%   |
| Union Memory        | 1         | 1      | 1.79%   |
| SMI                 | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| HGST                | 1         | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| SanDisk SSD PLUS 120GB              | 2         | 3.39%   |
| SanDisk Extreme SSD 500GB           | 2         | 3.39%   |
| NVMe Samsung SSD 980 500GB          | 2         | 3.39%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 3.39%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1.69%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1.69%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 1.69%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1.69%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 1.69%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1         | 1.69%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.69%   |
| Verbatim STORE N GO 64GB            | 1         | 1.69%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 1.69%   |
| SMI USB DISK 18302PB                | 1         | 1.69%   |
| Seagate ST9160821A 160GB            | 1         | 1.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.69%   |
| Seagate ST3500414CS 500GB           | 1         | 1.69%   |
| Seagate ST3250824AS P 250GB         | 1         | 1.69%   |
| Seagate ST3250318AS 250GB           | 1         | 1.69%   |
| SanDisk Cruzer Blade 64GB           | 1         | 1.69%   |
| Samsung SSD 870 QVO 2TB             | 1         | 1.69%   |
| Samsung SSD 870 EVO 500GB           | 1         | 1.69%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 1.69%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.69%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 1.69%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 1.69%   |
| Samsung HD161HJ 160GB               | 1         | 1.69%   |
| Samsung Flash Drive FIT 32GB        | 1         | 1.69%   |
| OPENBSD SR RAID 5 9.9TB             | 1         | 1.69%   |
| OPENBSD SR RAID 1 2TB               | 1         | 1.69%   |
| NVMe TOSHIBA-RC100 240GB            | 1         | 1.69%   |
| NVMe SSSTC CL1-4D256 256GB          | 1         | 1.69%   |
| NVMe Sabrent SB-1342- 1TB           | 1         | 1.69%   |
| NVMe KINGSTON SNVS200 2TB           | 1         | 1.69%   |
| NVMe KINGSTON SNV2S20 2TB           | 1         | 1.69%   |
| NVMe Asgard AN1TNVMe- 1TB           | 1         | 1.69%   |
| NVMe APPLE SSD AP0512 500GB         | 1         | 1.69%   |
| Kingston SMS200S330G 32GB           | 1         | 1.69%   |
| Kingston SA400S37480G 480GB         | 1         | 1.69%   |
| Kingston SA400S37240G 240GB         | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 23.33%  |
| NVMe                | 7         | 10     | 23.33%  |
| Hitachi             | 5         | 5      | 16.67%  |
| Seagate             | 4         | 5      | 13.33%  |
| Samsung Electronics | 2         | 2      | 6.67%   |
| OPENBSD             | 2         | 2      | 6.67%   |
| Verbatim            | 1         | 1      | 3.33%   |
| SMI                 | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 11     | 23.08%  |
| Kingston            | 5         | 5      | 19.23%  |
| SanDisk             | 4         | 6      | 15.38%  |
| NVMe                | 3         | 3      | 11.54%  |
| Crucial             | 2         | 3      | 7.69%   |
| Apacer              | 2         | 2      | 7.69%   |
| A-DATA Technology   | 2         | 2      | 7.69%   |
| Union Memory        | 1         | 1      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 24        | 34     | 50%     |
| HDD  | 24        | 34     | 50%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 68     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 35        | 46     | 74.47%  |
| 1.01-2.0        | 5         | 15     | 10.64%  |
| 0.51-1.0        | 5         | 5      | 10.64%  |
| More than 100.0 | 1         | 1      | 2.13%   |
| 4.01-10.0       | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 14        | 31.82%  |
| 101-250        | 14        | 31.82%  |
| 51-100         | 6         | 13.64%  |
| 251-500        | 4         | 9.09%   |
| More than 3000 | 2         | 4.55%   |
| 1-20           | 2         | 4.55%   |
| 1001-2000      | 1         | 2.27%   |
| 501-1000       | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 79.07%  |
| 21-50          | 4         | 9.3%    |
| More than 3000 | 1         | 2.33%   |
| 251-500        | 1         | 2.33%   |
| 2001-3000      | 1         | 2.33%   |
| 101-250        | 1         | 2.33%   |
| 51-100         | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 20%     |
| Samsung Electronics HD161HJ 160GB     | 1         | 1      | 20%     |
| Hitachi HDS722516VLAT80 164GB         | 1         | 1      | 20%     |
| A-DATA Technology SP550 480GB         | 1         | 1      | 20%     |
| A-DATA Technology SP550 240GB         | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 40%     |
| A-DATA Technology   | 2         | 2      | 40%     |
| Hitachi             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 60%     |
| HDD  | 2         | 2      | 40%     |

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
| Works    | 31        | 45     | 65.96%  |
| Detected | 11        | 18     | 23.4%   |
| Malfunc  | 5         | 5      | 10.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 29        | 61.7%   |
| AMD                            | 6         | 12.77%  |
| Samsung Electronics            | 4         | 8.51%   |
| Kingston Technology Company    | 2         | 4.26%   |
| VIA Technologies               | 1         | 2.13%   |
| Toshiba                        | 1         | 2.13%   |
| Solid State Storage Technology | 1         | 2.13%   |
| Silicon Motion                 | 1         | 2.13%   |
| Phison Electronics             | 1         | 2.13%   |
| Artop Electronic               | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 7.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 5.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 5.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 3.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 3.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 3.92%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 3.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 1.96%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 1.96%   |
| Solid State Storage CL1                                                                | 1         | 1.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.96%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.96%   |
| Kingston Company unknown                                                               | 1         | 1.96%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.96%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                    | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.96%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                           | 1         | 1.96%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.96%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                 | 1         | 1.96%   |
| Intel 631xESB/632xESB IDE Controller                                                   | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 1.96%   |
| Artop Electronic AEC6712U SCSI                                                         | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.96%   |
| AMD 500 Series Chipset SATA Controller                                                 | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 57.45%  |
| IDE  | 10        | 21.28%  |
| NVMe | 9         | 19.15%  |
| SCSI | 1         | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 32        | 74.42%  |
| AMD     | 9         | 20.93%  |
| ARM     | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 3         | 6.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 3         | 6.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 6.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 2         | 4.65%   |
| AMD GX-412TC SOC                                                | 2         | 4.65%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                             | 1         | 2.33%   |
| Intel Xeon CPU 5150 @ 2.66GHz                                   | 1         | 2.33%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 2.33%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 2.33%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 2.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 2.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz                                | 1         | 2.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 1         | 2.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 2.33%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 2.33%   |
| Intel Core i3-10100 CPU @ 3.60GHz                               | 1         | 2.33%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 2.33%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                           | 1         | 2.33%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 2.33%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 2.33%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                                 | 1         | 2.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 1         | 2.33%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 2.33%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                         | 1         | 2.33%   |
| ARM Cortex-A57 r1p3                                             | 1         | 2.33%   |
| AMD Ryzen 9 5950X 16-Core Processor                             | 1         | 2.33%   |
| AMD Ryzen 7 7700X 8-Core Processor                              | 1         | 2.33%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 2.33%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                      | 1         | 2.33%   |
| AMD Phenom 9550 Quad-Core Processor                             | 1         | 2.33%   |
| AMD K6                                                          | 1         | 2.33%   |
| AMD E1-2500 APU with Radeon HD Graphics                         | 1         | 2.33%   |
|                                                                 | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 16        | 37.21%  |
| Other             | 3         | 6.98%   |
| Intel Xeon        | 2         | 4.65%   |
| Intel Core i7     | 2         | 4.65%   |
| Intel Core i3     | 2         | 4.65%   |
| Intel Core 2 Duo  | 2         | 4.65%   |
| Intel Atom        | 2         | 4.65%   |
| AMD Ryzen 7       | 2         | 4.65%   |
| AMD GX            | 2         | 4.65%   |
| Intel Pentium 4   | 1         | 2.33%   |
| Intel Genuine     | 1         | 2.33%   |
| Intel Core 2 Quad | 1         | 2.33%   |
| Intel Core 2      | 1         | 2.33%   |
| Intel Celeron     | 1         | 2.33%   |
| ARM Cortex        | 1         | 2.33%   |
| AMD Ryzen 9       | 1         | 2.33%   |
| AMD Ryzen 5 PRO   | 1         | 2.33%   |
| AMD Phenom        | 1         | 2.33%   |
| AMD E1            | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 20        | 46.51%  |
| Unknown | 10        | 23.26%  |
| 4       | 8         | 18.6%   |
| 16      | 2         | 4.65%   |
| 32      | 1         | 2.33%   |
| 12      | 1         | 2.33%   |
| 1       | 1         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 35        | 81.4%   |
| Unknown | 7         | 16.28%  |
| 2       | 1         | 2.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 20        | 46.51%  |
| 1       | 13        | 30.23%  |
| Unknown | 10        | 23.26%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 5         | 11.63%  |
| SandyBridge   | 4         | 9.3%    |
| IvyBridge     | 4         | 9.3%    |
| Westmere      | 3         | 6.98%   |
| Core          | 3         | 6.98%   |
| Unknown       | 3         | 6.98%   |
| Zen 3         | 2         | 4.65%   |
| Puma          | 2         | 4.65%   |
| Penryn        | 2         | 4.65%   |
| KabyLake      | 2         | 4.65%   |
| Bonnell       | 2         | 4.65%   |
| Zen 2         | 1         | 2.33%   |
| TigerLake     | 1         | 2.33%   |
| P6            | 1         | 2.33%   |
| NetBurst      | 1         | 2.33%   |
| K10           | 1         | 2.33%   |
| Jaguar        | 1         | 2.33%   |
| Haswell       | 1         | 2.33%   |
| Goldmont plus | 1         | 2.33%   |
| Geode         | 1         | 2.33%   |
| CometLake     | 1         | 2.33%   |
| Broadwell     | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 27        | 65.85%  |
| AMD               | 8         | 19.51%  |
| Nvidia            | 5         | 12.2%   |
| ASPEED Technology | 1         | 2.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 9.09%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 9.09%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 6.82%   |
| Nvidia GK208B [GeForce GT 710]                                                | 2         | 4.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 4.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 2.27%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                | 1         | 2.27%   |
| Nvidia G73 [GeForce 7300 GT]                                                  | 1         | 2.27%   |
| Intel UHD Graphics 620                                                        | 1         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 2.27%   |
| Intel HD Graphics 630                                                         | 1         | 2.27%   |
| Intel HD Graphics 5500                                                        | 1         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 2.27%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1         | 2.27%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 2.27%   |
| AMD RV770 [Radeon HD 4850]                                                    | 1         | 2.27%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.27%   |
| AMD RV200 [Radeon 7500/7500 LE]                                               | 1         | 2.27%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 2.27%   |
| AMD Renoir                                                                    | 1         | 2.27%   |
| AMD Raphael                                                                   | 1         | 2.27%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 2.27%   |
| AMD Barcelo                                                                   | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 48.84%  |
| 1 x AMD        | 6         | 13.95%  |
| Other          | 5         | 11.63%  |
| 2 x Intel      | 4         | 9.3%    |
| 1 x Nvidia     | 3         | 6.98%   |
| Intel + Nvidia | 1         | 2.33%   |
| Intel + AMD    | 1         | 2.33%   |
| 1 x ASPEED     | 1         | 2.33%   |
| AMD + Nvidia   | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 34        | 79.07%  |
| Unknown | 9         | 20.93%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 23.81%  |
| Samsung Electronics | 3         | 14.29%  |
| Philips             | 2         | 9.52%   |
| Chimei Innolux      | 2         | 9.52%   |
| ViewSonic           | 1         | 4.76%   |
| TRU                 | 1         | 4.76%   |
| MSI                 | 1         | 4.76%   |
| LG Display          | 1         | 4.76%   |
| Lenovo              | 1         | 4.76%   |
| Iiyama              | 1         | 4.76%   |
| Goldstar            | 1         | 4.76%   |
| BOE                 | 1         | 4.76%   |
| BenQ                | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch        | 1         | 4.76%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                    | 1         | 4.76%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch              | 1         | 4.76%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 1         | 4.76%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1         | 4.76%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 4.76%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch             | 1         | 4.76%   |
| Iiyama PL2530H IVM6131 1920x1080 540x300mm 24.3-inch                 | 1         | 4.76%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch     | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 4.76%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 4.76%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 10        | 50%     |
| 1366x768 (WXGA)    | 5         | 25%     |
| 2560x1080          | 1         | 5%      |
| 1680x1050 (WSXGA+) | 1         | 5%      |
| 1600x900 (HD+)     | 1         | 5%      |
| 1440x900 (WXGA+)   | 1         | 5%      |
| 1280x1024 (SXGA)   | 1         | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 5         | 23.81%  |
| 24      | 3         | 14.29%  |
| 15      | 3         | 14.29%  |
| 12      | 2         | 9.52%   |
| 11      | 2         | 9.52%   |
| 34      | 1         | 4.76%   |
| 23      | 1         | 4.76%   |
| 21      | 1         | 4.76%   |
| 17      | 1         | 4.76%   |
| 14      | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 42.86%  |
| 201-300     | 5         | 23.81%  |
| 501-600     | 4         | 19.05%  |
| 701-800     | 1         | 4.76%   |
| 401-500     | 1         | 4.76%   |
| Unknown     | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 80%     |
| 16/10 | 2         | 10%     |
| 5/4   | 1         | 5%      |
| 21/9  | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 28.57%  |
| 201-250        | 4         | 19.05%  |
| 61-70          | 2         | 9.52%   |
| 51-60          | 2         | 9.52%   |
| 101-110        | 2         | 9.52%   |
| 351-500        | 1         | 4.76%   |
| 251-300        | 1         | 4.76%   |
| 141-150        | 1         | 4.76%   |
| 91-100         | 1         | 4.76%   |
| Unknown        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 57.14%  |
| 51-100  | 7         | 33.33%  |
| 101-120 | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 76.74%  |
| 0     | 9         | 20.93%  |
| 2     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 29        | 54.72%  |
| Realtek Semiconductor             | 12        | 22.64%  |
| Qualcomm Atheros                  | 3         | 5.66%   |
| Ericsson Business Mobile Networks | 2         | 3.77%   |
| Broadcom                          | 2         | 3.77%   |
| Sierra Wireless                   | 1         | 1.89%   |
| Ralink Technology                 | 1         | 1.89%   |
| Marvell Technology Group          | 1         | 1.89%   |
| Huawei Technologies               | 1         | 1.89%   |
| Edimax Technology                 | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 7         | 9.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 9.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 6         | 8%      |
| Intel Wireless 8260                                                         | 3         | 4%      |
| Intel I210 Gigabit Network Connection                                       | 3         | 4%      |
| Intel Ethernet Connection I219-LM                                           | 3         | 4%      |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 4%      |
| Realtek RTL8125 2.5GbE Controller                                           | 2         | 2.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 2.67%   |
| Intel Wireless 7265                                                         | 2         | 2.67%   |
| Intel Wireless 7260                                                         | 2         | 2.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 2.67%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 2.67%   |
| Sierra Wireless EM7455                                                      | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                  | 1         | 1.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.33%   |
| Ralink RT2501/RT2573 Wireless Adapter                                       | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.33%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 1         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.33%   |
| Intel Wireless 8265 / 8275                                                  | 1         | 1.33%   |
| Intel Wireless 3160                                                         | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                        | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 1.33%   |
| Intel 82566MM Gigabit Network Connection                                    | 1         | 1.33%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                      | 1         | 1.33%   |
| Huawei E3372 LTE/UMTS/GSM HiLink Modem/Networkcard                          | 1         | 1.33%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module          | 1         | 1.33%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 74.19%  |
| Realtek Semiconductor | 2         | 6.45%   |
| Qualcomm Atheros      | 2         | 6.45%   |
| Sierra Wireless       | 1         | 3.23%   |
| Ralink Technology     | 1         | 3.23%   |
| Edimax Technology     | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 21.88%  |
| Intel Wireless 8260                                            | 3         | 9.38%   |
| Intel Wireless 7265                                            | 2         | 6.25%   |
| Intel Wireless 7260                                            | 2         | 6.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 6.25%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.25%   |
| Sierra Wireless EM7455                                         | 1         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 3.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 3.13%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.13%   |
| Intel Wireless 3160                                            | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 3.13%   |
| Edimax AC600 Wireless LAN USB Adapter                          | 1         | 3.13%   |
| Broadcom BRCM4378 Wireless Network Adapter                     | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 23        | 58.97%  |
| Realtek Semiconductor    | 11        | 28.21%  |
| Qualcomm Atheros         | 3         | 7.69%   |
| Marvell Technology Group | 1         | 2.56%   |
| Broadcom                 | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 17.95%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 15.38%  |
| Intel I210 Gigabit Network Connection                             | 3         | 7.69%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 7.69%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 5.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 5.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 2.56%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 54.17%  |
| WiFi     | 29        | 40.28%  |
| Unknown  | 3         | 4.17%   |
| Modem    | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 57.5%   |
| Ethernet | 17        | 42.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 65.12%  |
| 1     | 10        | 23.26%  |
| 3     | 3         | 6.98%   |
| 0     | 2         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 11        | 50%     |
| Broadcom                | 4         | 18.18%  |
| Foxconn / Hon Hai       | 2         | 9.09%   |
| Alps Electric           | 2         | 9.09%   |
| Realtek Semiconductor   | 1         | 4.55%   |
| Cambridge Silicon Radio | 1         | 4.55%   |
| ASUSTek Computer        | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 9         | 40.91%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 2         | 9.09%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 9.09%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 9.09%   |
| Realtek Bluetooth Adapter                                | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 4.55%   |
| Intel AX200 Bluetooth                                    | 1         | 4.55%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 4.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1         | 4.55%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 30        | 71.43%  |
| AMD    | 7         | 16.67%  |
| Nvidia | 4         | 9.52%   |
| JMTek  | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 10.42%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 6.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 6.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 4.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 2.08%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 2.08%   |
| JMTek USB PnP Audio Device                                                 | 1         | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.08%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.08%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.08%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.08%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1         | 2.08%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.08%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1         | 2.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.08%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 36.36%  |
| Unknown             | 5         | 22.73%  |
| SK hynix            | 5         | 22.73%  |
| Kingston            | 3         | 13.64%  |
| Unknown             | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 2         | 8.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 8.33%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 4.17%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 4.17%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 4.17%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 4.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.17%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.17%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 4.17%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 4.17%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 4.17%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 4.17%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 4.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.17%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s   | 1         | 4.17%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 4.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s       | 1         | 4.17%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s   | 1         | 4.17%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s    | 1         | 4.17%   |
| Unknown                                                 | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 47.62%  |
| DDR4   | 5         | 23.81%  |
| DDR2   | 3         | 14.29%  |
| SDRAM  | 2         | 9.52%   |
| LPDDR3 | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 81.82%  |
| DIMM   | 3         | 13.64%  |
| Chip   | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 33.33%  |
| 2048  | 6         | 28.57%  |
| 8192  | 3         | 14.29%  |
| 1024  | 2         | 9.52%   |
| 32768 | 1         | 4.76%   |
| 16384 | 1         | 4.76%   |
| 512   | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2400    | 3         | 14.29%  |
| 1600    | 3         | 14.29%  |
| 1067    | 3         | 14.29%  |
| Unknown | 3         | 14.29%  |
| 1334    | 2         | 9.52%   |
| 1333    | 2         | 9.52%   |
| 667     | 2         | 9.52%   |
| 3200    | 1         | 4.76%   |
| 2133    | 1         | 4.76%   |
| 1867    | 1         | 4.76%   |

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


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 11        | 55%     |
| Lite-On Technology  | 3         | 15%     |
| Bison Electronics   | 3         | 15%     |
| Tripath Technology  | 1         | 5%      |
| Lenovo              | 1         | 5%      |
| IMC Networks        | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                | 3         | 15%     |
| Chicony Integrated Camera                | 3         | 15%     |
| Bison Integrated Camera                  | 3         | 15%     |
| Chicony Integrated Camera [ThinkPad]     | 2         | 10%     |
| Tripath PC Camera                        | 1         | 5%      |
| Lenovo Integrated Webcam                 | 1         | 5%      |
| IMC Networks Integrated Camera           | 1         | 5%      |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 5%      |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5%      |
| Chicony Lenovo EasyCamera                | 1         | 5%      |
| Chicony Integrated Camera (1280x720@30)  | 1         | 5%      |
| Chicony FJ Camera                        | 1         | 5%      |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 44.44%  |
| Synaptics        | 2         | 22.22%  |
| AuthenTec        | 2         | 22.22%  |
| Upek             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 11.11%  |
| AuthenTec AES2810                                      | 1         | 11.11%  |
| AuthenTec AES2660                                      | 1         | 11.11%  |

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
| 1     | 25        | 58.14%  |
| 0     | 10        | 23.26%  |
| 2     | 4         | 9.3%    |
| 5     | 2         | 4.65%   |
| 3     | 2         | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 25        | 53.19%  |
| Graphics card            | 8         | 17.02%  |
| Firewire controller      | 5         | 10.64%  |
| Network                  | 3         | 6.38%   |
| Storage/ata              | 2         | 4.26%   |
| Sound                    | 2         | 4.26%   |
| Net/wireless             | 2         | 4.26%   |

