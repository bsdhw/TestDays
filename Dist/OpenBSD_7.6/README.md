OpenBSD 7.6 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.6/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.6/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | H310M DS2 2.0               | Desktop     | [0ace2c80f5](https://bsd-hardware.info/?probe=0ace2c80f5) | Jan 06, 2025 |
| Gigabyte      | H310M DS2 2.0               | Desktop     | [bfa6a720f4](https://bsd-hardware.info/?probe=bfa6a720f4) | Jan 06, 2025 |
| Lenovo        | ThinkStation P320 Tiny 3... | Desktop     | [c8a55cde50](https://bsd-hardware.info/?probe=c8a55cde50) | Jan 04, 2025 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [92e2cb380a](https://bsd-hardware.info/?probe=92e2cb380a) | Jan 03, 2025 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [9f03b43d72](https://bsd-hardware.info/?probe=9f03b43d72) | Jan 03, 2025 |
| Lenovo        | ThinkPad T490 20N20028US    | Notebook    | [609bd09ed4](https://bsd-hardware.info/?probe=609bd09ed4) | Dec 28, 2024 |
| Intel         | D2500HN                     | Desktop     | [a316391d86](https://bsd-hardware.info/?probe=a316391d86) | Dec 27, 2024 |
| Lenovo        | ThinkPad X270 20HN0015MX    | Notebook    | [66b1686a32](https://bsd-hardware.info/?probe=66b1686a32) | Dec 25, 2024 |
| Dell          | Latitude D620               | Notebook    | [df7fa9c810](https://bsd-hardware.info/?probe=df7fa9c810) | Dec 25, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [757979fc58](https://bsd-hardware.info/?probe=757979fc58) | Dec 22, 2024 |
| ASUSTek       | 900                         | Notebook    | [a4c9546642](https://bsd-hardware.info/?probe=a4c9546642) | Dec 15, 2024 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [1fc4bc2661](https://bsd-hardware.info/?probe=1fc4bc2661) | Dec 12, 2024 |
| Lenovo        | ThinkPad X60s 1704R8G       | Notebook    | [cad87ee9a5](https://bsd-hardware.info/?probe=cad87ee9a5) | Dec 12, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [f34dc483d5](https://bsd-hardware.info/?probe=f34dc483d5) | Dec 11, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S3... | Convertible | [aa358442b4](https://bsd-hardware.info/?probe=aa358442b4) | Dec 08, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S3... | Convertible | [3aaaa724f1](https://bsd-hardware.info/?probe=3aaaa724f1) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [23b03d29a7](https://bsd-hardware.info/?probe=23b03d29a7) | Dec 06, 2024 |
| HP            | 829A                        | Mini pc     | [25abfdcee7](https://bsd-hardware.info/?probe=25abfdcee7) | Dec 06, 2024 |
| Biostar       | B450MH                      | Desktop     | [9596d106ab](https://bsd-hardware.info/?probe=9596d106ab) | Dec 01, 2024 |
| Lenovo        | ThinkCentre M715q 10M2S0... | Desktop     | [9082d8b443](https://bsd-hardware.info/?probe=9082d8b443) | Dec 01, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | Notebook    | [2bd04e188a](https://bsd-hardware.info/?probe=2bd04e188a) | Nov 29, 2024 |
| Samsung       | 535U3C                      | Notebook    | [615b4a9430](https://bsd-hardware.info/?probe=615b4a9430) | Nov 18, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [2bfe5665da](https://bsd-hardware.info/?probe=2bfe5665da) | Nov 14, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [3b6c29e294](https://bsd-hardware.info/?probe=3b6c29e294) | Nov 13, 2024 |
| Lenovo        | ThinkCentre M715q 10M2S0... | Desktop     | [bb5dc8520d](https://bsd-hardware.info/?probe=bb5dc8520d) | Nov 13, 2024 |
| Lenovo        | ThinkPad T490 20N3SFCE00    | Notebook    | [f5e420121b](https://bsd-hardware.info/?probe=f5e420121b) | Nov 10, 2024 |
| Biostar       | B450MH                      | Desktop     | [51f3b1e55e](https://bsd-hardware.info/?probe=51f3b1e55e) | Nov 09, 2024 |
| MSI           | MS-7C02                     | Desktop     | [6f6f894d63](https://bsd-hardware.info/?probe=6f6f894d63) | Nov 05, 2024 |
| Google        | Morphius                    | Notebook    | [d7948b7b2a](https://bsd-hardware.info/?probe=d7948b7b2a) | Oct 31, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [c16eee5fcc](https://bsd-hardware.info/?probe=c16eee5fcc) | Oct 27, 2024 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [96e9c16dc5](https://bsd-hardware.info/?probe=96e9c16dc5) | Oct 26, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [db3492b574](https://bsd-hardware.info/?probe=db3492b574) | Oct 25, 2024 |
| Dell          | Latitude 7490               | Notebook    | [46b2b68262](https://bsd-hardware.info/?probe=46b2b68262) | Oct 24, 2024 |
| ASUSTek       | 1000HE                      | Notebook    | [1a04fd3a79](https://bsd-hardware.info/?probe=1a04fd3a79) | Oct 22, 2024 |
| Gigabyte      | A620M H                     | Desktop     | [c1e5a0fe6f](https://bsd-hardware.info/?probe=c1e5a0fe6f) | Oct 22, 2024 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [d911fcdc27](https://bsd-hardware.info/?probe=d911fcdc27) | Oct 21, 2024 |
| Panasonic     | CF-54-1                     | Notebook    | [2c0a3bc2e3](https://bsd-hardware.info/?probe=2c0a3bc2e3) | Oct 18, 2024 |
| Fujitsu       | ESPRIMO_P556                | Desktop     | [acfba13c5e](https://bsd-hardware.info/?probe=acfba13c5e) | Oct 18, 2024 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [e7b0a90d19](https://bsd-hardware.info/?probe=e7b0a90d19) | Oct 13, 2024 |
| HP            | Compaq Presario CQ50        | Desktop     | [462666f013](https://bsd-hardware.info/?probe=462666f013) | Oct 13, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [6d6ba6974b](https://bsd-hardware.info/?probe=6d6ba6974b) | Oct 12, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [e556651aa4](https://bsd-hardware.info/?probe=e556651aa4) | Oct 11, 2024 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [dbdce5230f](https://bsd-hardware.info/?probe=dbdce5230f) | Oct 11, 2024 |
| Shuttle       | DS77U                       | Desktop     | [9386a947f0](https://bsd-hardware.info/?probe=9386a947f0) | Oct 10, 2024 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [19fac4e1e4](https://bsd-hardware.info/?probe=19fac4e1e4) | Oct 10, 2024 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [bbda83e57b](https://bsd-hardware.info/?probe=bbda83e57b) | Oct 10, 2024 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [01fa981bc4](https://bsd-hardware.info/?probe=01fa981bc4) | Oct 10, 2024 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [ac773e52cd](https://bsd-hardware.info/?probe=ac773e52cd) | Oct 10, 2024 |
| Dell          | OptiPlex 9020               | Desktop     | [e7027118cd](https://bsd-hardware.info/?probe=e7027118cd) | Oct 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37252abbb6](https://bsd-hardware.info/?probe=37252abbb6) | Oct 09, 2024 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [075e5d2557](https://bsd-hardware.info/?probe=075e5d2557) | Oct 08, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [47138b3361](https://bsd-hardware.info/?probe=47138b3361) | Sep 24, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [90220b30ee](https://bsd-hardware.info/?probe=90220b30ee) | Sep 09, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [545a918b07](https://bsd-hardware.info/?probe=545a918b07) | Sep 07, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [afe54c104a](https://bsd-hardware.info/?probe=afe54c104a) | Aug 24, 2024 |
| Lenovo        | 334A NOK                    | Mini pc     | [a173938fb3](https://bsd-hardware.info/?probe=a173938fb3) | Aug 10, 2024 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 36        | 81.82%  |
| i386  | 7         | 15.91%  |
| arm64 | 1         | 2.27%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 36        | 80%     |
| XFCE         | 4         | 8.89%   |
| stumpwm      | 1         | 2.22%   |
| LXQT         | 1         | 2.22%   |
| KDE6         | 1         | 2.22%   |
| GNOME        | 1         | 2.22%   |
| fvwm         | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 39        | 88.64%  |
| Console | 5         | 11.36%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 44        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 82.22%  |
| en_US   | 7         | 15.56%  |
| es_PY   | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 27        | 60%     |
| BIOS | 18        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 44        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 26        | 59.09%  |
| MBR  | 18        | 40.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 14        | 31.82%  |
| Panasonic                      | 5         | 11.36%  |
| ASUSTek Computer               | 4         | 9.09%   |
| Dell                           | 3         | 6.82%   |
| Hewlett-Packard                | 2         | 4.55%   |
| Gigabyte Technology            | 2         | 4.55%   |
| Fujitsu                        | 2         | 4.55%   |
| Shuttle                        | 1         | 2.27%   |
| Samsung Electronics            | 1         | 2.27%   |
| Raspberry Pi Foundation        | 1         | 2.27%   |
| MSI                            | 1         | 2.27%   |
| Matsushita Electric Industrial | 1         | 2.27%   |
| Intel                          | 1         | 2.27%   |
| IBM                            | 1         | 2.27%   |
| Google                         | 1         | 2.27%   |
| Framework                      | 1         | 2.27%   |
| Biostar                        | 1         | 2.27%   |
| Acer                           | 1         | 2.27%   |
| Unknown                        | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Shuttle DS77U                                   | 1         | 2.27%   |
| Samsung 535U3C                                  | 1         | 2.27%   |
| RPi Raspberry Pi 4 Model B                      | 1         | 2.27%   |
| Panasonic CFSZ6-2                               | 1         | 2.27%   |
| Panasonic CFSX4-1                               | 1         | 2.27%   |
| Panasonic CF-54-1                               | 1         | 2.27%   |
| Panasonic CF-53AAGHYDM                          | 1         | 2.27%   |
| Panasonic CF-52PFPBSFQ                          | 1         | 2.27%   |
| MSI MS-7C02                                     | 1         | 2.27%   |
| Matsushita Electric Industrial CF-51RCVDNLM     | 1         | 2.27%   |
| Lenovo Yoga 900S-12ISK 80ML                     | 1         | 2.27%   |
| Lenovo ThinkStation P320 Tiny 30C1S0QS00        | 1         | 2.27%   |
| Lenovo ThinkPad X60s 1704R8G                    | 1         | 2.27%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N           | 1         | 2.27%   |
| Lenovo ThinkPad X270 20HN0015MX                 | 1         | 2.27%   |
| Lenovo ThinkPad X260 20F5S2GM00                 | 1         | 2.27%   |
| Lenovo ThinkPad T490 20N3SFCE00                 | 1         | 2.27%   |
| Lenovo ThinkPad T490 20N20028US                 | 1         | 2.27%   |
| Lenovo ThinkPad T430 2347GZU                    | 1         | 2.27%   |
| Lenovo ThinkPad T410 2537N24                    | 1         | 2.27%   |
| Lenovo ThinkPad L13 Yoga 20R6S36000             | 1         | 2.27%   |
| Lenovo ThinkCentre M910s 10MK000TUS             | 1         | 2.27%   |
| Lenovo ThinkCentre M75q Gen 5 12RRS01200        | 1         | 2.27%   |
| Lenovo ThinkCentre M715q 10M2S08Y00             | 1         | 2.27%   |
| Intel D2500HN                                   | 1         | 2.27%   |
| IBM ThinkPad T43 1871F1G                        | 1         | 2.27%   |
| HP EliteDesk 800 G3 DM 35W                      | 1         | 2.27%   |
| HP Compaq Presario CQ50                         | 1         | 2.27%   |
| Google Morphius                                 | 1         | 2.27%   |
| Gigabyte H310M DS2 2.0                          | 1         | 2.27%   |
| Gigabyte A620M H                                | 1         | 2.27%   |
| Fujitsu LIFEBOOK E752                           | 1         | 2.27%   |
| Fujitsu ESPRIMO_P556                            | 1         | 2.27%   |
| Framework Laptop 13 (Intel Core Ultra Series 1) | 1         | 2.27%   |
| Dell OptiPlex 9020                              | 1         | 2.27%   |
| Dell Latitude D620                              | 1         | 2.27%   |
| Dell Latitude 7490                              | 1         | 2.27%   |
| Biostar B450MH                                  | 1         | 2.27%   |
| ASUS SABERTOOTH X58                             | 1         | 2.27%   |
| ASUS PRIME B650-PLUS                            | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 9         | 20.45%  |
| Lenovo ThinkCentre                          | 3         | 6.82%   |
| Dell Latitude                               | 2         | 4.55%   |
| Shuttle DS77U                               | 1         | 2.27%   |
| Samsung 535U3C                              | 1         | 2.27%   |
| RPi Raspberry                               | 1         | 2.27%   |
| Panasonic CFSZ6-2                           | 1         | 2.27%   |
| Panasonic CFSX4-1                           | 1         | 2.27%   |
| Panasonic CF-54-1                           | 1         | 2.27%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.27%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.27%   |
| MSI MS-7C02                                 | 1         | 2.27%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.27%   |
| Lenovo Yoga                                 | 1         | 2.27%   |
| Lenovo ThinkStation                         | 1         | 2.27%   |
| Intel D2500HN                               | 1         | 2.27%   |
| IBM ThinkPad                                | 1         | 2.27%   |
| HP EliteDesk                                | 1         | 2.27%   |
| HP Compaq                                   | 1         | 2.27%   |
| Google Morphius                             | 1         | 2.27%   |
| Gigabyte H310M                              | 1         | 2.27%   |
| Gigabyte A620M                              | 1         | 2.27%   |
| Fujitsu LIFEBOOK                            | 1         | 2.27%   |
| Fujitsu ESPRIMO                             | 1         | 2.27%   |
| Framework Laptop                            | 1         | 2.27%   |
| Dell OptiPlex                               | 1         | 2.27%   |
| Biostar B450MH                              | 1         | 2.27%   |
| ASUS SABERTOOTH                             | 1         | 2.27%   |
| ASUS PRIME                                  | 1         | 2.27%   |
| ASUS 900                                    | 1         | 2.27%   |
| ASUS 1000HE                                 | 1         | 2.27%   |
| Acer Aspire                                 | 1         | 2.27%   |
| Unknown                                     | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 7         | 15.91%  |
| 2017    | 5         | 11.36%  |
| 2024    | 4         | 9.09%   |
| 2023    | 3         | 6.82%   |
| 2020    | 3         | 6.82%   |
| 2016    | 3         | 6.82%   |
| 2012    | 3         | 6.82%   |
| 2010    | 3         | 6.82%   |
| 2011    | 2         | 4.55%   |
| 2009    | 2         | 4.55%   |
| 2006    | 2         | 4.55%   |
| 2022    | 1         | 2.27%   |
| 2021    | 1         | 2.27%   |
| 2015    | 1         | 2.27%   |
| 2013    | 1         | 2.27%   |
| 2008    | 1         | 2.27%   |
| 2007    | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 25        | 56.82%  |
| Desktop     | 16        | 36.36%  |
| Mini pc     | 2         | 4.55%   |
| Convertible | 1         | 2.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 97.73%  |
| Yes  | 1         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 10        | 22.73%  |
| 8.01-16.0  | 9         | 20.45%  |
| 2.01-3.0   | 7         | 15.91%  |
| 32.01-64.0 | 6         | 13.64%  |
| 4.01-8.0   | 5         | 11.36%  |
| 3.01-4.0   | 4         | 9.09%   |
| 24.01-32.0 | 2         | 4.55%   |
| 0.01-0.5   | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 34        | 77.27%  |
| 0.51-1.0 | 8         | 18.18%  |
| 0        | 2         | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 53.33%  |
| 2      | 14        | 31.11%  |
| 3      | 3         | 6.67%   |
| 0      | 3         | 6.67%   |
| 4      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 97.73%  |
| Yes       | 1         | 2.27%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 88.64%  |
| No        | 5         | 11.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 72.73%  |
| No        | 12        | 27.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 60%     |
| Yes       | 18        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Canada      | 11        | 25%     |
| USA         | 8         | 18.18%  |
| Russia      | 4         | 9.09%   |
| Germany     | 4         | 9.09%   |
| Italy       | 3         | 6.82%   |
| Spain       | 2         | 4.55%   |
| Finland     | 2         | 4.55%   |
| Vietnam     | 1         | 2.27%   |
| Turkey      | 1         | 2.27%   |
| South Korea | 1         | 2.27%   |
| Paraguay    | 1         | 2.27%   |
| Netherlands | 1         | 2.27%   |
| Malaysia    | 1         | 2.27%   |
| Czechia     | 1         | 2.27%   |
| Croatia     | 1         | 2.27%   |
| Colombia    | 1         | 2.27%   |
| China       | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Montreal         | 11        | 23.91%  |
| St Petersburg    | 3         | 6.52%   |
| Milan            | 2         | 4.35%   |
| Madison          | 2         | 4.35%   |
| Hoffman Estates  | 2         | 4.35%   |
| Zaragoza         | 1         | 2.17%   |
| Wenzhou          | 1         | 2.17%   |
| Waterbury        | 1         | 2.17%   |
| Villalfonsina    | 1         | 2.17%   |
| Valladolid       | 1         | 2.17%   |
| Vaasa            | 1         | 2.17%   |
| Tampere          | 1         | 2.17%   |
| Scottsville      | 1         | 2.17%   |
| Prague           | 1         | 2.17%   |
| Phoenix          | 1         | 2.17%   |
| Ochsenfurt       | 1         | 2.17%   |
| Medellín        | 1         | 2.17%   |
| Louisville       | 1         | 2.17%   |
| Kuala Lumpur     | 1         | 2.17%   |
| Jongno-gu        | 1         | 2.17%   |
| Ho Chi Minh City | 1         | 2.17%   |
| Hanover          | 1         | 2.17%   |
| Dubrovnik        | 1         | 2.17%   |
| Danville         | 1         | 2.17%   |
| Cologne          | 1         | 2.17%   |
| Cherepovets      | 1         | 2.17%   |
| Bursa            | 1         | 2.17%   |
| Bothell          | 1         | 2.17%   |
| Berlin           | 1         | 2.17%   |
| Asunción        | 1         | 2.17%   |
| Assendelft       | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 10        | 10     | 20.41%  |
| Samsung Electronics                    | 8         | 9      | 16.33%  |
| Toshiba                                | 4         | 5      | 8.16%   |
| SanDisk                                | 4         | 4      | 8.16%   |
| Kingston                               | 4         | 4      | 8.16%   |
| Seagate                                | 3         | 4      | 6.12%   |
| PNY                                    | 2         | 6      | 4.08%   |
| A-DATA Technology                      | 2         | 2      | 4.08%   |
| USB3.0                                 | 1         | 2      | 2.04%   |
| SPCC                                   | 1         | 1      | 2.04%   |
| Product:              USB DISK 3.0 Pro | 1         | 1      | 2.04%   |
| LITEONIT                               | 1         | 2      | 2.04%   |
| LITEON                                 | 1         | 1      | 2.04%   |
| Lexar                                  | 1         | 3      | 2.04%   |
| KIOXIA                                 | 1         | 1      | 2.04%   |
| Getrich                                | 1         | 1      | 2.04%   |
| Fujitsu                                | 1         | 1      | 2.04%   |
| Crucial                                | 1         | 1      | 2.04%   |
| ASUSTek Computer                       | 1         | 2      | 2.04%   |
| AGI                                    | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung SSD 990 PRO 1TB                                       | 2         | 3.92%   |
| PNY CS900 1TB SSD                                             | 2         | 3.92%   |
| Kingston SA400S37240G 240GB                                   | 2         | 3.92%   |
| WDC WDS250G2B0A-00SM50 250GB                                  | 1         | 1.96%   |
| WDC WD7500BPKX-00HPJT0 752GB                                  | 1         | 1.96%   |
| WDC WD7500BPKT-75PK4T0 752GB                                  | 1         | 1.96%   |
| WDC WD7500BPKT-00PK4T0 752GB                                  | 1         | 1.96%   |
| WDC WD5000LPLX-00ZNTT0 500GB                                  | 1         | 1.96%   |
| WDC WD3200BEVE-00A0HT0 320GB                                  | 1         | 1.96%   |
| WDC WD3200AAKX-001CA0 320GB                                   | 1         | 1.96%   |
| WDC WD2500BEVT-08A23T1 250GB                                  | 1         | 1.96%   |
| WDC WD10JPLX-00MBPT0 1TB                                      | 1         | 1.96%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                          | 1         | 1.96%   |
| USB3.0 storage 1TB                                            | 1         | 1.96%   |
| Toshiba KXG50ZNV1T02 NVMe 1024GB                              | 1         | 1.96%   |
| Toshiba KBG40ZMT128G MEMORY 128GB                             | 1         | 1.96%   |
| Toshiba DT01ACA100 1TB                                        | 1         | 1.96%   |
| Toshiba DT01ACA050 500GB                                      | 1         | 1.96%   |
| SPCC M.2 PCIe SSD 2TB                                         | 1         | 1.96%   |
| Seagate ST2000DM008-2FR102 2TB                                | 1         | 1.96%   |
| Seagate ST1000VM002-1SD102 1TB                                | 1         | 1.96%   |
| Seagate ST1000LM035-1RK172 1TB                                | 1         | 1.96%   |
| SanDisk SDSSDHII240G 240GB                                    | 1         | 1.96%   |
| SanDisk SD8SN8U-256G-1006 256GB                               | 1         | 1.96%   |
| SanDisk SD6SB1M-128G-1006 128GB                               | 1         | 1.96%   |
| SanDisk Cruzer Fit 8GB                                        | 1         | 1.96%   |
| Samsung SSD 860 EVO M.2 2TB                                   | 1         | 1.96%   |
| Samsung SSD 860 EVO 500GB                                     | 1         | 1.96%   |
| Samsung SSD 860 EVO 2TB                                       | 1         | 1.96%   |
| Samsung SSD 860 EVO 1TB                                       | 1         | 1.96%   |
| Samsung MZVLW256HEHP-000L7 256GB                              | 1         | 1.96%   |
| Samsung MZVLB256HBHQ-000L7 256GB                              | 1         | 1.96%   |
| Samsung MZ7TY256HDHP-000L7 256GB                              | 1         | 1.96%   |
| Product:              USB DISK 3.0 Pro USB DISK 3.0 Pro 128GB | 1         | 1.96%   |
| LITEONIT LCS-128M6S 128GB                                     | 1         | 1.96%   |
| LITEON L8H-128V2G-11 M.2 2280 128GB                           | 1         | 1.96%   |
| Lexar 128GB SSD                                               | 1         | 1.96%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                                | 1         | 1.96%   |
| Kingston SA400S37960G 960GB                                   | 1         | 1.96%   |
| Kingston DataTraveler 3.0 64GB                                | 1         | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 8         | 8      | 50%     |
| Seagate                                | 3         | 4      | 18.75%  |
| Toshiba                                | 2         | 3      | 12.5%   |
| USB3.0                                 | 1         | 2      | 6.25%   |
| Product:              USB DISK 3.0 Pro | 1         | 1      | 6.25%   |
| Fujitsu                                | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 16.67%  |
| Samsung Electronics | 4         | 5      | 16.67%  |
| Kingston            | 4         | 4      | 16.67%  |
| PNY                 | 2         | 6      | 8.33%   |
| A-DATA Technology   | 2         | 2      | 8.33%   |
| WDC                 | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 2      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Lexar               | 1         | 3      | 4.17%   |
| Getrich             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| ASUSTek Computer    | 1         | 2      | 4.17%   |
| AGI                 | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 33     | 47.62%  |
| HDD  | 13        | 19     | 30.95%  |
| NVMe | 9         | 9      | 21.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 52     | 76.92%  |
| NVMe | 9         | 9      | 23.08%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 29     | 58.33%  |
| 0.51-1.0   | 12        | 18     | 33.33%  |
| 1.01-2.0   | 3         | 5      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 31.11%  |
| 251-500        | 10        | 22.22%  |
| 21-50          | 9         | 20%     |
| 51-100         | 5         | 11.11%  |
| 1-20           | 2         | 4.44%   |
| 501-1000       | 2         | 4.44%   |
| More than 3000 | 1         | 2.22%   |
| 2001-3000      | 1         | 2.22%   |
| 1001-2000      | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 82.22%  |
| 21-50     | 3         | 6.67%   |
| 501-1000  | 2         | 4.44%   |
| 251-500   | 1         | 2.22%   |
| 2001-3000 | 1         | 2.22%   |
| 51-100    | 1         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB         | 1         | 1      | 25%     |
| Toshiba DT01ACA050 500GB       | 1         | 2      | 25%     |
| Seagate ST2000DM008-2FR102 2TB | 1         | 2      | 25%     |
| A-DATA Technology SP550 480GB  | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 3      | 50%     |
| Seagate           | 1         | 2      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 5      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 36        | 52     | 85.71%  |
| Malfunc  | 4         | 6      | 9.52%   |
| Detected | 2         | 3      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 27        | 55.1%   |
| Samsung Electronics         | 6         | 12.24%  |
| AMD                         | 6         | 12.24%  |
| SanDisk                     | 4         | 8.16%   |
| KIOXIA                      | 2         | 4.08%   |
| Toshiba                     | 1         | 2.04%   |
| Marvell Technology Group    | 1         | 2.04%   |
| Kingston Technology Company | 1         | 2.04%   |
| JMicron Technology          | 1         | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 7.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 7.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 5.77%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.77%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2         | 3.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.85%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 3.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 3.85%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 2         | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 3.85%   |
| AMD 600 Series Chipset SATA Controller                                         | 2         | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 3.85%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.92%   |
| Toshiba XG5 NVMe SSD Controller                                                | 1         | 1.92%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.92%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.92%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 1.92%   |
| Kingston Company OM8SEP4 Design-In PCIe 4 NVMe SSD (TLC) (DRAM-less)           | 1         | 1.92%   |
| JMicron JMB362 SATA Controller                                                 | 1         | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.92%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.92%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 55.1%   |
| NVMe | 14        | 28.57%  |
| IDE  | 8         | 16.33%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 79.55%  |
| AMD    | 8         | 18.18%  |
| ARM    | 1         | 2.27%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz                            | 2         | 4.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz                            | 2         | 4.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 2         | 4.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 2         | 4.55%   |
| Intel Pentium M processor                                    | 1         | 2.27%   |
| Intel Pentium III ("GenuineIntel" 686-class, 512KB L2 cache) | 1         | 2.27%   |
| Intel Genuine CPU T2300 @ 1.66GHz                            | 1         | 2.27%   |
| Intel Core Ultra 5 125H                                      | 1         | 2.27%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz                             | 1         | 2.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz                             | 1         | 2.27%   |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 1         | 2.27%   |
| Intel Core i7 CPU 960 @ 3.20GHz                              | 1         | 2.27%   |
| Intel Core i5-8350U CPU @ 1.70GHz                            | 1         | 2.27%   |
| Intel Core i5-7300U CPU @ 2.60GHz                            | 1         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz                            | 1         | 2.27%   |
| Intel Core i5-6500T CPU @ 2.50GHz                            | 1         | 2.27%   |
| Intel Core i5-6500 CPU @ 3.20GHz                             | 1         | 2.27%   |
| Intel Core i5-4570 CPU @ 3.20GHz                             | 1         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 1         | 2.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz                            | 1         | 2.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz                           | 1         | 2.27%   |
| Intel Core i3-N305                                           | 1         | 2.27%   |
| Intel Core i3-9100F CPU @ 3.60GHz                            | 1         | 2.27%   |
| Intel Core i3-6100T CPU @ 3.20GHz                            | 1         | 2.27%   |
| Intel Core Duo CPU                                           | 1         | 2.27%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz                         | 1         | 2.27%   |
| Intel Core 2 CPU T7200 @ 2.00GHz ("GenuineIntel" 686-class)  | 1         | 2.27%   |
| Intel Celeron M processor                                    | 1         | 2.27%   |
| Intel Celeron CPU 3865U @ 1.80GHz                            | 1         | 2.27%   |
| Intel Atom CPU N280 @ 1.66GHz                                | 1         | 2.27%   |
| Intel Atom CPU D2500 @ 1.86GHz                               | 1         | 2.27%   |
| ARM Cortex-A72 r0p3                                          | 1         | 2.27%   |
| AMD Ryzen 7 PRO 8700GE w/ Radeon 780M Graphics               | 1         | 2.27%   |
| AMD Ryzen 7 8700G w/ Radeon 780M Graphics                    | 1         | 2.27%   |
| AMD Ryzen 5 8500G w/ Radeon 740M Graphics                    | 1         | 2.27%   |
| AMD Ryzen 5 4600G with Radeon Graphics                       | 1         | 2.27%   |
| AMD Ryzen 5 3600XT 6-Core Processor                          | 1         | 2.27%   |
| AMD Ryzen 5 3500C with Radeon Vega Mobile Gfx                | 1         | 2.27%   |
| AMD PRO A6-8570E R5, 6 COMPUTE CORES 2C+4G                   | 1         | 2.27%   |
| AMD A6-4455M APU with Radeon HD Graphics                     | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 15        | 34.09%  |
| Intel Core i7     | 5         | 11.36%  |
| AMD Ryzen 5       | 4         | 9.09%   |
| Intel Core i3     | 3         | 6.82%   |
| Intel Atom        | 2         | 4.55%   |
| Other             | 1         | 2.27%   |
| Intel Pentium M   | 1         | 2.27%   |
| Intel Pentium III | 1         | 2.27%   |
| Intel Genuine     | 1         | 2.27%   |
| Intel Core m7     | 1         | 2.27%   |
| Intel Core Duo    | 1         | 2.27%   |
| Intel Core 2 Duo  | 1         | 2.27%   |
| Intel Core 2      | 1         | 2.27%   |
| Intel Core        | 1         | 2.27%   |
| Intel Celeron M   | 1         | 2.27%   |
| Intel Celeron     | 1         | 2.27%   |
| ARM Cortex        | 1         | 2.27%   |
| AMD Ryzen 7 PRO   | 1         | 2.27%   |
| AMD Ryzen 7       | 1         | 2.27%   |
| AMD A6            | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15        | 34.09%  |
| 4       | 10        | 22.73%  |
| Unknown | 9         | 20.45%  |
| 1       | 3         | 6.82%   |
| 16      | 2         | 4.55%   |
| 12      | 2         | 4.55%   |
| 8       | 2         | 4.55%   |
| 9       | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 37        | 84.09%  |
| Unknown | 7         | 15.91%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 19        | 43.18%  |
| 1       | 13        | 29.55%  |
| Unknown | 12        | 27.27%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 8         | 18.18%  |
| Skylake     | 7         | 15.91%  |
| KabyLake    | 7         | 15.91%  |
| P6          | 5         | 11.36%  |
| Westmere    | 2         | 4.55%   |
| IvyBridge   | 2         | 4.55%   |
| Broadwell   | 2         | 4.55%   |
| Bonnell     | 2         | 4.55%   |
| Zen+        | 1         | 2.27%   |
| Zen 2       | 1         | 2.27%   |
| SandyBridge | 1         | 2.27%   |
| Piledriver  | 1         | 2.27%   |
| Penryn      | 1         | 2.27%   |
| Nehalem     | 1         | 2.27%   |
| Haswell     | 1         | 2.27%   |
| Excavator   | 1         | 2.27%   |
| Core        | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 31        | 72.09%  |
| AMD                                  | 10        | 23.26%  |
| NVidia / SGS Thomson (Joint Venture) | 1         | 2.33%   |
| Nvidia                               | 1         | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                         | 4         | 8.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 6.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 4.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 4.35%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 4.35%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 2         | 4.35%   |
| Intel HD Graphics 620                                                         | 2         | 4.35%   |
| Intel HD Graphics 5500                                                        | 2         | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 4.35%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 4.35%   |
| AMD Phoenix1                                                                  | 2         | 4.35%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                 | 1         | 2.17%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                  | 1         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 2.17%   |
| Intel UHD Graphics 620                                                        | 1         | 2.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 2.17%   |
| Intel Meteor Lake-P [Intel Graphics]                                          | 1         | 2.17%   |
| Intel HD Graphics 610                                                         | 1         | 2.17%   |
| Intel HD Graphics 515                                                         | 1         | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 2.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 2.17%   |
| Intel Alder Lake-N [UHD Graphics]                                             | 1         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 2.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 2.17%   |
| AMD Turks XT [Radeon HD 6670/7670]                                            | 1         | 2.17%   |
| AMD Trinity [Radeon HD 7500G]                                                 | 1         | 2.17%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 1         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.17%   |
| AMD Phoenix2                                                                  | 1         | 2.17%   |
| AMD Oland GL [FirePro W2100]                                                  | 1         | 2.17%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 25        | 56.82%  |
| 1 x AMD                                  | 10        | 22.73%  |
| 2 x Intel                                | 6         | 13.64%  |
| Other                                    | 1         | 2.27%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 2.27%   |
| 1 x Nvidia                               | 1         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 41        | 93.18%  |
| Unknown | 3         | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 4         | 13.33%  |
| Chimei Innolux       | 4         | 13.33%  |
| Samsung Electronics  | 3         | 10%     |
| Philips              | 3         | 10%     |
| Dell                 | 2         | 6.67%   |
| BOE                  | 2         | 6.67%   |
| AU Optronics         | 2         | 6.67%   |
| Acer                 | 2         | 6.67%   |
| Sharp                | 1         | 3.33%   |
| LG Philips           | 1         | 3.33%   |
| Lenovo               | 1         | 3.33%   |
| HKC                  | 1         | 3.33%   |
| Hewlett-Packard      | 1         | 3.33%   |
| Goldstar             | 1         | 3.33%   |
| ASUSTek Computer     | 1         | 3.33%   |
| Ancor Communications | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 2         | 6.67%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch       | 2         | 6.67%   |
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch                | 1         | 3.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3246 1366x768 290x160mm 13.0-inch   | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch   | 1         | 3.33%   |
| Philips 221B PHL08A1 1920x1080 480x270mm 21.7-inch                     | 1         | 3.33%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD05A2 1920x1080 310x170mm 13.9-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 3.33%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 1         | 3.33%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch           | 1         | 3.33%   |
| Lenovo LEN L174 LEN240B 1280x1024 340x270mm 17.1-inch                  | 1         | 3.33%   |
| HKC F2145M HKC2251 1920x1080 480x260mm 21.5-inch                       | 1         | 3.33%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 520x330mm 24.2-inch           | 1         | 3.33%   |
| Goldstar BL450 GSM5B86 1920x1080 480x270mm 21.7-inch                   | 1         | 3.33%   |
| Dell U2720Q DEL41B5 3840x2160 600x340mm 27.2-inch                      | 1         | 3.33%   |
| Dell P2412H DELA07C 1920x1080 530x300mm 24.0-inch                      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 290x170mm 13.2-inch       | 1         | 3.33%   |
| BOE LCD Monitor BOE0BCA 2256x1504 280x190mm 13.3-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE07CB 1920x1080 340x190mm 15.3-inch                  | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO1A87 1920x1080 290x170mm 13.2-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO1068 1920x1200 260x170mm 12.2-inch         | 1         | 3.33%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch           | 1         | 3.33%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 620x340mm 27.8-inch | 1         | 3.33%   |
| Acer V277 E ACR0B7C 1920x1080 600x330mm 27.0-inch                      | 1         | 3.33%   |
| Acer ET322QU ACR0687 2560x1440 700x390mm 31.5-inch                     | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 53.33%  |
| 1366x768 (WXGA)   | 4         | 13.33%  |
| 3840x2160 (4K)    | 3         | 10%     |
| 2560x1440 (QHD)   | 2         | 6.67%   |
| 1920x1200 (WUXGA) | 2         | 6.67%   |
| 2256x1504         | 1         | 3.33%   |
| 1280x800 (WXGA)   | 1         | 3.33%   |
| 1280x1024 (SXGA)  | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 7         | 23.33%  |
| 21     | 5         | 16.67%  |
| 12     | 5         | 16.67%  |
| 27     | 4         | 13.33%  |
| 15     | 4         | 13.33%  |
| 24     | 3         | 10%     |
| 31     | 1         | 3.33%   |
| 17     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 201-300     | 9         | 30%     |
| 301-350     | 8         | 26.67%  |
| 501-600     | 5         | 16.67%  |
| 401-500     | 5         | 16.67%  |
| 601-700     | 3         | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 83.33%  |
| 3/2   | 2         | 6.67%   |
| 16/10 | 2         | 6.67%   |
| 5/4   | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 6         | 20%     |
| 61-70          | 5         | 16.67%  |
| 81-90          | 4         | 13.33%  |
| 301-350        | 4         | 13.33%  |
| 71-80          | 3         | 10%     |
| 101-110        | 3         | 10%     |
| 351-500        | 1         | 3.33%   |
| 251-300        | 1         | 3.33%   |
| 151-200        | 1         | 3.33%   |
| 141-150        | 1         | 3.33%   |
| 91-100         | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 161-240 | 8         | 26.67%  |
| 121-160 | 8         | 26.67%  |
| 51-100  | 8         | 26.67%  |
| 101-120 | 6         | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 80.85%  |
| 0     | 7         | 14.89%  |
| 2     | 2         | 4.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 53.85%  |
| Realtek Semiconductor    | 13        | 25%     |
| Qualcomm Atheros         | 5         | 9.62%   |
| Broadcom                 | 3         | 5.77%   |
| Sierra Wireless          | 1         | 1.92%   |
| MediaTek                 | 1         | 1.92%   |
| Marvell Technology Group | 1         | 1.92%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 8         | 10.67%  |
| Intel Wireless 8265 / 8275                                              | 4         | 5.33%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 4%      |
| Intel Wireless 8260                                                     | 2         | 2.67%   |
| Intel Wireless 7265                                                     | 2         | 2.67%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 2.67%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 2.67%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 2.67%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 2.67%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 2.67%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.67%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 2.67%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 1.33%   |
| Realtek USB 2.5GbE Controller                                           | 1         | 1.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1         | 1.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 1.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| MediaTek USB Ethernet-RNDIS                                             | 1         | 1.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 1.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.33%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 1.33%   |
| Intel Ethernet Connection I217-LM                                       | 1         | 1.33%   |
| Intel Ethernet Connection (5) I219-LM                                   | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 1.33%   |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 71.88%  |
| Qualcomm Atheros      | 4         | 12.5%   |
| Realtek Semiconductor | 3         | 9.38%   |
| Broadcom              | 2         | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 4         | 12.5%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 9.38%   |
| Intel Wireless 8260                                                     | 2         | 6.25%   |
| Intel Wireless 7265                                                     | 2         | 6.25%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 6.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 6.25%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 6.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 6.25%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 3.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 3.13%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.13%   |
| Intel CNVi: Wi-Fi                                                       | 1         | 3.13%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 3.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 55%     |
| Realtek Semiconductor    | 12        | 30%     |
| Qualcomm Atheros         | 2         | 5%      |
| Broadcom                 | 2         | 5%      |
| MediaTek                 | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 19.51%  |
| Intel Ethernet Connection I219-LM                                      | 3         | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 7.32%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 4.88%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 4.88%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 4.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 4.88%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 4.88%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 2.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 2.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1         | 2.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 2.44%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 2.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 2.44%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.44%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.44%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 2.44%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.44%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 2.44%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 2.44%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 53.42%  |
| WiFi     | 32        | 43.84%  |
| Modem    | 1         | 1.37%   |
| Unknown  | 1         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 27        | 54%     |
| WiFi     | 23        | 46%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 56.82%  |
| 1     | 17        | 38.64%  |
| 3     | 1         | 2.27%   |
| 0     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 91.11%  |
| Yes  | 4         | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 61.11%  |
| Alps Electric                   | 2         | 11.11%  |
| Realtek Semiconductor           | 1         | 5.56%   |
| Qualcomm Atheros Communications | 1         | 5.56%   |
| Foxconn / Hon Hai               | 1         | 5.56%   |
| Broadcom                        | 1         | 5.56%   |
| ASUSTek Computer                | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 7         | 38.89%  |
| Intel AX201 Bluetooth                                    | 2         | 11.11%  |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 11.11%  |
| Realtek Bluetooth Adapter                                | 1         | 5.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1         | 5.56%   |
| Intel AX210 Bluetooth                                    | 1         | 5.56%   |
| Intel AX200 Bluetooth                                    | 1         | 5.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 5.56%   |
| Broadcom Bluetooth 4.1 USB                               | 1         | 5.56%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 65.31%  |
| AMD                 | 10        | 20.41%  |
| Logitech            | 2         | 4.08%   |
| Focusrite-Novation  | 1         | 2.04%   |
| ESS Technology      | 1         | 2.04%   |
| Creative Technology | 1         | 2.04%   |
| Creative Labs       | 1         | 2.04%   |
| C-Media Electronics | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                           | Computers | Percent |
|-------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                 | 6         | 10.17%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5         | 8.47%   |
| Intel 200 Series PCH HD Audio                                                                   | 4         | 6.78%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 4         | 6.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 3         | 5.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 2         | 3.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                          | 2         | 3.39%   |
| Intel Broadwell-U Audio Controller                                                              | 2         | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 2         | 3.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 2         | 3.39%   |
| Logitech HD Webcam C910                                                                         | 1         | 1.69%   |
| Logitech G560 Gaming Speaker                                                                    | 1         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1         | 1.69%   |
| Intel Meteor Lake-P HD Audio Controller                                                         | 1         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                    | 1         | 1.69%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                         | 1         | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 1         | 1.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                      | 1         | 1.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 1         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1         | 1.69%   |
| Focusrite-Novation Scarlett 2i2 3rd Gen                                                         | 1         | 1.69%   |
| ESS Technology ES1978 Maestro 2E                                                                | 1         | 1.69%   |
| Creative Technology Sound Blaster Play! 3                                                       | 1         | 1.69%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1         | 1.69%   |
| C-Media Electronics C-Media USB Audio Device                                                    | 1         | 1.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                       | 1         | 1.69%   |
| AMD Trinity HDMI Audio Controller                                                               | 1         | 1.69%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 1         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 1         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 1         | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 1         | 1.69%   |
| AMD Navi 10 HDMI Audio                                                                          | 1         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                        | 1         | 1.69%   |
| AMD FCH Azalia Controller                                                                       | 1         | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 1         | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 31.58%  |
| Unknown             | 5         | 26.32%  |
| SK hynix            | 3         | 15.79%  |
| Unknown             | 3         | 15.79%  |
| Micron Technology   | 2         | 10.53%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 3         | 15%     |
| Unknown RAM Module 1GB SODIMM DDR2                       | 2         | 10%     |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s    | 2         | 10%     |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1         | 5%      |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s              | 1         | 5%      |
| Unknown RAM Module 1GB SODIMM DDR                        | 1         | 5%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 5%      |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s   | 1         | 5%      |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1         | 5%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 5%      |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 5%      |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 1         | 5%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 1         | 5%      |
| Samsung RAM M425R2GA3PB0-CWMOD 16GB SODIMM DDR5 5600MT/s | 1         | 5%      |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 5%      |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 6         | 33.33%  |
| DDR3    | 5         | 27.78%  |
| DDR2    | 3         | 16.67%  |
| SDRAM   | 1         | 5.56%   |
| DDR5    | 1         | 5.56%   |
| DDR     | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 16        | 88.89%  |
| DIMM   | 2         | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 36.84%  |
| 2048  | 5         | 26.32%  |
| 4096  | 3         | 15.79%  |
| 1024  | 3         | 15.79%  |
| 16384 | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 5         | 27.78%  |
| 2133    | 3         | 16.67%  |
| 2667    | 2         | 11.11%  |
| 1333    | 2         | 11.11%  |
| 1067    | 2         | 11.11%  |
| 5600    | 1         | 5.56%   |
| 2400    | 1         | 5.56%   |
| 1600    | 1         | 5.56%   |
| 400     | 1         | 5.56%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Bison Electronics             | 8         | 44.44%  |
| Chicony Electronics           | 4         | 22.22%  |
| Sunplus Innovation Technology | 1         | 5.56%   |
| Silicon Motion                | 1         | 5.56%   |
| Realtek Semiconductor         | 1         | 5.56%   |
| Lite-On Technology            | 1         | 5.56%   |
| IMC Networks                  | 1         | 5.56%   |
| Framework                     | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 4         | 22.22%  |
| Bison USB HD Webcam                      | 2         | 11.11%  |
| Sunplus LTD, NexiGo N930AF FHD Webcam    | 1         | 5.56%   |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 5.56%   |
| Realtek Integrated Webcam HD             | 1         | 5.56%   |
| Lite-On Integrated Camera                | 1         | 5.56%   |
| IMC Networks Integrated Camera           | 1         | 5.56%   |
| Framework Laptop Webcam Module (2nd Gen) | 1         | 5.56%   |
| Chicony Webcam                           | 1         | 5.56%   |
| Chicony Integrated Camera                | 1         | 5.56%   |
| Chicony FJ Camera                        | 1         | 5.56%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 5.56%   |
| Bison SunplusIT Integrated Camera        | 1         | 5.56%   |
| Bison Lenovo EasyCamera                  | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 28.57%  |
| STMicroelectronics         | 2         | 28.57%  |
| Synaptics                  | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader             | 2         | 28.57%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                | 1         | 14.29%  |
| AuthenTec AES2660                                 | 1         | 14.29%  |

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
| 1     | 29        | 65.91%  |
| 0     | 8         | 18.18%  |
| 2     | 6         | 13.64%  |
| 5     | 1         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 24        | 54.55%  |
| Graphics card            | 7         | 15.91%  |
| Firewire controller      | 4         | 9.09%   |
| Storage/ata              | 2         | 4.55%   |
| Sound                    | 2         | 4.55%   |
| Net/wireless             | 2         | 4.55%   |
| Network                  | 1         | 2.27%   |
| Net/ethernet             | 1         | 2.27%   |
| Modem                    | 1         | 2.27%   |

