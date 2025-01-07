OpenBSD 7.4 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.4.

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

Total: 52

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | G550 20023                  | [cb5ba2b818](https://bsd-hardware.info/?probe=cb5ba2b818) | Jun 01, 2024 |
| Samsung       | 100NZC                      | [2b36397928](https://bsd-hardware.info/?probe=2b36397928) | Apr 03, 2024 |
| Apple         | MacBookAir7,2               | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6e8c7ec804](https://bsd-hardware.info/?probe=6e8c7ec804) | Mar 21, 2024 |
| Google        | Droid                       | [47f0dcc73c](https://bsd-hardware.info/?probe=47f0dcc73c) | Mar 06, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [ba0295b8ea](https://bsd-hardware.info/?probe=ba0295b8ea) | Mar 05, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a716cc542a](https://bsd-hardware.info/?probe=a716cc542a) | Mar 04, 2024 |
| Apple         | MacBookPro12,1              | [736c13e863](https://bsd-hardware.info/?probe=736c13e863) | Feb 25, 2024 |
| Dell          | Latitude E5510              | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Lenovo        | ThinkPad T450 20BU000GUS    | [e1d99a4966](https://bsd-hardware.info/?probe=e1d99a4966) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [5306df5921](https://bsd-hardware.info/?probe=5306df5921) | Feb 12, 2024 |
| Sony          | Unknown                     | [c0013719ab](https://bsd-hardware.info/?probe=c0013719ab) | Feb 12, 2024 |
| Sony          | Unknown                     | [a17ecdd804](https://bsd-hardware.info/?probe=a17ecdd804) | Feb 12, 2024 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | [5b06b87ef0](https://bsd-hardware.info/?probe=5b06b87ef0) | Feb 06, 2024 |
| Panasonic     | CFSX4-1                     | [d998c9373a](https://bsd-hardware.info/?probe=d998c9373a) | Jan 25, 2024 |
| Dell          | Latitude 7320 Detachable    | [d29b86c141](https://bsd-hardware.info/?probe=d29b86c141) | Jan 21, 2024 |
| Dell          | Latitude 7320 Detachable    | [b1f9acd523](https://bsd-hardware.info/?probe=b1f9acd523) | Jan 18, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fcc009f8ba](https://bsd-hardware.info/?probe=fcc009f8ba) | Jan 15, 2024 |
| Panasonic     | CFSX4-1                     | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Apple         | MacBookPro7,1               | [f43cf3565a](https://bsd-hardware.info/?probe=f43cf3565a) | Dec 27, 2023 |
| HP            | ProBook 455 G7              | [11764c4c5e](https://bsd-hardware.info/?probe=11764c4c5e) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Toshiba       | Portable PC                 | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Lenovo        | ThinkPad P70 20ESS1L600     | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| Apple         | MacBookAir7,2               | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Star Labs     | LabTop                      | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| Apple         | MacBookAir4,1               | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Dell          | Latitude 7490               | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| Panasonic     | CFSX4-1                     | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E752               | [ee95b41634](https://bsd-hardware.info/?probe=ee95b41634) | Nov 10, 2023 |
| Panasonic     | CF-54-1                     | [c530bdbd88](https://bsd-hardware.info/?probe=c530bdbd88) | Nov 10, 2023 |
| Panasonic     | CFSX4-1                     | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| IBM           | ThinkPad R51 2889W11        | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Panasonic     | CF-C2CEAZXCM                | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| ASUSTek       | 1000HE                      | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| IBM           | ThinkPad R51 2889W11        | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Panasonic     | CFSX4-1                     | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 33        | 84.62%  |
| i386   | 5         | 12.82%  |
| macppc | 1         | 2.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 80%     |
| XFCE         | 7         | 17.5%   |
| GNOME        | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 39        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 39        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 82.05%  |
| en_US   | 4         | 10.26%  |
| ru_RU   | 1         | 2.56%   |
| pl_PL   | 1         | 2.56%   |
| de_DE   | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 62.5%   |
| BIOS | 15        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 39        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 25        | 62.5%   |
| MBR  | 15        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 14        | 35.9%   |
| Panasonic                      | 5         | 12.82%  |
| Apple                          | 5         | 12.82%  |
| Dell                           | 3         | 7.69%   |
| Matsushita Electric Industrial | 2         | 5.13%   |
| ASUSTek Computer               | 2         | 5.13%   |
| Toshiba                        | 1         | 2.56%   |
| Star Labs                      | 1         | 2.56%   |
| Sony                           | 1         | 2.56%   |
| Samsung Electronics            | 1         | 2.56%   |
| IBM                            | 1         | 2.56%   |
| Hewlett-Packard                | 1         | 2.56%   |
| Google                         | 1         | 2.56%   |
| Fujitsu                        | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Portable PC                         | 1         | 2.56%   |
| Star Labs LabTop                            | 1         | 2.56%   |
| Samsung 100NZC                              | 1         | 2.56%   |
| Panasonic CFSX4-1                           | 1         | 2.56%   |
| Panasonic CF-C2CEAZXCM                      | 1         | 2.56%   |
| Panasonic CF-54-1                           | 1         | 2.56%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.56%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.56%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.56%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.56%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 2.56%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 2.56%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04900    | 1         | 2.56%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 2.56%   |
| Lenovo ThinkPad T450 20BU000GUS             | 1         | 2.56%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.56%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.56%   |
| Lenovo ThinkPad T410 2518C3U                | 1         | 2.56%   |
| Lenovo ThinkPad P70 20ESS1L600              | 1         | 2.56%   |
| Lenovo ThinkPad Helix 2nd 20CHS1QW01        | 1         | 2.56%   |
| Lenovo ThinkPad E15 Gen 2 20TD003GUS        | 1         | 2.56%   |
| Lenovo ThinkBook 15 G4 IAP 21DJ             | 1         | 2.56%   |
| Lenovo G550 20023                           | 1         | 2.56%   |
| IBM ThinkPad R51 2889W11                    | 1         | 2.56%   |
| HP ProBook 455 G7                           | 1         | 2.56%   |
| Google Droid                                | 1         | 2.56%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.56%   |
| Dell Latitude E5510                         | 1         | 2.56%   |
| Dell Latitude 7490                          | 1         | 2.56%   |
| Dell Latitude 7320 Detachable               | 1         | 2.56%   |
| ASUS ASUS TUF Gaming A16 FA617NS_FA617NS    | 1         | 2.56%   |
| ASUS 1000HE                                 | 1         | 2.56%   |
| Apple PowerBook3,5                          | 1         | 2.56%   |
| Apple MacBookPro7,1                         | 1         | 2.56%   |
| Apple MacBookPro12,1                        | 1         | 2.56%   |
| Apple MacBookAir7,2                         | 1         | 2.56%   |
| Apple MacBookAir4,1                         | 1         | 2.56%   |
| Unknown                                     | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 12        | 30.77%  |
| Dell Latitude                               | 3         | 7.69%   |
| Toshiba Portable                            | 1         | 2.56%   |
| Star Labs LabTop                            | 1         | 2.56%   |
| Samsung 100NZC                              | 1         | 2.56%   |
| Panasonic CFSX4-1                           | 1         | 2.56%   |
| Panasonic CF-C2CEAZXCM                      | 1         | 2.56%   |
| Panasonic CF-54-1                           | 1         | 2.56%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.56%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.56%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.56%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.56%   |
| Lenovo ThinkBook                            | 1         | 2.56%   |
| Lenovo G550                                 | 1         | 2.56%   |
| IBM ThinkPad                                | 1         | 2.56%   |
| HP ProBook                                  | 1         | 2.56%   |
| Google Droid                                | 1         | 2.56%   |
| Fujitsu LIFEBOOK                            | 1         | 2.56%   |
| ASUS ASUS                                   | 1         | 2.56%   |
| ASUS 1000HE                                 | 1         | 2.56%   |
| Apple PowerBook3                            | 1         | 2.56%   |
| Apple MacBookPro7                           | 1         | 2.56%   |
| Apple MacBookPro12                          | 1         | 2.56%   |
| Apple MacBookAir7                           | 1         | 2.56%   |
| Apple MacBookAir4                           | 1         | 2.56%   |
| Unknown                                     | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 12.82%  |
| 2023    | 4         | 10.26%  |
| 2020    | 4         | 10.26%  |
| 2015    | 4         | 10.26%  |
| 2019    | 3         | 7.69%   |
| 2017    | 2         | 5.13%   |
| 2016    | 2         | 5.13%   |
| 2012    | 2         | 5.13%   |
| 2011    | 2         | 5.13%   |
| 2005    | 2         | 5.13%   |
| 2022    | 1         | 2.56%   |
| 2021    | 1         | 2.56%   |
| 2014    | 1         | 2.56%   |
| 2013    | 1         | 2.56%   |
| 2009    | 1         | 2.56%   |
| 2007    | 1         | 2.56%   |
| 2006    | 1         | 2.56%   |
| 2002    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 97.44%  |
| Yes  | 1         | 2.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 17        | 43.59%  |
| 16.01-24.0 | 6         | 15.38%  |
| 3.01-4.0   | 5         | 12.82%  |
| 4.01-8.0   | 3         | 7.69%   |
| 2.01-3.0   | 2         | 5.13%   |
| 1.01-2.0   | 2         | 5.13%   |
| 0.51-1.0   | 2         | 5.13%   |
| 32.01-64.0 | 1         | 2.56%   |
| 0.01-0.5   | 1         | 2.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 34        | 87.18%  |
| 0        | 4         | 10.26%  |
| 0.51-1.0 | 1         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 72.5%   |
| 2      | 10        | 25%     |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 79.49%  |
| No        | 8         | 20.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 92.31%  |
| No        | 3         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 67.5%   |
| No        | 13        | 32.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Canada    | 16        | 41.03%  |
| USA       | 9         | 23.08%  |
| Russia    | 3         | 7.69%   |
| Germany   | 2         | 5.13%   |
| UK        | 1         | 2.56%   |
| Spain     | 1         | 2.56%   |
| Slovakia  | 1         | 2.56%   |
| Romania   | 1         | 2.56%   |
| Poland    | 1         | 2.56%   |
| Indonesia | 1         | 2.56%   |
| Hungary   | 1         | 2.56%   |
| Guatemala | 1         | 2.56%   |
| Greece    | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Saint-Laurent   | 9         | 21.95%  |
| Montreal        | 5         | 12.2%   |
| Sun Prairie     | 3         | 7.32%   |
| Warwick         | 1         | 2.44%   |
| Uba             | 1         | 2.44%   |
| Torrent         | 1         | 2.44%   |
| Sydenham        | 1         | 2.44%   |
| Stuttgart       | 1         | 2.44%   |
| Stukenbrock     | 1         | 2.44%   |
| South Tangerang | 1         | 2.44%   |
| Smolensk        | 1         | 2.44%   |
| Ryazan          | 1         | 2.44%   |
| Quetzaltenango  | 1         | 2.44%   |
| Punta Gorda     | 1         | 2.44%   |
| Madison         | 1         | 2.44%   |
| Krakow          | 1         | 2.44%   |
| Košice         | 1         | 2.44%   |
| Kernersville    | 1         | 2.44%   |
| Hollis          | 1         | 2.44%   |
| Harrisonburg    | 1         | 2.44%   |
| Fresno          | 1         | 2.44%   |
| Delavan         | 1         | 2.44%   |
| Clapham         | 1         | 2.44%   |
| Caransebes      | 1         | 2.44%   |
| Budapest        | 1         | 2.44%   |
| Boynton Beach   | 1         | 2.44%   |
| Athens          | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 21.43%  |
| NVMe                | 9         | 10     | 21.43%  |
| Kingston            | 3         | 3      | 7.14%   |
| Apple               | 3         | 4      | 7.14%   |
| Seagate             | 2         | 2      | 4.76%   |
| SanDisk             | 2         | 2      | 4.76%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| Apacer              | 2         | 2      | 4.76%   |
| PNY                 | 1         | 5      | 2.38%   |
| MyDigitalSSD        | 1         | 1      | 2.38%   |
| Lexar               | 1         | 1      | 2.38%   |
| Hitachi             | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |
| Generic             | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |
| A-DATA Technology   | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 2.33%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 2.33%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 2.33%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 2.33%   |
| WDC WD3200LPCX-24C6HT0 320GB        | 1         | 2.33%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 2.33%   |
| WDC WD2500BEKT-75A25T0 250GB        | 1         | 2.33%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 2.33%   |
| WDC WD Elements 2621 2TB            | 1         | 2.33%   |
| Seagate ST9160821A 160GB            | 1         | 2.33%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 2.33%   |
| SanDisk SDCFXS-032G                 | 1         | 2.33%   |
| SanDisk SD8SN8U-256G-1006 256GB     | 1         | 2.33%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 2.33%   |
| Samsung SSD 860 EVO 1TB             | 1         | 2.33%   |
| PNY CS900 1TB SSD                   | 1         | 2.33%   |
| NVMe WDC PC SN530 SDB 1TB           | 1         | 2.33%   |
| NVMe WD Blue SN580 1T               | 1         | 2.33%   |
| NVMe UMIS RPEYJ1T24MK 1TB           | 1         | 2.33%   |
| NVMe Star Drive PCIe 480GB          | 1         | 2.33%   |
| NVMe SAMSUNG MZVLW256 256GB         | 1         | 2.33%   |
| NVMe SAMSUNG MZVLQ256 256GB         | 1         | 2.33%   |
| NVMe SAMSUNG MZVLB512 512GB         | 1         | 2.33%   |
| NVMe SAMSUNG MZALQ512 512GB         | 1         | 2.33%   |
| NVMe KINGSTON SNV2S50 500GB         | 1         | 2.33%   |
| NVMe CL1-3D256-Q11 NV 256GB         | 1         | 2.33%   |
| MyDigitalSSD SB2 240GB              | 1         | 2.33%   |
| Lexar 128GB SSD                     | 1         | 2.33%   |
| Kingston SA400S37480G 480GB         | 1         | 2.33%   |
| Kingston SA400S37240G 240GB         | 1         | 2.33%   |
| Kingston SA400S37120G 120GB         | 1         | 2.33%   |
| Intel SSDSCKJF240A5L 240GB          | 1         | 2.33%   |
| Intel SSDSC2BF180A5L 180GB          | 1         | 2.33%   |
| Hitachi HTS545025B9SA02 250GB       | 1         | 2.33%   |
| HGST HTS541010A9E680 1TB            | 1         | 2.33%   |
| Generic STORAGE DEVICE 2GB          | 1         | 2.33%   |
| Fujitsu MHS2060AT 64GB              | 1         | 2.33%   |
| Apple SSD SM256C 256GB              | 1         | 2.33%   |
| Apple SSD SM0256G 256GB             | 1         | 2.33%   |
| Apple SSD SM0128G 121GB             | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 9      | 37.5%   |
| NVMe    | 9         | 10     | 37.5%   |
| Seagate | 2         | 2      | 8.33%   |
| Hitachi | 1         | 1      | 4.17%   |
| HGST    | 1         | 1      | 4.17%   |
| Generic | 1         | 1      | 4.17%   |
| Fujitsu | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 16.67%  |
| Apple               | 3         | 4      | 16.67%  |
| SanDisk             | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| Apacer              | 2         | 2      | 11.11%  |
| PNY                 | 1         | 5      | 5.56%   |
| MyDigitalSSD        | 1         | 1      | 5.56%   |
| Lexar               | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 25     | 57.5%   |
| SSD  | 17        | 23     | 42.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 48     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 65.85%  |
| 0.51-1.0   | 11        | 15     | 26.83%  |
| 1.01-2.0   | 3         | 3      | 7.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 21-50      | 13        | 33.33%  |
| 101-250    | 11        | 28.21%  |
| 251-500    | 9         | 23.08%  |
| 51-100     | 4         | 10.26%  |
| 1-20       | 1         | 2.56%   |
| 501-1000   | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 34        | 82.93%  |
| 101-250  | 3         | 7.32%   |
| 21-50    | 2         | 4.88%   |
| 251-500  | 1         | 2.44%   |
| 501-1000 | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Intel SSDSCKJF240A5L 240GB    | 1         | 1      | 25%     |
| Intel SSDSC2BF180A5L 180GB    | 1         | 1      | 25%     |
| HGST HTS541010A9E680 1TB      | 1         | 1      | 25%     |
| A-DATA Technology SP550 480GB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Intel             | 2         | 2      | 50%     |
| HGST              | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 75%     |
| HDD  | 1         | 1      | 25%     |

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
| Works    | 26        | 32     | 65%     |
| Detected | 10        | 12     | 25%     |
| Malfunc  | 4         | 4      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 27        | 67.5%   |
| Samsung Electronics                     | 6         | 15%     |
| Solid State Storage Technology          | 1         | 2.5%    |
| Shenzhen Unionmemory Information System | 1         | 2.5%    |
| SanDisk                                 | 1         | 2.5%    |
| Phison Electronics                      | 1         | 2.5%    |
| Nvidia                                  | 1         | 2.5%    |
| Kingston Technology Company             | 1         | 2.5%    |
| AMD                                     | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                            | 5         | 11.9%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                            | 4         | 9.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                | 3         | 7.14%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                    | 2         | 4.76%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                   | 2         | 4.76%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                                 | 2         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                              | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                  | 2         | 4.76%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                                | 1         | 2.38%   |
| Shenzhen Unionmemory Information System RPEYJ1T24MKN2QWY PCIe 4.0 NVMe SSD 1024GB (DRAM-less) | 1         | 2.38%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                                    | 1         | 2.38%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                     | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                 | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                 | 1         | 2.38%   |
| Phison E12 NVMe Controller                                                                    | 1         | 2.38%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                      | 1         | 2.38%   |
| Kingston Company NV2 NVMe SSD [E19T] (DRAM-less)                                              | 1         | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                 | 1         | 2.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                             | 1         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                         | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                 | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                              | 1         | 2.38%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                        | 1         | 2.38%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                        | 1         | 2.38%   |
| Intel 82801CAM IDE U100 Controller                                                            | 1         | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                  | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                | 1         | 2.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                           | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 25        | 60.98%  |
| NVMe | 9         | 21.95%  |
| IDE  | 7         | 17.07%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 36        | 92.31%  |
| AMD     | 2         | 5.13%   |
| Unknown | 1         | 2.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                            | 4         | 10.26%  |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 3         | 7.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 2         | 5.13%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                         | 1         | 2.56%   |
| Intel Pentium M processor 1.73GHz ("GenuineIntel" 686-class) | 1         | 2.56%   |
| Intel Pentium M processor                                    | 1         | 2.56%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                           | 1         | 2.56%   |
| Intel Other                                                  | 1         | 2.56%   |
| Intel Genuine CPU T2300 @ 1.66GHz                            | 1         | 2.56%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                              | 1         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 1         | 2.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 1         | 2.56%   |
| Intel Core i7-2677M CPU @ 1.80GHz                            | 1         | 2.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz                            | 1         | 2.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz                            | 1         | 2.56%   |
| Intel Core i5-5350U CPU @ 1.80GHz                            | 1         | 2.56%   |
| Intel Core i5-5257U CPU @ 2.70GHz                            | 1         | 2.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz                            | 1         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 1         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz                            | 1         | 2.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                            | 1         | 2.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz                            | 1         | 2.56%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                         | 1         | 2.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                         | 1         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz                            | 1         | 2.56%   |
| Intel Atom CPU N280 @ 1.66GHz                                | 1         | 2.56%   |
| Intel Atom CPU N2100 @ 1.60GHz                               | 1         | 2.56%   |
| Intel 12th Gen Core i7-1260P                                 | 1         | 2.56%   |
| Intel 11th Gen Core i7-1180G7 @ 1.30GHz                      | 1         | 2.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                      | 1         | 2.56%   |
| AMD Ryzen 7 7735HS with Radeon Graphics                      | 1         | 2.56%   |
| AMD Ryzen 5 4500U with Radeon Graphics                       | 1         | 2.56%   |
|                                                              | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 17        | 43.59%  |
| Other            | 5         | 12.82%  |
| Intel Core i7    | 3         | 7.69%   |
| Intel Pentium M  | 2         | 5.13%   |
| Intel Core 2 Duo | 2         | 5.13%   |
| Intel Atom       | 2         | 5.13%   |
| Intel Xeon       | 1         | 2.56%   |
| Intel Pentium 4  | 1         | 2.56%   |
| Intel Genuine    | 1         | 2.56%   |
| Intel Core M     | 1         | 2.56%   |
| Intel Core i3    | 1         | 2.56%   |
| Intel Celeron    | 1         | 2.56%   |
| AMD Ryzen 7      | 1         | 2.56%   |
| AMD Ryzen 5      | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 21        | 53.85%  |
| Unknown | 7         | 17.95%  |
| 4       | 5         | 12.82%  |
| 1       | 3         | 7.69%   |
| 16      | 1         | 2.56%   |
| 8       | 1         | 2.56%   |
| 6       | 1         | 2.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 34        | 87.18%  |
| Unknown | 5         | 12.82%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 66.67%  |
| Unknown | 10        | 25.64%  |
| 1       | 3         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Broadwell     | 6         | 15.38%  |
| Skylake       | 5         | 12.82%  |
| Westmere      | 4         | 10.26%  |
| P6            | 3         | 7.69%   |
| KabyLake      | 3         | 7.69%   |
| Unknown       | 3         | 7.69%   |
| TigerLake     | 2         | 5.13%   |
| SandyBridge   | 2         | 5.13%   |
| Penryn        | 2         | 5.13%   |
| IvyBridge     | 2         | 5.13%   |
| Bonnell       | 2         | 5.13%   |
| Zen 2         | 1         | 2.56%   |
| NetBurst      | 1         | 2.56%   |
| Haswell       | 1         | 2.56%   |
| Goldmont plus | 1         | 2.56%   |
| Core          | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 82.5%   |
| AMD    | 4         | 10%     |
| Nvidia | 3         | 7.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 9.09%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 9.09%   |
| Intel HD Graphics 5500                                                        | 3         | 6.82%   |
| Intel UHD Graphics 620                                                        | 2         | 4.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 4.55%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 2.27%   |
| Nvidia GT218M [GeForce G210M]                                                 | 1         | 2.27%   |
| Nvidia GM107GLM [Quadro M600M]                                                | 1         | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.27%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                   | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2.27%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 2.27%   |
| Intel Iris Graphics 6100                                                      | 1         | 2.27%   |
| Intel HD Graphics P530                                                        | 1         | 2.27%   |
| Intel HD Graphics 620                                                         | 1         | 2.27%   |
| Intel HD Graphics 6000                                                        | 1         | 2.27%   |
| Intel HD Graphics 5300                                                        | 1         | 2.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.27%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.27%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 2.27%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 2.27%   |
| AMD RV250/M9 GL [Mobility FireGL 9000/Radeon 9000]                            | 1         | 2.27%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.27%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 1         | 2.27%   |
| AMD Rembrandt [Radeon 680M]                                                   | 1         | 2.27%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]         | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 71.79%  |
| 2 x Intel      | 4         | 10.26%  |
| 1 x AMD        | 3         | 7.69%   |
| 1 x Nvidia     | 2         | 5.13%   |
| 2 x AMD        | 1         | 2.56%   |
| Intel + Nvidia | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 36        | 92.31%  |
| Unknown | 3         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 6         | 24%     |
| AU Optronics        | 5         | 20%     |
| Apple               | 4         | 16%     |
| BOE                 | 3         | 12%     |
| Sharp               | 2         | 8%      |
| Chimei Innolux      | 2         | 8%      |
| Samsung Electronics | 1         | 4%      |
| Philips             | 1         | 4%      |
| Panasonic           | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LQ133M1JW08 SHP1425 1920x1080 290x170mm 13.2-inch              | 1         | 4%      |
| Sharp LCD Monitor SHP1526 1920x1280 270x180mm 12.8-inch              | 1         | 4%      |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 4%      |
| Philips PHL 240B9 PHL0966 1920x1200 520x320mm 24.0-inch              | 1         | 4%      |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 4%      |
| LG Display LCD Monitor LGD05A2 1920x1080 310x170mm 13.9-inch         | 1         | 4%      |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD0404 1366x768 280x160mm 12.7-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 4%      |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch         | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1520 1920x1080 340x190mm 15.3-inch     | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 4%      |
| BOE NE160WUM-NX2 BOE0B33 1920x1200 340x210mm 15.7-inch               | 1         | 4%      |
| BOE LCD Monitor BOE08C2 1920x1080 340x190mm 15.3-inch                | 1         | 4%      |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                 | 1         | 4%      |
| AU Optronics LCD Monitor AUO335D 1920x1080 260x140mm 11.6-inch       | 1         | 4%      |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 4%      |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch        | 1         | 4%      |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 4%      |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 1         | 4%      |
| Apple Color LCD APPA02A 2560x1600 290x180mm 13.4-inch                | 1         | 4%      |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 4%      |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 4%      |
| Apple Color LCD APP9C21 1280x854 320x220mm 15.3-inch                 | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 44%     |
| 1366x768 (WXGA)   | 7         | 28%     |
| 1920x1200 (WUXGA) | 2         | 8%      |
| 3840x2160 (4K)    | 1         | 4%      |
| 2560x1600         | 1         | 4%      |
| 1920x1280         | 1         | 4%      |
| 1440x900 (WXGA+)  | 1         | 4%      |
| 1280x854          | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 36%     |
| 15     | 8         | 32%     |
| 12     | 4         | 16%     |
| 11     | 2         | 8%      |
| 24     | 1         | 4%      |
| 17     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 56%     |
| 201-300     | 9         | 36%     |
| 501-600     | 1         | 4%      |
| 351-400     | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 76%     |
| 16/10 | 4         | 16%     |
| 3/2   | 2         | 8%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 32%     |
| 91-100         | 4         | 16%     |
| 61-70          | 3         | 12%     |
| 101-110        | 3         | 12%     |
| 71-80          | 2         | 8%      |
| 51-60          | 2         | 8%      |
| 251-300        | 1         | 4%      |
| 121-130        | 1         | 4%      |
| 111-120        | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 52%     |
| 161-240       | 5         | 20%     |
| 101-120       | 4         | 16%     |
| 51-100        | 2         | 8%      |
| More than 240 | 1         | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 92.31%  |
| 0     | 2         | 5.13%   |
| 2     | 1         | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 29        | 58%     |
| Realtek Semiconductor    | 9         | 18%     |
| Broadcom                 | 6         | 12%     |
| Sierra Wireless          | 2         | 4%      |
| Qualcomm Atheros         | 2         | 4%      |
| Marvell Technology Group | 1         | 2%      |
| Apple                    | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                    | 5         | 6.85%   |
| Intel Wireless 7265                                                    | 4         | 5.48%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 5.48%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3         | 4.11%   |
| Intel Wireless 8265 / 8275                                             | 3         | 4.11%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 4.11%   |
| Intel Centrino Advanced-N 6200                                         | 3         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 4.11%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 4.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 2.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 2.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 2.74%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 2.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 2.74%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.74%   |
| Sierra Wireless EM7455                                                 | 1         | 1.37%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 1.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1         | 1.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1         | 1.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 1.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.37%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.37%   |
| Intel Wireless 7260                                                    | 1         | 1.37%   |
| Intel Wi-Fi 6 AX200                                                    | 1         | 1.37%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                        | 1         | 1.37%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 1         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1         | 1.37%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.37%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.37%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                   | 1         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller      | 1         | 1.37%   |
| Intel 82566MC Gigabit Network Connection                               | 1         | 1.37%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.37%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.37%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.37%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 73.68%  |
| Realtek Semiconductor | 4         | 10.53%  |
| Broadcom              | 3         | 7.89%   |
| Qualcomm Atheros      | 2         | 5.26%   |
| Sierra Wireless       | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 12.82%  |
| Intel Wireless 7265                                            | 4         | 10.26%  |
| Intel Wireless 8265 / 8275                                     | 3         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 7.69%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 7.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 5.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 5.13%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 5.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 5.13%   |
| Sierra Wireless EM7455                                         | 1         | 2.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.56%   |
| Intel Wireless 7260                                            | 1         | 2.56%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.56%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                | 1         | 2.56%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 1         | 2.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2.56%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]           | 1         | 2.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 2.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 2.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 64.52%  |
| Realtek Semiconductor    | 6         | 19.35%  |
| Broadcom                 | 3         | 9.68%   |
| Qualcomm Atheros         | 1         | 3.23%   |
| Marvell Technology Group | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Intel Ethernet Connection I219-LM                                      | 4         | 12.9%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3         | 9.68%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 9.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 9.68%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 9.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 6.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 6.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 3.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 3.23%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.23%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 3.23%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 3.23%   |
| Intel 82566MC Gigabit Network Connection                               | 1         | 3.23%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 3.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 3.23%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 3.23%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 51.43%  |
| Ethernet | 31        | 44.29%  |
| Unknown  | 2         | 2.86%   |
| Modem    | 1         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 68.89%  |
| Ethernet | 14        | 31.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 71.79%  |
| 1     | 11        | 28.21%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 97.44%  |
| Yes  | 1         | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 55.56%  |
| Apple                           | 4         | 14.81%  |
| Alps Electric                   | 2         | 7.41%   |
| Realtek Semiconductor           | 1         | 3.7%    |
| Qualcomm Atheros Communications | 1         | 3.7%    |
| IMC Networks                    | 1         | 3.7%    |
| Foxconn / Hon Hai               | 1         | 3.7%    |
| Dell                            | 1         | 3.7%    |
| ASUSTek Computer                | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 11        | 40.74%  |
| Intel AX201 Bluetooth                                    | 2         | 7.41%   |
| Apple Bluetooth Host Controller                          | 2         | 7.41%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 7.41%   |
| Realtek Bluetooth Adapter                                | 1         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 3.7%    |
| Intel AX200 Bluetooth                                    | 1         | 3.7%    |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 3.7%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 3.7%    |
| Dell DW375 Bluetooth Module                              | 1         | 3.7%    |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1         | 3.7%    |
| Apple Broadcom Built-in Bluetooth                        | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 89.74%  |
| Nvidia | 2         | 5.13%   |
| AMD    | 2         | 5.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 14.58%  |
| Intel Broadwell-U Audio Controller                                         | 6         | 12.5%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 10.42%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 8.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 6.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.17%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 2         | 4.17%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.08%   |
| Nvidia High Definition Audio Controller                                    | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 2.08%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 2.08%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.08%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 35%     |
| Unknown             | 5         | 25%     |
| SK hynix            | 4         | 20%     |
| Unknown             | 2         | 10%     |
| Micron Technology   | 1         | 5%      |
| Elpida              | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s  | 2         | 9.09%   |
| Unknown                                                | 2         | 9.09%   |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 4.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 4.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 4.55%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 4.55%   |
| Unknown RAM Module 1GB SODIMM DDR                      | 1         | 4.55%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s  | 1         | 4.55%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 4.55%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 4.55%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s | 1         | 4.55%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s   | 1         | 4.55%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.55%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 1         | 4.55%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 4.55%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s | 1         | 4.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 1         | 4.55%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s  | 1         | 4.55%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s  | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 41.18%  |
| DDR4   | 4         | 23.53%  |
| SDRAM  | 2         | 11.76%  |
| DDR2   | 2         | 11.76%  |
| LPDDR3 | 1         | 5.88%   |
| DDR    | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 94.44%  |
| Chip   | 1         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 5         | 27.78%  |
| 2048  | 5         | 27.78%  |
| 4096  | 4         | 22.22%  |
| 1024  | 2         | 11.11%  |
| 16384 | 1         | 5.56%   |
| 512   | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4         | 23.53%  |
| 2133    | 2         | 11.76%  |
| 1600    | 2         | 11.76%  |
| 1333    | 2         | 11.76%  |
| 1067    | 2         | 11.76%  |
| 2667    | 1         | 5.88%   |
| 2400    | 1         | 5.88%   |
| 1867    | 1         | 5.88%   |
| 1334    | 1         | 5.88%   |
| 667     | 1         | 5.88%   |

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


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Chicony Electronics              | 6         | 25%     |
| Bison Electronics                | 6         | 25%     |
| Lite-On Technology               | 3         | 12.5%   |
| Silicon Motion                   | 2         | 8.33%   |
| Z-Star Microelectronics          | 1         | 4.17%   |
| Sunplus Innovation Technology    | 1         | 4.17%   |
| Shenzhen Kingcome Optoelectronic | 1         | 4.17%   |
| Realtek Semiconductor            | 1         | 4.17%   |
| Quanta                           | 1         | 4.17%   |
| IMC Networks                     | 1         | 4.17%   |
| Apple                            | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 4         | 16.67%  |
| Bison Integrated Camera                               | 4         | 16.67%  |
| Lite-On Integrated Camera                             | 3         | 12.5%   |
| Bison USB HD Webcam                                   | 2         | 8.33%   |
| Z-Star Visual Communication Camera VGP-VCC1           | 1         | 4.17%   |
| Sunplus HP HD Camera                                  | 1         | 4.17%   |
| Silicon Motion WebCam SC-03FFL11939N                  | 1         | 4.17%   |
| Silicon Motion Lenovo EasyCamera                      | 1         | 4.17%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 4.17%   |
| Realtek Integrated Webcam HD                          | 1         | 4.17%   |
| Quanta HP Universal Camera                            | 1         | 4.17%   |
| IMC Networks Integrated Camera                        | 1         | 4.17%   |
| Chicony FJ Camera                                     | 1         | 4.17%   |
| Chicony 2.0M UVC Webcam / CNF7129                     | 1         | 4.17%   |
| Apple FaceTime Camera                                 | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 5         | 62.5%   |
| Synaptics          | 1         | 12.5%   |
| STMicroelectronics | 1         | 12.5%   |
| AuthenTec          | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 25%     |
| Validity Sensors Synaptics WBDI                          | 1         | 12.5%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 12.5%   |
| AuthenTec AES2660                                        | 1         | 12.5%   |

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
| 1     | 21        | 52.5%   |
| 2     | 12        | 30%     |
| 0     | 3         | 7.5%    |
| 5     | 2         | 5%      |
| 4     | 1         | 2.5%    |
| 3     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 26        | 46.43%  |
| Firewire controller      | 8         | 14.29%  |
| Graphics card            | 7         | 12.5%   |
| Net/wireless             | 5         | 8.93%   |
| Network                  | 3         | 5.36%   |
| Storage/ata              | 2         | 3.57%   |
| Storage                  | 2         | 3.57%   |
| Sound                    | 2         | 3.57%   |
| Modem                    | 1         | 1.79%   |

