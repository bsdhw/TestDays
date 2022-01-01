OpenBSD 7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L5S1S000    | [0925acabe4](https://bsd-hardware.info/?probe=0925acabe4) | Dec 31, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Casper        | EXCALIBUR G900              | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Samsung       | 530XBB                      | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Samsung       | R720                        | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Dell          | G15 5510                    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| Dell          | G15 5510                    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Dell          | Vostro 3500                 | [923a99fade](https://bsd-hardware.info/?probe=923a99fade) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Dell          | Vostro 3500                 | [63443924f3](https://bsd-hardware.info/?probe=63443924f3) | Nov 19, 2021 |
| Acer          | AO722                       | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | Vostro 3500                 | [34d905d6f3](https://bsd-hardware.info/?probe=34d905d6f3) | Nov 11, 2021 |
| Google        | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Google        | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Google        | Grunt                       | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Google        | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Google        | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 28        | 90.32%  |
| i386  | 3         | 9.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| fvwm    | 26        | 83.87%  |
| Console | 3         | 9.68%   |
| Mutter  | 1         | 3.23%   |
| iwm     | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 28        | 90.32%  |
| Console | 3         | 9.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 25        | 80.65%  |
| SLiM    | 4         | 12.9%   |
| GDM     | 2         | 6.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 77.42%  |
| en_US   | 4         | 12.9%   |
| zh_CN   | 1         | 3.23%   |
| fr_FR   | 1         | 3.23%   |
| C       | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 18        | 58.06%  |
| BIOS | 13        | 41.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 31        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 17        | 53.13%  |
| MBR  | 15        | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 15        | 48.39%  |
| Dell                           | 3         | 9.68%   |
| Samsung Electronics            | 2         | 6.45%   |
| Panasonic                      | 2         | 6.45%   |
| Matsushita Electric Industrial | 2         | 6.45%   |
| Intel                          | 1         | 3.23%   |
| Hewlett-Packard                | 1         | 3.23%   |
| Google                         | 1         | 3.23%   |
| Casper                         | 1         | 3.23%   |
| ASUSTek Computer               | 1         | 3.23%   |
| Alienware                      | 1         | 3.23%   |
| Acer                           | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Samsung R720                                | 1         | 3.23%   |
| Samsung 530XBB                              | 1         | 3.23%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.23%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.23%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.23%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.23%   |
| Lenovo ThinkPad Yoga 11e 20DAS02S00         | 1         | 3.23%   |
| Lenovo ThinkPad X61 7675H7U                 | 1         | 3.23%   |
| Lenovo ThinkPad X220 429043U                | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0068GE    | 1         | 3.23%   |
| Lenovo ThinkPad T480 20L5S1S000             | 1         | 3.23%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 3.23%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 3.23%   |
| Lenovo ThinkPad T420 4236MBG                | 1         | 3.23%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 3.23%   |
| Lenovo ThinkPad P73 20QRS00200              | 1         | 3.23%   |
| Lenovo ThinkPad L14 Gen 1 20U1000VGE        | 1         | 3.23%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 3.23%   |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 3.23%   |
| Lenovo ThinkPad E14 Gen 2 20T6S02Y00        | 1         | 3.23%   |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 3.23%   |
| Intel SharkBay Platform                     | 1         | 3.23%   |
| HP Compaq 15                                | 1         | 3.23%   |
| Google Grunt                                | 1         | 3.23%   |
| Dell Vostro 3500                            | 1         | 3.23%   |
| Dell Inspiron 5570                          | 1         | 3.23%   |
| Dell G15 5510                               | 1         | 3.23%   |
| Casper EXCALIBUR G900                       | 1         | 3.23%   |
| ASUS 1000HE                                 | 1         | 3.23%   |
| Alienware m15                               | 1         | 3.23%   |
| Acer AO722                                  | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 14        | 45.16%  |
| Samsung R720                                | 1         | 3.23%   |
| Samsung 530XBB                              | 1         | 3.23%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.23%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.23%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.23%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.23%   |
| Lenovo IdeaPad                              | 1         | 3.23%   |
| Intel SharkBay                              | 1         | 3.23%   |
| HP Compaq                                   | 1         | 3.23%   |
| Google Grunt                                | 1         | 3.23%   |
| Dell Vostro                                 | 1         | 3.23%   |
| Dell Inspiron                               | 1         | 3.23%   |
| Dell G15                                    | 1         | 3.23%   |
| Casper EXCALIBUR                            | 1         | 3.23%   |
| ASUS 1000HE                                 | 1         | 3.23%   |
| Alienware m15                               | 1         | 3.23%   |
| Acer AO722                                  | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 19.35%  |
| 2021 | 5         | 16.13%  |
| 2018 | 4         | 12.9%   |
| 2019 | 3         | 9.68%   |
| 2009 | 3         | 9.68%   |
| 2015 | 2         | 6.45%   |
| 2011 | 2         | 6.45%   |
| 2014 | 1         | 3.23%   |
| 2013 | 1         | 3.23%   |
| 2012 | 1         | 3.23%   |
| 2010 | 1         | 3.23%   |
| 2006 | 1         | 3.23%   |
| 2002 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 96.77%  |
| Yes  | 1         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 8         | 25.81%  |
| 4.01-8.0   | 7         | 22.58%  |
| 3.01-4.0   | 5         | 16.13%  |
| 16.01-24.0 | 4         | 12.9%   |
| 2.01-3.0   | 3         | 9.68%   |
| 32.01-64.0 | 2         | 6.45%   |
| 1.01-2.0   | 1         | 3.23%   |
| 0.51-1.0   | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 28        | 90.32%  |
| 0.51-1.0 | 2         | 6.45%   |
| 0        | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 54.84%  |
| 2      | 10        | 32.26%  |
| 3      | 4         | 12.9%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 90.32%  |
| No        | 3         | 9.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 61.29%  |
| No        | 12        | 38.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Canada      | 9         | 29.03%  |
| USA         | 6         | 19.35%  |
| Germany     | 5         | 16.13%  |
| Sweden      | 2         | 6.45%   |
| France      | 2         | 6.45%   |
| Vietnam     | 1         | 3.23%   |
| Switzerland | 1         | 3.23%   |
| Russia      | 1         | 3.23%   |
| Poland      | 1         | 3.23%   |
| Czechia     | 1         | 3.23%   |
| China       | 1         | 3.23%   |
| Brazil      | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Montreal          | 6         | 18.75%  |
| Saint-Laurent     | 3         | 9.38%   |
| Paris             | 2         | 6.25%   |
| Henan             | 2         | 6.25%   |
| Frankfurt am Main | 2         | 6.25%   |
| Zurich            | 1         | 3.13%   |
| Yekaterinburg     | 1         | 3.13%   |
| Weinbohla         | 1         | 3.13%   |
| Warner            | 1         | 3.13%   |
| Sao Vicente       | 1         | 3.13%   |
| Queens            | 1         | 3.13%   |
| Prague            | 1         | 3.13%   |
| Portland          | 1         | 3.13%   |
| Pacierzow         | 1         | 3.13%   |
| Omaha             | 1         | 3.13%   |
| Nuremberg         | 1         | 3.13%   |
| Mountain View     | 1         | 3.13%   |
| Lidkoeping        | 1         | 3.13%   |
| Hohhot            | 1         | 3.13%   |
| Ho Chi Minh City  | 1         | 3.13%   |
| Gettysburg        | 1         | 3.13%   |
| Berlin            | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 10        | 14     | 27.78%  |
| WDC                 | 7         | 7      | 19.44%  |
| Samsung Electronics | 5         | 6      | 13.89%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 2         | 2      | 5.56%   |
| SK Hynix            | 1         | 1      | 2.78%   |
| Seagate             | 1         | 1      | 2.78%   |
| PLEXTOR             | 1         | 1      | 2.78%   |
| Netac               | 1         | 1      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba MK2556GSY 250GB          | 2         | 5.26%   |
| NVMe WDC PC SN730 SDB 256GB      | 2         | 5.26%   |
| WDC WDS480G2G0B-00EPW0 480GB     | 1         | 2.63%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 2.63%   |
| WDC WD7500BPKT-00PK4T0 752GB     | 1         | 2.63%   |
| WDC WD5000LPLX-00ZNTT0 500GB     | 1         | 2.63%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1         | 2.63%   |
| WDC WD3200BEVE-00A0HT0 320GB     | 1         | 2.63%   |
| WDC WD10JPLX-00MBPT0 1TB         | 1         | 2.63%   |
| Toshiba TR200 240GB              | 1         | 2.63%   |
| SK Hynix SC311 SATA 256GB        | 1         | 2.63%   |
| Seagate ST9160821A 160GB         | 1         | 2.63%   |
| Samsung SSD 860 EVO 1TB          | 1         | 2.63%   |
| Samsung SSD 850 EVO 500GB        | 1         | 2.63%   |
| Samsung MZ7TE128HMGR-000L1 128GB | 1         | 2.63%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 2.63%   |
| Samsung Flash Drive FIT 32GB     | 1         | 2.63%   |
| PLEXTOR PX-128M6S 128GB          | 1         | 2.63%   |
| NVMe Samsung SSD 970 250GB       | 1         | 2.63%   |
| NVMe SAMSUNG MZVLW1T0 1TB        | 1         | 2.63%   |
| NVMe SAMSUNG MZVLB256 256GB      | 1         | 2.63%   |
| NVMe SAMSUNG MZVLB1T0 1TB        | 1         | 2.63%   |
| NVMe Sabrent Rocket n 512GB      | 1         | 2.63%   |
| NVMe PC SN530 WD 512GB           | 1         | 2.63%   |
| NVMe OM3PDP3-AD 256GB            | 1         | 2.63%   |
| NVMe KXG50ZNV1T02 NVM 1TB        | 1         | 2.63%   |
| NVMe KIOXIA-EXCERIA S 500GB      | 1         | 2.63%   |
| NVMe INTEL SSDPEKKF51 512GB      | 1         | 2.63%   |
| Netac SSD 240GB                  | 1         | 2.63%   |
| Lexar USB Flash Drive 64GB       | 1         | 2.63%   |
| Intel SSDSA2M080G2GC 80GB        | 1         | 2.63%   |
| Hitachi HTS723232A7A364 320GB    | 1         | 2.63%   |
| Hitachi HTS722010K9SA00 100GB    | 1         | 2.63%   |
| Crucial CT500MX200SSD1 500GB     | 1         | 2.63%   |
| Apple HDD HTS547575A9E384 752GB  | 1         | 2.63%   |
| A-DATA SP550 480GB               | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 7         | 9      | 33.33%  |
| WDC                 | 6         | 6      | 28.57%  |
| Toshiba             | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| Seagate             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |
| Lexar               | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 28.57%  |
| NVMe                | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| SK Hynix            | 1         | 1      | 7.14%   |
| PLEXTOR             | 1         | 1      | 7.14%   |
| Netac               | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 24     | 58.82%  |
| SSD  | 12        | 14     | 35.29%  |
| NVMe | 2         | 3      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 38     | 93.55%  |
| NVMe | 2         | 3      | 6.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 27     | 68.75%  |
| 0.51-1.0   | 7         | 7      | 21.88%  |
| 1.01-2.0   | 3         | 4      | 9.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 8         | 25%     |
| 21-50      | 8         | 25%     |
| 51-100     | 8         | 25%     |
| 101-250    | 7         | 21.88%  |
| 501-1000   | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 26        | 83.87%  |
| 101-250 | 3         | 9.68%   |
| 21-50   | 2         | 6.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Intel SSDSA2M080G2GC 80GB     | 1         | 1      | 33.33%  |
| Hitachi HTS722010K9SA00 100GB | 1         | 1      | 33.33%  |
| A-DATA Technology SP550 480GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Intel             | 1         | 1      | 33.33%  |
| Hitachi           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

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
| Works    | 21        | 23     | 60%     |
| Detected | 11        | 15     | 31.43%  |
| Malfunc  | 3         | 3      | 8.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 23        | 63.89%  |
| Sandisk                     | 3         | 8.33%   |
| Samsung Electronics         | 3         | 8.33%   |
| AMD                         | 3         | 8.33%   |
| Toshiba                     | 1         | 2.78%   |
| Phison Electronics          | 1         | 2.78%   |
| KIOXIA                      | 1         | 2.78%   |
| Kingston Technology Company | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 8.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 5.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 5.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 5.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 5.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 5.41%   |
| Toshiba unknown                                                                        | 1         | 2.7%    |
| Sandisk unknown                                                                        | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 2.7%    |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.7%    |
| KIOXIA NVMe SSD                                                                        | 1         | 2.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 2.7%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 2.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 2.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 2.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 2.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 2.7%    |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 57.14%  |
| NVMe | 10        | 28.57%  |
| IDE  | 5         | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 83.87%  |
| AMD    | 5         | 16.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 9.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 6.45%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 6.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 6.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz            | 1         | 3.23%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 3.23%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 3.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 3.23%   |
| Intel Core i5-10200H CPU @ 2.40GHz            | 1         | 3.23%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 3.23%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 1         | 3.23%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 3.23%   |
| Intel Celeron CPU N2930 @ 1.83GHz             | 1         | 3.23%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 3.23%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.23%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1         | 3.23%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 3.23%   |
| AMD C-50 Processor                            | 1         | 3.23%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 45.16%  |
| Other            | 2         | 6.45%   |
| Intel Core i7    | 2         | 6.45%   |
| Intel Core 2 Duo | 2         | 6.45%   |
| Intel Celeron    | 2         | 6.45%   |
| Intel Pentium 4  | 1         | 3.23%   |
| Intel Genuine    | 1         | 3.23%   |
| Intel Core i9    | 1         | 3.23%   |
| Intel Atom       | 1         | 3.23%   |
| AMD Ryzen 7      | 1         | 3.23%   |
| AMD Ryzen 3      | 1         | 3.23%   |
| AMD E1           | 1         | 3.23%   |
| AMD C-50         | 1         | 3.23%   |
| AMD A4           | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 14        | 45.16%  |
| 4       | 8         | 25.81%  |
| Unknown | 5         | 16.13%  |
| 8       | 3         | 9.68%   |
| 6       | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 29        | 93.55%  |
| Unknown | 2         | 6.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 19        | 61.29%  |
| 1       | 7         | 22.58%  |
| Unknown | 5         | 16.13%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 22.58%  |
| SandyBridge   | 5         | 16.13%  |
| Westmere      | 2         | 6.45%   |
| Penryn        | 2         | 6.45%   |
| Zen 2         | 1         | 3.23%   |
| Zen           | 1         | 3.23%   |
| TigerLake     | 1         | 3.23%   |
| Silvermont    | 1         | 3.23%   |
| P6            | 1         | 3.23%   |
| NetBurst      | 1         | 3.23%   |
| Jaguar        | 1         | 3.23%   |
| IvyBridge     | 1         | 3.23%   |
| Goldmont plus | 1         | 3.23%   |
| Excavator     | 1         | 3.23%   |
| CometLake     | 1         | 3.23%   |
| Broadwell     | 1         | 3.23%   |
| Bonnell       | 1         | 3.23%   |
| Bobcat        | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 65.71%  |
| AMD    | 8         | 22.86%  |
| Nvidia | 4         | 11.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 13.16%  |
| Intel UHD Graphics 620                                                        | 2         | 5.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 5.26%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 2.63%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 2.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 2.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 2.63%   |
| Intel HD Graphics 620                                                         | 1         | 2.63%   |
| Intel HD Graphics 5500                                                        | 1         | 2.63%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 2.63%   |
| Intel Comet Lake UHD Graphics                                                 | 1         | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 2.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 1         | 2.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 2.63%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 2.63%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.63%   |
| AMD Renoir                                                                    | 1         | 2.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 2.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 2.63%   |
| AMD Kabini [Radeon HD 8210]                                                   | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 51.61%  |
| 1 x AMD        | 7         | 22.58%  |
| 2 x Intel      | 3         | 9.68%   |
| Intel + Nvidia | 3         | 9.68%   |
| 1 x Nvidia     | 1         | 3.23%   |
| Intel + AMD    | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 29        | 93.55%  |
| Unknown | 2         | 6.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 30%     |
| BOE                 | 5         | 25%     |
| Samsung Electronics | 3         | 15%     |
| LG Display          | 2         | 10%     |
| Chimei Innolux      | 2         | 10%     |
| PANDA               | 1         | 5%      |
| Gigabyte Technology | 1         | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch | 1         | 5%      |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 5%      |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 5%      |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch              | 1         | 5%      |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 1         | 5%      |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 5%      |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 5%      |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                | 1         | 5%      |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                | 1         | 5%      |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                | 1         | 5%      |
| BOE LCD Monitor BOE06A9 1920x1080 340x190mm 15.3-inch                | 1         | 5%      |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                 | 1         | 5%      |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch       | 1         | 5%      |
| AU Optronics LCD Monitor AUO4199 1920x1080 340x190mm 15.3-inch       | 1         | 5%      |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 5%      |
| AU Optronics LCD Monitor AUO34EB 3840x2160 340x190mm 15.3-inch       | 1         | 5%      |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 5%      |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 10        | 50%     |
| 1366x768 (WXGA) | 5         | 25%     |
| 3840x2160 (4K)  | 2         | 10%     |
| 1600x900 (HD+)  | 2         | 10%     |
| 2560x1440 (QHD) | 1         | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 45%     |
| 15     | 6         | 30%     |
| 11     | 3         | 15%     |
| 28     | 1         | 5%      |
| 12     | 1         | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 70%     |
| 201-300     | 5         | 25%     |
| 601-700     | 1         | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 40%     |
| 91-100         | 6         | 30%     |
| 51-60          | 3         | 15%     |
| 71-80          | 1         | 5%      |
| 61-70          | 1         | 5%      |
| 351-500        | 1         | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 80%     |
| 161-240       | 2         | 10%     |
| More than 240 | 1         | 5%      |
| 101-120       | 1         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 80.65%  |
| 0     | 6         | 19.35%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 24        | 51.06%  |
| Realtek Semiconductor             | 11        | 23.4%   |
| Qualcomm Atheros                  | 6         | 12.77%  |
| Marvell Technology Group          | 2         | 4.26%   |
| TP-Link                           | 1         | 2.13%   |
| Ralink Technology                 | 1         | 2.13%   |
| Ericsson Business Mobile Networks | 1         | 2.13%   |
| D-Link                            | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 8         | 12.9%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 5         | 8.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 5         | 8.06%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 4.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 2         | 3.23%   |
| Intel Wireless-AC 9260                                                      | 2         | 3.23%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 3.23%   |
| Intel Wireless 7260                                                         | 2         | 3.23%   |
| Intel Ethernet Connection (4) I219-V                                        | 2         | 3.23%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                                    | 2         | 3.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1         | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.61%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 1.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 1         | 1.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.61%   |
| Intel Wireless 3165                                                         | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 1         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 1.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                                       | 1         | 1.61%   |
| Intel Ethernet Connection (10) I219-V                                       | 1         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                              | 1         | 1.61%   |
| Intel 82566MM Gigabit Network Connection                                    | 1         | 1.61%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.61%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]        | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 72.73%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Realtek Semiconductor | 2         | 6.06%   |
| TP-Link               | 1         | 3.03%   |
| Ralink Technology     | 1         | 3.03%   |
| D-Link                | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 15.15%  |
| Intel Wi-Fi 6 AX200                                                     | 3         | 9.09%   |
| Intel Wireless-AC 9260                                                  | 2         | 6.06%   |
| Intel Wireless 8265 / 8275                                              | 2         | 6.06%   |
| Intel Wireless 7260                                                     | 2         | 6.06%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 6.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 3.03%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 3.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| Intel Wireless 3165                                                     | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 3.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 3.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 3.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 3.03%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 3.03%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 42.86%  |
| Realtek Semiconductor    | 11        | 39.29%  |
| Qualcomm Atheros         | 3         | 10.71%  |
| Marvell Technology Group | 2         | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 28.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 17.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 7.14%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 7.14%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 7.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 3.57%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.57%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.57%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50.85%  |
| Ethernet | 28        | 47.46%  |
| Unknown  | 1         | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 66.67%  |
| Ethernet | 11        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 87.1%   |
| 1     | 4         | 12.9%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 63.16%  |
| Broadcom              | 2         | 10.53%  |
| Alps Electric         | 2         | 10.53%  |
| Realtek Semiconductor | 1         | 5.26%   |
| Lite-On Technology    | 1         | 5.26%   |
| ASUSTek Computer      | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 3         | 15.79%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 2         | 10.53%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 10.53%  |
| Intel AX201 Bluetooth                          | 2         | 10.53%  |
| Intel AX200 Bluetooth                          | 2         | 10.53%  |
| Broadcom BCM2045B (BDC-2.1)                    | 2         | 10.53%  |
| Alps Electric UGTZ4 Bluetooth                  | 2         | 10.53%  |
| Realtek  Bluetooth Adapter                     | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 5.26%   |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 74.29%  |
| AMD    | 6         | 17.14%  |
| Nvidia | 3         | 8.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 10%     |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 7.5%    |
| Nvidia unknown                                                             | 2         | 5%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 5%      |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 5%      |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 5%      |
| Nvidia TU104 HD Audio Controller                                           | 1         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.5%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.5%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.5%    |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 2.5%    |
| AMD Wrestler HDMI Audio                                                    | 1         | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.5%    |
| AMD High Definition Audio Controller                                       | 1         | 2.5%    |
| AMD FCH Azalia Controller                                                  | 1         | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 38.46%  |
| Samsung Electronics | 5         | 38.46%  |
| SK Hynix            | 1         | 7.69%   |
| Kingston            | 1         | 7.69%   |
| Unknown             | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 2         | 14.29%  |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 14.29%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 7.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 7.14%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 7.14%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 7.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 7.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s  | 1         | 7.14%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s  | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 8         | 66.67%  |
| SDRAM | 2         | 16.67%  |
| DDR4  | 1         | 8.33%   |
| DDR2  | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 6         | 50%     |
| 2048 | 3         | 25%     |
| 8192 | 1         | 8.33%   |
| 1024 | 1         | 8.33%   |
| 512  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3         | 25%     |
| 1600    | 2         | 16.67%  |
| 1334    | 2         | 16.67%  |
| 1333    | 2         | 16.67%  |
| 1067    | 2         | 16.67%  |
| 3200    | 1         | 8.33%   |

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
| Chicony Electronics           | 7         | 33.33%  |
| Acer                          | 5         | 23.81%  |
| Microdia                      | 2         | 9.52%   |
| Sunplus Innovation Technology | 1         | 4.76%   |
| Silicon Motion                | 1         | 4.76%   |
| Realtek Semiconductor         | 1         | 4.76%   |
| Luxvisions Innotech Limited   | 1         | 4.76%   |
| IMC Networks                  | 1         | 4.76%   |
| ALi                           | 1         | 4.76%   |
| Alcor Micro                   | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 2         | 9.52%   |
| Chicony integrated camera                     | 2         | 9.52%   |
| Acer Integrated Camera                        | 2         | 9.52%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 4.76%   |
| Silicon Motion Web Camera                     | 1         | 4.76%   |
| Realtek Integrated Webcam                     | 1         | 4.76%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 4.76%   |
| IMC Networks Integrated Camera                | 1         | 4.76%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 4.76%   |
| Chicony Ltd., Integrated Camera               | 1         | 4.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 4.76%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 4.76%   |
| ALi WebCam                                    | 1         | 4.76%   |
| Alcor Micro USB 2.0 Camera                    | 1         | 4.76%   |
| Acer ThinkPad Integrated Camera               | 1         | 4.76%   |
| Acer SunplusIT Integrated Camera              | 1         | 4.76%   |
| Acer EasyCamera                               | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Upek                       | 2         | 28.57%  |
| Synaptics                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |
| Samsung Electronics        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Synaptics product 0x00be                               | 1         | 14.29%  |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 14.29%  |
| Samsung Fingerprint Device                             | 1         | 14.29%  |

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
| 1     | 16        | 48.48%  |
| 2     | 6         | 18.18%  |
| 0     | 5         | 15.15%  |
| 4     | 4         | 12.12%  |
| 5     | 1         | 3.03%   |
| 3     | 1         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 20        | 47.62%  |
| Graphics card            | 8         | 19.05%  |
| Net/wireless             | 5         | 11.9%   |
| Firewire controller      | 4         | 9.52%   |
| Sound                    | 3         | 7.14%   |
| Storage/ata              | 1         | 2.38%   |
| Network                  | 1         | 2.38%   |

