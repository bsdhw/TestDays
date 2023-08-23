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

Total: 60

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Dell          | XPS 13 9360                 | [648c09752f](https://bsd-hardware.info/?probe=648c09752f) | Jun 27, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Unknown       | Unknown                     | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| Acer          | Nitro AN515-55              | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Lenovo        | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| HP            | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| HP            | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| HP            | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Toshiba       | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple         | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Intel         | SandyBridge Platform        | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Apple         | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| ASUSTek       | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Dell          | G5 5590                     | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| HP            | ProBook 430 G3              | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Toshiba       | KIRA                        | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| ASUSTek       | K72F                        | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| HP            | Setzer                      | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Acer          | Peppy                       | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| helloSystem 0.8.1   | 4         | 8.16%   |
| FreeBSD 13.0        | 4         | 8.16%   |
| OpenBSD 6.8         | 3         | 6.12%   |
| helloSystem 0.4.0   | 3         | 6.12%   |
| OPNsense 22.1.6     | 2         | 4.08%   |
| OPNsense 21.1.3     | 2         | 4.08%   |
| OpenBSD 7.2         | 2         | 4.08%   |
| helloSystem 0.6.0   | 2         | 4.08%   |
| FreeBSD 13.2        | 2         | 4.08%   |
| FreeBSD 12.2        | 2         | 4.08%   |
| FreeBSD 12.1-p10    | 2         | 4.08%   |
| FreeBSD 12.1        | 2         | 4.08%   |
| OPNsense 23.1.4     | 1         | 2.04%   |
| OPNsense 22.1.1     | 1         | 2.04%   |
| OPNsense 21.7.1     | 1         | 2.04%   |
| OPNsense 21.7       | 1         | 2.04%   |
| OpenBSD 6.7         | 1         | 2.04%   |
| NomadBSD 81e34fc3   | 1         | 2.04%   |
| NomadBSD 1.4        | 1         | 2.04%   |
| helloSystem 0.5.0   | 1         | 2.04%   |
| FuguIta 7.1         | 1         | 2.04%   |
| FreeBSD 13.2-STABLE | 1         | 2.04%   |
| FreeBSD 13.1        | 1         | 2.04%   |
| FreeBSD 13.0-RC5    | 1         | 2.04%   |
| FreeBSD 13.0-p7     | 1         | 2.04%   |
| FreeBSD 13.0-p6     | 1         | 2.04%   |
| FreeBSD 13.0-BETA1  | 1         | 2.04%   |
| FreeBSD 12.2-p3     | 1         | 2.04%   |
| FreeBSD 12.2-p2     | 1         | 2.04%   |
| FreeBSD 12.1-p6     | 1         | 2.04%   |
| FreeBSD 11.4-STABLE | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 18        | 40%     |
| helloSystem | 10        | 22.22%  |
| OPNsense    | 8         | 17.78%  |
| OpenBSD     | 6         | 13.33%  |
| NomadBSD    | 2         | 4.44%   |
| FuguIta     | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 44        | 97.78%  |
| i386  | 1         | 2.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 13        | 28.26%  |
| Console      | 12        | 26.09%  |
| KDE5         | 4         | 8.7%    |
| fvwm         | 4         | 8.7%    |
| XFCE         | 3         | 6.52%   |
| GNOME        | 3         | 6.52%   |
| Openbox      | 2         | 4.35%   |
| i3           | 2         | 4.35%   |
| TWM          | 1         | 2.17%   |
| Fluxbox      | 1         | 2.17%   |
| AwesomeWM    | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 32        | 71.11%  |
| Console | 10        | 22.22%  |
| Wayland | 3         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 24        | 52.17%  |
| SLiM    | 11        | 23.91%  |
| SDDM    | 7         | 15.22%  |
| XDM     | 1         | 2.17%   |
| PCDM    | 1         | 2.17%   |
| Ly      | 1         | 2.17%   |
| GDM     | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 20        | 41.67%  |
| en_US           | 13        | 27.08%  |
| C               | 8         | 16.67%  |
| en_AU           | 5         | 10.42%  |
| en_AU.US-ASCII  | 1         | 2.08%   |
| en_AU.ISO8859-1 | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 36        | 80%     |
| BIOS | 9         | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 20        | 44.44%  |
| Ufs    | 14        | 31.11%  |
| Ffs    | 7         | 15.56%  |
| Cd9660 | 4         | 8.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 38        | 84.44%  |
| MBR  | 7         | 15.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 18        | 40%     |
| Hewlett-Packard      | 6         | 13.33%  |
| Toshiba              | 3         | 6.67%   |
| Dell                 | 3         | 6.67%   |
| ASUSTek Computer     | 3         | 6.67%   |
| Apple                | 3         | 6.67%   |
| Acer                 | 2         | 4.44%   |
| Unknown              | 2         | 4.44%   |
| Timi                 | 1         | 2.22%   |
| Samsung Electronics  | 1         | 2.22%   |
| Intel Client Systems | 1         | 2.22%   |
| Intel                | 1         | 2.22%   |
| Framework            | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 2         | 4.44%   |
| Toshiba Satellite L50-A                                                                  | 1         | 2.22%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 2.22%   |
| Toshiba KIRA                                                                             | 1         | 2.22%   |
| Timi TM1701                                                                              | 1         | 2.22%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 2.22%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 2.22%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 2.22%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 2.22%   |
| Lenovo ThinkPad X1C 5th W10DG 20K3A03CAU                                                 | 1         | 2.22%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 2.22%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 2.22%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 2.22%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 2.22%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 2.22%   |
| Lenovo ThinkPad T440s 20ARS1BK08                                                         | 1         | 2.22%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 2.22%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 2.22%   |
| Lenovo IdeaPad 5 15ALC05 82LN                                                            | 1         | 2.22%   |
| Lenovo G40-70 20369                                                                      | 1         | 2.22%   |
| Intel SandyBridge Platform                                                               | 1         | 2.22%   |
| Intel Client Systems LAPBC510                                                            | 1         | 2.22%   |
| HP ZBook 14                                                                              | 1         | 2.22%   |
| HP Setzer                                                                                | 1         | 2.22%   |
| HP ProBook 430 G3                                                                        | 1         | 2.22%   |
| HP Notebook                                                                              | 1         | 2.22%   |
| HP Laptop 15s-du1xxx                                                                     | 1         | 2.22%   |
| HP Compaq 6830s                                                                          | 1         | 2.22%   |
| Framework Laptop (12th Gen Intel Core)                                                   | 1         | 2.22%   |
| Dell XPS 13 9360                                                                         | 1         | 2.22%   |
| Dell Latitude E7450                                                                      | 1         | 2.22%   |
| Dell G5 5590                                                                             | 1         | 2.22%   |
| ASUS TP500LNG                                                                            | 1         | 2.22%   |
| ASUS K72F                                                                                | 1         | 2.22%   |
| ASUS G74Sx                                                                               | 1         | 2.22%   |
| Apple MacBookPro5,5                                                                      | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 16        | 35.56%  |
| Unknown                       | 2         | 4.44%   |
| Toshiba Satellite             | 1         | 2.22%   |
| Toshiba PORTEGE               | 1         | 2.22%   |
| Toshiba KIRA                  | 1         | 2.22%   |
| Timi TM1701                   | 1         | 2.22%   |
| Samsung 350V5C                | 1         | 2.22%   |
| Lenovo IdeaPad                | 1         | 2.22%   |
| Lenovo G40-70                 | 1         | 2.22%   |
| Intel SandyBridge             | 1         | 2.22%   |
| Intel Client Systems LAPBC510 | 1         | 2.22%   |
| HP ZBook                      | 1         | 2.22%   |
| HP Setzer                     | 1         | 2.22%   |
| HP ProBook                    | 1         | 2.22%   |
| HP Notebook                   | 1         | 2.22%   |
| HP Laptop                     | 1         | 2.22%   |
| HP Compaq                     | 1         | 2.22%   |
| Framework Laptop              | 1         | 2.22%   |
| Dell XPS                      | 1         | 2.22%   |
| Dell Latitude                 | 1         | 2.22%   |
| Dell G5                       | 1         | 2.22%   |
| ASUS TP500LNG                 | 1         | 2.22%   |
| ASUS K72F                     | 1         | 2.22%   |
| ASUS G74Sx                    | 1         | 2.22%   |
| Apple MacBookPro5             | 1         | 2.22%   |
| Apple MacBookPro11            | 1         | 2.22%   |
| Apple MacBookAir5             | 1         | 2.22%   |
| Acer Peppy                    | 1         | 2.22%   |
| Acer Nitro                    | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 13.33%  |
| 2017 | 5         | 11.11%  |
| 2015 | 5         | 11.11%  |
| 2014 | 4         | 8.89%   |
| 2012 | 4         | 8.89%   |
| 2020 | 3         | 6.67%   |
| 2023 | 2         | 4.44%   |
| 2021 | 2         | 4.44%   |
| 2018 | 2         | 4.44%   |
| 2016 | 2         | 4.44%   |
| 2013 | 2         | 4.44%   |
| 2011 | 2         | 4.44%   |
| 2010 | 2         | 4.44%   |
| 2022 | 1         | 2.22%   |
| 2009 | 1         | 2.22%   |
| 2008 | 1         | 2.22%   |
| 2007 | 1         | 2.22%   |

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
| No   | 43        | 95.56%  |
| Yes  | 2         | 4.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 20        | 44.44%  |
| 16.01-24.0  | 13        | 28.89%  |
| 4.01-8.0    | 6         | 13.33%  |
| 1.01-2.0    | 2         | 4.44%   |
| 32.01-64.0  | 1         | 2.22%   |
| 3.01-4.0    | 1         | 2.22%   |
| 2.01-3.0    | 1         | 2.22%   |
| 64.01-256.0 | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 21        | 45.65%  |
| 0.51-1.0 | 17        | 36.96%  |
| 1.01-2.0 | 3         | 6.52%   |
| 4.01-8.0 | 2         | 4.35%   |
| 2.01-3.0 | 2         | 4.35%   |
| 0        | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 88.89%  |
| 2      | 3         | 6.67%   |
| 3      | 1         | 2.22%   |
| 0      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 82.22%  |
| Yes       | 8         | 17.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 80%     |
| No        | 9         | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 91.11%  |
| No        | 4         | 8.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 68.89%  |
| No        | 14        | 31.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 45        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 13        | 28.89%  |
| Brisbane     | 7         | 15.56%  |
| Perth        | 6         | 13.33%  |
| Melbourne    | 5         | 11.11%  |
| Canberra     | 3         | 6.67%   |
| Adelaide     | 2         | 4.44%   |
| Warrnambool  | 1         | 2.22%   |
| South Yarra  | 1         | 2.22%   |
| Ryde         | 1         | 2.22%   |
| Kellyville   | 1         | 2.22%   |
| Gold Coast   | 1         | 2.22%   |
| East Malvern | 1         | 2.22%   |
| Darlinghurst | 1         | 2.22%   |
| Burwood      | 1         | 2.22%   |
| Adelaide CBD | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 12     | 26.67%  |
| Toshiba             | 6         | 7      | 13.33%  |
| Intel               | 5         | 5      | 11.11%  |
| Crucial             | 3         | 4      | 6.67%   |
| SK hynix            | 2         | 4      | 4.44%   |
| Seagate             | 2         | 3      | 4.44%   |
| SanDisk             | 2         | 3      | 4.44%   |
| NVMe                | 2         | 3      | 4.44%   |
| Kingston            | 2         | 2      | 4.44%   |
| WDC                 | 1         | 1      | 2.22%   |
| Silicon Motion      | 1         | 1      | 2.22%   |
| Jetflash            | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| HGST                | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |
| FORESEE             | 1         | 1      | 2.22%   |
| Dogfish             | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB      | 2         | 4.35%   |
| Samsung SSD 840 EVO 250GB        | 2         | 4.35%   |
| WDC WD10JPVX-60JC3T0 1TB         | 1         | 2.17%   |
| Toshiba THNSNF256GMCS 256GB      | 1         | 2.17%   |
| Toshiba THNSF5256GCJ7 256GB      | 1         | 2.17%   |
| Toshiba MQ01ABF050 500GB         | 1         | 2.17%   |
| Toshiba MQ01ABD100 1TB           | 1         | 2.17%   |
| SK hynix PC401 NVMe 512GB        | 1         | 2.17%   |
| SK hynix BC501 NVMe 512GB        | 1         | 2.17%   |
| Silicon Motion Aura Pro X2 960GB | 1         | 2.17%   |
| Seagate ST9500325AS 500GB        | 1         | 2.17%   |
| Seagate ST9250315ASG 250GB       | 1         | 2.17%   |
| SanDisk SD8TN8U256G1001 256GB    | 1         | 2.17%   |
| SanDisk SD5SG2128G1052E 128GB    | 1         | 2.17%   |
| Samsung SSD PM871 mSATA 256GB    | 1         | 2.17%   |
| Samsung SSD 860 EVO 500GB        | 1         | 2.17%   |
| Samsung MZVLB512HBJQ-000H1 512GB | 1         | 2.17%   |
| Samsung MZVLB256HAHQ-000L7 256GB | 1         | 2.17%   |
| Samsung MZVLB256HAHQ-00000 256GB | 1         | 2.17%   |
| Samsung MZVL2512HCJQ-00B00 512GB | 1         | 2.17%   |
| Samsung MZNLN256HCHP-000L7 256GB | 1         | 2.17%   |
| Samsung MZMTE128HMGR-00000 128GB | 1         | 2.17%   |
| Samsung MZALQ512HBLU-00BL2 512GB | 1         | 2.17%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 2.17%   |
| NVMe WD_BLACK SN850X 1TB         | 1         | 2.17%   |
| NVMe WD Blue SN570 2T            | 1         | 2.17%   |
| NVMe CT2000P3SSD8 2TB            | 1         | 2.17%   |
| Kingston SV300S37A120G 120GB     | 1         | 2.17%   |
| Kingston SNS4151S316G 16GB       | 1         | 2.17%   |
| Jetflash Transcend 8G            | 1         | 2.17%   |
| Intel SSDSC2KW128G8 128GB        | 1         | 2.17%   |
| Intel SSDSC2BF240A4L 240GB       | 1         | 2.17%   |
| Intel SSDSC2BF180A4L 180GB       | 1         | 2.17%   |
| Intel SSDSA2BW160G3L 160GB       | 1         | 2.17%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 2.17%   |
| Hitachi HTS542525K9A300 250GB    | 1         | 2.17%   |
| HGST HTS725050A7E630 500GB       | 1         | 2.17%   |
| Fujitsu MHY2160BH 160GB          | 1         | 2.17%   |
| FORESEE 64GB SSD                 | 1         | 2.17%   |
| Dogfish SSD 64GB                 | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 2         | 2      | 18.18%  |
| Seagate  | 2         | 3      | 18.18%  |
| NVMe     | 2         | 2      | 18.18%  |
| WDC      | 1         | 1      | 9.09%   |
| Jetflash | 1         | 1      | 9.09%   |
| Hitachi  | 1         | 1      | 9.09%   |
| HGST     | 1         | 1      | 9.09%   |
| Fujitsu  | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 30.43%  |
| Intel               | 4         | 4      | 17.39%  |
| Crucial             | 3         | 4      | 13.04%  |
| SanDisk             | 2         | 3      | 8.7%    |
| Kingston            | 2         | 2      | 8.7%    |
| Toshiba             | 1         | 1      | 4.35%   |
| NVMe                | 1         | 1      | 4.35%   |
| FORESEE             | 1         | 1      | 4.35%   |
| Dogfish             | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 25     | 48.89%  |
| NVMe | 12        | 15     | 26.67%  |
| HDD  | 11        | 12     | 24.44%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 37     | 72.09%  |
| NVMe | 12        | 15     | 27.91%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 84.38%  |
| 0.51-1.0   | 4         | 5      | 12.5%   |
| 1.01-2.0   | 1         | 2      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 35.56%  |
| 1-20       | 11        | 24.44%  |
| 251-500    | 10        | 22.22%  |
| 51-100     | 5         | 11.11%  |
| 501-1000   | 2         | 4.44%   |
| 21-50      | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 39        | 82.98%  |
| 21-50   | 4         | 8.51%   |
| 51-100  | 3         | 6.38%   |
| 101-250 | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Kingston SNS4151S316G 16GB    | 1         | 1      | 20%     |
| Intel SSDSC2BF180A4L 180GB    | 1         | 1      | 20%     |
| Hitachi HTS542525K9A300 250GB | 1         | 1      | 20%     |
| HGST HTS725050A7E630 500GB    | 1         | 1      | 20%     |
| Apple SSD SM256E 256GB        | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 1         | 1      | 20%     |
| Intel    | 1         | 1      | 20%     |
| Hitachi  | 1         | 1      | 20%     |
| HGST     | 1         | 1      | 20%     |
| Apple    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 37        | 44     | 84.09%  |
| Malfunc  | 5         | 5      | 11.36%  |
| Detected | 2         | 3      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 32        | 66.67%  |
| Samsung Electronics       | 5         | 10.42%  |
| Toshiba                   | 3         | 6.25%   |
| Sandisk                   | 2         | 4.17%   |
| AMD                       | 2         | 4.17%   |
| SK hynix                  | 1         | 2.08%   |
| Silicon Motion            | 1         | 2.08%   |
| Nvidia                    | 1         | 2.08%   |
| Micron/Crucial Technology | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 14.29%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 12.24%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 8.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 6.12%   |
| Toshiba XG4 NVMe SSD Controller                                                | 2         | 4.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.08%   |
| Toshiba XG3 NVMe SSD Controller                                                | 1         | 2.04%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 2.04%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2.04%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 1         | 2.04%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.04%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 2.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 2.04%   |
| Intel SSD 660P Series                                                          | 1         | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 32        | 66.67%  |
| NVMe | 13        | 27.08%  |
| RAID | 2         | 4.17%   |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 95.56%  |
| AMD    | 2         | 4.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                             | 3         | 6.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 2         | 4.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz                             | 2         | 4.44%   |
| Intel Core i7-3667U CPU @ 2.00GHz                             | 2         | 4.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 4.44%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH                            | 1         | 2.22%   |
| Intel CPU Version                                             | 1         | 2.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 1         | 2.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 1         | 2.22%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                            | 1         | 2.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 2.22%   |
| Intel Core i7-6500U CPU @ 2.50GHz                             | 1         | 2.22%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz                            | 1         | 2.22%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 2.22%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 1         | 2.22%   |
| Intel Core i7-3537U CPU @ 2.00GHz                             | 1         | 2.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                            | 1         | 2.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 2.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 2.22%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 2.22%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 1         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 2.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 2.22%   |
| Intel Core i5-4210Y CPU @ 1.50GHz                             | 1         | 2.22%   |
| Intel Core i5-3380M CPU @ 2.90GHz                             | 1         | 2.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz                             | 1         | 2.22%   |
| Intel Core i5 CPU M 480 @ 2.67GH                              | 1         | 2.22%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 2.22%   |
| Intel Core Duo CPU L2400 @ 1.66GHz ("GenuineIntel" 686-class) | 1         | 2.22%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz                          | 1         | 2.22%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 2.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz                             | 1         | 2.22%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 1         | 2.22%   |
| Intel Celeron CPU 1007U @ 1.50GHz                             | 1         | 2.22%   |
| Intel Celeron 2955U @ 1.40GHz                                 | 1         | 2.22%   |
| Intel 12th Gen Core i5-1240P                                  | 1         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                       | 1         | 2.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics                        | 1         | 2.22%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics                   | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 18        | 40%     |
| Intel Core i5    | 13        | 28.89%  |
| Intel Celeron    | 4         | 8.89%   |
| Other            | 3         | 6.67%   |
| Intel Core 2 Duo | 2         | 4.44%   |
| Intel Xeon       | 1         | 2.22%   |
| Intel Core i3    | 1         | 2.22%   |
| Intel Core Duo   | 1         | 2.22%   |
| AMD Ryzen 5      | 1         | 2.22%   |
| AMD A6           | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 27        | 60%     |
| 4       | 10        | 22.22%  |
| Unknown | 3         | 6.67%   |
| 6       | 2         | 4.44%   |
| 16      | 1         | 2.22%   |
| 12      | 1         | 2.22%   |
| 1       | 1         | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 43        | 95.56%  |
| 2       | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 34        | 75.56%  |
| 1       | 8         | 17.78%  |
| Unknown | 3         | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 8         | 17.78%  |
| Haswell     | 8         | 17.78%  |
| Skylake     | 6         | 13.33%  |
| KabyLake    | 6         | 13.33%  |
| SandyBridge | 4         | 8.89%   |
| Broadwell   | 2         | 4.44%   |
| Unknown     | 2         | 4.44%   |
| Westmere    | 1         | 2.22%   |
| TigerLake   | 1         | 2.22%   |
| Silvermont  | 1         | 2.22%   |
| Puma        | 1         | 2.22%   |
| Penryn      | 1         | 2.22%   |
| P6          | 1         | 2.22%   |
| Core        | 1         | 2.22%   |
| CometLake   | 1         | 2.22%   |
| Bonnell     | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 38        | 69.09%  |
| Nvidia         | 10        | 18.18%  |
| AMD            | 6         | 10.91%  |
| Silicon Motion | 1         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 12.5%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 8.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 8.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.36%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.57%   |
| Intel HD Graphics 620                                                                    | 2         | 3.57%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.57%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 1.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.79%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.79%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.79%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.79%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.79%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.79%   |
| Intel HD Graphics 530                                                                    | 1         | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.79%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.79%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.79%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 1.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.79%   |
| AMD Mars [Radeon HD 8730M]                                                               | 1         | 1.79%   |
| AMD Lucienne                                                                             | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 26        | 57.78%  |
| Intel + Nvidia     | 7         | 15.56%  |
| 1 x Nvidia         | 3         | 6.67%   |
| Intel + AMD        | 3         | 6.67%   |
| 1 x AMD            | 3         | 6.67%   |
| 2 x Intel          | 2         | 4.44%   |
| 1 x Silicon Motion | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 93.48%  |
| Unknown     | 2         | 4.35%   |
| Proprietary | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 95.56%  |
| 1.01-2.0   | 1         | 2.22%   |
| 0.01-0.5   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 27.27%  |
| LG Display          | 5         | 22.73%  |
| BOE                 | 3         | 13.64%  |
| Sharp               | 2         | 9.09%   |
| Samsung Electronics | 2         | 9.09%   |
| Chimei Innolux      | 2         | 9.09%   |
| Panasonic           | 1         | 4.55%   |
| Lenovo              | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 4.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 4.55%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 4.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 4.55%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 4.55%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 4.55%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 4.55%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 4.55%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 4.55%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 4.55%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 4.55%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 45.45%  |
| 1366x768 (WXGA) | 7         | 31.82%  |
| 2560x1440 (QHD) | 2         | 9.09%   |
| 2880x1620       | 1         | 4.55%   |
| 1600x900 (HD+)  | 1         | 4.55%   |
| 1280x720 (HD)   | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 40.91%  |
| 15     | 6         | 27.27%  |
| 11     | 3         | 13.64%  |
| 12     | 2         | 9.09%   |
| 17     | 1         | 4.55%   |
| 10     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 59.09%  |
| 201-300     | 8         | 36.36%  |
| 351-400     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 31.82%  |
| 91-100         | 5         | 22.73%  |
| 51-60          | 3         | 13.64%  |
| 71-80          | 2         | 9.09%   |
| 61-70          | 2         | 9.09%   |
| 41-50          | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |
| 101-110        | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 13        | 59.09%  |
| 161-240 | 5         | 22.73%  |
| 101-120 | 3         | 13.64%  |
| 51-100  | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 60.87%  |
| 0     | 18        | 39.13%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 48.44%  |
| Realtek Semiconductor             | 13        | 20.31%  |
| Qualcomm Atheros                  | 6         | 9.38%   |
| Broadcom                          | 5         | 7.81%   |
| Ericsson Business Mobile Networks | 2         | 3.13%   |
| Sierra Wireless                   | 1         | 1.56%   |
| Samsung Electronics               | 1         | 1.56%   |
| Nvidia                            | 1         | 1.56%   |
| NetGear                           | 1         | 1.56%   |
| Microsoft                         | 1         | 1.56%   |
| MediaTek                          | 1         | 1.56%   |
| Marvell Technology Group          | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 9         | 10.47%  |
| Intel Wireless 8260                                                | 6         | 6.98%   |
| Intel Wireless 8265 / 8275                                         | 3         | 3.49%   |
| Intel Wireless 7265                                                | 3         | 3.49%   |
| Intel Wireless 7260                                                | 3         | 3.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 3.49%   |
| Intel 82574L Gigabit Network Connection                            | 3         | 3.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 2         | 2.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 2         | 2.33%   |
| Intel Ethernet Connection I219-V                                   | 2         | 2.33%   |
| Intel Ethernet Connection I219-LM                                  | 2         | 2.33%   |
| Intel Ethernet Connection I218-LM                                  | 2         | 2.33%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 2.33%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 2         | 2.33%   |
| Sierra Wireless EM7455                                             | 1         | 1.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 1         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 1.16%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                   | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 1.16%   |
| Nvidia MCP79 Ethernet                                              | 1         | 1.16%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                    | 1         | 1.16%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                 | 1         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 1.16%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller            | 1         | 1.16%   |
| Intel Wireless 3165                                                | 1         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                | 1         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection              | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 61.36%  |
| Qualcomm Atheros      | 6         | 13.64%  |
| Broadcom              | 5         | 11.36%  |
| Realtek Semiconductor | 3         | 6.82%   |
| Sierra Wireless       | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| MediaTek              | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 6         | 13.33%  |
| Intel Wireless 8265 / 8275                                     | 3         | 6.67%   |
| Intel Wireless 7265                                            | 3         | 6.67%   |
| Intel Wireless 7260                                            | 3         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 6.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 4.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 4.44%   |
| Sierra Wireless EM7455                                         | 1         | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.22%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.22%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                | 1         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.22%   |
| Intel Wireless 3165                                            | 1         | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.22%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 48.65%  |
| Realtek Semiconductor    | 12        | 32.43%  |
| Qualcomm Atheros         | 2         | 5.41%   |
| Samsung Electronics      | 1         | 2.7%    |
| Nvidia                   | 1         | 2.7%    |
| Microsoft                | 1         | 2.7%    |
| Marvell Technology Group | 1         | 2.7%    |
| Broadcom                 | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 23.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.69%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 7.69%   |
| Intel Ethernet Connection I219-V                                  | 2         | 5.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 5.13%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 5.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.13%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.56%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 2.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.56%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                | 1         | 2.56%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 2.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 51.9%   |
| Ethernet | 36        | 45.57%  |
| Modem    | 2         | 2.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 50%     |
| Ethernet | 27        | 48.21%  |
| Modem    | 1         | 1.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 31        | 68.89%  |
| 1     | 12        | 26.67%  |
| 6     | 1         | 2.22%   |
| 4     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 91.11%  |
| Yes  | 4         | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 54.84%  |
| Broadcom                        | 3         | 9.68%   |
| Apple                           | 3         | 9.68%   |
| Realtek Semiconductor           | 2         | 6.45%   |
| Qualcomm Atheros Communications | 2         | 6.45%   |
| Foxconn / Hon Hai               | 2         | 6.45%   |
| IMC Networks                    | 1         | 3.23%   |
| Hewlett-Packard                 | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 13        | 41.94%  |
| Intel AX201 Bluetooth                                  | 2         | 6.45%   |
| Apple Bluetooth Host Controller                        | 2         | 6.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 3.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                 | 1         | 3.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 3.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 1         | 3.23%   |
| Intel AX210 Bluetooth                                  | 1         | 3.23%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 3.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 3.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 3.23%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 3.23%   |
| Broadcom Bluetooth 4.0                                 | 1         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 3.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 40        | 83.33%  |
| Nvidia | 5         | 10.42%  |
| AMD    | 3         | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 13.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 12.07%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 10.34%  |
| Intel 8 Series HD Audio Controller                                                                | 5         | 8.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 6.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.45%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.72%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 44.44%  |
| SK hynix            | 9         | 20%     |
| Micron Technology   | 6         | 13.33%  |
| Kingston            | 3         | 6.67%   |
| Crucial             | 3         | 6.67%   |
| Unknown             | 1         | 2.22%   |
| Transcend           | 1         | 2.22%   |
| Corsair             | 1         | 2.22%   |
| ASint Technology    | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 4.17%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 2.08%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 1         | 2.08%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.08%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 2.08%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 2.08%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                            | 1         | 2.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 2.08%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 2.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.08%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.08%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.08%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 2.08%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                            | 1         | 2.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                 | 1         | 2.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s              | 1         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s                   | 1         | 2.08%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.08%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB Chip DDR4 2133MT/s          | 1         | 2.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.08%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 2.08%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s           | 1         | 2.08%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s             | 1         | 2.08%   |
| Micron RAM MT52L512M32D2PF-10 4GB SODIMM LPDDR3 1867MT/s         | 1         | 2.08%   |
| Micron RAM MT52L512M32D2PF-10 4GB Chip LPDDR3 1867MT/s           | 1         | 2.08%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 2.08%   |
| Micron RAM L512M32D2PF107WT:B 4GB Row Of Chips LPDDR3 1867MT/s   | 1         | 2.08%   |
| Micron RAM 8KTF51264HZ-1G9E2 4GB SODIMM DDR3 1867MT/s            | 1         | 2.08%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.08%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 1         | 2.08%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s          | 1         | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 59.46%  |
| DDR4    | 7         | 18.92%  |
| LPDDR3  | 5         | 13.51%  |
| LPDDR4  | 1         | 2.7%    |
| DDR2    | 1         | 2.7%    |
| Unknown | 1         | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 70%     |
| Row Of Chips | 5         | 12.5%   |
| Chip         | 5         | 12.5%   |
| Unknown      | 2         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 16        | 39.02%  |
| 8192  | 15        | 36.59%  |
| 2048  | 6         | 14.63%  |
| 16384 | 4         | 9.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 16        | 40%     |
| 1867  | 5         | 12.5%   |
| 1333  | 5         | 12.5%   |
| 2667  | 3         | 7.5%    |
| 2400  | 3         | 7.5%    |
| 2133  | 2         | 5%      |
| 667   | 2         | 5%      |
| 4267  | 1         | 2.5%    |
| 3200  | 1         | 2.5%    |
| 1067  | 1         | 2.5%    |
| 800   | 1         | 2.5%    |

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
| Chicony Electronics                    | 10        | 35.71%  |
| Bison Electronics                      | 5         | 17.86%  |
| IMC Networks                           | 4         | 14.29%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Z-Star Microelectronics                | 1         | 3.57%   |
| Suyin                                  | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| Microdia                               | 1         | 3.57%   |
| Luxvisions Innotech Limited            | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| Apple                                  | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 6         | 20.69%  |
| Bison Integrated Camera                                      | 3         | 10.34%  |
| IMC Networks Integrated Webcam                               | 2         | 6.9%    |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 3.45%   |
| Suyin Lenovo Integrated Webcam                               | 1         | 3.45%   |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 3.45%   |
| Sunplus HD WebCam                                            | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD                                 | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                                | 1         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 3.45%   |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 3.45%   |
| IMC Networks EasyCamera                                      | 1         | 3.45%   |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 3.45%   |
| Chicony Lenovo Integrated Camera                             | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 3.45%   |
| Bison Lenovo Integrated Webcam                               | 1         | 3.45%   |
| Bison Lenovo EasyCamera                                      | 1         | 3.45%   |
| Apple FaceTime HD Camera (Built-in)                          | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 75%     |
| Elan Microelectronics | 2         | 16.67%  |
| Upek                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 4         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 25%     |
| Elan Fingerprint Sensor                                | 2         | 16.67%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 8.33%   |

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
| 1     | 18        | 39.13%  |
| 3     | 15        | 32.61%  |
| 2     | 8         | 17.39%  |
| 0     | 3         | 6.52%   |
| 6     | 1         | 2.17%   |
| 5     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 36        | 42.86%  |
| Bluetooth                | 12        | 14.29%  |
| Card reader              | 11        | 13.1%   |
| Fingerprint reader       | 10        | 11.9%   |
| Net/wireless             | 7         | 8.33%   |
| Graphics card            | 3         | 3.57%   |
| Firewire controller      | 2         | 2.38%   |
| Sound                    | 1         | 1.19%   |
| Network                  | 1         | 1.19%   |
| Net/ethernet             | 1         | 1.19%   |

