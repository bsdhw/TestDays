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

Total: 30

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 26        | 89.66%  |
| i386  | 3         | 10.34%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 22        | 75.86%  |
| fvwm         | 5         | 17.24%  |
| XFCE         | 1         | 3.45%   |
| MATE         | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 89.66%  |
| Console | 3         | 10.34%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 86.21%  |
| ru_RU   | 3         | 10.34%  |
| en_GB   | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 17        | 58.62%  |
| BIOS | 12        | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 29        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 15        | 51.72%  |
| GPT  | 14        | 48.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 13        | 44.83%  |
| TUXEDO                         | 2         | 6.9%    |
| Panasonic                      | 2         | 6.9%    |
| Matsushita Electric Industrial | 2         | 6.9%    |
| Dell                           | 2         | 6.9%    |
| ASUSTek Computer               | 2         | 6.9%    |
| MSI                            | 1         | 3.45%   |
| Hewlett-Packard                | 1         | 3.45%   |
| Fujitsu                        | 1         | 3.45%   |
| DEXP                           | 1         | 3.45%   |
| Apple                          | 1         | 3.45%   |
| Acer                           | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 3         | 10.34%  |
| TUXEDO Pulse 15 Gen1                        | 1         | 3.45%   |
| TUXEDO Aura 15 Gen1                         | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| MSI Modern 14 B11MOL                        | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 3.45%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V         | 1         | 3.45%   |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 3.45%   |
| Lenovo ThinkPad X220 429043U                | 1         | 3.45%   |
| Lenovo ThinkPad X121e 3053A52               | 1         | 3.45%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 3.45%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 3.45%   |
| Lenovo ThinkPad L530 24812TG                | 1         | 3.45%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 3.45%   |
| HP Pavilion Laptop 15-cs0xxx                | 1         | 3.45%   |
| Fujitsu LIFEBOOK E752                       | 1         | 3.45%   |
| DEXP NAVIS P100                             | 1         | 3.45%   |
| Dell Vostro 3550                            | 1         | 3.45%   |
| Dell Inspiron 5515                          | 1         | 3.45%   |
| ASUS K53TA                                  | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| Apple MacBookPro5,3                         | 1         | 3.45%   |
| Acer Aspire A114-33                         | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 12        | 41.38%  |
| TUXEDO Pulse                                | 1         | 3.45%   |
| TUXEDO Aura                                 | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| MSI Modern                                  | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo Yoga                                 | 1         | 3.45%   |
| HP Pavilion                                 | 1         | 3.45%   |
| Fujitsu LIFEBOOK                            | 1         | 3.45%   |
| DEXP NAVIS                                  | 1         | 3.45%   |
| Dell Vostro                                 | 1         | 3.45%   |
| Dell Inspiron                               | 1         | 3.45%   |
| ASUS K53TA                                  | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| Apple MacBookPro5                           | 1         | 3.45%   |
| Acer Aspire                                 | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 5         | 17.24%  |
| 2009 | 5         | 17.24%  |
| 2021 | 3         | 10.34%  |
| 2018 | 3         | 10.34%  |
| 2020 | 2         | 6.9%    |
| 2012 | 2         | 6.9%    |
| 2010 | 2         | 6.9%    |
| 2022 | 1         | 3.45%   |
| 2019 | 1         | 3.45%   |
| 2015 | 1         | 3.45%   |
| 2014 | 1         | 3.45%   |
| 2013 | 1         | 3.45%   |
| 2006 | 1         | 3.45%   |
| 2002 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 37.93%  |
| 8.01-16.0  | 6         | 20.69%  |
| 3.01-4.0   | 4         | 13.79%  |
| 2.01-3.0   | 3         | 10.34%  |
| 16.01-24.0 | 3         | 10.34%  |
| 32.01-64.0 | 1         | 3.45%   |
| 0.51-1.0   | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 26        | 89.66%  |
| 0        | 2         | 6.9%    |
| 0.51-1.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 55.17%  |
| 2      | 10        | 34.48%  |
| 3      | 3         | 10.34%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 86.21%  |
| No        | 4         | 13.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 72.41%  |
| No        | 8         | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 10        | 34.48%  |
| Russia  | 5         | 17.24%  |
| UK      | 3         | 10.34%  |
| Poland  | 3         | 10.34%  |
| France  | 3         | 10.34%  |
| USA     | 2         | 6.9%    |
| Spain   | 1         | 3.45%   |
| Italy   | 1         | 3.45%   |
| Chile   | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 34.48%  |
| Vladivostok         | 2         | 6.9%    |
| Gdansk              | 2         | 6.9%    |
| West Valley City    | 1         | 3.45%   |
| Valdivia            | 1         | 3.45%   |
| Sutton              | 1         | 3.45%   |
| Starogard Gdański  | 1         | 3.45%   |
| St Petersburg       | 1         | 3.45%   |
| Springboro          | 1         | 3.45%   |
| Ozersk              | 1         | 3.45%   |
| Newcastle upon Tyne | 1         | 3.45%   |
| Mâcon              | 1         | 3.45%   |
| Ermont              | 1         | 3.45%   |
| Edinburgh           | 1         | 3.45%   |
| Concesio            | 1         | 3.45%   |
| Chelyabinsk         | 1         | 3.45%   |
| Biot                | 1         | 3.45%   |
| Alcorisa            | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 19.35%  |
| Samsung Electronics | 6         | 6      | 19.35%  |
| NVMe                | 5         | 5      | 16.13%  |
| Seagate             | 2         | 2      | 6.45%   |
| SanDisk             | 2         | 2      | 6.45%   |
| Innostor            | 2         | 2      | 6.45%   |
| Hitachi             | 2         | 2      | 6.45%   |
| USB                 | 1         | 1      | 3.23%   |
| OWC                 | 1         | 1      | 3.23%   |
| LDLC F6+            | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung HM321HI 320GB            | 3         | 9.68%   |
| NVMe Samsung SSD 980 1TB         | 2         | 6.45%   |
| Innostor SSD 15GB                | 2         | 6.45%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 3.23%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1         | 3.23%   |
| WDC WD7500BPKT-00PK4T0 752GB     | 1         | 3.23%   |
| WDC WD5000LPLX-00ZNTT0 500GB     | 1         | 3.23%   |
| WDC WD3200BEVE-00A0HT0 320GB     | 1         | 3.23%   |
| WDC WD10JPLX-00MBPT0 1TB         | 1         | 3.23%   |
| USB SanDisk 3.2Gen1 64GB         | 1         | 3.23%   |
| Seagate ST9500420AS 500GB        | 1         | 3.23%   |
| Seagate ST9160821A 160GB         | 1         | 3.23%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 3.23%   |
| SanDisk Extreme 55AE 500GB       | 1         | 3.23%   |
| Samsung SSD 850 EVO 500GB        | 1         | 3.23%   |
| Samsung MZNLN512HMJP-000L7 512GB | 1         | 3.23%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 3.23%   |
| OWC Mercury Electra 6G SSD       | 1         | 3.23%   |
| NVMe WDC PC SN530 SDB 256GB      | 1         | 3.23%   |
| NVMe KINGSTON OM8PDP3 256GB      | 1         | 3.23%   |
| NVMe KBG40ZNS512G NVM 512GB      | 1         | 3.23%   |
| LDLC F6+ M.2 120 120GB           | 1         | 3.23%   |
| Kingston SV300S37A120G 120GB     | 1         | 3.23%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 3.23%   |
| Hitachi HTS547564A9E384 640GB    | 1         | 3.23%   |
| HGST HTS541010B7E610 1TB         | 1         | 3.23%   |
| A-DATA SP550 480GB               | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 31.58%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| NVMe                | 3         | 3      | 15.79%  |
| Seagate             | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| USB                 | 1         | 1      | 5.26%   |
| LDLC F6+            | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| SanDisk             | 2         | 2      | 16.67%  |
| NVMe                | 2         | 2      | 16.67%  |
| Innostor            | 2         | 2      | 16.67%  |
| OWC                 | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 19     | 62.07%  |
| SSD  | 11        | 12     | 37.93%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 27        | 31     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 21     | 62.96%  |
| 0.51-1.0   | 10        | 10     | 37.04%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 9         | 31.03%  |
| 21-50      | 8         | 27.59%  |
| 101-250    | 5         | 17.24%  |
| 51-100     | 4         | 13.79%  |
| 1-20       | 3         | 10.34%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 26        | 89.66%  |
| 101-250 | 2         | 6.9%    |
| 21-50   | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB     | 1         | 1      | 33.33%  |
| SanDisk SD7UB3Q256G1001 256GB | 1         | 1      | 33.33%  |
| A-DATA Technology SP550 480GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 1         | 1      | 33.33%  |
| SanDisk           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 21        | 22     | 72.41%  |
| Detected | 5         | 6      | 17.24%  |
| Malfunc  | 3         | 3      | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 67.74%  |
| AMD                         | 4         | 12.9%   |
| Samsung Electronics         | 2         | 6.45%   |
| SanDisk                     | 1         | 3.23%   |
| Nvidia                      | 1         | 3.23%   |
| KIOXIA                      | 1         | 3.23%   |
| Kingston Technology Company | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 9.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 9.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 9.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 6.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 6.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 6.25%   |
| SanDisk PC SN530                                                                       | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 3.13%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 3.13%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 3.13%   |
| KIOXIA unknown                                                                         | 1         | 3.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 3.13%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 3.13%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 70.97%  |
| NVMe | 5         | 16.13%  |
| IDE  | 4         | 12.9%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 75.86%  |
| AMD    | 6         | 20.69%  |
| 11th   | 1         | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 13.79%  |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 3         | 10.34%  |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 2         | 6.9%    |
| AMD Ryzen 7 4700U with Radeon Graphics   | 2         | 6.9%    |
| Intel Pentium Silver N6000 @ 1.10GHz     | 1         | 3.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 3.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz       | 1         | 3.45%   |
| Intel Genuine CPU T2300 @ 1.66GHz        | 1         | 3.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 1         | 3.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 3.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 3.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 1         | 3.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 3.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 3.45%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz     | 1         | 3.45%   |
| Intel Celeron CPU N3350 @ 1.10GHz        | 1         | 3.45%   |
| Intel Atom CPU N280 @ 1.66GHz            | 1         | 3.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 1         | 3.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 1         | 3.45%   |
| AMD E-300 APU with Radeon HD Graphics    | 1         | 3.45%   |
| AMD A6-3400M APU with Radeon HD Graphics | 1         | 3.45%   |
| 11th Gen Intel Core i5-1135G7 @ 2.40GHz  | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 11        | 37.93%  |
| Intel Core 2 Duo     | 4         | 13.79%  |
| AMD Ryzen 7          | 3         | 10.34%  |
| Intel Pentium Silver | 2         | 6.9%    |
| Other                | 1         | 3.45%   |
| Intel Pentium 4      | 1         | 3.45%   |
| Intel Genuine        | 1         | 3.45%   |
| Intel Core i7        | 1         | 3.45%   |
| Intel Celeron        | 1         | 3.45%   |
| Intel Atom           | 1         | 3.45%   |
| AMD Ryzen 5          | 1         | 3.45%   |
| AMD E                | 1         | 3.45%   |
| AMD A6               | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 13        | 44.83%  |
| Unknown | 8         | 27.59%  |
| 4       | 4         | 13.79%  |
| 8       | 2         | 6.9%    |
| 16      | 1         | 3.45%   |
| 12      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 24        | 82.76%  |
| Unknown | 5         | 17.24%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 12        | 41.38%  |
| 1       | 9         | 31.03%  |
| Unknown | 8         | 27.59%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 4         | 13.79%  |
| Penryn        | 4         | 13.79%  |
| Zen 2         | 3         | 10.34%  |
| IvyBridge     | 3         | 10.34%  |
| Unknown       | 3         | 10.34%  |
| Westmere      | 2         | 6.9%    |
| Skylake       | 1         | 3.45%   |
| P6            | 1         | 3.45%   |
| NetBurst      | 1         | 3.45%   |
| KabyLake      | 1         | 3.45%   |
| K10 Llano     | 1         | 3.45%   |
| Goldmont plus | 1         | 3.45%   |
| Goldmont      | 1         | 3.45%   |
| Broadwell     | 1         | 3.45%   |
| Bonnell       | 1         | 3.45%   |
| Bobcat        | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 70%     |
| AMD    | 8         | 26.67%  |
| Nvidia | 1         | 3.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 11.76%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 8.82%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 8.82%   |
| AMD Renoir                                                                    | 3         | 8.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 5.88%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 5.88%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 2         | 5.88%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 2.94%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 2.94%   |
| Intel UHD Graphics 620                                                        | 1         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 2.94%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2.94%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 2.94%   |
| Intel HD Graphics 5500                                                        | 1         | 2.94%   |
| Intel HD Graphics 500                                                         | 1         | 2.94%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 2.94%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 2.94%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 2.94%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.94%   |
| AMD Lucienne                                                                  | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 15        | 51.72%  |
| 1 x AMD     | 6         | 20.69%  |
| 2 x Intel   | 5         | 17.24%  |
| 2 x Nvidia  | 1         | 3.45%   |
| 2 x AMD     | 1         | 3.45%   |
| Intel + AMD | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 27        | 93.1%   |
| Unknown | 2         | 6.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 4         | 21.05%  |
| LG Display              | 3         | 15.79%  |
| Lenovo                  | 3         | 15.79%  |
| Samsung Electronics     | 2         | 10.53%  |
| Chimei Innolux          | 2         | 10.53%  |
| Chi Mei Optoelectronics | 2         | 10.53%  |
| AU Optronics            | 2         | 10.53%  |
| PANDA                   | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 15.79%  |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 10.53%  |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 5.26%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 5.26%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 5.26%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch         | 1         | 5.26%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 5.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 5.26%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 5.26%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 8         | 42.11%  |
| 1920x1080 (FHD) | 7         | 36.84%  |
| 1280x800 (WXGA) | 3         | 15.79%  |
| 1600x900 (HD+)  | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 42.11%  |
| 13     | 5         | 26.32%  |
| 12     | 5         | 26.32%  |
| 11     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 63.16%  |
| 201-300     | 7         | 36.84%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 84.21%  |
| 16/10 | 3         | 15.79%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 61-70          | 5         | 26.32%  |
| 81-90          | 4         | 21.05%  |
| 101-110        | 4         | 21.05%  |
| 91-100         | 4         | 21.05%  |
| 71-80          | 1         | 5.26%   |
| 51-60          | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 13        | 68.42%  |
| 51-100  | 3         | 15.79%  |
| 101-120 | 2         | 10.53%  |
| 161-240 | 1         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 86.21%  |
| 0     | 4         | 13.79%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 22        | 52.38%  |
| Realtek Semiconductor             | 10        | 23.81%  |
| Qualcomm Atheros                  | 3         | 7.14%   |
| Ericsson Business Mobile Networks | 2         | 4.76%   |
| Qualcomm Atheros Communications   | 1         | 2.38%   |
| Nvidia                            | 1         | 2.38%   |
| Marvell Technology Group          | 1         | 2.38%   |
| Dell                              | 1         | 2.38%   |
| Broadcom                          | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 8         | 14.04%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 5         | 8.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 5         | 8.77%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 5.26%   |
| Intel Ultimate N WiFi Link 5300                                             | 3         | 5.26%   |
| Intel 82567LM Gigabit Network Connection                                    | 3         | 5.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 3.51%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 3.51%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 3.51%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                             | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 1.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.75%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 1.75%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.75%   |
| Intel Wireless 8260                                                         | 1         | 1.75%   |
| Intel Wireless 7265                                                         | 1         | 1.75%   |
| Intel Wireless 3165                                                         | 1         | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                                  | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 1.75%   |
| Intel Ethernet Connection I219-LM                                           | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 1         | 1.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                               | 1         | 1.75%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                     | 1         | 1.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1         | 1.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 73.33%  |
| Realtek Semiconductor           | 3         | 10%     |
| Qualcomm Atheros                | 2         | 6.67%   |
| Qualcomm Atheros Communications | 1         | 3.33%   |
| Dell                            | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 16.67%  |
| Intel Wi-Fi 6 AX200                                            | 3         | 10%     |
| Intel Ultimate N WiFi Link 5300                                | 3         | 10%     |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 6.67%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Intel Wireless 8260                                            | 1         | 3.33%   |
| Intel Wireless 7265                                            | 1         | 3.33%   |
| Intel Wireless 3165                                            | 1         | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 3.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 3.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 3.33%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 3.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 48%     |
| Realtek Semiconductor    | 9         | 36%     |
| Qualcomm Atheros         | 2         | 8%      |
| Nvidia                   | 1         | 4%      |
| Marvell Technology Group | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 32%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 20%     |
| Intel 82567LM Gigabit Network Connection                          | 3         | 12%     |
| Intel 82577LM Gigabit Network Connection                          | 2         | 8%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 4%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 4%      |
| Nvidia MCP79 Ethernet                                             | 1         | 4%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 4%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 50.91%  |
| Ethernet | 25        | 45.45%  |
| Unknown  | 2         | 3.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 83.33%  |
| Ethernet | 5         | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 82.76%  |
| 1     | 5         | 17.24%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 96.55%  |
| Yes  | 1         | 3.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 42.86%  |
| Broadcom              | 6         | 28.57%  |
| Alps Electric         | 2         | 9.52%   |
| Realtek Semiconductor | 1         | 4.76%   |
| Foxconn / Hon Hai     | 1         | 4.76%   |
| ASUSTek Computer      | 1         | 4.76%   |
| Apple                 | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 3         | 14.29%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 3         | 14.29%  |
| Intel AX200 Bluetooth                                    | 2         | 9.52%   |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 9.52%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 4.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 4.76%   |
| Intel AX210 Bluetooth                                    | 1         | 4.76%   |
| Intel AX201 Bluetooth                                    | 1         | 4.76%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 4.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 4.76%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 4.76%   |
| Apple Bluetooth Host Controller                          | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 75.86%  |
| AMD    | 6         | 20.69%  |
| Nvidia | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 11.11%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 11.11%  |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 11.11%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 5.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 5.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 5.56%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.78%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 2.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.78%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.78%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 2.78%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.78%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.78%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 38.46%  |
| Samsung Electronics | 4         | 30.77%  |
| SK hynix            | 3         | 23.08%  |
| Kingston            | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 5         | 35.71%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 14.29%  |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 7.14%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 7.14%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |

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
| Chicony Electronics                    | 9         | 50%     |
| Acer                                   | 3         | 16.67%  |
| Sunplus Innovation Technology          | 1         | 5.56%   |
| Ricoh                                  | 1         | 5.56%   |
| Quanta                                 | 1         | 5.56%   |
| Denron                                 | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.56%   |
| Alcor Micro                            | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 2         | 11.11%  |
| Sunplus Integrated_Webcam_HD                                               | 1         | 5.56%   |
| Ricoh Integrated Webcam                                                    | 1         | 5.56%   |
| Quanta VGA WebCam                                                          | 1         | 5.56%   |
| Denron Corp., 2M Front Camera                                              | 1         | 5.56%   |
| Chicony Ltd., Integrated Camera                                            | 1         | 5.56%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 5.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 5.56%   |
| Chicony Integrated Camera [ThinkPad]                                       | 1         | 5.56%   |
| Chicony HD Webcam                                                          | 1         | 5.56%   |
| Chicony FJ Camera                                                          | 1         | 5.56%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 5.56%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 5.56%   |
| Acer Integrated Camera                                                     | 1         | 5.56%   |
| Acer HD Webcam                                                             | 1         | 5.56%   |
| Acer EasyCamera                                                            | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 40%     |
| Upek             | 2         | 40%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 40%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 20%     |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 20%     |

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
| 1     | 15        | 51.72%  |
| 0     | 6         | 20.69%  |
| 2     | 5         | 17.24%  |
| 5     | 1         | 3.45%   |
| 4     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 19        | 54.29%  |
| Graphics card            | 6         | 17.14%  |
| Firewire controller      | 4         | 11.43%  |
| Net/wireless             | 3         | 8.57%   |
| Storage/ata              | 1         | 2.86%   |
| Sound                    | 1         | 2.86%   |
| Network                  | 1         | 2.86%   |

