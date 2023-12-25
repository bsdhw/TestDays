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

Total: 73

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ed79ea60c4](https://bsd-hardware.info/?probe=ed79ea60c4) | Nov 13, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [2e6af170b9](https://bsd-hardware.info/?probe=2e6af170b9) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
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
| helloSystem 0.8.1   | 4         | 6.56%   |
| FreeBSD 13.0        | 4         | 6.56%   |
| OpenBSD 6.8         | 3         | 4.92%   |
| helloSystem 0.4.0   | 3         | 4.92%   |
| FreeBSD 13.2        | 3         | 4.92%   |
| OPNsense 22.1.6     | 2         | 3.28%   |
| OPNsense 21.1.3     | 2         | 3.28%   |
| OpenBSD 7.2         | 2         | 3.28%   |
| helloSystem 0.6.0   | 2         | 3.28%   |
| FreeBSD 14.0-BETA2  | 2         | 3.28%   |
| FreeBSD 12.2        | 2         | 3.28%   |
| FreeBSD 12.1-p10    | 2         | 3.28%   |
| FreeBSD 12.1        | 2         | 3.28%   |
| OPNsense 23.7.3     | 1         | 1.64%   |
| OPNsense 23.1.4     | 1         | 1.64%   |
| OPNsense 22.1.1     | 1         | 1.64%   |
| OPNsense 21.7.1     | 1         | 1.64%   |
| OPNsense 21.7       | 1         | 1.64%   |
| OpenBSD 6.7         | 1         | 1.64%   |
| NomadBSD 81e34fc3   | 1         | 1.64%   |
| NomadBSD 20231013   | 1         | 1.64%   |
| NomadBSD 1.4        | 1         | 1.64%   |
| helloSystem 0.5.0   | 1         | 1.64%   |
| FuguIta 7.1         | 1         | 1.64%   |
| FreeBSD 14.0-RC2    | 1         | 1.64%   |
| FreeBSD 14.0-BETA1  | 1         | 1.64%   |
| FreeBSD 14.0-ALPHA3 | 1         | 1.64%   |
| FreeBSD 14.0        | 1         | 1.64%   |
| FreeBSD 13.2-STABLE | 1         | 1.64%   |
| FreeBSD 13.2-p4     | 1         | 1.64%   |
| FreeBSD 13.2-p3     | 1         | 1.64%   |
| FreeBSD 13.2-p2     | 1         | 1.64%   |
| FreeBSD 13.1        | 1         | 1.64%   |
| FreeBSD 13.0-RC5    | 1         | 1.64%   |
| FreeBSD 13.0-p7     | 1         | 1.64%   |
| FreeBSD 13.0-p6     | 1         | 1.64%   |
| FreeBSD 13.0-BETA1  | 1         | 1.64%   |
| FreeBSD 12.2-p3     | 1         | 1.64%   |
| FreeBSD 12.2-p2     | 1         | 1.64%   |
| FreeBSD 12.1-p6     | 1         | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 27        | 48.21%  |
| helloSystem | 10        | 17.86%  |
| OPNsense    | 9         | 16.07%  |
| OpenBSD     | 6         | 10.71%  |
| NomadBSD    | 3         | 5.36%   |
| FuguIta     | 1         | 1.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 55        | 98.21%  |
| i386  | 1         | 1.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 16        | 28.07%  |
| helloDesktop | 13        | 22.81%  |
| XFCE         | 5         | 8.77%   |
| KDE5         | 5         | 8.77%   |
| fvwm         | 4         | 7.02%   |
| Openbox      | 3         | 5.26%   |
| i3           | 3         | 5.26%   |
| GNOME        | 3         | 5.26%   |
| TWM          | 2         | 3.51%   |
| Fluxbox      | 2         | 3.51%   |
| AwesomeWM    | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 39        | 68.42%  |
| Console | 11        | 19.3%   |
| Wayland | 7         | 12.28%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 32        | 56.14%  |
| SLiM    | 11        | 19.3%   |
| SDDM    | 9         | 15.79%  |
| XDM     | 1         | 1.75%   |
| PCDM    | 1         | 1.75%   |
| Ly      | 1         | 1.75%   |
| LightDM | 1         | 1.75%   |
| GDM     | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 23        | 38.98%  |
| C               | 14        | 23.73%  |
| en_US           | 13        | 22.03%  |
| en_AU           | 7         | 11.86%  |
| en_AU.US-ASCII  | 1         | 1.69%   |
| en_AU.ISO8859-1 | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 46        | 82.14%  |
| BIOS | 10        | 17.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 29        | 51.79%  |
| Ufs    | 16        | 28.57%  |
| Ffs    | 7         | 12.5%   |
| Cd9660 | 4         | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 49        | 87.5%   |
| MBR  | 7         | 12.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 23        | 41.07%  |
| Hewlett-Packard      | 7         | 12.5%   |
| Dell                 | 6         | 10.71%  |
| Toshiba              | 3         | 5.36%   |
| ASUSTek Computer     | 3         | 5.36%   |
| Apple                | 3         | 5.36%   |
| Unknown              | 3         | 5.36%   |
| Acer                 | 2         | 3.57%   |
| Timi                 | 1         | 1.79%   |
| Samsung Electronics  | 1         | 1.79%   |
| ReachingTech         | 1         | 1.79%   |
| Intel Client Systems | 1         | 1.79%   |
| Intel                | 1         | 1.79%   |
| Framework            | 1         | 1.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 3         | 5.36%   |
| Dell XPS 13 9360                                                                         | 2         | 3.57%   |
| Dell G5 5590                                                                             | 2         | 3.57%   |
| Toshiba Satellite L50-A                                                                  | 1         | 1.79%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 1.79%   |
| Toshiba KIRA                                                                             | 1         | 1.79%   |
| Timi TM1701                                                                              | 1         | 1.79%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 1.79%   |
| ReachingTech DreamQuest Pro 2022                                                         | 1         | 1.79%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 1.79%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 1.79%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 1.79%   |
| Lenovo ThinkPad X1C 5th W10DG 20K3A03CAU                                                 | 1         | 1.79%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS2XW00                                               | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW                                              | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB006FAU                                                 | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 1.79%   |
| Lenovo ThinkPad X1 Carbon 3443CTO                                                        | 1         | 1.79%   |
| Lenovo ThinkPad T480s 20L7S24F00                                                         | 1         | 1.79%   |
| Lenovo ThinkPad T470 W10DG 20JM000BUS                                                    | 1         | 1.79%   |
| Lenovo ThinkPad T470 20HES0ES1F                                                          | 1         | 1.79%   |
| Lenovo ThinkPad T460p 20FXCTO1WW                                                         | 1         | 1.79%   |
| Lenovo ThinkPad T450 20BVA020AU                                                          | 1         | 1.79%   |
| Lenovo ThinkPad T440s 20ARS1BK08                                                         | 1         | 1.79%   |
| Lenovo ThinkPad Mini10 3507A31                                                           | 1         | 1.79%   |
| Lenovo ThinkPad L390 20NRS00Q00                                                          | 1         | 1.79%   |
| Lenovo ThinkPad E420 1141CTO                                                             | 1         | 1.79%   |
| Lenovo IdeaPad 5 15ALC05 82LN                                                            | 1         | 1.79%   |
| Lenovo G40-70 20369                                                                      | 1         | 1.79%   |
| Intel SandyBridge Platform                                                               | 1         | 1.79%   |
| Intel Client Systems LAPBC510                                                            | 1         | 1.79%   |
| HP ZBook 14                                                                              | 1         | 1.79%   |
| HP Setzer                                                                                | 1         | 1.79%   |
| HP ProBook 430 G3                                                                        | 1         | 1.79%   |
| HP Pavilion dv5                                                                          | 1         | 1.79%   |
| HP Notebook                                                                              | 1         | 1.79%   |
| HP Laptop 15s-du1xxx                                                                     | 1         | 1.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 21        | 37.5%   |
| Unknown                       | 3         | 5.36%   |
| Dell XPS                      | 2         | 3.57%   |
| Dell G5                       | 2         | 3.57%   |
| Toshiba Satellite             | 1         | 1.79%   |
| Toshiba PORTEGE               | 1         | 1.79%   |
| Toshiba KIRA                  | 1         | 1.79%   |
| Timi TM1701                   | 1         | 1.79%   |
| Samsung 350V5C                | 1         | 1.79%   |
| ReachingTech DreamQuest       | 1         | 1.79%   |
| Lenovo IdeaPad                | 1         | 1.79%   |
| Lenovo G40-70                 | 1         | 1.79%   |
| Intel SandyBridge             | 1         | 1.79%   |
| Intel Client Systems LAPBC510 | 1         | 1.79%   |
| HP ZBook                      | 1         | 1.79%   |
| HP Setzer                     | 1         | 1.79%   |
| HP ProBook                    | 1         | 1.79%   |
| HP Pavilion                   | 1         | 1.79%   |
| HP Notebook                   | 1         | 1.79%   |
| HP Laptop                     | 1         | 1.79%   |
| HP Compaq                     | 1         | 1.79%   |
| Framework Laptop              | 1         | 1.79%   |
| Dell Latitude                 | 1         | 1.79%   |
| Dell G16                      | 1         | 1.79%   |
| ASUS TP500LNG                 | 1         | 1.79%   |
| ASUS K72F                     | 1         | 1.79%   |
| ASUS G74Sx                    | 1         | 1.79%   |
| Apple MacBookPro5             | 1         | 1.79%   |
| Apple MacBookPro11            | 1         | 1.79%   |
| Apple MacBookAir5             | 1         | 1.79%   |
| Acer Peppy                    | 1         | 1.79%   |
| Acer Nitro                    | 1         | 1.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 7         | 12.5%   |
| 2015 | 6         | 10.71%  |
| 2017 | 5         | 8.93%   |
| 2023 | 4         | 7.14%   |
| 2021 | 4         | 7.14%   |
| 2020 | 4         | 7.14%   |
| 2014 | 4         | 7.14%   |
| 2012 | 4         | 7.14%   |
| 2022 | 3         | 5.36%   |
| 2018 | 3         | 5.36%   |
| 2016 | 2         | 3.57%   |
| 2013 | 2         | 3.57%   |
| 2011 | 2         | 3.57%   |
| 2010 | 2         | 3.57%   |
| 2009 | 2         | 3.57%   |
| 2008 | 1         | 1.79%   |
| 2007 | 1         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 56        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 96.43%  |
| Yes  | 2         | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 23        | 41.07%  |
| 16.01-24.0  | 18        | 32.14%  |
| 4.01-8.0    | 7         | 12.5%   |
| 32.01-64.0  | 3         | 5.36%   |
| 1.01-2.0    | 2         | 3.57%   |
| 3.01-4.0    | 1         | 1.79%   |
| 2.01-3.0    | 1         | 1.79%   |
| 64.01-256.0 | 1         | 1.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 24        | 42.11%  |
| 0.01-0.5 | 23        | 40.35%  |
| 1.01-2.0 | 5         | 8.77%   |
| 4.01-8.0 | 2         | 3.51%   |
| 2.01-3.0 | 2         | 3.51%   |
| 0        | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 78.57%  |
| 0      | 7         | 12.5%   |
| 2      | 4         | 7.14%   |
| 3      | 1         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 47        | 83.93%  |
| Yes       | 9         | 16.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 78.57%  |
| No        | 12        | 21.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 92.86%  |
| No        | 4         | 7.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 73.68%  |
| No        | 15        | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 56        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Sydney       | 21        | 37.5%   |
| Brisbane     | 7         | 12.5%   |
| Perth        | 6         | 10.71%  |
| Melbourne    | 6         | 10.71%  |
| Adelaide     | 4         | 7.14%   |
| Canberra     | 3         | 5.36%   |
| Warrnambool  | 1         | 1.79%   |
| South Yarra  | 1         | 1.79%   |
| Ryde         | 1         | 1.79%   |
| Kellyville   | 1         | 1.79%   |
| Gold Coast   | 1         | 1.79%   |
| East Malvern | 1         | 1.79%   |
| Darlinghurst | 1         | 1.79%   |
| Burwood      | 1         | 1.79%   |
| Adelaide CBD | 1         | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 15     | 29.41%  |
| Toshiba             | 6         | 7      | 11.76%  |
| Intel               | 5         | 5      | 9.8%    |
| Seagate             | 4         | 5      | 7.84%   |
| Crucial             | 3         | 4      | 5.88%   |
| SK hynix            | 2         | 4      | 3.92%   |
| SanDisk             | 2         | 3      | 3.92%   |
| NVMe                | 2         | 3      | 3.92%   |
| Kingston            | 2         | 2      | 3.92%   |
| WDC                 | 1         | 1      | 1.96%   |
| Silicon Motion      | 1         | 1      | 1.96%   |
| Lenovo              | 1         | 1      | 1.96%   |
| Jetflash            | 1         | 1      | 1.96%   |
| Hitachi             | 1         | 1      | 1.96%   |
| HGST                | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| FORESEE             | 1         | 1      | 1.96%   |
| Dogfish             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba THNSF5256GPUK 256GB          | 2         | 3.85%   |
| Samsung SSD 840 EVO 250GB            | 2         | 3.85%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1.92%   |
| Toshiba THNSNF256GMCS 256GB          | 1         | 1.92%   |
| Toshiba THNSF5256GCJ7 256GB          | 1         | 1.92%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1.92%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1.92%   |
| SK hynix PC401 NVMe 512GB            | 1         | 1.92%   |
| SK hynix BC501 NVMe 512GB            | 1         | 1.92%   |
| Silicon Motion Aura Pro X2 960GB     | 1         | 1.92%   |
| Seagate ST9750420AS 752GB            | 1         | 1.92%   |
| Seagate ST9500325AS 500GB            | 1         | 1.92%   |
| Seagate ST9250315ASG 250GB           | 1         | 1.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.92%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 1.92%   |
| SanDisk SD5SG2128G1052E 128GB        | 1         | 1.92%   |
| Samsung SSD PM871 mSATA 256GB        | 1         | 1.92%   |
| Samsung SSD 980 1TB                  | 1         | 1.92%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.92%   |
| Samsung PM961 NVMe 256GB             | 1         | 1.92%   |
| Samsung MZVLB512HBJQ-000H1 512GB     | 1         | 1.92%   |
| Samsung MZVLB256HAHQ-000L7 256GB     | 1         | 1.92%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 1         | 1.92%   |
| Samsung MZVL2512HCJQ-00BL7 512GB     | 1         | 1.92%   |
| Samsung MZVL2512HCJQ-00B00 512GB     | 1         | 1.92%   |
| Samsung MZNLN256HCHP-000L7 256GB     | 1         | 1.92%   |
| Samsung MZMTE128HMGR-00000 128GB     | 1         | 1.92%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 1.92%   |
| Samsung MZ7PC128HAFU-000L1 128GB     | 1         | 1.92%   |
| NVMe WD_BLACK SN850X 1TB             | 1         | 1.92%   |
| NVMe WD Blue SN570 2T                | 1         | 1.92%   |
| NVMe CT2000P3SSD8 2TB                | 1         | 1.92%   |
| Lenovo LENSE30256GMSP34MEAT3TA 256GB | 1         | 1.92%   |
| Kingston SV300S37A120G 120GB         | 1         | 1.92%   |
| Kingston SNS4151S316G 16GB           | 1         | 1.92%   |
| Jetflash Transcend 8G                | 1         | 1.92%   |
| Intel SSDSC2KW128G8 128GB            | 1         | 1.92%   |
| Intel SSDSC2BF240A4L 240GB           | 1         | 1.92%   |
| Intel SSDSC2BF180A4L 180GB           | 1         | 1.92%   |
| Intel SSDSA2BW160G3L 160GB           | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 5      | 30.77%  |
| Toshiba  | 2         | 2      | 15.38%  |
| NVMe     | 2         | 2      | 15.38%  |
| WDC      | 1         | 1      | 7.69%   |
| Jetflash | 1         | 1      | 7.69%   |
| Hitachi  | 1         | 1      | 7.69%   |
| HGST     | 1         | 1      | 7.69%   |
| Fujitsu  | 1         | 1      | 7.69%   |

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
| SSD  | 22        | 25     | 43.14%  |
| NVMe | 16        | 19     | 31.37%  |
| HDD  | 13        | 14     | 25.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 39     | 67.35%  |
| NVMe | 16        | 19     | 32.65%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 30     | 79.41%  |
| 0.51-1.0   | 5         | 6      | 14.71%  |
| 1.01-2.0   | 2         | 3      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 35.71%  |
| 251-500    | 14        | 25%     |
| 1-20       | 12        | 21.43%  |
| 51-100     | 5         | 8.93%   |
| 501-1000   | 4         | 7.14%   |
| 21-50      | 1         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 48        | 82.76%  |
| 21-50   | 5         | 8.62%   |
| 51-100  | 3         | 5.17%   |
| 101-250 | 2         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST2000LM003 HN-M201RAD 2TB | 1         | 1      | 16.67%  |
| Kingston SNS4151S316G 16GB         | 1         | 1      | 16.67%  |
| Intel SSDSC2BF180A4L 180GB         | 1         | 1      | 16.67%  |
| Hitachi HTS542525K9A300 250GB      | 1         | 1      | 16.67%  |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 16.67%  |
| Apple SSD SM256E 256GB             | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 1         | 1      | 16.67%  |
| Kingston | 1         | 1      | 16.67%  |
| Intel    | 1         | 1      | 16.67%  |
| Hitachi  | 1         | 1      | 16.67%  |
| HGST     | 1         | 1      | 16.67%  |
| Apple    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 50%     |
| HDD  | 3         | 3      | 50%     |

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
| Works    | 42        | 49     | 84%     |
| Malfunc  | 6         | 6      | 12%     |
| Detected | 2         | 3      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 36        | 59.02%  |
| Samsung Electronics       | 10        | 16.39%  |
| Sandisk                   | 4         | 6.56%   |
| Toshiba                   | 3         | 4.92%   |
| AMD                       | 2         | 3.28%   |
| SK hynix                  | 1         | 1.64%   |
| Silicon Motion            | 1         | 1.64%   |
| Nvidia                    | 1         | 1.64%   |
| Micron/Crucial Technology | 1         | 1.64%   |
| Micron Technology         | 1         | 1.64%   |
| Lenovo                    | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 11.29%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 9.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 8.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 6.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 4.84%   |
| Toshiba XG4 NVMe SSD Controller                                                | 2         | 3.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.23%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.23%   |
| Toshiba XG3 NVMe SSD Controller                                                | 1         | 1.61%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.61%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.61%   |
| Sandisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 1         | 1.61%   |
| Sandisk WD Blue SN570 NVMe SSD 2TB                                             | 1         | 1.61%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 1         | 1.61%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                          | 1         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.61%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.61%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.61%   |
| Lenovo LENSE30256GMSP34MEAT3TA                                                 | 1         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.61%   |
| Intel SSD 660P Series                                                          | 1         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.61%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 57.38%  |
| NVMe | 22        | 36.07%  |
| RAID | 3         | 4.92%   |
| IDE  | 1         | 1.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 94.64%  |
| AMD    | 3         | 5.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                             | 3         | 5.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 2         | 3.57%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 2         | 3.57%   |
| Intel Core i7-4510U CPU @ 2.00GHz                             | 2         | 3.57%   |
| Intel Core i7-3667U CPU @ 2.00GHz                             | 2         | 3.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz                             | 2         | 3.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 3.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics                        | 2         | 3.57%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH                            | 1         | 1.79%   |
| Intel CPU Version                                             | 1         | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz                             | 1         | 1.79%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz                            | 1         | 1.79%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 1.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz                             | 1         | 1.79%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz                            | 1         | 1.79%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 1.79%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 1         | 1.79%   |
| Intel Core i7-3537U CPU @ 2.00GHz                             | 1         | 1.79%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                            | 1         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 1.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz                            | 1         | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz                             | 1         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz                             | 1         | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 1         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz                             | 1         | 1.79%   |
| Intel Core i5-4300U CPU @ 1.90GHz                             | 1         | 1.79%   |
| Intel Core i5-4210Y CPU @ 1.50GHz                             | 1         | 1.79%   |
| Intel Core i5-3380M CPU @ 2.90GHz                             | 1         | 1.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz                             | 1         | 1.79%   |
| Intel Core i5 CPU M 480 @ 2.67GH                              | 1         | 1.79%   |
| Intel Core i3-6100U CPU @ 2.30GHz                             | 1         | 1.79%   |
| Intel Core Duo CPU L2400 @ 1.66GHz ("GenuineIntel" 686-class) | 1         | 1.79%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                          | 1         | 1.79%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz                          | 1         | 1.79%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                          | 1         | 1.79%   |
| Intel Celeron N5105 @ 2.00GHz                                 | 1         | 1.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz                             | 1         | 1.79%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 1         | 1.79%   |
| Intel Celeron CPU 1007U @ 1.50GHz                             | 1         | 1.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 19        | 33.93%  |
| Intel Core i5    | 17        | 30.36%  |
| Other            | 6         | 10.71%  |
| Intel Celeron    | 5         | 8.93%   |
| Intel Core 2 Duo | 3         | 5.36%   |
| AMD Ryzen 5      | 2         | 3.57%   |
| Intel Xeon       | 1         | 1.79%   |
| Intel Core i3    | 1         | 1.79%   |
| Intel Core Duo   | 1         | 1.79%   |
| AMD A6           | 1         | 1.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 51.79%  |
| 4       | 14        | 25%     |
| Unknown | 4         | 7.14%   |
| 6       | 3         | 5.36%   |
| 12      | 2         | 3.57%   |
| 16      | 1         | 1.79%   |
| 10      | 1         | 1.79%   |
| 8       | 1         | 1.79%   |
| 1       | 1         | 1.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 54        | 96.43%  |
| 2       | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 75%     |
| 1       | 10        | 17.86%  |
| Unknown | 4         | 7.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 17.86%  |
| IvyBridge   | 8         | 14.29%  |
| Haswell     | 8         | 14.29%  |
| Skylake     | 7         | 12.5%   |
| Unknown     | 6         | 10.71%  |
| SandyBridge | 4         | 7.14%   |
| TigerLake   | 2         | 3.57%   |
| Penryn      | 2         | 3.57%   |
| Broadwell   | 2         | 3.57%   |
| Westmere    | 1         | 1.79%   |
| Silvermont  | 1         | 1.79%   |
| Puma        | 1         | 1.79%   |
| P6          | 1         | 1.79%   |
| Core        | 1         | 1.79%   |
| CometLake   | 1         | 1.79%   |
| Bonnell     | 1         | 1.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 47        | 69.12%  |
| Nvidia         | 13        | 19.12%  |
| AMD            | 7         | 10.29%  |
| Silicon Motion | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 10.14%  |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 8.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 7.25%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.35%   |
| Intel HD Graphics 620                                                                    | 3         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 4.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.9%    |
| Intel HD Graphics 5500                                                                   | 2         | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 2.9%    |
| AMD Lucienne                                                                             | 2         | 2.9%    |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 1.45%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.45%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.45%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.45%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.45%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.45%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.45%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.45%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.45%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 1         | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.45%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 1         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.45%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.45%   |
| Intel HD Graphics 530                                                                    | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 1         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.45%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 1.45%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.45%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 33        | 58.93%  |
| Intel + Nvidia     | 9         | 16.07%  |
| 1 x Nvidia         | 4         | 7.14%   |
| 1 x AMD            | 4         | 7.14%   |
| Intel + AMD        | 3         | 5.36%   |
| 2 x Intel          | 2         | 3.57%   |
| 1 x Silicon Motion | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 89.47%  |
| Proprietary | 4         | 7.02%   |
| Unknown     | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 91.07%  |
| 0.01-0.5   | 3         | 5.36%   |
| 7.01-8.0   | 1         | 1.79%   |
| 1.01-2.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 25%     |
| LG Display          | 5         | 17.86%  |
| Sharp               | 3         | 10.71%  |
| BOE                 | 3         | 10.71%  |
| Samsung Electronics | 2         | 7.14%   |
| Chimei Innolux      | 2         | 7.14%   |
| Panasonic           | 1         | 3.57%   |
| LG Philips          | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |
| CTO                 | 1         | 3.57%   |
| Unknown             | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 2         | 7.14%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 2         | 7.14%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 3.57%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 1         | 3.57%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch        | 1         | 3.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 3.57%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 3.57%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                    | 1         | 3.57%   |
| CTO LCD Monitor CTO1412 1920x1200 300x190mm 14.0-inch                | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 3.57%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 3.57%   |
| Unknown                                                              | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 13        | 46.43%  |
| 1366x768 (WXGA)   | 7         | 25%     |
| 2560x1440 (QHD)   | 2         | 7.14%   |
| 3840x2160 (4K)    | 1         | 3.57%   |
| 2560x1600         | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1600x900 (HD+)    | 1         | 3.57%   |
| 1280x800 (WXGA)   | 1         | 3.57%   |
| 1280x720 (HD)     | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 10        | 35.71%  |
| 15      | 7         | 25%     |
| 11      | 3         | 10.71%  |
| 17      | 2         | 7.14%   |
| 12      | 2         | 7.14%   |
| 23      | 1         | 3.57%   |
| 14      | 1         | 3.57%   |
| 10      | 1         | 3.57%   |
| Unknown | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 50%     |
| 201-300     | 10        | 35.71%  |
| 351-400     | 2         | 7.14%   |
| 501-600     | 1         | 3.57%   |
| Unknown     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 25        | 89.29%  |
| 16/10   | 2         | 7.14%   |
| Unknown | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 28.57%  |
| 91-100         | 5         | 17.86%  |
| 71-80          | 3         | 10.71%  |
| 51-60          | 3         | 10.71%  |
| 61-70          | 2         | 7.14%   |
| 121-130        | 2         | 7.14%   |
| 101-110        | 2         | 7.14%   |
| 41-50          | 1         | 3.57%   |
| 201-250        | 1         | 3.57%   |
| Unknown        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 50%     |
| 161-240       | 6         | 21.43%  |
| 101-120       | 3         | 10.71%  |
| 51-100        | 3         | 10.71%  |
| More than 240 | 1         | 3.57%   |
| Unknown       | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 59.65%  |
| 0     | 23        | 40.35%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 41        | 50%     |
| Realtek Semiconductor             | 18        | 21.95%  |
| Qualcomm Atheros                  | 7         | 8.54%   |
| Broadcom                          | 5         | 6.1%    |
| TP-Link                           | 2         | 2.44%   |
| Ericsson Business Mobile Networks | 2         | 2.44%   |
| Sierra Wireless                   | 1         | 1.22%   |
| Samsung Electronics               | 1         | 1.22%   |
| Nvidia                            | 1         | 1.22%   |
| NetGear                           | 1         | 1.22%   |
| Microsoft                         | 1         | 1.22%   |
| MediaTek                          | 1         | 1.22%   |
| Marvell Technology Group          | 1         | 1.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 13        | 11.93%  |
| Intel Wireless 8260                                                | 8         | 7.34%   |
| Intel Wireless 8265 / 8275                                         | 4         | 3.67%   |
| Intel Wireless 7265                                                | 4         | 3.67%   |
| Intel Wireless 7260                                                | 3         | 2.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection            | 3         | 2.75%   |
| Intel Ethernet Connection I219-LM                                  | 3         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 3         | 2.75%   |
| Intel 82574L Gigabit Network Connection                            | 3         | 2.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 2         | 1.83%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                   | 2         | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 2         | 1.83%   |
| Intel Wi-Fi 6 AX201                                                | 2         | 1.83%   |
| Intel Ethernet Connection I219-V                                   | 2         | 1.83%   |
| Intel Ethernet Connection I218-LM                                  | 2         | 1.83%   |
| Intel Ethernet Connection (4) I219-V                               | 2         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                              | 2         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 2         | 1.83%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                    | 2         | 1.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1         | 0.92%   |
| Sierra Wireless EM7455                                             | 1         | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1         | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1         | 0.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 0.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                   | 1         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 0.92%   |
| Nvidia MCP79 Ethernet                                              | 1         | 0.92%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                    | 1         | 0.92%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                 | 1         | 0.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 64.91%  |
| Qualcomm Atheros      | 7         | 12.28%  |
| Broadcom              | 5         | 8.77%   |
| Realtek Semiconductor | 3         | 5.26%   |
| TP-Link               | 2         | 3.51%   |
| Sierra Wireless       | 1         | 1.75%   |
| NetGear               | 1         | 1.75%   |
| MediaTek              | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 8         | 13.56%  |
| Intel Wireless 8265 / 8275                                     | 4         | 6.78%   |
| Intel Wireless 7265                                            | 4         | 6.78%   |
| Intel Wireless 7260                                            | 3         | 5.08%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 3.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.39%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 3.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 3.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.69%   |
| Sierra Wireless EM7455                                         | 1         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.69%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                | 1         | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.69%   |
| Intel Wireless 3165                                            | 1         | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.69%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 1.69%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 1         | 1.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 1.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 21        | 46.67%  |
| Realtek Semiconductor    | 17        | 37.78%  |
| Qualcomm Atheros         | 2         | 4.44%   |
| Samsung Electronics      | 1         | 2.22%   |
| Nvidia                   | 1         | 2.22%   |
| Microsoft                | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| Broadcom                 | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 27.08%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.25%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 6.25%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 4.17%   |
| Intel Ethernet Connection I219-V                                  | 2         | 4.17%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 4.17%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 4.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.17%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.08%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.08%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                | 1         | 2.08%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 2.08%   |
| Intel Ethernet Connection I218-V                                  | 1         | 2.08%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.08%   |
| Intel Ethernet 10G 2P X520 Adapter                                | 1         | 2.08%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.08%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 53.06%  |
| Ethernet | 44        | 44.9%   |
| Modem    | 2         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 49.23%  |
| Ethernet | 32        | 49.23%  |
| Modem    | 1         | 1.54%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 66.07%  |
| 1     | 15        | 26.79%  |
| 3     | 2         | 3.57%   |
| 6     | 1         | 1.79%   |
| 4     | 1         | 1.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 91.07%  |
| Yes  | 5         | 8.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 61.9%   |
| Qualcomm Atheros Communications | 3         | 7.14%   |
| Broadcom                        | 3         | 7.14%   |
| Apple                           | 3         | 7.14%   |
| Realtek Semiconductor           | 2         | 4.76%   |
| Hewlett-Packard                 | 2         | 4.76%   |
| Foxconn / Hon Hai               | 2         | 4.76%   |
| IMC Networks                    | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 17        | 40.48%  |
| Intel AX201 Bluetooth                                  | 4         | 9.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 3         | 7.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                 | 2         | 4.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 2         | 4.76%   |
| Apple Bluetooth Host Controller                        | 2         | 4.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 2.38%   |
| Intel AX211 Bluetooth                                  | 1         | 2.38%   |
| Intel AX210 Bluetooth                                  | 1         | 2.38%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 2.38%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 2.38%   |
| Broadcom Bluetooth 4.0                                 | 1         | 2.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 2.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 50        | 80.65%  |
| Nvidia                                       | 7         | 11.29%  |
| AMD                                          | 4         | 6.45%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 15.07%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 9.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 8.22%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.74%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.74%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 1.37%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.37%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.37%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.37%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1                                  | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.37%   |
| Unknown                                                                                           | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 40.35%  |
| SK hynix            | 13        | 22.81%  |
| Micron Technology   | 8         | 14.04%  |
| Kingston            | 3         | 5.26%   |
| Crucial             | 3         | 5.26%   |
| Team                | 2         | 3.51%   |
| Unknown             | 1         | 1.75%   |
| Transcend           | 1         | 1.75%   |
| Corsair             | 1         | 1.75%   |
| ASint Technology    | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                    | 3         | 4.84%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                     | 2         | 3.23%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                   | 2         | 3.23%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                           | 1         | 1.61%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                        | 1         | 1.61%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                          | 1         | 1.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                             | 1         | 1.61%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                          | 1         | 1.61%   |
| SK hynix RAM Module 2GB DDR3 1600MT/s                                    | 1         | 1.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s                    | 1         | 1.61%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                     | 1         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.61%   |
| SK hynix RAM HMCG66AEBSA095N 8GB SODIMM DDR5 4800MT/s                    | 1         | 1.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                   | 1         | 1.61%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 1.61%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s                   | 1         | 1.61%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s                     | 1         | 1.61%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                              | 1         | 1.61%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 1.61%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                                    | 1         | 1.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B5174BM0-YH9 4GB Chip DDR3 1333MT/s                      | 1         | 1.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B5173BH0-CK0 4GB DDR3 1333MT/s                           | 1         | 1.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s              | 1         | 1.61%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB Chip DDR4 2133MT/s                  | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.61%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s             | 1         | 1.61%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s                   | 1         | 1.61%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s                     | 1         | 1.61%   |
| Samsung RAM K3LKCKC0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.61%   |
| Samsung RAM B6B6B6B6B6B6B6B6B6B6B6B6B6B6B6B6B6B6 2GB SODIMM DDR2 800MT/s | 1         | 1.61%   |
| Samsung RAM 9C9C9C9C9C9C9C9C9C9C9C9C9C9C9C9C9C9C 2GB SODIMM DDR2 800MT/s | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 45.83%  |
| DDR4    | 11        | 22.92%  |
| LPDDR3  | 7         | 14.58%  |
| LPDDR4  | 3         | 6.25%   |
| DDR2    | 2         | 4.17%   |
| LPDDR5  | 1         | 2.08%   |
| DDR5    | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 67.31%  |
| Row Of Chips | 9         | 17.31%  |
| Chip         | 6         | 11.54%  |
| Unknown      | 2         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 19        | 35.85%  |
| 4096  | 19        | 35.85%  |
| 2048  | 8         | 15.09%  |
| 16384 | 5         | 9.43%   |
| 32768 | 2         | 3.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 16        | 30.77%  |
| 1867  | 7         | 13.46%  |
| 2667  | 5         | 9.62%   |
| 1333  | 5         | 9.62%   |
| 2400  | 4         | 7.69%   |
| 3200  | 3         | 5.77%   |
| 4267  | 2         | 3.85%   |
| 2133  | 2         | 3.85%   |
| 800   | 2         | 3.85%   |
| 667   | 2         | 3.85%   |
| 6400  | 1         | 1.92%   |
| 4800  | 1         | 1.92%   |
| 3733  | 1         | 1.92%   |
| 1067  | 1         | 1.92%   |

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
| Chicony Electronics                    | 13        | 36.11%  |
| Bison Electronics                      | 6         | 16.67%  |
| Microdia                               | 4         | 11.11%  |
| IMC Networks                           | 4         | 11.11%  |
| Suyin                                  | 2         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Z-Star Microelectronics                | 1         | 2.78%   |
| Realtek Semiconductor                  | 1         | 2.78%   |
| Luxvisions Innotech Limited            | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| Apple                                  | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 8         | 21.62%  |
| Microdia Integrated_Webcam_HD                                | 3         | 8.11%   |
| Bison Integrated Camera                                      | 3         | 8.11%   |
| IMC Networks Integrated Webcam                               | 2         | 5.41%   |
| Z-Star WebCam SC-03FFL11739P                                 | 1         | 2.7%    |
| Suyin Lenovo Integrated Webcam                               | 1         | 2.7%    |
| Suyin HP webcam [dv6-1190en]                                 | 1         | 2.7%    |
| Sunplus Laptop Integrated Webcam HD                          | 1         | 2.7%    |
| Sunplus HD WebCam                                            | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                                 | 1         | 2.7%    |
| Microdia Integrated Webcam HD                                | 1         | 2.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 2.7%    |
| IMC Networks SunplusIT Integrated Camera                     | 1         | 2.7%    |
| IMC Networks EasyCamera                                      | 1         | 2.7%    |
| Chicony USB2.0 VGA UVC WebCam                                | 1         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 2.7%    |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 2.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 2.7%    |
| Chicony Lenovo Integrated Camera                             | 1         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)                      | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 2.7%    |
| Bison SunplusIT Integrated Camera                            | 1         | 2.7%    |
| Bison Lenovo Integrated Webcam                               | 1         | 2.7%    |
| Bison Lenovo EasyCamera                                      | 1         | 2.7%    |
| Apple FaceTime HD Camera (Built-in)                          | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 12        | 75%     |
| Elan Microelectronics | 2         | 12.5%   |
| Upek                  | 1         | 6.25%   |
| Synaptics             | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 25%     |
| Validity Sensors Synaptics WBDI                        | 4         | 25%     |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 12.5%   |
| Elan Fingerprint Sensor                                | 2         | 12.5%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |

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
| 3     | 20        | 34.48%  |
| 1     | 19        | 32.76%  |
| 2     | 13        | 22.41%  |
| 0     | 3         | 5.17%   |
| 6     | 1         | 1.72%   |
| 5     | 1         | 1.72%   |
| 4     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 45        | 41.67%  |
| Bluetooth                | 18        | 16.67%  |
| Fingerprint reader       | 14        | 12.96%  |
| Card reader              | 11        | 10.19%  |
| Net/wireless             | 8         | 7.41%   |
| Net/ethernet             | 3         | 2.78%   |
| Graphics card            | 3         | 2.78%   |
| Firewire controller      | 3         | 2.78%   |
| Sound                    | 2         | 1.85%   |
| Network                  | 1         | 0.93%   |

