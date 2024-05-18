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

Total: 111

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | Legion Y7000P 81HC          | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | [34ab895e86](https://bsd-hardware.info/?probe=34ab895e86) | Mar 15, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
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
| Lenovo        | Legion Y7000P 81HC          | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
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
| FreeBSD 13.1         | 9         | 10%     |
| helloSystem 0.8.0    | 8         | 8.89%   |
| helloSystem 0.7.0    | 8         | 8.89%   |
| helloSystem 0.8.1    | 7         | 7.78%   |
| helloSystem 0.5.0    | 5         | 5.56%   |
| FreeBSD 14.0-CURRENT | 5         | 5.56%   |
| FreeBSD 13.2         | 4         | 4.44%   |
| FreeBSD 12.2         | 4         | 4.44%   |
| helloSystem 0.6.0    | 3         | 3.33%   |
| helloSystem 0.4.0    | 3         | 3.33%   |
| OPNsense 21.1.1      | 2         | 2.22%   |
| NomadBSD 5806f915    | 2         | 2.22%   |
| GhostBSD 21.08.27    | 2         | 2.22%   |
| FreeBSD 14.0         | 2         | 2.22%   |
| FreeBSD 13.0-p7      | 2         | 2.22%   |
| FreeBSD 13.0-p4      | 2         | 2.22%   |
| FreeBSD 13.0         | 2         | 2.22%   |
| OPNsense 22.7        | 1         | 1.11%   |
| OPNsense 21.1        | 1         | 1.11%   |
| OPNsense 20.7.8      | 1         | 1.11%   |
| OpenBSD 7.3          | 1         | 1.11%   |
| OpenBSD 7.0          | 1         | 1.11%   |
| NomadBSD 1.3.1       | 1         | 1.11%   |
| NetBSD 9.3           | 1         | 1.11%   |
| helloSystem 0.9.0    | 1         | 1.11%   |
| FreeBSD 14.0-p2      | 1         | 1.11%   |
| FreeBSD 14.0-BETA5   | 1         | 1.11%   |
| FreeBSD 13.1-STABLE  | 1         | 1.11%   |
| FreeBSD 13.1-RC3     | 1         | 1.11%   |
| FreeBSD 13.1-p5      | 1         | 1.11%   |
| FreeBSD 13.1-p2      | 1         | 1.11%   |
| FreeBSD 13.0-STABLE  | 1         | 1.11%   |
| FreeBSD 13.0-RC1     | 1         | 1.11%   |
| FreeBSD 13.0-p3      | 1         | 1.11%   |
| FreeBSD 13.0-p2      | 1         | 1.11%   |
| FreeBSD 12.2-p10     | 1         | 1.11%   |
| FreeBSD 12.1-p7      | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 39        | 46.43%  |
| helloSystem | 33        | 39.29%  |
| OPNsense    | 4         | 4.76%   |
| NomadBSD    | 3         | 3.57%   |
| OpenBSD     | 2         | 2.38%   |
| GhostBSD    | 2         | 2.38%   |
| NetBSD      | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 33        | 37.5%   |
| XFCE         | 13        | 14.77%  |
| Console      | 10        | 11.36%  |
| KDE5         | 9         | 10.23%  |
| GNOME        | 5         | 5.68%   |
| TWM          | 4         | 4.55%   |
| i3           | 4         | 4.55%   |
| Openbox      | 3         | 3.41%   |
| MATE         | 3         | 3.41%   |
| AwesomeWM    | 2         | 2.27%   |
| fvwm         | 1         | 1.14%   |
| DWM          | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 73        | 86.9%   |
| Console | 10        | 11.9%   |
| Wayland | 1         | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 43        | 50%     |
| Console | 20        | 23.26%  |
| SDDM    | 8         | 9.3%    |
| LightDM | 7         | 8.14%   |
| GDM     | 5         | 5.81%   |
| XDM     | 3         | 3.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 28        | 31.11%  |
| zh_CN        | 21        | 23.33%  |
| C            | 21        | 23.33%  |
| Unknown      | 17        | 18.89%  |
| en           | 2         | 2.22%   |
| zh_CN.GB2312 | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 89.16%  |
| BIOS | 9         | 10.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 46        | 52.87%  |
| Ufs    | 25        | 28.74%  |
| Cd9660 | 14        | 16.09%  |
| Ffs    | 2         | 2.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 78        | 93.98%  |
| MBR  | 5         | 6.02%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 40.24%  |
| Dell                | 8         | 9.76%   |
| Hewlett-Packard     | 6         | 7.32%   |
| ASUSTek Computer    | 5         | 6.1%    |
| Unknown             | 4         | 4.88%   |
| Notebook            | 3         | 3.66%   |
| Google              | 3         | 3.66%   |
| Timi                | 2         | 2.44%   |
| Sony                | 2         | 2.44%   |
| Panasonic           | 2         | 2.44%   |
| MECHREVO S1 Series  | 2         | 2.44%   |
| HUAWEI              | 2         | 2.44%   |
| HASEE Computer      | 2         | 2.44%   |
| Acer                | 2         | 2.44%   |
| WOOKING             | 1         | 1.22%   |
| Toshiba             | 1         | 1.22%   |
| Samsung Electronics | 1         | 1.22%   |
| NEC Computers       | 1         | 1.22%   |
| Intel               | 1         | 1.22%   |
| Apple               | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 5         | 6.1%    |
| MECHREVO S1 Series S1 Series                | 2         | 2.44%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 2.44%   |
| Google Kohaku                               | 2         | 2.44%   |
| WOOKING X5                                  | 1         | 1.22%   |
| Toshiba Satellite Pro L510                  | 1         | 1.22%   |
| Timi RedmiBook Pro 15                       | 1         | 1.22%   |
| Timi A34R                                   | 1         | 1.22%   |
| Sony SVS1511AJB                             | 1         | 1.22%   |
| Sony SVP13225SCBI                           | 1         | 1.22%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 1.22%   |
| Panasonic CF-NX1GDHYS                       | 1         | 1.22%   |
| Panasonic CF-B11JWCYS                       | 1         | 1.22%   |
| Notebook W65KJ1_KK1                         | 1         | 1.22%   |
| Notebook W650DC,DD                          | 1         | 1.22%   |
| Notebook N960Kx                             | 1         | 1.22%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 1.22%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 1.22%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 1.22%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 1.22%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7         | 1         | 1.22%   |
| Lenovo ThinkPad X270 20HNA04GCD             | 1         | 1.22%   |
| Lenovo ThinkPad X230 2324A14                | 1         | 1.22%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 1.22%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002LUS    | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 1.22%   |
| Lenovo ThinkPad X1 Carbon 3448AWU           | 1         | 1.22%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 1.22%   |
| Lenovo ThinkPad T480 20L5000UUS             | 1         | 1.22%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 1.22%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 1.22%   |
| Lenovo ThinkPad T430 2342AG4                | 1         | 1.22%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 1.22%   |
| Lenovo ThinkPad R14 Gen 4 21E5A05RCD        | 1         | 1.22%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 1.22%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 1.22%   |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 1.22%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 1.22%   |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 20        | 24.39%  |
| Unknown                    | 5         | 6.1%    |
| Dell Latitude              | 4         | 4.88%   |
| MECHREVO S1 Series S1      | 2         | 2.44%   |
| Lenovo IdeaPad             | 2         | 2.44%   |
| HP ProBook                 | 2         | 2.44%   |
| Google Kohaku              | 2         | 2.44%   |
| Dell Inspiron              | 2         | 2.44%   |
| WOOKING X5                 | 1         | 1.22%   |
| Toshiba Satellite          | 1         | 1.22%   |
| Timi RedmiBook             | 1         | 1.22%   |
| Timi A34R                  | 1         | 1.22%   |
| Sony SVS1511AJB            | 1         | 1.22%   |
| Sony SVP13225SCBI          | 1         | 1.22%   |
| Samsung 3570R              | 1         | 1.22%   |
| Panasonic CF-NX1GDHYS      | 1         | 1.22%   |
| Panasonic CF-B11JWCYS      | 1         | 1.22%   |
| Notebook W65KJ1            | 1         | 1.22%   |
| Notebook W650DC            | 1         | 1.22%   |
| Notebook N960Kx            | 1         | 1.22%   |
| NEC Computers PC-VK17HBBCD | 1         | 1.22%   |
| Lenovo ZhaoYang            | 1         | 1.22%   |
| Lenovo XiaoXinPro-13ARE    | 1         | 1.22%   |
| Lenovo XiaoXinPro-13API    | 1         | 1.22%   |
| Lenovo XiaoXinAir          | 1         | 1.22%   |
| Lenovo Rescuer-15ISK       | 1         | 1.22%   |
| Lenovo Legion              | 1         | 1.22%   |
| Lenovo G480                | 1         | 1.22%   |
| Lenovo G470                | 1         | 1.22%   |
| Lenovo B590                | 1         | 1.22%   |
| Lenovo B470                | 1         | 1.22%   |
| Lenovo B41-80              | 1         | 1.22%   |
| Intel H81U                 | 1         | 1.22%   |
| HUAWEI NBLL-WXX9           | 1         | 1.22%   |
| HUAWEI HLY-WX9XX           | 1         | 1.22%   |
| HP Pavilion                | 1         | 1.22%   |
| HP OMEN                    | 1         | 1.22%   |
| HP Laptop                  | 1         | 1.22%   |
| HASEE N95XKP6              | 1         | 1.22%   |
| HASEE CW35S                | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 10        | 12.2%   |
| 2021 | 10        | 12.2%   |
| 2012 | 9         | 10.98%  |
| 2019 | 8         | 9.76%   |
| 2018 | 8         | 9.76%   |
| 2017 | 8         | 9.76%   |
| 2013 | 7         | 8.54%   |
| 2020 | 5         | 6.1%    |
| 2016 | 5         | 6.1%    |
| 2011 | 4         | 4.88%   |
| 2015 | 3         | 3.66%   |
| 2009 | 2         | 2.44%   |
| 2024 | 1         | 1.22%   |
| 2023 | 1         | 1.22%   |
| 2010 | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 96.34%  |
| Yes  | 3         | 3.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 31        | 37.8%   |
| 4.01-8.0    | 21        | 25.61%  |
| 16.01-24.0  | 18        | 21.95%  |
| 32.01-64.0  | 6         | 7.32%   |
| 24.01-32.0  | 5         | 6.1%    |
| 64.01-256.0 | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 43        | 52.44%  |
| 0.51-1.0 | 21        | 25.61%  |
| 1.01-2.0 | 15        | 18.29%  |
| 2.01-3.0 | 2         | 2.44%   |
| Unknown  | 1         | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 61.63%  |
| 2      | 20        | 23.26%  |
| 0      | 10        | 11.63%  |
| 3      | 3         | 3.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 79.52%  |
| Yes       | 17        | 20.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 78.05%  |
| No        | 18        | 21.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 96.34%  |
| No        | 3         | 3.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 78.05%  |
| No        | 18        | 21.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 82        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Shanghai              | 9         | 10.47%  |
| Guangzhou             | 7         | 8.14%   |
| Shenzhen              | 6         | 6.98%   |
| Chengdu               | 6         | 6.98%   |
| Beijing               | 6         | 6.98%   |
| Hangzhou              | 5         | 5.81%   |
| Wuhan                 | 3         | 3.49%   |
| Zhengzhou             | 2         | 2.33%   |
| Yuzhong Chengguanzhen | 2         | 2.33%   |
| Xi'an                 | 2         | 2.33%   |
| Qiqihar               | 2         | 2.33%   |
| Nanjing               | 2         | 2.33%   |
| Chongqing             | 2         | 2.33%   |
| Changzhou             | 2         | 2.33%   |
| Zhumadian             | 1         | 1.16%   |
| Zhaoqing              | 1         | 1.16%   |
| Yichun                | 1         | 1.16%   |
| Xiamen                | 1         | 1.16%   |
| Wuxi                  | 1         | 1.16%   |
| Weifang               | 1         | 1.16%   |
| Taizhou               | 1         | 1.16%   |
| Shizishan             | 1         | 1.16%   |
| Shantou               | 1         | 1.16%   |
| Qinnan                | 1         | 1.16%   |
| Putian                | 1         | 1.16%   |
| Pudong                | 1         | 1.16%   |
| Nanning               | 1         | 1.16%   |
| Linyi                 | 1         | 1.16%   |
| Lanzhou               | 1         | 1.16%   |
| Jinniu                | 1         | 1.16%   |
| Jilin City            | 1         | 1.16%   |
| Jiaxing               | 1         | 1.16%   |
| Jiangbei              | 1         | 1.16%   |
| Huangpu               | 1         | 1.16%   |
| Hongyuan              | 1         | 1.16%   |
| Hohhot                | 1         | 1.16%   |
| Harbin                | 1         | 1.16%   |
| Guiyang               | 1         | 1.16%   |
| Guangzhou Shi         | 1         | 1.16%   |
| Dongguan              | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 19     | 17.71%  |
| WDC                 | 11        | 14     | 11.46%  |
| Seagate             | 9         | 10     | 9.38%   |
| Toshiba             | 7         | 8      | 7.29%   |
| HGST                | 4         | 4      | 4.17%   |
| Silicon Motion      | 3         | 3      | 3.13%   |
| SanDisk             | 3         | 3      | 3.13%   |
| Kingston            | 3         | 3      | 3.13%   |
| Intel               | 3         | 6      | 3.13%   |
| Hikvision           | 3         | 3      | 3.13%   |
| SK hynix            | 2         | 2      | 2.08%   |
| Plextor             | 2         | 3      | 2.08%   |
| Netac               | 2         | 2      | 2.08%   |
| Lenovo              | 2         | 2      | 2.08%   |
| KIOXIA              | 2         | 2      | 2.08%   |
| Hitachi             | 2         | 3      | 2.08%   |
| FORESEE             | 2         | 2      | 2.08%   |
| Crucial             | 2         | 2      | 2.08%   |
| UMIS                | 1         | 1      | 1.04%   |
| Topmore             | 1         | 1      | 1.04%   |
| SSSTC               | 1         | 1      | 1.04%   |
| SemsoTai            | 1         | 1      | 1.04%   |
| Pioneer             | 1         | 1      | 1.04%   |
| Phison              | 1         | 1      | 1.04%   |
| Lexar               | 1         | 1      | 1.04%   |
| KIOXIA-EXCERIA      | 1         | 3      | 1.04%   |
| KingSpec            | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| faspeed             | 1         | 1      | 1.04%   |
| Fanxiang            | 1         | 2      | 1.04%   |
| Colorful            | 1         | 1      | 1.04%   |
| China               | 1         | 2      | 1.04%   |
| BR                  | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |
| A-DATA Technology   | 1         | 1      | 1.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB                  | 2         | 1.98%   |
| SanDisk SSD U100 24GB                           | 2         | 1.98%   |
| Samsung SSD 970 EVO Plus 1TB                    | 2         | 1.98%   |
| Samsung SSD 870 EVO 1TB                         | 2         | 1.98%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 1.98%   |
| Samsung SSD 850 EVO 120GB                       | 2         | 1.98%   |
| Samsung MZVLB512HBJQ-000L2 512GB                | 2         | 1.98%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                  | 2         | 1.98%   |
| Hikvision HS-SSD-C2000ECO 1024G                 | 2         | 1.98%   |
| HGST HTS541010B7E610 1TB                        | 2         | 1.98%   |
| FORESEE P900F256GB                              | 2         | 1.98%   |
| WDC WDS480G2G0A-00JH30 480GB                    | 1         | 0.99%   |
| WDC WDS100T3X0C-00SJG0 1TB                      | 1         | 0.99%   |
| WDC WD5000LPCX-00VHAT0 500GB                    | 1         | 0.99%   |
| WDC WD3200BPVT-75ZEST0 320GB                    | 1         | 0.99%   |
| WDC WD2500BEVS-08VAT2 250GB                     | 1         | 0.99%   |
| WDC WD20SPZX-75UA7T0 2TB                        | 1         | 0.99%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 0.99%   |
| WDC WD10JPVX-00JC3T0 1TB                        | 1         | 0.99%   |
| WDC WD10JPCX-24UE4T0 1TB                        | 1         | 0.99%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB            | 1         | 0.99%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB            | 1         | 0.99%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB            | 1         | 0.99%   |
| UMIS RPJYJ512MKN1QWQ 512GB                      | 1         | 0.99%   |
| Toshiba THNSNK128GVN8 128GB                     | 1         | 0.99%   |
| Toshiba THNSNF128GCSS 128GB                     | 1         | 0.99%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 0.99%   |
| Toshiba MQ02ABF050H-SSHD-8GB                    | 1         | 0.99%   |
| Toshiba MQ01ACF050 500GB                        | 1         | 0.99%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 0.99%   |
| Toshiba KXG6APNV2T04 2TB                        | 1         | 0.99%   |
| Topmore capricornus 2TB                         | 1         | 0.99%   |
| SSSTC CL1-3D256 256GB                           | 1         | 0.99%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB         | 1         | 0.99%   |
| SK hynix BC511 NVMe 512GB                       | 1         | 0.99%   |
| Silicon Motion T70 2242 1TB                     | 1         | 0.99%   |
| Silicon Motion PCIe-8 SSD 512GB                 | 1         | 0.99%   |
| Silicon Motion Asgard AN2+ 256NVMe-M.2-80 256GB | 1         | 0.99%   |
| SemsoTai L150 SSD 1TB                           | 1         | 0.99%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 34.62%  |
| WDC     | 7         | 7      | 26.92%  |
| Toshiba | 4         | 4      | 15.38%  |
| HGST    | 4         | 4      | 15.38%  |
| Hitachi | 2         | 3      | 7.69%   |

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
| Plextor             | 2         | 3      | 5.26%   |
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
| SSD  | 36        | 46     | 40%     |
| NVMe | 30        | 38     | 33.33%  |
| HDD  | 24        | 28     | 26.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 74     | 63.41%  |
| NVMe | 30        | 38     | 36.59%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 37        | 52     | 64.91%  |
| 0.51-1.0   | 17        | 19     | 29.82%  |
| 1.01-2.0   | 3         | 3      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 25        | 29.07%  |
| 251-500    | 21        | 24.42%  |
| 101-250    | 16        | 18.6%   |
| 501-1000   | 7         | 8.14%   |
| 51-100     | 6         | 6.98%   |
| 21-50      | 5         | 5.81%   |
| 1001-2000  | 4         | 4.65%   |
| Unknown    | 2         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 69        | 82.14%  |
| 21-50   | 7         | 8.33%   |
| 251-500 | 3         | 3.57%   |
| 51-100  | 2         | 2.38%   |
| Unknown | 2         | 2.38%   |
| 101-250 | 1         | 1.19%   |

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
| Works   | 71        | 104    | 91.03%  |
| Malfunc | 7         | 8      | 8.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 58        | 56.86%  |
| Samsung Electronics                     | 12        | 11.76%  |
| SanDisk                                 | 6         | 5.88%   |
| Silicon Motion                          | 5         | 4.9%    |
| MAXIO Technology (Hangzhou)             | 3         | 2.94%   |
| INNOGRIT                                | 3         | 2.94%   |
| AMD                                     | 3         | 2.94%   |
| Solid State Storage Technology          | 2         | 1.96%   |
| SK hynix                                | 2         | 1.96%   |
| Marvell Technology Group                | 2         | 1.96%   |
| KIOXIA                                  | 2         | 1.96%   |
| Toshiba                                 | 1         | 0.98%   |
| Shenzhen Unionmemory Information System | 1         | 0.98%   |
| Shenzhen Longsys Electronics            | 1         | 0.98%   |
| Micron/Crucial Technology               | 1         | 0.98%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 13.46%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 10.58%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 6.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 5.77%   |
| Unknown                                                                        | 4         | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 2.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 2.88%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.88%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.92%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.92%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 0.96%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                    | 1         | 0.96%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 0.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.96%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                         | 1         | 0.96%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.96%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.96%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.96%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 0.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 0.96%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 0.96%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 0.96%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 0.96%   |
| INNOGRIT NVMe SSD Controller IG5220 (DRAM-less)                                | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 58        | 59.79%  |
| NVMe | 34        | 35.05%  |
| RAID | 3         | 3.09%   |
| IDE  | 2         | 2.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 74        | 90.24%  |
| AMD    | 8         | 9.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 6.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 4.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.66%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 3.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 3.66%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 2.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 2.44%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 2.44%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 2.44%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 1.22%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 1.22%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 1.22%   |
| Intel CPU Version                             | 1         | 1.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.22%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 1.22%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.22%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.22%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 1.22%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.22%   |
| Intel Core i7-2637M CPU                       | 1         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.22%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.22%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 1.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.22%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.22%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 1.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.22%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.22%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 43.9%   |
| Intel Core i7           | 14        | 17.07%  |
| Other                   | 10        | 12.2%   |
| Intel Core i3           | 7         | 8.54%   |
| AMD Ryzen 5             | 4         | 4.88%   |
| Intel Celeron           | 3         | 3.66%   |
| Intel Pentium           | 2         | 2.44%   |
| AMD Ryzen 7             | 2         | 2.44%   |
| Intel Xeon              | 1         | 1.22%   |
| Intel Core 2 Duo        | 1         | 1.22%   |
| Intel Celeron Dual-Core | 1         | 1.22%   |
| AMD Ryzen 9             | 1         | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 41        | 50%     |
| 4       | 27        | 32.93%  |
| 6       | 5         | 6.1%    |
| 16      | 3         | 3.66%   |
| 8       | 2         | 2.44%   |
| 24      | 1         | 1.22%   |
| 12      | 1         | 1.22%   |
| 10      | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 61        | 74.39%  |
| 1       | 20        | 24.39%  |
| Unknown | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 24        | 29.27%  |
| Skylake     | 9         | 10.98%  |
| SandyBridge | 9         | 10.98%  |
| IvyBridge   | 9         | 10.98%  |
| TigerLake   | 6         | 7.32%   |
| Haswell     | 5         | 6.1%    |
| Zen 2       | 3         | 3.66%   |
| Penryn      | 3         | 3.66%   |
| CometLake   | 3         | 3.66%   |
| Zen+        | 2         | 2.44%   |
| Zen 3       | 2         | 2.44%   |
| Broadwell   | 2         | 2.44%   |
| Unknown     | 2         | 2.44%   |
| Westmere    | 1         | 1.22%   |
| Silvermont  | 1         | 1.22%   |
| K10         | 1         | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 70        | 60.87%  |
| Nvidia | 30        | 26.09%  |
| AMD    | 15        | 13.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 7.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 6.96%   |
| Intel UHD Graphics 620                                                        | 6         | 5.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 5.22%   |
| Intel HD Graphics 620                                                         | 6         | 5.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 3.48%   |
| Nvidia GP108M [GeForce MX150]                                                 | 3         | 2.61%   |
| Intel HD Graphics 530                                                         | 3         | 2.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 3         | 2.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 2.61%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 3         | 2.61%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 2         | 1.74%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 1.74%   |
| Intel HD Graphics 630                                                         | 2         | 1.74%   |
| Intel HD Graphics 5500                                                        | 2         | 1.74%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 2         | 1.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.74%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.87%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 1         | 0.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.87%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.87%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.87%   |
| Nvidia GM108M [GeForce 920MX]                                                 | 1         | 0.87%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 1         | 0.87%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.87%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.87%   |
| Nvidia GK107M [GeForce GT 640M LE]                                            | 1         | 0.87%   |
| Nvidia GK106M [GeForce GTX 765M]                                              | 1         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.87%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 0.87%   |
| Nvidia G96CM [GeForce GT 220M]                                                | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 45.12%  |
| Intel + Nvidia | 25        | 30.49%  |
| Intel + AMD    | 7         | 8.54%   |
| 1 x AMD        | 7         | 8.54%   |
| 1 x Nvidia     | 4         | 4.88%   |
| 2 x Intel      | 1         | 1.22%   |
| AMD + Nvidia   | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 69        | 84.15%  |
| Proprietary | 9         | 10.98%  |
| Unknown     | 4         | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 84.34%  |
| 0.01-0.5   | 5         | 6.02%   |
| 0.51-1.0   | 4         | 4.82%   |
| 7.01-8.0   | 2         | 2.41%   |
| 1.01-2.0   | 2         | 2.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 18.64%  |
| Chimei Innolux          | 10        | 16.95%  |
| BOE                     | 9         | 15.25%  |
| AU Optronics            | 8         | 13.56%  |
| Samsung Electronics     | 3         | 5.08%   |
| CSO                     | 3         | 5.08%   |
| PANDA                   | 2         | 3.39%   |
| Lenovo                  | 2         | 3.39%   |
| Chi Mei Optoelectronics | 2         | 3.39%   |
| TMX                     | 1         | 1.69%   |
| Panasonic               | 1         | 1.69%   |
| LGD                     | 1         | 1.69%   |
| HPN                     | 1         | 1.69%   |
| Hewlett-Packard         | 1         | 1.69%   |
| Dell                    | 1         | 1.69%   |
| Daewoo                  | 1         | 1.69%   |
| Apple                   | 1         | 1.69%   |
| Unknown                 | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 2         | 3.39%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 3.39%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 290x170mm 13.2-inch    | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 1.69%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch              | 1         | 1.69%   |
| LGD LCD Monitor 3840x1080                                                | 1         | 1.69%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 1.69%   |
| HPN LCD Monitor OMEN 25i                                                 | 1         | 1.69%   |
| Hewlett-Packard LCD Monitor Inc. OMEN 25i                                | 1         | 1.69%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 1.69%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                        | 1         | 1.69%   |
| CSO LCD Monitor CSO1408 3120x2080 300x200mm 14.2-inch                    | 1         | 1.69%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 1.69%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                    | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 1.69%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 1.69%   |
| BOE LCD Monitor BOE0931 2240x1400 300x190mm 14.0-inch                    | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 22        | 38.6%   |
| 1366x768 (WXGA)   | 19        | 33.33%  |
| 1600x900 (HD+)    | 3         | 5.26%   |
| 3840x2160 (4K)    | 2         | 3.51%   |
| 2560x1600         | 2         | 3.51%   |
| 3840x1080         | 1         | 1.75%   |
| 3200x2000         | 1         | 1.75%   |
| 3120x2080         | 1         | 1.75%   |
| 2880x1800         | 1         | 1.75%   |
| 2560x1440 (QHD)   | 1         | 1.75%   |
| 2240x1400         | 1         | 1.75%   |
| 1920x1200 (WUXGA) | 1         | 1.75%   |
| 1280x1024 (SXGA)  | 1         | 1.75%   |
| Unknown           | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 26        | 46.43%  |
| 15      | 18        | 32.14%  |
| 14      | 3         | 5.36%   |
| 12      | 3         | 5.36%   |
| 16      | 2         | 3.57%   |
| 24      | 1         | 1.79%   |
| 21      | 1         | 1.79%   |
| 17      | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 67.86%  |
| 201-300     | 12        | 21.43%  |
| 351-400     | 3         | 5.36%   |
| 501-600     | 1         | 1.79%   |
| 401-500     | 1         | 1.79%   |
| Unknown     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 47        | 85.45%  |
| 16/10   | 6         | 10.91%  |
| 3/2     | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 24        | 42.86%  |
| 91-100         | 15        | 26.79%  |
| 71-80          | 4         | 7.14%   |
| 61-70          | 3         | 5.36%   |
| 111-120        | 3         | 5.36%   |
| 101-110        | 3         | 5.36%   |
| 201-250        | 1         | 1.79%   |
| 151-200        | 1         | 1.79%   |
| 121-130        | 1         | 1.79%   |
| Unknown        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 48.21%  |
| 101-120       | 14        | 25%     |
| 161-240       | 8         | 14.29%  |
| More than 240 | 3         | 5.36%   |
| 51-100        | 3         | 5.36%   |
| Unknown       | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 62        | 74.7%   |
| 0     | 19        | 22.89%  |
| 2     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 47.93%  |
| Realtek Semiconductor | 39        | 32.23%  |
| Qualcomm Atheros      | 14        | 11.57%  |
| Broadcom              | 6         | 4.96%   |
| Qualcomm Technologies | 1         | 0.83%   |
| Qualcomm              | 1         | 0.83%   |
| OPPO Electronics      | 1         | 0.83%   |
| Edimax Technology     | 1         | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 18.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 4.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4%      |
| Intel Wireless 8265 / 8275                                             | 6         | 4%      |
| Intel Wi-Fi 6 AX201                                                    | 6         | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 5         | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2%      |
| Intel Wireless 8260                                                    | 3         | 2%      |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2%      |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.33%   |
| Intel Wireless 7260                                                    | 2         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| Intel Centrino Wireless-N 2200                                         | 2         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 2         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.33%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 0.67%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.67%   |
| Qualcomm FP3                                                           | 1         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 63.86%  |
| Qualcomm Atheros      | 13        | 15.66%  |
| Realtek Semiconductor | 10        | 12.05%  |
| Broadcom              | 5         | 6.02%   |
| Qualcomm Technologies | 1         | 1.2%    |
| Edimax Technology     | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 6         | 7.14%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 7.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 5.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 5.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.57%   |
| Intel Wireless 8260                                               | 3         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.38%   |
| Intel Wireless 7260                                               | 2         | 2.38%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.38%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 2.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.38%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.19%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.19%   |
| Intel Wireless 7265                                               | 1         | 1.19%   |
| Intel Wireless 3165                                               | 1         | 1.19%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]         | 1         | 1.19%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]           | 1         | 1.19%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.19%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.19%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.19%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.19%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 51.52%  |
| Intel                 | 24        | 36.36%  |
| Qualcomm Atheros      | 4         | 6.06%   |
| Broadcom              | 2         | 3.03%   |
| Qualcomm              | 1         | 1.52%   |
| OPPO Electronics      | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 42.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 10.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 9.09%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 4.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 3.03%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 3.03%   |
| Qualcomm FP3                                                           | 1         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.52%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data         | 1         | 1.52%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.52%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.52%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.52%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.52%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.52%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 55.24%  |
| Ethernet | 64        | 44.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 50%     |
| Ethernet | 49        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 71.95%  |
| 1     | 19        | 23.17%  |
| 6     | 3         | 3.66%   |
| 3     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 93.9%   |
| Yes  | 5         | 6.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 64.06%  |
| Broadcom                        | 5         | 7.81%   |
| Qualcomm Atheros Communications | 3         | 4.69%   |
| Lite-On Technology              | 3         | 4.69%   |
| Foxconn / Hon Hai               | 3         | 4.69%   |
| Realtek Semiconductor           | 2         | 3.13%   |
| Cambridge Silicon Radio         | 2         | 3.13%   |
| Apple                           | 2         | 3.13%   |
| Skylight Digital                | 1         | 1.56%   |
| IMC Networks                    | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 16        | 25%     |
| Intel AX201 Bluetooth                                | 12        | 18.75%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 5         | 7.81%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 4         | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 2         | 3.13%   |
| Intel AX200 Bluetooth                                | 2         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 2         | 3.13%   |
| Apple Bluetooth Host Controller                      | 2         | 3.13%   |
| Skylight Digital Realtek Bluetooth Adapter           | 1         | 1.56%   |
| Realtek Bluetooth Adapter                            | 1         | 1.56%   |
| Realtek Bluetooth 4.0 Adapter                        | 1         | 1.56%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE  | 1         | 1.56%   |
| Lite-On Realtek Bluetooth Adapter                    | 1         | 1.56%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS          | 1         | 1.56%   |
| Lite-On BCM43142A0 Bluetooth Module                  | 1         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1         | 1.56%   |
| Intel AX211 Bluetooth                                | 1         | 1.56%   |
| Intel AX210 Bluetooth                                | 1         | 1.56%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS     | 1         | 1.56%   |
| Foxconn / Hon Hai Qualcomm WCN685x Bluetooth Adapter | 1         | 1.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device      | 1         | 1.56%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth           | 1         | 1.56%   |
| Alps Electric UGTZ4 Bluetooth                        | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 81.82%  |
| Nvidia | 8         | 9.09%   |
| AMD    | 8         | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 16.83%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 11.88%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 3.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.98%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.98%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.98%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.99%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 0.99%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.99%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.99%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.99%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 33        | 31.73%  |
| SK hynix             | 22        | 21.15%  |
| Micron Technology    | 12        | 11.54%  |
| Kingston             | 11        | 10.58%  |
| Ramaxel Technology   | 5         | 4.81%   |
| Unknown              | 3         | 2.88%   |
| Unknown              | 3         | 2.88%   |
| Transcend            | 2         | 1.92%   |
| Crucial              | 2         | 1.92%   |
| A-DATA Technology    | 2         | 1.92%   |
| Unknown (8AFD)       | 1         | 0.96%   |
| Unknown (08B5)       | 1         | 0.96%   |
| Team                 | 1         | 0.96%   |
| SemsoTai             | 1         | 0.96%   |
| Nanya Technology     | 1         | 0.96%   |
| Lenovo               | 1         | 0.96%   |
| KingTiger            | 1         | 0.96%   |
| Guangzhou MiaoYuanJi | 1         | 0.96%   |
| Elpida               | 1         | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 3.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 3.54%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 4         | 3.54%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 3         | 2.65%   |
| Unknown                                                      | 3         | 2.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.77%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s          | 2         | 1.77%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 1.77%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.77%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 2         | 1.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 1.77%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 0.88%   |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s     | 1         | 0.88%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s  | 1         | 0.88%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 0.88%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s       | 1         | 0.88%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.88%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.88%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 0.88%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s          | 1         | 0.88%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s        | 1         | 0.88%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s        | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 0.88%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 0.88%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.88%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s          | 1         | 0.88%   |
| SemsoTai RAM Module 16GB SODIMM DDR4 2400MT/s                | 1         | 0.88%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 0.88%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                  | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 40        | 48.78%  |
| DDR3    | 31        | 37.8%   |
| LPDDR3  | 5         | 6.1%    |
| LPDDR4  | 3         | 3.66%   |
| Unknown | 2         | 2.44%   |
| DDR5    | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 81.48%  |
| Row Of Chips | 13        | 16.05%  |
| Chip         | 1         | 1.23%   |
| Unknown      | 1         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 40.21%  |
| 4096  | 31        | 31.96%  |
| 2048  | 14        | 14.43%  |
| 16384 | 10        | 10.31%  |
| 32768 | 2         | 2.06%   |
| 1024  | 1         | 1.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 19        | 20.43%  |
| 2667    | 15        | 16.13%  |
| 3200    | 12        | 12.9%   |
| 2400    | 10        | 10.75%  |
| 2133    | 10        | 10.75%  |
| 1333    | 10        | 10.75%  |
| 1334    | 4         | 4.3%    |
| 4267    | 3         | 3.23%   |
| 1067    | 3         | 3.23%   |
| 800     | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |
| 4800    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 533     | 1         | 1.08%   |

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
| Chicony Electronics                    | 22        | 32.84%  |
| Bison Electronics                      | 11        | 16.42%  |
| Realtek Semiconductor                  | 7         | 10.45%  |
| Sunplus Innovation Technology          | 4         | 5.97%   |
| IMC Networks                           | 4         | 5.97%   |
| Syntek                                 | 3         | 4.48%   |
| Quanta                                 | 2         | 2.99%   |
| Microdia                               | 2         | 2.99%   |
| Luxvisions Innotech Limited            | 2         | 2.99%   |
| Lite-On Technology                     | 2         | 2.99%   |
| Unknown (3730304233435731375051)       | 1         | 1.49%   |
| Silicon Motion                         | 1         | 1.49%   |
| Lenovo                                 | 1         | 1.49%   |
| Importek                               | 1         | 1.49%   |
| Genesys Logic                          | 1         | 1.49%   |
| Foxconn / Hon Hai                      | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.49%   |
| ALi                                    | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 9         | 12.68%  |
| Realtek Integrated_Webcam_HD                                               | 3         | 4.23%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 4.23%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 4.23%   |
| Bison ThinkPad Integrated Camera                                           | 3         | 4.23%   |
| Bison Integrated Camera                                                    | 3         | 4.23%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 2.82%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 2         | 2.82%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 2.82%   |
| IMC Networks Integrated Camera                                             | 2         | 2.82%   |
| Chicony Realtek DMFT RGB                                                   | 2         | 2.82%   |
| Chicony Integrated IR Camera                                               | 2         | 2.82%   |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 2.82%   |
| Chicony 8M Camera                                                          | 2         | 2.82%   |
| Chicony 720p HD Camera                                                     | 2         | 2.82%   |
| Bison Lenovo Integrated Webcam                                             | 2         | 2.82%   |
| Bison Lenovo EasyCamera                                                    | 2         | 2.82%   |
| Unknown (3730304233435731375051) USB Camera                                | 1         | 1.41%   |
| Syntek Integrated Camera                                                   | 1         | 1.41%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 1.41%   |
| Realtek USB 2.0 PC Camera                                                  | 1         | 1.41%   |
| Realtek Integrated Webcam                                                  | 1         | 1.41%   |
| Realtek HD WebCam                                                          | 1         | 1.41%   |
| Realtek Front Camera                                                       | 1         | 1.41%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 1.41%   |
| Quanta ov9734_techfront_camera                                             | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 1.41%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.41%   |
| Lite-On Integrated Camera                                                  | 1         | 1.41%   |
| Lite-On HP HD Camera                                                       | 1         | 1.41%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.41%   |
| Importek USB 2.0 Camera                                                    | 1         | 1.41%   |
| IMC Networks Realtek PC Camera                                             | 1         | 1.41%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.41%   |
| Genesys Logic Camera                                                       | 1         | 1.41%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 1.41%   |
| Chicony HD WebCam                                                          | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.41%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 1.41%   |

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
| 1     | 24        | 28.92%  |
| 2     | 23        | 27.71%  |
| 3     | 22        | 26.51%  |
| 0     | 8         | 9.64%   |
| 4     | 6         | 7.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 69        | 46.31%  |
| Bluetooth                | 24        | 16.11%  |
| Net/wireless             | 18        | 12.08%  |
| Card reader              | 18        | 12.08%  |
| Fingerprint reader       | 17        | 11.41%  |
| Sound                    | 3         | 2.01%   |

