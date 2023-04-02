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

Total: 53

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown   | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Acer      | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek   | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Framework | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Lenovo    | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Dell      | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| HP        | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Lenovo    | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP        | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| HP        | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| HP        | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP        | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Dell      | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Samsung   | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung   | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Dell      | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Toshiba   | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple     | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| HP        | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo    | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo    | ThinkPad X1 Carbon 3443C... | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo    | ThinkPad X1 Carbon 3443C... | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| Lenovo    | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Intel     | SandyBridge Platform        | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| Toshiba   | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Apple     | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ASUSTek   | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Dell      | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| HP        | ProBook 430 G3              | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown   | Unknown                     | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo    | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo    | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo    | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Toshiba   | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo    | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo    | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| ASUSTek   | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek   | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| HP        | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo    | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo    | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo    | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Acer      | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer      | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Apple     | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo    | ThinkPad T460p 20FXCTO1W... | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo    | ThinkPad T470 W10DG 20JM... | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Lenovo    | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| FreeBSD 13.0        | 4         | 9.52%   |
| OpenBSD 6.8         | 3         | 7.14%   |
| helloSystem 0.4.0   | 3         | 7.14%   |
| OPNsense 22.1.6     | 2         | 4.76%   |
| OPNsense 21.1.3     | 2         | 4.76%   |
| OpenBSD 7.2         | 2         | 4.76%   |
| helloSystem 0.6.0   | 2         | 4.76%   |
| FreeBSD 12.2        | 2         | 4.76%   |
| FreeBSD 12.1-p10    | 2         | 4.76%   |
| FreeBSD 12.1        | 2         | 4.76%   |
| OPNsense 23.1.4     | 1         | 2.38%   |
| OPNsense 22.1.1     | 1         | 2.38%   |
| OPNsense 21.7.1     | 1         | 2.38%   |
| OPNsense 21.7       | 1         | 2.38%   |
| OpenBSD 6.7         | 1         | 2.38%   |
| NomadBSD 1.4        | 1         | 2.38%   |
| helloSystem 0.8.1   | 1         | 2.38%   |
| helloSystem 0.5.0   | 1         | 2.38%   |
| FuguIta 7.1         | 1         | 2.38%   |
| FreeBSD 13.1        | 1         | 2.38%   |
| FreeBSD 13.0-RC5    | 1         | 2.38%   |
| FreeBSD 13.0-p7     | 1         | 2.38%   |
| FreeBSD 13.0-p6     | 1         | 2.38%   |
| FreeBSD 13.0-BETA1  | 1         | 2.38%   |
| FreeBSD 12.2-p3     | 1         | 2.38%   |
| FreeBSD 12.2-p2     | 1         | 2.38%   |
| FreeBSD 12.1-p6     | 1         | 2.38%   |
| FreeBSD 11.4-STABLE | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 15        | 39.47%  |
| OPNsense    | 8         | 21.05%  |
| helloSystem | 7         | 18.42%  |
| OpenBSD     | 6         | 15.79%  |
| NomadBSD    | 1         | 2.63%   |
| FuguIta     | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 37        | 97.37%  |
| i386  | 1         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 10        | 25.64%  |
| Console      | 10        | 25.64%  |
| fvwm         | 4         | 10.26%  |
| XFCE         | 3         | 7.69%   |
| KDE5         | 3         | 7.69%   |
| GNOME        | 3         | 7.69%   |
| i3           | 2         | 5.13%   |
| TWM          | 1         | 2.56%   |
| Openbox      | 1         | 2.56%   |
| Fluxbox      | 1         | 2.56%   |
| AwesomeWM    | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 27        | 71.05%  |
| Console | 10        | 26.32%  |
| Wayland | 1         | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 22        | 56.41%  |
| SLiM    | 8         | 20.51%  |
| SDDM    | 5         | 12.82%  |
| XDM     | 1         | 2.56%   |
| PCDM    | 1         | 2.56%   |
| Ly      | 1         | 2.56%   |
| GDM     | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 19        | 46.34%  |
| en_US           | 10        | 24.39%  |
| C               | 6         | 14.63%  |
| en_AU           | 4         | 9.76%   |
| en_AU.US-ASCII  | 1         | 2.44%   |
| en_AU.ISO8859-1 | 1         | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 29        | 76.32%  |
| BIOS | 9         | 23.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 16        | 42.11%  |
| Ufs    | 14        | 36.84%  |
| Ffs    | 7         | 18.42%  |
| Cd9660 | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 31        | 81.58%  |
| MBR  | 7         | 18.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 15        | 39.47%  |
| Hewlett-Packard     | 5         | 13.16%  |
| Toshiba             | 3         | 7.89%   |
| ASUSTek Computer    | 3         | 7.89%   |
| Apple               | 3         | 7.89%   |
| Dell                | 2         | 5.26%   |
| Acer                | 2         | 5.26%   |
| Unknown             | 2         | 5.26%   |
| Samsung Electronics | 1         | 2.63%   |
| Intel               | 1         | 2.63%   |
| Framework           | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 2         | 5.26%   |
| Toshiba Satellite L50-A                                                                  | 1         | 2.63%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 2.63%   |
| Toshiba KIRA                                                                             | 1         | 2.63%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 2.63%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 2.63%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 2.63%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 2.63%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 2.63%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 2.63%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 2.63%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 2.63%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 2.63%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 2.63%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 2.63%   |
| Lenovo G40-70 20369                                                                      | 1         | 2.63%   |
| Intel SandyBridge Platform                                                               | 1         | 2.63%   |
| HP ZBook 14                                                                              | 1         | 2.63%   |
| HP Setzer                                                                                | 1         | 2.63%   |
| HP ProBook 430 G3                                                                        | 1         | 2.63%   |
| HP Notebook                                                                              | 1         | 2.63%   |
| HP Laptop 15s-du1xxx                                                                     | 1         | 2.63%   |
| Framework Laptop (12th Gen Intel Core)                                                   | 1         | 2.63%   |
| Dell Latitude E7450                                                                      | 1         | 2.63%   |
| Dell G5 5590                                                                             | 1         | 2.63%   |
| ASUS TP500LNG                                                                            | 1         | 2.63%   |
| ASUS K72F                                                                                | 1         | 2.63%   |
| ASUS G74Sx                                                                               | 1         | 2.63%   |
| Apple MacBookPro5,5                                                                      | 1         | 2.63%   |
| Apple MacBookPro11,3                                                                     | 1         | 2.63%   |
| Apple MacBookAir5,1                                                                      | 1         | 2.63%   |
| Acer Peppy                                                                               | 1         | 2.63%   |
| Acer Nitro AN515-55                                                                      | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 36.84%  |
| Unknown            | 2         | 5.26%   |
| Toshiba Satellite  | 1         | 2.63%   |
| Toshiba PORTEGE    | 1         | 2.63%   |
| Toshiba KIRA       | 1         | 2.63%   |
| Samsung 350V5C     | 1         | 2.63%   |
| Lenovo G40-70      | 1         | 2.63%   |
| Intel SandyBridge  | 1         | 2.63%   |
| HP ZBook           | 1         | 2.63%   |
| HP Setzer          | 1         | 2.63%   |
| HP ProBook         | 1         | 2.63%   |
| HP Notebook        | 1         | 2.63%   |
| HP Laptop          | 1         | 2.63%   |
| Framework Laptop   | 1         | 2.63%   |
| Dell Latitude      | 1         | 2.63%   |
| Dell G5            | 1         | 2.63%   |
| ASUS TP500LNG      | 1         | 2.63%   |
| ASUS K72F          | 1         | 2.63%   |
| ASUS G74Sx         | 1         | 2.63%   |
| Apple MacBookPro5  | 1         | 2.63%   |
| Apple MacBookPro11 | 1         | 2.63%   |
| Apple MacBookAir5  | 1         | 2.63%   |
| Acer Peppy         | 1         | 2.63%   |
| Acer Nitro         | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 13.16%  |
| 2017 | 4         | 10.53%  |
| 2015 | 4         | 10.53%  |
| 2014 | 4         | 10.53%  |
| 2012 | 4         | 10.53%  |
| 2020 | 3         | 7.89%   |
| 2018 | 2         | 5.26%   |
| 2016 | 2         | 5.26%   |
| 2013 | 2         | 5.26%   |
| 2011 | 2         | 5.26%   |
| 2010 | 2         | 5.26%   |
| 2022 | 1         | 2.63%   |
| 2021 | 1         | 2.63%   |
| 2009 | 1         | 2.63%   |
| 2007 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 94.74%  |
| Yes  | 2         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 44.74%  |
| 16.01-24.0  | 10        | 26.32%  |
| 4.01-8.0    | 5         | 13.16%  |
| 1.01-2.0    | 2         | 5.26%   |
| 32.01-64.0  | 1         | 2.63%   |
| 3.01-4.0    | 1         | 2.63%   |
| 2.01-3.0    | 1         | 2.63%   |
| 64.01-256.0 | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 48.72%  |
| 0.51-1.0 | 13        | 33.33%  |
| 1.01-2.0 | 3         | 7.69%   |
| 4.01-8.0 | 2         | 5.13%   |
| 2.01-3.0 | 1         | 2.56%   |
| 0        | 1         | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 86.84%  |
| 2      | 3         | 7.89%   |
| 3      | 1         | 2.63%   |
| 0      | 1         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 81.58%  |
| Yes       | 7         | 18.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 84.21%  |
| No        | 6         | 15.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 89.47%  |
| No        | 4         | 10.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 63.16%  |
| No        | 14        | 36.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 38        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 9         | 23.68%  |
| Brisbane     | 6         | 15.79%  |
| Perth        | 5         | 13.16%  |
| Melbourne    | 5         | 13.16%  |
| Canberra     | 3         | 7.89%   |
| Adelaide     | 2         | 5.26%   |
| Warrnambool  | 1         | 2.63%   |
| South Yarra  | 1         | 2.63%   |
| Ryde         | 1         | 2.63%   |
| Kellyville   | 1         | 2.63%   |
| East Malvern | 1         | 2.63%   |
| Darlinghurst | 1         | 2.63%   |
| Burwood      | 1         | 2.63%   |
| Adelaide CBD | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 21.05%  |
| Toshiba             | 6         | 7      | 15.79%  |
| Intel               | 4         | 4      | 10.53%  |
| Crucial             | 3         | 4      | 7.89%   |
| Seagate             | 2         | 3      | 5.26%   |
| SanDisk             | 2         | 3      | 5.26%   |
| NVMe                | 2         | 3      | 5.26%   |
| Kingston            | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 3      | 2.63%   |
| Silicon Motion      | 1         | 1      | 2.63%   |
| Jetflash            | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| FORESEE             | 1         | 1      | 2.63%   |
| Dogfish             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB      | 2         | 5.13%   |
| Samsung SSD 840 EVO 250GB        | 2         | 5.13%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1         | 2.56%   |
| Toshiba THNSNF256GMCS 256GB      | 1         | 2.56%   |
| Toshiba THNSF5256GCJ7 256GB      | 1         | 2.56%   |
| Toshiba MQ01ABF050 500GB         | 1         | 2.56%   |
| Toshiba MQ01ABD100 1TB           | 1         | 2.56%   |
| SK hynix BC501 NVMe 512GB        | 1         | 2.56%   |
| Silicon Motion Aura Pro X2 960GB | 1         | 2.56%   |
| Seagate ST9500325AS 500GB        | 1         | 2.56%   |
| Seagate ST9250315ASG 250GB       | 1         | 2.56%   |
| SanDisk SD8TN8U256G1001 256GB    | 1         | 2.56%   |
| SanDisk SD5SG2128G1052E 128GB    | 1         | 2.56%   |
| Samsung SSD PM871 mSATA 256GB    | 1         | 2.56%   |
| Samsung SSD 860 EVO 500GB        | 1         | 2.56%   |
| Samsung MZVLB512HBJQ-000H1 512GB | 1         | 2.56%   |
| Samsung MZNLN256HCHP-000L7 256GB | 1         | 2.56%   |
| Samsung MZMTE128HMGR-00000 128GB | 1         | 2.56%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 2.56%   |
| NVMe WD_BLACK SN850X 1TB         | 1         | 2.56%   |
| NVMe WD Blue SN570 2T            | 1         | 2.56%   |
| NVMe CT2000P3SSD8 2TB            | 1         | 2.56%   |
| Kingston SV300S37A120G 120GB     | 1         | 2.56%   |
| Kingston SNS4151S316G 16GB       | 1         | 2.56%   |
| Jetflash Transcend 8G            | 1         | 2.56%   |
| Intel SSDSC2KW128G8 128GB        | 1         | 2.56%   |
| Intel SSDSC2BF180A4L 180GB       | 1         | 2.56%   |
| Intel SSDSA2BW160G3L 160GB       | 1         | 2.56%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 2.56%   |
| HGST HTS725050A7E630 500GB       | 1         | 2.56%   |
| Fujitsu MHY2160BH 160GB          | 1         | 2.56%   |
| FORESEE 64GB SSD                 | 1         | 2.56%   |
| Dogfish SSD 64GB                 | 1         | 2.56%   |
| Crucial CT480BX200SSD1 480GB     | 1         | 2.56%   |
| Crucial CT250MX500SSD1 250GB     | 1         | 2.56%   |
| Crucial CT1000BX500SSD1 1TB      | 1         | 2.56%   |
| Apple SSD SM256E 256GB           | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 2         | 2      | 20%     |
| Seagate  | 2         | 3      | 20%     |
| NVMe     | 2         | 2      | 20%     |
| WDC      | 1         | 1      | 10%     |
| Jetflash | 1         | 1      | 10%     |
| HGST     | 1         | 1      | 10%     |
| Fujitsu  | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 31.82%  |
| Intel               | 3         | 3      | 13.64%  |
| Crucial             | 3         | 4      | 13.64%  |
| SanDisk             | 2         | 3      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Toshiba             | 1         | 1      | 4.55%   |
| NVMe                | 1         | 1      | 4.55%   |
| FORESEE             | 1         | 1      | 4.55%   |
| Dogfish             | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 21        | 24     | 55.26%  |
| HDD  | 10        | 11     | 26.32%  |
| NVMe | 7         | 10     | 18.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 35     | 80.56%  |
| NVMe | 7         | 10     | 19.44%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 28     | 83.33%  |
| 0.51-1.0   | 4         | 5      | 13.33%  |
| 1.01-2.0   | 1         | 2      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 36.84%  |
| 251-500    | 8         | 21.05%  |
| 1-20       | 8         | 21.05%  |
| 51-100     | 5         | 13.16%  |
| 501-1000   | 2         | 5.26%   |
| 21-50      | 1         | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 33        | 82.5%   |
| 21-50   | 4         | 10%     |
| 51-100  | 2         | 5%      |
| 101-250 | 1         | 2.5%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 31        | 38     | 83.78%  |
| Malfunc  | 4         | 4      | 10.81%  |
| Detected | 2         | 3      | 5.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 30        | 75%     |
| Toshiba                   | 3         | 7.5%    |
| Sandisk                   | 2         | 5%      |
| Silicon Motion            | 1         | 2.5%    |
| Samsung Electronics       | 1         | 2.5%    |
| Nvidia                    | 1         | 2.5%    |
| Micron/Crucial Technology | 1         | 2.5%    |
| AMD                       | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 17.07%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 12.2%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 9.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 7.32%   |
| Toshiba XG4 NVMe SSD Controller                                                | 2         | 4.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 4.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.88%   |
| Toshiba NVMe Controller                                                        | 1         | 2.44%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2.44%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1         | 2.44%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.44%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 2.44%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 2.44%   |
| Intel SSD 660P Series                                                          | 1         | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.44%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 72.5%   |
| NVMe | 8         | 20%     |
| RAID | 2         | 5%      |
| IDE  | 1         | 2.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 97.37%  |
| AMD    | 1         | 2.63%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                             | 3         | 7.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz                             | 2         | 5.26%   |
| Intel Core i7-3667U CPU @ 2.00GHz                             | 2         | 5.26%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 5.26%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH                            | 1         | 2.63%   |
| Intel CPU Version                                             | 1         | 2.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 1         | 2.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 1         | 2.63%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                            | 1         | 2.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 2.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz                             | 1         | 2.63%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz                            | 1         | 2.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 2.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 1         | 2.63%   |
| Intel Core i7-3537U CPU @ 2.00GHz                             | 1         | 2.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                            | 1         | 2.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 2.63%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 2.63%   |
| Intel Core i5-4210Y CPU @ 1.50GHz                             | 1         | 2.63%   |
| Intel Core i5-3380M CPU @ 2.90GHz                             | 1         | 2.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz                             | 1         | 2.63%   |
| Intel Core i5 CPU M 480 @ 2.67GH                              | 1         | 2.63%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 2.63%   |
| Intel Core Duo CPU L2400 @ 1.66GHz ("GenuineIntel" 686-class) | 1         | 2.63%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 2.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz                             | 1         | 2.63%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 1         | 2.63%   |
| Intel Celeron CPU 1007U @ 1.50GHz                             | 1         | 2.63%   |
| Intel Celeron 2955U @ 1.40GHz                                 | 1         | 2.63%   |
| Intel 12th Gen Core i5-1240P                                  | 1         | 2.63%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics                   | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 16        | 42.11%  |
| Intel Core i5    | 11        | 28.95%  |
| Intel Celeron    | 4         | 10.53%  |
| Other            | 2         | 5.26%   |
| Intel Xeon       | 1         | 2.63%   |
| Intel Core i3    | 1         | 2.63%   |
| Intel Core Duo   | 1         | 2.63%   |
| Intel Core 2 Duo | 1         | 2.63%   |
| AMD A6           | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 25        | 65.79%  |
| 4       | 7         | 18.42%  |
| 6       | 2         | 5.26%   |
| Unknown | 2         | 5.26%   |
| 16      | 1         | 2.63%   |
| 1       | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 36        | 94.74%  |
| 2       | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 76.32%  |
| 1       | 7         | 18.42%  |
| Unknown | 2         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 8         | 21.05%  |
| Haswell     | 7         | 18.42%  |
| Skylake     | 5         | 13.16%  |
| SandyBridge | 4         | 10.53%  |
| KabyLake    | 4         | 10.53%  |
| Broadwell   | 2         | 5.26%   |
| Westmere    | 1         | 2.63%   |
| Silvermont  | 1         | 2.63%   |
| Puma        | 1         | 2.63%   |
| Penryn      | 1         | 2.63%   |
| P6          | 1         | 2.63%   |
| CometLake   | 1         | 2.63%   |
| Bonnell     | 1         | 2.63%   |
| Unknown     | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 33        | 70.21%  |
| Nvidia         | 9         | 19.15%  |
| AMD            | 4         | 8.51%   |
| Silicon Motion | 1         | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 14.58%  |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 8.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 8.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 6.25%   |
| Intel HD Graphics 620                                                                    | 2         | 4.17%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.17%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 2.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.08%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 2.08%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.08%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.08%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.08%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 2.08%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 2.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.08%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 2.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.08%   |
| Intel HD Graphics 530                                                                    | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.08%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 2.08%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 2.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.08%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 22        | 57.89%  |
| Intel + Nvidia     | 6         | 15.79%  |
| 1 x Nvidia         | 3         | 7.89%   |
| Intel + AMD        | 3         | 7.89%   |
| 2 x Intel          | 2         | 5.26%   |
| 1 x Silicon Motion | 1         | 2.63%   |
| 1 x AMD            | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 36        | 92.31%  |
| Unknown     | 2         | 5.13%   |
| Proprietary | 1         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 100%    |

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
| 1     | 23        | 58.97%  |
| 0     | 16        | 41.03%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 26        | 48.15%  |
| Realtek Semiconductor             | 13        | 24.07%  |
| Qualcomm Atheros                  | 5         | 9.26%   |
| Broadcom                          | 5         | 9.26%   |
| Ericsson Business Mobile Networks | 2         | 3.7%    |
| Sierra Wireless                   | 1         | 1.85%   |
| Nvidia                            | 1         | 1.85%   |
| Microsoft                         | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 9         | 12.16%  |
| Intel Wireless 8260                                                | 5         | 6.76%   |
| Intel Wireless 7265                                                | 3         | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 4.05%   |
| Intel 82574L Gigabit Network Connection                            | 3         | 4.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 2         | 2.7%    |
| Intel Wireless 8265 / 8275                                         | 2         | 2.7%    |
| Intel Wireless 7260                                                | 2         | 2.7%    |
| Intel Ethernet Connection I219-LM                                  | 2         | 2.7%    |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 2.7%    |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                    | 2         | 2.7%    |
| Sierra Wireless EM7455                                             | 1         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                   | 1         | 1.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                   | 1         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 1.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 1.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 1.35%   |
| Nvidia MCP79 Ethernet                                              | 1         | 1.35%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                 | 1         | 1.35%   |
| Intel Wireless 3165                                                | 1         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 1         | 1.35%   |
| Intel Ethernet Connection I219-V                                   | 1         | 1.35%   |
| Intel Ethernet Connection I218-V                                   | 1         | 1.35%   |
| Intel Ethernet Connection I218-LM                                  | 1         | 1.35%   |
| Intel Ethernet Connection (4) I219-V                               | 1         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                              | 1         | 1.35%   |
| Intel Ethernet 10G 2P X520 Adapter                                 | 1         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 61.11%  |
| Qualcomm Atheros      | 5         | 13.89%  |
| Broadcom              | 5         | 13.89%  |
| Realtek Semiconductor | 3         | 8.33%   |
| Sierra Wireless       | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 5         | 13.51%  |
| Intel Wireless 7265                                            | 3         | 8.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 8.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 5.41%   |
| Intel Wireless 8265 / 8275                                     | 2         | 5.41%   |
| Intel Wireless 7260                                            | 2         | 5.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 5.41%   |
| Sierra Wireless EM7455                                         | 1         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.7%    |
| Intel Wireless 3165                                            | 1         | 2.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.7%    |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 48.48%  |
| Realtek Semiconductor | 12        | 36.36%  |
| Qualcomm Atheros      | 2         | 6.06%   |
| Nvidia                | 1         | 3.03%   |
| Microsoft             | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 25.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 8.57%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 8.57%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.86%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 2.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.86%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.86%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                | 1         | 2.86%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.86%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.86%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.86%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 2.86%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.86%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 50%     |
| Ethernet | 32        | 47.06%  |
| Modem    | 2         | 2.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 50%     |
| Ethernet | 25        | 48.08%  |
| Modem    | 1         | 1.92%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 73.68%  |
| 1     | 8         | 21.05%  |
| 6     | 1         | 2.63%   |
| 4     | 1         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 89.47%  |
| Yes  | 4         | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 54.17%  |
| Broadcom                        | 3         | 12.5%   |
| Apple                           | 3         | 12.5%   |
| Realtek Semiconductor           | 2         | 8.33%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| Foxconn / Hon Hai               | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 10        | 41.67%  |
| Apple Bluetooth Host Controller                        | 2         | 8.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1         | 4.17%   |
| Intel AX210 Bluetooth                                  | 1         | 4.17%   |
| Intel AX201 Bluetooth                                  | 1         | 4.17%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 4.17%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 4.17%   |
| Broadcom Bluetooth 4.0                                 | 1         | 4.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 4.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 82.93%  |
| Nvidia | 5         | 12.2%   |
| AMD    | 2         | 4.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 10.2%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 10.2%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 8.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 8.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.08%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 2.04%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.04%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 47.22%  |
| SK hynix            | 6         | 16.67%  |
| Micron Technology   | 4         | 11.11%  |
| Kingston            | 3         | 8.33%   |
| Crucial             | 3         | 8.33%   |
| Unknown             | 1         | 2.78%   |
| Corsair             | 1         | 2.78%   |
| ASint Technology    | 1         | 2.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 2.56%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 2.56%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 2.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 2.56%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                        | 1         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 2.56%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 2.56%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 2.56%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                        | 1         | 2.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s             | 1         | 2.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s          | 1         | 2.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s               | 1         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s        | 1         | 2.56%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB Chip DDR4 2133MT/s      | 1         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1         | 2.56%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.56%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s       | 1         | 2.56%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s         | 1         | 2.56%   |
| Micron RAM MT52L512M32D2PF-10 4GB SODIMM LPDDR3 1867MT/s     | 1         | 2.56%   |
| Micron RAM MT52L512M32D2PF-10 4GB Chip LPDDR3 1867MT/s       | 1         | 2.56%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 2.56%   |
| Micron RAM 8KTF51264HZ-1G9E2 4GB SODIMM DDR3 1867MT/s        | 1         | 2.56%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s       | 1         | 2.56%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s      | 1         | 2.56%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Kingston RAM 9965525-116.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| Crucial RAM CT102464BF1339.M16 8GB SODIMM DDR3 1333MT/s      | 1         | 2.56%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 1         | 2.56%   |
| ASint RAM SSA302G08-GDJEC 4GB SODIMM DDR3 1333MT/s           | 1         | 2.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 70%     |
| DDR4    | 5         | 16.67%  |
| LPDDR3  | 3         | 10%     |
| Unknown | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 78.13%  |
| Chip         | 4         | 12.5%   |
| Unknown      | 2         | 6.25%   |
| Row Of Chips | 1         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 14        | 41.18%  |
| 8192  | 13        | 38.24%  |
| 2048  | 4         | 11.76%  |
| 16384 | 3         | 8.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 15        | 46.88%  |
| 1333  | 5         | 15.63%  |
| 1867  | 4         | 12.5%   |
| 2667  | 3         | 9.38%   |
| 2400  | 2         | 6.25%   |
| 2133  | 1         | 3.13%   |
| 1067  | 1         | 3.13%   |
| 667   | 1         | 3.13%   |

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
| Chicony Electronics           | 9         | 39.13%  |
| Bison Electronics             | 4         | 17.39%  |
| IMC Networks                  | 3         | 13.04%  |
| Sunplus Innovation Technology | 2         | 8.7%    |
| Z-Star Microelectronics       | 1         | 4.35%   |
| Suyin                         | 1         | 4.35%   |
| Microdia                      | 1         | 4.35%   |
| Luxvisions Innotech Limited   | 1         | 4.35%   |
| Apple                         | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 20.83%  |
| IMC Networks Integrated Webcam                      | 2         | 8.33%   |
| Bison Integrated Camera                             | 2         | 8.33%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 4.17%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 4.17%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 4.17%   |
| Sunplus HD WebCam                                   | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.17%   |
| IMC Networks EasyCamera                             | 1         | 4.17%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera                    | 1         | 4.17%   |
| Bison Lenovo Integrated Webcam                      | 1         | 4.17%   |
| Bison Lenovo EasyCamera                             | 1         | 4.17%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 4.17%   |

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
| 1     | 17        | 43.59%  |
| 3     | 10        | 25.64%  |
| 2     | 8         | 20.51%  |
| 0     | 2         | 5.13%   |
| 6     | 1         | 2.56%   |
| 5     | 1         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 44.93%  |
| Card reader              | 10        | 14.49%  |
| Bluetooth                | 9         | 13.04%  |
| Fingerprint reader       | 6         | 8.7%    |
| Net/wireless             | 5         | 7.25%   |
| Graphics card            | 3         | 4.35%   |
| Firewire controller      | 2         | 2.9%    |
| Sound                    | 1         | 1.45%   |
| Network                  | 1         | 1.45%   |
| Net/ethernet             | 1         | 1.45%   |

