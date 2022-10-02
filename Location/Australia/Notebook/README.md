BSD in Australia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 49

| Vendor  | Model                       | Probe                                                     | Date         |
|---------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo  | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Dell    | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| HP      | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Lenovo  | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP      | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| HP      | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| HP      | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP      | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Dell    | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Samsung | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Dell    | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Toshiba | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple   | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| HP      | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo  | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo  | ThinkPad X1 Carbon 3443C... | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo  | ThinkPad X1 Carbon 3443C... | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| Lenovo  | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Intel   | SandyBridge Platform        | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| Toshiba | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Apple   | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ASUSTek | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Dell    | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| HP      | ProBook 430 G3              | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown | Unknown                     | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo  | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo  | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo  | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Toshiba | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo  | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo  | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| ASUSTek | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| HP      | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo  | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo  | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo  | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Acer    | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer    | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Apple   | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo  | ThinkPad T460p 20FXCTO1W... | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo  | ThinkPad T470 W10DG 20JM... | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Lenovo  | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| FreeBSD 13.0        | 4         | 10.53%  |
| OpenBSD 6.8         | 3         | 7.89%   |
| helloSystem 0.4.0   | 3         | 7.89%   |
| OPNsense 22.1.6     | 2         | 5.26%   |
| OPNsense 21.1.3     | 2         | 5.26%   |
| helloSystem 0.6.0   | 2         | 5.26%   |
| FreeBSD 12.2        | 2         | 5.26%   |
| FreeBSD 12.1-p10    | 2         | 5.26%   |
| FreeBSD 12.1        | 2         | 5.26%   |
| OPNsense 22.1.1     | 1         | 2.63%   |
| OPNsense 21.7.1     | 1         | 2.63%   |
| OPNsense 21.7       | 1         | 2.63%   |
| OpenBSD 6.7         | 1         | 2.63%   |
| NomadBSD 1.4        | 1         | 2.63%   |
| helloSystem 0.5.0   | 1         | 2.63%   |
| FuguIta 7.1         | 1         | 2.63%   |
| FreeBSD 13.1        | 1         | 2.63%   |
| FreeBSD 13.0-RC5    | 1         | 2.63%   |
| FreeBSD 13.0-p7     | 1         | 2.63%   |
| FreeBSD 13.0-p6     | 1         | 2.63%   |
| FreeBSD 13.0-BETA1  | 1         | 2.63%   |
| FreeBSD 12.2-p3     | 1         | 2.63%   |
| FreeBSD 12.2-p2     | 1         | 2.63%   |
| FreeBSD 12.1-p6     | 1         | 2.63%   |
| FreeBSD 11.4-STABLE | 1         | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 15        | 44.12%  |
| OPNsense    | 7         | 20.59%  |
| helloSystem | 6         | 17.65%  |
| OpenBSD     | 4         | 11.76%  |
| NomadBSD    | 1         | 2.94%   |
| FuguIta     | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 33        | 97.06%  |
| i386  | 1         | 2.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 9         | 25.71%  |
| helloDesktop | 7         | 20%     |
| fvwm         | 4         | 11.43%  |
| XFCE         | 3         | 8.57%   |
| KDE5         | 3         | 8.57%   |
| GNOME        | 3         | 8.57%   |
| i3           | 2         | 5.71%   |
| TWM          | 1         | 2.86%   |
| Openbox      | 1         | 2.86%   |
| Fluxbox      | 1         | 2.86%   |
| AwesomeWM    | 1         | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 24        | 70.59%  |
| Console | 9         | 26.47%  |
| Wayland | 1         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 19        | 54.29%  |
| SLiM    | 7         | 20%     |
| SDDM    | 5         | 14.29%  |
| XDM     | 1         | 2.86%   |
| PCDM    | 1         | 2.86%   |
| Ly      | 1         | 2.86%   |
| GDM     | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 16        | 43.24%  |
| en_US           | 9         | 24.32%  |
| C               | 6         | 16.22%  |
| en_AU           | 4         | 10.81%  |
| en_AU.US-ASCII  | 1         | 2.7%    |
| en_AU.ISO8859-1 | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 73.53%  |
| BIOS | 9         | 26.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 16        | 47.06%  |
| Ufs  | 13        | 38.24%  |
| Ffs  | 5         | 14.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 27        | 79.41%  |
| MBR  | 7         | 20.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 44.12%  |
| Hewlett-Packard     | 5         | 14.71%  |
| Toshiba             | 3         | 8.82%   |
| Apple               | 3         | 8.82%   |
| Dell                | 2         | 5.88%   |
| ASUSTek Computer    | 2         | 5.88%   |
| Samsung Electronics | 1         | 2.94%   |
| Intel               | 1         | 2.94%   |
| Acer                | 1         | 2.94%   |
| Unknown             | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Toshiba Satellite L50-A                                                                  | 1         | 2.94%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 2.94%   |
| Toshiba KIRA                                                                             | 1         | 2.94%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 2.94%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 2.94%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 2.94%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 2.94%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 2.94%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 2.94%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 2.94%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 2.94%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 2.94%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 2.94%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 2.94%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 2.94%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 2.94%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 2.94%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 2.94%   |
| Lenovo G40-70 20369                                                                      | 1         | 2.94%   |
| Intel SandyBridge Platform                                                               | 1         | 2.94%   |
| HP ZBook 14                                                                              | 1         | 2.94%   |
| HP Setzer                                                                                | 1         | 2.94%   |
| HP ProBook 430 G3                                                                        | 1         | 2.94%   |
| HP Notebook                                                                              | 1         | 2.94%   |
| HP Laptop 15s-du1xxx                                                                     | 1         | 2.94%   |
| Dell Latitude E7450                                                                      | 1         | 2.94%   |
| Dell G5 5590                                                                             | 1         | 2.94%   |
| ASUS TP500LNG                                                                            | 1         | 2.94%   |
| ASUS K72F                                                                                | 1         | 2.94%   |
| Apple MacBookPro5,5                                                                      | 1         | 2.94%   |
| Apple MacBookPro11,3                                                                     | 1         | 2.94%   |
| Apple MacBookAir5,1                                                                      | 1         | 2.94%   |
| Acer Peppy                                                                               | 1         | 2.94%   |
| Unknown                                                                                  | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 41.18%  |
| Toshiba Satellite  | 1         | 2.94%   |
| Toshiba PORTEGE    | 1         | 2.94%   |
| Toshiba KIRA       | 1         | 2.94%   |
| Samsung 350V5C     | 1         | 2.94%   |
| Lenovo G40-70      | 1         | 2.94%   |
| Intel SandyBridge  | 1         | 2.94%   |
| HP ZBook           | 1         | 2.94%   |
| HP Setzer          | 1         | 2.94%   |
| HP ProBook         | 1         | 2.94%   |
| HP Notebook        | 1         | 2.94%   |
| HP Laptop          | 1         | 2.94%   |
| Dell Latitude      | 1         | 2.94%   |
| Dell G5            | 1         | 2.94%   |
| ASUS TP500LNG      | 1         | 2.94%   |
| ASUS K72F          | 1         | 2.94%   |
| Apple MacBookPro5  | 1         | 2.94%   |
| Apple MacBookPro11 | 1         | 2.94%   |
| Apple MacBookAir5  | 1         | 2.94%   |
| Acer Peppy         | 1         | 2.94%   |
| Unknown            | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 11.76%  |
| 2017 | 4         | 11.76%  |
| 2015 | 4         | 11.76%  |
| 2014 | 4         | 11.76%  |
| 2012 | 4         | 11.76%  |
| 2020 | 3         | 8.82%   |
| 2018 | 2         | 5.88%   |
| 2016 | 2         | 5.88%   |
| 2013 | 2         | 5.88%   |
| 2010 | 2         | 5.88%   |
| 2011 | 1         | 2.94%   |
| 2009 | 1         | 2.94%   |
| 2007 | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 34        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 94.12%  |
| Yes  | 2         | 5.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 16        | 47.06%  |
| 16.01-24.0 | 8         | 23.53%  |
| 4.01-8.0   | 5         | 14.71%  |
| 1.01-2.0   | 2         | 5.88%   |
| 32.01-64.0 | 1         | 2.94%   |
| 3.01-4.0   | 1         | 2.94%   |
| 2.01-3.0   | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 17        | 48.57%  |
| 0.51-1.0 | 12        | 34.29%  |
| 4.01-8.0 | 2         | 5.71%   |
| 1.01-2.0 | 2         | 5.71%   |
| 2.01-3.0 | 1         | 2.86%   |
| 0        | 1         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 91.18%  |
| 2      | 2         | 5.88%   |
| 0      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 82.35%  |
| Yes       | 6         | 17.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 85.29%  |
| No        | 5         | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 91.18%  |
| No        | 3         | 8.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 61.76%  |
| No        | 13        | 38.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 34        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 8         | 23.53%  |
| Brisbane     | 6         | 17.65%  |
| Melbourne    | 5         | 14.71%  |
| Perth        | 4         | 11.76%  |
| Canberra     | 3         | 8.82%   |
| South Yarra  | 1         | 2.94%   |
| Ryde         | 1         | 2.94%   |
| Kellyville   | 1         | 2.94%   |
| East Malvern | 1         | 2.94%   |
| Darlinghurst | 1         | 2.94%   |
| Burwood      | 1         | 2.94%   |
| Adelaide CBD | 1         | 2.94%   |
| Adelaide     | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 24.24%  |
| Toshiba             | 6         | 7      | 18.18%  |
| Intel               | 4         | 4      | 12.12%  |
| Seagate             | 2         | 3      | 6.06%   |
| SanDisk             | 2         | 3      | 6.06%   |
| Kingston            | 2         | 2      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 3      | 3.03%   |
| Silicon Motion      | 1         | 1      | 3.03%   |
| Jetflash            | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Dogfish             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB      | 2         | 6.06%   |
| Samsung SSD 840 EVO 250GB        | 2         | 6.06%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1         | 3.03%   |
| Toshiba THNSNF256GMCS 256GB      | 1         | 3.03%   |
| Toshiba THNSF5256GCJ7 256GB      | 1         | 3.03%   |
| Toshiba MQ01ABF050 500GB         | 1         | 3.03%   |
| Toshiba MQ01ABD100 1TB           | 1         | 3.03%   |
| SK hynix BC501 NVMe 512GB        | 1         | 3.03%   |
| Silicon Motion Aura Pro X2 960GB | 1         | 3.03%   |
| Seagate ST9500325AS 500GB        | 1         | 3.03%   |
| Seagate ST9250315ASG 250GB       | 1         | 3.03%   |
| SanDisk SD8TN8U256G1001 256GB    | 1         | 3.03%   |
| SanDisk SD5SG2128G1052E 128GB    | 1         | 3.03%   |
| Samsung SSD PM871 mSATA 256GB    | 1         | 3.03%   |
| Samsung SSD 860 EVO 500GB        | 1         | 3.03%   |
| Samsung MZVLB512HBJQ-000H1 512GB | 1         | 3.03%   |
| Samsung MZNLN256HCHP-000L7 256GB | 1         | 3.03%   |
| Samsung MZMTE128HMGR-00000 128GB | 1         | 3.03%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 3.03%   |
| Kingston SV300S37A120G 120GB     | 1         | 3.03%   |
| Kingston SNS4151S316G 16GB       | 1         | 3.03%   |
| Jetflash Transcend 8G            | 1         | 3.03%   |
| Intel SSDSC2KW128G8 128GB        | 1         | 3.03%   |
| Intel SSDSC2BF180A4L 180GB       | 1         | 3.03%   |
| Intel SSDSA2BW160G3L 160GB       | 1         | 3.03%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 3.03%   |
| HGST HTS725050A7E630 500GB       | 1         | 3.03%   |
| Fujitsu MHY2160BH 160GB          | 1         | 3.03%   |
| Dogfish SSD 64GB                 | 1         | 3.03%   |
| Crucial CT480BX200SSD1 480GB     | 1         | 3.03%   |
| Apple SSD SM256E 256GB           | 1         | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 2         | 2      | 25%     |
| Seagate  | 2         | 3      | 25%     |
| WDC      | 1         | 1      | 12.5%   |
| Jetflash | 1         | 1      | 12.5%   |
| HGST     | 1         | 1      | 12.5%   |
| Fujitsu  | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 38.89%  |
| Intel               | 3         | 3      | 16.67%  |
| SanDisk             | 2         | 3      | 11.11%  |
| Kingston            | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Dogfish             | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 19     | 54.55%  |
| HDD  | 8         | 9      | 24.24%  |
| NVMe | 7         | 10     | 21.21%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 28     | 78.13%  |
| NVMe | 7         | 10     | 21.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 26     | 92%     |
| 0.51-1.0   | 2         | 2      | 8%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 38.24%  |
| 251-500    | 7         | 20.59%  |
| 1-20       | 7         | 20.59%  |
| 51-100     | 4         | 11.76%  |
| 501-1000   | 2         | 5.88%   |
| 21-50      | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 30        | 83.33%  |
| 21-50   | 3         | 8.33%   |
| 51-100  | 2         | 5.56%   |
| 101-250 | 1         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Kingston SNS4151S316G 16GB | 1         | 1      | 25%     |
| Intel SSDSC2BF180A4L 180GB | 1         | 1      | 25%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 25%     |
| Apple SSD SM256E 256GB     | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 1         | 1      | 25%     |
| Intel    | 1         | 1      | 25%     |
| HGST     | 1         | 1      | 25%     |
| Apple    | 1         | 1      | 25%     |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 28        | 34     | 87.5%   |
| Malfunc | 4         | 4      | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 27        | 79.41%  |
| Toshiba             | 3         | 8.82%   |
| Silicon Motion      | 1         | 2.94%   |
| Samsung Electronics | 1         | 2.94%   |
| Nvidia              | 1         | 2.94%   |
| AMD                 | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 20%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 8.57%   |
| Toshiba XG4 NVMe SSD Controller                                                | 2         | 5.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 5.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 5.71%   |
| Toshiba NVMe Controller                                                        | 1         | 2.86%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.86%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 2.86%   |
| Intel SSD 660P Series                                                          | 1         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 26        | 74.29%  |
| NVMe | 6         | 17.14%  |
| RAID | 2         | 5.71%   |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 97.06%  |
| AMD    | 1         | 2.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i7-4510U CPU @ 2.00GHz                             | 2         | 5.88%   |
| Intel Core i7-3667U CPU @ 2.00GHz                             | 2         | 5.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 5.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 2         | 5.88%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH                            | 1         | 2.94%   |
| Intel CPU Version                                             | 1         | 2.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 1         | 2.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 1         | 2.94%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                            | 1         | 2.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 2.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz                             | 1         | 2.94%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz                            | 1         | 2.94%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 2.94%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 1         | 2.94%   |
| Intel Core i7-3537U CPU @ 2.00GHz                             | 1         | 2.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 2.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 2.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 2.94%   |
| Intel Core i5-4210Y CPU @ 1.50GHz                             | 1         | 2.94%   |
| Intel Core i5-3380M CPU @ 2.90GHz                             | 1         | 2.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz                             | 1         | 2.94%   |
| Intel Core i5 CPU M 480 @ 2.67GH                              | 1         | 2.94%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 2.94%   |
| Intel Core Duo CPU L2400 @ 1.66GHz ("GenuineIntel" 686-class) | 1         | 2.94%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 2.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz                             | 1         | 2.94%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 1         | 2.94%   |
| Intel Celeron CPU 1007U @ 1.50GHz                             | 1         | 2.94%   |
| Intel Celeron 2955U @ 1.40GHz                                 | 1         | 2.94%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics                   | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 14        | 41.18%  |
| Intel Core i5    | 10        | 29.41%  |
| Intel Celeron    | 4         | 11.76%  |
| Other            | 1         | 2.94%   |
| Intel Xeon       | 1         | 2.94%   |
| Intel Core i3    | 1         | 2.94%   |
| Intel Core Duo   | 1         | 2.94%   |
| Intel Core 2 Duo | 1         | 2.94%   |
| AMD A6           | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 24        | 70.59%  |
| 4       | 6         | 17.65%  |
| Unknown | 2         | 5.88%   |
| 6       | 1         | 2.94%   |
| 1       | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 32        | 94.12%  |
| 2       | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 76.47%  |
| 1       | 6         | 17.65%  |
| Unknown | 2         | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 8         | 23.53%  |
| Haswell     | 7         | 20.59%  |
| Skylake     | 5         | 14.71%  |
| KabyLake    | 4         | 11.76%  |
| SandyBridge | 2         | 5.88%   |
| Broadwell   | 2         | 5.88%   |
| Westmere    | 1         | 2.94%   |
| Silvermont  | 1         | 2.94%   |
| Puma        | 1         | 2.94%   |
| Penryn      | 1         | 2.94%   |
| P6          | 1         | 2.94%   |
| Bonnell     | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 30        | 71.43%  |
| Nvidia         | 7         | 16.67%  |
| AMD            | 4         | 9.52%   |
| Silicon Motion | 1         | 2.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 16.28%  |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 9.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 9.3%    |
| Intel HD Graphics 620                                                                    | 2         | 4.65%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.65%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 2.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.33%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 2.33%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.33%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.33%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 2.33%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 2.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.33%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.33%   |
| Intel HD Graphics 530                                                                    | 1         | 2.33%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.33%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.33%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 2.33%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.33%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 20        | 58.82%  |
| Intel + Nvidia     | 5         | 14.71%  |
| Intel + AMD        | 3         | 8.82%   |
| 2 x Intel          | 2         | 5.88%   |
| 1 x Nvidia         | 2         | 5.88%   |
| 1 x Silicon Motion | 1         | 2.94%   |
| 1 x AMD            | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 33        | 94.29%  |
| Proprietary | 1         | 2.86%   |
| Unknown     | 1         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 31.58%  |
| LG Display          | 5         | 26.32%  |
| Samsung Electronics | 2         | 10.53%  |
| Chimei Innolux      | 2         | 10.53%  |
| Sharp               | 1         | 5.26%   |
| Panasonic           | 1         | 5.26%   |
| Lenovo              | 1         | 5.26%   |
| BOE                 | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 5.26%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 5.26%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 5.26%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 5.26%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 7         | 36.84%  |
| 1366x768 (WXGA) | 7         | 36.84%  |
| 2560x1440 (QHD) | 2         | 10.53%  |
| 2880x1620       | 1         | 5.26%   |
| 1600x900 (HD+)  | 1         | 5.26%   |
| 1280x720 (HD)   | 1         | 5.26%   |

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
| 17     | 1         | 5.26%   |
| 10     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 57.89%  |
| 201-300     | 7         | 36.84%  |
| 351-400     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 36.84%  |
| 51-60          | 3         | 15.79%  |
| 91-100         | 3         | 15.79%  |
| 61-70          | 2         | 10.53%  |
| 71-80          | 1         | 5.26%   |
| 41-50          | 1         | 5.26%   |
| 121-130        | 1         | 5.26%   |
| 101-110        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 57.89%  |
| 161-240 | 4         | 21.05%  |
| 101-120 | 3         | 15.79%  |
| 51-100  | 1         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 60%     |
| 0     | 14        | 40%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 23        | 47.92%  |
| Realtek Semiconductor             | 11        | 22.92%  |
| Broadcom                          | 5         | 10.42%  |
| Qualcomm Atheros                  | 4         | 8.33%   |
| Ericsson Business Mobile Networks | 2         | 4.17%   |
| Sierra Wireless                   | 1         | 2.08%   |
| Nvidia                            | 1         | 2.08%   |
| Microsoft                         | 1         | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 8         | 11.76%  |
| Intel Wireless 8260                                                | 5         | 7.35%   |
| Intel Wireless 7265                                                | 3         | 4.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 4.41%   |
| Intel Wireless 8265 / 8275                                         | 2         | 2.94%   |
| Intel Wireless 7260                                                | 2         | 2.94%   |
| Intel Ethernet Connection I219-LM                                  | 2         | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 2.94%   |
| Intel 82574L Gigabit Network Connection                            | 2         | 2.94%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 2.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 2         | 2.94%   |
| Sierra Wireless EM7455                                             | 1         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.47%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                   | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 1         | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 1.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 1.47%   |
| Nvidia MCP79 Ethernet                                              | 1         | 1.47%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                 | 1         | 1.47%   |
| Intel Wireless 3165                                                | 1         | 1.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 1         | 1.47%   |
| Intel Ethernet Connection I219-V                                   | 1         | 1.47%   |
| Intel Ethernet Connection I218-V                                   | 1         | 1.47%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                               | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                              | 1         | 1.47%   |
| Intel Ethernet 10G 2P X520 Adapter                                 | 1         | 1.47%   |
| Intel Centrino Advanced-N 6235                                     | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 1         | 1.47%   |
| Intel 82573L Gigabit Ethernet Controller                           | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 60.61%  |
| Broadcom              | 5         | 15.15%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Realtek Semiconductor | 3         | 9.09%   |
| Sierra Wireless       | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 14.71%  |
| Intel Wireless 7265                                            | 3         | 8.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 8.82%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.88%   |
| Intel Wireless 7260                                            | 2         | 5.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 5.88%   |
| Sierra Wireless EM7455                                         | 1         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.94%   |
| Intel Wireless 3165                                            | 1         | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.94%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 50%     |
| Realtek Semiconductor | 10        | 33.33%  |
| Qualcomm Atheros      | 2         | 6.67%   |
| Nvidia                | 1         | 3.33%   |
| Microsoft             | 1         | 3.33%   |
| Broadcom              | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.38%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 6.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 6.25%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.13%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 3.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 3.13%   |
| Nvidia MCP79 Ethernet                                             | 1         | 3.13%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                | 1         | 3.13%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection I218-V                                  | 1         | 3.13%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.13%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.13%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 3.13%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.13%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 50%     |
| Ethernet | 29        | 46.77%  |
| Modem    | 2         | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 24        | 50%     |
| WiFi     | 23        | 47.92%  |
| Modem    | 1         | 2.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 76.47%  |
| 1     | 7         | 20.59%  |
| 4     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 88.24%  |
| Yes  | 4         | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 52.38%  |
| Broadcom                        | 3         | 14.29%  |
| Apple                           | 3         | 14.29%  |
| Realtek Semiconductor           | 2         | 9.52%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 10        | 47.62%  |
| Apple Bluetooth Host Controller                | 2         | 9.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 1         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4.76%   |
| Foxconn / Hon Hai Bluetooth USB Module         | 1         | 4.76%   |
| Broadcom Broadcom Bluetooth 4.0                | 1         | 4.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 4.76%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 4.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI           | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 85.71%  |
| Nvidia | 3         | 8.57%   |
| AMD    | 2         | 5.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 16.28%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 11.63%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 11.63%  |
| Intel 8 Series HD Audio Controller                                                                | 4         | 9.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.65%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.33%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 2.33%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.33%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 51.52%  |
| SK hynix            | 6         | 18.18%  |
| Micron Technology   | 3         | 9.09%   |
| Kingston            | 3         | 9.09%   |
| Crucial             | 2         | 6.06%   |
| Unknown             | 1         | 3.03%   |
| Corsair             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 2.78%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 2.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 2.78%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.78%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                        | 1         | 2.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.78%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 2.78%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 2.78%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                        | 1         | 2.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 1         | 2.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s          | 1         | 2.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s               | 1         | 2.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB Chip DDR4 2133MT/s      | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1         | 2.78%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.78%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s       | 1         | 2.78%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s         | 1         | 2.78%   |
| Micron RAM MT52L512M32D2PF-10 4GB SODIMM LPDDR3 1867MT/s     | 1         | 2.78%   |
| Micron RAM MT52L512M32D2PF-10 4GB Chip LPDDR3 1867MT/s       | 1         | 2.78%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 2.78%   |
| Micron RAM 8KTF51264HZ-1G9E2 4GB SODIMM DDR3 1867MT/s        | 1         | 2.78%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s      | 1         | 2.78%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.78%   |
| Kingston RAM 9965525-116.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.78%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s      | 1         | 2.78%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 2.78%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 19        | 67.86%  |
| DDR4    | 5         | 17.86%  |
| LPDDR3  | 3         | 10.71%  |
| Unknown | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 76.67%  |
| Chip         | 4         | 13.33%  |
| Unknown      | 2         | 6.67%   |
| Row Of Chips | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 40.63%  |
| 8192  | 12        | 37.5%   |
| 2048  | 4         | 12.5%   |
| 16384 | 3         | 9.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 14        | 46.67%  |
| 1867  | 4         | 13.33%  |
| 1333  | 4         | 13.33%  |
| 2667  | 3         | 10%     |
| 2400  | 2         | 6.67%   |
| 2133  | 1         | 3.33%   |
| 1067  | 1         | 3.33%   |
| 667   | 1         | 3.33%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 40.91%  |
| Acer                          | 4         | 18.18%  |
| Sunplus Innovation Technology | 2         | 9.09%   |
| IMC Networks                  | 2         | 9.09%   |
| Z-Star Microelectronics       | 1         | 4.55%   |
| Suyin                         | 1         | 4.55%   |
| Microdia                      | 1         | 4.55%   |
| Luxvisions Innotech Limited   | 1         | 4.55%   |
| Apple                         | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 21.74%  |
| Acer Integrated Camera                              | 2         | 8.7%    |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 4.35%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 4.35%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 4.35%   |
| Sunplus HD WebCam                                   | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.35%   |
| IMC Networks Integrated Webcam                      | 1         | 4.35%   |
| IMC Networks EasyCamera                             | 1         | 4.35%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 4.35%   |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 4.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 4.35%   |
| Chicony Lenovo Integrated Camera                    | 1         | 4.35%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 4.35%   |
| Acer Lenovo Integrated Webcam                       | 1         | 4.35%   |
| Acer Lenovo EasyCamera                              | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 87.5%   |
| Upek             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 37.5%   |
| Validity Sensors Synaptics WBDI                        | 3         | 37.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |

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
| 1     | 15        | 42.86%  |
| 3     | 9         | 25.71%  |
| 2     | 7         | 20%     |
| 0     | 2         | 5.71%   |
| 6     | 1         | 2.86%   |
| 5     | 1         | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 27        | 43.55%  |
| Card reader              | 9         | 14.52%  |
| Bluetooth                | 8         | 12.9%   |
| Fingerprint reader       | 6         | 9.68%   |
| Net/wireless             | 5         | 8.06%   |
| Graphics card            | 2         | 3.23%   |
| Firewire controller      | 2         | 3.23%   |
| Sound                    | 1         | 1.61%   |
| Network                  | 1         | 1.61%   |
| Net/ethernet             | 1         | 1.61%   |

