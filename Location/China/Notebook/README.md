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

Total: 70

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.7.0    | 5         | 9.43%   |
| helloSystem 0.5.0    | 5         | 9.43%   |
| FreeBSD 14.0-CURRENT | 4         | 7.55%   |
| FreeBSD 12.2         | 4         | 7.55%   |
| helloSystem 0.6.0    | 3         | 5.66%   |
| helloSystem 0.4.0    | 3         | 5.66%   |
| FreeBSD 13.1         | 3         | 5.66%   |
| OPNsense 21.1.1      | 2         | 3.77%   |
| NomadBSD 5806f915    | 2         | 3.77%   |
| helloSystem 0.8.0    | 2         | 3.77%   |
| GhostBSD 21.08.27    | 2         | 3.77%   |
| FreeBSD 13.0-p7      | 2         | 3.77%   |
| FreeBSD 13.0-p4      | 2         | 3.77%   |
| FreeBSD 13.0         | 2         | 3.77%   |
| OPNsense 22.7        | 1         | 1.89%   |
| OPNsense 21.1        | 1         | 1.89%   |
| OPNsense 20.7.8      | 1         | 1.89%   |
| OpenBSD 7.0          | 1         | 1.89%   |
| NomadBSD 1.3.1       | 1         | 1.89%   |
| FreeBSD 13.1-RC3     | 1         | 1.89%   |
| FreeBSD 13.0-STABLE  | 1         | 1.89%   |
| FreeBSD 13.0-RC1     | 1         | 1.89%   |
| FreeBSD 13.0-p3      | 1         | 1.89%   |
| FreeBSD 13.0-p2      | 1         | 1.89%   |
| FreeBSD 12.2-p10     | 1         | 1.89%   |
| FreeBSD 12.1-p7      | 1         | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 23        | 45.1%   |
| helloSystem | 18        | 35.29%  |
| OPNsense    | 4         | 7.84%   |
| NomadBSD    | 3         | 5.88%   |
| GhostBSD    | 2         | 3.92%   |
| OpenBSD     | 1         | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 50        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 17        | 31.48%  |
| XFCE         | 9         | 16.67%  |
| KDE5         | 7         | 12.96%  |
| Console      | 7         | 12.96%  |
| GNOME        | 4         | 7.41%   |
| Openbox      | 3         | 5.56%   |
| i3           | 3         | 5.56%   |
| MATE         | 2         | 3.7%    |
| TWM          | 1         | 1.85%   |
| fvwm         | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 44        | 84.62%  |
| Console | 7         | 13.46%  |
| Wayland | 1         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 26        | 49.06%  |
| Console | 12        | 22.64%  |
| SDDM    | 5         | 9.43%   |
| LightDM | 5         | 9.43%   |
| GDM     | 4         | 7.55%   |
| XDM     | 1         | 1.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 21        | 39.62%  |
| zh_CN        | 12        | 22.64%  |
| Unknown      | 10        | 18.87%  |
| C            | 9         | 16.98%  |
| zh_CN.GB2312 | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 86.27%  |
| BIOS | 7         | 13.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 29        | 56.86%  |
| Ufs    | 17        | 33.33%  |
| Cd9660 | 4         | 7.84%   |
| Ffs    | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 46        | 90.2%   |
| MBR  | 5         | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 21        | 42%     |
| Dell             | 5         | 10%     |
| Unknown          | 4         | 8%      |
| Hewlett-Packard  | 3         | 6%      |
| ASUSTek Computer | 3         | 6%      |
| Sony             | 2         | 4%      |
| Notebook         | 2         | 4%      |
| HUAWEI           | 2         | 4%      |
| WOOKING          | 1         | 2%      |
| Toshiba          | 1         | 2%      |
| Timi             | 1         | 2%      |
| Panasonic        | 1         | 2%      |
| NEC Computers    | 1         | 2%      |
| HASEE Computer   | 1         | 2%      |
| Apple            | 1         | 2%      |
| Acer             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 4         | 8%      |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 4%      |
| WOOKING X5                                  | 1         | 2%      |
| Toshiba Satellite Pro L510                  | 1         | 2%      |
| Timi RedmiBook Pro 15                       | 1         | 2%      |
| Sony SVS1511AJB                             | 1         | 2%      |
| Sony SVP13225SCBI                           | 1         | 2%      |
| Panasonic CF-B11JWCYS                       | 1         | 2%      |
| Notebook W65KJ1_KK1                         | 1         | 2%      |
| Notebook W650DC,DD                          | 1         | 2%      |
| NEC Computers PC-VK17HBBCD                  | 1         | 2%      |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 2%      |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 2%      |
| Lenovo ThinkPad X230 23062S2                | 1         | 2%      |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 2%      |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 2%      |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 2%      |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 2%      |
| Lenovo ThinkPad T430 2349GCU                | 1         | 2%      |
| Lenovo ThinkPad SL410 28747GC               | 1         | 2%      |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 2%      |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 2%      |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 2%      |
| Lenovo ThinkPad E420 1141A83                | 1         | 2%      |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 2%      |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 2%      |
| Lenovo G480 20149                           | 1         | 2%      |
| Lenovo G470 20078                           | 1         | 2%      |
| Lenovo B470 HuronRiver Platform             | 1         | 2%      |
| Lenovo B41-80 80LG                          | 1         | 2%      |
| HUAWEI NBLL-WXX9                            | 1         | 2%      |
| HUAWEI HLY-WX9XX                            | 1         | 2%      |
| HP ProBook 440 G6                           | 1         | 2%      |
| HP ProBook 430 G4                           | 1         | 2%      |
| HP Pavilion Gaming Laptop 15-dk0xxx         | 1         | 2%      |
| HASEE CW35S                                 | 1         | 2%      |
| Dell Precision 3541                         | 1         | 2%      |
| Dell Latitude E5570                         | 1         | 2%      |
| Dell Latitude 5520                          | 1         | 2%      |
| Dell Latitude 5290                          | 1         | 2%      |
| Dell Inspiron N4030                         | 1         | 2%      |
| ASUS X540UP                                 | 1         | 2%      |
| ASUS X441UV                                 | 1         | 2%      |
| ASUS F83VD                                  | 1         | 2%      |
| Apple MacBookPro11,4                        | 1         | 2%      |
| Acer Aspire 4552G                           | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 13        | 26%     |
| Unknown                    | 4         | 8%      |
| Dell Latitude              | 3         | 6%      |
| HP ProBook                 | 2         | 4%      |
| WOOKING X5                 | 1         | 2%      |
| Toshiba Satellite          | 1         | 2%      |
| Timi RedmiBook             | 1         | 2%      |
| Sony SVS1511AJB            | 1         | 2%      |
| Sony SVP13225SCBI          | 1         | 2%      |
| Panasonic CF-B11JWCYS      | 1         | 2%      |
| Notebook W65KJ1            | 1         | 2%      |
| Notebook W650DC            | 1         | 2%      |
| NEC Computers PC-VK17HBBCD | 1         | 2%      |
| Lenovo ZhaoYang            | 1         | 2%      |
| Lenovo XiaoXinPro-13ARE    | 1         | 2%      |
| Lenovo Rescuer-15ISK       | 1         | 2%      |
| Lenovo IdeaPad             | 1         | 2%      |
| Lenovo G480                | 1         | 2%      |
| Lenovo G470                | 1         | 2%      |
| Lenovo B470                | 1         | 2%      |
| Lenovo B41-80              | 1         | 2%      |
| HUAWEI NBLL-WXX9           | 1         | 2%      |
| HUAWEI HLY-WX9XX           | 1         | 2%      |
| HP Pavilion                | 1         | 2%      |
| HASEE CW35S                | 1         | 2%      |
| Dell Precision             | 1         | 2%      |
| Dell Inspiron              | 1         | 2%      |
| ASUS X540UP                | 1         | 2%      |
| ASUS X441UV                | 1         | 2%      |
| ASUS F83VD                 | 1         | 2%      |
| Apple MacBookPro11         | 1         | 2%      |
| Acer Aspire                | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 16%     |
| 2017 | 7         | 14%     |
| 2012 | 6         | 12%     |
| 2019 | 4         | 8%      |
| 2016 | 4         | 8%      |
| 2013 | 4         | 8%      |
| 2011 | 4         | 8%      |
| 2022 | 3         | 6%      |
| 2020 | 3         | 6%      |
| 2018 | 3         | 6%      |
| 2009 | 2         | 4%      |
| 2015 | 1         | 2%      |
| 2010 | 1         | 2%      |

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
| No   | 50        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 18        | 36%     |
| 4.01-8.0    | 15        | 30%     |
| 16.01-24.0  | 10        | 20%     |
| 32.01-64.0  | 3         | 6%      |
| 24.01-32.0  | 3         | 6%      |
| 64.01-256.0 | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 26        | 52%     |
| 0.51-1.0 | 14        | 28%     |
| 1.01-2.0 | 9         | 18%     |
| 2.01-3.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 64.71%  |
| 2      | 12        | 23.53%  |
| 3      | 3         | 5.88%   |
| 0      | 3         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 72%     |
| Yes       | 14        | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 84%     |
| No        | 8         | 16%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 94%     |
| No        | 3         | 6%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 68%     |
| No        | 16        | 32%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 50        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Guangzhou               | 6         | 11.54%  |
| Beijing                 | 6         | 11.54%  |
| Shanghai                | 5         | 9.62%   |
| Shenzhen                | 4         | 7.69%   |
| Zhengzhou               | 2         | 3.85%   |
| Wuhan                   | 2         | 3.85%   |
| Nanjing                 | 2         | 3.85%   |
| Chengdu                 | 2         | 3.85%   |
| Changzhou               | 2         | 3.85%   |
| Zhumadian               | 1         | 1.92%   |
| Zhaoqing                | 1         | 1.92%   |
| Yichun                  | 1         | 1.92%   |
| Xi'an                   | 1         | 1.92%   |
| Wuxi                    | 1         | 1.92%   |
| Shizishan               | 1         | 1.92%   |
| Putian                  | 1         | 1.92%   |
| Pudong                  | 1         | 1.92%   |
| Linyi                   | 1         | 1.92%   |
| Lanzhou                 | 1         | 1.92%   |
| Jinniu                  | 1         | 1.92%   |
| Jilin City              | 1         | 1.92%   |
| Huangpu                 | 1         | 1.92%   |
| Hongyuan                | 1         | 1.92%   |
| Hohhot                  | 1         | 1.92%   |
| Hangzhou                | 1         | 1.92%   |
| Guangzhou Shi           | 1         | 1.92%   |
| Dongguan                | 1         | 1.92%   |
| Dangchang Chengguanzhen | 1         | 1.92%   |
| Changchun               | 1         | 1.92%   |
| Baiyun                  | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 17.46%  |
| Seagate             | 9         | 10     | 14.29%  |
| WDC                 | 7         | 10     | 11.11%  |
| Toshiba             | 6         | 7      | 9.52%   |
| HGST                | 3         | 3      | 4.76%   |
| SK hynix            | 2         | 2      | 3.17%   |
| SanDisk             | 2         | 2      | 3.17%   |
| Netac               | 2         | 2      | 3.17%   |
| KIOXIA              | 2         | 2      | 3.17%   |
| Kingston            | 2         | 2      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| Hikvision           | 2         | 2      | 3.17%   |
| Crucial             | 2         | 2      | 3.17%   |
| Plextor             | 1         | 1      | 1.59%   |
| Pioneer             | 1         | 1      | 1.59%   |
| Lexar               | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| Hewlett-Packard     | 1         | 1      | 1.59%   |
| Colorful            | 1         | 1      | 1.59%   |
| China               | 1         | 2      | 1.59%   |
| BR                  | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB          | 2         | 2.99%   |
| SanDisk SSD U100 24GB                   | 2         | 2.99%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 2.99%   |
| Samsung SSD 870 EVO 1TB                 | 2         | 2.99%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 2         | 2.99%   |
| Hikvision HS-SSD-C2000ECO 1024G         | 2         | 2.99%   |
| HGST HTS541010B7E610 1TB                | 2         | 2.99%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 1.49%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 1.49%   |
| WDC WD2500BEVS-08VAT2 250GB             | 1         | 1.49%   |
| WDC WD20SPZX-75UA7T0 2TB                | 1         | 1.49%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 1.49%   |
| WDC WD10JPVX-00JC3T0 1TB                | 1         | 1.49%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 1.49%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 1.49%   |
| Toshiba THNSNF128GCSS 128GB             | 1         | 1.49%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.49%   |
| Toshiba MQ02ABF050H-SSHD-8GB            | 1         | 1.49%   |
| Toshiba MQ01ACF050 500GB                | 1         | 1.49%   |
| Toshiba MQ01ABF050 500GB                | 1         | 1.49%   |
| Toshiba KXG6APNV2T04 2TB                | 1         | 1.49%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB | 1         | 1.49%   |
| SK hynix BC511 NVMe 512GB               | 1         | 1.49%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.49%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 1.49%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1.49%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1.49%   |
| Seagate ST2000LM015-2E8174 2TB          | 1         | 1.49%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 1.49%   |
| Samsung SSD 860 EVO 500GB               | 1         | 1.49%   |
| Samsung SSD 850 EVO 120GB               | 1         | 1.49%   |
| Samsung MZVLB512HBJQ-000H1 512GB        | 1         | 1.49%   |
| Samsung MZVLB512HAJQ-00000 512GB        | 1         | 1.49%   |
| Samsung MZNTY256HDHP-000L2 256GB        | 1         | 1.49%   |
| Samsung MZNTE128HMGR-000SO 128GB        | 1         | 1.49%   |
| Samsung MZALQ512HALU-000L2 512GB        | 1         | 1.49%   |
| Plextor PX-128M6S 128GB                 | 1         | 1.49%   |
| Pioneer APS-SE10N-256 256GB             | 1         | 1.49%   |
| Netac SSD 240GB                         | 1         | 1.49%   |
| Netac SSD 120GB                         | 1         | 1.49%   |
| Lexar 256GB SSD                         | 1         | 1.49%   |
| Lenovo SSD SL700 240G                   | 1         | 1.49%   |
| KIOXIA KBG40ZNV512G 512GB               | 1         | 1.49%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 1         | 1.49%   |
| Kingston SV300S37A120G 120GB            | 1         | 1.49%   |
| Kingston SA400M8240G 240GB              | 1         | 1.49%   |
| KingSpec P3-120 120GB                   | 1         | 1.49%   |
| Intel SSDSCKKW240H6 240GB               | 1         | 1.49%   |
| Intel SSDSA2CW120G3 120GB               | 1         | 1.49%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.49%   |
| HP SSD S700 1TB                         | 1         | 1.49%   |
| Crucial CT250MX200SSD3 250GB            | 1         | 1.49%   |
| Crucial CT1000P5SSD8 1TB                | 1         | 1.49%   |
| Colorful CN600 512GB                    | 1         | 1.49%   |
| China JWX 16GB MSATA                    | 1         | 1.49%   |
| BR SSD 64GB                             | 1         | 1.49%   |
| Apple SSD SM1024G 1TB                   | 1         | 1.49%   |
| A-DATA SP900 128GB                      | 1         | 1.49%   |

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
| Samsung Electronics | 6         | 6      | 24%     |
| SanDisk             | 2         | 2      | 8%      |
| Netac               | 2         | 2      | 8%      |
| Kingston            | 2         | 2      | 8%      |
| Intel               | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| Plextor             | 1         | 1      | 4%      |
| Lexar               | 1         | 1      | 4%      |
| Lenovo              | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| China               | 1         | 2      | 4%      |
| BR                  | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 23        | 26     | 38.98%  |
| HDD  | 19        | 22     | 32.2%   |
| NVMe | 17        | 23     | 28.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 48     | 68.52%  |
| NVMe | 17        | 23     | 31.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 31     | 60.98%  |
| 0.51-1.0   | 13        | 14     | 31.71%  |
| 1.01-2.0   | 3         | 3      | 7.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 28.85%  |
| 251-500    | 13        | 25%     |
| 101-250    | 8         | 15.38%  |
| 501-1000   | 5         | 9.62%   |
| 1001-2000  | 4         | 7.69%   |
| 21-50      | 3         | 5.77%   |
| 51-100     | 3         | 5.77%   |
| Unknown    | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 40        | 78.43%  |
| 21-50   | 6         | 11.76%  |
| 251-500 | 2         | 3.92%   |
| 101-250 | 1         | 1.96%   |
| 51-100  | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

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
| Works   | 45        | 65     | 90%     |
| Malfunc | 5         | 6      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 38        | 62.3%   |
| Samsung Electronics          | 8         | 13.11%  |
| SanDisk                      | 3         | 4.92%   |
| SK hynix                     | 2         | 3.28%   |
| MAXIO Technology (Hangzhou)  | 2         | 3.28%   |
| KIOXIA                       | 2         | 3.28%   |
| AMD                          | 2         | 3.28%   |
| Toshiba                      | 1         | 1.64%   |
| Silicon Motion               | 1         | 1.64%   |
| Shenzhen Longsys Electronics | 1         | 1.64%   |
| Micron/Crucial Technology    | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 14.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 9.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 7.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 6.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 4.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 4.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.17%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2         | 3.17%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 3.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.17%   |
| Unknown                                                                        | 2         | 3.17%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.59%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 1.59%   |
| SK hynix BC511                                                                 | 1         | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.59%   |
| Samsung SM951 AHCI                                                             | 1         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.59%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.59%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 1.59%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 38        | 64.41%  |
| NVMe | 17        | 28.81%  |
| RAID | 2         | 3.39%   |
| IDE  | 2         | 3.39%   |

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


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 6%      |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 6%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 6%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 4%      |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 4%      |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 2%      |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 2%      |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2%      |
| Intel CPU Version                             | 1         | 2%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2%      |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 2%      |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 2%      |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 2%      |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 2%      |
| Intel Core i7-2637M CPU                       | 1         | 2%      |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2%      |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2%      |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 2%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2%      |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 2%      |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2%      |
| Intel Core i3 CPU M 380 @ 2.53GH              | 1         | 2%      |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 1         | 2%      |
| Intel Celeron Dual-Core CPU T3300 @ 2.00GHz   | 1         | 2%      |
| Intel Celeron CPU 3855U @ 1.60GHz             | 1         | 2%      |
| Intel Celeron 2980U @ 1.60GHz                 | 1         | 2%      |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 2%      |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2%      |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD New Processor Technology                  | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 36%     |
| Intel Core i7           | 9         | 18%     |
| Other                   | 6         | 12%     |
| Intel Core i3           | 6         | 12%     |
| Intel Pentium           | 2         | 4%      |
| Intel Celeron           | 2         | 4%      |
| AMD Ryzen 5             | 2         | 4%      |
| Intel Xeon              | 1         | 2%      |
| Intel Core 2 Duo        | 1         | 2%      |
| Intel Celeron Dual-Core | 1         | 2%      |
| AMD Ryzen 9             | 1         | 2%      |
| AMD Ryzen 7             | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 28        | 56%     |
| 4       | 15        | 30%     |
| 6       | 3         | 6%      |
| 24      | 1         | 2%      |
| 16      | 1         | 2%      |
| 8       | 1         | 2%      |
| Unknown | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 35        | 70%     |
| 1       | 14        | 28%     |
| Unknown | 1         | 2%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 24%     |
| Skylake     | 8         | 16%     |
| SandyBridge | 7         | 14%     |
| IvyBridge   | 5         | 10%     |
| TigerLake   | 4         | 8%      |
| Haswell     | 4         | 8%      |
| Penryn      | 3         | 6%      |
| Zen 2       | 2         | 4%      |
| Zen+        | 1         | 2%      |
| Zen 3       | 1         | 2%      |
| Westmere    | 1         | 2%      |
| K10         | 1         | 2%      |
| CometLake   | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 60.56%  |
| Nvidia | 18        | 25.35%  |
| AMD    | 10        | 14.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 9.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 7.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 5.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 5.63%   |
| Intel HD Graphics 620                                                                 | 3         | 4.23%   |
| Intel HD Graphics 530                                                                 | 3         | 4.23%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 2.82%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 2         | 2.82%   |
| Intel UHD Graphics 620                                                                | 2         | 2.82%   |
| Intel HD Graphics 630                                                                 | 2         | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 2         | 2.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 2.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 2         | 2.82%   |
| AMD Renoir                                                                            | 2         | 2.82%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 1         | 1.41%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 1.41%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 1.41%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                 | 1         | 1.41%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 1.41%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.41%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.41%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                    | 1         | 1.41%   |
| Nvidia GK106M [GeForce GTX 765M]                                                      | 1         | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.41%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 1         | 1.41%   |
| Nvidia G96CM [GeForce GT 220M]                                                        | 1         | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.41%   |
| Intel HD Graphics P630                                                                | 1         | 1.41%   |
| Intel HD Graphics 510                                                                 | 1         | 1.41%   |
| Intel Crystal Well Integrated Graphics Controller                                     | 1         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 1.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.41%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 1         | 1.41%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                     | 1         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 42%     |
| Intel + Nvidia | 16        | 32%     |
| Intel + AMD    | 5         | 10%     |
| 1 x AMD        | 5         | 10%     |
| 1 x Nvidia     | 2         | 4%      |
| 2 x Intel      | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 43        | 86%     |
| Proprietary | 5         | 10%     |
| Unknown     | 2         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 84.31%  |
| 0.01-0.5   | 4         | 7.84%   |
| 0.51-1.0   | 2         | 3.92%   |
| 7.01-8.0   | 1         | 1.96%   |
| 1.01-2.0   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 22.22%  |
| BOE                     | 7         | 19.44%  |
| Chimei Innolux          | 6         | 16.67%  |
| AU Optronics            | 4         | 11.11%  |
| Samsung Electronics     | 2         | 5.56%   |
| Lenovo                  | 2         | 5.56%   |
| TMX                     | 1         | 2.78%   |
| PANDA                   | 1         | 2.78%   |
| Panasonic               | 1         | 2.78%   |
| Dell                    | 1         | 2.78%   |
| CSO                     | 1         | 2.78%   |
| Chi Mei Optoelectronics | 1         | 2.78%   |
| Apple                   | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 5.56%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 2.78%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 1         | 2.78%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 2.78%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 2.78%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 2.78%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE0877 1920x1080 310x170mm 13.9-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE06B9 1920x1080 340x190mm 15.3-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE065D 1920x1080 340x190mm 15.3-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                    | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.78%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 38.89%  |
| 1366x768 (WXGA)   | 14        | 38.89%  |
| 1600x900 (HD+)    | 2         | 5.56%   |
| 3200x2000         | 1         | 2.78%   |
| 2880x1800         | 1         | 2.78%   |
| 2880x1620         | 1         | 2.78%   |
| 2560x1600         | 1         | 2.78%   |
| 2560x1440 (QHD)   | 1         | 2.78%   |
| 1920x1200 (WUXGA) | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 16        | 44.44%  |
| 15     | 15        | 41.67%  |
| 12     | 2         | 5.56%   |
| 24     | 1         | 2.78%   |
| 16     | 1         | 2.78%   |
| 14     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 77.78%  |
| 201-300     | 6         | 16.67%  |
| 501-600     | 1         | 2.78%   |
| 351-400     | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 88.57%  |
| 16/10 | 4         | 11.43%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 41.67%  |
| 91-100         | 12        | 33.33%  |
| 71-80          | 2         | 5.56%   |
| 61-70          | 2         | 5.56%   |
| 111-120        | 2         | 5.56%   |
| 101-110        | 2         | 5.56%   |
| 201-250        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 50%     |
| 101-120 | 11        | 30.56%  |
| 161-240 | 6         | 16.67%  |
| 51-100  | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 72.55%  |
| 0     | 13        | 25.49%  |
| 2     | 1         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 46.58%  |
| Realtek Semiconductor | 23        | 31.51%  |
| Qualcomm Atheros      | 10        | 13.7%   |
| Broadcom              | 4         | 5.48%   |
| Qualcomm              | 1         | 1.37%   |
| Edimax Technology     | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 16.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 4.35%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.35%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.26%   |
| Intel Wireless 8260                                               | 3         | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.17%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.09%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.09%   |
| Intel Wireless-AC 9260                                            | 1         | 1.09%   |
| Intel Wireless 7260                                               | 1         | 1.09%   |
| Intel Wireless 3165                                               | 1         | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.09%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.09%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.09%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 1.09%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.09%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.09%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.09%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 60.42%  |
| Qualcomm Atheros      | 9         | 18.75%  |
| Realtek Semiconductor | 6         | 12.5%   |
| Broadcom              | 3         | 6.25%   |
| Edimax Technology     | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 8.16%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 8.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 8.16%   |
| Intel Wireless 8265 / 8275                                        | 3         | 6.12%   |
| Intel Wireless 8260                                               | 3         | 6.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 4.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 4.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 4.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 4.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 2.04%   |
| Intel Wireless-AC 9260                                            | 1         | 2.04%   |
| Intel Wireless 7260                                               | 1         | 2.04%   |
| Intel Wireless 3165                                               | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.04%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 2.04%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 2.04%   |
| Intel Centrino WiMAX 6150                                         | 1         | 2.04%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 2.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 2.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 46.51%  |
| Intel                 | 16        | 37.21%  |
| Qualcomm Atheros      | 4         | 9.3%    |
| Broadcom              | 2         | 4.65%   |
| Qualcomm              | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 34.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 9.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 4.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.65%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 4.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.33%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.33%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 2.33%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 52.81%  |
| Ethernet | 42        | 47.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 54.29%  |
| WiFi     | 32        | 45.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 76%     |
| 1     | 9         | 18%     |
| 6     | 3         | 6%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 92%     |
| Yes  | 4         | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 61.76%  |
| Foxconn / Hon Hai               | 2         | 5.88%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| Broadcom                        | 2         | 5.88%   |
| Apple                           | 2         | 5.88%   |
| Realtek Semiconductor           | 1         | 2.94%   |
| Realtek                         | 1         | 2.94%   |
| Qualcomm Atheros Communications | 1         | 2.94%   |
| Lite-On Technology              | 1         | 2.94%   |
| IMC Networks                    | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 29.41%  |
| Intel AX201 Bluetooth                               | 5         | 14.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.88%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 2.94%   |
| Realtek Bluetooth Radio                             | 1         | 2.94%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 2.94%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| Intel AX200 Bluetooth                               | 1         | 2.94%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.94%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 2.94%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 84.31%  |
| AMD    | 5         | 9.8%    |
| Nvidia | 3         | 5.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 9         | 15.52%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 12.07%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 4         | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 6.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 6.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 5.17%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 3.45%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 3.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1         | 1.72%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 1.72%   |
| Intel Crystal Well HD Audio Controller                                            | 1         | 1.72%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 1.72%   |
| Intel Comet Lake PCH cAVS                                                         | 1         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1         | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1         | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 30.77%  |
| SK hynix            | 15        | 23.08%  |
| Kingston            | 8         | 12.31%  |
| Micron Technology   | 6         | 9.23%   |
| Ramaxel Technology  | 4         | 6.15%   |
| Unknown             | 2         | 3.08%   |
| Transcend           | 2         | 3.08%   |
| Unknown             | 2         | 3.08%   |
| Unknown (08B5)      | 1         | 1.54%   |
| Team                | 1         | 1.54%   |
| Nanya Technology    | 1         | 1.54%   |
| KingTiger           | 1         | 1.54%   |
| Crucial             | 1         | 1.54%   |
| A-DATA Technology   | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 5.63%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 3         | 4.23%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 2         | 2.82%   |
| Unknown                                                      | 2         | 2.82%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 1.41%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s  | 1         | 1.41%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 1.41%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s       | 1         | 1.41%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.41%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 1.41%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 1.41%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s          | 1         | 1.41%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s        | 1         | 1.41%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.41%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                  | 1         | 1.41%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1333MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 1         | 1.41%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s  | 1         | 1.41%   |
| Samsung RAM M378B5273EBO-YKO 8GB SODIMM DDR3 1333MT/s        | 1         | 1.41%   |
| Samsung RAM M08GD04P1600C1 8GB SODIMM DDR3 1333MT/s          | 1         | 1.41%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.41%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2133MT/s     | 1         | 1.41%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 1         | 1.41%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.41%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.41%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| KingTiger RAM Module 2048MB SODIMM 800MT/s                   | 1         | 1.41%   |
| Kingston RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.41%   |
| Kingston RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 1.41%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s             | 1         | 1.41%   |
| Kingston RAM KHX1600C9S3L/4G 4GB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| Kingston RAM KF3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s      | 1         | 1.41%   |
| Kingston RAM 99U5469-015.A00LF 2GB SODIMM DDR3 1333MT/s      | 1         | 1.41%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 23        | 46%     |
| DDR3    | 22        | 44%     |
| LPDDR4  | 2         | 4%      |
| Unknown | 2         | 4%      |
| LPDDR3  | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 86%     |
| Row Of Chips | 7         | 14%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 38.33%  |
| 4096  | 19        | 31.67%  |
| 2048  | 10        | 16.67%  |
| 16384 | 6         | 10%     |
| 32768 | 1         | 1.67%   |
| 1024  | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 11        | 18.97%  |
| 1333    | 9         | 15.52%  |
| 2667    | 8         | 13.79%  |
| 2133    | 7         | 12.07%  |
| 3200    | 5         | 8.62%   |
| 2400    | 5         | 8.62%   |
| 1334    | 3         | 5.17%   |
| 4267    | 2         | 3.45%   |
| 1067    | 2         | 3.45%   |
| 800     | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 1867    | 1         | 1.72%   |
| 533     | 1         | 1.72%   |

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
| Chicony Electronics                    | 11        | 27.5%   |
| Acer                                   | 5         | 12.5%   |
| Realtek Semiconductor                  | 4         | 10%     |
| Syntek                                 | 3         | 7.5%    |
| IMC Networks                           | 3         | 7.5%    |
| Sunplus Innovation Technology          | 2         | 5%      |
| Quanta                                 | 2         | 5%      |
| Microdia                               | 2         | 5%      |
| Lite-On Technology                     | 2         | 5%      |
| Lenovo                                 | 1         | 2.5%    |
| Importek                               | 1         | 2.5%    |
| Genesys Logic                          | 1         | 2.5%    |
| Foxconn / Hon Hai                      | 1         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.5%    |
| ALi                                    | 1         | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 9.76%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 7.32%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.88%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.88%   |
| IMC Networks Integrated Camera                                             | 2         | 4.88%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 4.88%   |
| Acer ThinkPad Integrated Camera                                            | 2         | 4.88%   |
| Syntek Integrated Camera                                                   | 1         | 2.44%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 2.44%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.44%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 2.44%   |
| Realtek Front Camera                                                       | 1         | 2.44%   |
| Quanta Realtek DMFT - RGB                                                  | 1         | 2.44%   |
| Quanta ov9734_techfront_camera                                             | 1         | 2.44%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 2.44%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.44%   |
| Lite-On Integrated Camera                                                  | 1         | 2.44%   |
| Lite-On HP HD Camera                                                       | 1         | 2.44%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 2.44%   |
| Importek USB 2.0 Camera                                                    | 1         | 2.44%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.44%   |
| Genesys Logic Camera                                                       | 1         | 2.44%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2.44%   |
| Chicony Integrated IR Camera                                               | 1         | 2.44%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2.44%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.44%   |
| ALi Gateway Webcam                                                         | 1         | 2.44%   |
| Acer Lenovo Integrated Webcam                                              | 1         | 2.44%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.44%   |
| Acer Integrated Camera                                                     | 1         | 2.44%   |

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
| 2     | 15        | 30%     |
| 1     | 14        | 28%     |
| 3     | 13        | 26%     |
| 0     | 6         | 12%     |
| 4     | 2         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 41        | 47.67%  |
| Card reader              | 14        | 16.28%  |
| Net/wireless             | 12        | 13.95%  |
| Fingerprint reader       | 10        | 11.63%  |
| Bluetooth                | 9         | 10.47%  |

