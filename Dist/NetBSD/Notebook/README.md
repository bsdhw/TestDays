NetBSD - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for NetBSD.

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

Total: 57

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HUAWEI        | KPL-W0X                     | [ac7b8b09f0](https://bsd-hardware.info/?probe=ac7b8b09f0) | Dec 24, 2024 |
| Lenovo        | ThinkPad A285 20MXS01R00    | [9c548c9ffb](https://bsd-hardware.info/?probe=9c548c9ffb) | Sep 01, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [f78f3487b8](https://bsd-hardware.info/?probe=f78f3487b8) | Aug 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [424a038d10](https://bsd-hardware.info/?probe=424a038d10) | Aug 16, 2024 |
| eMachines     | eM250                       | [98c37607a3](https://bsd-hardware.info/?probe=98c37607a3) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ffdc8ec717](https://bsd-hardware.info/?probe=ffdc8ec717) | Aug 15, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | [248dd70da2](https://bsd-hardware.info/?probe=248dd70da2) | Jul 25, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [3589bb8629](https://bsd-hardware.info/?probe=3589bb8629) | Jun 16, 2024 |
| Dell          | Precision 7520              | [48232bd1d6](https://bsd-hardware.info/?probe=48232bd1d6) | Jun 06, 2024 |
| MSI           | GE62 6QC                    | [d8fe2ac91a](https://bsd-hardware.info/?probe=d8fe2ac91a) | May 18, 2024 |
| Acer          | TravelMate B118-M           | [66fbf7ab6c](https://bsd-hardware.info/?probe=66fbf7ab6c) | May 12, 2024 |
| Apple         | MacBookPro8,1               | [23e113910f](https://bsd-hardware.info/?probe=23e113910f) | May 05, 2024 |
| Apple         | MacBookPro8,1               | [55560acf02](https://bsd-hardware.info/?probe=55560acf02) | May 05, 2024 |
| Timi          | TM1612                      | [c139dfdf05](https://bsd-hardware.info/?probe=c139dfdf05) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | [5fa2016fc1](https://bsd-hardware.info/?probe=5fa2016fc1) | Mar 11, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0dc4820d7e](https://bsd-hardware.info/?probe=0dc4820d7e) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [c3f8fdaebb](https://bsd-hardware.info/?probe=c3f8fdaebb) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [6c6fcc3427](https://bsd-hardware.info/?probe=6c6fcc3427) | Mar 04, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [b35f962bce](https://bsd-hardware.info/?probe=b35f962bce) | Mar 01, 2024 |
| Dell          | Precision 7520              | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2518A37       | [b2515cf7fb](https://bsd-hardware.info/?probe=b2515cf7fb) | Feb 19, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Samsung       | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Google        | Kohaku                      | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Dell          | Vostro 3500                 | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| Apple         | MacBookPro11,1              | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Apple         | MacBookAir7,2               | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| HP            | Pavilion 17                 | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Dell          | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| Lenovo        | ThinkPad T420 4236D26       | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | X555LJ                      | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| Toshiba       | Satellite A100              | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| Sony          | SVF1421DSGW                 | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Apple         | MacBook2,1                  | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310                 | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                     | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Lenovo        | G500 20236                  | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| NetBSD 10.0       | 9         | 20.45%  |
| NetBSD 9.3        | 7         | 15.91%  |
| NetBSD 9.2        | 5         | 11.36%  |
| NetBSD 9.1        | 4         | 9.09%   |
| NetBSD 9.0        | 3         | 6.82%   |
| NetBSD 10.0_RC5   | 2         | 4.55%   |
| NetBSD 10.0_RC4   | 2         | 4.55%   |
| NetBSD 10.0_RC3   | 2         | 4.55%   |
| NetBSD 9.99.94    | 1         | 2.27%   |
| NetBSD 9.2_STABLE | 1         | 2.27%   |
| NetBSD 9.0_STABLE | 1         | 2.27%   |
| NetBSD 8.99.51    | 1         | 2.27%   |
| NetBSD 7.2        | 1         | 2.27%   |
| NetBSD 10.99.10   | 1         | 2.27%   |
| NetBSD 10.99.1    | 1         | 2.27%   |
| NetBSD 10.1       | 1         | 2.27%   |
| NetBSD 10.0_RC2   | 1         | 2.27%   |
| NetBSD 10.0_BETA  | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 41        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 34        | 82.93%  |
| i386  | 7         | 17.07%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| XFCE         | 11        | 25.58%  |
| Console      | 10        | 23.26%  |
| ctwm         | 4         | 9.3%    |
| MATE         | 3         | 6.98%   |
| iwm          | 3         | 6.98%   |
| DWM          | 3         | 6.98%   |
| LXQt         | 2         | 4.65%   |
| Fluxbox      | 2         | 4.65%   |
| sdorfehs     | 1         | 2.33%   |
| Ratpoison    | 1         | 2.33%   |
| helloDesktop | 1         | 2.33%   |
| GNOME        | 1         | 2.33%   |
| Awesome      | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 36        | 87.8%   |
| Console | 5         | 12.2%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 32        | 78.05%  |
| SLiM    | 6         | 14.63%  |
| XDM     | 2         | 4.88%   |
| GDM     | 1         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 76.19%  |
| en_US   | 7         | 16.67%  |
| ru_RU   | 1         | 2.38%   |
| fr_FR   | 1         | 2.38%   |
| es_MX   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 40        | 97.56%  |
| EFI  | 1         | 2.44%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Ufs    | 39        | 95.12%  |
| Ffs    | 1         | 2.44%   |
| Cd9660 | 1         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 68.29%  |
| Unknown | 13        | 31.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 34.15%  |
| Apple               | 4         | 9.76%   |
| Dell                | 3         | 7.32%   |
| ASUSTek Computer    | 3         | 7.32%   |
| Samsung Electronics | 2         | 4.88%   |
| eMachines           | 2         | 4.88%   |
| Acer                | 2         | 4.88%   |
| Toshiba             | 1         | 2.44%   |
| Timi                | 1         | 2.44%   |
| Sony                | 1         | 2.44%   |
| MSI                 | 1         | 2.44%   |
| MiTAC               | 1         | 2.44%   |
| Intel               | 1         | 2.44%   |
| IBM                 | 1         | 2.44%   |
| HUAWEI              | 1         | 2.44%   |
| Hewlett-Packard     | 1         | 2.44%   |
| Google              | 1         | 2.44%   |
| Fujitsu Siemens     | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba Satellite A100                 | 1         | 2.44%   |
| Timi TM1612                            | 1         | 2.44%   |
| Sony SVF1421DSGW                       | 1         | 2.44%   |
| Samsung N150/N210/N220                 | 1         | 2.44%   |
| Samsung 530U3C/530U4C/532U3C           | 1         | 2.44%   |
| MSI GE62 6QC                           | 1         | 2.44%   |
| MiTAC 5033                             | 1         | 2.44%   |
| Lenovo ThinkPad X260 20F60097US        | 1         | 2.44%   |
| Lenovo ThinkPad X240 20AMS0J01N        | 1         | 2.44%   |
| Lenovo ThinkPad T510 4313CTO           | 1         | 2.44%   |
| Lenovo ThinkPad T490 20N3S4PX02        | 1         | 2.44%   |
| Lenovo ThinkPad T480s 20L8S45W00       | 1         | 2.44%   |
| Lenovo ThinkPad T470 W10DG 20JNS0L300  | 1         | 2.44%   |
| Lenovo ThinkPad T470 20HES0EV0A        | 1         | 2.44%   |
| Lenovo ThinkPad T460s 20FAS3L002       | 1         | 2.44%   |
| Lenovo ThinkPad T430s 23564H3          | 1         | 2.44%   |
| Lenovo ThinkPad T430 2347A45           | 1         | 2.44%   |
| Lenovo ThinkPad T420 4236D26           | 1         | 2.44%   |
| Lenovo ThinkPad T410 2518A37           | 1         | 2.44%   |
| Lenovo ThinkPad 13 20GJCTO1WW          | 1         | 2.44%   |
| Lenovo G500 20236                      | 1         | 2.44%   |
| Intel Jasper Lake Client Platform      | 1         | 2.44%   |
| IBM ThinkPad R51 2887AVG               | 1         | 2.44%   |
| HUAWEI KPL-W0X                         | 1         | 2.44%   |
| HP Pavilion 17                         | 1         | 2.44%   |
| Google Kohaku                          | 1         | 2.44%   |
| Fujitsu Siemens AMILO L7310            | 1         | 2.44%   |
| eMachines eME642G                      | 1         | 2.44%   |
| eMachines eM250                        | 1         | 2.44%   |
| Dell Vostro 3500                       | 1         | 2.44%   |
| Dell Precision M4500                   | 1         | 2.44%   |
| Dell Precision 7520                    | 1         | 2.44%   |
| ASUS X555LJ                            | 1         | 2.44%   |
| ASUS VivoBook_ASUSLaptop X512JA_X512JA | 1         | 2.44%   |
| ASUS A3L                               | 1         | 2.44%   |
| Apple MacBookPro8,1                    | 1         | 2.44%   |
| Apple MacBookPro11,1                   | 1         | 2.44%   |
| Apple MacBookAir7,2                    | 1         | 2.44%   |
| Apple MacBook2,1                       | 1         | 2.44%   |
| Acer Aspire ES1-132                    | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 13        | 31.71%  |
| Dell Precision        | 2         | 4.88%   |
| Acer Aspire           | 2         | 4.88%   |
| Toshiba Satellite     | 1         | 2.44%   |
| Timi TM1612           | 1         | 2.44%   |
| Sony SVF1421DSGW      | 1         | 2.44%   |
| Samsung N150          | 1         | 2.44%   |
| Samsung 530U3C        | 1         | 2.44%   |
| MSI GE62              | 1         | 2.44%   |
| MiTAC 5033            | 1         | 2.44%   |
| Lenovo G500           | 1         | 2.44%   |
| Intel Jasper          | 1         | 2.44%   |
| IBM ThinkPad          | 1         | 2.44%   |
| HUAWEI KPL-W0X        | 1         | 2.44%   |
| HP Pavilion           | 1         | 2.44%   |
| Google Kohaku         | 1         | 2.44%   |
| Fujitsu Siemens AMILO | 1         | 2.44%   |
| eMachines eME642G     | 1         | 2.44%   |
| eMachines eM250       | 1         | 2.44%   |
| Dell Vostro           | 1         | 2.44%   |
| ASUS X555LJ           | 1         | 2.44%   |
| ASUS VivoBook         | 1         | 2.44%   |
| ASUS A3L              | 1         | 2.44%   |
| Apple MacBookPro8     | 1         | 2.44%   |
| Apple MacBookPro11    | 1         | 2.44%   |
| Apple MacBookAir7     | 1         | 2.44%   |
| Apple MacBook2        | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 5         | 12.2%   |
| 2013    | 5         | 12.2%   |
| 2010    | 4         | 9.76%   |
| 2022    | 3         | 7.32%   |
| 2021    | 3         | 7.32%   |
| 2018    | 3         | 7.32%   |
| 2005    | 3         | 7.32%   |
| 2020    | 2         | 4.88%   |
| 2019    | 2         | 4.88%   |
| 2017    | 2         | 4.88%   |
| 2011    | 2         | 4.88%   |
| 2007    | 2         | 4.88%   |
| 2023    | 1         | 2.44%   |
| 2014    | 1         | 2.44%   |
| 2012    | 1         | 2.44%   |
| 2009    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 95.12%  |
| Yes  | 2         | 4.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 38.1%   |
| 3.01-4.0    | 7         | 16.67%  |
| 8.01-16.0   | 6         | 14.29%  |
| 16.01-24.0  | 5         | 11.9%   |
| 0.51-1.0    | 3         | 7.14%   |
| 1.01-2.0    | 2         | 4.76%   |
| 64.01-256.0 | 1         | 2.38%   |
| 0.01-0.5    | 1         | 2.38%   |
| 0           | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 41        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 0      | 23        | 54.76%  |
| 1      | 18        | 42.86%  |
| 4      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 92.68%  |
| Yes       | 3         | 7.32%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 85.37%  |
| No        | 6         | 14.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 95.12%  |
| No        | 2         | 4.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 68.29%  |
| No        | 13        | 31.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 7         | 17.07%  |
| France       | 6         | 14.63%  |
| Russia       | 4         | 9.76%   |
| Italy        | 4         | 9.76%   |
| Germany      | 3         | 7.32%   |
| Vietnam      | 2         | 4.88%   |
| Saudi Arabia | 2         | 4.88%   |
| India        | 2         | 4.88%   |
| Hungary      | 2         | 4.88%   |
| Canada       | 2         | 4.88%   |
| Taiwan       | 1         | 2.44%   |
| Spain        | 1         | 2.44%   |
| Mexico       | 1         | 2.44%   |
| Finland      | 1         | 2.44%   |
| Denmark      | 1         | 2.44%   |
| China        | 1         | 2.44%   |
| Brazil       | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 4         | 9.3%    |
| Noyon            | 3         | 6.98%   |
| Riyadh           | 2         | 4.65%   |
| Moscow           | 2         | 4.65%   |
| Ho Chi Minh City | 2         | 4.65%   |
| Gardony          | 2         | 4.65%   |
| Washington       | 1         | 2.33%   |
| Turenki          | 1         | 2.33%   |
| Taipei           | 1         | 2.33%   |
| Surrey           | 1         | 2.33%   |
| Sun Prairie      | 1         | 2.33%   |
| Rio Blanco       | 1         | 2.33%   |
| Ozersk           | 1         | 2.33%   |
| Ottawa           | 1         | 2.33%   |
| Novosibirsk      | 1         | 2.33%   |
| New York         | 1         | 2.33%   |
| Ladbergen        | 1         | 2.33%   |
| Kalispell        | 1         | 2.33%   |
| Genzano di Roma  | 1         | 2.33%   |
| Frederiksberg    | 1         | 2.33%   |
| Fort Myers       | 1         | 2.33%   |
| Draguignan       | 1         | 2.33%   |
| Deggendorf       | 1         | 2.33%   |
| Córdoba         | 1         | 2.33%   |
| Chennai          | 1         | 2.33%   |
| Chengdu          | 1         | 2.33%   |
| Chandler         | 1         | 2.33%   |
| Carry-le-Rouet   | 1         | 2.33%   |
| Bridgton         | 1         | 2.33%   |
| Berlin           | 1         | 2.33%   |
| Belo Horizonte   | 1         | 2.33%   |
| Amiens           | 1         | 2.33%   |
| Ahmedabad        | 1         | 2.33%   |
| A Coruña        | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 3         | 3      | 15%     |
| Kingston                           | 3         | 3      | 15%     |
| Intel                              | 3         | 3      | 15%     |
| Hitachi                            | 3         | 4      | 15%     |
| SanDisk                            | 2         | 2      | 10%     |
| HGST                               | 2         | 2      | 10%     |
| WDC                                | 1         | 1      | 5%      |
| Samsung Electronics                | 1         | 1      | 5%      |
| Product:              USB DISK 2.0 | 1         | 1      | 5%      |
| Generic                            | 1         | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| WDC WD1600BEVT-00A23T0 160GB                         | 1         | 5%      |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 1         | 5%      |
| Seagate ST500VT000-1DK142 500GB                      | 1         | 5%      |
| Seagate ST500LT012-9WS142 500GB                      | 1         | 5%      |
| SanDisk Ultra USB 3.0 64GB                           | 1         | 5%      |
| SanDisk SSD i100 24GB                                | 1         | 5%      |
| Samsung HM080HC 80GB                                 | 1         | 5%      |
| Product:              USB DISK 2.0 USB DISK 2.0 16GB | 1         | 5%      |
| Kingston SUV400S37240G 240GB                         | 1         | 5%      |
| Kingston SA400S37240G 240GB                          | 1         | 5%      |
| Kingston SA400S37120G 120GB                          | 1         | 5%      |
| Intel SSDSC2KW120H6 120GB                            | 1         | 5%      |
| Intel SSDSC2CW120A3 120GB                            | 1         | 5%      |
| Intel SSDSC2BF180A4L 180GB                           | 1         | 5%      |
| Hitachi HTS721060G9AT00 64GB                         | 1         | 5%      |
| Hitachi HTS548040M9AT00 37GB                         | 1         | 5%      |
| Hitachi HTS545025B9A300 250GB                        | 1         | 5%      |
| HGST HTS545050A7E680 500GB                           | 1         | 5%      |
| HGST HTS541010A9E680 1TB                             | 1         | 5%      |
| Generic STORAGE DEVICE 2GB                           | 1         | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 3         | 3      | 25%     |
| Hitachi                            | 3         | 4      | 25%     |
| HGST                               | 2         | 2      | 16.67%  |
| WDC                                | 1         | 1      | 8.33%   |
| Samsung Electronics                | 1         | 1      | 8.33%   |
| Product:              USB DISK 2.0 | 1         | 1      | 8.33%   |
| Generic                            | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Kingston | 3         | 3      | 37.5%   |
| Intel    | 3         | 3      | 37.5%   |
| SanDisk  | 2         | 2      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 61.11%  |
| SSD  | 7         | 8      | 38.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 21     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 19     | 88.24%  |
| 0.51-1.0   | 2         | 2      | 11.76%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 47.62%  |
| 251-500    | 8         | 19.05%  |
| 501-1000   | 5         | 11.9%   |
| 21-50      | 3         | 7.14%   |
| 51-100     | 3         | 7.14%   |
| 1-20       | 2         | 4.76%   |
| 1001-2000  | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 31        | 72.09%  |
| 21-50    | 8         | 18.6%   |
| 51-100   | 2         | 4.65%   |
| 101-250  | 1         | 2.33%   |
| 501-1000 | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 12.5%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 12.5%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 12.5%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 12.5%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 12.5%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 12.5%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Intel   | 3         | 3      | 37.5%   |
| Hitachi | 2         | 3      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| Hitachi | 2         | 3      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

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
| Malfunc  | 8         | 9      | 44.44%  |
| Works    | 8         | 9      | 44.44%  |
| Detected | 2         | 3      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 35        | 72.92%  |
| Samsung Electronics            | 5         | 10.42%  |
| AMD                            | 4         | 8.33%   |
| VIA Technologies               | 1         | 2.08%   |
| Solid State Storage Technology | 1         | 2.08%   |
| Micron/Crucial Technology      | 1         | 2.08%   |
| Kingston Technology Company    | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 11.54%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 5         | 9.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 3         | 5.77%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 5.77%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 2         | 3.85%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 2         | 3.85%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 2         | 3.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 2         | 3.85%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                        | 2         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 3.85%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 1.92%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 1.92%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                            | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.92%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 1.92%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.92%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]            | 1         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 1         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 1.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1         | 1.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 1.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 1.92%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 1.92%   |
| AMD FCH IDE Controller                                                        | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 69.23%  |
| NVMe | 8         | 15.38%  |
| IDE  | 7         | 13.46%  |
| RAID | 1         | 1.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 36        | 87.8%   |
| AMD          | 4         | 9.76%   |
| 123456789ABC | 1         | 2.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 686-class                               | 5         | 11.63%  |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 4.65%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 4.65%   |
| Intel Pentium M processor 1.60GHz             | 1         | 2.33%   |
| Intel Pentium M processor                     | 1         | 2.33%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.33%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 2.33%   |
| Intel Core i7-7920HQ CPU @ 3.10GHz            | 1         | 2.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 2.33%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.33%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 2.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.33%   |
| Intel Core i5 CPU M 560 @ 2.67GH              | 1         | 2.33%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 2.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 2.33%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 1         | 2.33%   |
| Intel Core 2 CPU T7                           | 1         | 2.33%   |
| Intel Celeron N5100 @ 1.10GHz                 | 1         | 2.33%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 2.33%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.33%   |
| AMD Tillamook                                 | 1         | 2.33%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD Athlon II P340 Dual-Core Processor        | 1         | 2.33%   |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 2.33%   |
| 123456789ABC Pentium 4                        | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 14        | 33.33%  |
| Intel Core i7   | 6         | 14.29%  |
| Intel 686-class | 5         | 11.9%   |
| Other           | 3         | 7.14%   |
| Intel Pentium M | 2         | 4.76%   |
| Intel Core i3   | 2         | 4.76%   |
| Intel Core 2    | 2         | 4.76%   |
| Intel Atom      | 2         | 4.76%   |
| Intel Pentium   | 1         | 2.38%   |
| Intel Core m3   | 1         | 2.38%   |
| Intel Celeron   | 1         | 2.38%   |
| AMD Ryzen 5     | 1         | 2.38%   |
| AMD Athlon II   | 1         | 2.38%   |
| AMD A10         | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 46.51%  |
| Unknown | 13        | 30.23%  |
| 4       | 10        | 23.26%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 36        | 85.71%  |
| Unknown | 6         | 14.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 24        | 57.14%  |
| Unknown | 13        | 30.95%  |
| 1       | 5         | 11.9%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 10        | 23.26%  |
| Skylake     | 6         | 13.95%  |
| KabyLake    | 5         | 11.63%  |
| IvyBridge   | 5         | 11.63%  |
| SandyBridge | 2         | 4.65%   |
| P6          | 2         | 4.65%   |
| Core        | 2         | 4.65%   |
| Broadwell   | 2         | 4.65%   |
| Zen         | 1         | 2.33%   |
| Westmere    | 1         | 2.33%   |
| TigerLake   | 1         | 2.33%   |
| Piledriver  | 1         | 2.33%   |
| K10         | 1         | 2.33%   |
| IceLake     | 1         | 2.33%   |
| Haswell     | 1         | 2.33%   |
| Geode       | 1         | 2.33%   |
| Bonnell     | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 34        | 73.91%  |
| Nvidia               | 6         | 13.04%  |
| AMD                  | 4         | 8.7%    |
| VIA Technologies     | 1         | 2.17%   |
| Trident Microsystems | 1         | 2.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 10%     |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 8%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 6%      |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 4%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 4%      |
| Intel JasperLake [UHD Graphics]                                               | 2         | 4%      |
| Intel HD Graphics 6000                                                        | 2         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 4%      |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 4%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 4%      |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 2%      |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 2%      |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 2%      |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 2%      |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 2%      |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 2%      |
| Intel UHD Graphics 620                                                        | 1         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 2%      |
| Intel HD Graphics 630                                                         | 1         | 2%      |
| Intel HD Graphics 620                                                         | 1         | 2%      |
| Intel HD Graphics 5500                                                        | 1         | 2%      |
| Intel HD Graphics 530                                                         | 1         | 2%      |
| Intel HD Graphics 515                                                         | 1         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 2%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2%      |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 2%      |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 2%      |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 26        | 61.9%   |
| 2 x Intel                | 4         | 9.52%   |
| 1 x Nvidia               | 4         | 9.52%   |
| Intel + Nvidia           | 3         | 7.14%   |
| 1 x AMD                  | 3         | 7.14%   |
| 1 x VIA                  | 1         | 2.38%   |
| 1 x Trident Microsystems | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 35        | 83.33%  |
| Unknown | 7         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 50%     |
| 1.01-2.0   | 8         | 19.05%  |
| 0.01-0.5   | 7         | 16.67%  |
| 3.01-4.0   | 4         | 9.52%   |
| 0.51-1.0   | 2         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 22.73%  |
| Chimei Innolux          | 4         | 18.18%  |
| Samsung Electronics     | 3         | 13.64%  |
| Lenovo                  | 2         | 9.09%   |
| BOE                     | 2         | 9.09%   |
| Apple                   | 2         | 9.09%   |
| LG Philips              | 1         | 4.55%   |
| InfoVision              | 1         | 4.55%   |
| Dell                    | 1         | 4.55%   |
| Chi Mei Optoelectronics | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC554E 1024x600 220x130mm 10.1-inch    | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch    | 1         | 4.55%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 4.55%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch            | 1         | 4.55%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch             | 1         | 4.55%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                 | 1         | 4.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                 | 1         | 4.55%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch            | 1         | 4.55%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                       | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 340x190mm 15.3-inch        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 340x190mm 15.3-inch        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch         | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch         | 1         | 4.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch | 1         | 4.55%   |
| BOE LCD Monitor BOE0827 1366x768 310x170mm 13.9-inch                    | 1         | 4.55%   |
| BOE LCD Monitor BOE074F 1920x1080 310x170mm 13.9-inch                   | 1         | 4.55%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                  | 1         | 4.55%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                  | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 31.82%  |
| 1920x1080 (FHD)  | 6         | 27.27%  |
| 1600x900 (HD+)   | 3         | 13.64%  |
| 1280x800 (WXGA)  | 3         | 13.64%  |
| 1024x600         | 2         | 9.09%   |
| 1440x900 (WXGA+) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 10        | 45.45%  |
| 15     | 7         | 31.82%  |
| 24     | 1         | 4.55%   |
| 14     | 1         | 4.55%   |
| 12     | 1         | 4.55%   |
| 10     | 1         | 4.55%   |
| 9      | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 68.18%  |
| 201-300     | 6         | 27.27%  |
| 501-600     | 1         | 4.55%   |

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
| 81-90          | 11        | 50%     |
| 91-100         | 4         | 18.18%  |
| 101-110        | 3         | 13.64%  |
| 41-50          | 2         | 9.09%   |
| 61-70          | 1         | 4.55%   |
| 201-250        | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 45.45%  |
| 121-160 | 9         | 40.91%  |
| 51-100  | 3         | 13.64%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 73.81%  |
| 0     | 11        | 26.19%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 28        | 41.18%  |
| Realtek Semiconductor             | 14        | 20.59%  |
| Qualcomm Atheros                  | 9         | 13.24%  |
| Broadcom                          | 7         | 10.29%  |
| Marvell Technology Group          | 2         | 2.94%   |
| VIA Technologies                  | 1         | 1.47%   |
| TP-Link                           | 1         | 1.47%   |
| Qualcomm Atheros Communications   | 1         | 1.47%   |
| Huawei Technologies               | 1         | 1.47%   |
| Ericsson Business Mobile Networks | 1         | 1.47%   |
| Dell                              | 1         | 1.47%   |
| D-Link                            | 1         | 1.47%   |
| Apple                             | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 9         | 10%     |
| Intel Wireless 8260                                                                   | 5         | 5.56%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.44%   |
| Intel Ethernet Connection I219-LM                                                     | 3         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 3.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 3         | 3.33%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.22%   |
| Intel Wireless 7265                                                                   | 2         | 2.22%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 2         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                                              | 2         | 2.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.11%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 1.11%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.11%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.11%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                             | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.11%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 1.11%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.11%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 1.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 1.11%   |
| Intel Wireless 7260                                                                   | 1         | 1.11%   |
| Intel Wireless 3165                                                                   | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.11%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.11%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 54.35%  |
| Realtek Semiconductor           | 6         | 13.04%  |
| Qualcomm Atheros                | 6         | 13.04%  |
| Broadcom                        | 6         | 13.04%  |
| TP-Link                         | 1         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 2.17%   |
| D-Link                          | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                                   | 5         | 10.64%  |
| Intel Wireless 8265 / 8275                                                            | 4         | 8.51%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 3         | 6.38%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.26%   |
| Intel Wireless 7265                                                                   | 2         | 4.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.13%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 2.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.13%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.13%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.13%   |
| Intel Wireless 7260                                                                   | 1         | 2.13%   |
| Intel Wireless 3165                                                                   | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 2.13%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 1         | 2.13%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 16        | 42.11%  |
| Realtek Semiconductor    | 11        | 28.95%  |
| Qualcomm Atheros         | 3         | 7.89%   |
| Broadcom                 | 3         | 7.89%   |
| Marvell Technology Group | 2         | 5.26%   |
| VIA Technologies         | 1         | 2.63%   |
| Huawei Technologies      | 1         | 2.63%   |
| Apple                    | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 9         | 23.68%  |
| Intel Ethernet Connection I219-LM                                      | 3         | 7.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 7.89%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 5.26%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 5.26%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 2.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 2.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 2.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 2.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 2.63%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 2.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 2.63%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 2.63%   |
| Intel Ethernet Connection I219-V                                       | 1         | 2.63%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.63%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2.63%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.63%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 2.63%   |
| Huawei USB Device                                                      | 1         | 2.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 2.63%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 2.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.63%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 48.15%  |
| Ethernet | 37        | 45.68%  |
| Unknown  | 3         | 3.7%    |
| Modem    | 2         | 2.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 48%     |
| Ethernet | 24        | 48%     |
| Unknown  | 2         | 4%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 80.49%  |
| 1     | 6         | 14.63%  |
| 0     | 2         | 4.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 73.81%  |
| Yes  | 11        | 26.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 20        | 64.52%  |
| Apple                   | 5         | 16.13%  |
| Broadcom                | 3         | 9.68%   |
| Realtek Semiconductor   | 1         | 3.23%   |
| IMC Networks            | 1         | 3.23%   |
| Cambridge Silicon Radio | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 38.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 12.9%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 6.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.45%   |
| Apple Broadcom Built-in Bluetooth                   | 2         | 6.45%   |
| Apple Bluetooth Host Controller                     | 2         | 6.45%   |
| Realtek Bluetooth Adapter                           | 1         | 3.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.23%   |
| Intel AX201 Bluetooth                               | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.23%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 37        | 80.43%  |
| Nvidia           | 4         | 8.7%    |
| AMD              | 4         | 8.7%    |
| VIA Technologies | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 12.5%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 8.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 7.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 5.36%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 5.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 5.36%   |
| Nvidia High Definition Audio Controller                                    | 2         | 3.57%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.57%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.57%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 2         | 3.57%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 1.79%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.79%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.79%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.79%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 28.26%  |
| SK hynix            | 8         | 17.39%  |
| Unknown             | 5         | 10.87%  |
| Micron Technology   | 4         | 8.7%    |
| Ramaxel Technology  | 3         | 6.52%   |
| Kingston            | 3         | 6.52%   |
| Unknown             | 2         | 4.35%   |
| SHARETRONIC         | 1         | 2.17%   |
| Patriot             | 1         | 2.17%   |
| Nanya Technology    | 1         | 2.17%   |
| G.Skill             | 1         | 2.17%   |
| Elpida              | 1         | 2.17%   |
| Crucial             | 1         | 2.17%   |
| A-DATA Technology   | 1         | 2.17%   |
| 48spaces            | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 2         | 4%      |
| Unknown                                                     | 2         | 4%      |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s                | 1         | 2%      |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                | 1         | 2%      |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 2%      |
| Unknown RAM Module 256MB SODIMM DDR                         | 1         | 2%      |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s              | 1         | 2%      |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s               | 1         | 2%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 2%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 2%      |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 2%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 2%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 2%      |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1         | 2%      |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s         | 1         | 2%      |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s               | 1         | 2%      |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                 | 1         | 2%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 2%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 2%      |
| Samsung RAM M471A5644EB0-CRC 2GB SODIMM DDR4 2400MT/s       | 1         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 1         | 2%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 1         | 2%      |
| Samsung RAM M471A5244BB0-CRC 4GB Row Of Chips DDR4 2400MT/s | 1         | 2%      |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 2%      |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 2%      |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s      | 1         | 2%      |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 1         | 2%      |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s     | 1         | 2%      |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s    | 1         | 2%      |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s    | 1         | 2%      |
| Patriot RAM PSD34G13332S 4GB SODIMM DDR3 1334MT/s           | 1         | 2%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 2%      |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s       | 1         | 2%      |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 1         | 2%      |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s      | 1         | 2%      |
| Kingston RAM Module 2GB SODIMM DDR2 533MT/s                 | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 15        | 41.67%  |
| DDR4   | 13        | 36.11%  |
| DDR2   | 3         | 8.33%   |
| LPDDR3 | 2         | 5.56%   |
| SDRAM  | 1         | 2.78%   |
| DRAM   | 1         | 2.78%   |
| DDR    | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 91.43%  |
| Row Of Chips | 2         | 5.71%   |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 11        | 27.5%   |
| 2048  | 11        | 27.5%   |
| 8192  | 9         | 22.5%   |
| 16384 | 5         | 12.5%   |
| 512   | 2         | 5%      |
| 1024  | 1         | 2.5%    |
| 256   | 1         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 7         | 17.07%  |
| 2667    | 5         | 12.2%   |
| 2400    | 5         | 12.2%   |
| 2133    | 4         | 9.76%   |
| 1867    | 3         | 7.32%   |
| 1334    | 3         | 7.32%   |
| 3200    | 2         | 4.88%   |
| 1333    | 2         | 4.88%   |
| 1067    | 2         | 4.88%   |
| 533     | 2         | 4.88%   |
| Unknown | 2         | 4.88%   |
| 1066    | 1         | 2.44%   |
| 800     | 1         | 2.44%   |
| 266     | 1         | 2.44%   |
| 166     | 1         | 2.44%   |

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
| Chicony Electronics           | 9         | 33.33%  |
| Realtek Semiconductor         | 3         | 11.11%  |
| Lenovo                        | 2         | 7.41%   |
| IMC Networks                  | 2         | 7.41%   |
| Bison Electronics             | 2         | 7.41%   |
| Z-Star Microelectronics       | 1         | 3.7%    |
| Syntek                        | 1         | 3.7%    |
| Sunplus Innovation Technology | 1         | 3.7%    |
| Silicon Motion                | 1         | 3.7%    |
| Quanta                        | 1         | 3.7%    |
| Microdia                      | 1         | 3.7%    |
| Lite-On Technology            | 1         | 3.7%    |
| Apple                         | 1         | 3.7%    |
| ALi                           | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 4         | 14.29%  |
| Lenovo Integrated Webcam [R5U877]        | 2         | 7.14%   |
| Z-Star Webcam                            | 1         | 3.57%   |
| Syntek Lenovo EasyCamera                 | 1         | 3.57%   |
| Sunplus Integrated Camera                | 1         | 3.57%   |
| Silicon Motion Realtek USB 2.0 PC Camera | 1         | 3.57%   |
| Realtek USB Camera                       | 1         | 3.57%   |
| Realtek USB 2.0 PC Camera                | 1         | 3.57%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 3.57%   |
| Quanta VGA WebCam                        | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD            | 1         | 3.57%   |
| Lite-On Integrated Camera                | 1         | 3.57%   |
| IMC Networks Realtek PC Camera           | 1         | 3.57%   |
| IMC Networks EasyCamera                  | 1         | 3.57%   |
| Chicony XiaoMi USB 2.0 Webcam            | 1         | 3.57%   |
| Chicony Thinkpad T430 camera             | 1         | 3.57%   |
| Chicony Integrated Camera (1280x720@30)  | 1         | 3.57%   |
| Chicony Front Camera                     | 1         | 3.57%   |
| Chicony 8M Camera                        | 1         | 3.57%   |
| Chicony 720p HD Camera                   | 1         | 3.57%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 3.57%   |
| Bison Integrated Camera                  | 1         | 3.57%   |
| Apple FaceTime HD Camera                 | 1         | 3.57%   |
| ALi Gateway Webcam                       | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Upek             | 1         | 20%     |
| Synaptics        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |

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
| 2     | 17        | 39.53%  |
| 1     | 14        | 32.56%  |
| 3     | 4         | 9.3%    |
| 0     | 4         | 9.3%    |
| 5     | 2         | 4.65%   |
| 4     | 2         | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 32        | 50%     |
| Net/wireless             | 15        | 23.44%  |
| Card reader              | 7         | 10.94%  |
| Graphics card            | 6         | 9.38%   |
| Storage                  | 1         | 1.56%   |
| Sound                    | 1         | 1.56%   |
| Modem                    | 1         | 1.56%   |
| Bluetooth                | 1         | 1.56%   |

