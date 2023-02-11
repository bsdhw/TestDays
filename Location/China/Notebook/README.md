BSD in China - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in China.

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

Total: 78

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Acidanther... | MacBookPro15,1              | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Unknown       | Unknown                     | [3efcb47333](https://bsd-hardware.info/?probe=3efcb47333) | Jul 31, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Lenovo        | B470 HuronRiver Platform    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| Dell          | Latitude 5290               | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HUAWEI        | NBLL-WXX9                   | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Panasonic     | CF-B11JWCYS                 | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| HASEE Comp... | CW35S                       | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| WOOKING       | X5                          | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| Sony          | SVP13225SCBI                | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| Toshiba       | Satellite Pro L510          | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| Sony          | SVS1511AJB                  | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | F83VD                       | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| HUAWEI        | HLY-WX9XX                   | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| NEC Comput... | PC-VK17HBBCD                | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [2b05811c5f](https://bsd-hardware.info/?probe=2b05811c5f) | Jun 18, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Unknown       | Unknown                     | [def6a6516d](https://bsd-hardware.info/?probe=def6a6516d) | Apr 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| Notebook      | W65KJ1_KK1                  | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| Dell          | Latitude E5570              | [da926f1065](https://bsd-hardware.info/?probe=da926f1065) | Apr 11, 2021 |
| ASUSTek       | X540UP                      | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Lenovo        | ThinkPad E460 20ETA00DCD    | [0a6985f078](https://bsd-hardware.info/?probe=0a6985f078) | Mar 13, 2021 |
| Lenovo        | B41-80 80LG                 | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| Dell          | Precision 3541              | [d07a4dc2c7](https://bsd-hardware.info/?probe=d07a4dc2c7) | Mar 04, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| Lenovo        | G470 20078                  | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| Unknown       | Unknown                     | [5068d55701](https://bsd-hardware.info/?probe=5068d55701) | Feb 16, 2021 |
| Dell          | Inspiron N4030              | [419b61f1d8](https://bsd-hardware.info/?probe=419b61f1d8) | Feb 15, 2021 |
| Dell          | Inspiron N4030              | [62d7379d24](https://bsd-hardware.info/?probe=62d7379d24) | Feb 14, 2021 |
| Unknown       | Unknown                     | [5550236531](https://bsd-hardware.info/?probe=5550236531) | Feb 08, 2021 |
| Apple         | MacBookPro11,4              | [dad5d994a0](https://bsd-hardware.info/?probe=dad5d994a0) | Jan 20, 2021 |
| Lenovo        | ThinkPad T580 20L9000ECD    | [771d8ead80](https://bsd-hardware.info/?probe=771d8ead80) | Nov 10, 2020 |
| Lenovo        | ThinkPad SL410 28747GC      | [3b62dd9788](https://bsd-hardware.info/?probe=3b62dd9788) | Jul 19, 2020 |
| Unknown       | Unknown                     | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 8         | 12.5%   |
| FreeBSD 13.1         | 7         | 10.94%  |
| helloSystem 0.5.0    | 5         | 7.81%   |
| helloSystem 0.8.0    | 4         | 6.25%   |
| FreeBSD 14.0-CURRENT | 4         | 6.25%   |
| FreeBSD 12.2         | 4         | 6.25%   |
| helloSystem 0.6.0    | 3         | 4.69%   |
| helloSystem 0.4.0    | 3         | 4.69%   |
| OPNsense 21.1.1      | 2         | 3.13%   |
| NomadBSD 5806f915    | 2         | 3.13%   |
| GhostBSD 21.08.27    | 2         | 3.13%   |
| FreeBSD 13.0-p7      | 2         | 3.13%   |
| FreeBSD 13.0-p4      | 2         | 3.13%   |
| FreeBSD 13.0         | 2         | 3.13%   |
| OPNsense 22.7        | 1         | 1.56%   |
| OPNsense 21.1        | 1         | 1.56%   |
| OPNsense 20.7.8      | 1         | 1.56%   |
| OpenBSD 7.0          | 1         | 1.56%   |
| NomadBSD 1.3.1       | 1         | 1.56%   |
| FreeBSD 13.1-RC3     | 1         | 1.56%   |
| FreeBSD 13.1-p5      | 1         | 1.56%   |
| FreeBSD 13.1-p2      | 1         | 1.56%   |
| FreeBSD 13.0-STABLE  | 1         | 1.56%   |
| FreeBSD 13.0-RC1     | 1         | 1.56%   |
| FreeBSD 13.0-p3      | 1         | 1.56%   |
| FreeBSD 13.0-p2      | 1         | 1.56%   |
| FreeBSD 12.2-p10     | 1         | 1.56%   |
| FreeBSD 12.1-p7      | 1         | 1.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 29        | 47.54%  |
| helloSystem | 22        | 36.07%  |
| OPNsense    | 4         | 6.56%   |
| NomadBSD    | 3         | 4.92%   |
| GhostBSD    | 2         | 3.28%   |
| OpenBSD     | 1         | 1.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 60        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 21        | 32.81%  |
| XFCE         | 11        | 17.19%  |
| KDE5         | 7         | 10.94%  |
| Console      | 7         | 10.94%  |
| GNOME        | 5         | 7.81%   |
| i3           | 4         | 6.25%   |
| Openbox      | 3         | 4.69%   |
| MATE         | 3         | 4.69%   |
| TWM          | 2         | 3.13%   |
| fvwm         | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 87.1%   |
| Console | 7         | 11.29%  |
| Wayland | 1         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 30        | 47.62%  |
| Console | 13        | 20.63%  |
| SDDM    | 6         | 9.52%   |
| LightDM | 6         | 9.52%   |
| GDM     | 5         | 7.94%   |
| XDM     | 3         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 26        | 40.63%  |
| zh_CN        | 14        | 21.88%  |
| C            | 12        | 18.75%  |
| Unknown      | 11        | 17.19%  |
| zh_CN.GB2312 | 1         | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 53        | 86.89%  |
| BIOS | 8         | 13.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 36        | 58.06%  |
| Ufs    | 18        | 29.03%  |
| Cd9660 | 7         | 11.29%  |
| Ffs    | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 56        | 91.8%   |
| MBR  | 5         | 8.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 25        | 41.67%  |
| Dell                | 6         | 10%     |
| ASUSTek Computer    | 4         | 6.67%   |
| Unknown             | 4         | 6.67%   |
| Hewlett-Packard     | 3         | 5%      |
| Sony                | 2         | 3.33%   |
| Notebook            | 2         | 3.33%   |
| HUAWEI              | 2         | 3.33%   |
| HASEE Computer      | 2         | 3.33%   |
| WOOKING             | 1         | 1.67%   |
| Toshiba             | 1         | 1.67%   |
| Timi                | 1         | 1.67%   |
| Samsung Electronics | 1         | 1.67%   |
| Panasonic           | 1         | 1.67%   |
| NEC Computers       | 1         | 1.67%   |
| Google              | 1         | 1.67%   |
| Apple               | 1         | 1.67%   |
| Acidanthera         | 1         | 1.67%   |
| Acer                | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 4         | 6.67%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 3.33%   |
| WOOKING X5                                  | 1         | 1.67%   |
| Toshiba Satellite Pro L510                  | 1         | 1.67%   |
| Timi RedmiBook Pro 15                       | 1         | 1.67%   |
| Sony SVS1511AJB                             | 1         | 1.67%   |
| Sony SVP13225SCBI                           | 1         | 1.67%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.67%   |
| Panasonic CF-B11JWCYS                       | 1         | 1.67%   |
| Notebook W65KJ1_KK1                         | 1         | 1.67%   |
| Notebook W650DC,DD                          | 1         | 1.67%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 1.67%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 1.67%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.67%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 1.67%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 1.67%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 3448AWU           | 1         | 1.67%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 1.67%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 1.67%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 1.67%   |
| Lenovo ThinkPad T430 2342AG4                | 1         | 1.67%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 1.67%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.67%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 1.67%   |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 1.67%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 1.67%   |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 1.67%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.67%   |
| Lenovo G480 20149                           | 1         | 1.67%   |
| Lenovo G470 20078                           | 1         | 1.67%   |
| Lenovo B590 20208                           | 1         | 1.67%   |
| Lenovo B470 HuronRiver Platform             | 1         | 1.67%   |
| Lenovo B41-80 80LG                          | 1         | 1.67%   |
| HUAWEI NBLL-WXX9                            | 1         | 1.67%   |
| HUAWEI HLY-WX9XX                            | 1         | 1.67%   |
| HP ProBook 440 G6                           | 1         | 1.67%   |
| HP ProBook 430 G4                           | 1         | 1.67%   |
| HP Pavilion Gaming Laptop 15-dk0xxx         | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 15        | 25%     |
| Dell Latitude              | 4         | 6.67%   |
| Unknown                    | 4         | 6.67%   |
| HP ProBook                 | 2         | 3.33%   |
| WOOKING X5                 | 1         | 1.67%   |
| Toshiba Satellite          | 1         | 1.67%   |
| Timi RedmiBook             | 1         | 1.67%   |
| Sony SVS1511AJB            | 1         | 1.67%   |
| Sony SVP13225SCBI          | 1         | 1.67%   |
| Samsung 3570R              | 1         | 1.67%   |
| Panasonic CF-B11JWCYS      | 1         | 1.67%   |
| Notebook W65KJ1            | 1         | 1.67%   |
| Notebook W650DC            | 1         | 1.67%   |
| NEC Computers PC-VK17HBBCD | 1         | 1.67%   |
| Lenovo ZhaoYang            | 1         | 1.67%   |
| Lenovo XiaoXinPro-13ARE    | 1         | 1.67%   |
| Lenovo XiaoXinPro-13API    | 1         | 1.67%   |
| Lenovo Rescuer-15ISK       | 1         | 1.67%   |
| Lenovo IdeaPad             | 1         | 1.67%   |
| Lenovo G480                | 1         | 1.67%   |
| Lenovo G470                | 1         | 1.67%   |
| Lenovo B590                | 1         | 1.67%   |
| Lenovo B470                | 1         | 1.67%   |
| Lenovo B41-80              | 1         | 1.67%   |
| HUAWEI NBLL-WXX9           | 1         | 1.67%   |
| HUAWEI HLY-WX9XX           | 1         | 1.67%   |
| HP Pavilion                | 1         | 1.67%   |
| HASEE N95XKP6              | 1         | 1.67%   |
| HASEE CW35S                | 1         | 1.67%   |
| Google Edgar               | 1         | 1.67%   |
| Dell Precision             | 1         | 1.67%   |
| Dell Inspiron              | 1         | 1.67%   |
| ASUS X540UP                | 1         | 1.67%   |
| ASUS X455LJ                | 1         | 1.67%   |
| ASUS X441UV                | 1         | 1.67%   |
| ASUS F83VD                 | 1         | 1.67%   |
| Apple MacBookPro11         | 1         | 1.67%   |
| Acidanthera MacBookPro15   | 1         | 1.67%   |
| Acer Aspire                | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 13.33%  |
| 2017 | 7         | 11.67%  |
| 2013 | 7         | 11.67%  |
| 2012 | 7         | 11.67%  |
| 2022 | 6         | 10%     |
| 2019 | 5         | 8.33%   |
| 2018 | 4         | 6.67%   |
| 2016 | 4         | 6.67%   |
| 2011 | 4         | 6.67%   |
| 2020 | 3         | 5%      |
| 2015 | 2         | 3.33%   |
| 2009 | 2         | 3.33%   |
| 2010 | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 22        | 36.67%  |
| 4.01-8.0    | 18        | 30%     |
| 16.01-24.0  | 12        | 20%     |
| 24.01-32.0  | 4         | 6.67%   |
| 32.01-64.0  | 3         | 5%      |
| 64.01-256.0 | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 33        | 55%     |
| 0.51-1.0 | 15        | 25%     |
| 1.01-2.0 | 11        | 18.33%  |
| 2.01-3.0 | 1         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 64.52%  |
| 2      | 15        | 24.19%  |
| 0      | 4         | 6.45%   |
| 3      | 3         | 4.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 43        | 71.67%  |
| Yes       | 17        | 28.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 81.67%  |
| No        | 11        | 18.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 95%     |
| No        | 3         | 5%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 71.67%  |
| No        | 17        | 28.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 60        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Guangzhou               | 7         | 11.29%  |
| Shanghai                | 6         | 9.68%   |
| Beijing                 | 6         | 9.68%   |
| Shenzhen                | 5         | 8.06%   |
| Zhengzhou               | 2         | 3.23%   |
| Wuhan                   | 2         | 3.23%   |
| Nanjing                 | 2         | 3.23%   |
| Chengdu                 | 2         | 3.23%   |
| Changzhou               | 2         | 3.23%   |
| Zhumadian               | 1         | 1.61%   |
| Zhaoqing                | 1         | 1.61%   |
| Yichun                  | 1         | 1.61%   |
| Xiamen                  | 1         | 1.61%   |
| Xi'an                   | 1         | 1.61%   |
| Wuxi                    | 1         | 1.61%   |
| Weifang                 | 1         | 1.61%   |
| Shizishan               | 1         | 1.61%   |
| Shantou                 | 1         | 1.61%   |
| Qiqihar                 | 1         | 1.61%   |
| Qinnan                  | 1         | 1.61%   |
| Putian                  | 1         | 1.61%   |
| Pudong                  | 1         | 1.61%   |
| Linyi                   | 1         | 1.61%   |
| Lanzhou                 | 1         | 1.61%   |
| Jinniu                  | 1         | 1.61%   |
| Jilin City              | 1         | 1.61%   |
| Jiangbei                | 1         | 1.61%   |
| Huangpu                 | 1         | 1.61%   |
| Hongyuan                | 1         | 1.61%   |
| Hohhot                  | 1         | 1.61%   |
| Hangzhou                | 1         | 1.61%   |
| Guangzhou Shi           | 1         | 1.61%   |
| Dongguan                | 1         | 1.61%   |
| Dangchang Chengguanzhen | 1         | 1.61%   |
| Chengxiang              | 1         | 1.61%   |
| Changchun               | 1         | 1.61%   |
| Baiyun                  | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 17.33%  |
| Seagate             | 9         | 10     | 12%     |
| WDC                 | 8         | 11     | 10.67%  |
| Toshiba             | 6         | 7      | 8%      |
| Intel               | 3         | 4      | 4%      |
| Hikvision           | 3         | 3      | 4%      |
| HGST                | 3         | 3      | 4%      |
| SK hynix            | 2         | 2      | 2.67%   |
| SanDisk             | 2         | 2      | 2.67%   |
| Plextor             | 2         | 2      | 2.67%   |
| Netac               | 2         | 2      | 2.67%   |
| Lenovo              | 2         | 2      | 2.67%   |
| KIOXIA              | 2         | 2      | 2.67%   |
| Kingston            | 2         | 2      | 2.67%   |
| Hitachi             | 2         | 2      | 2.67%   |
| Crucial             | 2         | 2      | 2.67%   |
| Silicon Motion      | 1         | 1      | 1.33%   |
| Pioneer             | 1         | 1      | 1.33%   |
| Phison              | 1         | 1      | 1.33%   |
| Lexar               | 1         | 1      | 1.33%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| Colorful            | 1         | 1      | 1.33%   |
| China               | 1         | 2      | 1.33%   |
| BR                  | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |
| A-DATA Technology   | 1         | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB                  | 2         | 2.53%   |
| SanDisk SSD U100 24GB                           | 2         | 2.53%   |
| Samsung SSD 970 EVO Plus 1TB                    | 2         | 2.53%   |
| Samsung SSD 870 EVO 1TB                         | 2         | 2.53%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 2.53%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                  | 2         | 2.53%   |
| Hikvision HS-SSD-C2000ECO 1024G                 | 2         | 2.53%   |
| HGST HTS541010B7E610 1TB                        | 2         | 2.53%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 1.27%   |
| WDC WDS100T3X0C-00SJG0 1TB                      | 1         | 1.27%   |
| WDC WD3200BPVT-75ZEST0 320GB                    | 1         | 1.27%   |
| WDC WD2500BEVS-08VAT2 250GB                     | 1         | 1.27%   |
| WDC WD20SPZX-75UA7T0 2TB                        | 1         | 1.27%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 1.27%   |
| WDC WD10JPVX-00JC3T0 1TB                        | 1         | 1.27%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB            | 1         | 1.27%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB            | 1         | 1.27%   |
| Toshiba THNSNF128GCSS 128GB                     | 1         | 1.27%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.27%   |
| Toshiba MQ02ABF050H-SSHD-8GB                    | 1         | 1.27%   |
| Toshiba MQ01ACF050 500GB                        | 1         | 1.27%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.27%   |
| Toshiba KXG6APNV2T04 2TB                        | 1         | 1.27%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB         | 1         | 1.27%   |
| SK hynix BC511 NVMe 512GB                       | 1         | 1.27%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1.27%   |
| Seagate ST500LM030-2E717D 500GB                 | 1         | 1.27%   |
| Seagate ST320LT007-9ZV142 320GB                 | 1         | 1.27%   |
| Seagate ST2000LM015-2E8174 2TB                  | 1         | 1.27%   |
| Seagate ST2000LM007-1R8174 2TB                  | 1         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB                  | 1         | 1.27%   |
| Samsung SSD 850 EVO 120GB                       | 1         | 1.27%   |
| Samsung MZVLB512HBJQ-000L2 512GB                | 1         | 1.27%   |
| Samsung MZVLB512HBJQ-000H1 512GB                | 1         | 1.27%   |
| Samsung MZVLB512HAJQ-00000 512GB                | 1         | 1.27%   |
| Samsung MZNTY256HDHP-000L2 256GB                | 1         | 1.27%   |
| Samsung MZNTE128HMGR-000SO 128GB                | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 39.13%  |
| WDC     | 5         | 5      | 21.74%  |
| Toshiba | 4         | 4      | 17.39%  |
| HGST    | 3         | 3      | 13.04%  |
| Hitachi | 2         | 2      | 8.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 21.88%  |
| Intel               | 3         | 4      | 9.38%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Plextor             | 2         | 2      | 6.25%   |
| Netac               | 2         | 2      | 6.25%   |
| Lenovo              | 2         | 2      | 6.25%   |
| Kingston            | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| Toshiba             | 1         | 1      | 3.13%   |
| Phison              | 1         | 1      | 3.13%   |
| Lexar               | 1         | 1      | 3.13%   |
| KIOXIA-EXCERIA      | 1         | 1      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 2      | 3.13%   |
| BR                  | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 30        | 34     | 42.25%  |
| HDD  | 21        | 24     | 29.58%  |
| NVMe | 20        | 26     | 28.17%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 58     | 68.75%  |
| NVMe | 20        | 26     | 31.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 40     | 64.58%  |
| 0.51-1.0   | 14        | 15     | 29.17%  |
| 1.01-2.0   | 3         | 3      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 17        | 26.98%  |
| 1-20       | 17        | 26.98%  |
| 101-250    | 11        | 17.46%  |
| 501-1000   | 5         | 7.94%   |
| 21-50      | 4         | 6.35%   |
| 1001-2000  | 4         | 6.35%   |
| 51-100     | 3         | 4.76%   |
| Unknown    | 2         | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 48        | 78.69%  |
| 21-50   | 7         | 11.48%  |
| 251-500 | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| 101-250 | 1         | 1.64%   |
| 51-100  | 1         | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 16.67%  |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 16.67%  |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 16.67%  |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 16.67%  |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 16.67%  |
| China JWX 16GB MSATA            | 1         | 2      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |
| China   | 1         | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 83.33%  |
| SSD  | 1         | 2      | 16.67%  |

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
| Works   | 54        | 77     | 90%     |
| Malfunc | 6         | 7      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 63.38%  |
| Samsung Electronics          | 9         | 12.68%  |
| Silicon Motion               | 3         | 4.23%   |
| SanDisk                      | 3         | 4.23%   |
| SK hynix                     | 2         | 2.82%   |
| MAXIO Technology (Hangzhou)  | 2         | 2.82%   |
| KIOXIA                       | 2         | 2.82%   |
| AMD                          | 2         | 2.82%   |
| Toshiba                      | 1         | 1.41%   |
| Shenzhen Longsys Electronics | 1         | 1.41%   |
| Micron/Crucial Technology    | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 13.7%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 12.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 6.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 4.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 4.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.74%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2         | 2.74%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.74%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.37%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.37%   |
| SK hynix BC511                                                                 | 1         | 1.37%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.37%   |
| Shenzhen Longsys unknown                                                       | 1         | 1.37%   |
| Samsung SM951 AHCI                                                             | 1         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.37%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.37%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.37%   |
| Unknown                                                                        | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 45        | 65.22%  |
| NVMe | 20        | 28.99%  |
| RAID | 2         | 2.9%    |
| IDE  | 2         | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 90%     |
| AMD    | 6         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 5%      |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 5%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 5%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.33%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 3.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 3.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 3.33%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 3.33%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 1.67%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 1.67%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1.67%   |
| Intel CPU Version                             | 1         | 1.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.67%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.67%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 1.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.67%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.67%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 1.67%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.67%   |
| Intel Core i7-2637M CPU                       | 1         | 1.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.67%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.67%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.67%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.67%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.67%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.67%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 1.67%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.67%   |
| Intel Core i3 CPU M 380 @ 2.53GH              | 1         | 1.67%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 38.33%  |
| Intel Core i7           | 11        | 18.33%  |
| Intel Core i3           | 7         | 11.67%  |
| Other                   | 6         | 10%     |
| Intel Celeron           | 3         | 5%      |
| AMD Ryzen 5             | 3         | 5%      |
| Intel Pentium           | 2         | 3.33%   |
| Intel Xeon              | 1         | 1.67%   |
| Intel Core 2 Duo        | 1         | 1.67%   |
| Intel Celeron Dual-Core | 1         | 1.67%   |
| AMD Ryzen 9             | 1         | 1.67%   |
| AMD Ryzen 7             | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 33        | 55%     |
| 4       | 18        | 30%     |
| 6       | 4         | 6.67%   |
| 8       | 2         | 3.33%   |
| 24      | 1         | 1.67%   |
| 16      | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 70%     |
| 1       | 17        | 28.33%  |
| Unknown | 1         | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 15        | 25%     |
| Skylake     | 8         | 13.33%  |
| SandyBridge | 8         | 13.33%  |
| IvyBridge   | 8         | 13.33%  |
| TigerLake   | 4         | 6.67%   |
| Haswell     | 4         | 6.67%   |
| Penryn      | 3         | 5%      |
| Zen+        | 2         | 3.33%   |
| Zen 2       | 2         | 3.33%   |
| Zen 3       | 1         | 1.67%   |
| Westmere    | 1         | 1.67%   |
| Silvermont  | 1         | 1.67%   |
| K10         | 1         | 1.67%   |
| CometLake   | 1         | 1.67%   |
| Broadwell   | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 60%     |
| Nvidia | 22        | 25.88%  |
| AMD    | 12        | 14.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 8         | 9.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 8.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 4.71%   |
| Intel HD Graphics 620                                                         | 3         | 3.53%   |
| Intel HD Graphics 530                                                         | 3         | 3.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 3.53%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.35%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 2.35%   |
| Intel UHD Graphics 620                                                        | 2         | 2.35%   |
| Intel HD Graphics 630                                                         | 2         | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 2.35%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.35%   |
| AMD Renoir                                                                    | 2         | 2.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.35%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 1.18%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.18%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 1         | 1.18%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.18%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 1.18%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.18%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 1.18%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.18%   |
| Nvidia GK107M [GeForce GT 640M LE]                                            | 1         | 1.18%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 1.18%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.18%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 1.18%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.18%   |
| Nvidia G96CM [GeForce GT 220M]                                                | 1         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.18%   |
| Intel HD Graphics P630                                                        | 1         | 1.18%   |
| Intel HD Graphics 5500                                                        | 1         | 1.18%   |
| Intel HD Graphics 510                                                         | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 41.67%  |
| Intel + Nvidia | 19        | 31.67%  |
| Intel + AMD    | 6         | 10%     |
| 1 x AMD        | 6         | 10%     |
| 1 x Nvidia     | 3         | 5%      |
| 2 x Intel      | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 85%     |
| Proprietary | 7         | 11.67%  |
| Unknown     | 2         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 83.61%  |
| 0.51-1.0   | 4         | 6.56%   |
| 0.01-0.5   | 4         | 6.56%   |
| 7.01-8.0   | 1         | 1.64%   |
| 1.01-2.0   | 1         | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 23.91%  |
| Chimei Innolux          | 7         | 15.22%  |
| BOE                     | 7         | 15.22%  |
| AU Optronics            | 7         | 15.22%  |
| Samsung Electronics     | 2         | 4.35%   |
| PANDA                   | 2         | 4.35%   |
| Lenovo                  | 2         | 4.35%   |
| CSO                     | 2         | 4.35%   |
| Chi Mei Optoelectronics | 2         | 4.35%   |
| TMX                     | 1         | 2.17%   |
| Panasonic               | 1         | 2.17%   |
| Dell                    | 1         | 2.17%   |
| Apple                   | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 2         | 4.35%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 4.35%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 2.17%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 2.17%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 2.17%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 2.17%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                    | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 2.17%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE0877 1920x1080 310x170mm 13.9-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE06B9 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE065D 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 290x170mm 13.2-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO363C 1366x768 310x170mm 13.9-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 39.13%  |
| 1366x768 (WXGA)   | 18        | 39.13%  |
| 1600x900 (HD+)    | 3         | 6.52%   |
| 2560x1600         | 2         | 4.35%   |
| 3200x2000         | 1         | 2.17%   |
| 2880x1800         | 1         | 2.17%   |
| 2880x1620         | 1         | 2.17%   |
| 2560x1440 (QHD)   | 1         | 2.17%   |
| 1920x1200 (WUXGA) | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 22        | 47.83%  |
| 15     | 19        | 41.3%   |
| 12     | 2         | 4.35%   |
| 24     | 1         | 2.17%   |
| 16     | 1         | 2.17%   |
| 14     | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 78.26%  |
| 201-300     | 8         | 17.39%  |
| 501-600     | 1         | 2.17%   |
| 351-400     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 88.89%  |
| 16/10 | 5         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 20        | 43.48%  |
| 91-100         | 15        | 32.61%  |
| 71-80          | 3         | 6.52%   |
| 101-110        | 3         | 6.52%   |
| 61-70          | 2         | 4.35%   |
| 111-120        | 2         | 4.35%   |
| 201-250        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 47.83%  |
| 101-120 | 14        | 30.43%  |
| 161-240 | 8         | 17.39%  |
| 51-100  | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 77.05%  |
| 0     | 13        | 21.31%  |
| 2     | 1         | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 46.59%  |
| Realtek Semiconductor | 28        | 31.82%  |
| Qualcomm Atheros      | 11        | 12.5%   |
| Broadcom              | 6         | 6.82%   |
| Qualcomm              | 1         | 1.14%   |
| Edimax Technology     | 1         | 1.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 18.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 3.64%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 3.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 3.64%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.73%   |
| Intel Wireless 8260                                               | 3         | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.82%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 1.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 1.82%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.91%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.91%   |
| Intel Wireless-AC 9260                                            | 1         | 0.91%   |
| Intel Wireless 7265                                               | 1         | 0.91%   |
| Intel Wireless 7260                                               | 1         | 0.91%   |
| Intel Wireless 3165                                               | 1         | 0.91%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.91%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 61.02%  |
| Qualcomm Atheros      | 10        | 16.95%  |
| Realtek Semiconductor | 7         | 11.86%  |
| Broadcom              | 5         | 8.47%   |
| Edimax Technology     | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 6.67%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 6.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 6.67%   |
| Intel Wireless 8265 / 8275                                        | 3         | 5%      |
| Intel Wireless 8260                                               | 3         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 5%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.33%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 3.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.67%   |
| Intel Wireless-AC 9260                                            | 1         | 1.67%   |
| Intel Wireless 7265                                               | 1         | 1.67%   |
| Intel Wireless 7260                                               | 1         | 1.67%   |
| Intel Wireless 3165                                               | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.67%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.67%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.67%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 50%     |
| Intel                 | 18        | 36%     |
| Qualcomm Atheros      | 4         | 8%      |
| Broadcom              | 2         | 4%      |
| Qualcomm              | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 10%     |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4%      |
| Intel 82583V Gigabit Network Connection                           | 2         | 4%      |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 2%      |
| Intel I211 Gigabit Network Connection                             | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2%      |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2%      |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2%      |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2%      |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2%      |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 53.77%  |
| Ethernet | 49        | 46.23%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 53.16%  |
| WiFi     | 37        | 46.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 75%     |
| 1     | 12        | 20%     |
| 6     | 3         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 93.33%  |
| Yes  | 4         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 60.47%  |
| Broadcom                        | 4         | 9.3%    |
| Qualcomm Atheros Communications | 2         | 4.65%   |
| Lite-On Technology              | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| Cambridge Silicon Radio         | 2         | 4.65%   |
| Apple                           | 2         | 4.65%   |
| Realtek Semiconductor           | 1         | 2.33%   |
| Realtek                         | 1         | 2.33%   |
| IMC Networks                    | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 25.58%  |
| Intel AX201 Bluetooth                               | 6         | 13.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 9.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 9.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.65%   |
| Intel AX200 Bluetooth                               | 2         | 4.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.65%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 2.33%   |
| Realtek Bluetooth Radio                             | 1         | 2.33%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.33%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 2.33%   |
| Lite-On BCM43142A0 Bluetooth Module                 | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.33%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.33%   |
| Apple Bluetooth Host Controller                     | 1         | 2.33%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 83.87%  |
| AMD    | 6         | 9.68%   |
| Nvidia | 4         | 6.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 15.49%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 12.68%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 5.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 5.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.82%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 2.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.41%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.41%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 30.77%  |
| SK hynix            | 20        | 25.64%  |
| Kingston            | 9         | 11.54%  |
| Micron Technology   | 7         | 8.97%   |
| Ramaxel Technology  | 4         | 5.13%   |
| Unknown             | 2         | 2.56%   |
| Transcend           | 2         | 2.56%   |
| Unknown             | 2         | 2.56%   |
| Unknown (8AFD)      | 1         | 1.28%   |
| Unknown (08B5)      | 1         | 1.28%   |
| Team                | 1         | 1.28%   |
| Nanya Technology    | 1         | 1.28%   |
| KingTiger           | 1         | 1.28%   |
| Elpida              | 1         | 1.28%   |
| Crucial             | 1         | 1.28%   |
| A-DATA Technology   | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 4.65%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 3         | 3.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.33%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 2         | 2.33%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 2         | 2.33%   |
| Unknown                                                      | 2         | 2.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.16%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 1.16%   |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s     | 1         | 1.16%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s  | 1         | 1.16%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 1.16%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s       | 1         | 1.16%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.16%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.16%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.16%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.16%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 1.16%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 1.16%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s          | 1         | 1.16%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s        | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.16%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 1.16%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.16%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 1.16%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s          | 1         | 1.16%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.16%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                  | 1         | 1.16%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s             | 1         | 1.16%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1333MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 45.9%   |
| DDR3    | 27        | 44.26%  |
| LPDDR4  | 2         | 3.28%   |
| LPDDR3  | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 83.33%  |
| Row Of Chips | 8         | 13.33%  |
| Chip         | 1         | 1.67%   |
| Unknown      | 1         | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 27        | 37.5%   |
| 4096  | 24        | 33.33%  |
| 2048  | 12        | 16.67%  |
| 16384 | 7         | 9.72%   |
| 32768 | 1         | 1.39%   |
| 1024  | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 22.86%  |
| 2667    | 11        | 15.71%  |
| 1333    | 10        | 14.29%  |
| 2400    | 7         | 10%     |
| 2133    | 7         | 10%     |
| 3200    | 6         | 8.57%   |
| 1334    | 3         | 4.29%   |
| 4267    | 2         | 2.86%   |
| 1067    | 2         | 2.86%   |
| 800     | 2         | 2.86%   |
| Unknown | 2         | 2.86%   |
| 1867    | 1         | 1.43%   |
| 533     | 1         | 1.43%   |

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
| Chicony Electronics                    | 15        | 30.61%  |
| Acer                                   | 7         | 14.29%  |
| Realtek Semiconductor                  | 6         | 12.24%  |
| Syntek                                 | 3         | 6.12%   |
| IMC Networks                           | 3         | 6.12%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Quanta                                 | 2         | 4.08%   |
| Microdia                               | 2         | 4.08%   |
| Lite-On Technology                     | 2         | 4.08%   |
| Silicon Motion                         | 1         | 2.04%   |
| Lenovo                                 | 1         | 2.04%   |
| Importek                               | 1         | 2.04%   |
| Genesys Logic                          | 1         | 2.04%   |
| Foxconn / Hon Hai                      | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.04%   |
| ALi                                    | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 5         | 10%     |
| Realtek Integrated_Webcam_HD                                               | 3         | 6%      |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 6%      |
| Chicony Lenovo EasyCamera                                                  | 3         | 6%      |
| Acer Integrated Camera                                                     | 3         | 6%      |
| Syntek Lenovo EasyCamera                                                   | 2         | 4%      |
| IMC Networks Integrated Camera                                             | 2         | 4%      |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 4%      |
| Chicony Chicony USB2.0 Camera                                              | 2         | 4%      |
| Acer ThinkPad Integrated Camera                                            | 2         | 4%      |
| Syntek Integrated Camera                                                   | 1         | 2%      |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2%      |
| Silicon Motion Realtek USB2.0 PC Camera                                    | 1         | 2%      |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 2%      |
| Realtek HD WebCam                                                          | 1         | 2%      |
| Realtek Front Camera                                                       | 1         | 2%      |
| Quanta Realtek DMFT - RGB                                                  | 1         | 2%      |
| Quanta ov9734_techfront_camera                                             | 1         | 2%      |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                              | 1         | 2%      |
| Lite-On Integrated Camera                                                  | 1         | 2%      |
| Lite-On HP HD Camera                                                       | 1         | 2%      |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 2%      |
| Importek USB 2.0 Camera                                                    | 1         | 2%      |
| IMC Networks Integrated Webcam                                             | 1         | 2%      |
| Genesys Logic Camera                                                       | 1         | 2%      |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2%      |
| Chicony Integrated IR Camera                                               | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| ALi Gateway Webcam                                                         | 1         | 2%      |
| Acer Lenovo Integrated Webcam                                              | 1         | 2%      |
| Acer Lenovo EasyCamera                                                     | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 60%     |
| Synaptics                  | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                            | 3         | 30%     |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 10%     |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 10%     |

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
| 2     | 18        | 30%     |
| 1     | 18        | 30%     |
| 3     | 15        | 25%     |
| 0     | 7         | 11.67%  |
| 4     | 2         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 49        | 48.51%  |
| Net/wireless             | 14        | 13.86%  |
| Card reader              | 14        | 13.86%  |
| Bluetooth                | 14        | 13.86%  |
| Fingerprint reader       | 10        | 9.9%    |

