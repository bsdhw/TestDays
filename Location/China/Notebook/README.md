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

Total: 72

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
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
| Lenovo        | ThinkPad E420 1141A83       | [9731048099](https://bsd-hardware.info/?probe=9731048099) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [03d4d9a468](https://bsd-hardware.info/?probe=03d4d9a468) | Feb 20, 2021 |
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
| helloSystem 0.7.0    | 5         | 9.09%   |
| helloSystem 0.5.0    | 5         | 9.09%   |
| FreeBSD 13.1         | 5         | 9.09%   |
| FreeBSD 14.0-CURRENT | 4         | 7.27%   |
| FreeBSD 12.2         | 4         | 7.27%   |
| helloSystem 0.6.0    | 3         | 5.45%   |
| helloSystem 0.4.0    | 3         | 5.45%   |
| OPNsense 21.1.1      | 2         | 3.64%   |
| NomadBSD 5806f915    | 2         | 3.64%   |
| helloSystem 0.8.0    | 2         | 3.64%   |
| GhostBSD 21.08.27    | 2         | 3.64%   |
| FreeBSD 13.0-p7      | 2         | 3.64%   |
| FreeBSD 13.0-p4      | 2         | 3.64%   |
| FreeBSD 13.0         | 2         | 3.64%   |
| OPNsense 22.7        | 1         | 1.82%   |
| OPNsense 21.1        | 1         | 1.82%   |
| OPNsense 20.7.8      | 1         | 1.82%   |
| OpenBSD 7.0          | 1         | 1.82%   |
| NomadBSD 1.3.1       | 1         | 1.82%   |
| FreeBSD 13.1-RC3     | 1         | 1.82%   |
| FreeBSD 13.0-STABLE  | 1         | 1.82%   |
| FreeBSD 13.0-RC1     | 1         | 1.82%   |
| FreeBSD 13.0-p3      | 1         | 1.82%   |
| FreeBSD 13.0-p2      | 1         | 1.82%   |
| FreeBSD 12.2-p10     | 1         | 1.82%   |
| FreeBSD 12.1-p7      | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 25        | 47.17%  |
| helloSystem | 18        | 33.96%  |
| OPNsense    | 4         | 7.55%   |
| NomadBSD    | 3         | 5.66%   |
| GhostBSD    | 2         | 3.77%   |
| OpenBSD     | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 17        | 30.36%  |
| XFCE         | 10        | 17.86%  |
| KDE5         | 7         | 12.5%   |
| Console      | 7         | 12.5%   |
| GNOME        | 5         | 8.93%   |
| Openbox      | 3         | 5.36%   |
| i3           | 3         | 5.36%   |
| MATE         | 2         | 3.57%   |
| TWM          | 1         | 1.79%   |
| fvwm         | 1         | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 85.19%  |
| Console | 7         | 12.96%  |
| Wayland | 1         | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 26        | 47.27%  |
| Console | 12        | 21.82%  |
| SDDM    | 5         | 9.09%   |
| LightDM | 5         | 9.09%   |
| GDM     | 5         | 9.09%   |
| XDM     | 2         | 3.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 21        | 38.18%  |
| zh_CN        | 13        | 23.64%  |
| C            | 10        | 18.18%  |
| Unknown      | 10        | 18.18%  |
| zh_CN.GB2312 | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 46        | 86.79%  |
| BIOS | 7         | 13.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 31        | 58.49%  |
| Ufs    | 17        | 32.08%  |
| Cd9660 | 4         | 7.55%   |
| Ffs    | 1         | 1.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 48        | 90.57%  |
| MBR  | 5         | 9.43%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 21        | 40.38%  |
| Dell             | 6         | 11.54%  |
| ASUSTek Computer | 4         | 7.69%   |
| Unknown          | 4         | 7.69%   |
| Hewlett-Packard  | 3         | 5.77%   |
| Sony             | 2         | 3.85%   |
| Notebook         | 2         | 3.85%   |
| HUAWEI           | 2         | 3.85%   |
| WOOKING          | 1         | 1.92%   |
| Toshiba          | 1         | 1.92%   |
| Timi             | 1         | 1.92%   |
| Panasonic        | 1         | 1.92%   |
| NEC Computers    | 1         | 1.92%   |
| HASEE Computer   | 1         | 1.92%   |
| Apple            | 1         | 1.92%   |
| Acer             | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 4         | 7.69%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 3.85%   |
| WOOKING X5                                  | 1         | 1.92%   |
| Toshiba Satellite Pro L510                  | 1         | 1.92%   |
| Timi RedmiBook Pro 15                       | 1         | 1.92%   |
| Sony SVS1511AJB                             | 1         | 1.92%   |
| Sony SVP13225SCBI                           | 1         | 1.92%   |
| Panasonic CF-B11JWCYS                       | 1         | 1.92%   |
| Notebook W65KJ1_KK1                         | 1         | 1.92%   |
| Notebook W650DC,DD                          | 1         | 1.92%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 1.92%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 1.92%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.92%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 1.92%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.92%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.92%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 1.92%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 1.92%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 1.92%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 1.92%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.92%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 1.92%   |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 1.92%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 1.92%   |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 1.92%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.92%   |
| Lenovo G480 20149                           | 1         | 1.92%   |
| Lenovo G470 20078                           | 1         | 1.92%   |
| Lenovo B470 HuronRiver Platform             | 1         | 1.92%   |
| Lenovo B41-80 80LG                          | 1         | 1.92%   |
| HUAWEI NBLL-WXX9                            | 1         | 1.92%   |
| HUAWEI HLY-WX9XX                            | 1         | 1.92%   |
| HP ProBook 440 G6                           | 1         | 1.92%   |
| HP ProBook 430 G4                           | 1         | 1.92%   |
| HP Pavilion Gaming Laptop 15-dk0xxx         | 1         | 1.92%   |
| HASEE CW35S                                 | 1         | 1.92%   |
| Dell Precision 3541                         | 1         | 1.92%   |
| Dell Latitude E5570                         | 1         | 1.92%   |
| Dell Latitude 5520                          | 1         | 1.92%   |
| Dell Latitude 5310                          | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 13        | 25%     |
| Dell Latitude              | 4         | 7.69%   |
| Unknown                    | 4         | 7.69%   |
| HP ProBook                 | 2         | 3.85%   |
| WOOKING X5                 | 1         | 1.92%   |
| Toshiba Satellite          | 1         | 1.92%   |
| Timi RedmiBook             | 1         | 1.92%   |
| Sony SVS1511AJB            | 1         | 1.92%   |
| Sony SVP13225SCBI          | 1         | 1.92%   |
| Panasonic CF-B11JWCYS      | 1         | 1.92%   |
| Notebook W65KJ1            | 1         | 1.92%   |
| Notebook W650DC            | 1         | 1.92%   |
| NEC Computers PC-VK17HBBCD | 1         | 1.92%   |
| Lenovo ZhaoYang            | 1         | 1.92%   |
| Lenovo XiaoXinPro-13ARE    | 1         | 1.92%   |
| Lenovo Rescuer-15ISK       | 1         | 1.92%   |
| Lenovo IdeaPad             | 1         | 1.92%   |
| Lenovo G480                | 1         | 1.92%   |
| Lenovo G470                | 1         | 1.92%   |
| Lenovo B470                | 1         | 1.92%   |
| Lenovo B41-80              | 1         | 1.92%   |
| HUAWEI NBLL-WXX9           | 1         | 1.92%   |
| HUAWEI HLY-WX9XX           | 1         | 1.92%   |
| HP Pavilion                | 1         | 1.92%   |
| HASEE CW35S                | 1         | 1.92%   |
| Dell Precision             | 1         | 1.92%   |
| Dell Inspiron              | 1         | 1.92%   |
| ASUS X540UP                | 1         | 1.92%   |
| ASUS X455LJ                | 1         | 1.92%   |
| ASUS X441UV                | 1         | 1.92%   |
| ASUS F83VD                 | 1         | 1.92%   |
| Apple MacBookPro11         | 1         | 1.92%   |
| Acer Aspire                | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 15.38%  |
| 2017 | 7         | 13.46%  |
| 2012 | 6         | 11.54%  |
| 2022 | 4         | 7.69%   |
| 2019 | 4         | 7.69%   |
| 2016 | 4         | 7.69%   |
| 2013 | 4         | 7.69%   |
| 2011 | 4         | 7.69%   |
| 2020 | 3         | 5.77%   |
| 2018 | 3         | 5.77%   |
| 2015 | 2         | 3.85%   |
| 2009 | 2         | 3.85%   |
| 2010 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 36.54%  |
| 4.01-8.0    | 15        | 28.85%  |
| 16.01-24.0  | 10        | 19.23%  |
| 24.01-32.0  | 4         | 7.69%   |
| 32.01-64.0  | 3         | 5.77%   |
| 64.01-256.0 | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 27        | 51.92%  |
| 0.51-1.0 | 14        | 26.92%  |
| 1.01-2.0 | 10        | 19.23%  |
| 2.01-3.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 66.04%  |
| 2      | 12        | 22.64%  |
| 3      | 3         | 5.66%   |
| 0      | 3         | 5.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 71.15%  |
| Yes       | 15        | 28.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 84.62%  |
| No        | 8         | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 94.23%  |
| No        | 3         | 5.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 69.23%  |
| No        | 16        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 52        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Guangzhou               | 6         | 11.11%  |
| Beijing                 | 6         | 11.11%  |
| Shanghai                | 5         | 9.26%   |
| Shenzhen                | 4         | 7.41%   |
| Zhengzhou               | 2         | 3.7%    |
| Wuhan                   | 2         | 3.7%    |
| Nanjing                 | 2         | 3.7%    |
| Chengdu                 | 2         | 3.7%    |
| Changzhou               | 2         | 3.7%    |
| Zhumadian               | 1         | 1.85%   |
| Zhaoqing                | 1         | 1.85%   |
| Yichun                  | 1         | 1.85%   |
| Xiamen                  | 1         | 1.85%   |
| Xi'an                   | 1         | 1.85%   |
| Wuxi                    | 1         | 1.85%   |
| Shizishan               | 1         | 1.85%   |
| Qinnan                  | 1         | 1.85%   |
| Putian                  | 1         | 1.85%   |
| Pudong                  | 1         | 1.85%   |
| Linyi                   | 1         | 1.85%   |
| Lanzhou                 | 1         | 1.85%   |
| Jinniu                  | 1         | 1.85%   |
| Jilin City              | 1         | 1.85%   |
| Huangpu                 | 1         | 1.85%   |
| Hongyuan                | 1         | 1.85%   |
| Hohhot                  | 1         | 1.85%   |
| Hangzhou                | 1         | 1.85%   |
| Guangzhou Shi           | 1         | 1.85%   |
| Dongguan                | 1         | 1.85%   |
| Dangchang Chengguanzhen | 1         | 1.85%   |
| Changchun               | 1         | 1.85%   |
| Baiyun                  | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 16.92%  |
| Seagate             | 9         | 10     | 13.85%  |
| WDC                 | 8         | 11     | 12.31%  |
| Toshiba             | 6         | 7      | 9.23%   |
| HGST                | 3         | 3      | 4.62%   |
| SK hynix            | 2         | 2      | 3.08%   |
| SanDisk             | 2         | 2      | 3.08%   |
| Netac               | 2         | 2      | 3.08%   |
| KIOXIA              | 2         | 2      | 3.08%   |
| Kingston            | 2         | 2      | 3.08%   |
| Intel               | 2         | 2      | 3.08%   |
| Hikvision           | 2         | 2      | 3.08%   |
| Crucial             | 2         | 2      | 3.08%   |
| Silicon Motion      | 1         | 1      | 1.54%   |
| Plextor             | 1         | 1      | 1.54%   |
| Pioneer             | 1         | 1      | 1.54%   |
| Lexar               | 1         | 1      | 1.54%   |
| Lenovo              | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 1      | 1.54%   |
| Hewlett-Packard     | 1         | 1      | 1.54%   |
| Colorful            | 1         | 1      | 1.54%   |
| China               | 1         | 2      | 1.54%   |
| BR                  | 1         | 1      | 1.54%   |
| Apple               | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB                  | 2         | 2.9%    |
| SanDisk SSD U100 24GB                           | 2         | 2.9%    |
| Samsung SSD 970 EVO Plus 1TB                    | 2         | 2.9%    |
| Samsung SSD 870 EVO 1TB                         | 2         | 2.9%    |
| Samsung MZVL21T0HCLR-00BL7 1TB                  | 2         | 2.9%    |
| Hikvision HS-SSD-C2000ECO 1024G                 | 2         | 2.9%    |
| HGST HTS541010B7E610 1TB                        | 2         | 2.9%    |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 1.45%   |
| WDC WDS100T3X0C-00SJG0 1TB                      | 1         | 1.45%   |
| WDC WD3200BPVT-75ZEST0 320GB                    | 1         | 1.45%   |
| WDC WD2500BEVS-08VAT2 250GB                     | 1         | 1.45%   |
| WDC WD20SPZX-75UA7T0 2TB                        | 1         | 1.45%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 1.45%   |
| WDC WD10JPVX-00JC3T0 1TB                        | 1         | 1.45%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB            | 1         | 1.45%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB            | 1         | 1.45%   |
| Toshiba THNSNF128GCSS 128GB                     | 1         | 1.45%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.45%   |
| Toshiba MQ02ABF050H-SSHD-8GB                    | 1         | 1.45%   |
| Toshiba MQ01ACF050 500GB                        | 1         | 1.45%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.45%   |
| Toshiba KXG6APNV2T04 2TB                        | 1         | 1.45%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB         | 1         | 1.45%   |
| SK hynix BC511 NVMe 512GB                       | 1         | 1.45%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 1.45%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.45%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1.45%   |
| Seagate ST500LM030-2E717D 500GB                 | 1         | 1.45%   |
| Seagate ST320LT007-9ZV142 320GB                 | 1         | 1.45%   |
| Seagate ST2000LM015-2E8174 2TB                  | 1         | 1.45%   |
| Seagate ST2000LM007-1R8174 2TB                  | 1         | 1.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1.45%   |
| Seagate ST1000DM010-2EP102 1TB                  | 1         | 1.45%   |
| Samsung SSD 860 EVO 500GB                       | 1         | 1.45%   |
| Samsung SSD 850 EVO 120GB                       | 1         | 1.45%   |
| Samsung MZVLB512HBJQ-000H1 512GB                | 1         | 1.45%   |
| Samsung MZVLB512HAJQ-00000 512GB                | 1         | 1.45%   |
| Samsung MZNTY256HDHP-000L2 256GB                | 1         | 1.45%   |
| Samsung MZNTE128HMGR-000SO 128GB                | 1         | 1.45%   |
| Samsung MZALQ512HALU-000L2 512GB                | 1         | 1.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 42.86%  |
| WDC     | 5         | 5      | 23.81%  |
| Toshiba | 4         | 4      | 19.05%  |
| HGST    | 3         | 3      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 23.08%  |
| SanDisk             | 2         | 2      | 7.69%   |
| Netac               | 2         | 2      | 7.69%   |
| Kingston            | 2         | 2      | 7.69%   |
| Intel               | 2         | 2      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Lexar               | 1         | 1      | 3.85%   |
| Lenovo              | 1         | 1      | 3.85%   |
| KingSpec            | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Crucial             | 1         | 1      | 3.85%   |
| China               | 1         | 2      | 3.85%   |
| BR                  | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 24        | 27     | 39.34%  |
| HDD  | 19        | 22     | 31.15%  |
| NVMe | 18        | 24     | 29.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 49     | 67.86%  |
| NVMe | 18        | 24     | 32.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 32     | 61.9%   |
| 0.51-1.0   | 13        | 14     | 30.95%  |
| 1.01-2.0   | 3         | 3      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 27.78%  |
| 251-500    | 14        | 25.93%  |
| 101-250    | 9         | 16.67%  |
| 501-1000   | 5         | 9.26%   |
| 1001-2000  | 4         | 7.41%   |
| 21-50      | 3         | 5.56%   |
| 51-100     | 3         | 5.56%   |
| Unknown    | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 42        | 79.25%  |
| 21-50   | 6         | 11.32%  |
| 251-500 | 2         | 3.77%   |
| 101-250 | 1         | 1.89%   |
| 51-100  | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 20%     |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 20%     |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 20%     |
| China JWX 16GB MSATA            | 1         | 2      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| China   | 1         | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 2      | 20%     |

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
| Works   | 47        | 67     | 90.38%  |
| Malfunc | 5         | 6      | 9.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 39        | 61.9%   |
| Samsung Electronics          | 8         | 12.7%   |
| SanDisk                      | 3         | 4.76%   |
| SK hynix                     | 2         | 3.17%   |
| Silicon Motion               | 2         | 3.17%   |
| MAXIO Technology (Hangzhou)  | 2         | 3.17%   |
| KIOXIA                       | 2         | 3.17%   |
| AMD                          | 2         | 3.17%   |
| Toshiba                      | 1         | 1.59%   |
| Shenzhen Longsys Electronics | 1         | 1.59%   |
| Micron/Crucial Technology    | 1         | 1.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 13.85%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 9.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 6.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 4.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 4.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.08%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2         | 3.08%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.08%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.54%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.54%   |
| SK hynix BC511                                                                 | 1         | 1.54%   |
| Shenzhen Longsys unknown                                                       | 1         | 1.54%   |
| Samsung SM951 AHCI                                                             | 1         | 1.54%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.54%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.54%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.54%   |
| Unknown                                                                        | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 39        | 63.93%  |
| NVMe | 18        | 29.51%  |
| RAID | 2         | 3.28%   |
| IDE  | 2         | 3.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 90.38%  |
| AMD    | 5         | 9.62%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 5.77%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 5.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 5.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 3.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 2         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 3.85%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz        | 1         | 1.92%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1         | 1.92%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 1.92%   |
| Intel CPU Version                           | 1         | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.92%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.92%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz          | 1         | 1.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.92%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 1.92%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.92%   |
| Intel Core i7-2637M CPU                     | 1         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.92%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.92%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.92%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.92%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 1.92%   |
| Intel Core i3 CPU M 380 @ 2.53GH            | 1         | 1.92%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 1         | 1.92%   |
| Intel Celeron Dual-Core CPU T3300 @ 2.00GHz | 1         | 1.92%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 1         | 1.92%   |
| Intel Celeron 2980U @ 1.60GHz               | 1         | 1.92%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz     | 1         | 1.92%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1         | 1.92%   |
| AMD Ryzen 7 4800U with Radeon Graphics      | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 36.54%  |
| Intel Core i7           | 10        | 19.23%  |
| Other                   | 6         | 11.54%  |
| Intel Core i3           | 6         | 11.54%  |
| Intel Pentium           | 2         | 3.85%   |
| Intel Celeron           | 2         | 3.85%   |
| AMD Ryzen 5             | 2         | 3.85%   |
| Intel Xeon              | 1         | 1.92%   |
| Intel Core 2 Duo        | 1         | 1.92%   |
| Intel Celeron Dual-Core | 1         | 1.92%   |
| AMD Ryzen 9             | 1         | 1.92%   |
| AMD Ryzen 7             | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 55.77%  |
| 4       | 16        | 30.77%  |
| 6       | 3         | 5.77%   |
| 24      | 1         | 1.92%   |
| 16      | 1         | 1.92%   |
| 8       | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 71.15%  |
| 1       | 14        | 26.92%  |
| Unknown | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 13        | 25%     |
| Skylake     | 8         | 15.38%  |
| SandyBridge | 7         | 13.46%  |
| IvyBridge   | 5         | 9.62%   |
| TigerLake   | 4         | 7.69%   |
| Haswell     | 4         | 7.69%   |
| Penryn      | 3         | 5.77%   |
| Zen 2       | 2         | 3.85%   |
| Zen+        | 1         | 1.92%   |
| Zen 3       | 1         | 1.92%   |
| Westmere    | 1         | 1.92%   |
| K10         | 1         | 1.92%   |
| CometLake   | 1         | 1.92%   |
| Broadwell   | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 60.81%  |
| Nvidia | 19        | 25.68%  |
| AMD    | 10        | 13.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 9.46%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 6.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 5.41%   |
| Intel HD Graphics 620                                                         | 3         | 4.05%   |
| Intel HD Graphics 530                                                         | 3         | 4.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.7%    |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 2.7%    |
| Intel UHD Graphics 620                                                        | 2         | 2.7%    |
| Intel HD Graphics 630                                                         | 2         | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 2.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.7%    |
| AMD Renoir                                                                    | 2         | 2.7%    |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 1.35%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.35%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 1         | 1.35%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 1.35%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 1.35%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.35%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 1.35%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 1.35%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 1.35%   |
| Nvidia GK107M [GeForce GT 640M LE]                                            | 1         | 1.35%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 1.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.35%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.35%   |
| Nvidia G96CM [GeForce GT 220M]                                                | 1         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.35%   |
| Intel HD Graphics P630                                                        | 1         | 1.35%   |
| Intel HD Graphics 5500                                                        | 1         | 1.35%   |
| Intel HD Graphics 510                                                         | 1         | 1.35%   |
| Intel Crystal Well Integrated Graphics Controller                             | 1         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 42.31%  |
| Intel + Nvidia | 17        | 32.69%  |
| Intel + AMD    | 5         | 9.62%   |
| 1 x AMD        | 5         | 9.62%   |
| 1 x Nvidia     | 2         | 3.85%   |
| 2 x Intel      | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 44        | 84.62%  |
| Proprietary | 6         | 11.54%  |
| Unknown     | 2         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 84.91%  |
| 0.01-0.5   | 4         | 7.55%   |
| 0.51-1.0   | 2         | 3.77%   |
| 7.01-8.0   | 1         | 1.89%   |
| 1.01-2.0   | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 21.05%  |
| BOE                     | 7         | 18.42%  |
| Chimei Innolux          | 6         | 15.79%  |
| AU Optronics            | 6         | 15.79%  |
| Samsung Electronics     | 2         | 5.26%   |
| Lenovo                  | 2         | 5.26%   |
| TMX                     | 1         | 2.63%   |
| PANDA                   | 1         | 2.63%   |
| Panasonic               | 1         | 2.63%   |
| Dell                    | 1         | 2.63%   |
| CSO                     | 1         | 2.63%   |
| Chi Mei Optoelectronics | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 5.26%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 2.63%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 1         | 2.63%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 2.63%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 2.63%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0877 1920x1080 310x170mm 13.9-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06B9 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE065D 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                    | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 290x170mm 13.2-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO363C 1366x768 310x170mm 13.9-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.63%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 39.47%  |
| 1366x768 (WXGA)   | 15        | 39.47%  |
| 1600x900 (HD+)    | 2         | 5.26%   |
| 3200x2000         | 1         | 2.63%   |
| 2880x1800         | 1         | 2.63%   |
| 2880x1620         | 1         | 2.63%   |
| 2560x1600         | 1         | 2.63%   |
| 2560x1440 (QHD)   | 1         | 2.63%   |
| 1920x1200 (WUXGA) | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 18        | 47.37%  |
| 15     | 15        | 39.47%  |
| 12     | 2         | 5.26%   |
| 24     | 1         | 2.63%   |
| 16     | 1         | 2.63%   |
| 14     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 76.32%  |
| 201-300     | 7         | 18.42%  |
| 501-600     | 1         | 2.63%   |
| 351-400     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 89.19%  |
| 16/10 | 4         | 10.81%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 42.11%  |
| 91-100         | 12        | 31.58%  |
| 71-80          | 3         | 7.89%   |
| 61-70          | 2         | 5.26%   |
| 111-120        | 2         | 5.26%   |
| 101-110        | 2         | 5.26%   |
| 201-250        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 47.37%  |
| 101-120 | 12        | 31.58%  |
| 161-240 | 7         | 18.42%  |
| 51-100  | 1         | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 39        | 73.58%  |
| 0     | 13        | 24.53%  |
| 2     | 1         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 46.05%  |
| Realtek Semiconductor | 24        | 31.58%  |
| Qualcomm Atheros      | 10        | 13.16%  |
| Broadcom              | 5         | 6.58%   |
| Qualcomm              | 1         | 1.32%   |
| Edimax Technology     | 1         | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 4.17%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.17%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.13%   |
| Intel Wireless 8260                                               | 3         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.08%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.04%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.04%   |
| Intel Wireless-AC 9260                                            | 1         | 1.04%   |
| Intel Wireless 7260                                               | 1         | 1.04%   |
| Intel Wireless 3165                                               | 1         | 1.04%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.04%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.04%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.04%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 60%     |
| Qualcomm Atheros      | 9         | 18%     |
| Realtek Semiconductor | 6         | 12%     |
| Broadcom              | 4         | 8%      |
| Edimax Technology     | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 7.84%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 7.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 7.84%   |
| Intel Wireless 8265 / 8275                                        | 3         | 5.88%   |
| Intel Wireless 8260                                               | 3         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 3.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.96%   |
| Intel Wireless-AC 9260                                            | 1         | 1.96%   |
| Intel Wireless 7260                                               | 1         | 1.96%   |
| Intel Wireless 3165                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.96%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.96%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 1.96%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.96%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 46.67%  |
| Intel                 | 17        | 37.78%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Broadcom              | 2         | 4.44%   |
| Qualcomm              | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 35.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 8.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 4.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.44%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 4.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.22%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 2.22%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.22%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.22%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.22%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.22%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 52.69%  |
| Ethernet | 44        | 47.31%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 55.56%  |
| WiFi     | 32        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 76.92%  |
| 1     | 9         | 17.31%  |
| 6     | 3         | 5.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 92.31%  |
| Yes  | 4         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 61.11%  |
| Lite-On Technology              | 2         | 5.56%   |
| Foxconn / Hon Hai               | 2         | 5.56%   |
| Cambridge Silicon Radio         | 2         | 5.56%   |
| Broadcom                        | 2         | 5.56%   |
| Apple                           | 2         | 5.56%   |
| Realtek Semiconductor           | 1         | 2.78%   |
| Realtek                         | 1         | 2.78%   |
| Qualcomm Atheros Communications | 1         | 2.78%   |
| IMC Networks                    | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 27.78%  |
| Intel AX201 Bluetooth                               | 6         | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.56%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 2.78%   |
| Realtek Bluetooth Radio                             | 1         | 2.78%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 2.78%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 2.78%   |
| Lite-On BCM43142A0 Bluetooth Module                 | 1         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.78%   |
| Intel AX200 Bluetooth                               | 1         | 2.78%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.78%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.78%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.78%   |
| Apple Bluetooth Host Controller                     | 1         | 2.78%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 84.91%  |
| AMD    | 5         | 9.43%   |
| Nvidia | 3         | 5.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 9         | 14.75%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 11.48%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 6.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 6.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 6.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 4.92%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 4.92%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 3.28%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 3.28%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 3.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 1.64%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1         | 1.64%   |
| Intel Crystal Well HD Audio Controller                                            | 1         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 1.64%   |
| Intel Broadwell-U Audio Controller                                                | 1         | 1.64%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1         | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 30.88%  |
| SK hynix            | 16        | 23.53%  |
| Kingston            | 9         | 13.24%  |
| Micron Technology   | 6         | 8.82%   |
| Ramaxel Technology  | 4         | 5.88%   |
| Unknown             | 2         | 2.94%   |
| Transcend           | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| Unknown (08B5)      | 1         | 1.47%   |
| Team                | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| KingTiger           | 1         | 1.47%   |
| Crucial             | 1         | 1.47%   |
| A-DATA Technology   | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 4         | 5.33%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 3         | 4%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 2.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 2         | 2.67%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 2.67%   |
| Unknown                                                     | 2         | 2.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 1.33%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s | 1         | 1.33%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s      | 1         | 1.33%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                | 1         | 1.33%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 1.33%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.33%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 1.33%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 1.33%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s         | 1         | 1.33%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s       | 1         | 1.33%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.33%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s     | 1         | 1.33%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.33%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                 | 1         | 1.33%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s | 1         | 1.33%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s      | 1         | 1.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 1.33%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 24        | 46.15%  |
| DDR3    | 23        | 44.23%  |
| LPDDR4  | 2         | 3.85%   |
| Unknown | 2         | 3.85%   |
| LPDDR3  | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 86.54%  |
| Row Of Chips | 7         | 13.46%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 37.1%   |
| 4096  | 20        | 32.26%  |
| 2048  | 10        | 16.13%  |
| 16384 | 7         | 11.29%  |
| 32768 | 1         | 1.61%   |
| 1024  | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 19.67%  |
| 1333    | 9         | 14.75%  |
| 2667    | 8         | 13.11%  |
| 2133    | 7         | 11.48%  |
| 3200    | 6         | 9.84%   |
| 2400    | 6         | 9.84%   |
| 1334    | 3         | 4.92%   |
| 4267    | 2         | 3.28%   |
| 1067    | 2         | 3.28%   |
| 800     | 2         | 3.28%   |
| Unknown | 2         | 3.28%   |
| 1867    | 1         | 1.64%   |
| 533     | 1         | 1.64%   |

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
| Chicony Electronics                    | 12        | 28.57%  |
| Realtek Semiconductor                  | 5         | 11.9%   |
| Acer                                   | 5         | 11.9%   |
| Syntek                                 | 3         | 7.14%   |
| IMC Networks                           | 3         | 7.14%   |
| Sunplus Innovation Technology          | 2         | 4.76%   |
| Quanta                                 | 2         | 4.76%   |
| Microdia                               | 2         | 4.76%   |
| Lite-On Technology                     | 2         | 4.76%   |
| Lenovo                                 | 1         | 2.38%   |
| Importek                               | 1         | 2.38%   |
| Genesys Logic                          | 1         | 2.38%   |
| Foxconn / Hon Hai                      | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |
| ALi                                    | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 9.3%    |
| Realtek Integrated_Webcam_HD                                               | 3         | 6.98%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 6.98%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 6.98%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.65%   |
| IMC Networks Integrated Camera                                             | 2         | 4.65%   |
| Acer ThinkPad Integrated Camera                                            | 2         | 4.65%   |
| Syntek Integrated Camera                                                   | 1         | 2.33%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.33%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 2.33%   |
| Realtek Front Camera                                                       | 1         | 2.33%   |
| Quanta Realtek DMFT - RGB                                                  | 1         | 2.33%   |
| Quanta ov9734_techfront_camera                                             | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.33%   |
| Lite-On Integrated Camera                                                  | 1         | 2.33%   |
| Lite-On HP HD Camera                                                       | 1         | 2.33%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 2.33%   |
| Importek USB 2.0 Camera                                                    | 1         | 2.33%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.33%   |
| Genesys Logic Camera                                                       | 1         | 2.33%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2.33%   |
| Chicony Integrated IR Camera                                               | 1         | 2.33%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2.33%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.33%   |
| ALi Gateway Webcam                                                         | 1         | 2.33%   |
| Acer Lenovo Integrated Webcam                                              | 1         | 2.33%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.33%   |
| Acer Integrated Camera                                                     | 1         | 2.33%   |

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
| 2     | 16        | 30.77%  |
| 3     | 14        | 26.92%  |
| 1     | 14        | 26.92%  |
| 0     | 6         | 11.54%  |
| 4     | 2         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 47.25%  |
| Card reader              | 14        | 15.38%  |
| Net/wireless             | 13        | 14.29%  |
| Bluetooth                | 11        | 12.09%  |
| Fingerprint reader       | 10        | 10.99%  |

