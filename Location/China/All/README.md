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

Total: 189

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | Desktop     | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [6484798368](https://bsd-hardware.info/?probe=6484798368) | Sep 29, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [901ca48f69](https://bsd-hardware.info/?probe=901ca48f69) | Sep 28, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 15        | 9.8%    |
| helloSystem 0.5.0    | 9         | 5.88%   |
| OPNsense 21.7.1      | 8         | 5.23%   |
| OPNsense 21.1.7      | 6         | 3.92%   |
| FreeBSD 13.1         | 6         | 3.92%   |
| OPNsense 21.7.3      | 5         | 3.27%   |
| helloSystem 0.8.0    | 5         | 3.27%   |
| helloSystem 0.6.0    | 5         | 3.27%   |
| helloSystem 0.4.0    | 5         | 3.27%   |
| FreeBSD 12.2         | 5         | 3.27%   |
| OPNsense 21.7.5      | 4         | 2.61%   |
| OPNsense 21.7.2      | 4         | 2.61%   |
| OPNsense 21.1        | 4         | 2.61%   |
| FreeBSD 14.0-CURRENT | 4         | 2.61%   |
| OPNsense 22.7.5      | 3         | 1.96%   |
| OPNsense 21.1.6      | 3         | 1.96%   |
| OPNsense 21.1.3      | 3         | 1.96%   |
| OPNsense 21.1.1      | 3         | 1.96%   |
| GhostBSD 21.08.27    | 3         | 1.96%   |
| FreeBSD 13.1-p2      | 3         | 1.96%   |
| FreeBSD 13.0-p4      | 3         | 1.96%   |
| OPNsense 22.7.4      | 2         | 1.31%   |
| OPNsense 22.7.2      | 2         | 1.31%   |
| OPNsense 22.1.8      | 2         | 1.31%   |
| OPNsense 22.1.4      | 2         | 1.31%   |
| OPNsense 22.1.2      | 2         | 1.31%   |
| OPNsense 22.1.10     | 2         | 1.31%   |
| OPNsense 21.7.4      | 2         | 1.31%   |
| NomadBSD 5806f915    | 2         | 1.31%   |
| FreeBSD 13.0-p7      | 2         | 1.31%   |
| FreeBSD 13.0         | 2         | 1.31%   |
| OPNsense 22.7.6      | 1         | 0.65%   |
| OPNsense 22.7.3      | 1         | 0.65%   |
| OPNsense 22.7        | 1         | 0.65%   |
| OPNsense 22.1.7      | 1         | 0.65%   |
| OPNsense 22.1.3      | 1         | 0.65%   |
| OPNsense 21.7.8      | 1         | 0.65%   |
| OPNsense 21.7.7      | 1         | 0.65%   |
| OPNsense 21.7.6      | 1         | 0.65%   |
| OPNsense 21.7        | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 52        | 38.81%  |
| helloSystem | 39        | 29.1%   |
| FreeBSD     | 36        | 26.87%  |
| NomadBSD    | 3         | 2.24%   |
| GhostBSD    | 3         | 2.24%   |
| OpenBSD     | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 130       | 98.48%  |
| arm64 | 2         | 1.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 60        | 43.8%   |
| helloDesktop | 38        | 27.74%  |
| XFCE         | 11        | 8.03%   |
| KDE5         | 11        | 8.03%   |
| GNOME        | 5         | 3.65%   |
| Openbox      | 3         | 2.19%   |
| MATE         | 3         | 2.19%   |
| i3           | 3         | 2.19%   |
| TWM          | 2         | 1.46%   |
| fvwm         | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 73        | 54.48%  |
| Console | 60        | 44.78%  |
| Wayland | 1         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 65        | 47.79%  |
| SLiM    | 47        | 34.56%  |
| SDDM    | 11        | 8.09%   |
| LightDM | 6         | 4.41%   |
| GDM     | 5         | 3.68%   |
| XDM     | 2         | 1.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 62        | 45.59%  |
| en_US        | 42        | 30.88%  |
| zh_CN        | 16        | 11.76%  |
| C            | 15        | 11.03%  |
| zh_CN.GB2312 | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 112       | 83.58%  |
| BIOS | 22        | 16.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 61        | 45.19%  |
| Zfs    | 59        | 43.7%   |
| Cd9660 | 14        | 10.37%  |
| Ffs    | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 118       | 88.06%  |
| MBR     | 14        | 10.45%  |
| Unknown | 2         | 1.49%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo                                     | 30        | 22.73%  |
| Unknown                                    | 20        | 15.15%  |
| Dell                                       | 14        | 10.61%  |
| Hewlett-Packard                            | 8         | 6.06%   |
| ASUSTek Computer                           | 8         | 6.06%   |
| Gigabyte Technology                        | 5         | 3.79%   |
| MSI                                        | 4         | 3.03%   |
| Supermicro                                 | 3         | 2.27%   |
| Intel                                      | 3         | 2.27%   |
| Sony                                       | 2         | 1.52%   |
| ShenZhen MinWin Technology                 | 2         | 1.52%   |
| PAIQ                                       | 2         | 1.52%   |
| Notebook                                   | 2         | 1.52%   |
| NEC Computers                              | 2         | 1.52%   |
| HUAWEI                                     | 2         | 1.52%   |
| Google                                     | 2         | 1.52%   |
| ASRock                                     | 2         | 1.52%   |
| AMI                                        | 2         | 1.52%   |
| YANYU                                      | 1         | 0.76%   |
| WOOKING                                    | 1         | 0.76%   |
| WlanCN                                     | 1         | 0.76%   |
| Toshiba                                    | 1         | 0.76%   |
| Timi                                       | 1         | 0.76%   |
| Techvision                                 | 1         | 0.76%   |
| Protectli                                  | 1         | 0.76%   |
| Panasonic                                  | 1         | 0.76%   |
| OEM                                        | 1         | 0.76%   |
| MAXSUN                                     | 1         | 0.76%   |
| HASEE Computer                             | 1         | 0.76%   |
| GuoGuang                                   | 1         | 0.76%   |
| Colorful YuGong Technology And Development | 1         | 0.76%   |
| Colorful Technology                        | 1         | 0.76%   |
| CNCTION-IAF-E3845                          | 1         | 0.76%   |
| Centerm                                    | 1         | 0.76%   |
| Apple                                      | 1         | 0.76%   |
| AMD                                        | 1         | 0.76%   |
| Acer                                       | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 21        | 15.91%  |
| ShenZhen MinWin MW-NANO-APL-4L              | 2         | 1.52%   |
| PAIQ EC3-BT19D4L                            | 2         | 1.52%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 1.52%   |
| HP ProLiant DL320e Gen8 v2                  | 2         | 1.52%   |
| AMI Aptio CRB                               | 2         | 1.52%   |
| YANYU ITX-N29 VER:1.5 baytrail              | 1         | 0.76%   |
| WOOKING X5                                  | 1         | 0.76%   |
| WlanCN 6000 Series                          | 1         | 0.76%   |
| Toshiba Satellite Pro L510                  | 1         | 0.76%   |
| Timi RedmiBook Pro 15                       | 1         | 0.76%   |
| Techvision TVI7309X                         | 1         | 0.76%   |
| Supermicro X10SRA                           | 1         | 0.76%   |
| Supermicro X10SL7-F                         | 1         | 0.76%   |
| Supermicro Super Server                     | 1         | 0.76%   |
| Sony SVS1511AJB                             | 1         | 0.76%   |
| Sony SVP13225SCBI                           | 1         | 0.76%   |
| Protectli FW6                               | 1         | 0.76%   |
| Panasonic CF-B11JWCYS                       | 1         | 0.76%   |
| OEM B85 JHS359                              | 1         | 0.76%   |
| Notebook W65KJ1_KK1                         | 1         | 0.76%   |
| Notebook W650DC,DD                          | 1         | 0.76%   |
| NEC Computers SHARKBAY                      | 1         | 0.76%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.76%   |
| MSI MS-7C82                                 | 1         | 0.76%   |
| MSI MS-7C37                                 | 1         | 0.76%   |
| MSI MS-7A38                                 | 1         | 0.76%   |
| MSI MS-7972                                 | 1         | 0.76%   |
| MAXSUN MS-H110D4L FS M.2                    | 1         | 0.76%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 0.76%   |
| Lenovo YangTianW2090v-00                    | 1         | 0.76%   |
| Lenovo YangTianM6880N                       | 1         | 0.76%   |
| Lenovo YangTianA8800T                       | 1         | 0.76%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.76%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.76%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 0.76%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.76%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 0.76%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 21        | 15.91%  |
| Lenovo ThinkPad                | 13        | 9.85%   |
| Dell Latitude                  | 4         | 3.03%   |
| Dell OptiPlex                  | 3         | 2.27%   |
| ShenZhen MinWin MW-NANO-APL-4L | 2         | 1.52%   |
| PAIQ EC3-BT19D4L               | 2         | 1.52%   |
| Lenovo ThinkCentre             | 2         | 1.52%   |
| HP ProLiant                    | 2         | 1.52%   |
| HP ProBook                     | 2         | 1.52%   |
| Dell Precision                 | 2         | 1.52%   |
| Dell PowerEdge                 | 2         | 1.52%   |
| Dell Inspiron                  | 2         | 1.52%   |
| ASUS TUF                       | 2         | 1.52%   |
| AMI Aptio                      | 2         | 1.52%   |
| YANYU ITX-N29                  | 1         | 0.76%   |
| WOOKING X5                     | 1         | 0.76%   |
| WlanCN 6000                    | 1         | 0.76%   |
| Toshiba Satellite              | 1         | 0.76%   |
| Timi RedmiBook                 | 1         | 0.76%   |
| Techvision TVI7309X            | 1         | 0.76%   |
| Supermicro X10SRA              | 1         | 0.76%   |
| Supermicro X10SL7-F            | 1         | 0.76%   |
| Supermicro Super               | 1         | 0.76%   |
| Sony SVS1511AJB                | 1         | 0.76%   |
| Sony SVP13225SCBI              | 1         | 0.76%   |
| Protectli FW6                  | 1         | 0.76%   |
| Panasonic CF-B11JWCYS          | 1         | 0.76%   |
| OEM B85                        | 1         | 0.76%   |
| Notebook W65KJ1                | 1         | 0.76%   |
| Notebook W650DC                | 1         | 0.76%   |
| NEC Computers SHARKBAY         | 1         | 0.76%   |
| NEC Computers PC-VK17HBBCD     | 1         | 0.76%   |
| MSI MS-7C82                    | 1         | 0.76%   |
| MSI MS-7C37                    | 1         | 0.76%   |
| MSI MS-7A38                    | 1         | 0.76%   |
| MSI MS-7972                    | 1         | 0.76%   |
| MAXSUN MS-H110D4L              | 1         | 0.76%   |
| Lenovo ZhaoYang                | 1         | 0.76%   |
| Lenovo YangTianW2090v-00       | 1         | 0.76%   |
| Lenovo YangTianM6880N          | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 14.39%  |
| 2019    | 16        | 12.12%  |
| 2017    | 15        | 11.36%  |
| 2012    | 12        | 9.09%   |
| 2020    | 10        | 7.58%   |
| 2022    | 9         | 6.82%   |
| 2018    | 9         | 6.82%   |
| 2016    | 8         | 6.06%   |
| 2013    | 8         | 6.06%   |
| 2014    | 7         | 5.3%    |
| 2011    | 6         | 4.55%   |
| 2015    | 5         | 3.79%   |
| 2010    | 3         | 2.27%   |
| 2009    | 2         | 1.52%   |
| 2008    | 1         | 0.76%   |
| 2007    | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 62        | 46.97%  |
| Notebook       | 54        | 40.91%  |
| Server         | 8         | 6.06%   |
| Mini pc        | 5         | 3.79%   |
| System on chip | 1         | 0.76%   |
| Convertible    | 1         | 0.76%   |
| All in one     | 1         | 0.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 97.73%  |
| Yes  | 3         | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 47        | 35.34%  |
| 4.01-8.0    | 35        | 26.32%  |
| 16.01-24.0  | 24        | 18.05%  |
| 32.01-64.0  | 10        | 7.52%   |
| 2.01-3.0    | 8         | 6.02%   |
| 24.01-32.0  | 4         | 3.01%   |
| 64.01-256.0 | 2         | 1.5%    |
| 0.51-1.0    | 2         | 1.5%    |
| 1.01-2.0    | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 78        | 58.65%  |
| 0.51-1.0 | 34        | 25.56%  |
| 1.01-2.0 | 19        | 14.29%  |
| 3.01-4.0 | 1         | 0.75%   |
| 2.01-3.0 | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 64.71%  |
| 2      | 22        | 16.18%  |
| 0      | 16        | 11.76%  |
| 3      | 6         | 4.41%   |
| 5      | 3         | 2.21%   |
| 4      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 80.45%  |
| Yes       | 26        | 19.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 90.15%  |
| No        | 13        | 9.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 51.52%  |
| No        | 64        | 48.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 60.61%  |
| Yes       | 52        | 39.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 132       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 19        | 13.48%  |
| Shanghai         | 15        | 10.64%  |
| Shenzhen         | 11        | 7.8%    |
| Guangzhou        | 10        | 7.09%   |
| Chengdu          | 8         | 5.67%   |
| Zhengzhou        | 5         | 3.55%   |
| Hangzhou         | 4         | 2.84%   |
| Xi'an            | 3         | 2.13%   |
| Wuhan            | 3         | 2.13%   |
| Nanjing          | 3         | 2.13%   |
| Jinrongjie       | 3         | 2.13%   |
| Xiamen           | 2         | 1.42%   |
| Qinnan           | 2         | 1.42%   |
| Qingdao          | 2         | 1.42%   |
| Changzhou        | 2         | 1.42%   |
| Changchun        | 2         | 1.42%   |
| Baiyun           | 2         | 1.42%   |
| Zhumadian        | 1         | 0.71%   |
| Zhongshan        | 1         | 0.71%   |
| Zhaoqing         | 1         | 0.71%   |
| Yichun           | 1         | 0.71%   |
| Yangpu           | 1         | 0.71%   |
| Yancheng         | 1         | 0.71%   |
| Xicheng District | 1         | 0.71%   |
| Wuxi             | 1         | 0.71%   |
| Weifang          | 1         | 0.71%   |
| Tongshan         | 1         | 0.71%   |
| Tongchuanshi     | 1         | 0.71%   |
| Tieling          | 1         | 0.71%   |
| Suzhou           | 1         | 0.71%   |
| Shizishan        | 1         | 0.71%   |
| Shahekou         | 1         | 0.71%   |
| Qingpu           | 1         | 0.71%   |
| Putuo            | 1         | 0.71%   |
| Putian           | 1         | 0.71%   |
| Pudong           | 1         | 0.71%   |
| Ningbo           | 1         | 0.71%   |
| Luoyang          | 1         | 0.71%   |
| Liuzhou          | 1         | 0.71%   |
| Linyi            | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 34     | 16.03%  |
| Seagate             | 22        | 27     | 14.1%   |
| WDC                 | 20        | 34     | 12.82%  |
| Intel               | 11        | 12     | 7.05%   |
| Toshiba             | 10        | 11     | 6.41%   |
| SanDisk             | 7         | 8      | 4.49%   |
| Kingston            | 5         | 5      | 3.21%   |
| HGST                | 5         | 7      | 3.21%   |
| China               | 4         | 7      | 2.56%   |
| Netac               | 3         | 3      | 1.92%   |
| Hitachi             | 3         | 3      | 1.92%   |
| Crucial             | 3         | 3      | 1.92%   |
| Transcend           | 2         | 2      | 1.28%   |
| SK hynix            | 2         | 2      | 1.28%   |
| Silicon Motion      | 2         | 2      | 1.28%   |
| Plextor             | 2         | 3      | 1.28%   |
| Micron Technology   | 2         | 3      | 1.28%   |
| Lenovo              | 2         | 2      | 1.28%   |
| KIOXIA              | 2         | 2      | 1.28%   |
| KingSpec            | 2         | 2      | 1.28%   |
| Hikvision           | 2         | 2      | 1.28%   |
| Hewlett-Packard     | 2         | 2      | 1.28%   |
| Colorful            | 2         | 2      | 1.28%   |
| tigo                | 1         | 1      | 0.64%   |
| Ramsta              | 1         | 1      | 0.64%   |
| Pioneer             | 1         | 1      | 0.64%   |
| ORICO               | 1         | 1      | 0.64%   |
| LITEONIT            | 1         | 1      | 0.64%   |
| Lexar               | 1         | 1      | 0.64%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.64%   |
| Hoodisk             | 1         | 2      | 0.64%   |
| FREEBSD             | 1         | 1      | 0.64%   |
| FORESEE             | 1         | 1      | 0.64%   |
| Faspeed             | 1         | 1      | 0.64%   |
| BR                  | 1         | 1      | 0.64%   |
| BIWIN               | 1         | 3      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |
| Apacer              | 1         | 1      | 0.64%   |
| A-DATA Technology   | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 4         | 2.33%   |
| Toshiba MQ04ABF100 1TB          | 2         | 1.16%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 1.16%   |
| Seagate ST1000LM048-2E7172 1TB  | 2         | 1.16%   |
| SanDisk SSD U100 24GB           | 2         | 1.16%   |
| Samsung SSD 970 EVO Plus 1TB    | 2         | 1.16%   |
| Samsung SSD 870 EVO 1TB         | 2         | 1.16%   |
| Samsung MZVL21T0HCLR-00BL7 1TB  | 2         | 1.16%   |
| Samsung HM320II 320GB           | 2         | 1.16%   |
| Netac SSD 120GB                 | 2         | 1.16%   |
| Intel SSDSA2SH032G1GN 32GB      | 2         | 1.16%   |
| Intel SSDSA2CW120G3 120GB       | 2         | 1.16%   |
| Hikvision HS-SSD-C2000ECO 1024G | 2         | 1.16%   |
| HGST HTS541010B7E610 1TB        | 2         | 1.16%   |
| WDC WUH721414ALE6L4 14TB        | 1         | 0.58%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1         | 0.58%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1         | 0.58%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1         | 0.58%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1         | 0.58%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 1         | 0.58%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1         | 0.58%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1         | 0.58%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1         | 0.58%   |
| WDC WD40NPZZ-00A9JT0 4TB        | 1         | 0.58%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1         | 0.58%   |
| WDC WD3200BPVT-75ZEST0 320GB    | 1         | 0.58%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1         | 0.58%   |
| WDC WD2500BEVS-08VAT2 250GB     | 1         | 0.58%   |
| WDC WD20SPZX-75UA7T0 2TB        | 1         | 0.58%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1         | 0.58%   |
| WDC WD2003FYYS-007BA0 2TB       | 1         | 0.58%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1         | 0.58%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1         | 0.58%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1         | 0.58%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 0.58%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1         | 0.58%   |
| WDC WD10SPCX-00KHST0 1TB        | 1         | 0.58%   |
| WDC WD10JPVX-00JC3T0 1TB        | 1         | 0.58%   |
| WDC WD10EZEX-21WN4A0 1TB        | 1         | 0.58%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 27     | 40%     |
| WDC                 | 15        | 24     | 27.27%  |
| Toshiba             | 7         | 7      | 12.73%  |
| HGST                | 5         | 7      | 9.09%   |
| Hitachi             | 3         | 3      | 5.45%   |
| Samsung Electronics | 2         | 4      | 3.64%   |
| Hewlett-Packard     | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 18.06%  |
| Intel               | 10        | 11     | 13.89%  |
| SanDisk             | 7         | 8      | 9.72%   |
| Kingston            | 4         | 4      | 5.56%   |
| China               | 4         | 7      | 5.56%   |
| Netac               | 3         | 3      | 4.17%   |
| WDC                 | 2         | 2      | 2.78%   |
| Transcend           | 2         | 2      | 2.78%   |
| Toshiba             | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 3      | 2.78%   |
| Lenovo              | 2         | 2      | 2.78%   |
| KingSpec            | 2         | 2      | 2.78%   |
| tigo                | 1         | 1      | 1.39%   |
| Ramsta              | 1         | 1      | 1.39%   |
| Plextor             | 1         | 1      | 1.39%   |
| ORICO               | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| Lexar               | 1         | 1      | 1.39%   |
| KIOXIA-EXCERIA      | 1         | 2      | 1.39%   |
| Hoodisk             | 1         | 2      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| FREEBSD             | 1         | 1      | 1.39%   |
| FORESEE             | 1         | 1      | 1.39%   |
| Faspeed             | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| Colorful            | 1         | 1      | 1.39%   |
| BR                  | 1         | 1      | 1.39%   |
| BIWIN               | 1         | 3      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| A-DATA Technology   | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 68        | 83     | 45.95%  |
| HDD  | 48        | 73     | 32.43%  |
| NVMe | 32        | 42     | 21.62%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 156    | 76.12%  |
| NVMe | 32        | 42     | 23.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 107    | 66.39%  |
| 0.51-1.0   | 28        | 32     | 22.95%  |
| 1.01-2.0   | 7         | 8      | 5.74%   |
| 3.01-4.0   | 2         | 2      | 1.64%   |
| 2.01-3.0   | 2         | 3      | 1.64%   |
| 10.01-20.0 | 1         | 2      | 0.82%   |
| 4.01-10.0  | 1         | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 39        | 28.26%  |
| 251-500    | 29        | 21.01%  |
| 101-250    | 29        | 21.01%  |
| 21-50      | 14        | 10.14%  |
| 51-100     | 12        | 8.7%    |
| 501-1000   | 8         | 5.8%    |
| 1001-2000  | 5         | 3.62%   |
| Unknown    | 2         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 116       | 86.57%  |
| 21-50   | 10        | 7.46%   |
| 51-100  | 3         | 2.24%   |
| 251-500 | 2         | 1.49%   |
| Unknown | 2         | 1.49%   |
| 101-250 | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-22L7A0 160GB     | 1         | 1      | 5.88%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 5.88%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1         | 1      | 5.88%   |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 5.88%   |
| Seagate ST3320418AS 320GB       | 1         | 2      | 5.88%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 5.88%   |
| Seagate ST31500541AS 1.5TB      | 1         | 1      | 5.88%   |
| Seagate ST31000528AS 1TB        | 1         | 1      | 5.88%   |
| Intel SSDSA2M160G2GC 160GB      | 1         | 2      | 5.88%   |
| Intel SSDSA2M120G2GC 120GB      | 1         | 1      | 5.88%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB      | 1         | 2      | 5.88%   |
| Colorful SL500 640GB            | 1         | 1      | 5.88%   |
| China XJH-32GB                  | 1         | 1      | 5.88%   |
| China JWX 16GB MSATA            | 1         | 2      | 5.88%   |
| BIWIN SSD 32GB                  | 1         | 3      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 6      | 29.41%  |
| WDC      | 3         | 3      | 17.65%  |
| Intel    | 2         | 3      | 11.76%  |
| China    | 2         | 3      | 11.76%  |
| Toshiba  | 1         | 1      | 5.88%   |
| Hitachi  | 1         | 1      | 5.88%   |
| HGST     | 1         | 2      | 5.88%   |
| Colorful | 1         | 1      | 5.88%   |
| BIWIN    | 1         | 3      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 45.45%  |
| WDC     | 3         | 3      | 27.27%  |
| Toshiba | 1         | 1      | 9.09%   |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 64.71%  |
| SSD  | 6         | 10     | 35.29%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 108       | 174    | 85.71%  |
| Malfunc  | 17        | 23     | 13.49%  |
| Detected | 1         | 1      | 0.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 104       | 65.82%  |
| Samsung Electronics          | 14        | 8.86%   |
| AMD                          | 13        | 8.23%   |
| SanDisk                      | 6         | 3.8%    |
| Broadcom / LSI               | 4         | 2.53%   |
| Silicon Motion               | 3         | 1.9%    |
| SK hynix                     | 2         | 1.27%   |
| Micron/Crucial Technology    | 2         | 1.27%   |
| MAXIO Technology (Hangzhou)  | 2         | 1.27%   |
| KIOXIA                       | 2         | 1.27%   |
| Toshiba                      | 1         | 0.63%   |
| Shenzhen Longsys Electronics | 1         | 0.63%   |
| Lite-On Technology           | 1         | 0.63%   |
| Kingston Technology Company  | 1         | 0.63%   |
| JMicron Technology           | 1         | 0.63%   |
| ASMedia Technology           | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 8.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 5.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 5.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 3.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 3.98%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 3.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 1.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.14%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 2         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.14%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 2         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.14%   |
| Unknown                                                                          | 2         | 1.14%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.57%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                      | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 106       | 66.67%  |
| NVMe | 32        | 20.13%  |
| IDE  | 14        | 8.81%   |
| RAID | 5         | 3.14%   |
| SAS  | 2         | 1.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 113       | 85.61%  |
| AMD     | 17        | 12.88%  |
| ARM     | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz             | 8         | 6.06%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 3         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.27%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 2.27%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 2.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.27%   |
| Intel Pentium CPU G3260T @ 2.90GHz            | 2         | 1.52%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.52%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 2         | 1.52%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.52%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 1.52%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 2         | 1.52%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.52%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.52%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz         | 1         | 0.76%   |
| Intel Xeon CPU X5647 @ 2.93GHz                | 1         | 0.76%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 0.76%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.76%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.76%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 1         | 0.76%   |
| Intel Xeon CPU D-1537 @ 1.70GHz               | 1         | 0.76%   |
| Intel Xeon                                    | 1         | 0.76%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 0.76%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.76%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 0.76%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.76%   |
| Intel Pentium CPU G3460T @ 3.00GHz            | 1         | 0.76%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.76%   |
| Intel Genuine CPU 0000 @ 2.50GHz              | 1         | 0.76%   |
| Intel CPU Version                             | 1         | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i7-8559U CPU @ 2.70GHz             | 1         | 0.76%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.76%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.76%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 25        | 18.94%  |
| Intel Core i5           | 24        | 18.18%  |
| Intel Core i7           | 16        | 12.12%  |
| Intel Core i3           | 13        | 9.85%   |
| Intel Xeon              | 10        | 7.58%   |
| Other                   | 7         | 5.3%    |
| Intel Pentium           | 7         | 5.3%    |
| Intel Atom              | 6         | 4.55%   |
| AMD Ryzen 5             | 6         | 4.55%   |
| Intel Core 2 Duo        | 3         | 2.27%   |
| AMD Ryzen 9             | 2         | 1.52%   |
| AMD Ryzen 7             | 2         | 1.52%   |
| AMD G                   | 2         | 1.52%   |
| Intel Xeon Silver       | 1         | 0.76%   |
| Intel Pentium Dual-Core | 1         | 0.76%   |
| Intel Genuine           | 1         | 0.76%   |
| Intel Celeron Dual-Core | 1         | 0.76%   |
| ARM Cortex              | 1         | 0.76%   |
| AMD Ryzen 3             | 1         | 0.76%   |
| AMD Phenom II X4        | 1         | 0.76%   |
| AMD GX                  | 1         | 0.76%   |
| AMD A10                 | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 58        | 43.94%  |
| 2       | 54        | 40.91%  |
| 6       | 5         | 3.79%   |
| 8       | 4         | 3.03%   |
| 12      | 3         | 2.27%   |
| Unknown | 3         | 2.27%   |
| 24      | 2         | 1.52%   |
| 16      | 2         | 1.52%   |
| 10      | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 130       | 98.48%  |
| Unknown | 2         | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 69        | 52.27%  |
| 2       | 60        | 45.45%  |
| Unknown | 3         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 18.18%  |
| Haswell       | 14        | 10.61%  |
| Skylake       | 12        | 9.09%   |
| Silvermont    | 12        | 9.09%   |
| SandyBridge   | 9         | 6.82%   |
| IvyBridge     | 7         | 5.3%    |
| CometLake     | 6         | 4.55%   |
| Penryn        | 5         | 3.79%   |
| Bonnell       | 5         | 3.79%   |
| Zen 2         | 4         | 3.03%   |
| TigerLake     | 4         | 3.03%   |
| Goldmont      | 4         | 3.03%   |
| Zen+          | 3         | 2.27%   |
| Westmere      | 3         | 2.27%   |
| Goldmont plus | 3         | 2.27%   |
| Broadwell     | 3         | 2.27%   |
| Unknown       | 3         | 2.27%   |
| Zen 3         | 2         | 1.52%   |
| Zen           | 2         | 1.52%   |
| K10           | 2         | 1.52%   |
| Bobcat        | 2         | 1.52%   |
| Piledriver    | 1         | 0.76%   |
| Jaguar        | 1         | 0.76%   |
| Core          | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 94        | 62.67%  |
| Nvidia                     | 29        | 19.33%  |
| AMD                        | 20        | 13.33%  |
| Matrox Electronics Systems | 4         | 2.67%   |
| ASPEED Technology          | 3         | 2%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.3%    |
| Intel HD Graphics 620                                                                    | 6         | 3.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.65%   |
| Intel HD Graphics 530                                                                    | 4         | 2.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.65%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 1.99%   |
| Intel HD Graphics 500                                                                    | 3         | 1.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.99%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.32%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 1.32%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.32%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.32%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.32%   |
| Intel HD Graphics 630                                                                    | 2         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.32%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.32%   |
| AMD Renoir                                                                               | 2         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.32%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.66%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.66%   |
| Nvidia GP107GLM [Quadro P620]                                                            | 1         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 50.76%  |
| Intel + Nvidia | 17        | 12.88%  |
| 1 x AMD        | 14        | 10.61%  |
| 1 x Nvidia     | 12        | 9.09%   |
| 2 x Intel      | 5         | 3.79%   |
| Intel + AMD    | 5         | 3.79%   |
| Other          | 4         | 3.03%   |
| 1 x Matrox     | 4         | 3.03%   |
| 1 x ASPEED     | 3         | 2.27%   |
| 2 x AMD        | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 112       | 84.85%  |
| Proprietary | 12        | 9.09%   |
| Unknown     | 8         | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 86.47%  |
| 0.01-0.5   | 6         | 4.51%   |
| 0.51-1.0   | 4         | 3.01%   |
| 7.01-8.0   | 3         | 2.26%   |
| 1.01-2.0   | 2         | 1.5%    |
| 5.01-6.0   | 1         | 0.75%   |
| 3.01-4.0   | 1         | 0.75%   |
| 8.01-16.0  | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 13.33%  |
| AU Optronics            | 8         | 13.33%  |
| BOE                     | 7         | 11.67%  |
| Chimei Innolux          | 6         | 10%     |
| Dell                    | 5         | 8.33%   |
| Lenovo                  | 4         | 6.67%   |
| AOC                     | 3         | 5%      |
| Samsung Electronics     | 2         | 3.33%   |
| Philips                 | 2         | 3.33%   |
| CSO                     | 2         | 3.33%   |
| ZL_                     | 1         | 1.67%   |
| TMX                     | 1         | 1.67%   |
| PANDA                   | 1         | 1.67%   |
| Panasonic               | 1         | 1.67%   |
| Mi                      | 1         | 1.67%   |
| Haier                   | 1         | 1.67%   |
| GRR                     | 1         | 1.67%   |
| CND                     | 1         | 1.67%   |
| Chi Mei Optoelectronics | 1         | 1.67%   |
| CAN                     | 1         | 1.67%   |
| BenQ                    | 1         | 1.67%   |
| Apple                   | 1         | 1.67%   |
| Acer                    | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 3.33%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                   | 1         | 1.67%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch     | 1         | 1.67%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                    | 1         | 1.67%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                        | 1         | 1.67%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch                  | 1         | 1.67%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 1.67%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                     | 1         | 1.67%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.67%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                    | 1         | 1.67%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch                 | 1         | 1.67%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                            | 1         | 1.67%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                        | 1         | 1.67%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                        | 1         | 1.67%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                        | 1         | 1.67%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                        | 1         | 1.67%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                       | 1         | 1.67%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                    | 1         | 1.67%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                    | 1         | 1.67%   |
| CND HDMI CND2510 2560x1080 680x290mm 29.1-inch                           | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1368 1366x768 290x160mm 13.0-inch          | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 310x170mm 13.9-inch | 1         | 1.67%   |
| CAN F55C CAN0055 3840x2160 1210x680mm 54.6-inch                          | 1         | 1.67%   |
| BOE LCD Monitor BOE0973 2560x1440 340x190mm 15.3-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0928 1920x1080 340x190mm 15.3-inch                    | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 41.67%  |
| 1366x768 (WXGA)    | 16        | 26.67%  |
| 2560x1440 (QHD)    | 4         | 6.67%   |
| 1440x900 (WXGA+)   | 3         | 5%      |
| 2560x1600          | 2         | 3.33%   |
| 1600x900 (HD+)     | 2         | 3.33%   |
| 3840x2160 (4K)     | 1         | 1.67%   |
| 3200x2000          | 1         | 1.67%   |
| 2880x1800          | 1         | 1.67%   |
| 2880x1620          | 1         | 1.67%   |
| 2560x1080          | 1         | 1.67%   |
| 1920x1200 (WUXGA)  | 1         | 1.67%   |
| 1680x1050 (WSXGA+) | 1         | 1.67%   |
| 1280x1024 (SXGA)   | 1         | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 20        | 33.33%  |
| 15     | 15        | 25%     |
| 27     | 4         | 6.67%   |
| 23     | 4         | 6.67%   |
| 24     | 3         | 5%      |
| 19     | 3         | 5%      |
| 21     | 2         | 3.33%   |
| 12     | 2         | 3.33%   |
| 54     | 1         | 1.67%   |
| 29     | 1         | 1.67%   |
| 22     | 1         | 1.67%   |
| 18     | 1         | 1.67%   |
| 16     | 1         | 1.67%   |
| 14     | 1         | 1.67%   |
| 11     | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 50%     |
| 501-600     | 11        | 18.33%  |
| 201-300     | 9         | 15%     |
| 401-500     | 5         | 8.33%   |
| 351-400     | 3         | 5%      |
| 601-700     | 1         | 1.67%   |
| 1001-1500   | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 81.36%  |
| 16/10 | 9         | 15.25%  |
| 5/4   | 1         | 1.69%   |
| 21/9  | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 30%     |
| 91-100         | 12        | 20%     |
| 201-250        | 10        | 16.67%  |
| 301-350        | 5         | 8.33%   |
| 151-200        | 4         | 6.67%   |
| 71-80          | 3         | 5%      |
| 61-70          | 2         | 3.33%   |
| 111-120        | 2         | 3.33%   |
| 101-110        | 2         | 3.33%   |
| More than 1000 | 1         | 1.67%   |
| 51-60          | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 33.33%  |
| 101-120 | 17        | 28.33%  |
| 51-100  | 15        | 25%     |
| 161-240 | 8         | 13.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 52.99%  |
| 1     | 62        | 46.27%  |
| 2     | 1         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 86        | 49.71%  |
| Realtek Semiconductor    | 58        | 33.53%  |
| Qualcomm Atheros         | 13        | 7.51%   |
| Broadcom                 | 11        | 6.36%   |
| Ralink Technology        | 1         | 0.58%   |
| Qualcomm                 | 1         | 0.58%   |
| Mellanox Technologies    | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Edimax Technology        | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 21.7%   |
| Intel I211 Gigabit Network Connection                             | 15        | 7.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.83%   |
| Intel 82583V Gigabit Network Connection                           | 6         | 2.83%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.36%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.36%   |
| Intel I350 Gigabit Network Connection                             | 5         | 2.36%   |
| Intel I210 Gigabit Network Connection                             | 5         | 2.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.89%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 4         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.42%   |
| Intel Wireless 8260                                               | 3         | 1.42%   |
| Intel Wireless 7260                                               | 3         | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.94%   |
| Intel Wireless 3165                                               | 2         | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.94%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.47%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 60.56%  |
| Qualcomm Atheros      | 12        | 16.9%   |
| Realtek Semiconductor | 9         | 12.68%  |
| Broadcom              | 5         | 7.04%   |
| Ralink Technology     | 1         | 1.41%   |
| Edimax Technology     | 1         | 1.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 5         | 6.94%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 6.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 5.56%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 5.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 4.17%   |
| Intel Wireless 8260                                               | 3         | 4.17%   |
| Intel Wireless 7260                                               | 3         | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 2.78%   |
| Intel Wireless 3165                                               | 2         | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.39%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.39%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.39%   |
| Intel Wireless-AC 9260                                            | 1         | 1.39%   |
| Intel Wireless 7265                                               | 1         | 1.39%   |
| Intel Wireless 3160                                               | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.39%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.39%   |
| Intel Centrino Wireless-N 2200                                    | 1         | 1.39%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.39%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.39%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 60        | 47.24%  |
| Realtek Semiconductor    | 54        | 42.52%  |
| Broadcom                 | 7         | 5.51%   |
| Qualcomm Atheros         | 4         | 3.15%   |
| Qualcomm                 | 1         | 0.79%   |
| Marvell Technology Group | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 33.09%  |
| Intel I211 Gigabit Network Connection                             | 15        | 10.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 4.32%   |
| Intel 82583V Gigabit Network Connection                           | 6         | 4.32%   |
| Intel I350 Gigabit Network Connection                             | 5         | 3.6%    |
| Intel I210 Gigabit Network Connection                             | 5         | 3.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 4         | 2.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.44%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.44%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 1.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.72%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.72%   |
| Intel Ethernet Connection X553 1GbE                               | 1         | 0.72%   |
| Intel Ethernet Connection X552 10 GbE SFP+                        | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.72%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.72%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.72%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 0.72%   |
| Intel 82575GB Gigabit Network Connection                          | 1         | 0.72%   |
| Intel 82575EB Gigabit Network Connection                          | 1         | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 119       | 63.3%   |
| WiFi     | 68        | 36.17%  |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 114       | 74.03%  |
| WiFi     | 40        | 25.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 74        | 55.64%  |
| 1     | 24        | 18.05%  |
| 6     | 14        | 10.53%  |
| 4     | 10        | 7.52%   |
| 5     | 5         | 3.76%   |
| 8     | 2         | 1.5%    |
| 7     | 2         | 1.5%    |
| 0     | 2         | 1.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 82.96%  |
| Yes  | 23        | 17.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 63.46%  |
| Realtek Semiconductor           | 3         | 5.77%   |
| Cambridge Silicon Radio         | 3         | 5.77%   |
| Apple                           | 3         | 5.77%   |
| Qualcomm Atheros Communications | 2         | 3.85%   |
| Lite-On Technology              | 2         | 3.85%   |
| Foxconn / Hon Hai               | 2         | 3.85%   |
| Broadcom                        | 2         | 3.85%   |
| Realtek                         | 1         | 1.92%   |
| IMC Networks                    | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 28.85%  |
| Intel AX201 Bluetooth                                       | 6         | 11.54%  |
| Intel AX200 Bluetooth                                       | 5         | 9.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 5.77%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.85%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.92%   |
| Realtek Bluetooth Radio                                     | 1         | 1.92%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.92%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.92%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.92%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.92%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.92%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.92%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 1.92%   |
| Apple Bluetooth Host Controller                             | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 95        | 74.8%   |
| AMD                    | 18        | 14.17%  |
| Nvidia                 | 13        | 10.24%  |
| Generalplus Technology | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 4.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 4.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 2.07%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 2.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.38%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.38%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.38%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.38%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 26.8%   |
| SK hynix            | 25        | 16.34%  |
| Kingston            | 25        | 16.34%  |
| Micron Technology   | 15        | 9.8%    |
| Unknown             | 14        | 9.15%   |
| A-DATA Technology   | 7         | 4.58%   |
| Ramaxel Technology  | 5         | 3.27%   |
| Unknown             | 5         | 3.27%   |
| Nanya Technology    | 3         | 1.96%   |
| Transcend           | 2         | 1.31%   |
| Team                | 2         | 1.31%   |
| G.Skill             | 2         | 1.31%   |
| Unknown (08B5)      | 1         | 0.65%   |
| Ramsta              | 1         | 0.65%   |
| KingTiger           | 1         | 0.65%   |
| Innodisk            | 1         | 0.65%   |
| Elpida              | 1         | 0.65%   |
| Crucial             | 1         | 0.65%   |
| Corsair             | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 5         | 3.07%   |
| Unknown                                                      | 5         | 3.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 2.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 3         | 1.84%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 3         | 1.84%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 2         | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 2         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.23%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 2         | 1.23%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s         | 2         | 1.23%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                   | 2         | 1.23%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s                | 1         | 0.61%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s   | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1         | 0.61%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s        | 1         | 0.61%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s  | 1         | 0.61%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s         | 1         | 0.61%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s       | 1         | 0.61%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s           | 1         | 0.61%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.61%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.61%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.61%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s              | 1         | 0.61%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s         | 1         | 0.61%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 0.61%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1         | 0.61%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1         | 0.61%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 0.61%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s          | 1         | 0.61%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s        | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 45.31%  |
| DDR3    | 58        | 45.31%  |
| DDR2    | 4         | 3.13%   |
| LPDDR4  | 3         | 2.34%   |
| Unknown | 3         | 2.34%   |
| LPDDR3  | 2         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 55.04%  |
| DIMM         | 47        | 36.43%  |
| Row Of Chips | 8         | 6.2%    |
| Unknown      | 3         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 48        | 33.57%  |
| 8192  | 47        | 32.87%  |
| 2048  | 26        | 18.18%  |
| 16384 | 18        | 12.59%  |
| 1024  | 3         | 2.1%    |
| 32768 | 1         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 21.38%  |
| 1333    | 22        | 15.17%  |
| 2133    | 19        | 13.1%   |
| 2667    | 16        | 11.03%  |
| 2400    | 16        | 11.03%  |
| 3200    | 11        | 7.59%   |
| 800     | 7         | 4.83%   |
| 1334    | 6         | 4.14%   |
| 2933    | 3         | 2.07%   |
| 2666    | 3         | 2.07%   |
| 4267    | 2         | 1.38%   |
| 1867    | 2         | 1.38%   |
| 1067    | 2         | 1.38%   |
| Unknown | 2         | 1.38%   |
| 1066    | 1         | 0.69%   |
| 667     | 1         | 0.69%   |
| 533     | 1         | 0.69%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 26.53%  |
| Realtek Semiconductor                  | 6         | 12.24%  |
| Acer                                   | 6         | 12.24%  |
| Syntek                                 | 3         | 6.12%   |
| Microdia                               | 3         | 6.12%   |
| IMC Networks                           | 3         | 6.12%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Quanta                                 | 2         | 4.08%   |
| Logitech                               | 2         | 4.08%   |
| Lite-On Technology                     | 2         | 4.08%   |
| Z-Star Microelectronics                | 1         | 2.04%   |
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


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 5         | 10%     |
| Realtek Integrated_Webcam_HD                                               | 3         | 6%      |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 6%      |
| Chicony Lenovo EasyCamera                                                  | 3         | 6%      |
| Syntek Lenovo EasyCamera                                                   | 2         | 4%      |
| IMC Networks Integrated Camera                                             | 2         | 4%      |
| Acer ThinkPad Integrated Camera                                            | 2         | 4%      |
| Z-Star Lenovo USB2.0 UVC Camera                                            | 1         | 2%      |
| Syntek Integrated Camera                                                   | 1         | 2%      |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                                               | 1         | 2%      |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 2%      |
| Realtek HD WebCam                                                          | 1         | 2%      |
| Realtek Front Camera                                                       | 1         | 2%      |
| Quanta Realtek DMFT - RGB                                                  | 1         | 2%      |
| Quanta ov9734_techfront_camera                                             | 1         | 2%      |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                              | 1         | 2%      |
| Microdia Camera                                                            | 1         | 2%      |
| Logitech Webcam C170                                                       | 1         | 2%      |
| Logitech C670i FHD Webcam                                                  | 1         | 2%      |
| Lite-On Integrated Camera                                                  | 1         | 2%      |
| Lite-On HP HD Camera                                                       | 1         | 2%      |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 2%      |
| Importek USB 2.0 Camera                                                    | 1         | 2%      |
| IMC Networks Integrated Webcam                                             | 1         | 2%      |
| Genesys Logic Camera                                                       | 1         | 2%      |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 2%      |
| Chicony Integrated IR Camera                                               | 1         | 2%      |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 2%      |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| ALi Gateway Webcam                                                         | 1         | 2%      |
| Acer Lenovo Integrated Webcam                                              | 1         | 2%      |
| Acer Lenovo EasyCamera                                                     | 1         | 2%      |
| Acer Integrated Camera                                                     | 1         | 2%      |
| Acer EasyCamera                                                            | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 60%     |
| Synaptics                  | 2         | 20%     |
| Upek                       | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 33.83%  |
| 0     | 42        | 31.58%  |
| 2     | 27        | 20.3%   |
| 3     | 15        | 11.28%  |
| 4     | 4         | 3.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 82        | 55.41%  |
| Net/wireless             | 20        | 13.51%  |
| Card reader              | 17        | 11.49%  |
| Bluetooth                | 15        | 10.14%  |
| Fingerprint reader       | 10        | 6.76%   |
| Net/ethernet             | 2         | 1.35%   |
| Sound                    | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |

