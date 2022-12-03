OpenBSD 7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.0.

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

Total: 65

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| IBM           | 2658MNG                     | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| HP            | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Lenovo        | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| Lenovo        | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Lenovo        | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| HP            | EliteBook 2530p             | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Lenovo        | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Framework     | Laptop                      | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
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
| amd64 | 46        | 92%     |
| i386  | 4         | 8%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| fvwm    | 42        | 82.35%  |
| Console | 3         | 5.88%   |
| XFCE    | 2         | 3.92%   |
| Mutter  | 2         | 3.92%   |
| Openbox | 1         | 1.96%   |
| iwm     | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 47        | 94%     |
| Console | 3         | 6%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 42        | 82.35%  |
| SLiM    | 6         | 11.76%  |
| GDM     | 3         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 76.47%  |
| en_US   | 5         | 9.8%    |
| fr_FR   | 3         | 5.88%   |
| C       | 2         | 3.92%   |
| zh_CN   | 1         | 1.96%   |
| en_GB   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 32        | 64%     |
| BIOS | 18        | 36%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 50        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 28        | 54.9%   |
| MBR  | 23        | 45.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 25        | 50%     |
| Dell                           | 5         | 10%     |
| Hewlett-Packard                | 3         | 6%      |
| Samsung Electronics            | 2         | 4%      |
| Panasonic                      | 2         | 4%      |
| Matsushita Electric Industrial | 2         | 4%      |
| Apple                          | 2         | 4%      |
| Acer                           | 2         | 4%      |
| Intel                          | 1         | 2%      |
| IBM                            | 1         | 2%      |
| Google                         | 1         | 2%      |
| Framework                      | 1         | 2%      |
| Casper                         | 1         | 2%      |
| ASUSTek Computer               | 1         | 2%      |
| Alienware                      | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G                | 3         | 6%      |
| Samsung R720                                | 1         | 2%      |
| Samsung 530XBB                              | 1         | 2%      |
| Panasonic CF-53AAGHYDM                      | 1         | 2%      |
| Panasonic CF-52PFPBSFQ                      | 1         | 2%      |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2%      |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2%      |
| Lenovo V130-15IGM 81HL                      | 1         | 2%      |
| Lenovo ThinkPad Yoga 11e 20DAS02S00         | 1         | 2%      |
| Lenovo ThinkPad X61 7675H7U                 | 1         | 2%      |
| Lenovo ThinkPad X260 20F5S08Q00             | 1         | 2%      |
| Lenovo ThinkPad X250 20CLS59400             | 1         | 2%      |
| Lenovo ThinkPad X240 20AMS2QD0C             | 1         | 2%      |
| Lenovo ThinkPad X220 4291QT1                | 1         | 2%      |
| Lenovo ThinkPad X220 429043U                | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0061MX  | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon 5th 20HR0068GE    | 1         | 2%      |
| Lenovo ThinkPad T480 20L5S1S000             | 1         | 2%      |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2%      |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2%      |
| Lenovo ThinkPad T420 4236MBG                | 1         | 2%      |
| Lenovo ThinkPad T410 2537N24                | 1         | 2%      |
| Lenovo ThinkPad P73 20QRS00200              | 1         | 2%      |
| Lenovo ThinkPad L14 Gen 1 20U1000VGE        | 1         | 2%      |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 2%      |
| Lenovo ThinkPad E490 20N8CTO1WW             | 1         | 2%      |
| Lenovo ThinkPad E14 Gen 2 20T6S02Y00        | 1         | 2%      |
| Lenovo IdeaPad 330-15ARR 81D2               | 1         | 2%      |
| Lenovo Flex 2-15 20405                      | 1         | 2%      |
| Intel SharkBay Platform                     | 1         | 2%      |
| IBM 2658MNG                                 | 1         | 2%      |
| HP EliteBook 8440p                          | 1         | 2%      |
| HP EliteBook 2530p                          | 1         | 2%      |
| HP Compaq 15                                | 1         | 2%      |
| Google Grunt                                | 1         | 2%      |
| Framework Laptop                            | 1         | 2%      |
| Dell Vostro 3550                            | 1         | 2%      |
| Dell Vostro 3500                            | 1         | 2%      |
| Dell Latitude 3400                          | 1         | 2%      |
| Dell Inspiron 5570                          | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 22        | 44%     |
| HP EliteBook                                | 2         | 4%      |
| Dell Vostro                                 | 2         | 4%      |
| Samsung R720                                | 1         | 2%      |
| Samsung 530XBB                              | 1         | 2%      |
| Panasonic CF-53AAGHYDM                      | 1         | 2%      |
| Panasonic CF-52PFPBSFQ                      | 1         | 2%      |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2%      |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2%      |
| Lenovo V130-15IGM                           | 1         | 2%      |
| Lenovo IdeaPad                              | 1         | 2%      |
| Lenovo Flex                                 | 1         | 2%      |
| Intel SharkBay                              | 1         | 2%      |
| IBM 2658MNG                                 | 1         | 2%      |
| HP Compaq                                   | 1         | 2%      |
| Google Grunt                                | 1         | 2%      |
| Framework Laptop                            | 1         | 2%      |
| Dell Latitude                               | 1         | 2%      |
| Dell Inspiron                               | 1         | 2%      |
| Dell G15                                    | 1         | 2%      |
| Casper EXCALIBUR                            | 1         | 2%      |
| ASUS 1000HE                                 | 1         | 2%      |
| Apple MacBookPro9                           | 1         | 2%      |
| Apple MacBook5                              | 1         | 2%      |
| Alienware m15                               | 1         | 2%      |
| Acer Aspire                                 | 1         | 2%      |
| Acer AO722                                  | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 14%     |
| 2011 | 6         | 12%     |
| 2020 | 5         | 10%     |
| 2015 | 5         | 10%     |
| 2009 | 5         | 10%     |
| 2019 | 3         | 6%      |
| 2018 | 3         | 6%      |
| 2010 | 3         | 6%      |
| 2014 | 2         | 4%      |
| 2013 | 2         | 4%      |
| 2012 | 2         | 4%      |
| 2017 | 1         | 2%      |
| 2016 | 1         | 2%      |
| 2008 | 1         | 2%      |
| 2007 | 1         | 2%      |
| 2006 | 1         | 2%      |
| 2003 | 1         | 2%      |
| 2002 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 50        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 16        | 32%     |
| 4.01-8.0   | 12        | 24%     |
| 3.01-4.0   | 7         | 14%     |
| 16.01-24.0 | 6         | 12%     |
| 32.01-64.0 | 3         | 6%      |
| 2.01-3.0   | 3         | 6%      |
| 0.51-1.0   | 2         | 4%      |
| 1.01-2.0   | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 45        | 90%     |
| 0.51-1.0 | 3         | 6%      |
| 0        | 2         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 52.94%  |
| 2      | 18        | 35.29%  |
| 3      | 5         | 9.8%    |
| 0      | 1         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 98%     |
| Yes       | 1         | 2%      |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 90%     |
| No        | 5         | 10%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 96%     |
| No        | 2         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 62%     |
| No        | 19        | 38%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Canada      | 9         | 18%     |
| USA         | 8         | 16%     |
| Germany     | 8         | 16%     |
| Poland      | 5         | 10%     |
| France      | 5         | 10%     |
| Sweden      | 3         | 6%      |
| Vietnam     | 1         | 2%      |
| UK          | 1         | 2%      |
| Turkey      | 1         | 2%      |
| Switzerland | 1         | 2%      |
| Russia      | 1         | 2%      |
| Norway      | 1         | 2%      |
| Netherlands | 1         | 2%      |
| Malaysia    | 1         | 2%      |
| Finland     | 1         | 2%      |
| Czechia     | 1         | 2%      |
| China       | 1         | 2%      |
| Brazil      | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Montreal          | 6         | 11.54%  |
| Paris             | 4         | 7.69%   |
| Gdansk            | 4         | 7.69%   |
| Saint-Laurent     | 3         | 5.77%   |
| Portland          | 2         | 3.85%   |
| Henan             | 2         | 3.85%   |
| Frankfurt am Main | 2         | 3.85%   |
| Zurich            | 1         | 1.92%   |
| Yekaterinburg     | 1         | 1.92%   |
| Weinbohla         | 1         | 1.92%   |
| Warner            | 1         | 1.92%   |
| Stuttgart         | 1         | 1.92%   |
| SkellefteÃ¥     | 1         | 1.92%   |
| Sinzig            | 1         | 1.92%   |
| Sheboygan         | 1         | 1.92%   |
| Sao Vicente       | 1         | 1.92%   |
| Queens            | 1         | 1.92%   |
| Prague            | 1         | 1.92%   |
| Pacierzow         | 1         | 1.92%   |
| Oslo              | 1         | 1.92%   |
| Omaha             | 1         | 1.92%   |
| Nuremberg         | 1         | 1.92%   |
| Munich            | 1         | 1.92%   |
| Mountain View     | 1         | 1.92%   |
| Milton Keynes     | 1         | 1.92%   |
| Mâcon            | 1         | 1.92%   |
| Lidkoeping        | 1         | 1.92%   |
| Kuala Lumpur      | 1         | 1.92%   |
| Istanbul          | 1         | 1.92%   |
| Hohhot            | 1         | 1.92%   |
| Ho Chi Minh City  | 1         | 1.92%   |
| Helsinki          | 1         | 1.92%   |
| Gettysburg        | 1         | 1.92%   |
| Dortmund          | 1         | 1.92%   |
| Berlin            | 1         | 1.92%   |
| Amsterdam         | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 14        | 19     | 25.45%  |
| Samsung Electronics | 9         | 10     | 16.36%  |
| WDC                 | 7         | 7      | 12.73%  |
| Toshiba             | 5         | 6      | 9.09%   |
| Seagate             | 3         | 3      | 5.45%   |
| SK hynix            | 2         | 2      | 3.64%   |
| Kingston            | 2         | 2      | 3.64%   |
| Intel               | 2         | 2      | 3.64%   |
| Hitachi             | 2         | 2      | 3.64%   |
| A-DATA Technology   | 2         | 2      | 3.64%   |
| SanDisk             | 1         | 1      | 1.82%   |
| Plextor             | 1         | 1      | 1.82%   |
| Netac               | 1         | 1      | 1.82%   |
| Lexar               | 1         | 1      | 1.82%   |
| HGST                | 1         | 2      | 1.82%   |
| Crucial             | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung HM321HI 320GB             | 3         | 5.26%   |
| NVMe WDC PC SN730 SDB 256GB       | 3         | 5.26%   |
| Toshiba MK2556GSY 250GB           | 2         | 3.51%   |
| WDC WDS480G2G0B-00EPW0 480GB      | 1         | 1.75%   |
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 1.75%   |
| WDC WD7500BPKT-00PK4T0 752GB      | 1         | 1.75%   |
| WDC WD5000LPLX-00ZNTT0 500GB      | 1         | 1.75%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 1.75%   |
| WDC WD3200BEVE-00A0HT0 320GB      | 1         | 1.75%   |
| WDC WD10JPLX-00MBPT0 1TB          | 1         | 1.75%   |
| Toshiba TR200 240GB               | 1         | 1.75%   |
| Toshiba THNSFJ256GCSU 256GB       | 1         | 1.75%   |
| Toshiba MK1629GSGF 160GB          | 1         | 1.75%   |
| SK hynix SC311 SATA 256GB         | 1         | 1.75%   |
| SK hynix HFS128G32TNF-N3A0A 128GB | 1         | 1.75%   |
| Seagate ST9500420AS 500GB         | 1         | 1.75%   |
| Seagate ST9320423AS 320GB         | 1         | 1.75%   |
| Seagate ST9160821A 160GB          | 1         | 1.75%   |
| SanDisk Cruzer Blade 16GB         | 1         | 1.75%   |
| Samsung SSD 860 EVO 1TB           | 1         | 1.75%   |
| Samsung SSD 850 EVO 500GB         | 1         | 1.75%   |
| Samsung SSD 840 EVO 120GB         | 1         | 1.75%   |
| Samsung MZ7TE128HMGR-000L1 128GB  | 1         | 1.75%   |
| Samsung MZ7PC128HAFU-000L1 128GB  | 1         | 1.75%   |
| Samsung Flash Drive FIT 32GB      | 1         | 1.75%   |
| Plextor PX-128M6S 128GB           | 1         | 1.75%   |
| NVMe Samsung SSD 970 250GB        | 1         | 1.75%   |
| NVMe SAMSUNG MZVLW1T0 1TB         | 1         | 1.75%   |
| NVMe SAMSUNG MZVLB256 256GB       | 1         | 1.75%   |
| NVMe SAMSUNG MZVLB1T0 1TB         | 1         | 1.75%   |
| NVMe SAMSUNG MZVL21T0 1TB         | 1         | 1.75%   |
| NVMe Sabrent Rocket n 512GB       | 1         | 1.75%   |
| NVMe PC SN530 WD 512GB            | 1         | 1.75%   |
| NVMe OM3PDP3-AD 256GB             | 1         | 1.75%   |
| NVMe KXG50ZNV1T02 NVM 1TB         | 1         | 1.75%   |
| NVMe KIOXIA-EXCERIA S 500GB       | 1         | 1.75%   |
| NVMe KINGSTON RBUSNS8 256GB       | 1         | 1.75%   |
| NVMe INTEL SSDPEKKF51 512GB       | 1         | 1.75%   |
| NVMe IM2P33F3 AD 256GB            | 1         | 1.75%   |
| Netac SSD 240GB                   | 1         | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 10        | 13     | 32.26%  |
| WDC                 | 6         | 6      | 19.35%  |
| Samsung Electronics | 4         | 5      | 12.9%   |
| Toshiba             | 3         | 4      | 9.68%   |
| Seagate             | 3         | 3      | 9.68%   |
| Hitachi             | 2         | 2      | 6.45%   |
| Lexar               | 1         | 1      | 3.23%   |
| HGST                | 1         | 2      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 22.73%  |
| Toshiba             | 2         | 2      | 9.09%   |
| SK hynix            | 2         | 2      | 9.09%   |
| NVMe                | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| Intel               | 2         | 2      | 9.09%   |
| A-DATA Technology   | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| SanDisk             | 1         | 1      | 4.55%   |
| Plextor             | 1         | 1      | 4.55%   |
| Netac               | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 37     | 57.69%  |
| SSD  | 19        | 22     | 36.54%  |
| NVMe | 3         | 4      | 5.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 59     | 93.88%  |
| NVMe | 3         | 4      | 6.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 46     | 77.55%  |
| 0.51-1.0   | 7         | 7      | 14.29%  |
| 1.01-2.0   | 4         | 6      | 8.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 15        | 29.41%  |
| 251-500    | 12        | 23.53%  |
| 21-50      | 10        | 19.61%  |
| 51-100     | 10        | 19.61%  |
| 1-20       | 2         | 3.92%   |
| 501-1000   | 2         | 3.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 41        | 82%     |
| 21-50   | 4         | 8%      |
| 101-250 | 4         | 8%      |
| 51-100  | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Toshiba MK1629GSGF 160GB      | 1         | 2      | 11.11%  |
| Seagate ST9500420AS 500GB     | 1         | 1      | 11.11%  |
| Seagate ST9320423AS 320GB     | 1         | 1      | 11.11%  |
| Intel SSDSC2KF256H6L 256GB    | 1         | 1      | 11.11%  |
| Intel SSDSA2M080G2GC 80GB     | 1         | 1      | 11.11%  |
| Hitachi HTS722010K9SA00 100GB | 1         | 1      | 11.11%  |
| HGST HTS545050A7E660 500GB    | 1         | 2      | 11.11%  |
| A-DATA Technology SP550 480GB | 1         | 1      | 11.11%  |
| A-DATA Technology SP550 240GB | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 2         | 2      | 22.22%  |
| Intel             | 2         | 2      | 22.22%  |
| A-DATA Technology | 2         | 2      | 22.22%  |
| Toshiba           | 1         | 2      | 11.11%  |
| Hitachi           | 1         | 1      | 11.11%  |
| HGST              | 1         | 2      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Toshiba | 1         | 2      | 20%     |
| Hitachi | 1         | 1      | 20%     |
| HGST    | 1         | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 55.56%  |
| SSD  | 4         | 4      | 44.44%  |

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
| Works    | 30        | 32     | 55.56%  |
| Detected | 15        | 20     | 27.78%  |
| Malfunc  | 9         | 11     | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 68.42%  |
| SanDisk                     | 4         | 7.02%   |
| Samsung Electronics         | 4         | 7.02%   |
| AMD                         | 3         | 5.26%   |
| Kingston Technology Company | 2         | 3.51%   |
| Toshiba                     | 1         | 1.75%   |
| Phison Electronics          | 1         | 1.75%   |
| Nvidia                      | 1         | 1.75%   |
| KIOXIA                      | 1         | 1.75%   |
| ADATA Technology            | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 8.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 8.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 5.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 5.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 3.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 3.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 3.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 3.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 3.39%   |
| Intel 82801CAM IDE U100 Controller                                                     | 2         | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.39%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 3.39%   |
| Toshiba XG5 NVMe SSD Controller                                                        | 1         | 1.69%   |
| SanDisk unknown                                                                        | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.69%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.69%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 1.69%   |
| KIOXIA NVMe SSD                                                                        | 1         | 1.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 1.69%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.69%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.69%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 1.69%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.69%   |
| ADATA Technology unknown                                                               | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 61.4%   |
| NVMe | 14        | 24.56%  |
| IDE  | 8         | 14.04%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 90%     |
| AMD    | 5         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                                 | 5         | 10%     |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                              | 3         | 6%      |
| Intel Core i5-8250U CPU @ 1.60GHz                                 | 2         | 4%      |
| Intel Core i5-2540M CPU @ 2.60GHz                                 | 2         | 4%      |
| Intel Core i5 CPU M 520 @ 2.40GHz                                 | 2         | 4%      |
| Intel Celeron N4000 CPU @ 1.10GHz                                 | 2         | 4%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                           | 2         | 4%      |
| Intel Pentium 4 Mobile CPU 1.60GHz                                | 1         | 2%      |
| Intel Mobile Pentium 4 - M CPU 1.70GHz ("GenuineIntel" 686-class) | 1         | 2%      |
| Intel Genuine CPU T2300 @ 1.66GHz                                 | 1         | 2%      |
| Intel Core i9-9880H CPU @ 2.30GHz                                 | 1         | 2%      |
| Intel Core i7-8750H CPU @ 2.20GHz                                 | 1         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz                                 | 1         | 2%      |
| Intel Core i7-7500U CPU @ 2.70GHz                                 | 1         | 2%      |
| Intel Core i7-5600U CPU @ 2.60GHz                                 | 1         | 2%      |
| Intel Core i7-3520M CPU @ 2.90GHz                                 | 1         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz                                 | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz                                 | 1         | 2%      |
| Intel Core i5-5200U CPU @ 2.20GHz                                 | 1         | 2%      |
| Intel Core i5-4300U CPU @ 1.90GHz                                 | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz                                 | 1         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz                                | 1         | 2%      |
| Intel Core i5-10200H CPU @ 2.40GHz                                | 1         | 2%      |
| Intel Core i5 CPU M 560 @ 2.67GHz                                 | 1         | 2%      |
| Intel Core i3-4010U CPU @ 1.70GHz                                 | 1         | 2%      |
| Intel Core i3-10110U CPU @ 2.10GHz                                | 1         | 2%      |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz                              | 1         | 2%      |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz                              | 1         | 2%      |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz                              | 1         | 2%      |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz                              | 1         | 2%      |
| Intel Celeron CPU N2930 @ 1.83GHz                                 | 1         | 2%      |
| Intel Atom CPU N280 @ 1.66GHz                                     | 1         | 2%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz                           | 1         | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz                           | 1         | 2%      |
| AMD Ryzen 7 4700U with Radeon Graphics                            | 1         | 2%      |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                     | 1         | 2%      |
| AMD E1-2100 APU with Radeon HD Graphics                           | 1         | 2%      |
| AMD C-50 Processor                                                | 1         | 2%      |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G                     | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 19        | 38%     |
| Intel Core 2 Duo       | 7         | 14%     |
| Intel Core i7          | 5         | 10%     |
| Other                  | 4         | 8%      |
| Intel Celeron          | 3         | 6%      |
| Intel Core i3          | 2         | 4%      |
| Intel Pentium 4        | 1         | 2%      |
| Intel Mobile Pentium 4 | 1         | 2%      |
| Intel Genuine          | 1         | 2%      |
| Intel Core i9          | 1         | 2%      |
| Intel Atom             | 1         | 2%      |
| AMD Ryzen 7            | 1         | 2%      |
| AMD Ryzen 3            | 1         | 2%      |
| AMD E1                 | 1         | 2%      |
| AMD C-50               | 1         | 2%      |
| AMD A4                 | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 24        | 48%     |
| 4       | 11        | 22%     |
| Unknown | 10        | 20%     |
| 8       | 3         | 6%      |
| 6       | 1         | 2%      |
| 1       | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 42        | 84%     |
| Unknown | 8         | 16%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 31        | 62%     |
| Unknown | 11        | 22%     |
| 1       | 8         | 16%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 18%     |
| SandyBridge   | 7         | 14%     |
| Penryn        | 7         | 14%     |
| Westmere      | 3         | 6%      |
| TigerLake     | 3         | 6%      |
| NetBurst      | 2         | 4%      |
| IvyBridge     | 2         | 4%      |
| Haswell       | 2         | 4%      |
| Goldmont plus | 2         | 4%      |
| Broadwell     | 2         | 4%      |
| Zen 2         | 1         | 2%      |
| Zen           | 1         | 2%      |
| Skylake       | 1         | 2%      |
| Silvermont    | 1         | 2%      |
| P6            | 1         | 2%      |
| Jaguar        | 1         | 2%      |
| Excavator     | 1         | 2%      |
| CometLake     | 1         | 2%      |
| Bonnell       | 1         | 2%      |
| Bobcat        | 1         | 2%      |
| Unknown       | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 39        | 69.64%  |
| AMD    | 10        | 17.86%  |
| Nvidia | 7         | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 11.86%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 6.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 5.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.39%   |
| Intel UHD Graphics 620                                                        | 2         | 3.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 3.39%   |
| Intel HD Graphics 5500                                                        | 2         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.39%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 3.39%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 3.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 3.39%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.39%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                              | 1         | 1.69%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 1.69%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 1.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.69%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.69%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.69%   |
| Intel HD Graphics 620                                                         | 1         | 1.69%   |
| Intel Comet Lake-H GT1 [UHD Graphics 610]                                     | 1         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.69%   |
| AMD Wrestler [Radeon HD 6250]                                                 | 1         | 1.69%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.69%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                  | 1         | 1.69%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 1.69%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 1.69%   |
| AMD Renoir                                                                    | 1         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 1.69%   |
| AMD Kabini [Radeon HD 8210]                                                   | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 52%     |
| 1 x AMD        | 8         | 16%     |
| 2 x Intel      | 7         | 14%     |
| Intel + Nvidia | 4         | 8%      |
| 1 x Nvidia     | 3         | 6%      |
| Intel + AMD    | 2         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 48        | 96%     |
| Unknown | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 8         | 21.05%  |
| AU Optronics            | 8         | 21.05%  |
| Chimei Innolux          | 5         | 13.16%  |
| LG Display              | 4         | 10.53%  |
| Samsung Electronics     | 3         | 7.89%   |
| Lenovo                  | 3         | 7.89%   |
| Apple                   | 2         | 5.26%   |
| PANDA                   | 1         | 2.63%   |
| Gigabyte Technology     | 1         | 2.63%   |
| CSO                     | 1         | 2.63%   |
| Chi Mei Optoelectronics | 1         | 2.63%   |
| Ancor Communications    | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 7.89%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 5.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 2.63%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch                  | 1         | 2.63%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 2.63%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 2.63%   |
| CSO LCD Monitor CSO1403 3840x2400 300x190mm 14.0-inch                    | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 310x170mm 13.9-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE082E 1920x1080 310x170mm 13.9-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06A9 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO9314 1280x800 260x160mm 12.0-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO4199 1920x1080 340x190mm 15.3-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO34EB 3840x2160 340x190mm 15.3-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch            | 1         | 2.63%   |
| Apple LCD Monitor APP9C89 1280x800 290x180mm 13.4-inch                   | 1         | 2.63%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 1         | 2.63%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 14        | 36.84%  |
| 1366x768 (WXGA) | 11        | 28.95%  |
| 1280x800 (WXGA) | 6         | 15.79%  |
| 3840x2160 (4K)  | 2         | 5.26%   |
| 1600x900 (HD+)  | 2         | 5.26%   |
| 3840x2400       | 1         | 2.63%   |
| 2560x1440 (QHD) | 1         | 2.63%   |
| 2256x1504       | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 13        | 34.21%  |
| 15     | 10        | 26.32%  |
| 12     | 9         | 23.68%  |
| 11     | 3         | 7.89%   |
| 28     | 1         | 2.63%   |
| 24     | 1         | 2.63%   |
| 14     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 50%     |
| 201-300     | 17        | 44.74%  |
| 601-700     | 1         | 2.63%   |
| 501-600     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 78.38%  |
| 16/10 | 7         | 18.92%  |
| 3/2   | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 34.21%  |
| 61-70          | 9         | 23.68%  |
| 91-100         | 8         | 21.05%  |
| 51-60          | 3         | 7.89%   |
| 101-110        | 2         | 5.26%   |
| 71-80          | 1         | 2.63%   |
| 351-500        | 1         | 2.63%   |
| 201-250        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 60.53%  |
| 161-240       | 5         | 13.16%  |
| 101-120       | 5         | 13.16%  |
| 51-100        | 3         | 7.89%   |
| More than 240 | 2         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 42        | 82.35%  |
| 0     | 8         | 15.69%  |
| 2     | 1         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 50%     |
| Realtek Semiconductor             | 18        | 23.08%  |
| Qualcomm Atheros                  | 7         | 8.97%   |
| Ericsson Business Mobile Networks | 3         | 3.85%   |
| Broadcom                          | 3         | 3.85%   |
| Marvell Technology Group          | 2         | 2.56%   |
| TP-Link                           | 1         | 1.28%   |
| Ralink Technology                 | 1         | 1.28%   |
| Nvidia                            | 1         | 1.28%   |
| Dell                              | 1         | 1.28%   |
| D-Link System                     | 1         | 1.28%   |
| D-Link                            | 1         | 1.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 13        | 12.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 5.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 5         | 4.85%   |
| Intel 82567LM Gigabit Network Connection                                    | 4         | 3.88%   |
| Intel Wireless 7260                                                         | 3         | 2.91%   |
| Intel Wi-Fi 6 AX201                                                         | 3         | 2.91%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 2.91%   |
| Intel Ultimate N WiFi Link 5300                                             | 3         | 2.91%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 2.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 2         | 1.94%   |
| Intel Wireless-AC 9260                                                      | 2         | 1.94%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 1.94%   |
| Intel Ethernet Connection (4) I219-V                                        | 2         | 1.94%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 1.94%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 0.97%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 1         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 1         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 0.97%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 0.97%   |
| Nvidia MCP79 Ethernet                                                       | 1         | 0.97%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                     | 1         | 0.97%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 0.97%   |
| Intel Wireless 8260                                                         | 1         | 0.97%   |
| Intel Wireless 7265                                                         | 1         | 0.97%   |
| Intel Wireless 3165                                                         | 1         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 1         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 1         | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 68.52%  |
| Qualcomm Atheros      | 5         | 9.26%   |
| Realtek Semiconductor | 4         | 7.41%   |
| Broadcom              | 3         | 5.56%   |
| TP-Link               | 1         | 1.85%   |
| Ralink Technology     | 1         | 1.85%   |
| Dell                  | 1         | 1.85%   |
| D-Link System         | 1         | 1.85%   |
| D-Link                | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 5         | 9.26%   |
| Intel Wireless 7260                                                               | 3         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                               | 3         | 5.56%   |
| Intel Wi-Fi 6 AX200                                                               | 3         | 5.56%   |
| Intel Ultimate N WiFi Link 5300                                                   | 3         | 5.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 2         | 3.7%    |
| Intel Wireless-AC 9260                                                            | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                                        | 2         | 3.7%    |
| Intel Centrino Advanced-N 6200                                                    | 2         | 3.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1         | 1.85%   |
| Ralink RT5370 Wireless Adapter                                                    | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)           | 1         | 1.85%   |
| Intel Wireless 8260                                                               | 1         | 1.85%   |
| Intel Wireless 7265                                                               | 1         | 1.85%   |
| Intel Wireless 3165                                                               | 1         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                    | 1         | 1.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                           | 1         | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                     | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                             | 1         | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                                   | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                 | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 1         | 1.85%   |
| Intel Centrino Wireless-N 2230                                                    | 1         | 1.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                     | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                    | 1         | 1.85%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                           | 1         | 1.85%   |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1         | 1.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                                    | 1         | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                            | 1         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                                     | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 22        | 48.89%  |
| Realtek Semiconductor    | 16        | 35.56%  |
| Qualcomm Atheros         | 3         | 6.67%   |
| Marvell Technology Group | 2         | 4.44%   |
| Nvidia                   | 1         | 2.22%   |
| Broadcom                 | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 28.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 13.33%  |
| Intel 82567LM Gigabit Network Connection                          | 4         | 8.89%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.44%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 4.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.22%   |
| Nvidia MCP79 Ethernet                                             | 1         | 2.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.22%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 2.22%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 49.48%  |
| Ethernet | 45        | 46.39%  |
| Modem    | 2         | 2.06%   |
| Unknown  | 2         | 2.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 70.37%  |
| Ethernet | 16        | 29.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 86%     |
| 1     | 7         | 14%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 50        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 61.29%  |
| Broadcom                        | 4         | 12.9%   |
| Apple                           | 2         | 6.45%   |
| Alps Electric                   | 2         | 6.45%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| Lite-On Technology              | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 22.58%  |
| Intel AX201 Bluetooth                               | 4         | 12.9%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.45%   |
| Intel AX200 Bluetooth                               | 2         | 6.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 6.45%   |
| Alps Electric UGTZ4 Bluetooth                       | 2         | 6.45%   |
| Realtek  Bluetooth Adapter                          | 1         | 3.23%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 3.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.23%   |
| Broadcom BCM43142A0 Bluetooth Module                | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 3.23%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 3.23%   |
| Apple Bluetooth Host Controller                     | 1         | 3.23%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 80%     |
| AMD    | 6         | 10.91%  |
| Nvidia | 5         | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 9.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 7.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 6.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 4.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 3.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 3.17%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.17%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 2         | 3.17%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.17%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.17%   |
| Nvidia unknown                                                             | 1         | 1.59%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.59%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.59%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.59%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.59%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.59%   |
| AMD High Definition Audio Controller                                       | 1         | 1.59%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.59%   |

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
| SK hynix            | 1         | 7.69%   |
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
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 7.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s       | 1         | 7.14%   |
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
| Chicony Electronics           | 9         | 29.03%  |
| Acer                          | 7         | 22.58%  |
| Realtek Semiconductor         | 2         | 6.45%   |
| Microdia                      | 2         | 6.45%   |
| IMC Networks                  | 2         | 6.45%   |
| Syntek                        | 1         | 3.23%   |
| Sunplus Innovation Technology | 1         | 3.23%   |
| Silicon Motion                | 1         | 3.23%   |
| Ricoh                         | 1         | 3.23%   |
| Luxvisions Innotech Limited   | 1         | 3.23%   |
| Lite-On Technology            | 1         | 3.23%   |
| Apple                         | 1         | 3.23%   |
| ALi                           | 1         | 3.23%   |
| Alcor Micro                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 3         | 9.68%   |
| Acer Integrated Camera                        | 3         | 9.68%   |
| Microdia Integrated_Webcam_HD                 | 2         | 6.45%   |
| IMC Networks Integrated Camera                | 2         | 6.45%   |
| Syntek Lenovo EasyCamera                      | 1         | 3.23%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 3.23%   |
| Silicon Motion Web Camera                     | 1         | 3.23%   |
| Ricoh Integrated Webcam                       | 1         | 3.23%   |
| Realtek USB 2 Webcam                          | 1         | 3.23%   |
| Realtek Integrated Webcam                     | 1         | 3.23%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 3.23%   |
| Lite-On Integrated Camera                     | 1         | 3.23%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 3.23%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 3.23%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 3.23%   |
| Chicony HP Webcam [2 MP]                      | 1         | 3.23%   |
| Chicony HP Webcam [2 MP Macro]                | 1         | 3.23%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 3.23%   |
| Apple FaceTime HD Camera                      | 1         | 3.23%   |
| ALi WebCam                                    | 1         | 3.23%   |
| Alcor Micro USB 2.0 Camera                    | 1         | 3.23%   |
| Acer ThinkPad P50 Integrated Camera           | 1         | 3.23%   |
| Acer ThinkPad Integrated Camera               | 1         | 3.23%   |
| Acer SunplusIT Integrated Camera              | 1         | 3.23%   |
| Acer EasyCamera                               | 1         | 3.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Synaptics                  | 2         | 18.18%  |
| STMicroelectronics         | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Samsung Electronics        | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 9.09%   |
| Synaptics product 0x00be                               | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 9.09%   |
| Samsung Fingerprint Device                             | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |

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
| 1     | 25        | 47.17%  |
| 2     | 14        | 26.42%  |
| 4     | 5         | 9.43%   |
| 0     | 5         | 9.43%   |
| 3     | 3         | 5.66%   |
| 5     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 37        | 52.11%  |
| Graphics card            | 13        | 18.31%  |
| Net/wireless             | 8         | 11.27%  |
| Firewire controller      | 7         | 9.86%   |
| Sound                    | 3         | 4.23%   |
| Storage/ata              | 1         | 1.41%   |
| Network                  | 1         | 1.41%   |
| Modem                    | 1         | 1.41%   |

