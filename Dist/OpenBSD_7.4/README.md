OpenBSD 7.4 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.4/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.4/Notebook/README.md).

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

Total: 87

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| FUJI wortm... | D1547                       | Desktop     | [b0c75a2f48](https://bsd-hardware.info/?probe=b0c75a2f48) | Jul 01, 2024 |
| Lenovo        | G550 20023                  | Notebook    | [cb5ba2b818](https://bsd-hardware.info/?probe=cb5ba2b818) | Jun 01, 2024 |
| Samsung       | 100NZC                      | Notebook    | [2b36397928](https://bsd-hardware.info/?probe=2b36397928) | Apr 03, 2024 |
| Dell          | Vostro 3268                 | Desktop     | [3492b3ebb5](https://bsd-hardware.info/?probe=3492b3ebb5) | Mar 31, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | Desktop     | [feb3803dbc](https://bsd-hardware.info/?probe=feb3803dbc) | Mar 24, 2024 |
| Dell          | Inspiron 5521               | Desktop     | [15446ac441](https://bsd-hardware.info/?probe=15446ac441) | Mar 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6e8c7ec804](https://bsd-hardware.info/?probe=6e8c7ec804) | Mar 21, 2024 |
| Sun           | SUNW,Ultra-1                | Desktop     | [33ed69952b](https://bsd-hardware.info/?probe=33ed69952b) | Mar 17, 2024 |
| HP            | ProLiant ML370 G4           | Desktop     | [e3d8ea32d4](https://bsd-hardware.info/?probe=e3d8ea32d4) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [9015dcf1b5](https://bsd-hardware.info/?probe=9015dcf1b5) | Mar 12, 2024 |
| Lenovo        | ThinkCentre M75n 11BXS00... | Desktop     | [6ed6f9c86f](https://bsd-hardware.info/?probe=6ed6f9c86f) | Mar 09, 2024 |
| Google        | Droid                       | Notebook    | [47f0dcc73c](https://bsd-hardware.info/?probe=47f0dcc73c) | Mar 06, 2024 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | Notebook    | [ba0295b8ea](https://bsd-hardware.info/?probe=ba0295b8ea) | Mar 05, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a716cc542a](https://bsd-hardware.info/?probe=a716cc542a) | Mar 04, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [736c13e863](https://bsd-hardware.info/?probe=736c13e863) | Feb 25, 2024 |
| Intel(R) C... | NUC10i3FNH                  | Mini pc     | [924461c416](https://bsd-hardware.info/?probe=924461c416) | Feb 22, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [cf452e34d1](https://bsd-hardware.info/?probe=cf452e34d1) | Feb 20, 2024 |
| Dell          | Latitude E5510              | Notebook    | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | Notebook    | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Biostar       | B450NH                      | Desktop     | [9f4dedfcd6](https://bsd-hardware.info/?probe=9f4dedfcd6) | Feb 17, 2024 |
| Lenovo        | ThinkPad T450 20BU000GUS    | Notebook    | [e1d99a4966](https://bsd-hardware.info/?probe=e1d99a4966) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [5306df5921](https://bsd-hardware.info/?probe=5306df5921) | Feb 12, 2024 |
| Sony          | Unknown                     | Notebook    | [c0013719ab](https://bsd-hardware.info/?probe=c0013719ab) | Feb 12, 2024 |
| Sony          | Unknown                     | Notebook    | [a17ecdd804](https://bsd-hardware.info/?probe=a17ecdd804) | Feb 12, 2024 |
| Lenovo        | ThinkCentre M91p 7052C1G    | Desktop     | [3aeb926332](https://bsd-hardware.info/?probe=3aeb926332) | Feb 08, 2024 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Notebook    | [5b06b87ef0](https://bsd-hardware.info/?probe=5b06b87ef0) | Feb 06, 2024 |
| MSI           | MS-7D15                     | Desktop     | [a22ee27a4a](https://bsd-hardware.info/?probe=a22ee27a4a) | Feb 03, 2024 |
| MSI           | MS-7D15                     | Desktop     | [476be56dc7](https://bsd-hardware.info/?probe=476be56dc7) | Feb 03, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [f6f19ac329](https://bsd-hardware.info/?probe=f6f19ac329) | Feb 02, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [b2ecf149ab](https://bsd-hardware.info/?probe=b2ecf149ab) | Jan 31, 2024 |
| AZW           | MINI S                      | Desktop     | [99c79c2cc8](https://bsd-hardware.info/?probe=99c79c2cc8) | Jan 30, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [d998c9373a](https://bsd-hardware.info/?probe=d998c9373a) | Jan 25, 2024 |
| Dell          | Latitude 7320 Detachable    | Notebook    | [d29b86c141](https://bsd-hardware.info/?probe=d29b86c141) | Jan 21, 2024 |
| IBM           | 830381U                     | Desktop     | [e44647b8cd](https://bsd-hardware.info/?probe=e44647b8cd) | Jan 20, 2024 |
| Microsoft     | Windows Dev Kit 2023        | Desktop     | [2cd25bfacf](https://bsd-hardware.info/?probe=2cd25bfacf) | Jan 19, 2024 |
| HP            | s5-1210br                   | Desktop     | [9ce94bc2b7](https://bsd-hardware.info/?probe=9ce94bc2b7) | Jan 19, 2024 |
| Dell          | Latitude 7320 Detachable    | Notebook    | [b1f9acd523](https://bsd-hardware.info/?probe=b1f9acd523) | Jan 18, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fcc009f8ba](https://bsd-hardware.info/?probe=fcc009f8ba) | Jan 15, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f43cf3565a](https://bsd-hardware.info/?probe=f43cf3565a) | Dec 27, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [11764c4c5e](https://bsd-hardware.info/?probe=11764c4c5e) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | Notebook    | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Toshiba       | Portable PC                 | Notebook    | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Lenovo        | ThinkPad P70 20ESS1L600     | Notebook    | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Star Labs     | LabTop                      | Notebook    | [e8dcf01d78](https://bsd-hardware.info/?probe=e8dcf01d78) | Dec 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | Desktop     | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | Desktop     | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | Desktop     | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| HP            | Compaq CQ45                 | Desktop     | [4f3c176253](https://bsd-hardware.info/?probe=4f3c176253) | Nov 14, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [de988c2e66](https://bsd-hardware.info/?probe=de988c2e66) | Nov 14, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [ee95b41634](https://bsd-hardware.info/?probe=ee95b41634) | Nov 10, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [c530bdbd88](https://bsd-hardware.info/?probe=c530bdbd88) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [e2a506d1b7](https://bsd-hardware.info/?probe=e2a506d1b7) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| ASUSTek       | MINIPC PN53-G               | Desktop     | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Dell          | PowerEdge T110 II           | Desktop     | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | Desktop     | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Panasonic     | CF-C2CEAZXCM                | Notebook    | [a871fb0596](https://bsd-hardware.info/?probe=a871fb0596) | Oct 27, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| MECHREVO      | Unknown                     | Desktop     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 60        | 83.33%  |
| i386    | 6         | 8.33%   |
| arm64   | 3         | 4.17%   |
| sparc64 | 2         | 2.78%   |
| macppc  | 1         | 1.39%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 58        | 79.45%  |
| XFCE         | 13        | 17.81%  |
| GNOME        | 2         | 2.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 60        | 83.33%  |
| Console | 12        | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 72        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 84.72%  |
| en_US   | 5         | 6.94%   |
| pl_PL   | 2         | 2.78%   |
| ru_RU   | 1         | 1.39%   |
| fr_FR   | 1         | 1.39%   |
| es_CO   | 1         | 1.39%   |
| de_DE   | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 71.23%  |
| BIOS | 21        | 28.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 72        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 48        | 65.75%  |
| MBR  | 25        | 34.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 18        | 25%     |
| Dell                           | 6         | 8.33%   |
| ASUSTek Computer               | 6         | 8.33%   |
| Apple                          | 6         | 8.33%   |
| Panasonic                      | 5         | 6.94%   |
| Hewlett-Packard                | 4         | 5.56%   |
| Unknown                        | 3         | 4.17%   |
| Sun                            | 2         | 2.78%   |
| Matsushita Electric Industrial | 2         | 2.78%   |
| Intel                          | 2         | 2.78%   |
| Gigabyte Technology            | 2         | 2.78%   |
| AZW                            | 2         | 2.78%   |
| Toshiba                        | 1         | 1.39%   |
| Star Labs                      | 1         | 1.39%   |
| Sony                           | 1         | 1.39%   |
| Samsung Electronics            | 1         | 1.39%   |
| MSI                            | 1         | 1.39%   |
| Microsoft                      | 1         | 1.39%   |
| MECHREVO                       | 1         | 1.39%   |
| Intel(R) Client Systems        | 1         | 1.39%   |
| IBM                            | 1         | 1.39%   |
| Google                         | 1         | 1.39%   |
| Fujitsu                        | 1         | 1.39%   |
| FUJI wortmann                  | 1         | 1.39%   |
| Chuwi                          | 1         | 1.39%   |
| Biostar                        | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 5         | 6.94%   |
| Toshiba Portable PC                         | 1         | 1.39%   |
| Sun SUNW,Ultra-1                            | 1         | 1.39%   |
| Sun SUNW,SPARC-Enterprise-T5120             | 1         | 1.39%   |
| Star Labs LabTop                            | 1         | 1.39%   |
| Samsung 100NZC                              | 1         | 1.39%   |
| Panasonic CFSX4-1                           | 1         | 1.39%   |
| Panasonic CF-C2CEAZXCM                      | 1         | 1.39%   |
| Panasonic CF-54-1                           | 1         | 1.39%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.39%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.39%   |
| MSI MS-7D15                                 | 1         | 1.39%   |
| Microsoft Windows Dev Kit 2023              | 1         | 1.39%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.39%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.39%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 1.39%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 1.39%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS04900    | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 1.39%   |
| Lenovo ThinkPad T450 20BU000GUS             | 1         | 1.39%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 1.39%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 1.39%   |
| Lenovo ThinkPad T410 2518C3U                | 1         | 1.39%   |
| Lenovo ThinkPad P70 20ESS1L600              | 1         | 1.39%   |
| Lenovo ThinkPad Helix 2nd 20CHS1QW01        | 1         | 1.39%   |
| Lenovo ThinkPad E15 Gen 2 20TD003GUS        | 1         | 1.39%   |
| Lenovo ThinkCentre M91p 7052C1G             | 1         | 1.39%   |
| Lenovo ThinkCentre M90n-1 11AHS0B200        | 1         | 1.39%   |
| Lenovo ThinkCentre M75n 11BXS00100          | 1         | 1.39%   |
| Lenovo ThinkCentre M720s 10SUSB7Y00         | 1         | 1.39%   |
| Lenovo ThinkBook 15 G4 IAP 21DJ             | 1         | 1.39%   |
| Lenovo G550 20023                           | 1         | 1.39%   |
| Intel(R) Client Systems NUC10i3FNH          | 1         | 1.39%   |
| Intel NUC7i3BNHX                            | 1         | 1.39%   |
| Intel DCP847SKE                             | 1         | 1.39%   |
| IBM ThinkPad R51 2889W11                    | 1         | 1.39%   |
| HP s5-1210br                                | 1         | 1.39%   |
| HP ProLiant ML370 G4                        | 1         | 1.39%   |
| HP ProBook 455 G7                           | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 12        | 16.67%  |
| Unknown                                     | 5         | 6.94%   |
| Lenovo ThinkCentre                          | 4         | 5.56%   |
| Dell Latitude                               | 3         | 4.17%   |
| Sun SUNW                                    | 2         | 2.78%   |
| ASUS TUF                                    | 2         | 2.78%   |
| Toshiba Portable                            | 1         | 1.39%   |
| Star Labs LabTop                            | 1         | 1.39%   |
| Samsung 100NZC                              | 1         | 1.39%   |
| Panasonic CFSX4-1                           | 1         | 1.39%   |
| Panasonic CF-C2CEAZXCM                      | 1         | 1.39%   |
| Panasonic CF-54-1                           | 1         | 1.39%   |
| Panasonic CF-53AAGHYDM                      | 1         | 1.39%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 1.39%   |
| MSI MS-7D15                                 | 1         | 1.39%   |
| Microsoft Windows                           | 1         | 1.39%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 1.39%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 1.39%   |
| Lenovo ThinkBook                            | 1         | 1.39%   |
| Lenovo G550                                 | 1         | 1.39%   |
| Intel(R) Client Systems NUC10i3FNH          | 1         | 1.39%   |
| Intel NUC7i3BNHX                            | 1         | 1.39%   |
| Intel DCP847SKE                             | 1         | 1.39%   |
| IBM ThinkPad                                | 1         | 1.39%   |
| HP s5-1210br                                | 1         | 1.39%   |
| HP ProLiant                                 | 1         | 1.39%   |
| HP ProBook                                  | 1         | 1.39%   |
| HP Compaq                                   | 1         | 1.39%   |
| Google Droid                                | 1         | 1.39%   |
| Gigabyte Z690                               | 1         | 1.39%   |
| Gigabyte H81M-S2PV                          | 1         | 1.39%   |
| Fujitsu LIFEBOOK                            | 1         | 1.39%   |
| FUJI wortmann D1547                         | 1         | 1.39%   |
| Dell Vostro                                 | 1         | 1.39%   |
| Dell PowerEdge                              | 1         | 1.39%   |
| Dell Inspiron                               | 1         | 1.39%   |
| Chuwi LarkBox                               | 1         | 1.39%   |
| Biostar B450NH                              | 1         | 1.39%   |
| AZW SER                                     | 1         | 1.39%   |
| AZW MINI                                    | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 16        | 22.22%  |
| 2022    | 5         | 6.94%   |
| 2021    | 5         | 6.94%   |
| 2020    | 5         | 6.94%   |
| 2010    | 5         | 6.94%   |
| 2019    | 4         | 5.56%   |
| 2015    | 4         | 5.56%   |
| 2012    | 4         | 5.56%   |
| 2011    | 3         | 4.17%   |
| Unknown | 3         | 4.17%   |
| 2017    | 2         | 2.78%   |
| 2016    | 2         | 2.78%   |
| 2014    | 2         | 2.78%   |
| 2013    | 2         | 2.78%   |
| 2009    | 2         | 2.78%   |
| 2006    | 2         | 2.78%   |
| 2005    | 2         | 2.78%   |
| 2018    | 1         | 1.39%   |
| 2007    | 1         | 1.39%   |
| 2003    | 1         | 1.39%   |
| 2002    | 1         | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 39        | 54.17%  |
| Desktop        | 28        | 38.89%  |
| Mini pc        | 3         | 4.17%   |
| System on chip | 2         | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 98.61%  |
| Yes  | 1         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 24        | 33.33%  |
| 16.01-24.0  | 11        | 15.28%  |
| 4.01-8.0    | 9         | 12.5%   |
| 3.01-4.0    | 7         | 9.72%   |
| 32.01-64.0  | 5         | 6.94%   |
| 2.01-3.0    | 4         | 5.56%   |
| 64.01-256.0 | 3         | 4.17%   |
| 0.51-1.0    | 3         | 4.17%   |
| 24.01-32.0  | 2         | 2.78%   |
| 1.01-2.0    | 2         | 2.78%   |
| 0.01-0.5    | 2         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 57        | 79.17%  |
| 0.51-1.0 | 6         | 8.33%   |
| 0        | 5         | 6.94%   |
| 1.01-2.0 | 3         | 4.17%   |
| 4.01-8.0 | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 67.12%  |
| 2      | 18        | 24.66%  |
| 4      | 3         | 4.11%   |
| 8      | 1         | 1.37%   |
| 3      | 1         | 1.37%   |
| 0      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 83.33%  |
| No        | 12        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 76.39%  |
| No        | 17        | 23.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 58.9%   |
| No        | 30        | 41.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Canada    | 17        | 23.61%  |
| USA       | 14        | 19.44%  |
| Russia    | 6         | 8.33%   |
| Germany   | 5         | 6.94%   |
| Italy     | 4         | 5.56%   |
| Romania   | 3         | 4.17%   |
| Poland    | 3         | 4.17%   |
| UK        | 2         | 2.78%   |
| Spain     | 2         | 2.78%   |
| Colombia  | 2         | 2.78%   |
| Australia | 2         | 2.78%   |
| Ukraine   | 1         | 1.39%   |
| Turkey    | 1         | 1.39%   |
| Slovakia  | 1         | 1.39%   |
| Norway    | 1         | 1.39%   |
| Indonesia | 1         | 1.39%   |
| Hungary   | 1         | 1.39%   |
| Guatemala | 1         | 1.39%   |
| Greece    | 1         | 1.39%   |
| France    | 1         | 1.39%   |
| China     | 1         | 1.39%   |
| Brazil    | 1         | 1.39%   |
| Austria   | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Saint-Laurent   | 9         | 12.16%  |
| Montreal        | 5         | 6.76%   |
| Milan           | 4         | 5.41%   |
| Sun Prairie     | 3         | 4.05%   |
| New York        | 3         | 4.05%   |
| Sydenham        | 2         | 2.7%    |
| Canberra        | 2         | 2.7%    |
| Wolfsburg       | 1         | 1.35%   |
| Witow           | 1         | 1.35%   |
| Warwick         | 1         | 1.35%   |
| Volgograd       | 1         | 1.35%   |
| Valmojado       | 1         | 1.35%   |
| Uba             | 1         | 1.35%   |
| Torrent         | 1         | 1.35%   |
| Stuttgart       | 1         | 1.35%   |
| Stukenbrock     | 1         | 1.35%   |
| Stade           | 1         | 1.35%   |
| St Petersburg   | 1         | 1.35%   |
| South Tangerang | 1         | 1.35%   |
| Songjiang       | 1         | 1.35%   |
| Smolensk        | 1         | 1.35%   |
| Simferopol      | 1         | 1.35%   |
| Sao Paulo       | 1         | 1.35%   |
| Ryazan          | 1         | 1.35%   |
| Quetzaltenango  | 1         | 1.35%   |
| Punta Gorda     | 1         | 1.35%   |
| Prudhoe         | 1         | 1.35%   |
| Ploieşti       | 1         | 1.35%   |
| Orenburg        | 1         | 1.35%   |
| Mersin          | 1         | 1.35%   |
| Medellín       | 1         | 1.35%   |
| Madison         | 1         | 1.35%   |
| Lodz            | 1         | 1.35%   |
| Krakow          | 1         | 1.35%   |
| Košice         | 1         | 1.35%   |
| Kernersville    | 1         | 1.35%   |
| Hollis          | 1         | 1.35%   |
| Harrisonburg    | 1         | 1.35%   |
| Furth im Wald   | 1         | 1.35%   |
| Fresno          | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 22        | 25     | 25.58%  |
| WDC                 | 12        | 12     | 13.95%  |
| Samsung Electronics | 8         | 13     | 9.3%    |
| Seagate             | 7         | 7      | 8.14%   |
| Kingston            | 6         | 6      | 6.98%   |
| Hitachi             | 3         | 4      | 3.49%   |
| Apple               | 3         | 4      | 3.49%   |
| SanDisk             | 2         | 2      | 2.33%   |
| Intel               | 2         | 2      | 2.33%   |
| HGST                | 2         | 2      | 2.33%   |
| Generic             | 2         | 2      | 2.33%   |
| Apacer              | 2         | 2      | 2.33%   |
| Toshiba             | 1         | 1      | 1.16%   |
| PNY                 | 1         | 5      | 1.16%   |
| OPENBSD             | 1         | 1      | 1.16%   |
| Netac               | 1         | 1      | 1.16%   |
| MyDigitalSSD        | 1         | 1      | 1.16%   |
| LSILOGIC            | 1         | 1      | 1.16%   |
| Lexar               | 1         | 1      | 1.16%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.16%   |
| Hewlett-Packard     | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| External            | 1         | 1      | 1.16%   |
| Crucial             | 1         | 1      | 1.16%   |
| China               | 1         | 1      | 1.16%   |
| AirDisk             | 1         | 1      | 1.16%   |
| A-DATA Technology   | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 3         | 3.37%   |
| NVMe Samsung SSD 980 1TB            | 2         | 2.25%   |
| NVMe SAMSUNG MZALQ128 128GB         | 2         | 2.25%   |
| Kingston SA400S37120G 120GB         | 2         | 2.25%   |
| Generic STORAGE DEVICE 2GB          | 2         | 2.25%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 1.12%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 1.12%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 1.12%   |
| WDC WD64 00AAKS-22A7B2 640GB        | 1         | 1.12%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 1.12%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 1.12%   |
| WDC WD3200LPCX-24C6HT0 320GB        | 1         | 1.12%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 1.12%   |
| WDC WD2500BEKT-75A25T0 250GB        | 1         | 1.12%   |
| WDC WD10JPVT-75A1YT0 1TB            | 1         | 1.12%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.12%   |
| WDC WD Elements 2621 2TB            | 1         | 1.12%   |
| Toshiba DT01ACA050 500GB            | 1         | 1.12%   |
| Seagate ST9160821A 160GB            | 1         | 1.12%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1.12%   |
| Seagate ST31000340AS 1TB            | 1         | 1.12%   |
| Seagate ST250DM000-1BD141 250GB     | 1         | 1.12%   |
| Seagate ST2000NT001-3M3101 2TB      | 1         | 1.12%   |
| Seagate ST2000LX001-1RG174 2TB      | 1         | 1.12%   |
| Seagate ST1000DM003-1CH162 1TB      | 1         | 1.12%   |
| SanDisk SDCFXS-032G                 | 1         | 1.12%   |
| SanDisk SD8SN8U-256G-1006 256GB     | 1         | 1.12%   |
| Samsung SSD 870 QVO 2TB             | 1         | 1.12%   |
| Samsung SSD 870 EVO 500GB           | 1         | 1.12%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 1.12%   |
| Samsung SSD 860 EVO 250GB           | 1         | 1.12%   |
| Samsung SSD 860 EVO 1TB             | 1         | 1.12%   |
| Samsung SSD 840 EVO 500GB           | 1         | 1.12%   |
| Samsung SSD 840 EVO 250GB           | 1         | 1.12%   |
| Samsung Flash Drive 128GB           | 1         | 1.12%   |
| PNY CS900 1TB SSD                   | 1         | 1.12%   |
| OPENBSD SR RAID 5 9.9TB             | 1         | 1.12%   |
| NVMe WDC PC SN530 SDB 1TB           | 1         | 1.12%   |
| NVMe WDBRPG5000ANC-WR 500GB         | 1         | 1.12%   |
| NVMe WD Blue SN580 1T               | 1         | 1.12%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 15        | 17     | 31.25%  |
| WDC                 | 12        | 12     | 25%     |
| Seagate             | 7         | 7      | 14.58%  |
| Hitachi             | 3         | 4      | 6.25%   |
| HGST                | 2         | 2      | 4.17%   |
| Generic             | 2         | 2      | 4.17%   |
| Toshiba             | 1         | 1      | 2.08%   |
| Samsung Electronics | 1         | 1      | 2.08%   |
| OPENBSD             | 1         | 1      | 2.08%   |
| LSILOGIC            | 1         | 1      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| External            | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 12     | 18.42%  |
| NVMe                | 7         | 7      | 18.42%  |
| Kingston            | 6         | 6      | 15.79%  |
| Apple               | 3         | 4      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Intel               | 2         | 2      | 5.26%   |
| Apacer              | 2         | 2      | 5.26%   |
| PNY                 | 1         | 5      | 2.63%   |
| Netac               | 1         | 1      | 2.63%   |
| MyDigitalSSD        | 1         | 1      | 2.63%   |
| Lexar               | 1         | 1      | 2.63%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.63%   |
| Crucial             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |
| AirDisk             | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 51     | 53.85%  |
| SSD  | 35        | 48     | 44.87%  |
| NVMe | 1         | 1      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 99     | 98.57%  |
| NVMe | 1         | 1      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 57     | 61.25%  |
| 0.51-1.0   | 21        | 27     | 26.25%  |
| 1.01-2.0   | 9         | 14     | 11.25%  |
| 4.01-10.0  | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 25        | 34.72%  |
| 101-250        | 21        | 29.17%  |
| 21-50          | 15        | 20.83%  |
| 51-100         | 6         | 8.33%   |
| 501-1000       | 2         | 2.78%   |
| More than 3000 | 1         | 1.39%   |
| 1001-2000      | 1         | 1.39%   |
| 1-20           | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 59        | 79.73%  |
| 21-50    | 8         | 10.81%  |
| 101-250  | 3         | 4.05%   |
| 501-1000 | 2         | 2.7%    |
| 251-500  | 1         | 1.35%   |
| 51-100   | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 10%     |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 10%     |
| Seagate ST250DM000-1BD141 250GB       | 1         | 1      | 10%     |
| Samsung Electronics SSD 840 EVO 250GB | 1         | 1      | 10%     |
| Intel SSDSCKJF240A5L 240GB            | 1         | 1      | 10%     |
| Intel SSDSC2BF180A5L 180GB            | 1         | 1      | 10%     |
| Hitachi HTS541010G9SA00 100GB         | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 10%     |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 10%     |
| A-DATA Technology SP550 480GB         | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 20%     |
| Intel               | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |
| Seagate             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| A-DATA Technology   | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 33.33%  |
| HGST    | 2         | 2      | 33.33%  |
| Seagate | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 60%     |
| SSD  | 4         | 4      | 40%     |

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
| Works    | 42        | 59     | 53.85%  |
| Detected | 26        | 31     | 33.33%  |
| Malfunc  | 10        | 10     | 12.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 45        | 56.25%  |
| Samsung Electronics                     | 10        | 12.5%   |
| AMD                                     | 5         | 6.25%   |
| Shenzhen Longsys Electronics            | 2         | 2.5%    |
| SanDisk                                 | 2         | 2.5%    |
| Phison Electronics                      | 2         | 2.5%    |
| KIOXIA                                  | 2         | 2.5%    |
| Broadcom / LSI                          | 2         | 2.5%    |
| Solid State Storage Technology          | 1         | 1.25%   |
| Shenzhen Unionmemory Information System | 1         | 1.25%   |
| Nvidia                                  | 1         | 1.25%   |
| Micron/Crucial Technology               | 1         | 1.25%   |
| MAXIO Technology (Hangzhou)             | 1         | 1.25%   |
| Kingston Technology Company             | 1         | 1.25%   |
| Compaq Computer                         | 1         | 1.25%   |
| Biwin Storage Technology                | 1         | 1.25%   |
| ASMedia Technology                      | 1         | 1.25%   |
| Unknown                                 | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                            | 6         | 7.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                   | 5         | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                              | 5         | 5.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                            | 4         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller                 | 3         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                | 3         | 3.57%   |
| AMD 500 Series Chipset SATA Controller                                                        | 3         | 3.57%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                             | 2         | 2.38%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                    | 2         | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                 | 2         | 2.38%   |
| Intel Alder Lake-N SATA AHCI Controller                                                       | 2         | 2.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                                 | 2         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                  | 2         | 2.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                           | 2         | 2.38%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                                | 1         | 1.19%   |
| Shenzhen Unionmemory Information System RPEYJ1T24MKN2QWY PCIe 4.0 NVMe SSD 1024GB (DRAM-less) | 1         | 1.19%   |
| Sandisk WD Blue SN580 NVMe SSD (DRAM-less)                                                    | 1         | 1.19%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                     | 1         | 1.19%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                          | 1         | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                 | 1         | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                 | 1         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                | 1         | 1.19%   |
| Phison E16 PCIe4 NVMe Controller                                                              | 1         | 1.19%   |
| Phison E12 NVMe Controller                                                                    | 1         | 1.19%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                      | 1         | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                          | 1         | 1.19%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                      | 1         | 1.19%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                    | 1         | 1.19%   |
| KIOXIA NVMe SSD                                                                               | 1         | 1.19%   |
| Kingston Company NV2 NVMe SSD [E19T] (DRAM-less)                                              | 1         | 1.19%   |
| Intel NVMe Optane Memory Series                                                               | 1         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                             | 1         | 1.19%   |
| Intel Jasper Lake SATA AHCI Controller                                                        | 1         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                                         | 1         | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                    | 1         | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                             | 1         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                         | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                 | 1         | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                              | 1         | 1.19%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                        | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 57.5%   |
| NVMe | 22        | 27.5%   |
| IDE  | 9         | 11.25%  |
| SCSI | 2         | 2.5%    |
| RAID | 1         | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 56        | 77.78%  |
| AMD     | 10        | 13.89%  |
| ARM     | 3         | 4.17%   |
| Unknown | 3         | 4.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                            | 4         | 5.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 3         | 4.17%   |
|                                                              | 3         | 4.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 2         | 2.78%   |
| Intel Xeon CPU E5520 @ 2.27GHz                               | 1         | 1.39%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                         | 1         | 1.39%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz                          | 1         | 1.39%   |
| Intel Xeon CPU 3.40GHz                                       | 1         | 1.39%   |
| Intel Pentium M processor 1.73GHz ("GenuineIntel" 686-class) | 1         | 1.39%   |
| Intel Pentium M processor                                    | 1         | 1.39%   |
| Intel Pentium CPU G620 @ 2.60GHz                             | 1         | 1.39%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                           | 1         | 1.39%   |
| Intel Pentium 4 CPU 2.66GHz ("GenuineIntel" 686-class)       | 1         | 1.39%   |
| Intel Other                                                  | 1         | 1.39%   |
| Intel N95                                                    | 1         | 1.39%   |
| Intel N100                                                   | 1         | 1.39%   |
| Intel Genuine CPU T2300 @ 1.66GHz                            | 1         | 1.39%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                              | 1         | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 1         | 1.39%   |
| Intel Core i7-3537U CPU @ 2.00GHz                            | 1         | 1.39%   |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 1         | 1.39%   |
| Intel Core i7-2677M CPU @ 1.80GHz                            | 1         | 1.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz                             | 1         | 1.39%   |
| Intel Core i5-8350U CPU @ 1.70GHz                            | 1         | 1.39%   |
| Intel Core i5-7500 CPU @ 3.40GHz                             | 1         | 1.39%   |
| Intel Core i5-7300U CPU @ 2.60GHz                            | 1         | 1.39%   |
| Intel Core i5-5350U CPU @ 1.80GHz                            | 1         | 1.39%   |
| Intel Core i5-5257U CPU @ 2.70GHz                            | 1         | 1.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz                            | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 1         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz                            | 1         | 1.39%   |
| Intel Core i5-10400F CPU @ 2.90GHz                           | 1         | 1.39%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                            | 1         | 1.39%   |
| Intel Core i3-8145U CPU @ 2.10GHz                            | 1         | 1.39%   |
| Intel Core i3-8100 CPU @ 3.60GHz                             | 1         | 1.39%   |
| Intel Core i3-7100U CPU @ 2.40GHz                            | 1         | 1.39%   |
| Intel Core i3-10110U CPU @ 2.10GHz                           | 1         | 1.39%   |
| Intel Core i3 CPU M 370 @ 2.40GHz                            | 1         | 1.39%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                         | 1         | 1.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                         | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 19        | 26.39%  |
| Other            | 10        | 13.89%  |
| Intel Core i7    | 5         | 6.94%   |
| Intel Core i3    | 5         | 6.94%   |
| Intel Celeron    | 5         | 6.94%   |
| Intel Xeon       | 4         | 5.56%   |
| AMD Ryzen 5      | 4         | 5.56%   |
| ARM Cortex       | 3         | 4.17%   |
| AMD Ryzen 7      | 3         | 4.17%   |
| Intel Pentium M  | 2         | 2.78%   |
| Intel Pentium 4  | 2         | 2.78%   |
| Intel Core 2 Duo | 2         | 2.78%   |
| Intel Atom       | 2         | 2.78%   |
| AMD Ryzen 9      | 2         | 2.78%   |
| Intel Pentium    | 1         | 1.39%   |
| Intel Genuine    | 1         | 1.39%   |
| Intel Core M     | 1         | 1.39%   |
| AMD Athlon       | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 29        | 40.28%  |
| Unknown | 14        | 19.44%  |
| 4       | 12        | 16.67%  |
| 1       | 5         | 6.94%   |
| 16      | 4         | 5.56%   |
| 12      | 4         | 5.56%   |
| 8       | 2         | 2.78%   |
| 32      | 1         | 1.39%   |
| 6       | 1         | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 57        | 79.17%  |
| Unknown | 14        | 19.44%  |
| 2       | 1         | 1.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 33        | 45.83%  |
| 1       | 20        | 27.78%  |
| Unknown | 19        | 26.39%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 15        | 20.83%  |
| KabyLake      | 8         | 11.11%  |
| SandyBridge   | 6         | 8.33%   |
| Broadwell     | 6         | 8.33%   |
| Skylake       | 5         | 6.94%   |
| Zen 3         | 4         | 5.56%   |
| Westmere      | 4         | 5.56%   |
| IvyBridge     | 4         | 5.56%   |
| P6            | 3         | 4.17%   |
| NetBurst      | 3         | 4.17%   |
| Zen 2         | 2         | 2.78%   |
| TigerLake     | 2         | 2.78%   |
| Penryn        | 2         | 2.78%   |
| Haswell       | 2         | 2.78%   |
| Bonnell       | 2         | 2.78%   |
| Zen           | 1         | 1.39%   |
| Nehalem       | 1         | 1.39%   |
| Goldmont plus | 1         | 1.39%   |
| Core          | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 46        | 66.67%  |
| AMD                        | 16        | 23.19%  |
| Nvidia                     | 6         | 8.7%    |
| Matrox Electronics Systems | 1         | 1.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 6.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 5.41%   |
| Intel Core Processor Integrated Graphics Controller                           | 4         | 5.41%   |
| Intel HD Graphics 5500                                                        | 3         | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 4.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 4.05%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2         | 2.7%    |
| Intel UHD Graphics 620                                                        | 2         | 2.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 2.7%    |
| Intel HD Graphics 620                                                         | 2         | 2.7%    |
| Intel Alder Lake-N [UHD Graphics]                                             | 2         | 2.7%    |
| AMD Rembrandt [Radeon 680M]                                                   | 2         | 2.7%    |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 1.35%   |
| Nvidia GT218M [GeForce G210M]                                                 | 1         | 1.35%   |
| Nvidia GM107GLM [Quadro M600M]                                                | 1         | 1.35%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1         | 1.35%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.35%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                   | 1         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.35%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.35%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.35%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.35%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 1.35%   |
| Intel Iris Graphics 6100                                                      | 1         | 1.35%   |
| Intel HD Graphics P530                                                        | 1         | 1.35%   |
| Intel HD Graphics 630                                                         | 1         | 1.35%   |
| Intel HD Graphics 6000                                                        | 1         | 1.35%   |
| Intel HD Graphics 5300                                                        | 1         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 1         | 1.35%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.35%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 1         | 1.35%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 1         | 1.35%   |
| AMD RV280 [Radeon 9200] (Secondary)                                           | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 55.56%  |
| 1 x AMD        | 13        | 18.06%  |
| Other          | 5         | 6.94%   |
| 1 x Nvidia     | 5         | 6.94%   |
| 2 x Intel      | 4         | 5.56%   |
| 2 x AMD        | 2         | 2.78%   |
| 1 x Matrox     | 1         | 1.39%   |
| Intel + Nvidia | 1         | 1.39%   |
| Intel + AMD    | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 61        | 84.72%  |
| Unknown | 11        | 15.28%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 7         | 16.28%  |
| AU Optronics         | 6         | 13.95%  |
| Philips              | 5         | 11.63%  |
| Apple                | 4         | 9.3%    |
| Samsung Electronics  | 3         | 6.98%   |
| BOE                  | 3         | 6.98%   |
| ASUSTek Computer     | 3         | 6.98%   |
| Sharp                | 2         | 4.65%   |
| Dell                 | 2         | 4.65%   |
| Chimei Innolux       | 2         | 4.65%   |
| Ancor Communications | 2         | 4.65%   |
| Panasonic            | 1         | 2.33%   |
| NEC Computers        | 1         | 2.33%   |
| MSI                  | 1         | 2.33%   |
| AOC                  | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 3         | 6.98%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 290x170mm 13.2-inch              | 1         | 2.33%   |
| Sharp LCD Monitor SHP1526 1920x1280 270x180mm 12.8-inch              | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM041E 2048x1152 510x290mm 23.1-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 2.33%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 700x390mm 31.5-inch    | 1         | 2.33%   |
| Philips PHL 240B9 PHL0966 1920x1200 520x320mm 24.0-inch              | 1         | 2.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch              | 1         | 2.33%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 2.33%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch           | 1         | 2.33%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1         | 2.33%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD05A2 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0404 1366x768 280x160mm 12.7-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch         | 1         | 2.33%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1         | 2.33%   |
| Dell P2210 DEL404E 1680x1050 470x300mm 22.0-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1520 1920x1080 340x190mm 15.3-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 1         | 2.33%   |
| BOE NE160WUM-NX2 BOE0B33 1920x1200 340x210mm 15.7-inch               | 1         | 2.33%   |
| BOE LCD Monitor BOE08C2 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                 | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO335D 1920x1080 260x140mm 11.6-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| ASUSTek Computer XG49WCR AUS4932 3840x1080 1190x340mm 48.7-inch      | 1         | 2.33%   |
| ASUSTek Computer XG49V AUS49A1 3840x1080 1200x340mm 49.1-inch        | 1         | 2.33%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch         | 1         | 2.33%   |
| Apple Color LCD APPA02A 2560x1600 290x180mm 13.4-inch                | 1         | 2.33%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 2.33%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 2.33%   |
| Apple Color LCD APP9C21 1280x854 320x220mm 15.3-inch                 | 1         | 2.33%   |
| AOC Q27G2WG4 AOC2702 2560x1440 600x340mm 27.2-inch                   | 1         | 2.33%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 17        | 41.46%  |
| 1366x768 (WXGA)    | 8         | 19.51%  |
| 3840x2160 (4K)     | 2         | 4.88%   |
| 3840x1080          | 2         | 4.88%   |
| 2560x1440 (QHD)    | 2         | 4.88%   |
| 1920x1200 (WUXGA)  | 2         | 4.88%   |
| 1440x900 (WXGA+)   | 2         | 4.88%   |
| 3440x1440          | 1         | 2.44%   |
| 2560x1600          | 1         | 2.44%   |
| 2048x1152          | 1         | 2.44%   |
| 1920x1280          | 1         | 2.44%   |
| 1680x1050 (WSXGA+) | 1         | 2.44%   |
| 1280x854           | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 10        | 23.81%  |
| 15     | 9         | 21.43%  |
| 21     | 4         | 9.52%   |
| 12     | 4         | 9.52%   |
| 24     | 3         | 7.14%   |
| 27     | 2         | 4.76%   |
| 11     | 2         | 4.76%   |
| 49     | 1         | 2.38%   |
| 48     | 1         | 2.38%   |
| 34     | 1         | 2.38%   |
| 31     | 1         | 2.38%   |
| 23     | 1         | 2.38%   |
| 22     | 1         | 2.38%   |
| 19     | 1         | 2.38%   |
| 17     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 38.1%   |
| 201-300     | 9         | 21.43%  |
| 501-600     | 6         | 14.29%  |
| 401-500     | 6         | 14.29%  |
| 1001-1500   | 2         | 4.76%   |
| 701-800     | 1         | 2.38%   |
| 601-700     | 1         | 2.38%   |
| 351-400     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 73.17%  |
| 16/10 | 6         | 14.63%  |
| 32/9  | 2         | 4.88%   |
| 3/2   | 2         | 4.88%   |
| 21/9  | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 20.93%  |
| 201-250        | 8         | 18.6%   |
| 91-100         | 5         | 11.63%  |
| 61-70          | 3         | 6.98%   |
| 101-110        | 3         | 6.98%   |
| 71-80          | 2         | 4.65%   |
| 51-60          | 2         | 4.65%   |
| 351-500        | 2         | 4.65%   |
| 301-350        | 2         | 4.65%   |
| 151-200        | 2         | 4.65%   |
| 501-1000       | 2         | 4.65%   |
| 251-300        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |
| 111-120        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 33.33%  |
| 101-120       | 11        | 26.19%  |
| 51-100        | 10        | 23.81%  |
| 161-240       | 6         | 14.29%  |
| More than 240 | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 50        | 69.44%  |
| 0     | 19        | 26.39%  |
| 2     | 3         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 48.45%  |
| Realtek Semiconductor    | 28        | 28.87%  |
| Broadcom                 | 9         | 9.28%   |
| Qualcomm Atheros         | 4         | 4.12%   |
| Sierra Wireless          | 2         | 2.06%   |
| ASUSTek Computer         | 2         | 2.06%   |
| Qualcomm Technologies    | 1         | 1.03%   |
| Motorola PCS             | 1         | 1.03%   |
| MediaTek                 | 1         | 1.03%   |
| Marvell Technology Group | 1         | 1.03%   |
| Apple                    | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 14        | 11.2%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 5.6%    |
| Intel Wireless 8260                                                           | 5         | 4%      |
| Intel Wireless 8265 / 8275                                                    | 4         | 3.2%    |
| Intel Wireless 7265                                                           | 4         | 3.2%    |
| Intel Wi-Fi 6 AX200                                                           | 4         | 3.2%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 3.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 3.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.4%    |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 2.4%    |
| Intel Centrino Advanced-N 6200                                                | 3         | 2.4%    |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 2.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2         | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 1.6%    |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.6%    |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 1.6%    |
| Sierra Wireless EM7455                                                        | 1         | 0.8%    |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.8%    |
| Qualcomm QCNFA765 Wireless Network Adapter                                    | 1         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.8%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.8%    |
| Motorola PCS USB RNDIS Device                                                 | 1         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1         | 0.8%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 0.8%    |
| Intel Wireless 7260                                                           | 1         | 0.8%    |
| Intel Wireless 3165                                                           | 1         | 0.8%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1         | 0.8%    |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 0.8%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 0.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.8%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 66.67%  |
| Realtek Semiconductor | 6         | 10.53%  |
| Qualcomm Atheros      | 4         | 7.02%   |
| Broadcom              | 4         | 7.02%   |
| ASUSTek Computer      | 2         | 3.51%   |
| Sierra Wireless       | 1         | 1.75%   |
| Qualcomm Technologies | 1         | 1.75%   |
| MediaTek              | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                | 5         | 8.62%   |
| Intel Wireless 8265 / 8275                                         | 4         | 6.9%    |
| Intel Wireless 7265                                                | 4         | 6.9%    |
| Intel Wi-Fi 6 AX200                                                | 4         | 6.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 5.17%   |
| Intel Centrino Advanced-N 6200                                     | 3         | 5.17%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 2         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 2         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 2         | 3.45%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 2         | 3.45%   |
| Sierra Wireless EM7455                                             | 1         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 1         | 1.72%   |
| Qualcomm QCNFA765 Wireless Network Adapter                         | 1         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 1         | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 1         | 1.72%   |
| Intel Wireless 7260                                                | 1         | 1.72%   |
| Intel Wireless 3165                                                | 1         | 1.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]          | 1         | 1.72%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                    | 1         | 1.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection           | 1         | 1.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 1         | 1.72%   |
| Intel CNVi: Wi-Fi                                                  | 1         | 1.72%   |
| Intel Centrino Wireless-N 2230                                     | 1         | 1.72%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]               | 1         | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 1         | 1.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                        | 1         | 1.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter       | 1         | 1.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 1         | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller             | 1         | 1.72%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1         | 1.72%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                | 1         | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 30        | 47.62%  |
| Realtek Semiconductor    | 25        | 39.68%  |
| Broadcom                 | 5         | 7.94%   |
| Qualcomm Atheros         | 1         | 1.59%   |
| Motorola PCS             | 1         | 1.59%   |
| Marvell Technology Group | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 14        | 21.88%  |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 10.94%  |
| Intel Ethernet Connection I219-LM                                             | 4         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 4.69%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 4.69%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 4.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 3.13%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 3.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 3.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.56%   |
| Motorola PCS USB RNDIS Device                                                 | 1         | 1.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.56%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 1.56%   |
| Intel Ethernet Connection (16) I219-V                                         | 1         | 1.56%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1         | 1.56%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.56%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 1.56%   |
| Intel 82566MC Gigabit Network Connection                                      | 1         | 1.56%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 1.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 1.56%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                             | 1         | 1.56%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 1.56%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1         | 1.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 60        | 50.85%  |
| WiFi     | 55        | 46.61%  |
| Unknown  | 2         | 1.69%   |
| Modem    | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 54.29%  |
| WiFi     | 32        | 45.71%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 42        | 58.33%  |
| 1     | 21        | 29.17%  |
| 3     | 5         | 6.94%   |
| 0     | 3         | 4.17%   |
| 4     | 1         | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 95.83%  |
| Yes  | 3         | 4.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 58.14%  |
| Apple                           | 5         | 11.63%  |
| Realtek Semiconductor           | 3         | 6.98%   |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Alps Electric                   | 2         | 4.65%   |
| IMC Networks                    | 1         | 2.33%   |
| Dell                            | 1         | 2.33%   |
| ASUSTek Computer                | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 30.23%  |
| Intel AX201 Bluetooth                                       | 4         | 9.3%    |
| Intel AX200 Bluetooth                                       | 4         | 9.3%    |
| Realtek Bluetooth Adapter                                   | 3         | 6.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 4.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 4.65%   |
| Apple Bluetooth Host Controller                             | 2         | 4.65%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 4.65%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.33%   |
| Intel AX210 Bluetooth                                       | 1         | 2.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 2.33%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 2.33%   |
| Dell DW375 Bluetooth Module                                 | 1         | 2.33%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 2.33%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 52        | 68.42%  |
| AMD                                          | 12        | 15.79%  |
| Nvidia                                       | 4         | 5.26%   |
| C-Media Electronics                          | 2         | 2.63%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.32%   |
| Texas Instruments                            | 1         | 1.32%   |
| Logitech                                     | 1         | 1.32%   |
| KTMicro                                      | 1         | 1.32%   |
| JMTek                                        | 1         | 1.32%   |
| Creative Labs                                | 1         | 1.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 8.6%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 8         | 8.6%    |
| Intel Broadwell-U Audio Controller                                         | 6         | 6.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 5.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 4.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 3.23%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 3.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3.23%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 2.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.15%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 2         | 2.15%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.15%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                     | 2         | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 2.15%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 1.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 1.08%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 1.08%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.08%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 1.08%   |
| KTMicro KT USB Audio                                                       | 1         | 1.08%   |
| JMTek USB PnP Audio Device                                                 | 1         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.08%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.08%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.08%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1         | 1.08%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 33.33%  |
| Unknown             | 5         | 23.81%  |
| SK hynix            | 4         | 19.05%  |
| Unknown             | 2         | 9.52%   |
| Micron Technology   | 1         | 4.76%   |
| Kingston            | 1         | 4.76%   |
| Elpida              | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s  | 2         | 8.7%    |
| Unknown                                                | 2         | 8.7%    |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 4.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 4.35%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 4.35%   |
| Unknown RAM Module 1GB SODIMM DDR                      | 1         | 4.35%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s  | 1         | 4.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 4.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s   | 1         | 4.35%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.35%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 4.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 1         | 4.35%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 4.35%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s | 1         | 4.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 1         | 4.35%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s  | 1         | 4.35%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3000MT/s  | 1         | 4.35%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s  | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 38.89%  |
| DDR4   | 5         | 27.78%  |
| SDRAM  | 2         | 11.11%  |
| DDR2   | 2         | 11.11%  |
| LPDDR3 | 1         | 5.56%   |
| DDR    | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 89.47%  |
| DIMM   | 1         | 5.26%   |
| Chip   | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 5         | 26.32%  |
| 2048  | 5         | 26.32%  |
| 4096  | 4         | 21.05%  |
| 1024  | 2         | 10.53%  |
| 32768 | 1         | 5.26%   |
| 16384 | 1         | 5.26%   |
| 512   | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4         | 22.22%  |
| 2133    | 2         | 11.11%  |
| 1600    | 2         | 11.11%  |
| 1333    | 2         | 11.11%  |
| 1067    | 2         | 11.11%  |
| 3000    | 1         | 5.56%   |
| 2667    | 1         | 5.56%   |
| 2400    | 1         | 5.56%   |
| 1867    | 1         | 5.56%   |
| 1334    | 1         | 5.56%   |
| 667     | 1         | 5.56%   |

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


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Chicony Electronics              | 6         | 23.08%  |
| Bison Electronics                | 6         | 23.08%  |
| Lite-On Technology               | 3         | 11.54%  |
| Silicon Motion                   | 2         | 7.69%   |
| Realtek Semiconductor            | 2         | 7.69%   |
| Z-Star Microelectronics          | 1         | 3.85%   |
| Sunplus Innovation Technology    | 1         | 3.85%   |
| Shenzhen Kingcome Optoelectronic | 1         | 3.85%   |
| Quanta                           | 1         | 3.85%   |
| Logitech                         | 1         | 3.85%   |
| IMC Networks                     | 1         | 3.85%   |
| Apple                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 4         | 15.38%  |
| Bison Integrated Camera                               | 4         | 15.38%  |
| Lite-On Integrated Camera                             | 3         | 11.54%  |
| Realtek Integrated Webcam HD                          | 2         | 7.69%   |
| Bison USB HD Webcam                                   | 2         | 7.69%   |
| Z-Star Visual Communication Camera VGP-VCC1           | 1         | 3.85%   |
| Sunplus HP HD Camera                                  | 1         | 3.85%   |
| Silicon Motion WebCam SC-03FFL11939N                  | 1         | 3.85%   |
| Silicon Motion Lenovo EasyCamera                      | 1         | 3.85%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 3.85%   |
| Quanta HP Universal Camera                            | 1         | 3.85%   |
| Logitech C920 PRO HD Webcam                           | 1         | 3.85%   |
| IMC Networks Integrated Camera                        | 1         | 3.85%   |
| Chicony FJ Camera                                     | 1         | 3.85%   |
| Chicony 2.0M UVC Webcam / CNF7129                     | 1         | 3.85%   |
| Apple FaceTime Camera                                 | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 5         | 62.5%   |
| Synaptics          | 1         | 12.5%   |
| STMicroelectronics | 1         | 12.5%   |
| AuthenTec          | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 50.68%  |
| 2     | 17        | 23.29%  |
| 0     | 14        | 19.18%  |
| 5     | 2         | 2.74%   |
| 3     | 2         | 2.74%   |
| 4     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 42        | 50%     |
| Net/wireless             | 11        | 13.1%   |
| Graphics card            | 11        | 13.1%   |
| Firewire controller      | 9         | 10.71%  |
| Sound                    | 3         | 3.57%   |
| Network                  | 3         | 3.57%   |
| Storage/ata              | 2         | 2.38%   |
| Storage                  | 2         | 2.38%   |
| Modem                    | 1         | 1.19%   |

