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

Total: 61

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | Latitude E7470              | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Dell          | Latitude E6420              | [b90b748742](https://bsd-hardware.info/?probe=b90b748742) | Sep 14, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
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
| amd64 | 39        | 79.59%  |
| i386  | 9         | 18.37%  |
| arm64 | 1         | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 41        | 83.67%  |
| GNOME        | 7         | 14.29%  |
| MATE         | 1         | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 93.88%  |
| Console | 3         | 6.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 49        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 37        | 75.51%  |
| en_US   | 6         | 12.24%  |
| C       | 2         | 4.08%   |
| zh_TW   | 1         | 2.04%   |
| pl_PL   | 1         | 2.04%   |
| es_ES   | 1         | 2.04%   |
| en_EN   | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 54%     |
| BIOS | 23        | 46%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 49        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 27        | 54%     |
| MBR  | 23        | 46%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 24        | 48.98%  |
| Dell                           | 4         | 8.16%   |
| Panasonic                      | 3         | 6.12%   |
| ASUSTek Computer               | 3         | 6.12%   |
| Tactus                         | 2         | 4.08%   |
| Matsushita Electric Industrial | 2         | 4.08%   |
| Hewlett-Packard                | 2         | 4.08%   |
| Toshiba                        | 1         | 2.04%   |
| Sony                           | 1         | 2.04%   |
| IBM                            | 1         | 2.04%   |
| GPD                            | 1         | 2.04%   |
| Getac                          | 1         | 2.04%   |
| Fujitsu Siemens                | 1         | 2.04%   |
| Fujitsu                        | 1         | 2.04%   |
| Apple                          | 1         | 2.04%   |
| Unknown                        | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba NB250                               | 1         | 2.04%   |
| Tactus GeoFlex 110                          | 1         | 2.04%   |
| Tactus GeoBook 140                          | 1         | 2.04%   |
| Sony VPCX115KX                              | 1         | 2.04%   |
| Panasonic CFSX4-1                           | 1         | 2.04%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.04%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.04%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.04%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.04%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 2.04%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 2.04%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 2.04%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 2.04%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 2.04%   |
| Lenovo ThinkPad X220 429043U                | 1         | 2.04%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 2.04%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD001UUS    | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 2.04%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 2.04%   |
| Lenovo ThinkPad T500 205663G                | 1         | 2.04%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 2.04%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 2.04%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 2.04%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.04%   |
| Lenovo ThinkPad T430 2344BZU                | 1         | 2.04%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2.04%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.04%   |
| Lenovo ThinkPad T410 2522NP6                | 1         | 2.04%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 2.04%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 2.04%   |
| Lenovo G570 20079                           | 1         | 2.04%   |
| Lenovo B590 20208                           | 1         | 2.04%   |
| IBM ThinkPad T43 1871F1G                    | 1         | 2.04%   |
| HP Pavilion Notebook                        | 1         | 2.04%   |
| HP Pavilion Gaming Laptop 15-cx0xxx         | 1         | 2.04%   |
| GPD G1619-04                                | 1         | 2.04%   |
| Getac V110G2                                | 1         | 2.04%   |
| Fujitsu Siemens LIFEBOOK P1610              | 1         | 2.04%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 22        | 44.9%   |
| Dell Latitude                               | 3         | 6.12%   |
| HP Pavilion                                 | 2         | 4.08%   |
| Toshiba NB250                               | 1         | 2.04%   |
| Tactus GeoFlex                              | 1         | 2.04%   |
| Tactus GeoBook                              | 1         | 2.04%   |
| Sony VPCX115KX                              | 1         | 2.04%   |
| Panasonic CFSX4-1                           | 1         | 2.04%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.04%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.04%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.04%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.04%   |
| Lenovo G570                                 | 1         | 2.04%   |
| Lenovo B590                                 | 1         | 2.04%   |
| IBM ThinkPad                                | 1         | 2.04%   |
| GPD G1619-04                                | 1         | 2.04%   |
| Getac V110G2                                | 1         | 2.04%   |
| Fujitsu Siemens LIFEBOOK                    | 1         | 2.04%   |
| Fujitsu LIFEBOOK                            | 1         | 2.04%   |
| Dell XPS                                    | 1         | 2.04%   |
| ASUS VivoBook                               | 1         | 2.04%   |
| ASUS 900                                    | 1         | 2.04%   |
| ASUS 1000HE                                 | 1         | 2.04%   |
| Apple MacBookAir4                           | 1         | 2.04%   |
| Unknown                                     | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 6         | 12.24%  |
| 2010    | 5         | 10.2%   |
| 2020    | 4         | 8.16%   |
| 2019    | 4         | 8.16%   |
| 2022    | 3         | 6.12%   |
| 2015    | 3         | 6.12%   |
| 2013    | 3         | 6.12%   |
| 2012    | 3         | 6.12%   |
| 2009    | 3         | 6.12%   |
| 2006    | 3         | 6.12%   |
| 2023    | 2         | 4.08%   |
| 2021    | 2         | 4.08%   |
| 2018    | 2         | 4.08%   |
| 2016    | 2         | 4.08%   |
| 2017    | 1         | 2.04%   |
| 2007    | 1         | 2.04%   |
| 2002    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 97.96%  |
| Yes  | 1         | 2.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 13        | 26%     |
| 4.01-8.0   | 10        | 20%     |
| 16.01-24.0 | 8         | 16%     |
| 3.01-4.0   | 7         | 14%     |
| 2.01-3.0   | 5         | 10%     |
| 0.51-1.0   | 3         | 6%      |
| 24.01-32.0 | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |
| 1.01-2.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 42        | 85.71%  |
| 0        | 4         | 8.16%   |
| 0.51-1.0 | 2         | 4.08%   |
| 1.01-2.0 | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 56%     |
| 2      | 14        | 28%     |
| 3      | 5         | 10%     |
| 0      | 3         | 6%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 83.67%  |
| No        | 8         | 16.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 95.92%  |
| No        | 2         | 4.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 66%     |
| No        | 17        | 34%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Canada             | 14        | 28.57%  |
| Russia             | 8         | 16.33%  |
| USA                | 5         | 10.2%   |
| Brazil             | 4         | 8.16%   |
| Uruguay            | 3         | 6.12%   |
| Poland             | 3         | 6.12%   |
| Germany            | 2         | 4.08%   |
| Colombia           | 2         | 4.08%   |
| Ukraine            | 1         | 2.04%   |
| Taiwan             | 1         | 2.04%   |
| Spain              | 1         | 2.04%   |
| Romania            | 1         | 2.04%   |
| Mexico             | 1         | 2.04%   |
| France             | 1         | 2.04%   |
| Dominican Republic | 1         | 2.04%   |
| China              | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Saint-Laurent           | 14        | 28.57%  |
| St Petersburg           | 6         | 12.24%  |
| Sun Prairie             | 3         | 6.12%   |
| Montevideo              | 3         | 6.12%   |
| Blumenau                | 3         | 6.12%   |
| Montería               | 2         | 4.08%   |
| Lübeck                 | 2         | 4.08%   |
| Wroclaw                 | 1         | 2.04%   |
| Taipei                  | 1         | 2.04%   |
| Swilcza                 | 1         | 2.04%   |
| Sao Paulo               | 1         | 2.04%   |
| Santo Domingo           | 1         | 2.04%   |
| Roswell                 | 1         | 2.04%   |
| Puebla City             | 1         | 2.04%   |
| Piaseczno               | 1         | 2.04%   |
| Novosibirsk             | 1         | 2.04%   |
| Navalcarnero            | 1         | 2.04%   |
| Moscow                  | 1         | 2.04%   |
| Les Pavillons-sous-Bois | 1         | 2.04%   |
| Harbin                  | 1         | 2.04%   |
| Brovary                 | 1         | 2.04%   |
| Brasov                  | 1         | 2.04%   |
| Austin                  | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 11        | 13     | 20.37%  |
| WDC                 | 7         | 7      | 12.96%  |
| Samsung Electronics | 5         | 5      | 9.26%   |
| SanDisk             | 4         | 4      | 7.41%   |
| Kingston            | 4         | 4      | 7.41%   |
| Hitachi             | 3         | 3      | 5.56%   |
| Toshiba             | 2         | 2      | 3.7%    |
| Seagate             | 2         | 2      | 3.7%    |
| Intenso             | 2         | 2      | 3.7%    |
| Apacer              | 2         | 2      | 3.7%    |
| Verbatim            | 1         | 1      | 1.85%   |
| Union Memory        | 1         | 1      | 1.85%   |
| SMI                 | 1         | 1      | 1.85%   |
| PNY                 | 1         | 2      | 1.85%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.85%   |
| JetFlash            | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| ASUSTek Computer    | 1         | 2      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| SanDisk Extreme SSD 500GB           | 2         | 3.51%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 3.51%   |
| Intenso SSD 256GB                   | 2         | 3.51%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1.75%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1.75%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 1.75%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1.75%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1.75%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 1.75%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.75%   |
| Verbatim STORE N GO 64GB            | 1         | 1.75%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 1.75%   |
| Toshiba MK8007GAH 80GB              | 1         | 1.75%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB | 1         | 1.75%   |
| SMI USB DISK 18302PB                | 1         | 1.75%   |
| Seagate ST9160821A 160GB            | 1         | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.75%   |
| SanDisk X400 M.2 2280 512GB         | 1         | 1.75%   |
| SanDisk SSD PLUS 120GB              | 1         | 1.75%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 1.75%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.75%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 1.75%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 1.75%   |
| Samsung MMCRE28GFMXP-MVB 128GB      | 1         | 1.75%   |
| PNY CS900 1TB SSD                   | 1         | 1.75%   |
| NVMe WDC PC SN730 SDB 512GB         | 1         | 1.75%   |
| NVMe SKHynix_HFS512GD 512GB         | 1         | 1.75%   |
| NVMe Sabrent SB-1342- 1TB           | 1         | 1.75%   |
| NVMe PM9A1 Samsu 1TB                | 1         | 1.75%   |
| NVMe KINGSTON SNVS500 500GB         | 1         | 1.75%   |
| NVMe KINGSTON SNVS200 2TB           | 1         | 1.75%   |
| NVMe KINGSTON SNV2S20 2TB           | 1         | 1.75%   |
| NVMe INTEL SSDPEKNU51 512GB         | 1         | 1.75%   |
| NVMe CT500P2SSD8 500GB              | 1         | 1.75%   |
| NVMe BIWIN CNF80V51G0 1TB           | 1         | 1.75%   |
| NVMe APPLE SSD AP0512 500GB         | 1         | 1.75%   |
| KIOXIA-EXCERIA SATA SSD 480GB       | 1         | 1.75%   |
| Kingston SA400S37480G 480GB         | 1         | 1.75%   |
| Kingston SA400S37240G 240GB         | 1         | 1.75%   |
| Kingston SA400S37120G 120GB         | 1         | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| NVMe     | 8         | 9      | 32%     |
| WDC      | 7         | 7      | 28%     |
| Hitachi  | 3         | 3      | 12%     |
| Seagate  | 2         | 2      | 8%      |
| Verbatim | 1         | 1      | 4%      |
| Toshiba  | 1         | 1      | 4%      |
| SMI      | 1         | 1      | 4%      |
| JetFlash | 1         | 1      | 4%      |
| Fujitsu  | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 17.24%  |
| SanDisk             | 4         | 4      | 13.79%  |
| Kingston            | 4         | 4      | 13.79%  |
| NVMe                | 3         | 3      | 10.34%  |
| Intenso             | 2         | 2      | 6.9%    |
| Apacer              | 2         | 2      | 6.9%    |
| Union Memory        | 1         | 1      | 3.45%   |
| Toshiba             | 1         | 1      | 3.45%   |
| PNY                 | 1         | 2      | 3.45%   |
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
| SSD  | 28        | 31     | 53.85%  |
| HDD  | 23        | 26     | 44.23%  |
| NVMe | 1         | 1      | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 57     | 97.87%  |
| NVMe | 1         | 1      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 35        | 41     | 71.43%  |
| 0.51-1.0        | 10        | 11     | 20.41%  |
| 1.01-2.0        | 3         | 4      | 6.12%   |
| More than 100.0 | 1         | 1      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 32.65%  |
| 21-50      | 12        | 24.49%  |
| 251-500    | 10        | 20.41%  |
| 51-100     | 5         | 10.2%   |
| 1-20       | 4         | 8.16%   |
| 1001-2000  | 2         | 4.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 39        | 78%     |
| 21-50   | 7         | 14%     |
| 101-250 | 2         | 4%      |
| 51-100  | 2         | 4%      |

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
| Works    | 34        | 38     | 69.39%  |
| Detected | 13        | 18     | 26.53%  |
| Malfunc  | 2         | 2      | 4.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 79.59%  |
| Samsung Electronics         | 3         | 6.12%   |
| Kingston Technology Company | 3         | 6.12%   |
| SanDisk                     | 1         | 2.04%   |
| Phison Electronics          | 1         | 2.04%   |
| Biwin Storage Technology    | 1         | 2.04%   |
| AMD                         | 1         | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 11.76%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 9.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 7.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 5.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 3.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 3.92%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 2         | 3.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.96%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.96%   |
| Kingston Company unknown                                                               | 1         | 1.96%   |
| Kingston Company NVMe Controller                                                       | 1         | 1.96%   |
| Kingston Company NV1 NVMe SSD                                                          | 1         | 1.96%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 1.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 1         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.96%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.96%   |
| Biwin Storage EX900 NVMe SSD (DRAM-less)                                               | 1         | 1.96%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.96%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 64.58%  |
| NVMe | 9         | 18.75%  |
| IDE  | 8         | 16.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 43        | 87.76%  |
| AMD     | 5         | 10.2%   |
| Unknown | 1         | 2.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 5         | 10.2%   |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 4         | 8.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 6.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 3         | 6.12%   |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 2         | 4.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 2         | 4.08%   |
| Intel Pentium M processor                                       | 1         | 2.04%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 2.04%   |
| Intel Genuine CPU U1400                                         | 1         | 2.04%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 2.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 2.04%   |
| Intel Core i7-6600U CPU @ 2.60GHz                               | 1         | 2.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 2.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz                               | 1         | 2.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz                               | 1         | 2.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz                               | 1         | 2.04%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 2.04%   |
| Intel Core i5-2557M CPU @ 1.70GHz                               | 1         | 2.04%   |
| Intel Core i5-2540M CPU @ 2.60GHz                               | 1         | 2.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 2.04%   |
| Intel Core i3-3120M CPU @ 2.50GHz                               | 1         | 2.04%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 2.04%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 2.04%   |
| Intel Celeron M processor                                       | 1         | 2.04%   |
| Intel Atom CPU Z550 @ 2.00GHz ("GenuineIntel" 686-class)        | 1         | 2.04%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 2.04%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 2.04%   |
| Intel 12th Gen Core i7-1260P                                    | 1         | 2.04%   |
| AMD Ryzen 7 6800U with Radeon Graphics                          | 1         | 2.04%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 2.04%   |
| AMD Ryzen 7 4800HS with Radeon Graphics                         | 1         | 2.04%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                      | 1         | 2.04%   |
| AMD E1-2500 APU with Radeon HD Graphics                         | 1         | 2.04%   |
|                                                                 | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 25        | 51.02%  |
| Intel Core i7    | 3         | 6.12%   |
| Intel Atom       | 3         | 6.12%   |
| AMD Ryzen 7      | 3         | 6.12%   |
| Other            | 2         | 4.08%   |
| Intel Genuine    | 2         | 4.08%   |
| Intel Core i3    | 2         | 4.08%   |
| Intel Core 2 Duo | 2         | 4.08%   |
| Intel Celeron    | 2         | 4.08%   |
| Intel Pentium M  | 1         | 2.04%   |
| Intel Pentium 4  | 1         | 2.04%   |
| Intel Celeron M  | 1         | 2.04%   |
| AMD Ryzen 5 PRO  | 1         | 2.04%   |
| AMD E1           | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 30        | 61.22%  |
| Unknown | 8         | 16.33%  |
| 16      | 3         | 6.12%   |
| 4       | 3         | 6.12%   |
| 1       | 3         | 6.12%   |
| 12      | 1         | 2.04%   |
| 8       | 1         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 44        | 89.8%   |
| Unknown | 5         | 10.2%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 31        | 63.27%  |
| Unknown | 11        | 22.45%  |
| 1       | 7         | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Skylake       | 7         | 14.29%  |
| SandyBridge   | 6         | 12.24%  |
| IvyBridge     | 6         | 12.24%  |
| Westmere      | 4         | 8.16%   |
| P6            | 4         | 8.16%   |
| KabyLake      | 3         | 6.12%   |
| Broadwell     | 3         | 6.12%   |
| Bonnell       | 3         | 6.12%   |
| Unknown       | 3         | 6.12%   |
| Zen 2         | 2         | 4.08%   |
| Goldmont plus | 2         | 4.08%   |
| Zen 3         | 1         | 2.04%   |
| Penryn        | 1         | 2.04%   |
| NetBurst      | 1         | 2.04%   |
| Jaguar        | 1         | 2.04%   |
| Haswell       | 1         | 2.04%   |
| Core          | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 83.67%  |
| AMD    | 7         | 14.29%  |
| Nvidia | 1         | 2.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 13.21%  |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 11.32%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 11.32%  |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 7.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 5.66%   |
| Intel HD Graphics 5500                                                        | 3         | 5.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 3.77%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 3.77%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.77%   |
| AMD Renoir                                                                    | 2         | 3.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.89%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 1.89%   |
| Intel UHD Graphics 620                                                        | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.89%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 1.89%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.89%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 1.89%   |
| AMD Rembrandt [Radeon 680M]                                                   | 1         | 1.89%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.89%   |
| AMD Barcelo                                                                   | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 65.31%  |
| 2 x Intel      | 7         | 14.29%  |
| 1 x AMD        | 6         | 12.24%  |
| Other          | 2         | 4.08%   |
| Intel + Nvidia | 1         | 2.04%   |
| Intel + AMD    | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 44        | 89.8%   |
| Unknown | 5         | 10.2%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 8         | 34.78%  |
| Samsung Electronics | 3         | 13.04%  |
| LG Display          | 2         | 8.7%    |
| Chimei Innolux      | 2         | 8.7%    |
| BOE                 | 2         | 8.7%    |
| Apple               | 2         | 8.7%    |
| TRU                 | 1         | 4.35%   |
| Lenovo              | 1         | 4.35%   |
| JDI                 | 1         | 4.35%   |
| BenQ                | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch | 1         | 4.35%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 4.35%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch              | 1         | 4.35%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 340x190mm 15.3-inch      | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 4.35%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                 | 1         | 4.35%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                 | 1         | 4.35%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 310x170mm 13.9-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch        | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch         | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 1         | 4.35%   |
| Apple Color LCD APPA010 1366x768 260x140mm 11.6-inch                  | 1         | 4.35%   |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                  | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 8         | 36.36%  |
| 1920x1080 (FHD)    | 6         | 27.27%  |
| 1600x900 (HD+)     | 2         | 9.09%   |
| 1440x900 (WXGA+)   | 2         | 9.09%   |
| 3456x2160          | 1         | 4.55%   |
| 2560x1600          | 1         | 4.55%   |
| 2560x1440 (QHD)    | 1         | 4.55%   |
| 1680x1050 (WSXGA+) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 11        | 47.83%  |
| 15     | 4         | 17.39%  |
| 11     | 3         | 13.04%  |
| 12     | 2         | 8.7%    |
| 40     | 1         | 4.35%   |
| 24     | 1         | 4.35%   |
| 14     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 56.52%  |
| 201-300     | 8         | 34.78%  |
| 801-900     | 1         | 4.35%   |
| 501-600     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 81.82%  |
| 16/10 | 4         | 18.18%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 52.17%  |
| 51-60          | 3         | 13.04%  |
| 61-70          | 2         | 8.7%    |
| 101-110        | 2         | 8.7%    |
| 91-100         | 2         | 8.7%    |
| 201-250        | 1         | 4.35%   |
| 501-1000       | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 69.57%  |
| 51-100        | 3         | 13.04%  |
| 101-120       | 2         | 8.7%    |
| More than 240 | 1         | 4.35%   |
| 161-240       | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 42        | 85.71%  |
| 0     | 5         | 10.2%   |
| 2     | 2         | 4.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 37        | 57.81%  |
| Realtek Semiconductor             | 10        | 15.63%  |
| Qualcomm Atheros                  | 5         | 7.81%   |
| Marvell Technology Group          | 3         | 4.69%   |
| Broadcom                          | 3         | 4.69%   |
| Ericsson Business Mobile Networks | 2         | 3.13%   |
| TP-Link                           | 1         | 1.56%   |
| Sierra Wireless                   | 1         | 1.56%   |
| Ralink Technology                 | 1         | 1.56%   |
| ASUSTek Computer                  | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 9.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 9.28%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 5         | 5.15%   |
| Intel Wireless 8260                                                     | 5         | 5.15%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 5.15%   |
| Intel Wireless 7265                                                     | 4         | 4.12%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 4.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 3.09%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 3.09%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.06%   |
| Intel Wireless 7260                                                     | 2         | 2.06%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 2.06%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.03%   |
| Sierra Wireless EM7455                                                  | 1         | 1.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.03%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 1.03%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 1.03%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.03%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 1.03%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 1.03%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.03%   |
| Intel Wireless 3160                                                     | 1         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.03%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.03%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                                    | 1         | 1.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 70.59%  |
| Qualcomm Atheros      | 5         | 9.8%    |
| Realtek Semiconductor | 4         | 7.84%   |
| Broadcom              | 2         | 3.92%   |
| TP-Link               | 1         | 1.96%   |
| Sierra Wireless       | 1         | 1.96%   |
| Ralink Technology     | 1         | 1.96%   |
| ASUSTek Computer      | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 17.31%  |
| Intel Wireless 8260                                                     | 5         | 9.62%   |
| Intel Wireless 7265                                                     | 4         | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 5.77%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.85%   |
| Intel Wireless 7260                                                     | 2         | 3.85%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.92%   |
| Sierra Wireless EM7455                                                  | 1         | 1.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 1.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.92%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.92%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.92%   |
| Intel Wireless 3160                                                     | 1         | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.92%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.92%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.92%   |
| Broadcom BRCM4378 Wireless Network Adapter                              | 1         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.92%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                     | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 27        | 65.85%  |
| Realtek Semiconductor    | 7         | 17.07%  |
| Qualcomm Atheros         | 3         | 7.32%   |
| Marvell Technology Group | 3         | 7.32%   |
| Broadcom                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 21.95%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 12.2%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 12.2%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 9.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 7.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.44%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.44%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 51.09%  |
| Ethernet | 41        | 44.57%  |
| Modem    | 2         | 2.17%   |
| Unknown  | 2         | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 77.08%  |
| Ethernet | 11        | 22.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 81.63%  |
| 1     | 7         | 14.29%  |
| 3     | 1         | 2.04%   |
| 0     | 1         | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 51.52%  |
| Broadcom              | 5         | 15.15%  |
| Alps Electric         | 3         | 9.09%   |
| Realtek Semiconductor | 2         | 6.06%   |
| Foxconn / Hon Hai     | 2         | 6.06%   |
| Taiyo Yuden           | 1         | 3.03%   |
| IMC Networks          | 1         | 3.03%   |
| ASUSTek Computer      | 1         | 3.03%   |
| Apple                 | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 39.39%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 9.09%   |
| Realtek Bluetooth Adapter                                | 2         | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 2         | 6.06%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 6.06%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 6.06%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                  | 1         | 3.03%   |
| Intel AX210 Bluetooth                                    | 1         | 3.03%   |
| Intel AX200 Bluetooth                                    | 1         | 3.03%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 3.03%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 3.03%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 3.03%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1         | 3.03%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 89.13%  |
| AMD    | 5         | 10.87%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 14.55%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 10.91%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 10.91%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 7.27%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 7.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 5.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 5.45%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 5.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 5.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.82%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.82%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.82%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.82%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 35.71%  |
| Unknown             | 6         | 21.43%  |
| SK hynix            | 5         | 17.86%  |
| Unknown             | 3         | 10.71%  |
| Crucial             | 2         | 7.14%   |
| Micron Technology   | 1         | 3.57%   |
| A-DATA Technology   | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 3         | 9.38%   |
| Unknown                                                 | 3         | 9.38%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s        | 2         | 6.25%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 2         | 6.25%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 1333MT/s        | 2         | 6.25%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 3.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 3.13%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 3.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 3.13%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 3.13%   |
| Unknown RAM Module 1GB SODIMM DDR                       | 1         | 3.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 3.13%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 3.13%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 3.13%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 3.13%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 3.13%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 3.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 3.13%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s        | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 3.13%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 3.13%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 3.13%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s    | 1         | 3.13%   |

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
| 4096  | 9         | 31.03%  |
| 2048  | 8         | 27.59%  |
| 8192  | 7         | 24.14%  |
| 1024  | 3         | 10.34%  |
| 16384 | 1         | 3.45%   |
| 512   | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 21.43%  |
| 1334    | 4         | 14.29%  |
| 1333    | 4         | 14.29%  |
| Unknown | 4         | 14.29%  |
| 1067    | 3         | 10.71%  |
| 3200    | 1         | 3.57%   |
| 2667    | 1         | 3.57%   |
| 2133    | 1         | 3.57%   |
| 1867    | 1         | 3.57%   |
| 667     | 1         | 3.57%   |
| 400     | 1         | 3.57%   |
| 266     | 1         | 3.57%   |

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
| Chicony Electronics                    | 12        | 34.29%  |
| Lite-On Technology                     | 5         | 14.29%  |
| Bison Electronics                      | 5         | 14.29%  |
| Tripath Technology                     | 2         | 5.71%   |
| Lenovo                                 | 2         | 5.71%   |
| IMC Networks                           | 2         | 5.71%   |
| SunplusIT                              | 1         | 2.86%   |
| Ricoh                                  | 1         | 2.86%   |
| Realtek Semiconductor                  | 1         | 2.86%   |
| Jiangxi Shinetech Optical              | 1         | 2.86%   |
| Genesys Logic                          | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                                | 4         | 11.43%  |
| Bison Integrated Camera                                  | 3         | 8.57%   |
| Tripath USB Camera                                       | 2         | 5.71%   |
| IMC Networks Integrated Camera                           | 2         | 5.71%   |
| Chicony Integrated Camera [ThinkPad]                     | 2         | 5.71%   |
| Chicony Integrated Camera                                | 2         | 5.71%   |
| SunplusIT USB camera                                     | 1         | 2.86%   |
| Ricoh Laptop_Integrated_Webcam_FHD                       | 1         | 2.86%   |
| Realtek Integrated Webcam HD                             | 1         | 2.86%   |
| Lite-On Realtek DMFT RGB                                 | 1         | 2.86%   |
| Lenovo Integrated Webcam [R5U877]                        | 1         | 2.86%   |
| Lenovo Integrated Webcam                                 | 1         | 2.86%   |
| Jiangxi Shinetech Optical Realtek PC Camera              | 1         | 2.86%   |
| Genesys Logic ASUS USB 2.0 UVC 1.3M WebCam               | 1         | 2.86%   |
| Chicony thinkpad t430s camera                            | 1         | 2.86%   |
| Chicony Sonix ST50220 USB Video Camera                   | 1         | 2.86%   |
| Chicony Ltd., USB 2.0 Camera                             | 1         | 2.86%   |
| Chicony Lenovo Integrated Camera (0.3MP)                 | 1         | 2.86%   |
| Chicony Lenovo EasyCamera                                | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)                  | 1         | 2.86%   |
| Chicony FJ Camera                                        | 1         | 2.86%   |
| Chicony 2.0M UVC Webcam / CNF7129                        | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Realtek PC Camera | 1         | 2.86%   |
| Bison USB HD Webcam                                      | 1         | 2.86%   |
| Bison Lenovo Integrated Webcam                           | 1         | 2.86%   |
| Apple FaceTime Camera                                    | 1         | 2.86%   |

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
| 1     | 31        | 63.27%  |
| 0     | 6         | 12.24%  |
| 2     | 5         | 10.2%   |
| 3     | 4         | 8.16%   |
| 5     | 3         | 6.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 34        | 51.52%  |
| Graphics card            | 9         | 13.64%  |
| Net/wireless             | 5         | 7.58%   |
| Firewire controller      | 5         | 7.58%   |
| Network                  | 4         | 6.06%   |
| Storage/ata              | 3         | 4.55%   |
| Sound                    | 3         | 4.55%   |
| Storage                  | 1         | 1.52%   |
| Modem                    | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |

