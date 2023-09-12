OpenBSD 7.3 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 56

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Panasonic     | CFSX4-1                     | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Dell          | Latitude 7280               | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Getac         | V110G2                      | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [27cf2b3e46](https://bsd-hardware.info/?probe=27cf2b3e46) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| Apple         | MacBookAir4,2               | [b1c97a3a9d](https://bsd-hardware.info/?probe=b1c97a3a9d) | Aug 09, 2023 |
| Apple         | MacBookAir4,2               | [4fdd124b61](https://bsd-hardware.info/?probe=4fdd124b61) | Aug 07, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| Panasonic     | CFSX4-1                     | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173fe60308](https://bsd-hardware.info/?probe=173fe60308) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [26e44ab6e6](https://bsd-hardware.info/?probe=26e44ab6e6) | Jul 23, 2023 |
| ASUSTek       | 900                         | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| Sony          | VPCX115KX                   | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| Lenovo        | G570 20079                  | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 35        | 77.78%  |
| i386  | 9         | 20%     |
| arm64 | 1         | 2.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 38        | 84.44%  |
| GNOME        | 6         | 13.33%  |
| MATE         | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 42        | 93.33%  |
| Console | 3         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 45        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 77.78%  |
| en_US   | 5         | 11.11%  |
| C       | 2         | 4.44%   |
| zh_TW   | 1         | 2.22%   |
| pl_PL   | 1         | 2.22%   |
| es_ES   | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 23        | 51.11%  |
| BIOS | 22        | 48.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 45        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 23        | 51.11%  |
| MBR  | 22        | 48.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 53.33%  |
| Panasonic                      | 3         | 6.67%   |
| ASUSTek Computer               | 3         | 6.67%   |
| Tactus                         | 2         | 4.44%   |
| Matsushita Electric Industrial | 2         | 4.44%   |
| Hewlett-Packard                | 2         | 4.44%   |
| Toshiba                        | 1         | 2.22%   |
| Sony                           | 1         | 2.22%   |
| IBM                            | 1         | 2.22%   |
| Getac                          | 1         | 2.22%   |
| Fujitsu Siemens                | 1         | 2.22%   |
| Fujitsu                        | 1         | 2.22%   |
| Dell                           | 1         | 2.22%   |
| Apple                          | 1         | 2.22%   |
| Unknown                        | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba NB250                               | 1         | 2.22%   |
| Tactus GeoFlex 110                          | 1         | 2.22%   |
| Tactus GeoBook 140                          | 1         | 2.22%   |
| Sony VPCX115KX                              | 1         | 2.22%   |
| Panasonic CFSX4-1                           | 1         | 2.22%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.22%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.22%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.22%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.22%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 2.22%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 2.22%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 2.22%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 2.22%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 2.22%   |
| Lenovo ThinkPad X220 429043U                | 1         | 2.22%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 2.22%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD001UUS    | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 2.22%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 2.22%   |
| Lenovo ThinkPad T500 205663G                | 1         | 2.22%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 2.22%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 2.22%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 2.22%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.22%   |
| Lenovo ThinkPad T430 2344BZU                | 1         | 2.22%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2.22%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.22%   |
| Lenovo ThinkPad T410 2522NP6                | 1         | 2.22%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 2.22%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 2.22%   |
| Lenovo G570 20079                           | 1         | 2.22%   |
| Lenovo B590 20208                           | 1         | 2.22%   |
| IBM ThinkPad T43 1871F1G                    | 1         | 2.22%   |
| HP Pavilion Notebook                        | 1         | 2.22%   |
| HP Pavilion Gaming Laptop 15-cx0xxx         | 1         | 2.22%   |
| Getac V110G2                                | 1         | 2.22%   |
| Fujitsu Siemens LIFEBOOK P1610              | 1         | 2.22%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.22%   |
| Dell Latitude 7280                          | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 22        | 48.89%  |
| HP Pavilion                                 | 2         | 4.44%   |
| Toshiba NB250                               | 1         | 2.22%   |
| Tactus GeoFlex                              | 1         | 2.22%   |
| Tactus GeoBook                              | 1         | 2.22%   |
| Sony VPCX115KX                              | 1         | 2.22%   |
| Panasonic CFSX4-1                           | 1         | 2.22%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.22%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.22%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.22%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.22%   |
| Lenovo G570                                 | 1         | 2.22%   |
| Lenovo B590                                 | 1         | 2.22%   |
| IBM ThinkPad                                | 1         | 2.22%   |
| Getac V110G2                                | 1         | 2.22%   |
| Fujitsu Siemens LIFEBOOK                    | 1         | 2.22%   |
| Fujitsu LIFEBOOK                            | 1         | 2.22%   |
| Dell Latitude                               | 1         | 2.22%   |
| ASUS VivoBook                               | 1         | 2.22%   |
| ASUS 900                                    | 1         | 2.22%   |
| ASUS 1000HE                                 | 1         | 2.22%   |
| Apple MacBookAir4                           | 1         | 2.22%   |
| Unknown                                     | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 5         | 11.11%  |
| 2010    | 5         | 11.11%  |
| 2019    | 4         | 8.89%   |
| 2020    | 3         | 6.67%   |
| 2015    | 3         | 6.67%   |
| 2013    | 3         | 6.67%   |
| 2012    | 3         | 6.67%   |
| 2009    | 3         | 6.67%   |
| 2006    | 3         | 6.67%   |
| 2022    | 2         | 4.44%   |
| 2021    | 2         | 4.44%   |
| 2018    | 2         | 4.44%   |
| 2016    | 2         | 4.44%   |
| 2023    | 1         | 2.22%   |
| 2017    | 1         | 2.22%   |
| 2007    | 1         | 2.22%   |
| 2002    | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 45        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 97.78%  |
| Yes  | 1         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 22.22%  |
| 8.01-16.0  | 10        | 22.22%  |
| 3.01-4.0   | 7         | 15.56%  |
| 16.01-24.0 | 7         | 15.56%  |
| 2.01-3.0   | 5         | 11.11%  |
| 0.51-1.0   | 3         | 6.67%   |
| 32.01-64.0 | 1         | 2.22%   |
| 24.01-32.0 | 1         | 2.22%   |
| 1.01-2.0   | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 39        | 86.67%  |
| 0        | 4         | 8.89%   |
| 1.01-2.0 | 1         | 2.22%   |
| 0.51-1.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 56.52%  |
| 2      | 12        | 26.09%  |
| 3      | 5         | 10.87%  |
| 0      | 3         | 6.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 86.67%  |
| No        | 6         | 13.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 95.56%  |
| No        | 2         | 4.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 69.57%  |
| No        | 14        | 30.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Canada   | 14        | 31.11%  |
| Russia   | 7         | 15.56%  |
| USA      | 5         | 11.11%  |
| Uruguay  | 3         | 6.67%   |
| Brazil   | 3         | 6.67%   |
| Poland   | 2         | 4.44%   |
| Germany  | 2         | 4.44%   |
| Colombia | 2         | 4.44%   |
| Ukraine  | 1         | 2.22%   |
| Taiwan   | 1         | 2.22%   |
| Spain    | 1         | 2.22%   |
| Romania  | 1         | 2.22%   |
| Mexico   | 1         | 2.22%   |
| France   | 1         | 2.22%   |
| China    | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Saint-Laurent           | 14        | 31.11%  |
| St Petersburg           | 6         | 13.33%  |
| Sun Prairie             | 3         | 6.67%   |
| Montevideo              | 3         | 6.67%   |
| Blumenau                | 3         | 6.67%   |
| Montería               | 2         | 4.44%   |
| Lübeck                 | 2         | 4.44%   |
| Wroclaw                 | 1         | 2.22%   |
| Taipei                  | 1         | 2.22%   |
| Swilcza                 | 1         | 2.22%   |
| Roswell                 | 1         | 2.22%   |
| Puebla City             | 1         | 2.22%   |
| Novosibirsk             | 1         | 2.22%   |
| Navalcarnero            | 1         | 2.22%   |
| Les Pavillons-sous-Bois | 1         | 2.22%   |
| Harbin                  | 1         | 2.22%   |
| Brovary                 | 1         | 2.22%   |
| Brasov                  | 1         | 2.22%   |
| Austin                  | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 9         | 11     | 17.65%  |
| WDC                 | 6         | 6      | 11.76%  |
| Samsung Electronics | 5         | 5      | 9.8%    |
| Kingston            | 4         | 4      | 7.84%   |
| SanDisk             | 3         | 3      | 5.88%   |
| Hitachi             | 3         | 3      | 5.88%   |
| Toshiba             | 2         | 2      | 3.92%   |
| Seagate             | 2         | 2      | 3.92%   |
| PNY                 | 2         | 3      | 3.92%   |
| Intenso             | 2         | 2      | 3.92%   |
| Apacer              | 2         | 2      | 3.92%   |
| Verbatim            | 1         | 1      | 1.96%   |
| Union Memory        | 1         | 1      | 1.96%   |
| SMI                 | 1         | 1      | 1.96%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.96%   |
| JetFlash            | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| Crucial             | 1         | 1      | 1.96%   |
| ASUSTek Computer    | 1         | 2      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| SanDisk Extreme SSD 500GB           | 2         | 3.7%    |
| PNY CS900 1TB SSD                   | 2         | 3.7%    |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 3.7%    |
| Intenso SSD 256GB                   | 2         | 3.7%    |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1.85%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1.85%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 1.85%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1.85%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 1.85%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.85%   |
| Verbatim STORE N GO 64GB            | 1         | 1.85%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 1.85%   |
| Toshiba MK8007GAH 80GB              | 1         | 1.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 1         | 1.85%   |
| SMI USB DISK 18302PB                | 1         | 1.85%   |
| Seagate ST9160821A 160GB            | 1         | 1.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.85%   |
| SanDisk SSD PLUS 120GB              | 1         | 1.85%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 1.85%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.85%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 1.85%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 1.85%   |
| Samsung MMCRE28GFMXP-MVB 128GB      | 1         | 1.85%   |
| NVMe WDC PC SN730 SDB 512GB         | 1         | 1.85%   |
| NVMe SKHynix_HFS512GD 512GB         | 1         | 1.85%   |
| NVMe Sabrent SB-1342- 1TB           | 1         | 1.85%   |
| NVMe KINGSTON SNVS500 500GB         | 1         | 1.85%   |
| NVMe KINGSTON SNVS200 2TB           | 1         | 1.85%   |
| NVMe KINGSTON SNV2S20 2TB           | 1         | 1.85%   |
| NVMe INTEL SSDPEKNU51 512GB         | 1         | 1.85%   |
| NVMe CT500P2SSD8 500GB              | 1         | 1.85%   |
| NVMe APPLE SSD AP0512 500GB         | 1         | 1.85%   |
| KIOXIA-EXCERIA SATA SSD 480GB       | 1         | 1.85%   |
| Kingston SA400S37480G 480GB         | 1         | 1.85%   |
| Kingston SA400S37240G 240GB         | 1         | 1.85%   |
| Kingston SA400S37120G 120GB         | 1         | 1.85%   |
| Kingston SA400M8240G 240GB          | 1         | 1.85%   |
| JetFlash Transcend 8GB              | 1         | 1.85%   |
| Intel SSDSC2BW480H6 480GB           | 1         | 1.85%   |
| Hitachi HTS723232A7A364 320GB       | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| NVMe     | 7         | 8      | 30.43%  |
| WDC      | 6         | 6      | 26.09%  |
| Hitachi  | 3         | 3      | 13.04%  |
| Seagate  | 2         | 2      | 8.7%    |
| Verbatim | 1         | 1      | 4.35%   |
| Toshiba  | 1         | 1      | 4.35%   |
| SMI      | 1         | 1      | 4.35%   |
| JetFlash | 1         | 1      | 4.35%   |
| Fujitsu  | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 17.24%  |
| Kingston            | 4         | 4      | 13.79%  |
| SanDisk             | 3         | 3      | 10.34%  |
| NVMe                | 3         | 3      | 10.34%  |
| PNY                 | 2         | 3      | 6.9%    |
| Intenso             | 2         | 2      | 6.9%    |
| Apacer              | 2         | 2      | 6.9%    |
| Union Memory        | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| ASUSTek Computer    | 1         | 2      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 28        | 31     | 57.14%  |
| HDD  | 21        | 24     | 42.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 55     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 34        | 40     | 72.34%  |
| 0.51-1.0        | 10        | 11     | 21.28%  |
| 1.01-2.0        | 2         | 3      | 4.26%   |
| More than 100.0 | 1         | 1      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 34.78%  |
| 21-50      | 12        | 26.09%  |
| 251-500    | 8         | 17.39%  |
| 51-100     | 4         | 8.7%    |
| 1-20       | 3         | 6.52%   |
| 1001-2000  | 2         | 4.35%   |
| 501-1000   | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 36        | 76.6%   |
| 21-50   | 6         | 12.77%  |
| 101-250 | 2         | 4.26%   |
| 51-100  | 2         | 4.26%   |
| 251-500 | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Intel SSDSC2BW480H6 480GB     | 1         | 1      | 50%     |
| A-DATA Technology SP550 480GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Intel             | 1         | 1      | 50%     |
| A-DATA Technology | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 33        | 37     | 71.74%  |
| Detected | 11        | 16     | 23.91%  |
| Malfunc  | 2         | 2      | 4.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 37        | 82.22%  |
| Kingston Technology Company | 3         | 6.67%   |
| Samsung Electronics         | 2         | 4.44%   |
| SanDisk                     | 1         | 2.22%   |
| Phison Electronics          | 1         | 2.22%   |
| AMD                         | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 13.04%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 10.87%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 8.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 8.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 6.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 4.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 4.35%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 2         | 4.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 2.17%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.17%   |
| Kingston Company unknown                                                               | 1         | 2.17%   |
| Kingston Company NVMe Controller                                                       | 1         | 2.17%   |
| Kingston Company NV1 NVMe SSD                                                          | 1         | 2.17%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 2.17%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 1         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.17%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.17%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 65.91%  |
| IDE  | 8         | 18.18%  |
| NVMe | 7         | 15.91%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 40        | 88.89%  |
| AMD     | 4         | 8.89%   |
| Unknown | 1         | 2.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 5         | 11.11%  |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 4         | 8.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 6.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 3         | 6.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 2         | 4.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 2         | 4.44%   |
| Intel Pentium M processor                                       | 1         | 2.22%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 2.22%   |
| Intel Genuine CPU U1400                                         | 1         | 2.22%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 2.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 2.22%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 2.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz                               | 1         | 2.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz                               | 1         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 2.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz                               | 1         | 2.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 2.22%   |
| Intel Core i5-2557M CPU @ 1.70GHz                               | 1         | 2.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 2.22%   |
| Intel Core i3-3120M CPU @ 2.50GHz                               | 1         | 2.22%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 2.22%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 2.22%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 2.22%   |
| Intel Celeron M processor                                       | 1         | 2.22%   |
| Intel Atom CPU Z550 @ 2.00GHz ("GenuineIntel" 686-class)        | 1         | 2.22%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 2.22%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 2.22%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 2.22%   |
| AMD Ryzen 7 4800HS with Radeon Graphics                         | 1         | 2.22%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                      | 1         | 2.22%   |
| AMD E1-2500 APU with Radeon HD Graphics                         | 1         | 2.22%   |
|                                                                 | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 24        | 53.33%  |
| Intel Atom       | 3         | 6.67%   |
| Intel Genuine    | 2         | 4.44%   |
| Intel Core i7    | 2         | 4.44%   |
| Intel Core i3    | 2         | 4.44%   |
| Intel Core 2 Duo | 2         | 4.44%   |
| Intel Celeron    | 2         | 4.44%   |
| AMD Ryzen 7      | 2         | 4.44%   |
| Other            | 1         | 2.22%   |
| Intel Pentium M  | 1         | 2.22%   |
| Intel Pentium 4  | 1         | 2.22%   |
| Intel Celeron M  | 1         | 2.22%   |
| AMD Ryzen 5 PRO  | 1         | 2.22%   |
| AMD E1           | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 28        | 62.22%  |
| Unknown | 8         | 17.78%  |
| 4       | 3         | 6.67%   |
| 1       | 3         | 6.67%   |
| 16      | 2         | 4.44%   |
| 12      | 1         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 40        | 88.89%  |
| Unknown | 5         | 11.11%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 28        | 62.22%  |
| Unknown | 11        | 24.44%  |
| 1       | 6         | 13.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Skylake       | 6         | 13.33%  |
| IvyBridge     | 6         | 13.33%  |
| SandyBridge   | 5         | 11.11%  |
| Westmere      | 4         | 8.89%   |
| P6            | 4         | 8.89%   |
| KabyLake      | 3         | 6.67%   |
| Broadwell     | 3         | 6.67%   |
| Bonnell       | 3         | 6.67%   |
| Zen 2         | 2         | 4.44%   |
| Goldmont plus | 2         | 4.44%   |
| Zen 3         | 1         | 2.22%   |
| Penryn        | 1         | 2.22%   |
| NetBurst      | 1         | 2.22%   |
| Jaguar        | 1         | 2.22%   |
| Haswell       | 1         | 2.22%   |
| Core          | 1         | 2.22%   |
| Unknown       | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 84.44%  |
| AMD    | 6         | 13.33%  |
| Nvidia | 1         | 2.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 6         | 12.24%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 12.24%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 10.2%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 8.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 6.12%   |
| Intel HD Graphics 5500                                                        | 3         | 6.12%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 4.08%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 4.08%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 4.08%   |
| AMD Renoir                                                                    | 2         | 4.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 2.04%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 2.04%   |
| Intel UHD Graphics 620                                                        | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 2.04%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.04%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 2.04%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 2.04%   |
| AMD Barcelo                                                                   | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 64.44%  |
| 2 x Intel      | 7         | 15.56%  |
| 1 x AMD        | 5         | 11.11%  |
| Other          | 2         | 4.44%   |
| Intel + Nvidia | 1         | 2.22%   |
| Intel + AMD    | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 40        | 88.89%  |
| Unknown | 5         | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 42.11%  |
| Samsung Electronics | 2         | 10.53%  |
| Chimei Innolux      | 2         | 10.53%  |
| Apple               | 2         | 10.53%  |
| TRU                 | 1         | 5.26%   |
| LG Display          | 1         | 5.26%   |
| Lenovo              | 1         | 5.26%   |
| BOE                 | 1         | 5.26%   |
| BenQ                | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 5.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 5.26%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch             | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch     | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 5.26%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 5.26%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 310x170mm 13.9-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 5.26%   |
| Apple Color LCD APPA010 1366x768 260x140mm 11.6-inch                 | 1         | 5.26%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                 | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 7         | 38.89%  |
| 1920x1080 (FHD)    | 5         | 27.78%  |
| 1600x900 (HD+)     | 2         | 11.11%  |
| 1440x900 (WXGA+)   | 2         | 11.11%  |
| 2560x1440 (QHD)    | 1         | 5.56%   |
| 1680x1050 (WSXGA+) | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 8         | 42.11%  |
| 15     | 4         | 21.05%  |
| 11     | 3         | 15.79%  |
| 12     | 2         | 10.53%  |
| 24     | 1         | 5.26%   |
| 14     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 57.89%  |
| 201-300     | 7         | 36.84%  |
| 501-600     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 83.33%  |
| 16/10 | 3         | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 47.37%  |
| 51-60          | 3         | 15.79%  |
| 61-70          | 2         | 10.53%  |
| 101-110        | 2         | 10.53%  |
| 91-100         | 2         | 10.53%  |
| 201-250        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 78.95%  |
| 51-100  | 2         | 10.53%  |
| 161-240 | 1         | 5.26%   |
| 101-120 | 1         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 84.44%  |
| 0     | 5         | 11.11%  |
| 2     | 2         | 4.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 55%     |
| Realtek Semiconductor             | 10        | 16.67%  |
| Qualcomm Atheros                  | 5         | 8.33%   |
| Marvell Technology Group          | 3         | 5%      |
| Broadcom                          | 3         | 5%      |
| Ericsson Business Mobile Networks | 2         | 3.33%   |
| TP-Link                           | 1         | 1.67%   |
| Sierra Wireless                   | 1         | 1.67%   |
| Ralink Technology                 | 1         | 1.67%   |
| ASUSTek Computer                  | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 8.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 8.79%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 5         | 5.49%   |
| Intel Wireless 8260                                                     | 4         | 4.4%    |
| Intel Wireless 7265                                                     | 4         | 4.4%    |
| Intel Ethernet Connection I219-LM                                       | 4         | 4.4%    |
| Intel 82577LM Gigabit Network Connection                                | 4         | 4.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.3%    |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 3.3%    |
| Intel Wireless 8265 / 8275                                              | 2         | 2.2%    |
| Intel Wireless 7260                                                     | 2         | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 2.2%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.1%    |
| Sierra Wireless EM7455                                                  | 1         | 1.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.1%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.1%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1         | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 1.1%    |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 1.1%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.1%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.1%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.1%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.1%    |
| Intel Wireless 3160                                                     | 1         | 1.1%    |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.1%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.1%    |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 1.1%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 68.09%  |
| Qualcomm Atheros      | 5         | 10.64%  |
| Realtek Semiconductor | 4         | 8.51%   |
| Broadcom              | 2         | 4.26%   |
| TP-Link               | 1         | 2.13%   |
| Sierra Wireless       | 1         | 2.13%   |
| Ralink Technology     | 1         | 2.13%   |
| ASUSTek Computer      | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 16.67%  |
| Intel Wireless 8260                                                     | 4         | 8.33%   |
| Intel Wireless 7265                                                     | 4         | 8.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 6.25%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.17%   |
| Intel Wireless 7260                                                     | 2         | 4.17%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 4.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2.08%   |
| Sierra Wireless EM7455                                                  | 1         | 2.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 2.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 2.08%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 2.08%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.08%   |
| Intel Wireless 3160                                                     | 1         | 2.08%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.08%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 2.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 2.08%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1         | 2.08%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 2.08%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 25        | 64.1%   |
| Realtek Semiconductor    | 7         | 17.95%  |
| Qualcomm Atheros         | 3         | 7.69%   |
| Marvell Technology Group | 3         | 7.69%   |
| Broadcom                 | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 20.51%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 12.82%  |
| Intel Ethernet Connection I219-LM                                 | 4         | 10.26%  |
| Intel 82577LM Gigabit Network Connection                          | 4         | 10.26%  |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 7.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 5.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.56%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.56%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 50%     |
| Ethernet | 39        | 45.35%  |
| Modem    | 2         | 2.33%   |
| Unknown  | 2         | 2.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 74.42%  |
| Ethernet | 11        | 25.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 84.44%  |
| 1     | 5         | 11.11%  |
| 3     | 1         | 2.22%   |
| 0     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 50%     |
| Broadcom              | 5         | 15.63%  |
| Alps Electric         | 3         | 9.38%   |
| Realtek Semiconductor | 2         | 6.25%   |
| Foxconn / Hon Hai     | 2         | 6.25%   |
| Taiyo Yuden           | 1         | 3.13%   |
| IMC Networks          | 1         | 3.13%   |
| ASUSTek Computer      | 1         | 3.13%   |
| Apple                 | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 40.63%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 9.38%   |
| Realtek Bluetooth Adapter                                | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 2         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 6.25%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 6.25%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 3.13%   |
| Intel AX200 Bluetooth                                    | 1         | 3.13%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 3.13%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 3.13%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 3.13%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1         | 3.13%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 90.7%   |
| AMD    | 4         | 9.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 13.73%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 9.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 7.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 5.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 5.88%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 5.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.92%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.96%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.96%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.96%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 38.46%  |
| Unknown             | 6         | 23.08%  |
| SK hynix            | 5         | 19.23%  |
| Unknown             | 3         | 11.54%  |
| Micron Technology   | 1         | 3.85%   |
| Crucial             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 10%     |
| Unknown                                                 | 3         | 10%     |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s        | 2         | 6.67%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 6.67%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 3.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 3.33%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 3.33%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 1         | 3.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 3.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 3.33%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 3.33%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 3.33%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 3.33%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 3.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 3.33%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s        | 1         | 3.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 3.33%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 3.33%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 3.33%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 800MT/s         | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 14        | 56%     |
| DDR2   | 4         | 16%     |
| DDR4   | 3         | 12%     |
| SDRAM  | 2         | 8%      |
| LPDDR3 | 1         | 4%      |
| DDR    | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 25        | 96.15%  |
| Chip   | 1         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 9         | 32.14%  |
| 2048  | 8         | 28.57%  |
| 8192  | 6         | 21.43%  |
| 1024  | 3         | 10.71%  |
| 16384 | 1         | 3.57%   |
| 512   | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 22.22%  |
| 1334    | 4         | 14.81%  |
| Unknown | 4         | 14.81%  |
| 1067    | 3         | 11.11%  |
| 1333    | 2         | 7.41%   |
| 3200    | 1         | 3.7%    |
| 2667    | 1         | 3.7%    |
| 2133    | 1         | 3.7%    |
| 1867    | 1         | 3.7%    |
| 800     | 1         | 3.7%    |
| 667     | 1         | 3.7%    |
| 400     | 1         | 3.7%    |
| 266     | 1         | 3.7%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 36.36%  |
| Lite-On Technology                     | 5         | 15.15%  |
| Bison Electronics                      | 5         | 15.15%  |
| Lenovo                                 | 2         | 6.06%   |
| IMC Networks                           | 2         | 6.06%   |
| Tripath Technology                     | 1         | 3.03%   |
| SunplusIT                              | 1         | 3.03%   |
| Realtek Semiconductor                  | 1         | 3.03%   |
| Jiangxi Shinetech Optical              | 1         | 3.03%   |
| Genesys Logic                          | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                                | 4         | 12.12%  |
| Bison Integrated Camera                                  | 3         | 9.09%   |
| IMC Networks Integrated Camera                           | 2         | 6.06%   |
| Chicony Integrated Camera [ThinkPad]                     | 2         | 6.06%   |
| Chicony Integrated Camera                                | 2         | 6.06%   |
| Tripath PC Camera                                        | 1         | 3.03%   |
| SunplusIT USB camera                                     | 1         | 3.03%   |
| Realtek Integrated Webcam HD                             | 1         | 3.03%   |
| Lite-On Realtek DMFT RGB                                 | 1         | 3.03%   |
| Lenovo Integrated Webcam [R5U877]                        | 1         | 3.03%   |
| Lenovo Integrated Webcam                                 | 1         | 3.03%   |
| Jiangxi Shinetech Optical Realtek PC Camera              | 1         | 3.03%   |
| Genesys Logic ASUS USB 2.0 UVC 1.3M WebCam               | 1         | 3.03%   |
| Chicony thinkpad t430s camera                            | 1         | 3.03%   |
| Chicony Sonix ST50220 USB Video Camera                   | 1         | 3.03%   |
| Chicony Ltd., USB 2.0 Camera                             | 1         | 3.03%   |
| Chicony Lenovo Integrated Camera (0.3MP)                 | 1         | 3.03%   |
| Chicony Lenovo EasyCamera                                | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                  | 1         | 3.03%   |
| Chicony FJ Camera                                        | 1         | 3.03%   |
| Chicony 2.0M UVC Webcam / CNF7129                        | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Realtek PC Camera | 1         | 3.03%   |
| Bison USB HD Webcam                                      | 1         | 3.03%   |
| Bison Lenovo Integrated Webcam                           | 1         | 3.03%   |
| Apple FaceTime Camera                                    | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 28.57%  |
| Synaptics             | 3         | 21.43%  |
| AuthenTec             | 3         | 21.43%  |
| Upek                  | 2         | 14.29%  |
| STMicroelectronics    | 1         | 7.14%   |
| LighTuning Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 21.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |
| AuthenTec AES2660                                      | 1         | 7.14%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 7.14%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 66.67%  |
| 0     | 5         | 11.11%  |
| 2     | 4         | 8.89%   |
| 5     | 3         | 6.67%   |
| 3     | 3         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 50%     |
| Graphics card            | 9         | 14.52%  |
| Net/wireless             | 5         | 8.06%   |
| Firewire controller      | 5         | 8.06%   |
| Network                  | 4         | 6.45%   |
| Storage/ata              | 3         | 4.84%   |
| Sound                    | 3         | 4.84%   |
| Modem                    | 1         | 1.61%   |
| Card reader              | 1         | 1.61%   |

