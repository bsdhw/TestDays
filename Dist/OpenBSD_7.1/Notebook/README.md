OpenBSD 7.1 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

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

Total: 45

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 2530p             | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Toshiba       | Satellite BE96-F299         | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Alienware     | m15 R4                      | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| Dell          | XPS 13 9360                 | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Nitro AN515-55              | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Dell          | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 37        | 90.24%  |
| i386  | 4         | 9.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 78.05%  |
| fvwm         | 5         | 12.2%   |
| XFCE         | 3         | 7.32%   |
| MATE         | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 37        | 90.24%  |
| Console | 4         | 9.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 41        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 83.33%  |
| ru_RU   | 3         | 7.14%   |
| fr_FR   | 2         | 4.76%   |
| pl_PL   | 1         | 2.38%   |
| en_GB   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 63.41%  |
| BIOS | 15        | 36.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 41        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 23        | 56.1%   |
| MBR  | 18        | 43.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 18        | 43.9%   |
| Dell                           | 3         | 7.32%   |
| ASUSTek Computer               | 3         | 7.32%   |
| TUXEDO                         | 2         | 4.88%   |
| Panasonic                      | 2         | 4.88%   |
| Matsushita Electric Industrial | 2         | 4.88%   |
| Hewlett-Packard                | 2         | 4.88%   |
| Acer                           | 2         | 4.88%   |
| Toshiba                        | 1         | 2.44%   |
| Tactus                         | 1         | 2.44%   |
| MSI                            | 1         | 2.44%   |
| Fujitsu                        | 1         | 2.44%   |
| DEXP                           | 1         | 2.44%   |
| Apple                          | 1         | 2.44%   |
| Alienware                      | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 3         | 7.32%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 2.44%   |
| TUXEDO Aura 15 Gen1                         | 1         | 2.44%   |
| Toshiba Satellite BE96-F299                 | 1         | 2.44%   |
| Tactus GeoFlex 110                          | 1         | 2.44%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.44%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.44%   |
| MSI Modern 14 B11MOL                        | 1         | 2.44%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.44%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.44%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 2.44%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 2.44%   |
| Lenovo ThinkPad X270 W10DG 20K5S5MD0F       | 1         | 2.44%   |
| Lenovo ThinkPad X260 20F5S10W0H             | 1         | 2.44%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 2.44%   |
| Lenovo ThinkPad X220 429043U                | 1         | 2.44%   |
| Lenovo ThinkPad X200 7458NP9                | 1         | 2.44%   |
| Lenovo ThinkPad X121e 3053A52               | 1         | 2.44%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2.44%   |
| Lenovo ThinkPad T420s 4174DL7               | 1         | 2.44%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2.44%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 2.44%   |
| Lenovo ThinkPad L530 24812TG                | 1         | 2.44%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 2.44%   |
| Lenovo IdeaPad S12 20021,2959               | 1         | 2.44%   |
| HP Pavilion Laptop 15-cs0xxx                | 1         | 2.44%   |
| HP EliteBook 2530p                          | 1         | 2.44%   |
| Fujitsu LIFEBOOK E752                       | 1         | 2.44%   |
| DEXP NAVIS P100                             | 1         | 2.44%   |
| Dell XPS 13 9360                            | 1         | 2.44%   |
| Dell Vostro 3550                            | 1         | 2.44%   |
| Dell Inspiron 5515                          | 1         | 2.44%   |
| ASUS X751LB                                 | 1         | 2.44%   |
| ASUS K53TA                                  | 1         | 2.44%   |
| ASUS 1000HE                                 | 1         | 2.44%   |
| Apple MacBookPro5,3                         | 1         | 2.44%   |
| Alienware m15 R4                            | 1         | 2.44%   |
| Acer Nitro AN515-55                         | 1         | 2.44%   |
| Acer Aspire A114-33                         | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 16        | 39.02%  |
| TUXEDO Pulse                                | 1         | 2.44%   |
| TUXEDO Aura                                 | 1         | 2.44%   |
| Toshiba Satellite                           | 1         | 2.44%   |
| Tactus GeoFlex                              | 1         | 2.44%   |
| Panasonic CF-53AAGHYDM                      | 1         | 2.44%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 2.44%   |
| MSI Modern                                  | 1         | 2.44%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2.44%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2.44%   |
| Lenovo Yoga                                 | 1         | 2.44%   |
| Lenovo IdeaPad                              | 1         | 2.44%   |
| HP Pavilion                                 | 1         | 2.44%   |
| HP EliteBook                                | 1         | 2.44%   |
| Fujitsu LIFEBOOK                            | 1         | 2.44%   |
| DEXP NAVIS                                  | 1         | 2.44%   |
| Dell XPS                                    | 1         | 2.44%   |
| Dell Vostro                                 | 1         | 2.44%   |
| Dell Inspiron                               | 1         | 2.44%   |
| ASUS X751LB                                 | 1         | 2.44%   |
| ASUS K53TA                                  | 1         | 2.44%   |
| ASUS 1000HE                                 | 1         | 2.44%   |
| Apple MacBookPro5                           | 1         | 2.44%   |
| Alienware m15                               | 1         | 2.44%   |
| Acer Nitro                                  | 1         | 2.44%   |
| Acer Aspire                                 | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 7         | 17.07%  |
| 2021    | 6         | 14.63%  |
| 2011    | 6         | 14.63%  |
| 2018    | 4         | 9.76%   |
| 2012    | 4         | 9.76%   |
| 2010    | 3         | 7.32%   |
| 2020    | 2         | 4.88%   |
| 2019    | 2         | 4.88%   |
| 2022    | 1         | 2.44%   |
| 2016    | 1         | 2.44%   |
| 2015    | 1         | 2.44%   |
| 2013    | 1         | 2.44%   |
| 2006    | 1         | 2.44%   |
| 2002    | 1         | 2.44%   |
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
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 13        | 31.71%  |
| 4.01-8.0   | 12        | 29.27%  |
| 3.01-4.0   | 6         | 14.63%  |
| 2.01-3.0   | 4         | 9.76%   |
| 16.01-24.0 | 3         | 7.32%   |
| 32.01-64.0 | 2         | 4.88%   |
| 0.51-1.0   | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 37        | 90.24%  |
| 0.51-1.0 | 2         | 4.88%   |
| 0        | 2         | 4.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 48.78%  |
| 2      | 17        | 41.46%  |
| 3      | 3         | 7.32%   |
| 0      | 1         | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 82.93%  |
| No        | 7         | 17.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 97.56%  |
| No        | 1         | 2.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 73.17%  |
| No        | 11        | 26.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Canada      | 10        | 23.81%  |
| Russia      | 5         | 11.9%   |
| Poland      | 4         | 9.52%   |
| France      | 4         | 9.52%   |
| USA         | 3         | 7.14%   |
| UK          | 3         | 7.14%   |
| Spain       | 2         | 4.76%   |
| Netherlands | 2         | 4.76%   |
| Germany     | 2         | 4.76%   |
| Slovakia    | 1         | 2.38%   |
| Philippines | 1         | 2.38%   |
| Montserrat  | 1         | 2.38%   |
| Italy       | 1         | 2.38%   |
| India       | 1         | 2.38%   |
| Egypt       | 1         | 2.38%   |
| Chile       | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 23.81%  |
| Vladivostok         | 2         | 4.76%   |
| Gdansk              | 2         | 4.76%   |
| Amsterdam           | 2         | 4.76%   |
| West Valley City    | 1         | 2.38%   |
| Valdivia            | 1         | 2.38%   |
| Tanta               | 1         | 2.38%   |
| Sutton              | 1         | 2.38%   |
| Starogard Gdański  | 1         | 2.38%   |
| St Petersburg       | 1         | 2.38%   |
| Springboro          | 1         | 2.38%   |
| Quezon City         | 1         | 2.38%   |
| Plymouth            | 1         | 2.38%   |
| Ozersk              | 1         | 2.38%   |
| Newcastle upon Tyne | 1         | 2.38%   |
| Mumbai              | 1         | 2.38%   |
| Memphis             | 1         | 2.38%   |
| Madrid              | 1         | 2.38%   |
| Mâcon              | 1         | 2.38%   |
| Lublin              | 1         | 2.38%   |
| Lübeck             | 1         | 2.38%   |
| Laiz                | 1         | 2.38%   |
| Ermont              | 1         | 2.38%   |
| Edinburgh           | 1         | 2.38%   |
| Concesio            | 1         | 2.38%   |
| Chelyabinsk         | 1         | 2.38%   |
| Bratislava          | 1         | 2.38%   |
| Biot                | 1         | 2.38%   |
| Alcorisa            | 1         | 2.38%   |
| Aidlingen           | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 9         | 10     | 20.93%  |
| WDC                 | 7         | 7      | 16.28%  |
| Samsung Electronics | 6         | 6      | 13.95%  |
| Seagate             | 3         | 3      | 6.98%   |
| Toshiba             | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| Kingston            | 2         | 2      | 4.65%   |
| Innostor            | 2         | 2      | 4.65%   |
| Hitachi             | 2         | 3      | 4.65%   |
| HGST                | 2         | 2      | 4.65%   |
| Apacer              | 2         | 2      | 4.65%   |
| USB                 | 1         | 1      | 2.33%   |
| OWC                 | 1         | 1      | 2.33%   |
| LDLC F6+            | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung HM321HI 320GB            | 3         | 6.98%   |
| NVMe WDC PC SN530 SDB 256GB      | 2         | 4.65%   |
| NVMe Samsung SSD 980 500GB       | 2         | 4.65%   |
| Innostor SSD 15GB                | 2         | 4.65%   |
| Apacer AS340 240GB               | 2         | 4.65%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 2.33%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1         | 2.33%   |
| WDC WD7500BPKT-00PK4T0 752GB     | 1         | 2.33%   |
| WDC WD5000LPLX-00ZNTT0 500GB     | 1         | 2.33%   |
| WDC WD3200BEVE-00A0HT0 320GB     | 1         | 2.33%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 2.33%   |
| WDC WD10JPLX-00MBPT0 1TB         | 1         | 2.33%   |
| USB SanDisk 3.2Gen1 16GB         | 1         | 2.33%   |
| Toshiba MK6475GSX 640GB          | 1         | 2.33%   |
| Toshiba MK1629GSGF 160GB         | 1         | 2.33%   |
| Seagate ST9500420AS 500GB        | 1         | 2.33%   |
| Seagate ST9160821A 160GB         | 1         | 2.33%   |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 2.33%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 2.33%   |
| SanDisk Extreme 55AE 500GB       | 1         | 2.33%   |
| Samsung SSD 850 EVO 500GB        | 1         | 2.33%   |
| Samsung MZNLN512HMJP-000L7 512GB | 1         | 2.33%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 2.33%   |
| OWC Mercury Electra 6G SSD       | 1         | 2.33%   |
| NVMe PM9A1 Samsu 512GB           | 1         | 2.33%   |
| NVMe PC300 SK hy 256GB           | 1         | 2.33%   |
| NVMe LENSE20256GMSP34 256GB      | 1         | 2.33%   |
| NVMe KINGSTON OM8PDP3 256GB      | 1         | 2.33%   |
| NVMe KBG40ZNS512G NVM 512GB      | 1         | 2.33%   |
| LDLC F6+ M.2 120 120GB           | 1         | 2.33%   |
| Kingston SV300S37A120G 120GB     | 1         | 2.33%   |
| Kingston SA400S37240G 240GB      | 1         | 2.33%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 2.33%   |
| Hitachi HTS547564A9E384 640GB    | 1         | 2.33%   |
| HGST HTS541010B7E610 1TB         | 1         | 2.33%   |
| HGST HTS541010A9E680 1TB         | 1         | 2.33%   |
| A-DATA SP550 480GB               | 1         | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 26.92%  |
| NVMe                | 5         | 5      | 19.23%  |
| Seagate             | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| Hitachi             | 2         | 3      | 7.69%   |
| HGST                | 2         | 2      | 7.69%   |
| USB                 | 1         | 1      | 3.85%   |
| LDLC F6+            | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 20%     |
| SanDisk             | 2         | 2      | 13.33%  |
| NVMe                | 2         | 2      | 13.33%  |
| Kingston            | 2         | 2      | 13.33%  |
| Innostor            | 2         | 2      | 13.33%  |
| Apacer              | 2         | 2      | 13.33%  |
| OWC                 | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 27     | 60%     |
| SSD  | 14        | 15     | 35%     |
| NVMe | 2         | 3      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 42     | 94.74%  |
| NVMe | 2         | 3      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 30     | 70.27%  |
| 0.51-1.0   | 11        | 12     | 29.73%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 29.27%  |
| 251-500    | 11        | 26.83%  |
| 21-50      | 9         | 21.95%  |
| 1-20       | 4         | 9.76%   |
| 51-100     | 4         | 9.76%   |
| 501-1000   | 1         | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 34        | 82.93%  |
| 21-50   | 2         | 4.88%   |
| 101-250 | 2         | 4.88%   |
| 51-100  | 2         | 4.88%   |
| 251-500 | 1         | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Toshiba MK6475GSX 640GB       | 1         | 1      | 20%     |
| Toshiba MK1629GSGF 160GB      | 1         | 1      | 20%     |
| Seagate ST9500420AS 500GB     | 1         | 1      | 20%     |
| SanDisk SD7UB3Q256G1001 256GB | 1         | 1      | 20%     |
| A-DATA Technology SP550 480GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 40%     |
| Seagate           | 1         | 1      | 20%     |
| SanDisk           | 1         | 1      | 20%     |
| A-DATA Technology | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

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
| Works    | 27        | 29     | 65.85%  |
| Detected | 9         | 11     | 21.95%  |
| Malfunc  | 5         | 5      | 12.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 30        | 68.18%  |
| AMD                         | 4         | 9.09%   |
| Samsung Electronics         | 3         | 6.82%   |
| SanDisk                     | 2         | 4.55%   |
| SK hynix                    | 1         | 2.27%   |
| Nvidia                      | 1         | 2.27%   |
| Lenovo                      | 1         | 2.27%   |
| KIOXIA                      | 1         | 2.27%   |
| Kingston Technology Company | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 10.42%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 6.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 4.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 4.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 4.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 4.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 4.17%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                            | 1         | 2.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 2.08%   |
| SanDisk NVMe Controller                                                                | 1         | 2.08%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.08%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 2.08%   |
| Lenovo unknown                                                                         | 1         | 2.08%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 1         | 2.08%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 2.08%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 2.08%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 2.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.08%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 65.22%  |
| NVMe | 9         | 19.57%  |
| IDE  | 7         | 15.22%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 82.93%  |
| AMD    | 6         | 14.63%  |
| 11th   | 1         | 2.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                        | 5         | 12.2%   |
| Intel Core i5-6300U CPU @ 2.40GHz                        | 3         | 7.32%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                     | 3         | 7.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                        | 2         | 4.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics                   | 2         | 4.88%   |
| Intel Pentium Silver N6000 @ 1.10GHz                     | 1         | 2.44%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                 | 1         | 2.44%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                       | 1         | 2.44%   |
| Intel Genuine CPU T2300 @ 1.66GHz                        | 1         | 2.44%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                      | 1         | 2.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz                        | 1         | 2.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz                        | 1         | 2.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz                        | 1         | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz                        | 1         | 2.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz                        | 1         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz                        | 1         | 2.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz                        | 1         | 2.44%   |
| Intel Core i5-10300H CPU @ 2.50GHz                       | 1         | 2.44%   |
| Intel Core i3-3120M CPU @ 2.50GHz                        | 1         | 2.44%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                     | 1         | 2.44%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz                     | 1         | 2.44%   |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz                     | 1         | 2.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz                        | 1         | 2.44%   |
| Intel Celeron CPU N3350 @ 1.10GHz                        | 1         | 2.44%   |
| Intel Atom CPU N280 @ 1.66GHz                            | 1         | 2.44%   |
| Intel Atom CPU N270 @ 1.60GHz ("GenuineIntel" 686-class) | 1         | 2.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics                   | 1         | 2.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics                   | 1         | 2.44%   |
| AMD E-300 APU with Radeon HD Graphics                    | 1         | 2.44%   |
| AMD A6-3400M APU with Radeon HD Graphics                 | 1         | 2.44%   |
| 11th Gen Intel Core i5-1135G7 @ 2.40GHz                  | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 15        | 36.59%  |
| Intel Core 2 Duo     | 6         | 14.63%  |
| Intel Core i7        | 3         | 7.32%   |
| AMD Ryzen 7          | 3         | 7.32%   |
| Intel Pentium Silver | 2         | 4.88%   |
| Intel Celeron        | 2         | 4.88%   |
| Intel Atom           | 2         | 4.88%   |
| Other                | 1         | 2.44%   |
| Intel Pentium 4      | 1         | 2.44%   |
| Intel Genuine        | 1         | 2.44%   |
| Intel Core i9        | 1         | 2.44%   |
| Intel Core i3        | 1         | 2.44%   |
| AMD Ryzen 5          | 1         | 2.44%   |
| AMD E                | 1         | 2.44%   |
| AMD A6               | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 48.78%  |
| Unknown | 11        | 26.83%  |
| 4       | 5         | 12.2%   |
| 8       | 3         | 7.32%   |
| 16      | 1         | 2.44%   |
| 12      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 33        | 80.49%  |
| Unknown | 8         | 19.51%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 48.78%  |
| Unknown | 11        | 26.83%  |
| 1       | 10        | 24.39%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 6         | 14.63%  |
| SandyBridge   | 5         | 12.2%   |
| IvyBridge     | 4         | 9.76%   |
| Zen 2         | 3         | 7.32%   |
| Skylake       | 3         | 7.32%   |
| Unknown       | 3         | 7.32%   |
| Westmere      | 2         | 4.88%   |
| KabyLake      | 2         | 4.88%   |
| Goldmont plus | 2         | 4.88%   |
| CometLake     | 2         | 4.88%   |
| Broadwell     | 2         | 4.88%   |
| Bonnell       | 2         | 4.88%   |
| P6            | 1         | 2.44%   |
| NetBurst      | 1         | 2.44%   |
| K10 Llano     | 1         | 2.44%   |
| Goldmont      | 1         | 2.44%   |
| Bobcat        | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 73.33%  |
| AMD    | 8         | 17.78%  |
| Nvidia | 4         | 8.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 5         | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 10%     |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 8%      |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 6%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 6%      |
| AMD Renoir                                                                    | 3         | 6%      |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 4%      |
| Intel HD Graphics 5500                                                        | 2         | 4%      |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 4%      |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 4%      |
| Nvidia TU117M                                                                 | 1         | 2%      |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 2%      |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 2%      |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 2%      |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 2%      |
| Intel UHD Graphics 620                                                        | 1         | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2%      |
| Intel JasperLake [UHD Graphics]                                               | 1         | 2%      |
| Intel HD Graphics 620                                                         | 1         | 2%      |
| Intel HD Graphics 500                                                         | 1         | 2%      |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2%      |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 2%      |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 2%      |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2%      |
| AMD Lucienne                                                                  | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 51.22%  |
| 2 x Intel      | 8         | 19.51%  |
| 1 x AMD        | 6         | 14.63%  |
| Intel + Nvidia | 3         | 7.32%   |
| 2 x Nvidia     | 1         | 2.44%   |
| 2 x AMD        | 1         | 2.44%   |
| Intel + AMD    | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 39        | 95.12%  |
| Unknown | 2         | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 19.23%  |
| Lenovo                  | 4         | 15.38%  |
| BOE                     | 4         | 15.38%  |
| AU Optronics            | 4         | 15.38%  |
| Chimei Innolux          | 3         | 11.54%  |
| Samsung Electronics     | 2         | 7.69%   |
| Chi Mei Optoelectronics | 2         | 7.69%   |
| TRU                     | 1         | 3.85%   |
| PANDA                   | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 11.54%  |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 2         | 7.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 7.69%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 3.85%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 3.85%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 3.85%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 3.85%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch              | 1         | 3.85%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 3.85%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 3.85%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 3.85%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 3.85%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 3.85%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 10        | 38.46%  |
| 1920x1080 (FHD) | 8         | 30.77%  |
| 1280x800 (WXGA) | 5         | 19.23%  |
| 1600x900 (HD+)  | 3         | 11.54%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 34.62%  |
| 12     | 8         | 30.77%  |
| 13     | 6         | 23.08%  |
| 11     | 2         | 7.69%   |
| 17     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 53.85%  |
| 201-300     | 11        | 42.31%  |
| 351-400     | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 80.77%  |
| 16/10 | 4         | 15.38%  |
| 3/2   | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 61-70          | 8         | 30.77%  |
| 81-90          | 5         | 19.23%  |
| 91-100         | 5         | 19.23%  |
| 101-110        | 4         | 15.38%  |
| 51-60          | 2         | 7.69%   |
| 71-80          | 1         | 3.85%   |
| 121-130        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 73.08%  |
| 101-120 | 3         | 11.54%  |
| 51-100  | 3         | 11.54%  |
| 161-240 | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 85.37%  |
| 0     | 6         | 14.63%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 31        | 53.45%  |
| Realtek Semiconductor             | 12        | 20.69%  |
| Qualcomm Atheros                  | 4         | 6.9%    |
| Ericsson Business Mobile Networks | 2         | 3.45%   |
| Broadcom                          | 2         | 3.45%   |
| Sierra Wireless                   | 1         | 1.72%   |
| Qualcomm Atheros Communications   | 1         | 1.72%   |
| Nvidia                            | 1         | 1.72%   |
| Marvell Technology Group          | 1         | 1.72%   |
| Hewlett-Packard                   | 1         | 1.72%   |
| Dell                              | 1         | 1.72%   |
| ASUSTek Computer                  | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 8         | 9.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 6         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 7.41%   |
| Intel Wi-Fi 6 AX200                                                         | 5         | 6.17%   |
| Intel 82567LM Gigabit Network Connection                                    | 5         | 6.17%   |
| Intel Ultimate N WiFi Link 5300                                             | 4         | 4.94%   |
| Intel Wireless 8260                                                         | 3         | 3.7%    |
| Intel Ethernet Connection I219-LM                                           | 3         | 3.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 2.47%   |
| Intel Wireless 7265                                                         | 2         | 2.47%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 2.47%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 2.47%   |
| Sierra Wireless EM7455                                                      | 1         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                            | 1         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                             | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.23%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 1.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.23%   |
| Intel Wireless 3165                                                         | 1         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                                  | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 1.23%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                         | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1         | 1.23%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                               | 1         | 1.23%   |
| HP un2400 Gobi Wireless Modem (QDL mode)                                    | 1         | 1.23%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                          | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 70.45%  |
| Realtek Semiconductor           | 4         | 9.09%   |
| Qualcomm Atheros                | 3         | 6.82%   |
| Broadcom                        | 2         | 4.55%   |
| Sierra Wireless                 | 1         | 2.27%   |
| Qualcomm Atheros Communications | 1         | 2.27%   |
| Dell                            | 1         | 2.27%   |
| ASUSTek Computer                | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 13.64%  |
| Intel Wi-Fi 6 AX200                                            | 5         | 11.36%  |
| Intel Ultimate N WiFi Link 5300                                | 4         | 9.09%   |
| Intel Wireless 8260                                            | 3         | 6.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 4.55%   |
| Intel Wireless 7265                                            | 2         | 4.55%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.55%   |
| Sierra Wireless EM7455                                         | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 2.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Intel Wireless 3165                                            | 1         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 2.27%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter             | 1         | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 2.27%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 52.94%  |
| Realtek Semiconductor    | 11        | 32.35%  |
| Qualcomm Atheros         | 2         | 5.88%   |
| Nvidia                   | 1         | 2.94%   |
| Marvell Technology Group | 1         | 2.94%   |
| Broadcom                 | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 23.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 17.65%  |
| Intel 82567LM Gigabit Network Connection                          | 5         | 14.71%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 8.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.94%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.94%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.94%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.94%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.94%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 51.95%  |
| Ethernet | 34        | 44.16%  |
| Unknown  | 2         | 2.6%    |
| Modem    | 1         | 1.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 80.49%  |
| Ethernet | 8         | 19.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 80.49%  |
| 1     | 8         | 19.51%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 97.56%  |
| Yes  | 1         | 2.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 46.67%  |
| Broadcom              | 8         | 26.67%  |
| Alps Electric         | 2         | 6.67%   |
| Realtek Semiconductor | 1         | 3.33%   |
| IMC Networks          | 1         | 3.33%   |
| Hewlett-Packard       | 1         | 3.33%   |
| Foxconn / Hon Hai     | 1         | 3.33%   |
| ASUSTek Computer      | 1         | 3.33%   |
| Apple                 | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 6         | 20%     |
| Intel AX200 Bluetooth                                    | 3         | 10%     |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 3         | 10%     |
| Broadcom BCM2045B (BDC-2.1)                              | 3         | 10%     |
| Intel AX201 Bluetooth                                    | 2         | 6.67%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 3.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 3.33%   |
| Intel AX210 Bluetooth                                    | 1         | 3.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 3.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 1         | 3.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 3.33%   |
| Broadcom BCM2046 Bluetooth Device                        | 1         | 3.33%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 3.33%   |
| Apple Bluetooth Host Controller                          | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 79.07%  |
| AMD    | 6         | 13.95%  |
| Nvidia | 3         | 6.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 9.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 9.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 9.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 7.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 7.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 5.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.92%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.92%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.96%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.96%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.96%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 1.96%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.96%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.96%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 4         | 30.77%  |
| Samsung Electronics | 4         | 30.77%  |
| SK hynix            | 3         | 23.08%  |
| Kingston            | 1         | 7.69%   |
| Unknown             | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 14.29%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 7.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 7.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 7.14%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 7.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 7.14%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s       | 1         | 7.14%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 7.14%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 8         | 72.73%  |
| SDRAM | 2         | 18.18%  |
| DDR2  | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 5         | 41.67%  |
| 2048 | 5         | 41.67%  |
| 1024 | 1         | 8.33%   |
| 512  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1333    | 3         | 27.27%  |
| Unknown | 3         | 27.27%  |
| 1334    | 2         | 18.18%  |
| 1067    | 2         | 18.18%  |
| 1600    | 1         | 9.09%   |

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
| Chicony Electronics                    | 12        | 46.15%  |
| Bison Electronics                      | 4         | 15.38%  |
| Realtek Semiconductor                  | 2         | 7.69%   |
| Tripath Technology                     | 1         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Ricoh                                  | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Lite-On Technology                     | 1         | 3.85%   |
| Denron                                 | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                                  | 5         | 19.23%  |
| Tripath PC Camera                                                          | 1         | 3.85%   |
| Sunplus Integrated HD Webcam                                               | 1         | 3.85%   |
| Ricoh Integrated Webcam                                                    | 1         | 3.85%   |
| Realtek USB Camera                                                         | 1         | 3.85%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.85%   |
| Quanta VGA WebCam                                                          | 1         | 3.85%   |
| Lite-On Integrated Camera                                                  | 1         | 3.85%   |
| Denron Corp., 2M Front Camera                                              | 1         | 3.85%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 3.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 3.85%   |
| Chicony Integrated IR Camera                                               | 1         | 3.85%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 3.85%   |
| Chicony HP Webcam [2 MP]                                                   | 1         | 3.85%   |
| Chicony FJ Camera                                                          | 1         | 3.85%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.85%   |
| Bison Integrated Camera                                                    | 1         | 3.85%   |
| Bison HD Webcam                                                            | 1         | 3.85%   |
| Bison EasyCamera                                                           | 1         | 3.85%   |
| Bison BisonCam, NB Pro                                                     | 1         | 3.85%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 37.5%   |
| Upek             | 3         | 37.5%   |
| AuthenTec        | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 37.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                        | 1         | 12.5%   |
| AuthenTec AES2810                                      | 1         | 12.5%   |
| AuthenTec AES2660                                      | 1         | 12.5%   |

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
| 1     | 20        | 48.78%  |
| 2     | 9         | 21.95%  |
| 0     | 6         | 14.63%  |
| 3     | 4         | 9.76%   |
| 5     | 1         | 2.44%   |
| 4     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 30        | 53.57%  |
| Graphics card            | 12        | 21.43%  |
| Net/wireless             | 5         | 8.93%   |
| Firewire controller      | 5         | 8.93%   |
| Sound                    | 2         | 3.57%   |
| Storage/ata              | 1         | 1.79%   |
| Network                  | 1         | 1.79%   |

