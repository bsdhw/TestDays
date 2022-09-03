BSD in China - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in China.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/China/Desktop/README.md) and [notebooks](/Location/China/Notebook/README.md).

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

Total: 170

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | DTB1168                     | Desktop     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| WlanCN        | 6000 Series                 | Desktop     | [7fda15ca84](https://bsd-hardware.info/?probe=7fda15ca84) | Aug 25, 2022 |
| Acer          | Aspire 4552G                | Notebook    | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [3efcb47333](https://bsd-hardware.info/?probe=3efcb47333) | Jul 31, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | Desktop     | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b2aa5f61e2](https://bsd-hardware.info/?probe=b2aa5f61e2) | Jul 11, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Lenovo        | 300e 81FY                   | Convertible | [eb136e5d7e](https://bsd-hardware.info/?probe=eb136e5d7e) | Jun 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f45bdf1ec](https://bsd-hardware.info/?probe=0f45bdf1ec) | Jun 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ccc77e76e0](https://bsd-hardware.info/?probe=ccc77e76e0) | Jun 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [57a6f58607](https://bsd-hardware.info/?probe=57a6f58607) | Jun 09, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Unknown       | Unknown                     | All in one  | [732a9df612](https://bsd-hardware.info/?probe=732a9df612) | May 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Latitude 5520               | Notebook    | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [214f7d6461](https://bsd-hardware.info/?probe=214f7d6461) | May 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Lenovo        | B470 HuronRiver Platform    | Notebook    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| OEM           | B85 JHS359                  | Desktop     | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Panasonic     | CF-B11JWCYS                 | Notebook    | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [9642cf3129](https://bsd-hardware.info/?probe=9642cf3129) | Mar 30, 2022 |
| ASRock        | Q1900M                      | Desktop     | [e2473b7f22](https://bsd-hardware.info/?probe=e2473b7f22) | Mar 29, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [97f4960723](https://bsd-hardware.info/?probe=97f4960723) | Mar 28, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e2717ea0eb](https://bsd-hardware.info/?probe=e2717ea0eb) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| HASEE Comp... | CW35S                       | Notebook    | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d08da1541a](https://bsd-hardware.info/?probe=d08da1541a) | Mar 14, 2022 |
| Lenovo        | IdeaCentre B545 10100       | Desktop     | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [ce3fedcbaf](https://bsd-hardware.info/?probe=ce3fedcbaf) | Mar 07, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b54ace2a34](https://bsd-hardware.info/?probe=b54ace2a34) | Mar 03, 2022 |
| WOOKING       | X5                          | Notebook    | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| Intel         | X58                         | Desktop     | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8eda642f6a](https://bsd-hardware.info/?probe=8eda642f6a) | Jan 04, 2022 |
| Dell          | 0H9KW5 A00                  | Desktop     | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [e115f87ef7](https://bsd-hardware.info/?probe=e115f87ef7) | Nov 30, 2021 |
| Sony          | SVP13225SCBI                | Notebook    | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [f9af97f07a](https://bsd-hardware.info/?probe=f9af97f07a) | Nov 24, 2021 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [fdeae82fab](https://bsd-hardware.info/?probe=fdeae82fab) | Nov 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [08f546f789](https://bsd-hardware.info/?probe=08f546f789) | Nov 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [d958c5d8f1](https://bsd-hardware.info/?probe=d958c5d8f1) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [d3e799d3a6](https://bsd-hardware.info/?probe=d3e799d3a6) | Nov 13, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [8c72c2f429](https://bsd-hardware.info/?probe=8c72c2f429) | Nov 12, 2021 |
| GuoGuang      | IC2M1028V-6                 | Desktop     | [1aa8bbd5b2](https://bsd-hardware.info/?probe=1aa8bbd5b2) | Nov 07, 2021 |
| Toshiba       | Satellite Pro L510          | Notebook    | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | 3136 SDK0J40697 WIN         | Mini pc     | [bfc921bfbb](https://bsd-hardware.info/?probe=bfc921bfbb) | Oct 29, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | Desktop     | [9b545faf66](https://bsd-hardware.info/?probe=9b545faf66) | Oct 28, 2021 |
| Dell          | 04JN2K A09                  | Server      | [89d5f99632](https://bsd-hardware.info/?probe=89d5f99632) | Oct 27, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | Desktop     | [f269216a0d](https://bsd-hardware.info/?probe=f269216a0d) | Oct 27, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [f9c5120643](https://bsd-hardware.info/?probe=f9c5120643) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Dell          | 0DR845                      | Desktop     | [d8324d1639](https://bsd-hardware.info/?probe=d8324d1639) | Oct 21, 2021 |
| HP            | 3398                        | Desktop     | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| Supermicro    | X10SRA                      | Server      | [e1eba3b8f0](https://bsd-hardware.info/?probe=e1eba3b8f0) | Oct 09, 2021 |
| ASUSTek       | F83VD                       | Notebook    | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| Supermicro    | X10SL7-F                    | Server      | [d26ebdbb9f](https://bsd-hardware.info/?probe=d26ebdbb9f) | Oct 04, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [84f06376e2](https://bsd-hardware.info/?probe=84f06376e2) | Oct 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2d13da6566](https://bsd-hardware.info/?probe=2d13da6566) | Sep 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4f5dd7630a](https://bsd-hardware.info/?probe=4f5dd7630a) | Sep 23, 2021 |
| NEC Comput... | SHARKBAY                    | Desktop     | [24229ed11f](https://bsd-hardware.info/?probe=24229ed11f) | Sep 22, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [aad95eb2bf](https://bsd-hardware.info/?probe=aad95eb2bf) | Sep 21, 2021 |
| YANYU         | ITX-N29 VER:1.5 baytrail    | Desktop     | [c851a73aa5](https://bsd-hardware.info/?probe=c851a73aa5) | Sep 20, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [0da457285c](https://bsd-hardware.info/?probe=0da457285c) | Aug 23, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3063e4b82f](https://bsd-hardware.info/?probe=3063e4b82f) | Aug 21, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | Notebook    | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [cce0d947f1](https://bsd-hardware.info/?probe=cce0d947f1) | Aug 20, 2021 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [1a438c7632](https://bsd-hardware.info/?probe=1a438c7632) | Aug 19, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [7763f089a3](https://bsd-hardware.info/?probe=7763f089a3) | Aug 17, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [f523f4f6c9](https://bsd-hardware.info/?probe=f523f4f6c9) | Aug 10, 2021 |
| NEC Comput... | PC-VK17HBBCD                | Notebook    | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [dc1e25a4e0](https://bsd-hardware.info/?probe=dc1e25a4e0) | Aug 07, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | Notebook    | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| Lenovo        | NOK                         | Desktop     | [de711c244f](https://bsd-hardware.info/?probe=de711c244f) | Aug 05, 2021 |
| Supermicro    | X10SL7-F                    | Server      | [50e9da16d7](https://bsd-hardware.info/?probe=50e9da16d7) | Aug 04, 2021 |
| Lenovo        | NOK                         | Desktop     | [5bd27802f0](https://bsd-hardware.info/?probe=5bd27802f0) | Aug 04, 2021 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [73a22d60fc](https://bsd-hardware.info/?probe=73a22d60fc) | Jul 30, 2021 |
| GuoGuang      | IC2M1028V-6                 | Desktop     | [9bfe0dca00](https://bsd-hardware.info/?probe=9bfe0dca00) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [e0e6f62814](https://bsd-hardware.info/?probe=e0e6f62814) | Jul 19, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [e71b6ac13d](https://bsd-hardware.info/?probe=e71b6ac13d) | Jul 10, 2021 |
| Gigabyte      | GA-6UPCP2/4/5               | Server      | [f1e7cb51d7](https://bsd-hardware.info/?probe=f1e7cb51d7) | Jul 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [58f03a472f](https://bsd-hardware.info/?probe=58f03a472f) | Jul 03, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | Notebook    | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b8712916f2](https://bsd-hardware.info/?probe=b8712916f2) | Jun 29, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [0b0951a048](https://bsd-hardware.info/?probe=0b0951a048) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [8fe29978c3](https://bsd-hardware.info/?probe=8fe29978c3) | Jun 22, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | Notebook    | [2b05811c5f](https://bsd-hardware.info/?probe=2b05811c5f) | Jun 18, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [2268ef2689](https://bsd-hardware.info/?probe=2268ef2689) | Jun 18, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | Notebook    | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Protectli     | FW6                         | Desktop     | [7fe94af21a](https://bsd-hardware.info/?probe=7fe94af21a) | Jun 11, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [ff1a657505](https://bsd-hardware.info/?probe=ff1a657505) | Jun 08, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [c0b3c87810](https://bsd-hardware.info/?probe=c0b3c87810) | Jun 04, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [39b99e57af](https://bsd-hardware.info/?probe=39b99e57af) | Jun 01, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [63a3fc3982](https://bsd-hardware.info/?probe=63a3fc3982) | May 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [def6a6516d](https://bsd-hardware.info/?probe=def6a6516d) | Apr 30, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [acc8b02e3b](https://bsd-hardware.info/?probe=acc8b02e3b) | Apr 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| Notebook      | W65KJ1_KK1                  | Notebook    | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [d902b4ebd8](https://bsd-hardware.info/?probe=d902b4ebd8) | Apr 24, 2021 |
| Dell          | Latitude E5570              | Notebook    | [da926f1065](https://bsd-hardware.info/?probe=da926f1065) | Apr 11, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [2338aa8fff](https://bsd-hardware.info/?probe=2338aa8fff) | Apr 03, 2021 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [5283765cbe](https://bsd-hardware.info/?probe=5283765cbe) | Apr 03, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [3623b04225](https://bsd-hardware.info/?probe=3623b04225) | Mar 31, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [065e6c08fd](https://bsd-hardware.info/?probe=065e6c08fd) | Mar 28, 2021 |
| ASUSTek       | X540UP                      | Notebook    | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [13754ed4ee](https://bsd-hardware.info/?probe=13754ed4ee) | Mar 23, 2021 |
| Dell          | 0YXT71 A00                  | Desktop     | [cb3d9f12c6](https://bsd-hardware.info/?probe=cb3d9f12c6) | Mar 20, 2021 |
| Lenovo        | ThinkPad E460 20ETA00DCD    | Notebook    | [0a6985f078](https://bsd-hardware.info/?probe=0a6985f078) | Mar 13, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [19923e24d6](https://bsd-hardware.info/?probe=19923e24d6) | Mar 10, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| Dell          | Precision 3541              | Notebook    | [d07a4dc2c7](https://bsd-hardware.info/?probe=d07a4dc2c7) | Mar 04, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [9a23dee2ea](https://bsd-hardware.info/?probe=9a23dee2ea) | Mar 01, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | Notebook    | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [9731048099](https://bsd-hardware.info/?probe=9731048099) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [03d4d9a468](https://bsd-hardware.info/?probe=03d4d9a468) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| Gigabyte      | GA-870-UD3P                 | Desktop     | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [a54f14d773](https://bsd-hardware.info/?probe=a54f14d773) | Feb 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Google        | Guado                       | Desktop     | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [5068d55701](https://bsd-hardware.info/?probe=5068d55701) | Feb 16, 2021 |
| HP            | 8768 A                      | Desktop     | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [419b61f1d8](https://bsd-hardware.info/?probe=419b61f1d8) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | Desktop     | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [62d7379d24](https://bsd-hardware.info/?probe=62d7379d24) | Feb 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [bc823e0dfc](https://bsd-hardware.info/?probe=bc823e0dfc) | Feb 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [5550236531](https://bsd-hardware.info/?probe=5550236531) | Feb 08, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [12e20c2cb0](https://bsd-hardware.info/?probe=12e20c2cb0) | Jan 23, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [dad5d994a0](https://bsd-hardware.info/?probe=dad5d994a0) | Jan 20, 2021 |
| Lenovo        | ThinkPad T580 20L9000ECD    | Notebook    | [771d8ead80](https://bsd-hardware.info/?probe=771d8ead80) | Nov 10, 2020 |
| Unknown       | Raspberry Pi                | Soc         | [cd269c4db1](https://bsd-hardware.info/?probe=cd269c4db1) | Nov 01, 2020 |
| ASRock        | A320M-ITX                   | Desktop     | [7fab9dd55a](https://bsd-hardware.info/?probe=7fab9dd55a) | Oct 31, 2020 |
| HP            | 213D A01                    | Desktop     | [b081e36525](https://bsd-hardware.info/?probe=b081e36525) | Oct 31, 2020 |
| Lenovo        | ThinkPad SL410 28747GC      | Notebook    | [3b62dd9788](https://bsd-hardware.info/?probe=3b62dd9788) | Jul 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 15        | 11.03%  |
| helloSystem 0.5.0    | 9         | 6.62%   |
| OPNsense 21.7.1      | 8         | 5.88%   |
| OPNsense 21.1.7      | 6         | 4.41%   |
| OPNsense 21.7.3      | 5         | 3.68%   |
| helloSystem 0.6.0    | 5         | 3.68%   |
| helloSystem 0.4.0    | 5         | 3.68%   |
| FreeBSD 12.2         | 5         | 3.68%   |
| OPNsense 21.7.5      | 4         | 2.94%   |
| OPNsense 21.7.2      | 4         | 2.94%   |
| OPNsense 21.1        | 4         | 2.94%   |
| FreeBSD 14.0-CURRENT | 4         | 2.94%   |
| OPNsense 21.1.6      | 3         | 2.21%   |
| OPNsense 21.1.3      | 3         | 2.21%   |
| OPNsense 21.1.1      | 3         | 2.21%   |
| GhostBSD 21.08.27    | 3         | 2.21%   |
| FreeBSD 13.1         | 3         | 2.21%   |
| FreeBSD 13.0-p4      | 3         | 2.21%   |
| OPNsense 22.7.2      | 2         | 1.47%   |
| OPNsense 22.1.8      | 2         | 1.47%   |
| OPNsense 22.1.4      | 2         | 1.47%   |
| OPNsense 22.1.2      | 2         | 1.47%   |
| OPNsense 21.7.4      | 2         | 1.47%   |
| NomadBSD 5806f915    | 2         | 1.47%   |
| helloSystem 0.8.0    | 2         | 1.47%   |
| FreeBSD 13.0-p7      | 2         | 1.47%   |
| FreeBSD 13.0         | 2         | 1.47%   |
| OPNsense 22.7        | 1         | 0.74%   |
| OPNsense 22.1.7      | 1         | 0.74%   |
| OPNsense 22.1.3      | 1         | 0.74%   |
| OPNsense 22.1.10     | 1         | 0.74%   |
| OPNsense 21.7.8      | 1         | 0.74%   |
| OPNsense 21.7.7      | 1         | 0.74%   |
| OPNsense 21.7.6      | 1         | 0.74%   |
| OPNsense 21.7        | 1         | 0.74%   |
| OPNsense 21.1.5      | 1         | 0.74%   |
| OPNsense 21.1.4      | 1         | 0.74%   |
| OPNsense 21.1.2      | 1         | 0.74%   |
| OPNsense 20.7.8      | 1         | 0.74%   |
| OpenBSD 7.0          | 1         | 0.74%   |
| NomadBSD 1.3.1       | 1         | 0.74%   |
| FreeBSD 13.1-RC3     | 1         | 0.74%   |
| FreeBSD 13.0-STABLE  | 1         | 0.74%   |
| FreeBSD 13.0-RC5     | 1         | 0.74%   |
| FreeBSD 13.0-RC1     | 1         | 0.74%   |
| FreeBSD 13.0-p3      | 1         | 0.74%   |
| FreeBSD 13.0-p2      | 1         | 0.74%   |
| FreeBSD 12.2-p4      | 1         | 0.74%   |
| FreeBSD 12.2-p2      | 1         | 0.74%   |
| FreeBSD 12.2-p10     | 1         | 0.74%   |
| FreeBSD 12.1-p7      | 1         | 0.74%   |
| FreeBSD 12.1         | 1         | 0.74%   |
| FreeBSD 12.0         | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 46        | 38.66%  |
| helloSystem | 36        | 30.25%  |
| FreeBSD     | 30        | 25.21%  |
| NomadBSD    | 3         | 2.52%   |
| GhostBSD    | 3         | 2.52%   |
| OpenBSD     | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 117       | 99.15%  |
| arm64 | 1         | 0.85%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 54        | 44.26%  |
| helloDesktop | 35        | 28.69%  |
| XFCE         | 9         | 7.38%   |
| KDE5         | 9         | 7.38%   |
| GNOME        | 4         | 3.28%   |
| Openbox      | 3         | 2.46%   |
| MATE         | 3         | 2.46%   |
| i3           | 3         | 2.46%   |
| TWM          | 1         | 0.82%   |
| fvwm         | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 65        | 54.17%  |
| Console | 54        | 45%     |
| Wayland | 1         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 59        | 48.76%  |
| SLiM    | 44        | 36.36%  |
| SDDM    | 7         | 5.79%   |
| LightDM | 6         | 4.96%   |
| GDM     | 4         | 3.31%   |
| XDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 56        | 46.28%  |
| en_US        | 39        | 32.23%  |
| zh_CN        | 13        | 10.74%  |
| C            | 12        | 9.92%   |
| zh_CN.GB2312 | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 99        | 82.5%   |
| BIOS | 21        | 17.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 54        | 45%     |
| Ufs    | 54        | 45%     |
| Cd9660 | 11        | 9.17%   |
| Ffs    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 105       | 87.5%   |
| MBR     | 13        | 10.83%  |
| Unknown | 2         | 1.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo                                     | 28        | 23.73%  |
| Unknown                                    | 18        | 15.25%  |
| Dell                                       | 11        | 9.32%   |
| Hewlett-Packard                            | 8         | 6.78%   |
| ASUSTek Computer                           | 7         | 5.93%   |
| Gigabyte Technology                        | 5         | 4.24%   |
| Supermicro                                 | 3         | 2.54%   |
| Sony                                       | 2         | 1.69%   |
| ShenZhen MinWin Technology                 | 2         | 1.69%   |
| PAIQ                                       | 2         | 1.69%   |
| Notebook                                   | 2         | 1.69%   |
| NEC Computers                              | 2         | 1.69%   |
| MSI                                        | 2         | 1.69%   |
| Intel                                      | 2         | 1.69%   |
| HUAWEI                                     | 2         | 1.69%   |
| ASRock                                     | 2         | 1.69%   |
| AMI                                        | 2         | 1.69%   |
| YANYU                                      | 1         | 0.85%   |
| WOOKING                                    | 1         | 0.85%   |
| WlanCN                                     | 1         | 0.85%   |
| Toshiba                                    | 1         | 0.85%   |
| Timi                                       | 1         | 0.85%   |
| Techvision                                 | 1         | 0.85%   |
| Protectli                                  | 1         | 0.85%   |
| Panasonic                                  | 1         | 0.85%   |
| OEM                                        | 1         | 0.85%   |
| MAXSUN                                     | 1         | 0.85%   |
| HASEE Computer                             | 1         | 0.85%   |
| GuoGuang                                   | 1         | 0.85%   |
| Google                                     | 1         | 0.85%   |
| Colorful YuGong Technology And Development | 1         | 0.85%   |
| Colorful Technology                        | 1         | 0.85%   |
| CNCTION-IAF-E3845                          | 1         | 0.85%   |
| Apple                                      | 1         | 0.85%   |
| Acer                                       | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 19        | 16.1%   |
| ShenZhen MinWin MW-NANO-APL-4L              | 2         | 1.69%   |
| PAIQ EC3-BT19D4L                            | 2         | 1.69%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 1.69%   |
| HP ProLiant DL320e Gen8 v2                  | 2         | 1.69%   |
| AMI Aptio CRB                               | 2         | 1.69%   |
| YANYU ITX-N29 VER:1.5 baytrail              | 1         | 0.85%   |
| WOOKING X5                                  | 1         | 0.85%   |
| WlanCN 6000 Series                          | 1         | 0.85%   |
| Toshiba Satellite Pro L510                  | 1         | 0.85%   |
| Timi RedmiBook Pro 15                       | 1         | 0.85%   |
| Techvision TVI7309X                         | 1         | 0.85%   |
| Supermicro X10SRA                           | 1         | 0.85%   |
| Supermicro X10SL7-F                         | 1         | 0.85%   |
| Supermicro Super Server                     | 1         | 0.85%   |
| Sony SVS1511AJB                             | 1         | 0.85%   |
| Sony SVP13225SCBI                           | 1         | 0.85%   |
| Protectli FW6                               | 1         | 0.85%   |
| Panasonic CF-B11JWCYS                       | 1         | 0.85%   |
| OEM B85 JHS359                              | 1         | 0.85%   |
| Notebook W65KJ1_KK1                         | 1         | 0.85%   |
| Notebook W650DC,DD                          | 1         | 0.85%   |
| NEC Computers SHARKBAY                      | 1         | 0.85%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.85%   |
| MSI MS-7C82                                 | 1         | 0.85%   |
| MSI MS-7972                                 | 1         | 0.85%   |
| MAXSUN MS-H110D4L FS M.2                    | 1         | 0.85%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 0.85%   |
| Lenovo YangTianW2090v-00                    | 1         | 0.85%   |
| Lenovo YangTianA8800T                       | 1         | 0.85%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.85%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.85%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 0.85%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.85%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 0.85%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 0.85%   |
| Lenovo ThinkPad P51 20HHCTO1WW              | 1         | 0.85%   |
| Lenovo ThinkPad Edge E430 3254A68           | 1         | 0.85%   |
| Lenovo ThinkPad E460 20ETA00DCD             | 1         | 0.85%   |
| Lenovo ThinkPad E420 1141A83                | 1         | 0.85%   |
| Lenovo ThinkCentre M93p 10AA0020CN          | 1         | 0.85%   |
| Lenovo ThinkCentre M720q 10T700A9GE         | 1         | 0.85%   |
| Lenovo SHARKBAY 0B98401 WIN                 | 1         | 0.85%   |
| Lenovo Rescuer-15ISK 80RQ                   | 1         | 0.85%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 0.85%   |
| Lenovo IdeaCentre B545 10100                | 1         | 0.85%   |
| Lenovo G480 20149                           | 1         | 0.85%   |
| Lenovo G470 20078                           | 1         | 0.85%   |
| Lenovo B470 HuronRiver Platform             | 1         | 0.85%   |
| Lenovo B41-80 80LG                          | 1         | 0.85%   |
| Lenovo 300e 81FY                            | 1         | 0.85%   |
| Intel X58                                   | 1         | 0.85%   |
| Intel NUC7i3BNK                             | 1         | 0.85%   |
| HUAWEI NBLL-WXX9                            | 1         | 0.85%   |
| HUAWEI HLY-WX9XX                            | 1         | 0.85%   |
| HP t620 PLUS Quad Core TC                   | 1         | 0.85%   |
| HP Slim Desktop S01-pF1xxx                  | 1         | 0.85%   |
| HP ProBook 440 G6                           | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 19        | 16.1%   |
| Lenovo ThinkPad                | 13        | 11.02%  |
| Dell Latitude                  | 3         | 2.54%   |
| ShenZhen MinWin MW-NANO-APL-4L | 2         | 1.69%   |
| PAIQ EC3-BT19D4L               | 2         | 1.69%   |
| Lenovo ThinkCentre             | 2         | 1.69%   |
| HP ProLiant                    | 2         | 1.69%   |
| HP ProBook                     | 2         | 1.69%   |
| Dell Precision                 | 2         | 1.69%   |
| Dell OptiPlex                  | 2         | 1.69%   |
| Dell Inspiron                  | 2         | 1.69%   |
| ASUS TUF                       | 2         | 1.69%   |
| AMI Aptio                      | 2         | 1.69%   |
| YANYU ITX-N29                  | 1         | 0.85%   |
| WOOKING X5                     | 1         | 0.85%   |
| WlanCN 6000                    | 1         | 0.85%   |
| Toshiba Satellite              | 1         | 0.85%   |
| Timi RedmiBook                 | 1         | 0.85%   |
| Techvision TVI7309X            | 1         | 0.85%   |
| Supermicro X10SRA              | 1         | 0.85%   |
| Supermicro X10SL7-F            | 1         | 0.85%   |
| Supermicro Super               | 1         | 0.85%   |
| Sony SVS1511AJB                | 1         | 0.85%   |
| Sony SVP13225SCBI              | 1         | 0.85%   |
| Protectli FW6                  | 1         | 0.85%   |
| Panasonic CF-B11JWCYS          | 1         | 0.85%   |
| OEM B85                        | 1         | 0.85%   |
| Notebook W65KJ1                | 1         | 0.85%   |
| Notebook W650DC                | 1         | 0.85%   |
| NEC Computers SHARKBAY         | 1         | 0.85%   |
| NEC Computers PC-VK17HBBCD     | 1         | 0.85%   |
| MSI MS-7C82                    | 1         | 0.85%   |
| MSI MS-7972                    | 1         | 0.85%   |
| MAXSUN MS-H110D4L              | 1         | 0.85%   |
| Lenovo ZhaoYang                | 1         | 0.85%   |
| Lenovo YangTianW2090v-00       | 1         | 0.85%   |
| Lenovo YangTianA8800T          | 1         | 0.85%   |
| Lenovo XiaoXinPro-13ARE        | 1         | 0.85%   |
| Lenovo SHARKBAY                | 1         | 0.85%   |
| Lenovo Rescuer-15ISK           | 1         | 0.85%   |
| Lenovo IdeaPad                 | 1         | 0.85%   |
| Lenovo IdeaCentre              | 1         | 0.85%   |
| Lenovo G480                    | 1         | 0.85%   |
| Lenovo G470                    | 1         | 0.85%   |
| Lenovo B470                    | 1         | 0.85%   |
| Lenovo B41-80                  | 1         | 0.85%   |
| Lenovo 300e                    | 1         | 0.85%   |
| Intel X58                      | 1         | 0.85%   |
| Intel NUC7i3BNK                | 1         | 0.85%   |
| HUAWEI NBLL-WXX9               | 1         | 0.85%   |
| HUAWEI HLY-WX9XX               | 1         | 0.85%   |
| HP t620                        | 1         | 0.85%   |
| HP Slim                        | 1         | 0.85%   |
| HP Pavilion                    | 1         | 0.85%   |
| HP Compaq                      | 1         | 0.85%   |
| HASEE CW35S                    | 1         | 0.85%   |
| GuoGuang IC2M1028V-6           | 1         | 0.85%   |
| Google Guado                   | 1         | 0.85%   |
| Gigabyte H410M                 | 1         | 0.85%   |
| Gigabyte GB-BACE-3150          | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 17        | 14.41%  |
| 2017    | 15        | 12.71%  |
| 2019    | 13        | 11.02%  |
| 2012    | 11        | 9.32%   |
| 2020    | 10        | 8.47%   |
| 2018    | 9         | 7.63%   |
| 2016    | 8         | 6.78%   |
| 2014    | 7         | 5.93%   |
| 2013    | 7         | 5.93%   |
| 2011    | 6         | 5.08%   |
| 2022    | 4         | 3.39%   |
| 2015    | 4         | 3.39%   |
| 2010    | 2         | 1.69%   |
| 2009    | 2         | 1.69%   |
| 2008    | 1         | 0.85%   |
| 2007    | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 54        | 45.76%  |
| Notebook       | 50        | 42.37%  |
| Server         | 7         | 5.93%   |
| Mini pc        | 4         | 3.39%   |
| System on chip | 1         | 0.85%   |
| Convertible    | 1         | 0.85%   |
| All in one     | 1         | 0.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 98.31%  |
| Yes  | 2         | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 43        | 36.13%  |
| 4.01-8.0    | 32        | 26.89%  |
| 16.01-24.0  | 21        | 17.65%  |
| 32.01-64.0  | 9         | 7.56%   |
| 2.01-3.0    | 7         | 5.88%   |
| 24.01-32.0  | 3         | 2.52%   |
| 64.01-256.0 | 2         | 1.68%   |
| 1.01-2.0    | 1         | 0.84%   |
| 0.51-1.0    | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 72        | 60.5%   |
| 0.51-1.0 | 28        | 23.53%  |
| 1.01-2.0 | 17        | 14.29%  |
| 3.01-4.0 | 1         | 0.84%   |
| 2.01-3.0 | 1         | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 65.57%  |
| 2      | 19        | 15.57%  |
| 0      | 13        | 10.66%  |
| 3      | 6         | 4.92%   |
| 5      | 3         | 2.46%   |
| 4      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 80.51%  |
| Yes       | 23        | 19.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 91.53%  |
| No        | 10        | 8.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 52.54%  |
| No        | 56        | 47.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 61.02%  |
| Yes       | 46        | 38.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 118       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Beijing                 | 15        | 11.9%   |
| Shanghai                | 14        | 11.11%  |
| Shenzhen                | 11        | 8.73%   |
| Guangzhou               | 10        | 7.94%   |
| Chengdu                 | 7         | 5.56%   |
| Zhengzhou               | 4         | 3.17%   |
| Hangzhou                | 4         | 3.17%   |
| Xi'an                   | 3         | 2.38%   |
| Nanjing                 | 3         | 2.38%   |
| Wuhan                   | 2         | 1.59%   |
| Qingdao                 | 2         | 1.59%   |
| Jinrongjie              | 2         | 1.59%   |
| Changzhou               | 2         | 1.59%   |
| Changchun               | 2         | 1.59%   |
| Baiyun                  | 2         | 1.59%   |
| Zhumadian               | 1         | 0.79%   |
| Zhongshan               | 1         | 0.79%   |
| Zhaoqing                | 1         | 0.79%   |
| Yichun                  | 1         | 0.79%   |
| Yancheng                | 1         | 0.79%   |
| Xicheng District        | 1         | 0.79%   |
| Xiamen                  | 1         | 0.79%   |
| Wuxi                    | 1         | 0.79%   |
| Tongshan                | 1         | 0.79%   |
| Tongchuanshi            | 1         | 0.79%   |
| Tieling                 | 1         | 0.79%   |
| Suzhou                  | 1         | 0.79%   |
| Shizishan               | 1         | 0.79%   |
| Shahekou                | 1         | 0.79%   |
| Qinnan                  | 1         | 0.79%   |
| Qingpu                  | 1         | 0.79%   |
| Putuo                   | 1         | 0.79%   |
| Putian                  | 1         | 0.79%   |
| Pudong                  | 1         | 0.79%   |
| Ningbo                  | 1         | 0.79%   |
| Luoyang                 | 1         | 0.79%   |
| Liuzhou                 | 1         | 0.79%   |
| Linyi                   | 1         | 0.79%   |
| Lanzhou                 | 1         | 0.79%   |
| Kunming                 | 1         | 0.79%   |
| Kuiju                   | 1         | 0.79%   |
| Jinniu                  | 1         | 0.79%   |
| Jilin City              | 1         | 0.79%   |
| Huangpu                 | 1         | 0.79%   |
| Hongyuan                | 1         | 0.79%   |
| Hongkou                 | 1         | 0.79%   |
| Hohhot                  | 1         | 0.79%   |
| Hengshui                | 1         | 0.79%   |
| Guli                    | 1         | 0.79%   |
| Guangzhou Shi           | 1         | 0.79%   |
| Gaoqiao                 | 1         | 0.79%   |
| Gaoleshan               | 1         | 0.79%   |
| Fuzhou                  | 1         | 0.79%   |
| Dongguan                | 1         | 0.79%   |
| Dangchang Chengguanzhen | 1         | 0.79%   |
| Dalian                  | 1         | 0.79%   |
| Chaoyang Shi            | 1         | 0.79%   |
| Bijie                   | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 30     | 15.49%  |
| Seagate             | 20        | 25     | 14.08%  |
| WDC                 | 16        | 26     | 11.27%  |
| Intel               | 11        | 12     | 7.75%   |
| Toshiba             | 10        | 11     | 7.04%   |
| SanDisk             | 7         | 8      | 4.93%   |
| Kingston            | 5         | 5      | 3.52%   |
| HGST                | 4         | 5      | 2.82%   |
| China               | 4         | 7      | 2.82%   |
| Netac               | 3         | 3      | 2.11%   |
| Hitachi             | 3         | 3      | 2.11%   |
| Transcend           | 2         | 2      | 1.41%   |
| SK hynix            | 2         | 2      | 1.41%   |
| Plextor             | 2         | 2      | 1.41%   |
| Micron Technology   | 2         | 3      | 1.41%   |
| Lenovo              | 2         | 2      | 1.41%   |
| KIOXIA              | 2         | 2      | 1.41%   |
| KingSpec            | 2         | 2      | 1.41%   |
| Hikvision           | 2         | 2      | 1.41%   |
| Crucial             | 2         | 2      | 1.41%   |
| Colorful            | 2         | 2      | 1.41%   |
| tigo                | 1         | 1      | 0.7%    |
| Silicon Motion      | 1         | 1      | 0.7%    |
| Ramsta              | 1         | 1      | 0.7%    |
| Pioneer             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Lexar               | 1         | 1      | 0.7%    |
| KIOXIA-EXCERIA      | 1         | 2      | 0.7%    |
| Hoodisk             | 1         | 2      | 0.7%    |
| Hewlett-Packard     | 1         | 1      | 0.7%    |
| FREEBSD             | 1         | 1      | 0.7%    |
| FORESEE             | 1         | 1      | 0.7%    |
| Faspeed             | 1         | 1      | 0.7%    |
| BR                  | 1         | 1      | 0.7%    |
| BIWIN               | 1         | 3      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |
| Apacer              | 1         | 1      | 0.7%    |
| A-DATA Technology   | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Seagate ST1000DM003-1SB102 1TB                 | 3         | 1.92%   |
| Toshiba MQ04ABF100 1TB                         | 2         | 1.28%   |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 1.28%   |
| SanDisk SSD U100 24GB                          | 2         | 1.28%   |
| Samsung SSD 970 EVO Plus 1TB                   | 2         | 1.28%   |
| Samsung SSD 870 EVO 1TB                        | 2         | 1.28%   |
| Samsung MZVL21T0HCLR-00BL7 1TB                 | 2         | 1.28%   |
| Samsung HM320II 320GB                          | 2         | 1.28%   |
| Netac SSD 120GB                                | 2         | 1.28%   |
| Intel SSDSA2SH032G1GN 32GB                     | 2         | 1.28%   |
| Intel SSDSA2CW120G3 120GB                      | 2         | 1.28%   |
| Hikvision HS-SSD-C2000ECO 1024G                | 2         | 1.28%   |
| HGST HTS541010B7E610 1TB                       | 2         | 1.28%   |
| WDC WUH721414ALE6L4 14TB                       | 1         | 0.64%   |
| WDC WDS500G2B0C-00PXH0 500GB                   | 1         | 0.64%   |
| WDC WDS120G2G0B-00EPW0 120GB                   | 1         | 0.64%   |
| WDC WDS100T3X0C-00SJG0 1TB                     | 1         | 0.64%   |
| WDC WDS100T2B0C-00PXH0 1TB                     | 1         | 0.64%   |
| WDC WD7500LPCX-00KHST0 752GB                   | 1         | 0.64%   |
| WDC WD5000LPCX-00VHAT0 500GB                   | 1         | 0.64%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 0.64%   |
| WDC WD30EZRZ-00WN9B0 3TB                       | 1         | 0.64%   |
| WDC WD2500BEVS-08VAT2 250GB                    | 1         | 0.64%   |
| WDC WD20SPZX-75UA7T0 2TB                       | 1         | 0.64%   |
| WDC WD20SPZX-22UA7T0 2TB                       | 1         | 0.64%   |
| WDC WD2003FYYS-007BA0 2TB                      | 1         | 0.64%   |
| WDC WD1600BEVT-22ZCT0 160GB                    | 1         | 0.64%   |
| WDC WD1600AAJS-22L7A0 160GB                    | 1         | 0.64%   |
| WDC WD120EMAZ-11BLFA0 12TB                     | 1         | 0.64%   |
| WDC WD10SPZX-60Z10T0 1TB                       | 1         | 0.64%   |
| WDC WD10SPZX-00Z10T0 1TB                       | 1         | 0.64%   |
| WDC WD10JPVX-00JC3T0 1TB                       | 1         | 0.64%   |
| WDC WD10EZEX-21WN4A0 1TB                       | 1         | 0.64%   |
| WDC WD10EARS-003BB1 1TB                        | 1         | 0.64%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB           | 1         | 0.64%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB           | 1         | 0.64%   |
| Transcend TS4GCF150 4GB                        | 1         | 0.64%   |
| Transcend TS128GMTS400 128GB                   | 1         | 0.64%   |
| Toshiba THNSNF128GCSS 128GB                    | 1         | 0.64%   |
| Toshiba MQ02ABF050H-SSHD-8GB                   | 1         | 0.64%   |
| Toshiba MQ01ACF050 500GB                       | 1         | 0.64%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 0.64%   |
| Toshiba KXG6APNV2T04 2TB                       | 1         | 0.64%   |
| Toshiba DT01ACA100 1TB                         | 1         | 0.64%   |
| Toshiba DT01ACA050 500GB                       | 1         | 0.64%   |
| Toshiba A100 240GB                             | 1         | 0.64%   |
| tigo SSD 480GB                                 | 1         | 0.64%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB        | 1         | 0.64%   |
| SK hynix BC511 NVMe 512GB                      | 1         | 0.64%   |
| Silicon Motion Asgard AN2 500NVMe-M.2-80 500GB | 1         | 0.64%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 0.64%   |
| Seagate ST500LM030-2E717D 500GB                | 1         | 0.64%   |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 0.64%   |
| Seagate ST500DM002-1SB10A 500GB                | 1         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 0.64%   |
| Seagate ST3500418AS 500GB                      | 1         | 0.64%   |
| Seagate ST3500312CS 500GB                      | 1         | 0.64%   |
| Seagate ST3320418AS 320GB                      | 1         | 0.64%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 25     | 40.82%  |
| WDC                 | 13        | 18     | 26.53%  |
| Toshiba             | 7         | 7      | 14.29%  |
| HGST                | 4         | 5      | 8.16%   |
| Hitachi             | 3         | 3      | 6.12%   |
| Samsung Electronics | 2         | 4      | 4.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 13     | 17.39%  |
| Intel               | 10        | 11     | 14.49%  |
| SanDisk             | 7         | 8      | 10.14%  |
| Kingston            | 4         | 4      | 5.8%    |
| China               | 4         | 7      | 5.8%    |
| Netac               | 3         | 3      | 4.35%   |
| Transcend           | 2         | 2      | 2.9%    |
| Toshiba             | 2         | 2      | 2.9%    |
| Micron Technology   | 2         | 3      | 2.9%    |
| Lenovo              | 2         | 2      | 2.9%    |
| KingSpec            | 2         | 2      | 2.9%    |
| WDC                 | 1         | 1      | 1.45%   |
| tigo                | 1         | 1      | 1.45%   |
| Ramsta              | 1         | 1      | 1.45%   |
| Plextor             | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| Lexar               | 1         | 1      | 1.45%   |
| KIOXIA-EXCERIA      | 1         | 2      | 1.45%   |
| Hoodisk             | 1         | 2      | 1.45%   |
| Hewlett-Packard     | 1         | 1      | 1.45%   |
| FREEBSD             | 1         | 1      | 1.45%   |
| FORESEE             | 1         | 1      | 1.45%   |
| Faspeed             | 1         | 1      | 1.45%   |
| Crucial             | 1         | 1      | 1.45%   |
| Colorful            | 1         | 1      | 1.45%   |
| BR                  | 1         | 1      | 1.45%   |
| BIWIN               | 1         | 3      | 1.45%   |
| Apple               | 1         | 1      | 1.45%   |
| Apacer              | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 80     | 48.51%  |
| HDD  | 42        | 62     | 31.34%  |
| NVMe | 27        | 35     | 20.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 142    | 77.5%   |
| NVMe | 27        | 35     | 22.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 99     | 66.37%  |
| 0.51-1.0   | 27        | 29     | 23.89%  |
| 1.01-2.0   | 7         | 8      | 6.19%   |
| 2.01-3.0   | 2         | 2      | 1.77%   |
| 10.01-20.0 | 1         | 2      | 0.88%   |
| 4.01-10.0  | 1         | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 36        | 29.51%  |
| 101-250    | 25        | 20.49%  |
| 251-500    | 24        | 19.67%  |
| 21-50      | 12        | 9.84%   |
| 51-100     | 12        | 9.84%   |
| 501-1000   | 7         | 5.74%   |
| 1001-2000  | 5         | 4.1%    |
| Unknown    | 1         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 105       | 88.24%  |
| 21-50   | 9         | 7.56%   |
| 251-500 | 2         | 1.68%   |
| 101-250 | 1         | 0.84%   |
| 51-100  | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-22L7A0 160GB     | 1         | 1      | 6.67%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 6.67%   |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 6.67%   |
| Seagate ST3320418AS 320GB       | 1         | 2      | 6.67%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 6.67%   |
| Seagate ST31500541AS 1.5TB      | 1         | 1      | 6.67%   |
| Seagate ST31000528AS 1TB        | 1         | 1      | 6.67%   |
| Intel SSDSA2M160G2GC 160GB      | 1         | 2      | 6.67%   |
| Intel SSDSA2M120G2GC 120GB      | 1         | 1      | 6.67%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 6.67%   |
| Colorful SL500 640GB            | 1         | 1      | 6.67%   |
| China XJH-32GB                  | 1         | 1      | 6.67%   |
| China JWX 16GB MSATA            | 1         | 2      | 6.67%   |
| BIWIN SSD 32GB                  | 1         | 3      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 6      | 33.33%  |
| WDC      | 2         | 2      | 13.33%  |
| Intel    | 2         | 3      | 13.33%  |
| China    | 2         | 3      | 13.33%  |
| Toshiba  | 1         | 1      | 6.67%   |
| Hitachi  | 1         | 1      | 6.67%   |
| Colorful | 1         | 1      | 6.67%   |
| BIWIN    | 1         | 3      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 55.56%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 60%     |
| SSD  | 6         | 10     | 40%     |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 97        | 156    | 85.84%  |
| Malfunc  | 15        | 20     | 13.27%  |
| Detected | 1         | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 98        | 69.01%  |
| Samsung Electronics          | 12        | 8.45%   |
| AMD                          | 9         | 6.34%   |
| SanDisk                      | 5         | 3.52%   |
| Broadcom / LSI               | 4         | 2.82%   |
| SK hynix                     | 2         | 1.41%   |
| Silicon Motion               | 2         | 1.41%   |
| MAXIO Technology (Hangzhou)  | 2         | 1.41%   |
| KIOXIA                       | 2         | 1.41%   |
| Toshiba                      | 1         | 0.7%    |
| Shenzhen Longsys Electronics | 1         | 0.7%    |
| Micron/Crucial Technology    | 1         | 0.7%    |
| Lite-On Technology           | 1         | 0.7%    |
| Kingston Technology Company  | 1         | 0.7%    |
| JMicron Technology           | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 9.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 6.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 5.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 3.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 3.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.92%   |
| Unknown                                                                          | 3         | 1.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.28%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.28%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 2         | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.28%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 2         | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.28%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.64%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                      | 1         | 0.64%   |
| SK hynix BC511                                                                   | 1         | 0.64%   |
| Samsung SM951 AHCI                                                               | 1         | 0.64%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.64%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 1         | 0.64%   |
| JMicron JMB368 IDE controller                                                    | 1         | 0.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.64%   |
| Intel SSD 660P Series                                                            | 1         | 0.64%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.64%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.64%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.64%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 0.64%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 0.64%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.64%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1         | 0.64%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1         | 0.64%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1         | 0.64%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.64%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 1         | 0.64%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.64%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 98        | 68.53%  |
| NVMe | 27        | 18.88%  |
| IDE  | 11        | 7.69%   |
| RAID | 5         | 3.5%    |
| SAS  | 2         | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 105       | 88.98%  |
| AMD     | 12        | 10.17%  |
| Unknown | 1         | 0.85%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 8         | 6.78%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 3         | 2.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 2.54%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 3         | 2.54%   |
| Intel Atom CPU D525 @ 1.80GHz               | 3         | 2.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.54%   |
| Intel Pentium CPU G3260T @ 2.90GHz          | 2         | 1.69%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 2         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.69%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 2         | 1.69%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.69%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2         | 1.69%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 2         | 1.69%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 1.69%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz       | 1         | 0.85%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1         | 0.85%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1         | 0.85%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz        | 1         | 0.85%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.85%   |
| Intel Xeon CPU D-1537 @ 1.70GHz             | 1         | 0.85%   |
| Intel Xeon                                  | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.85%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.85%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1         | 0.85%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.85%   |
| Intel Pentium CPU G3460T @ 3.00GHz          | 1         | 0.85%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.85%   |
| Intel Genuine CPU 0000 @ 2.50GHz            | 1         | 0.85%   |
| Intel CPU Version                           | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz          | 1         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.85%   |
| Intel Core i7-2637M CPU                     | 1         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.85%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.85%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 1         | 0.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.85%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 0.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.85%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 0.85%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 0.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 19.49%  |
| Intel Celeron           | 23        | 19.49%  |
| Intel Core i7           | 14        | 11.86%  |
| Intel Core i3           | 12        | 10.17%  |
| Intel Xeon              | 9         | 7.63%   |
| Other                   | 7         | 5.93%   |
| Intel Pentium           | 7         | 5.93%   |
| Intel Atom              | 6         | 5.08%   |
| AMD Ryzen 5             | 4         | 3.39%   |
| Intel Core 2 Duo        | 2         | 1.69%   |
| AMD Ryzen 9             | 2         | 1.69%   |
| Intel Xeon Silver       | 1         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Genuine           | 1         | 0.85%   |
| Intel Celeron Dual-Core | 1         | 0.85%   |
| AMD Ryzen 7             | 1         | 0.85%   |
| AMD Ryzen 3             | 1         | 0.85%   |
| AMD Phenom II X4        | 1         | 0.85%   |
| AMD GX                  | 1         | 0.85%   |
| AMD A10                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 53        | 44.92%  |
| 2       | 49        | 41.53%  |
| 6       | 5         | 4.24%   |
| 8       | 3         | 2.54%   |
| 24      | 2         | 1.69%   |
| 12      | 2         | 1.69%   |
| Unknown | 2         | 1.69%   |
| 16      | 1         | 0.85%   |
| 10      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 117       | 99.15%  |
| Unknown | 1         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 59        | 50%     |
| 2       | 57        | 48.31%  |
| Unknown | 2         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 17.8%   |
| Haswell       | 14        | 11.86%  |
| Skylake       | 11        | 9.32%   |
| Silvermont    | 11        | 9.32%   |
| SandyBridge   | 9         | 7.63%   |
| IvyBridge     | 7         | 5.93%   |
| CometLake     | 5         | 4.24%   |
| Bonnell       | 5         | 4.24%   |
| TigerLake     | 4         | 3.39%   |
| Penryn        | 4         | 3.39%   |
| Goldmont      | 4         | 3.39%   |
| Zen 2         | 3         | 2.54%   |
| Westmere      | 3         | 2.54%   |
| Goldmont plus | 3         | 2.54%   |
| Zen 3         | 2         | 1.69%   |
| Zen           | 2         | 1.69%   |
| K10           | 2         | 1.69%   |
| Broadwell     | 2         | 1.69%   |
| Unknown       | 2         | 1.69%   |
| Zen+          | 1         | 0.85%   |
| Piledriver    | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |
| Core          | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 87        | 63.97%  |
| Nvidia                     | 27        | 19.85%  |
| AMD                        | 16        | 11.76%  |
| Matrox Electronics Systems | 3         | 2.21%   |
| ASPEED Technology          | 3         | 2.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 6.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.84%   |
| Intel HD Graphics 620                                                                    | 6         | 4.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.92%   |
| Intel HD Graphics 530                                                                    | 4         | 2.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.92%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 2.19%   |
| Intel HD Graphics 500                                                                    | 3         | 2.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.19%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.19%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 2.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.46%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 1.46%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.46%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.46%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.46%   |
| Intel HD Graphics 630                                                                    | 2         | 1.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.46%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.46%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.46%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.46%   |
| AMD Renoir                                                                               | 2         | 1.46%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.73%   |
| Nvidia GP107GLM [Quadro P620]                                                            | 1         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.73%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.73%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.73%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.73%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.73%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.73%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.73%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.73%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 0.73%   |
| Nvidia GF104 [GeForce GTX 460 SE]                                                        | 1         | 0.73%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.73%   |
| Nvidia G96CM [GeForce GT 220M]                                                           | 1         | 0.73%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.73%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.73%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.73%   |
| Intel HD Graphics P630                                                                   | 1         | 0.73%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.73%   |
| Intel HD Graphics 510                                                                    | 1         | 0.73%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 0.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 51.69%  |
| Intel + Nvidia | 16        | 13.56%  |
| 1 x Nvidia     | 11        | 9.32%   |
| 1 x AMD        | 10        | 8.47%   |
| 2 x Intel      | 5         | 4.24%   |
| Intel + AMD    | 5         | 4.24%   |
| Other          | 3         | 2.54%   |
| 1 x Matrox     | 3         | 2.54%   |
| 1 x ASPEED     | 3         | 2.54%   |
| 2 x AMD        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 101       | 85.59%  |
| Proprietary | 10        | 8.47%   |
| Unknown     | 7         | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 87.39%  |
| 0.01-0.5   | 6         | 5.04%   |
| 0.51-1.0   | 3         | 2.52%   |
| 7.01-8.0   | 2         | 1.68%   |
| 1.01-2.0   | 2         | 1.68%   |
| 3.01-4.0   | 1         | 0.84%   |
| 8.01-16.0  | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 15.38%  |
| BOE                     | 7         | 13.46%  |
| Chimei Innolux          | 6         | 11.54%  |
| AU Optronics            | 5         | 9.62%   |
| Lenovo                  | 3         | 5.77%   |
| Dell                    | 3         | 5.77%   |
| AOC                     | 3         | 5.77%   |
| Samsung Electronics     | 2         | 3.85%   |
| ZL_                     | 1         | 1.92%   |
| TMX                     | 1         | 1.92%   |
| Philips                 | 1         | 1.92%   |
| PANDA                   | 1         | 1.92%   |
| Panasonic               | 1         | 1.92%   |
| Mi                      | 1         | 1.92%   |
| Haier                   | 1         | 1.92%   |
| GRR                     | 1         | 1.92%   |
| CSO                     | 1         | 1.92%   |
| CND                     | 1         | 1.92%   |
| Chi Mei Optoelectronics | 1         | 1.92%   |
| CAN                     | 1         | 1.92%   |
| BenQ                    | 1         | 1.92%   |
| Apple                   | 1         | 1.92%   |
| Acer                    | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 3.85%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                   | 1         | 1.92%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 1.92%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                        | 1         | 1.92%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 1         | 1.92%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 1.92%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                     | 1         | 1.92%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.92%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch                 | 1         | 1.92%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                            | 1         | 1.92%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 1.92%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                        | 1         | 1.92%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                        | 1         | 1.92%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 1.92%   |
| CND HDMI CND2510 2560x1080 680x290mm 29.1-inch                           | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 1.92%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch                          | 1         | 1.92%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE0877 1920x1080 310x170mm 13.9-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE06B9 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE065D 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BenQ FP91G+ BNQ76A6 1280x1024 380x300mm 19.1-inch                        | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO405C 1366x768 260x140mm 11.6-inch            | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO2026 2560x1600 290x180mm 13.4-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 1.92%   |
| Apple Color LCD APPA02E 2880x1800 330x210mm 15.4-inch                    | 1         | 1.92%   |
| AOC Q27P1B AOC2701 1920x1080 600x340mm 27.2-inch                         | 1         | 1.92%   |
| AOC 2778X AOC2778 2560x1440 600x340mm 27.2-inch                          | 1         | 1.92%   |
| AOC 2479W AOC2479 1920x1080 520x290mm 23.4-inch                          | 1         | 1.92%   |
| Acer G195WV ACR0263 1440x900 410x260mm 19.1-inch                         | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 21        | 40.38%  |
| 1366x768 (WXGA)   | 15        | 28.85%  |
| 2560x1440 (QHD)   | 4         | 7.69%   |
| 1600x900 (HD+)    | 2         | 3.85%   |
| 1440x900 (WXGA+)  | 2         | 3.85%   |
| 3840x2160 (4K)    | 1         | 1.92%   |
| 3200x2000         | 1         | 1.92%   |
| 2880x1800         | 1         | 1.92%   |
| 2880x1620         | 1         | 1.92%   |
| 2560x1600         | 1         | 1.92%   |
| 2560x1080         | 1         | 1.92%   |
| 1920x1200 (WUXGA) | 1         | 1.92%   |
| 1280x1024 (SXGA)  | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 16        | 30.77%  |
| 15     | 15        | 28.85%  |
| 27     | 4         | 7.69%   |
| 23     | 3         | 5.77%   |
| 24     | 2         | 3.85%   |
| 21     | 2         | 3.85%   |
| 19     | 2         | 3.85%   |
| 12     | 2         | 3.85%   |
| 54     | 1         | 1.92%   |
| 29     | 1         | 1.92%   |
| 18     | 1         | 1.92%   |
| 16     | 1         | 1.92%   |
| 14     | 1         | 1.92%   |
| 11     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 53.85%  |
| 501-600     | 9         | 17.31%  |
| 201-300     | 7         | 13.46%  |
| 401-500     | 3         | 5.77%   |
| 351-400     | 3         | 5.77%   |
| 601-700     | 1         | 1.92%   |
| 1001-1500   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 84.31%  |
| 16/10 | 6         | 11.76%  |
| 5/4   | 1         | 1.96%   |
| 21/9  | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 28.85%  |
| 91-100         | 12        | 23.08%  |
| 201-250        | 7         | 13.46%  |
| 301-350        | 5         | 9.62%   |
| 151-200        | 3         | 5.77%   |
| 71-80          | 2         | 3.85%   |
| 61-70          | 2         | 3.85%   |
| 111-120        | 2         | 3.85%   |
| 101-110        | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 51-60          | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 36.54%  |
| 101-120 | 16        | 30.77%  |
| 51-100  | 11        | 21.15%  |
| 161-240 | 6         | 11.54%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 65        | 54.62%  |
| 1     | 53        | 44.54%  |
| 2     | 1         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 50.32%  |
| Realtek Semiconductor | 51        | 32.9%   |
| Qualcomm Atheros      | 13        | 8.39%   |
| Broadcom              | 9         | 5.81%   |
| Ralink Technology     | 1         | 0.65%   |
| Qualcomm              | 1         | 0.65%   |
| Mellanox Technologies | 1         | 0.65%   |
| Edimax Technology     | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 20.83%  |
| Intel I211 Gigabit Network Connection                             | 15        | 7.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.13%   |
| Intel 82583V Gigabit Network Connection                           | 6         | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.6%    |
| Intel I350 Gigabit Network Connection                             | 5         | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 2.08%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.08%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.08%   |
| Intel I210 Gigabit Network Connection                             | 4         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.56%   |
| Intel Wireless 8260                                               | 3         | 1.56%   |
| Intel Wireless 7260                                               | 3         | 1.56%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.04%   |
| Intel Wireless 3165                                               | 2         | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.04%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.52%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.52%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 0.52%   |
| Intel Wireless-AC 9260                                            | 1         | 0.52%   |
| Intel Wireless 3160                                               | 1         | 0.52%   |
| Intel Ethernet Connection X553 1GbE                               | 1         | 0.52%   |
| Intel Ethernet Connection X552 10 GbE SFP+                        | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.52%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 59.38%  |
| Qualcomm Atheros      | 12        | 18.75%  |
| Realtek Semiconductor | 8         | 12.5%   |
| Broadcom              | 4         | 6.25%   |
| Ralink Technology     | 1         | 1.56%   |
| Edimax Technology     | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 5         | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 6.15%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 6.15%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 6.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 6.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.62%   |
| Intel Wireless 8260                                               | 3         | 4.62%   |
| Intel Wireless 7260                                               | 3         | 4.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 3.08%   |
| Intel Wireless 3165                                               | 2         | 3.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 3.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.54%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.54%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1         | 1.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.54%   |
| Intel Wireless-AC 9260                                            | 1         | 1.54%   |
| Intel Wireless 3160                                               | 1         | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.54%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.54%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 1.54%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.54%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.54%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 48.25%  |
| Realtek Semiconductor | 48        | 42.11%  |
| Broadcom              | 6         | 5.26%   |
| Qualcomm Atheros      | 4         | 3.51%   |
| Qualcomm              | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 40        | 31.75%  |
| Intel I211 Gigabit Network Connection                                 | 15        | 11.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 7         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 6         | 4.76%   |
| Intel 82583V Gigabit Network Connection                               | 6         | 4.76%   |
| Intel I350 Gigabit Network Connection                                 | 5         | 3.97%   |
| Intel I210 Gigabit Network Connection                                 | 4         | 3.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 2.38%   |
| Realtek RTL8125 2.5GbE Controller                                     | 2         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                            | 2         | 1.59%   |
| Intel Ethernet Controller I225-V                                      | 2         | 1.59%   |
| Intel Ethernet Connection I217-LM                                     | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                  | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                 | 2         | 1.59%   |
| Intel 82576 Gigabit Network Connection                                | 2         | 1.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                       | 1         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                 | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 1         | 0.79%   |
| Qualcomm ALCATEL Composite RNDIS Interface                            | 1         | 0.79%   |
| Intel Ethernet Connection X553 1GbE                                   | 1         | 0.79%   |
| Intel Ethernet Connection X552 10 GbE SFP+                            | 1         | 0.79%   |
| Intel Ethernet Connection I219-V                                      | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                      | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                  | 1         | 0.79%   |
| Intel Ethernet Connection (13) I219-V                                 | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-V                                 | 1         | 0.79%   |
| Intel 82580 Gigabit Network Connection                                | 1         | 0.79%   |
| Intel 82575GB Gigabit Network Connection                              | 1         | 0.79%   |
| Intel 82575EB Gigabit Network Connection                              | 1         | 0.79%   |
| Intel 82574L Gigabit Network Connection                               | 1         | 0.79%   |
| Intel 82566DM-2 Gigabit Network Connection                            | 1         | 0.79%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                     | 1         | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 1         | 0.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                       | 1         | 0.79%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 63.16%  |
| WiFi     | 62        | 36.26%  |
| Unknown  | 1         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 73.76%  |
| WiFi     | 37        | 26.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 68        | 57.14%  |
| 1     | 19        | 15.97%  |
| 6     | 12        | 10.08%  |
| 4     | 10        | 8.4%    |
| 5     | 5         | 4.2%    |
| 8     | 2         | 1.68%   |
| 7     | 2         | 1.68%   |
| 0     | 1         | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 84.3%   |
| Yes  | 19        | 15.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 60.87%  |
| Realtek Semiconductor           | 3         | 6.52%   |
| Cambridge Silicon Radio         | 3         | 6.52%   |
| Apple                           | 3         | 6.52%   |
| Qualcomm Atheros Communications | 2         | 4.35%   |
| Foxconn / Hon Hai               | 2         | 4.35%   |
| Broadcom                        | 2         | 4.35%   |
| Realtek                         | 1         | 2.17%   |
| Lite-On Technology              | 1         | 2.17%   |
| IMC Networks                    | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 30.43%  |
| Intel AX201 Bluetooth                                       | 5         | 10.87%  |
| Intel AX200 Bluetooth                                       | 4         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 6.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 6.52%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 4.35%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 2.17%   |
| Realtek Bluetooth Radio                                     | 1         | 2.17%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 2.17%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.17%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.17%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 2.17%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 2.17%   |
| Apple Bluetooth Host Controller                             | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 89        | 77.39%  |
| AMD                    | 13        | 11.3%   |
| Nvidia                 | 12        | 10.43%  |
| Generalplus Technology | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 9.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 7.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 5.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 5.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 3.13%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 2.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.34%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 2.34%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 2.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.56%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.78%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.78%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.78%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.78%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.78%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.78%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.78%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.78%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 28.99%  |
| SK hynix            | 20        | 14.49%  |
| Kingston            | 20        | 14.49%  |
| Micron Technology   | 15        | 10.87%  |
| Unknown             | 13        | 9.42%   |
| Ramaxel Technology  | 5         | 3.62%   |
| A-DATA Technology   | 5         | 3.62%   |
| Unknown             | 5         | 3.62%   |
| Nanya Technology    | 3         | 2.17%   |
| Transcend           | 2         | 1.45%   |
| Team                | 2         | 1.45%   |
| G.Skill             | 2         | 1.45%   |
| Unknown (08B5)      | 1         | 0.72%   |
| Ramsta              | 1         | 0.72%   |
| KingTiger           | 1         | 0.72%   |
| Innodisk            | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| Crucial             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 5         | 3.42%   |
| Unknown                                                     | 5         | 3.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 2.74%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 3         | 2.05%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 2         | 1.37%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 1.37%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 1.37%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s               | 1         | 0.68%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s  | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                   | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                  | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                  | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 1         | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1         | 0.68%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s | 1         | 0.68%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 0.68%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s          | 1         | 0.68%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                | 1         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s             | 1         | 0.68%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.68%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.68%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s         | 1         | 0.68%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s       | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 0.68%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s     | 1         | 0.68%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 0.68%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s       | 1         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 0.68%   |
| SK hynix RAM 8ATF1G64HZ-2G3A1 8GB DIMM DDR4 2400MT/s        | 1         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.68%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                 | 1         | 0.68%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 1333MT/s         | 1         | 0.68%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5273DM0-CH9 4GB DIMM DDR3 1333MT/s         | 1         | 0.68%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.68%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB DIMM DDR3 1333MT/s         | 1         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB DDR3 1600MT/s           | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 55        | 47.83%  |
| DDR4    | 50        | 43.48%  |
| LPDDR4  | 3         | 2.61%   |
| DDR2    | 3         | 2.61%   |
| Unknown | 3         | 2.61%   |
| LPDDR3  | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 56.9%   |
| DIMM         | 41        | 35.34%  |
| Row Of Chips | 7         | 6.03%   |
| Unknown      | 2         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 44        | 34.11%  |
| 8192  | 43        | 33.33%  |
| 2048  | 23        | 17.83%  |
| 16384 | 15        | 11.63%  |
| 1024  | 3         | 2.33%   |
| 32768 | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 22.48%  |
| 1333    | 21        | 16.28%  |
| 2133    | 17        | 13.18%  |
| 2667    | 13        | 10.08%  |
| 2400    | 13        | 10.08%  |
| 3200    | 10        | 7.75%   |
| 1334    | 6         | 4.65%   |
| 800     | 5         | 3.88%   |
| 2666    | 3         | 2.33%   |
| 4267    | 2         | 1.55%   |
| 1867    | 2         | 1.55%   |
| 1067    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 2933    | 1         | 0.78%   |
| 1066    | 1         | 0.78%   |
| 667     | 1         | 0.78%   |
| 533     | 1         | 0.78%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 25%     |
| Acer                                   | 6         | 13.64%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Syntek                                 | 3         | 6.82%   |
| IMC Networks                           | 3         | 6.82%   |
| Sunplus Innovation Technology          | 2         | 4.55%   |
| Quanta                                 | 2         | 4.55%   |
| Microdia                               | 2         | 4.55%   |
| Logitech                               | 2         | 4.55%   |
| Lite-On Technology                     | 2         | 4.55%   |
| Z-Star Microelectronics                | 1         | 2.27%   |
| Lenovo                                 | 1         | 2.27%   |
| Importek                               | 1         | 2.27%   |
| Genesys Logic                          | 1         | 2.27%   |
| Foxconn / Hon Hai                      | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| ALi                                    | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 8.89%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 6.67%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 4.44%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.44%   |
| IMC Networks Integrated Camera                                             | 2         | 4.44%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 4.44%   |
| Acer ThinkPad Integrated Camera                                            | 2         | 4.44%   |
| Z-Star Lenovo USB2.0 UVC Camera                                            | 1         | 2.22%   |
| Syntek Integrated Camera                                                   | 1         | 2.22%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2.22%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 2.22%   |
| Realtek Front Camera                                                       | 1         | 2.22%   |
| Quanta Realtek DMFT - RGB                                                  | 1         | 2.22%   |
| Quanta ov9734_techfront_camera                                             | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 2.22%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.22%   |
| Logitech Webcam C170                                                       | 1         | 2.22%   |
| Logitech C670i FHD Webcam                                                  | 1         | 2.22%   |
| Lite-On Integrated Camera                                                  | 1         | 2.22%   |
| Lite-On HP HD Camera                                                       | 1         | 2.22%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 2.22%   |
| Importek USB 2.0 Camera                                                    | 1         | 2.22%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.22%   |
| Genesys Logic Camera                                                       | 1         | 2.22%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2.22%   |
| Chicony Integrated IR Camera                                               | 1         | 2.22%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2.22%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.22%   |
| ALi Gateway Webcam                                                         | 1         | 2.22%   |
| Acer Lenovo Integrated Webcam                                              | 1         | 2.22%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.22%   |
| Acer Integrated Camera                                                     | 1         | 2.22%   |
| Acer EasyCamera                                                            | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 60%     |
| Synaptics                  | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 35.29%  |
| 0     | 35        | 29.41%  |
| 2     | 24        | 20.17%  |
| 3     | 14        | 11.76%  |
| 4     | 4         | 3.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 76        | 55.07%  |
| Net/wireless             | 19        | 13.77%  |
| Card reader              | 17        | 12.32%  |
| Bluetooth                | 12        | 8.7%    |
| Fingerprint reader       | 10        | 7.25%   |
| Net/ethernet             | 2         | 1.45%   |
| Sound                    | 1         | 0.72%   |
| Network                  | 1         | 0.72%   |

