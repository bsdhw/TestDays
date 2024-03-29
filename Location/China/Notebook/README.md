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

Total: 108

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Notebook      | N960Kx                      | [4e83c12f96](https://bsd-hardware.info/?probe=4e83c12f96) | Feb 12, 2024 |
| Dell          | Vostro 5470                 | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| Google        | Kohaku                      | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Intel         | H81U                        | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Google        | Kohaku                      | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Timi          | A34R                        | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Dell          | Inspiron 14-3467            | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | B590 20208                  | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Lenovo        | B590 20208                  | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| Lenovo        | B590 20208                  | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Unknown                     | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| HP            | Unknown                     | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| MECHREVO S... | S1 Series                   | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Acer          | TravelMate TX50-G2          | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
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
| FreeBSD 13.1         | 9         | 10.23%  |
| helloSystem 0.8.0    | 8         | 9.09%   |
| helloSystem 0.7.0    | 8         | 9.09%   |
| helloSystem 0.8.1    | 6         | 6.82%   |
| helloSystem 0.5.0    | 5         | 5.68%   |
| FreeBSD 14.0-CURRENT | 5         | 5.68%   |
| FreeBSD 13.2         | 4         | 4.55%   |
| FreeBSD 12.2         | 4         | 4.55%   |
| helloSystem 0.6.0    | 3         | 3.41%   |
| helloSystem 0.4.0    | 3         | 3.41%   |
| OPNsense 21.1.1      | 2         | 2.27%   |
| NomadBSD 5806f915    | 2         | 2.27%   |
| GhostBSD 21.08.27    | 2         | 2.27%   |
| FreeBSD 13.0-p7      | 2         | 2.27%   |
| FreeBSD 13.0-p4      | 2         | 2.27%   |
| FreeBSD 13.0         | 2         | 2.27%   |
| OPNsense 22.7        | 1         | 1.14%   |
| OPNsense 21.1        | 1         | 1.14%   |
| OPNsense 20.7.8      | 1         | 1.14%   |
| OpenBSD 7.3          | 1         | 1.14%   |
| OpenBSD 7.0          | 1         | 1.14%   |
| NomadBSD 1.3.1       | 1         | 1.14%   |
| NetBSD 9.3           | 1         | 1.14%   |
| helloSystem 0.9.0    | 1         | 1.14%   |
| FreeBSD 14.0-p2      | 1         | 1.14%   |
| FreeBSD 14.0-BETA5   | 1         | 1.14%   |
| FreeBSD 14.0         | 1         | 1.14%   |
| FreeBSD 13.1-STABLE  | 1         | 1.14%   |
| FreeBSD 13.1-RC3     | 1         | 1.14%   |
| FreeBSD 13.1-p5      | 1         | 1.14%   |
| FreeBSD 13.1-p2      | 1         | 1.14%   |
| FreeBSD 13.0-STABLE  | 1         | 1.14%   |
| FreeBSD 13.0-RC1     | 1         | 1.14%   |
| FreeBSD 13.0-p3      | 1         | 1.14%   |
| FreeBSD 13.0-p2      | 1         | 1.14%   |
| FreeBSD 12.2-p10     | 1         | 1.14%   |
| FreeBSD 12.1-p7      | 1         | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 38        | 46.34%  |
| helloSystem | 32        | 39.02%  |
| OPNsense    | 4         | 4.88%   |
| NomadBSD    | 3         | 3.66%   |
| OpenBSD     | 2         | 2.44%   |
| GhostBSD    | 2         | 2.44%   |
| NetBSD      | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 80        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 32        | 37.21%  |
| XFCE         | 13        | 15.12%  |
| Console      | 10        | 11.63%  |
| KDE5         | 9         | 10.47%  |
| GNOME        | 5         | 5.81%   |
| TWM          | 4         | 4.65%   |
| i3           | 4         | 4.65%   |
| Openbox      | 3         | 3.49%   |
| MATE         | 3         | 3.49%   |
| fvwm         | 1         | 1.16%   |
| DWM          | 1         | 1.16%   |
| AwesomeWM    | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 71        | 86.59%  |
| Console | 10        | 12.2%   |
| Wayland | 1         | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 42        | 50%     |
| Console | 20        | 23.81%  |
| SDDM    | 8         | 9.52%   |
| LightDM | 6         | 7.14%   |
| GDM     | 5         | 5.95%   |
| XDM     | 3         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 28        | 31.82%  |
| C            | 21        | 23.86%  |
| zh_CN        | 20        | 22.73%  |
| Unknown      | 16        | 18.18%  |
| en           | 2         | 2.27%   |
| zh_CN.GB2312 | 1         | 1.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 88.89%  |
| BIOS | 9         | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 45        | 53.57%  |
| Ufs    | 24        | 28.57%  |
| Cd9660 | 13        | 15.48%  |
| Ffs    | 2         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 76        | 93.83%  |
| MBR  | 5         | 6.17%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 30        | 37.5%   |
| Dell                | 8         | 10%     |
| Hewlett-Packard     | 6         | 7.5%    |
| ASUSTek Computer    | 5         | 6.25%   |
| Unknown             | 4         | 5%      |
| Notebook            | 3         | 3.75%   |
| Google              | 3         | 3.75%   |
| Timi                | 2         | 2.5%    |
| Sony                | 2         | 2.5%    |
| Panasonic           | 2         | 2.5%    |
| MECHREVO S1 Series  | 2         | 2.5%    |
| HUAWEI              | 2         | 2.5%    |
| HASEE Computer      | 2         | 2.5%    |
| Acer                | 2         | 2.5%    |
| WOOKING             | 1         | 1.25%   |
| Toshiba             | 1         | 1.25%   |
| Samsung Electronics | 1         | 1.25%   |
| NEC Computers       | 1         | 1.25%   |
| Intel               | 1         | 1.25%   |
| Apple               | 1         | 1.25%   |
| Acidanthera         | 1         | 1.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 5         | 6.25%   |
| MECHREVO S1 Series S1 Series                | 2         | 2.5%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 2.5%    |
| Google Kohaku                               | 2         | 2.5%    |
| WOOKING X5                                  | 1         | 1.25%   |
| Toshiba Satellite Pro L510                  | 1         | 1.25%   |
| Timi RedmiBook Pro 15                       | 1         | 1.25%   |
| Timi A34R                                   | 1         | 1.25%   |
| Sony SVS1511AJB                             | 1         | 1.25%   |
| Sony SVP13225SCBI                           | 1         | 1.25%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.25%   |
| Panasonic CF-NX1GDHYS                       | 1         | 1.25%   |
| Panasonic CF-B11JWCYS                       | 1         | 1.25%   |
| Notebook W65KJ1_KK1                         | 1         | 1.25%   |
| Notebook W650DC,DD                          | 1         | 1.25%   |
| Notebook N960Kx                             | 1         | 1.25%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 1.25%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 1.25%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.25%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 1.25%   |
| Lenovo ThinkPad X270 20HNA04GCD             | 1         | 1.25%   |
| Lenovo ThinkPad X230 2324A14                | 1         | 1.25%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 1.25%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002LUS    | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.25%   |
| Lenovo ThinkPad X1 Carbon 3448AWU           | 1         | 1.25%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 1.25%   |
| Lenovo ThinkPad T480 20L5000UUS             | 1         | 1.25%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 1.25%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 1.25%   |
| Lenovo ThinkPad T430 2342AG4                | 1         | 1.25%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 1.25%   |
| Lenovo ThinkPad R14 Gen 4 21E5A05RCD        | 1         | 1.25%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.25%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 1.25%   |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 1.25%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 1.25%   |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 1.25%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 20        | 25%     |
| Unknown                    | 5         | 6.25%   |
| Dell Latitude              | 4         | 5%      |
| MECHREVO S1 Series S1      | 2         | 2.5%    |
| HP ProBook                 | 2         | 2.5%    |
| Google Kohaku              | 2         | 2.5%    |
| Dell Inspiron              | 2         | 2.5%    |
| WOOKING X5                 | 1         | 1.25%   |
| Toshiba Satellite          | 1         | 1.25%   |
| Timi RedmiBook             | 1         | 1.25%   |
| Timi A34R                  | 1         | 1.25%   |
| Sony SVS1511AJB            | 1         | 1.25%   |
| Sony SVP13225SCBI          | 1         | 1.25%   |
| Samsung 3570R              | 1         | 1.25%   |
| Panasonic CF-NX1GDHYS      | 1         | 1.25%   |
| Panasonic CF-B11JWCYS      | 1         | 1.25%   |
| Notebook W65KJ1            | 1         | 1.25%   |
| Notebook W650DC            | 1         | 1.25%   |
| Notebook N960Kx            | 1         | 1.25%   |
| NEC Computers PC-VK17HBBCD | 1         | 1.25%   |
| Lenovo ZhaoYang            | 1         | 1.25%   |
| Lenovo XiaoXinPro-13ARE    | 1         | 1.25%   |
| Lenovo XiaoXinPro-13API    | 1         | 1.25%   |
| Lenovo Rescuer-15ISK       | 1         | 1.25%   |
| Lenovo IdeaPad             | 1         | 1.25%   |
| Lenovo G480                | 1         | 1.25%   |
| Lenovo G470                | 1         | 1.25%   |
| Lenovo B590                | 1         | 1.25%   |
| Lenovo B470                | 1         | 1.25%   |
| Lenovo B41-80              | 1         | 1.25%   |
| Intel H81U                 | 1         | 1.25%   |
| HUAWEI NBLL-WXX9           | 1         | 1.25%   |
| HUAWEI HLY-WX9XX           | 1         | 1.25%   |
| HP Pavilion                | 1         | 1.25%   |
| HP OMEN                    | 1         | 1.25%   |
| HP Laptop                  | 1         | 1.25%   |
| HASEE N95XKP6              | 1         | 1.25%   |
| HASEE CW35S                | 1         | 1.25%   |
| Google Edgar               | 1         | 1.25%   |
| Dell Vostro                | 1         | 1.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 15%     |
| 2021 | 10        | 12.5%   |
| 2012 | 9         | 11.25%  |
| 2019 | 8         | 10%     |
| 2018 | 8         | 10%     |
| 2017 | 8         | 10%     |
| 2013 | 7         | 8.75%   |
| 2016 | 4         | 5%      |
| 2011 | 4         | 5%      |
| 2020 | 3         | 3.75%   |
| 2015 | 3         | 3.75%   |
| 2009 | 2         | 2.5%    |
| 2023 | 1         | 1.25%   |
| 2010 | 1         | 1.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 80        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 96.25%  |
| Yes  | 3         | 3.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 31        | 38.75%  |
| 4.01-8.0    | 20        | 25%     |
| 16.01-24.0  | 17        | 21.25%  |
| 32.01-64.0  | 6         | 7.5%    |
| 24.01-32.0  | 5         | 6.25%   |
| 64.01-256.0 | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 42        | 52.5%   |
| 0.51-1.0 | 21        | 26.25%  |
| 1.01-2.0 | 15        | 18.75%  |
| 2.01-3.0 | 1         | 1.25%   |
| Unknown  | 1         | 1.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 60.24%  |
| 2      | 20        | 24.1%   |
| 0      | 10        | 12.05%  |
| 3      | 3         | 3.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 79.01%  |
| Yes       | 17        | 20.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 78.75%  |
| No        | 17        | 21.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 96.25%  |
| No        | 3         | 3.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 77.5%   |
| No        | 18        | 22.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 80        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Shanghai                | 9         | 10.84%  |
| Guangzhou               | 7         | 8.43%   |
| Shenzhen                | 6         | 7.23%   |
| Chengdu                 | 6         | 7.23%   |
| Beijing                 | 6         | 7.23%   |
| Hangzhou                | 5         | 6.02%   |
| Zhengzhou               | 2         | 2.41%   |
| Yuzhong Chengguanzhen   | 2         | 2.41%   |
| Xi'an                   | 2         | 2.41%   |
| Wuhan                   | 2         | 2.41%   |
| Qiqihar                 | 2         | 2.41%   |
| Nanjing                 | 2         | 2.41%   |
| Chongqing               | 2         | 2.41%   |
| Changzhou               | 2         | 2.41%   |
| Zhumadian               | 1         | 1.2%    |
| Zhaoqing                | 1         | 1.2%    |
| Yichun                  | 1         | 1.2%    |
| Xiamen                  | 1         | 1.2%    |
| Wuxi                    | 1         | 1.2%    |
| Weifang                 | 1         | 1.2%    |
| Shizishan               | 1         | 1.2%    |
| Shantou                 | 1         | 1.2%    |
| Qinnan                  | 1         | 1.2%    |
| Putian                  | 1         | 1.2%    |
| Pudong                  | 1         | 1.2%    |
| Nanning                 | 1         | 1.2%    |
| Linyi                   | 1         | 1.2%    |
| Lanzhou                 | 1         | 1.2%    |
| Jinniu                  | 1         | 1.2%    |
| Jilin City              | 1         | 1.2%    |
| Jiaxing                 | 1         | 1.2%    |
| Jiangbei                | 1         | 1.2%    |
| Huangpu                 | 1         | 1.2%    |
| Hongyuan                | 1         | 1.2%    |
| Hohhot                  | 1         | 1.2%    |
| Harbin                  | 1         | 1.2%    |
| Guangzhou Shi           | 1         | 1.2%    |
| Dongguan                | 1         | 1.2%    |
| Dangchang Chengguanzhen | 1         | 1.2%    |
| Chengxiang              | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 17.02%  |
| WDC                 | 10        | 13     | 10.64%  |
| Seagate             | 9         | 10     | 9.57%   |
| Toshiba             | 7         | 8      | 7.45%   |
| HGST                | 4         | 4      | 4.26%   |
| Silicon Motion      | 3         | 3      | 3.19%   |
| SanDisk             | 3         | 3      | 3.19%   |
| Kingston            | 3         | 3      | 3.19%   |
| Intel               | 3         | 6      | 3.19%   |
| Hikvision           | 3         | 3      | 3.19%   |
| SK hynix            | 2         | 2      | 2.13%   |
| Plextor             | 2         | 2      | 2.13%   |
| Netac               | 2         | 2      | 2.13%   |
| Lenovo              | 2         | 2      | 2.13%   |
| KIOXIA              | 2         | 2      | 2.13%   |
| Hitachi             | 2         | 3      | 2.13%   |
| FORESEE             | 2         | 2      | 2.13%   |
| Crucial             | 2         | 2      | 2.13%   |
| UMIS                | 1         | 1      | 1.06%   |
| Topmore             | 1         | 1      | 1.06%   |
| SSSTC               | 1         | 1      | 1.06%   |
| SemsoTai            | 1         | 1      | 1.06%   |
| Pioneer             | 1         | 1      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| Lexar               | 1         | 1      | 1.06%   |
| KIOXIA-EXCERIA      | 1         | 3      | 1.06%   |
| KingSpec            | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| faspeed             | 1         | 1      | 1.06%   |
| Fanxiang            | 1         | 2      | 1.06%   |
| Colorful            | 1         | 1      | 1.06%   |
| China               | 1         | 2      | 1.06%   |
| BR                  | 1         | 1      | 1.06%   |
| Apple               | 1         | 1      | 1.06%   |
| A-DATA Technology   | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB                  | 2         | 2.02%   |
| SanDisk SSD U100 24GB                           | 2         | 2.02%   |
| Samsung SSD 970 EVO Plus 1TB                    | 2         | 2.02%   |
| Samsung SSD 870 EVO 1TB                         | 2         | 2.02%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 2.02%   |
| Samsung SSD 850 EVO 120GB                       | 2         | 2.02%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                  | 2         | 2.02%   |
| Hikvision HS-SSD-C2000ECO 1024G                 | 2         | 2.02%   |
| HGST HTS541010B7E610 1TB                        | 2         | 2.02%   |
| FORESEE P900F256GB                              | 2         | 2.02%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 1.01%   |
| WDC WDS100T3X0C-00SJG0 1TB                      | 1         | 1.01%   |
| WDC WD5000LPCX-00VHAT0 500GB                    | 1         | 1.01%   |
| WDC WD3200BPVT-75ZEST0 320GB                    | 1         | 1.01%   |
| WDC WD2500BEVS-08VAT2 250GB                     | 1         | 1.01%   |
| WDC WD20SPZX-75UA7T0 2TB                        | 1         | 1.01%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 1.01%   |
| WDC WD10JPVX-00JC3T0 1TB                        | 1         | 1.01%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB            | 1         | 1.01%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB            | 1         | 1.01%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB            | 1         | 1.01%   |
| UMIS RPJYJ512MKN1QWQ 512GB                      | 1         | 1.01%   |
| Toshiba THNSNK128GVN8 128GB                     | 1         | 1.01%   |
| Toshiba THNSNF128GCSS 128GB                     | 1         | 1.01%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.01%   |
| Toshiba MQ02ABF050H-SSHD-8GB                    | 1         | 1.01%   |
| Toshiba MQ01ACF050 500GB                        | 1         | 1.01%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.01%   |
| Toshiba KXG6APNV2T04 2TB                        | 1         | 1.01%   |
| Topmore capricornus 2TB                         | 1         | 1.01%   |
| SSSTC CL1-3D256 256GB                           | 1         | 1.01%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB         | 1         | 1.01%   |
| SK hynix BC511 NVMe 512GB                       | 1         | 1.01%   |
| Silicon Motion T70 2242 1TB                     | 1         | 1.01%   |
| Silicon Motion PCIe-8 SSD 512GB                 | 1         | 1.01%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 1.01%   |
| SemsoTai L150 SSD 1TB                           | 1         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.01%   |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1.01%   |
| Seagate ST500LM030-2E717D 500GB                 | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 36%     |
| WDC     | 6         | 6      | 24%     |
| Toshiba | 4         | 4      | 16%     |
| HGST    | 4         | 4      | 16%     |
| Hitachi | 2         | 3      | 8%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 21.05%  |
| Kingston            | 3         | 3      | 7.89%   |
| Intel               | 3         | 6      | 7.89%   |
| Toshiba             | 2         | 2      | 5.26%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Plextor             | 2         | 2      | 5.26%   |
| Netac               | 2         | 2      | 5.26%   |
| Lenovo              | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| SemsoTai            | 1         | 1      | 2.63%   |
| Phison              | 1         | 1      | 2.63%   |
| Lexar               | 1         | 1      | 2.63%   |
| KIOXIA-EXCERIA      | 1         | 3      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| faspeed             | 1         | 1      | 2.63%   |
| Fanxiang            | 1         | 2      | 2.63%   |
| Crucial             | 1         | 1      | 2.63%   |
| China               | 1         | 2      | 2.63%   |
| BR                  | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 36        | 45     | 40.91%  |
| NVMe | 29        | 37     | 32.95%  |
| HDD  | 23        | 27     | 26.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 72     | 63.75%  |
| NVMe | 29        | 37     | 36.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 52     | 66.07%  |
| 0.51-1.0   | 16        | 17     | 28.57%  |
| 1.01-2.0   | 3         | 3      | 5.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 24        | 28.92%  |
| 251-500    | 20        | 24.1%   |
| 101-250    | 16        | 19.28%  |
| 501-1000   | 6         | 7.23%   |
| 51-100     | 6         | 7.23%   |
| 21-50      | 5         | 6.02%   |
| 1001-2000  | 4         | 4.82%   |
| Unknown    | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 67        | 81.71%  |
| 21-50   | 7         | 8.54%   |
| 251-500 | 3         | 3.66%   |
| 51-100  | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| 101-250 | 1         | 1.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 14.29%  |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 14.29%  |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 14.29%  |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 14.29%  |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 14.29%  |
| Fanxiang S101-240GB             | 1         | 1      | 14.29%  |
| China JWX 16GB MSATA            | 1         | 2      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 28.57%  |
| WDC      | 1         | 1      | 14.29%  |
| Toshiba  | 1         | 1      | 14.29%  |
| Hitachi  | 1         | 1      | 14.29%  |
| Fanxiang | 1         | 1      | 14.29%  |
| China    | 1         | 2      | 14.29%  |

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
| HDD  | 5         | 5      | 71.43%  |
| SSD  | 2         | 3      | 28.57%  |

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
| Works   | 69        | 101    | 90.79%  |
| Malfunc | 7         | 8      | 9.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 57        | 57%     |
| Samsung Electronics                     | 11        | 11%     |
| SanDisk                                 | 6         | 6%      |
| Silicon Motion                          | 5         | 5%      |
| MAXIO Technology (Hangzhou)             | 3         | 3%      |
| INNOGRIT                                | 3         | 3%      |
| AMD                                     | 3         | 3%      |
| Solid State Storage Technology          | 2         | 2%      |
| SK hynix                                | 2         | 2%      |
| Marvell Technology Group                | 2         | 2%      |
| KIOXIA                                  | 2         | 2%      |
| Toshiba                                 | 1         | 1%      |
| Shenzhen Unionmemory Information System | 1         | 1%      |
| Shenzhen Longsys Electronics            | 1         | 1%      |
| Micron/Crucial Technology               | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 12.75%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 10.78%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 5.88%   |
| Unknown                                                                        | 4         | 3.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 2.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 2.94%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.94%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.96%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.98%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.98%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.98%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.98%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                         | 1         | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.98%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.98%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 0.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.98%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.98%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.98%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.98%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 0.98%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 0.98%   |
| INNOGRIT NVMe SSD Controller IG5220 (DRAM-less)                                | 1         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 60%     |
| NVMe | 33        | 34.74%  |
| RAID | 3         | 3.16%   |
| IDE  | 2         | 2.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 91.25%  |
| AMD    | 7         | 8.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 6.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 3.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 3.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 3.75%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 2.5%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 2.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.5%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 2.5%    |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 1.25%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 1.25%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1.25%   |
| Intel CPU Version                             | 1         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.25%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.25%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.25%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.25%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 1.25%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.25%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.25%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 1.25%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.25%   |
| Intel Core i7-2637M CPU                       | 1         | 1.25%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.25%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.25%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.25%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.25%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.25%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.25%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.25%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.25%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 43.75%  |
| Intel Core i7           | 14        | 17.5%   |
| Other                   | 10        | 12.5%   |
| Intel Core i3           | 7         | 8.75%   |
| Intel Celeron           | 3         | 3.75%   |
| AMD Ryzen 5             | 3         | 3.75%   |
| Intel Pentium           | 2         | 2.5%    |
| AMD Ryzen 7             | 2         | 2.5%    |
| Intel Xeon              | 1         | 1.25%   |
| Intel Core 2 Duo        | 1         | 1.25%   |
| Intel Celeron Dual-Core | 1         | 1.25%   |
| AMD Ryzen 9             | 1         | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 40        | 50%     |
| 4       | 27        | 33.75%  |
| 6       | 5         | 6.25%   |
| 16      | 3         | 3.75%   |
| 8       | 2         | 2.5%    |
| 24      | 1         | 1.25%   |
| 10      | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 60        | 75%     |
| 1       | 19        | 23.75%  |
| Unknown | 1         | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 24        | 30%     |
| SandyBridge | 9         | 11.25%  |
| IvyBridge   | 9         | 11.25%  |
| Skylake     | 8         | 10%     |
| TigerLake   | 6         | 7.5%    |
| Haswell     | 5         | 6.25%   |
| Zen 2       | 3         | 3.75%   |
| Penryn      | 3         | 3.75%   |
| CometLake   | 3         | 3.75%   |
| Zen+        | 2         | 2.5%    |
| Broadwell   | 2         | 2.5%    |
| Unknown     | 2         | 2.5%    |
| Zen 3       | 1         | 1.25%   |
| Westmere    | 1         | 1.25%   |
| Silvermont  | 1         | 1.25%   |
| K10         | 1         | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 61.06%  |
| Nvidia | 30        | 26.55%  |
| AMD    | 14        | 12.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 7.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 7.08%   |
| Intel UHD Graphics 620                                                        | 6         | 5.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 5.31%   |
| Intel HD Graphics 620                                                         | 6         | 5.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 3.54%   |
| Nvidia GP108M [GeForce MX150]                                                 | 3         | 2.65%   |
| Intel HD Graphics 530                                                         | 3         | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 2.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 2.65%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 3         | 2.65%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 1.77%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 1.77%   |
| Intel HD Graphics 630                                                         | 2         | 1.77%   |
| Intel HD Graphics 5500                                                        | 2         | 1.77%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 2         | 1.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.77%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.88%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 1         | 0.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.88%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.88%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.88%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.88%   |
| Nvidia GK107M [GeForce GT 640M LE]                                            | 1         | 0.88%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.88%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 0.88%   |
| Nvidia G96CM [GeForce GT 220M]                                                | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 45%     |
| Intel + Nvidia | 25        | 31.25%  |
| Intel + AMD    | 7         | 8.75%   |
| 1 x AMD        | 6         | 7.5%    |
| 1 x Nvidia     | 4         | 5%      |
| 2 x Intel      | 1         | 1.25%   |
| AMD + Nvidia   | 1         | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 83.75%  |
| Proprietary | 9         | 11.25%  |
| Unknown     | 4         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 85.19%  |
| 0.01-0.5   | 5         | 6.17%   |
| 0.51-1.0   | 4         | 4.94%   |
| 7.01-8.0   | 2         | 2.47%   |
| 1.01-2.0   | 1         | 1.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 19.3%   |
| Chimei Innolux          | 10        | 17.54%  |
| BOE                     | 8         | 14.04%  |
| AU Optronics            | 7         | 12.28%  |
| Samsung Electronics     | 3         | 5.26%   |
| CSO                     | 3         | 5.26%   |
| PANDA                   | 2         | 3.51%   |
| Lenovo                  | 2         | 3.51%   |
| Chi Mei Optoelectronics | 2         | 3.51%   |
| TMX                     | 1         | 1.75%   |
| Panasonic               | 1         | 1.75%   |
| LGD                     | 1         | 1.75%   |
| HPN                     | 1         | 1.75%   |
| Hewlett-Packard         | 1         | 1.75%   |
| Dell                    | 1         | 1.75%   |
| Daewoo                  | 1         | 1.75%   |
| Apple                   | 1         | 1.75%   |
| Unknown                 | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 2         | 3.51%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 3.51%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 290x170mm 13.2-inch    | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 1.75%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 1.75%   |
| LGD LCD Monitor 3840x1080                                                | 1         | 1.75%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 1.75%   |
| HPN LCD Monitor OMEN 25i                                                 | 1         | 1.75%   |
| Hewlett-Packard LCD Monitor Inc. OMEN 25i                                | 1         | 1.75%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 1.75%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                        | 1         | 1.75%   |
| CSO LCD Monitor CSO1408 3120x2080 300x200mm 14.2-inch                    | 1         | 1.75%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 1.75%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                    | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 1.75%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 38.18%  |
| 1366x768 (WXGA)   | 19        | 34.55%  |
| 1600x900 (HD+)    | 3         | 5.45%   |
| 3840x2160 (4K)    | 2         | 3.64%   |
| 2560x1600         | 2         | 3.64%   |
| 3840x1080         | 1         | 1.82%   |
| 3200x2000         | 1         | 1.82%   |
| 3120x2080         | 1         | 1.82%   |
| 2880x1800         | 1         | 1.82%   |
| 2560x1440 (QHD)   | 1         | 1.82%   |
| 1920x1200 (WUXGA) | 1         | 1.82%   |
| 1280x1024 (SXGA)  | 1         | 1.82%   |
| Unknown           | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 25        | 46.3%   |
| 15      | 18        | 33.33%  |
| 12      | 3         | 5.56%   |
| 16      | 2         | 3.7%    |
| 14      | 2         | 3.7%    |
| 24      | 1         | 1.85%   |
| 21      | 1         | 1.85%   |
| 17      | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 68.52%  |
| 201-300     | 11        | 20.37%  |
| 351-400     | 3         | 5.56%   |
| 501-600     | 1         | 1.85%   |
| 401-500     | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 46        | 86.79%  |
| 16/10   | 5         | 9.43%   |
| 3/2     | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 40.74%  |
| 91-100         | 15        | 27.78%  |
| 71-80          | 4         | 7.41%   |
| 61-70          | 3         | 5.56%   |
| 111-120        | 3         | 5.56%   |
| 101-110        | 3         | 5.56%   |
| 201-250        | 1         | 1.85%   |
| 151-200        | 1         | 1.85%   |
| 121-130        | 1         | 1.85%   |
| Unknown        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 48.15%  |
| 101-120       | 14        | 25.93%  |
| 161-240       | 7         | 12.96%  |
| More than 240 | 3         | 5.56%   |
| 51-100        | 3         | 5.56%   |
| Unknown       | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 74.07%  |
| 0     | 19        | 23.46%  |
| 2     | 2         | 2.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 48.31%  |
| Realtek Semiconductor | 37        | 31.36%  |
| Qualcomm Atheros      | 14        | 11.86%  |
| Broadcom              | 6         | 5.08%   |
| Qualcomm Technologies | 1         | 0.85%   |
| Qualcomm              | 1         | 0.85%   |
| OPPO Electronics      | 1         | 0.85%   |
| Edimax Technology     | 1         | 0.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27        | 18.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.08%   |
| Intel Wireless 8265 / 8275                                             | 6         | 4.08%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 4.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 3.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 2.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.04%   |
| Intel Wireless 8260                                                    | 3         | 2.04%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 2.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2         | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.36%   |
| Intel Wireless 7260                                                    | 2         | 1.36%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.36%   |
| Intel Centrino Wireless-N 2200                                         | 2         | 1.36%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 2         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.36%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.68%   |
| Qualcomm FP3                                                           | 1         | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.68%   |
| OPPO PGCM10 RNDIS Control RNDIS Ethernet Data                          | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 64.2%   |
| Qualcomm Atheros      | 13        | 16.05%  |
| Realtek Semiconductor | 9         | 11.11%  |
| Broadcom              | 5         | 6.17%   |
| Qualcomm Technologies | 1         | 1.23%   |
| Edimax Technology     | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 6         | 7.32%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 7.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 6.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 4.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 4.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.66%   |
| Intel Wireless 8260                                               | 3         | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 3.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.44%   |
| Intel Wireless 7260                                               | 2         | 2.44%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.44%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 2.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.22%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.22%   |
| Intel Wireless 7265                                               | 1         | 1.22%   |
| Intel Wireless 3165                                               | 1         | 1.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]         | 1         | 1.22%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]           | 1         | 1.22%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.22%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.22%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.22%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 1         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 50.77%  |
| Intel                 | 24        | 36.92%  |
| Qualcomm Atheros      | 4         | 6.15%   |
| Broadcom              | 2         | 3.08%   |
| Qualcomm              | 1         | 1.54%   |
| OPPO Electronics      | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27        | 41.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 10.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 9.23%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 4.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 4.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 3.08%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 3.08%   |
| Qualcomm FP3                                                           | 1         | 1.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.54%   |
| OPPO PGCM10 RNDIS Control RNDIS Ethernet Data                          | 1         | 1.54%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.54%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.54%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.54%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.54%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.54%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 55%     |
| Ethernet | 63        | 45%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 50.52%  |
| WiFi     | 48        | 49.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 72.5%   |
| 1     | 18        | 22.5%   |
| 6     | 3         | 3.75%   |
| 3     | 1         | 1.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 93.75%  |
| Yes  | 5         | 6.25%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 64.52%  |
| Broadcom                        | 5         | 8.06%   |
| Qualcomm Atheros Communications | 3         | 4.84%   |
| Lite-On Technology              | 3         | 4.84%   |
| Foxconn / Hon Hai               | 3         | 4.84%   |
| Cambridge Silicon Radio         | 2         | 3.23%   |
| Apple                           | 2         | 3.23%   |
| Skylight Digital                | 1         | 1.61%   |
| Realtek Semiconductor           | 1         | 1.61%   |
| IMC Networks                    | 1         | 1.61%   |
| Alps Electric                   | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 15        | 24.19%  |
| Intel AX201 Bluetooth                                | 12        | 19.35%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 5         | 8.06%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4         | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 4         | 6.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 3.23%   |
| Intel AX200 Bluetooth                                | 2         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 2         | 3.23%   |
| Apple Bluetooth Host Controller                      | 2         | 3.23%   |
| Skylight Digital Realtek Bluetooth Adapter           | 1         | 1.61%   |
| Realtek Bluetooth 4.0 Adapter                        | 1         | 1.61%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE  | 1         | 1.61%   |
| Lite-On Realtek Bluetooth Adapter                    | 1         | 1.61%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS          | 1         | 1.61%   |
| Lite-On BCM43142A0 Bluetooth Module                  | 1         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 1.61%   |
| Intel AX211 Bluetooth                                | 1         | 1.61%   |
| Intel AX210 Bluetooth                                | 1         | 1.61%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS     | 1         | 1.61%   |
| Foxconn / Hon Hai Qualcomm WCN685x Bluetooth Adapter | 1         | 1.61%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device      | 1         | 1.61%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth           | 1         | 1.61%   |
| Alps Electric UGTZ4 Bluetooth                        | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 82.56%  |
| Nvidia | 8         | 9.3%    |
| AMD    | 7         | 8.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 16.33%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 12.24%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 4.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.04%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.04%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.04%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.02%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 1.02%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.02%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 33        | 32.35%  |
| SK hynix             | 22        | 21.57%  |
| Micron Technology    | 11        | 10.78%  |
| Kingston             | 11        | 10.78%  |
| Ramaxel Technology   | 4         | 3.92%   |
| Unknown              | 3         | 2.94%   |
| Unknown              | 3         | 2.94%   |
| Transcend            | 2         | 1.96%   |
| Crucial              | 2         | 1.96%   |
| A-DATA Technology    | 2         | 1.96%   |
| Unknown (8AFD)       | 1         | 0.98%   |
| Unknown (08B5)       | 1         | 0.98%   |
| Team                 | 1         | 0.98%   |
| SemsoTai             | 1         | 0.98%   |
| Nanya Technology     | 1         | 0.98%   |
| Lenovo               | 1         | 0.98%   |
| KingTiger            | 1         | 0.98%   |
| Guangzhou MiaoYuanJi | 1         | 0.98%   |
| Elpida               | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 3.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 3.6%    |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 3         | 2.7%    |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 3         | 2.7%    |
| Unknown                                                      | 3         | 2.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.8%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s          | 2         | 1.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 2         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 1.8%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 0.9%    |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s     | 1         | 0.9%    |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s  | 1         | 0.9%    |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 0.9%    |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s       | 1         | 0.9%    |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.9%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.9%    |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.9%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.9%    |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.9%    |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 0.9%    |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s          | 1         | 0.9%    |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s        | 1         | 0.9%    |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s        | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 0.9%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 0.9%    |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.9%    |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s          | 1         | 0.9%    |
| SemsoTai RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 0.9%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 0.9%    |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                  | 1         | 0.9%    |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s        | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 48.75%  |
| DDR3    | 30        | 37.5%   |
| LPDDR3  | 5         | 6.25%   |
| LPDDR4  | 3         | 3.75%   |
| Unknown | 2         | 2.5%    |
| DDR5    | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 81.01%  |
| Row Of Chips | 13        | 16.46%  |
| Chip         | 1         | 1.27%   |
| Unknown      | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 38        | 40%     |
| 4096  | 30        | 31.58%  |
| 2048  | 14        | 14.74%  |
| 16384 | 10        | 10.53%  |
| 32768 | 2         | 2.11%   |
| 1024  | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 19.78%  |
| 2667    | 15        | 16.48%  |
| 3200    | 11        | 12.09%  |
| 2133    | 11        | 12.09%  |
| 1333    | 10        | 10.99%  |
| 2400    | 9         | 9.89%   |
| 1334    | 4         | 4.4%    |
| 4267    | 3         | 3.3%    |
| 1067    | 3         | 3.3%    |
| 800     | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| 4800    | 1         | 1.1%    |
| 1867    | 1         | 1.1%    |
| 533     | 1         | 1.1%    |

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
| Chicony Electronics                    | 21        | 32.31%  |
| Bison Electronics                      | 10        | 15.38%  |
| Realtek Semiconductor                  | 7         | 10.77%  |
| Sunplus Innovation Technology          | 4         | 6.15%   |
| IMC Networks                           | 4         | 6.15%   |
| Syntek                                 | 3         | 4.62%   |
| Quanta                                 | 2         | 3.08%   |
| Microdia                               | 2         | 3.08%   |
| Luxvisions Innotech Limited            | 2         | 3.08%   |
| Lite-On Technology                     | 2         | 3.08%   |
| Silicon Motion                         | 1         | 1.54%   |
| Qtech                                  | 1         | 1.54%   |
| Lenovo                                 | 1         | 1.54%   |
| Importek                               | 1         | 1.54%   |
| Genesys Logic                          | 1         | 1.54%   |
| Foxconn / Hon Hai                      | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.54%   |
| ALi                                    | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 8         | 11.59%  |
| Realtek Integrated_Webcam_HD                                               | 3         | 4.35%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 4.35%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 4.35%   |
| Bison ThinkPad Integrated Camera                                           | 3         | 4.35%   |
| Bison Integrated Camera                                                    | 3         | 4.35%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 2.9%    |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 2         | 2.9%    |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.9%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 2.9%    |
| IMC Networks Integrated Camera                                             | 2         | 2.9%    |
| Chicony Realtek DMFT RGB                                                   | 2         | 2.9%    |
| Chicony Integrated IR Camera                                               | 2         | 2.9%    |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 2.9%    |
| Chicony 8M Camera                                                          | 2         | 2.9%    |
| Chicony 720p HD Camera                                                     | 2         | 2.9%    |
| Bison Lenovo Integrated Webcam                                             | 2         | 2.9%    |
| Syntek Integrated Camera                                                   | 1         | 1.45%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 1.45%   |
| Realtek USB 2.0 PC Camera                                                  | 1         | 1.45%   |
| Realtek Integrated Webcam                                                  | 1         | 1.45%   |
| Realtek HD WebCam                                                          | 1         | 1.45%   |
| Realtek Front Camera                                                       | 1         | 1.45%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 1.45%   |
| Quanta ov9734_techfront_camera                                             | 1         | 1.45%   |
| Qtech USB Camera                                                           | 1         | 1.45%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 1.45%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.45%   |
| Lite-On Integrated Camera                                                  | 1         | 1.45%   |
| Lite-On HP HD Camera                                                       | 1         | 1.45%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.45%   |
| Importek USB 2.0 Camera                                                    | 1         | 1.45%   |
| IMC Networks Realtek PC Camera                                             | 1         | 1.45%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.45%   |
| Genesys Logic Camera                                                       | 1         | 1.45%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 1.45%   |
| Chicony HD WebCam                                                          | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.45%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 1.45%   |
| Bison Lenovo EasyCamera                                                    | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Synaptics                  | 5         | 29.41%  |
| Shenzhen Goodix Technology | 2         | 11.76%  |
| Upek                       | 1         | 5.88%   |
| Fingerprint Cards          | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                            | 4         | 23.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 11.76%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 11.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 5.88%   |
| Fingerprint Cards FPC Fingerprint Reader                                   | 1         | 5.88%   |

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
| 2     | 23        | 28.4%   |
| 1     | 23        | 28.4%   |
| 3     | 21        | 25.93%  |
| 0     | 8         | 9.88%   |
| 4     | 6         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 68        | 46.9%   |
| Bluetooth                | 23        | 15.86%  |
| Net/wireless             | 17        | 11.72%  |
| Fingerprint reader       | 17        | 11.72%  |
| Card reader              | 17        | 11.72%  |
| Sound                    | 3         | 2.07%   |

