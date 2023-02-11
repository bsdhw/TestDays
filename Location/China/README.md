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

Total: 206

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| HASEE Comp... | N95XKP6                     | Notebook    | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| ASUSTek       | PRIME H310T2 R2.0           | All in one  | [d1cc7c07e0](https://bsd-hardware.info/?probe=d1cc7c07e0) | Dec 02, 2022 |
| Acidanther... | MacBookPro15,1              | Notebook    | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 20        | 11.83%  |
| helloSystem 0.5.0    | 9         | 5.33%   |
| OPNsense 21.7.1      | 8         | 4.73%   |
| FreeBSD 13.1         | 7         | 4.14%   |
| OPNsense 21.1.7      | 6         | 3.55%   |
| helloSystem 0.8.0    | 6         | 3.55%   |
| OPNsense 21.7.3      | 5         | 2.96%   |
| helloSystem 0.6.0    | 5         | 2.96%   |
| helloSystem 0.4.0    | 5         | 2.96%   |
| FreeBSD 13.1-p2      | 5         | 2.96%   |
| FreeBSD 12.2         | 5         | 2.96%   |
| OPNsense 21.7.5      | 4         | 2.37%   |
| OPNsense 21.7.2      | 4         | 2.37%   |
| OPNsense 21.1        | 4         | 2.37%   |
| FreeBSD 14.0-CURRENT | 4         | 2.37%   |
| OPNsense 22.7.5      | 3         | 1.78%   |
| OPNsense 21.1.6      | 3         | 1.78%   |
| OPNsense 21.1.3      | 3         | 1.78%   |
| OPNsense 21.1.1      | 3         | 1.78%   |
| GhostBSD 21.08.27    | 3         | 1.78%   |
| FreeBSD 13.0-p4      | 3         | 1.78%   |
| OPNsense 22.7.9      | 2         | 1.18%   |
| OPNsense 22.7.4      | 2         | 1.18%   |
| OPNsense 22.7.2      | 2         | 1.18%   |
| OPNsense 22.1.8      | 2         | 1.18%   |
| OPNsense 22.1.4      | 2         | 1.18%   |
| OPNsense 22.1.2      | 2         | 1.18%   |
| OPNsense 22.1.10     | 2         | 1.18%   |
| OPNsense 21.7.4      | 2         | 1.18%   |
| NomadBSD 5806f915    | 2         | 1.18%   |
| FreeBSD 13.1-p5      | 2         | 1.18%   |
| FreeBSD 13.0-p7      | 2         | 1.18%   |
| FreeBSD 13.0         | 2         | 1.18%   |
| OPNsense 22.7.8      | 1         | 0.59%   |
| OPNsense 22.7.6      | 1         | 0.59%   |
| OPNsense 22.7.3      | 1         | 0.59%   |
| OPNsense 22.7        | 1         | 0.59%   |
| OPNsense 22.1.7      | 1         | 0.59%   |
| OPNsense 22.1.3      | 1         | 0.59%   |
| OPNsense 21.7.8      | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 53        | 36.3%   |
| helloSystem | 44        | 30.14%  |
| FreeBSD     | 42        | 28.77%  |
| NomadBSD    | 3         | 2.05%   |
| GhostBSD    | 3         | 2.05%   |
| OpenBSD     | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 142       | 98.61%  |
| arm64 | 2         | 1.39%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 62        | 41.61%  |
| helloDesktop | 43        | 28.86%  |
| XFCE         | 12        | 8.05%   |
| KDE5         | 11        | 7.38%   |
| i3           | 5         | 3.36%   |
| GNOME        | 5         | 3.36%   |
| MATE         | 4         | 2.68%   |
| Openbox      | 3         | 2.01%   |
| TWM          | 2         | 1.34%   |
| GNUstep      | 1         | 0.67%   |
| fvwm         | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 56.85%  |
| Console | 62        | 42.47%  |
| Wayland | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 69        | 46.62%  |
| SLiM    | 53        | 35.81%  |
| SDDM    | 11        | 7.43%   |
| LightDM | 7         | 4.73%   |
| GDM     | 5         | 3.38%   |
| XDM     | 3         | 2.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 64        | 42.95%  |
| en_US        | 48        | 32.21%  |
| zh_CN        | 19        | 12.75%  |
| C            | 17        | 11.41%  |
| zh_CN.GB2312 | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 123       | 84.25%  |
| BIOS | 23        | 15.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 66        | 44.59%  |
| Ufs    | 63        | 42.57%  |
| Cd9660 | 18        | 12.16%  |
| Ffs    | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 130       | 89.04%  |
| MBR     | 14        | 9.59%   |
| Unknown | 2         | 1.37%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo                                     | 33        | 22.92%  |
| Unknown                                    | 20        | 13.89%  |
| Dell                                       | 16        | 11.11%  |
| ASUSTek Computer                           | 9         | 6.25%   |
| Hewlett-Packard                            | 8         | 5.56%   |
| Gigabyte Technology                        | 5         | 3.47%   |
| MSI                                        | 4         | 2.78%   |
| Supermicro                                 | 3         | 2.08%   |
| ShenZhen MinWin Technology                 | 3         | 2.08%   |
| Intel                                      | 3         | 2.08%   |
| Sony                                       | 2         | 1.39%   |
| PAIQ                                       | 2         | 1.39%   |
| Notebook                                   | 2         | 1.39%   |
| NEC Computers                              | 2         | 1.39%   |
| HUAWEI                                     | 2         | 1.39%   |
| HASEE Computer                             | 2         | 1.39%   |
| Google                                     | 2         | 1.39%   |
| ASRock                                     | 2         | 1.39%   |
| AMI                                        | 2         | 1.39%   |
| YANYU                                      | 1         | 0.69%   |
| WOOKING                                    | 1         | 0.69%   |
| WlanCN                                     | 1         | 0.69%   |
| Toshiba                                    | 1         | 0.69%   |
| TOPFEEL                                    | 1         | 0.69%   |
| Timi                                       | 1         | 0.69%   |
| Techvision                                 | 1         | 0.69%   |
| Samsung Electronics                        | 1         | 0.69%   |
| Protectli                                  | 1         | 0.69%   |
| Panasonic                                  | 1         | 0.69%   |
| ONDA                                       | 1         | 0.69%   |
| OEM                                        | 1         | 0.69%   |
| MAXSUN                                     | 1         | 0.69%   |
| GuoGuang                                   | 1         | 0.69%   |
| Colorful YuGong Technology And Development | 1         | 0.69%   |
| Colorful Technology                        | 1         | 0.69%   |
| CNCTION-IAF-E3845                          | 1         | 0.69%   |
| Centerm                                    | 1         | 0.69%   |
| Apple                                      | 1         | 0.69%   |
| AMD                                        | 1         | 0.69%   |
| Acidanthera                                | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 21        | 14.58%  |
| ShenZhen MinWin MW-NANO-APL-4L              | 3         | 2.08%   |
| PAIQ EC3-BT19D4L                            | 2         | 1.39%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 1.39%   |
| HP ProLiant DL320e Gen8 v2                  | 2         | 1.39%   |
| AMI Aptio CRB                               | 2         | 1.39%   |
| YANYU ITX-N29 VER:1.5 baytrail              | 1         | 0.69%   |
| WOOKING X5                                  | 1         | 0.69%   |
| WlanCN 6000 Series                          | 1         | 0.69%   |
| Toshiba Satellite Pro L510                  | 1         | 0.69%   |
| TOPFEEL Topone series                       | 1         | 0.69%   |
| Timi RedmiBook Pro 15                       | 1         | 0.69%   |
| Techvision TVI7309X                         | 1         | 0.69%   |
| Supermicro X10SRA                           | 1         | 0.69%   |
| Supermicro X10SL7-F                         | 1         | 0.69%   |
| Supermicro Super Server                     | 1         | 0.69%   |
| Sony SVS1511AJB                             | 1         | 0.69%   |
| Sony SVP13225SCBI                           | 1         | 0.69%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 0.69%   |
| Protectli FW6                               | 1         | 0.69%   |
| Panasonic CF-B11JWCYS                       | 1         | 0.69%   |
| ONDA N78G5D3 Ver:5.00                       | 1         | 0.69%   |
| OEM B85 JHS359                              | 1         | 0.69%   |
| Notebook W65KJ1_KK1                         | 1         | 0.69%   |
| Notebook W650DC,DD                          | 1         | 0.69%   |
| NEC Computers SHARKBAY                      | 1         | 0.69%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.69%   |
| MSI MS-7C82                                 | 1         | 0.69%   |
| MSI MS-7C37                                 | 1         | 0.69%   |
| MSI MS-7A38                                 | 1         | 0.69%   |
| MSI MS-7972                                 | 1         | 0.69%   |
| MAXSUN MS-H110D4L FS M.2                    | 1         | 0.69%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 0.69%   |
| Lenovo YangTianW2090v-00                    | 1         | 0.69%   |
| Lenovo YangTianM6880N                       | 1         | 0.69%   |
| Lenovo YangTianA8800T                       | 1         | 0.69%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.69%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.69%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 0.69%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 21        | 14.58%  |
| Lenovo ThinkPad                | 15        | 10.42%  |
| Dell Latitude                  | 4         | 2.78%   |
| ShenZhen MinWin MW-NANO-APL-4L | 3         | 2.08%   |
| Dell Precision                 | 3         | 2.08%   |
| Dell PowerEdge                 | 3         | 2.08%   |
| Dell OptiPlex                  | 3         | 2.08%   |
| PAIQ EC3-BT19D4L               | 2         | 1.39%   |
| Lenovo ThinkCentre             | 2         | 1.39%   |
| HP ProLiant                    | 2         | 1.39%   |
| HP ProBook                     | 2         | 1.39%   |
| Dell Inspiron                  | 2         | 1.39%   |
| ASUS TUF                       | 2         | 1.39%   |
| AMI Aptio                      | 2         | 1.39%   |
| YANYU ITX-N29                  | 1         | 0.69%   |
| WOOKING X5                     | 1         | 0.69%   |
| WlanCN 6000                    | 1         | 0.69%   |
| Toshiba Satellite              | 1         | 0.69%   |
| TOPFEEL Topone                 | 1         | 0.69%   |
| Timi RedmiBook                 | 1         | 0.69%   |
| Techvision TVI7309X            | 1         | 0.69%   |
| Supermicro X10SRA              | 1         | 0.69%   |
| Supermicro X10SL7-F            | 1         | 0.69%   |
| Supermicro Super               | 1         | 0.69%   |
| Sony SVS1511AJB                | 1         | 0.69%   |
| Sony SVP13225SCBI              | 1         | 0.69%   |
| Samsung 3570R                  | 1         | 0.69%   |
| Protectli FW6                  | 1         | 0.69%   |
| Panasonic CF-B11JWCYS          | 1         | 0.69%   |
| ONDA N78G5D3                   | 1         | 0.69%   |
| OEM B85                        | 1         | 0.69%   |
| Notebook W65KJ1                | 1         | 0.69%   |
| Notebook W650DC                | 1         | 0.69%   |
| NEC Computers SHARKBAY         | 1         | 0.69%   |
| NEC Computers PC-VK17HBBCD     | 1         | 0.69%   |
| MSI MS-7C82                    | 1         | 0.69%   |
| MSI MS-7C37                    | 1         | 0.69%   |
| MSI MS-7A38                    | 1         | 0.69%   |
| MSI MS-7972                    | 1         | 0.69%   |
| MAXSUN MS-H110D4L              | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 13.19%  |
| 2019    | 17        | 11.81%  |
| 2017    | 16        | 11.11%  |
| 2012    | 14        | 9.72%   |
| 2020    | 12        | 8.33%   |
| 2018    | 11        | 7.64%   |
| 2013    | 11        | 7.64%   |
| 2022    | 10        | 6.94%   |
| 2016    | 8         | 5.56%   |
| 2014    | 7         | 4.86%   |
| 2011    | 6         | 4.17%   |
| 2015    | 5         | 3.47%   |
| 2010    | 3         | 2.08%   |
| 2009    | 2         | 1.39%   |
| 2008    | 1         | 0.69%   |
| 2007    | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 66        | 45.83%  |
| Notebook       | 60        | 41.67%  |
| Server         | 9         | 6.25%   |
| Mini pc        | 5         | 3.47%   |
| All in one     | 2         | 1.39%   |
| System on chip | 1         | 0.69%   |
| Convertible    | 1         | 0.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 141       | 97.92%  |
| Yes  | 3         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 52        | 35.86%  |
| 4.01-8.0    | 38        | 26.21%  |
| 16.01-24.0  | 27        | 18.62%  |
| 32.01-64.0  | 11        | 7.59%   |
| 2.01-3.0    | 8         | 5.52%   |
| 24.01-32.0  | 4         | 2.76%   |
| 64.01-256.0 | 2         | 1.38%   |
| 0.51-1.0    | 2         | 1.38%   |
| 1.01-2.0    | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 86        | 59.31%  |
| 0.51-1.0 | 37        | 25.52%  |
| 1.01-2.0 | 20        | 13.79%  |
| 3.01-4.0 | 1         | 0.69%   |
| 2.01-3.0 | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 96        | 64.43%  |
| 2      | 26        | 17.45%  |
| 0      | 17        | 11.41%  |
| 3      | 6         | 4.03%   |
| 5      | 3         | 2.01%   |
| 4      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 80%     |
| Yes       | 29        | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 90.28%  |
| No        | 14        | 9.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 52.78%  |
| No        | 68        | 47.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 85        | 59.03%  |
| Yes       | 59        | 40.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 144       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Beijing          | 19        | 12.42%  |
| Shanghai         | 16        | 10.46%  |
| Shenzhen         | 13        | 8.5%    |
| Guangzhou        | 11        | 7.19%   |
| Chengdu          | 8         | 5.23%   |
| Zhengzhou        | 5         | 3.27%   |
| Hangzhou         | 4         | 2.61%   |
| Xi'an            | 3         | 1.96%   |
| Wuhan            | 3         | 1.96%   |
| Nanjing          | 3         | 1.96%   |
| Jinrongjie       | 3         | 1.96%   |
| Yancheng         | 2         | 1.31%   |
| Xiamen           | 2         | 1.31%   |
| Qinnan           | 2         | 1.31%   |
| Qingdao          | 2         | 1.31%   |
| Jiangbei         | 2         | 1.31%   |
| Changzhou        | 2         | 1.31%   |
| Changchun        | 2         | 1.31%   |
| Baiyun           | 2         | 1.31%   |
| Zhumadian        | 1         | 0.65%   |
| Zhongshan        | 1         | 0.65%   |
| Zhaoqing         | 1         | 0.65%   |
| Yuefeng          | 1         | 0.65%   |
| Yichun           | 1         | 0.65%   |
| Yangpu           | 1         | 0.65%   |
| Xicheng District | 1         | 0.65%   |
| Wuxi             | 1         | 0.65%   |
| Wenzhou          | 1         | 0.65%   |
| Weifang          | 1         | 0.65%   |
| Tongshan         | 1         | 0.65%   |
| Tongchuanshi     | 1         | 0.65%   |
| Tieling          | 1         | 0.65%   |
| Suzhou           | 1         | 0.65%   |
| Shizishan        | 1         | 0.65%   |
| Shantou          | 1         | 0.65%   |
| Shahekou         | 1         | 0.65%   |
| Qiqihar          | 1         | 0.65%   |
| Qingpu           | 1         | 0.65%   |
| Putuo            | 1         | 0.65%   |
| Putian           | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 38     | 15.79%  |
| Seagate             | 23        | 29     | 13.45%  |
| WDC                 | 22        | 36     | 12.87%  |
| Intel               | 13        | 15     | 7.6%    |
| Toshiba             | 10        | 11     | 5.85%   |
| SanDisk             | 7         | 8      | 4.09%   |
| Kingston            | 6         | 6      | 3.51%   |
| Hitachi             | 5         | 5      | 2.92%   |
| HGST                | 5         | 9      | 2.92%   |
| China               | 4         | 7      | 2.34%   |
| Plextor             | 3         | 4      | 1.75%   |
| Netac               | 3         | 3      | 1.75%   |
| Lenovo              | 3         | 3      | 1.75%   |
| Hikvision           | 3         | 3      | 1.75%   |
| Crucial             | 3         | 3      | 1.75%   |
| Transcend           | 2         | 2      | 1.17%   |
| SK hynix            | 2         | 2      | 1.17%   |
| Silicon Motion      | 2         | 2      | 1.17%   |
| Micron Technology   | 2         | 3      | 1.17%   |
| KIOXIA-EXCERIA      | 2         | 3      | 1.17%   |
| KIOXIA              | 2         | 2      | 1.17%   |
| KingSpec            | 2         | 2      | 1.17%   |
| Hewlett-Packard     | 2         | 2      | 1.17%   |
| Colorful            | 2         | 2      | 1.17%   |
| tigo                | 1         | 1      | 0.58%   |
| Ramsta              | 1         | 1      | 0.58%   |
| Pioneer             | 1         | 1      | 0.58%   |
| Phison              | 1         | 1      | 0.58%   |
| ORICO               | 1         | 1      | 0.58%   |
| LITEONIT            | 1         | 1      | 0.58%   |
| Lexar               | 1         | 1      | 0.58%   |
| Hoodisk             | 1         | 2      | 0.58%   |
| FREEBSD             | 1         | 1      | 0.58%   |
| FORESEE             | 1         | 1      | 0.58%   |
| Faspeed             | 1         | 1      | 0.58%   |
| BR                  | 1         | 1      | 0.58%   |
| BIWIN               | 1         | 3      | 0.58%   |
| Apple               | 1         | 1      | 0.58%   |
| Apacer              | 1         | 1      | 0.58%   |
| A-DATA Technology   | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 4         | 2.14%   |
| Samsung SSD 860 EVO 500GB       | 3         | 1.6%    |
| Toshiba MQ04ABF100 1TB          | 2         | 1.07%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 1.07%   |
| Seagate ST2000LM007-1R8174 2TB  | 2         | 1.07%   |
| Seagate ST1000LM048-2E7172 1TB  | 2         | 1.07%   |
| SanDisk SSD U100 24GB           | 2         | 1.07%   |
| Samsung SSD 970 EVO Plus 1TB    | 2         | 1.07%   |
| Samsung SSD 870 EVO 1TB         | 2         | 1.07%   |
| Samsung MZVL21T0HCLR-00BL7 1TB  | 2         | 1.07%   |
| Samsung HM320II 320GB           | 2         | 1.07%   |
| Netac SSD 120GB                 | 2         | 1.07%   |
| Intel SSDSA2SH032G1GN 32GB      | 2         | 1.07%   |
| Intel SSDSA2CW120G3 120GB       | 2         | 1.07%   |
| Hikvision HS-SSD-C2000ECO 1024G | 2         | 1.07%   |
| HGST HTS541010B7E610 1TB        | 2         | 1.07%   |
| WDC WUH721414ALE6L4 14TB        | 1         | 0.53%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1         | 0.53%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1         | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1         | 0.53%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1         | 0.53%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 1         | 0.53%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1         | 0.53%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1         | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 1         | 0.53%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 1         | 0.53%   |
| WDC WD40NPZZ-00A9JT0 4TB        | 1         | 0.53%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1         | 0.53%   |
| WDC WD3200BPVT-75ZEST0 320GB    | 1         | 0.53%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1         | 0.53%   |
| WDC WD2500BEVS-08VAT2 250GB     | 1         | 0.53%   |
| WDC WD20SPZX-75UA7T0 2TB        | 1         | 0.53%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1         | 0.53%   |
| WDC WD2003FYYS-007BA0 2TB       | 1         | 0.53%   |
| WDC WD1600BEVT-22ZCT0 160GB     | 1         | 0.53%   |
| WDC WD1600AAJS-22L7A0 160GB     | 1         | 0.53%   |
| WDC WD120EMAZ-11BLFA0 12TB      | 1         | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 0.53%   |
| WDC WD10SPZX-00Z10T0 1TB        | 1         | 0.53%   |
| WDC WD10SPCX-00KHST0 1TB        | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 29     | 38.33%  |
| WDC                 | 17        | 26     | 28.33%  |
| Toshiba             | 7         | 7      | 11.67%  |
| Hitachi             | 5         | 5      | 8.33%   |
| HGST                | 5         | 9      | 8.33%   |
| Samsung Electronics | 2         | 4      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 18.52%  |
| Intel               | 12        | 14     | 14.81%  |
| SanDisk             | 7         | 8      | 8.64%   |
| Kingston            | 5         | 5      | 6.17%   |
| China               | 4         | 7      | 4.94%   |
| Netac               | 3         | 3      | 3.7%    |
| Lenovo              | 3         | 3      | 3.7%    |
| WDC                 | 2         | 2      | 2.47%   |
| Transcend           | 2         | 2      | 2.47%   |
| Toshiba             | 2         | 2      | 2.47%   |
| Plextor             | 2         | 2      | 2.47%   |
| Micron Technology   | 2         | 3      | 2.47%   |
| KIOXIA-EXCERIA      | 2         | 3      | 2.47%   |
| KingSpec            | 2         | 2      | 2.47%   |
| tigo                | 1         | 1      | 1.23%   |
| Ramsta              | 1         | 1      | 1.23%   |
| Phison              | 1         | 1      | 1.23%   |
| ORICO               | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| Lexar               | 1         | 1      | 1.23%   |
| Hoodisk             | 1         | 2      | 1.23%   |
| Hewlett-Packard     | 1         | 1      | 1.23%   |
| FREEBSD             | 1         | 1      | 1.23%   |
| FORESEE             | 1         | 1      | 1.23%   |
| Faspeed             | 1         | 1      | 1.23%   |
| Crucial             | 1         | 1      | 1.23%   |
| Colorful            | 1         | 1      | 1.23%   |
| BR                  | 1         | 1      | 1.23%   |
| BIWIN               | 1         | 3      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |
| Apacer              | 1         | 1      | 1.23%   |
| A-DATA Technology   | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 77        | 93     | 47.24%  |
| HDD  | 53        | 81     | 32.52%  |
| NVMe | 33        | 45     | 20.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 174    | 77.4%   |
| NVMe | 33        | 45     | 22.6%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 122    | 67.16%  |
| 0.51-1.0   | 30        | 34     | 22.39%  |
| 1.01-2.0   | 8         | 9      | 5.97%   |
| 3.01-4.0   | 2         | 2      | 1.49%   |
| 2.01-3.0   | 2         | 3      | 1.49%   |
| 10.01-20.0 | 1         | 2      | 0.75%   |
| 4.01-10.0  | 1         | 2      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 43        | 28.48%  |
| 101-250    | 33        | 21.85%  |
| 251-500    | 32        | 21.19%  |
| 21-50      | 15        | 9.93%   |
| 51-100     | 12        | 7.95%   |
| 501-1000   | 9         | 5.96%   |
| 1001-2000  | 5         | 3.31%   |
| Unknown    | 2         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 126       | 86.3%   |
| 21-50   | 12        | 8.22%   |
| 51-100  | 3         | 2.05%   |
| 251-500 | 2         | 1.37%   |
| Unknown | 2         | 1.37%   |
| 101-250 | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-22L7A0 160GB     | 1         | 1      | 5.56%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 5.56%   |
| WDC WD10EJRX-89N74Y0 1TB        | 1         | 1      | 5.56%   |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 5.56%   |
| Seagate ST3320418AS 320GB       | 1         | 2      | 5.56%   |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 5.56%   |
| Seagate ST31500541AS 1.5TB      | 1         | 1      | 5.56%   |
| Seagate ST31000528AS 1TB        | 1         | 1      | 5.56%   |
| Intel SSDSA2M160G2GC 160GB      | 1         | 2      | 5.56%   |
| Intel SSDSA2M120G2GC 120GB      | 1         | 1      | 5.56%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 5.56%   |
| HGST HTS725050A7E630 500GB      | 1         | 4      | 5.56%   |
| Colorful SL500 640GB            | 1         | 1      | 5.56%   |
| China XJH-32GB                  | 1         | 1      | 5.56%   |
| China JWX 16GB MSATA            | 1         | 2      | 5.56%   |
| BIWIN SSD 32GB                  | 1         | 3      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 6      | 27.78%  |
| WDC      | 3         | 3      | 16.67%  |
| Intel    | 2         | 3      | 11.11%  |
| Hitachi  | 2         | 2      | 11.11%  |
| China    | 2         | 3      | 11.11%  |
| Toshiba  | 1         | 1      | 5.56%   |
| HGST     | 1         | 4      | 5.56%   |
| Colorful | 1         | 1      | 5.56%   |
| BIWIN    | 1         | 3      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 41.67%  |
| WDC     | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |
| HGST    | 1         | 4      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 16     | 66.67%  |
| SSD  | 6         | 10     | 33.33%  |

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
| Works    | 118       | 191    | 85.51%  |
| Malfunc  | 18        | 26     | 13.04%  |
| Detected | 2         | 2      | 1.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 115       | 67.25%  |
| Samsung Electronics          | 14        | 8.19%   |
| AMD                          | 13        | 7.6%    |
| SanDisk                      | 6         | 3.51%   |
| Silicon Motion               | 4         | 2.34%   |
| Broadcom / LSI               | 4         | 2.34%   |
| SK hynix                     | 2         | 1.17%   |
| Micron/Crucial Technology    | 2         | 1.17%   |
| MAXIO Technology (Hangzhou)  | 2         | 1.17%   |
| KIOXIA                       | 2         | 1.17%   |
| Toshiba                      | 1         | 0.58%   |
| Shenzhen Longsys Electronics | 1         | 0.58%   |
| Nvidia                       | 1         | 0.58%   |
| Lite-On Technology           | 1         | 0.58%   |
| Kingston Technology Company  | 1         | 0.58%   |
| JMicron Technology           | 1         | 0.58%   |
| ASMedia Technology           | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 7.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 5.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 5.26%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 4.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 3.68%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 2.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 1.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.58%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.58%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 2         | 1.05%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.05%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.05%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 2         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.05%   |
| Unknown                                                                          | 2         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 67.44%  |
| NVMe | 33        | 19.19%  |
| IDE  | 15        | 8.72%   |
| RAID | 6         | 3.49%   |
| SAS  | 2         | 1.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 124       | 86.11%  |
| AMD     | 18        | 12.5%   |
| ARM     | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz             | 8         | 5.56%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 3         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.08%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 2.08%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 3         | 2.08%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.08%   |
| Intel Pentium CPU G3260T @ 2.90GHz            | 2         | 1.39%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.39%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 2         | 1.39%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.39%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 2         | 1.39%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.39%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.39%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz         | 1         | 0.69%   |
| Intel Xeon CPU X5647 @ 2.93GHz                | 1         | 0.69%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz           | 1         | 0.69%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 0.69%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.69%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.69%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 1         | 0.69%   |
| Intel Xeon CPU D-1537 @ 1.70GHz               | 1         | 0.69%   |
| Intel Xeon                                    | 1         | 0.69%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz   | 1         | 0.69%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.69%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 0.69%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.69%   |
| Intel Pentium CPU G3460T @ 3.00GHz            | 1         | 0.69%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.69%   |
| Intel Genuine CPU 0000 @ 2.50GHz              | 1         | 0.69%   |
| Intel CPU Version                             | 1         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.69%   |
| Intel Core i7-8559U CPU @ 2.70GHz             | 1         | 0.69%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.69%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 20.14%  |
| Intel Celeron           | 26        | 18.06%  |
| Intel Core i7           | 17        | 11.81%  |
| Intel Core i3           | 15        | 10.42%  |
| Intel Xeon              | 12        | 8.33%   |
| Other                   | 7         | 4.86%   |
| Intel Pentium           | 7         | 4.86%   |
| Intel Atom              | 6         | 4.17%   |
| AMD Ryzen 5             | 6         | 4.17%   |
| Intel Core 2 Duo        | 3         | 2.08%   |
| AMD Ryzen 9             | 2         | 1.39%   |
| AMD Ryzen 7             | 2         | 1.39%   |
| AMD G                   | 2         | 1.39%   |
| Intel Xeon Silver       | 1         | 0.69%   |
| Intel Pentium Dual-Core | 1         | 0.69%   |
| Intel Genuine           | 1         | 0.69%   |
| Intel Celeron Dual-Core | 1         | 0.69%   |
| ARM Cortex              | 1         | 0.69%   |
| AMD Ryzen 3             | 1         | 0.69%   |
| AMD Phenom II X4        | 1         | 0.69%   |
| AMD GX                  | 1         | 0.69%   |
| AMD Athlon II X4        | 1         | 0.69%   |
| AMD A10                 | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 61        | 42.36%  |
| 2       | 59        | 40.97%  |
| 6       | 7         | 4.86%   |
| 12      | 4         | 2.78%   |
| 8       | 4         | 2.78%   |
| Unknown | 3         | 2.08%   |
| 24      | 2         | 1.39%   |
| 16      | 2         | 1.39%   |
| 20      | 1         | 0.69%   |
| 10      | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 141       | 97.92%  |
| Unknown | 2         | 1.39%   |
| 2       | 1         | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 73        | 50.69%  |
| 2       | 68        | 47.22%  |
| Unknown | 3         | 2.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 19.44%  |
| Haswell       | 15        | 10.42%  |
| Skylake       | 12        | 8.33%   |
| Silvermont    | 12        | 8.33%   |
| IvyBridge     | 11        | 7.64%   |
| SandyBridge   | 10        | 6.94%   |
| CometLake     | 6         | 4.17%   |
| Penryn        | 5         | 3.47%   |
| Goldmont      | 5         | 3.47%   |
| Bonnell       | 5         | 3.47%   |
| Zen 2         | 4         | 2.78%   |
| TigerLake     | 4         | 2.78%   |
| Zen+          | 3         | 2.08%   |
| Westmere      | 3         | 2.08%   |
| K10           | 3         | 2.08%   |
| Goldmont plus | 3         | 2.08%   |
| Broadwell     | 3         | 2.08%   |
| Unknown       | 3         | 2.08%   |
| Zen 3         | 2         | 1.39%   |
| Zen           | 2         | 1.39%   |
| Bobcat        | 2         | 1.39%   |
| Piledriver    | 1         | 0.69%   |
| Jaguar        | 1         | 0.69%   |
| Core          | 1         | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 102       | 61.82%  |
| Nvidia                     | 34        | 20.61%  |
| AMD                        | 21        | 12.73%  |
| Matrox Electronics Systems | 5         | 3.03%   |
| ASPEED Technology          | 3         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.82%   |
| Intel HD Graphics 620                                                                    | 6         | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 2.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.41%   |
| Intel HD Graphics 530                                                                    | 4         | 2.41%   |
| Intel HD Graphics 500                                                                    | 4         | 2.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 2.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.41%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 1.81%   |
| Intel HD Graphics 630                                                                    | 3         | 1.81%   |
| Intel HD Graphics 610                                                                    | 3         | 1.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.81%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 1.2%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.2%    |
| Matrox Electronics Systems G200eR2                                                       | 2         | 1.2%    |
| Intel UHD Graphics 620                                                                   | 2         | 1.2%    |
| Intel HD Graphics 5500                                                                   | 2         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.2%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 1.2%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.2%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.2%    |
| AMD Renoir                                                                               | 2         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.2%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.6%    |
| Nvidia GP107GLM [Quadro P620]                                                            | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 50%     |
| Intel + Nvidia | 19        | 13.19%  |
| 1 x Nvidia     | 15        | 10.42%  |
| 1 x AMD        | 14        | 9.72%   |
| Intel + AMD    | 6         | 4.17%   |
| 2 x Intel      | 5         | 3.47%   |
| 1 x Matrox     | 5         | 3.47%   |
| Other          | 4         | 2.78%   |
| 1 x ASPEED     | 3         | 2.08%   |
| 2 x AMD        | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 121       | 84.03%  |
| Proprietary | 15        | 10.42%  |
| Unknown     | 8         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 86.21%  |
| 0.01-0.5   | 6         | 4.14%   |
| 0.51-1.0   | 5         | 3.45%   |
| 7.01-8.0   | 3         | 2.07%   |
| 1.01-2.0   | 3         | 2.07%   |
| 5.01-6.0   | 1         | 0.69%   |
| 3.01-4.0   | 1         | 0.69%   |
| 8.01-16.0  | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 16.18%  |
| AU Optronics            | 8         | 11.76%  |
| Chimei Innolux          | 7         | 10.29%  |
| BOE                     | 7         | 10.29%  |
| Dell                    | 6         | 8.82%   |
| Lenovo                  | 4         | 5.88%   |
| AOC                     | 4         | 5.88%   |
| Samsung Electronics     | 2         | 2.94%   |
| Philips                 | 2         | 2.94%   |
| PANDA                   | 2         | 2.94%   |
| CSO                     | 2         | 2.94%   |
| Chi Mei Optoelectronics | 2         | 2.94%   |
| ZL_                     | 1         | 1.47%   |
| TMX                     | 1         | 1.47%   |
| Panasonic               | 1         | 1.47%   |
| Mi                      | 1         | 1.47%   |
| Haier                   | 1         | 1.47%   |
| GRR                     | 1         | 1.47%   |
| CND                     | 1         | 1.47%   |
| CAN                     | 1         | 1.47%   |
| BenQ                    | 1         | 1.47%   |
| Apple                   | 1         | 1.47%   |
| Acer                    | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch              | 2         | 2.94%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch              | 2         | 2.94%   |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch               | 1         | 1.47%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch | 1         | 1.47%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch | 1         | 1.47%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                | 1         | 1.47%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                    | 1         | 1.47%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.47%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                 | 1         | 1.47%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch         | 1         | 1.47%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch         | 1         | 1.47%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch         | 1         | 1.47%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 1.47%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch          | 1         | 1.47%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 1         | 1.47%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                | 1         | 1.47%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch             | 1         | 1.47%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                        | 1         | 1.47%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1         | 1.47%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 1         | 1.47%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                    | 1         | 1.47%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                    | 1         | 1.47%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                    | 1         | 1.47%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                   | 1         | 1.47%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                | 1         | 1.47%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                | 1         | 1.47%   |
| CND HDMI CND2510 2560x1080 680x290mm 29.1-inch                       | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch     | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch     | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN150D 1920x1080 340x190mm 15.3-inch     | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch      | 1         | 1.47%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch      | 1         | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 41.18%  |
| 1366x768 (WXGA)    | 19        | 27.94%  |
| 2560x1440 (QHD)    | 4         | 5.88%   |
| 1600x900 (HD+)     | 3         | 4.41%   |
| 1440x900 (WXGA+)   | 3         | 4.41%   |
| 3840x2160 (4K)     | 2         | 2.94%   |
| 2560x1600          | 2         | 2.94%   |
| 3200x2000          | 1         | 1.47%   |
| 2880x1800          | 1         | 1.47%   |
| 2880x1620          | 1         | 1.47%   |
| 2560x1080          | 1         | 1.47%   |
| 1920x1200 (WUXGA)  | 1         | 1.47%   |
| 1680x1050 (WSXGA+) | 1         | 1.47%   |
| 1280x1024 (SXGA)   | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 22        | 32.35%  |
| 15     | 19        | 27.94%  |
| 24     | 5         | 7.35%   |
| 27     | 4         | 5.88%   |
| 23     | 4         | 5.88%   |
| 19     | 3         | 4.41%   |
| 21     | 2         | 2.94%   |
| 12     | 2         | 2.94%   |
| 54     | 1         | 1.47%   |
| 29     | 1         | 1.47%   |
| 22     | 1         | 1.47%   |
| 18     | 1         | 1.47%   |
| 16     | 1         | 1.47%   |
| 14     | 1         | 1.47%   |
| 11     | 1         | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 52.94%  |
| 501-600     | 13        | 19.12%  |
| 201-300     | 9         | 13.24%  |
| 401-500     | 5         | 7.35%   |
| 351-400     | 3         | 4.41%   |
| 601-700     | 1         | 1.47%   |
| 1001-1500   | 1         | 1.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 83.58%  |
| 16/10 | 9         | 13.43%  |
| 5/4   | 1         | 1.49%   |
| 21/9  | 1         | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 20        | 29.41%  |
| 91-100         | 15        | 22.06%  |
| 201-250        | 12        | 17.65%  |
| 301-350        | 5         | 7.35%   |
| 151-200        | 4         | 5.88%   |
| 71-80          | 3         | 4.41%   |
| 101-110        | 3         | 4.41%   |
| 61-70          | 2         | 2.94%   |
| 111-120        | 2         | 2.94%   |
| More than 1000 | 1         | 1.47%   |
| 51-60          | 1         | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 23        | 33.82%  |
| 101-120 | 19        | 27.94%  |
| 51-100  | 17        | 25%     |
| 161-240 | 9         | 13.24%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 74        | 50.68%  |
| 1     | 71        | 48.63%  |
| 2     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 94        | 49.21%  |
| Realtek Semiconductor    | 65        | 34.03%  |
| Qualcomm Atheros         | 14        | 7.33%   |
| Broadcom                 | 13        | 6.81%   |
| Ralink Technology        | 1         | 0.52%   |
| Qualcomm                 | 1         | 0.52%   |
| Mellanox Technologies    | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| Edimax Technology        | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 22.32%  |
| Intel I211 Gigabit Network Connection                             | 16        | 6.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3%      |
| Intel I350 Gigabit Network Connection                             | 6         | 2.58%   |
| Intel 82583V Gigabit Network Connection                           | 6         | 2.58%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.15%   |
| Intel I210 Gigabit Network Connection                             | 5         | 2.15%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.72%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.29%   |
| Intel Wireless 8260                                               | 3         | 1.29%   |
| Intel Wireless 7260                                               | 3         | 1.29%   |
| Intel Wireless 3165                                               | 3         | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.86%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 0.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.86%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 60%     |
| Qualcomm Atheros      | 13        | 16.25%  |
| Realtek Semiconductor | 11        | 13.75%  |
| Broadcom              | 6         | 7.5%    |
| Ralink Technology     | 1         | 1.25%   |
| Edimax Technology     | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 5         | 6.17%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 6.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 4.94%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 4.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 4.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.7%    |
| Intel Wireless 8260                                               | 3         | 3.7%    |
| Intel Wireless 7260                                               | 3         | 3.7%    |
| Intel Wireless 3165                                               | 3         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.47%   |
| Intel Centrino Wireless-N 2200                                    | 2         | 2.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 2.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.23%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.23%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.23%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter   | 1         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.23%   |
| Intel Wireless-AC 9260                                            | 1         | 1.23%   |
| Intel Wireless 7265                                               | 1         | 1.23%   |
| Intel Wireless 3160                                               | 1         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.23%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.23%   |
| Intel Centrino WiMAX 6150                                         | 1         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.23%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU] | 1         | 1.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 64        | 46.04%  |
| Realtek Semiconductor    | 61        | 43.88%  |
| Broadcom                 | 8         | 5.76%   |
| Qualcomm Atheros         | 4         | 2.88%   |
| Qualcomm                 | 1         | 0.72%   |
| Marvell Technology Group | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 34.44%  |
| Intel I211 Gigabit Network Connection                             | 16        | 10.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.64%   |
| Intel I350 Gigabit Network Connection                             | 6         | 3.97%   |
| Intel 82583V Gigabit Network Connection                           | 6         | 3.97%   |
| Intel I210 Gigabit Network Connection                             | 5         | 3.31%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 3.31%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.32%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.32%   |
| Intel 82576 Gigabit Network Connection                            | 2         | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.66%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.66%   |
| Intel Ethernet Connection X553 1GbE                               | 1         | 0.66%   |
| Intel Ethernet Connection X552 10 GbE SFP+                        | 1         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.66%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.66%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.66%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 0.66%   |
| Intel 82575GB Gigabit Network Connection                          | 1         | 0.66%   |
| Intel 82575EB Gigabit Network Connection                          | 1         | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 130       | 62.8%   |
| WiFi     | 76        | 36.71%  |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 73.33%  |
| WiFi     | 44        | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 81        | 55.86%  |
| 1     | 27        | 18.62%  |
| 6     | 14        | 9.66%   |
| 4     | 12        | 8.28%   |
| 5     | 5         | 3.45%   |
| 8     | 2         | 1.38%   |
| 7     | 2         | 1.38%   |
| 0     | 2         | 1.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 124       | 84.35%  |
| Yes  | 23        | 15.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 61.02%  |
| Realtek Semiconductor           | 4         | 6.78%   |
| Broadcom                        | 4         | 6.78%   |
| Qualcomm Atheros Communications | 3         | 5.08%   |
| Cambridge Silicon Radio         | 3         | 5.08%   |
| Apple                           | 3         | 5.08%   |
| Lite-On Technology              | 2         | 3.39%   |
| Foxconn / Hon Hai               | 2         | 3.39%   |
| Realtek                         | 1         | 1.69%   |
| IMC Networks                    | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 16        | 27.12%  |
| Intel AX201 Bluetooth                                       | 6         | 10.17%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 8.47%   |
| Intel AX200 Bluetooth                                       | 5         | 8.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 6.78%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 5.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 5.08%   |
| Realtek  Bluetooth 4.0 Adapter                              | 2         | 3.39%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 3.39%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.69%   |
| Realtek Bluetooth Radio                                     | 1         | 1.69%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.69%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.69%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.69%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.69%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.69%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.69%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 1.69%   |
| Apple Bluetooth Host Controller                             | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 105       | 75%     |
| AMD                    | 18        | 12.86%  |
| Nvidia                 | 16        | 11.43%  |
| Generalplus Technology | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 8.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 7.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 5.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 3.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 2.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.53%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.9%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 1.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.27%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.27%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 27.38%  |
| SK hynix            | 28        | 16.67%  |
| Kingston            | 27        | 16.07%  |
| Micron Technology   | 17        | 10.12%  |
| Unknown             | 14        | 8.33%   |
| A-DATA Technology   | 7         | 4.17%   |
| Unknown             | 6         | 3.57%   |
| Ramaxel Technology  | 5         | 2.98%   |
| Nanya Technology    | 3         | 1.79%   |
| Transcend           | 2         | 1.19%   |
| Team                | 2         | 1.19%   |
| G.Skill             | 2         | 1.19%   |
| Elpida              | 2         | 1.19%   |
| Unknown (8AFD)      | 1         | 0.6%    |
| Unknown (08B5)      | 1         | 0.6%    |
| Ramsta              | 1         | 0.6%    |
| KingTiger           | 1         | 0.6%    |
| Innodisk            | 1         | 0.6%    |
| Crucial             | 1         | 0.6%    |
| Corsair             | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 6         | 3.35%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 5         | 2.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 2.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 3         | 1.68%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 3         | 1.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.12%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 1.12%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 1.12%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s        | 2         | 1.12%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 1.12%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s  | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                  | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                  | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1         | 0.56%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s       | 1         | 0.56%   |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s    | 1         | 0.56%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s | 1         | 0.56%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s          | 1         | 0.56%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.56%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.56%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.56%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM 1066MT/s             | 1         | 0.56%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 1         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 0.56%   |
| SK hynix RAM HMT125S6BFR8C-G7 2048MB SODIMM 800MT/s         | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 45.39%  |
| DDR3    | 64        | 45.39%  |
| DDR2    | 4         | 2.84%   |
| Unknown | 4         | 2.84%   |
| LPDDR4  | 3         | 2.13%   |
| LPDDR3  | 2         | 1.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 56.03%  |
| DIMM         | 49        | 34.75%  |
| Row Of Chips | 8         | 5.67%   |
| Unknown      | 3         | 2.13%   |
| RIMM         | 1         | 0.71%   |
| Chip         | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 54        | 34.39%  |
| 4096  | 54        | 34.39%  |
| 2048  | 27        | 17.2%   |
| 16384 | 18        | 11.46%  |
| 1024  | 3         | 1.91%   |
| 32768 | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 36        | 22.64%  |
| 1333    | 24        | 15.09%  |
| 2133    | 21        | 13.21%  |
| 2667    | 18        | 11.32%  |
| 2400    | 17        | 10.69%  |
| 3200    | 12        | 7.55%   |
| 800     | 7         | 4.4%    |
| 1334    | 6         | 3.77%   |
| 2666    | 4         | 2.52%   |
| 4267    | 2         | 1.26%   |
| 2933    | 2         | 1.26%   |
| 1867    | 2         | 1.26%   |
| 1067    | 2         | 1.26%   |
| 667     | 2         | 1.26%   |
| Unknown | 2         | 1.26%   |
| 1066    | 1         | 0.63%   |
| 533     | 1         | 0.63%   |

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
| Chicony Electronics                    | 15        | 27.78%  |
| Acer                                   | 8         | 14.81%  |
| Realtek Semiconductor                  | 6         | 11.11%  |
| Syntek                                 | 3         | 5.56%   |
| Microdia                               | 3         | 5.56%   |
| IMC Networks                           | 3         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 3.7%    |
| Quanta                                 | 2         | 3.7%    |
| Logitech                               | 2         | 3.7%    |
| Lite-On Technology                     | 2         | 3.7%    |
| Z-Star Microelectronics                | 1         | 1.85%   |
| Silicon Motion                         | 1         | 1.85%   |
| Lenovo                                 | 1         | 1.85%   |
| Importek                               | 1         | 1.85%   |
| Genesys Logic                          | 1         | 1.85%   |
| Foxconn / Hon Hai                      | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.85%   |
| ALi                                    | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 5         | 9.09%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 5.45%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 5.45%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 5.45%   |
| Acer Integrated Camera                                                     | 3         | 5.45%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 3.64%   |
| IMC Networks Integrated Camera                                             | 2         | 3.64%   |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 3.64%   |
| Chicony Chicony USB2.0 Camera                                              | 2         | 3.64%   |
| Acer ThinkPad Integrated Camera                                            | 2         | 3.64%   |
| Z-Star Lenovo USB2.0 UVC Camera                                            | 1         | 1.82%   |
| Syntek Integrated Camera                                                   | 1         | 1.82%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 1         | 1.82%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.82%   |
| Silicon Motion Realtek USB2.0 PC Camera                                    | 1         | 1.82%   |
| Realtek Realtek USB2.0 PC Camera                                           | 1         | 1.82%   |
| Realtek HD WebCam                                                          | 1         | 1.82%   |
| Realtek Front Camera                                                       | 1         | 1.82%   |
| Quanta Realtek DMFT - RGB                                                  | 1         | 1.82%   |
| Quanta ov9734_techfront_camera                                             | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.82%   |
| Microdia Camera                                                            | 1         | 1.82%   |
| Logitech Webcam C170                                                       | 1         | 1.82%   |
| Logitech C670i FHD Webcam                                                  | 1         | 1.82%   |
| Lite-On Integrated Camera                                                  | 1         | 1.82%   |
| Lite-On HP HD Camera                                                       | 1         | 1.82%   |
| Lenovo Integrated Webcam [R5U877]                                          | 1         | 1.82%   |
| Importek USB 2.0 Camera                                                    | 1         | 1.82%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.82%   |
| Genesys Logic Camera                                                       | 1         | 1.82%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 1.82%   |
| Chicony Integrated IR Camera                                               | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.82%   |
| ALi Gateway Webcam                                                         | 1         | 1.82%   |
| Acer Lenovo Integrated Webcam                                              | 1         | 1.82%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.82%   |
| Acer EasyCamera                                                            | 1         | 1.82%   |

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
| 1     | 50        | 34.48%  |
| 0     | 43        | 29.66%  |
| 2     | 32        | 22.07%  |
| 3     | 16        | 11.03%  |
| 4     | 4         | 2.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 93        | 56.71%  |
| Net/wireless             | 22        | 13.41%  |
| Bluetooth                | 18        | 10.98%  |
| Card reader              | 17        | 10.37%  |
| Fingerprint reader       | 10        | 6.1%    |
| Net/ethernet             | 2         | 1.22%   |
| Sound                    | 1         | 0.61%   |
| Network                  | 1         | 0.61%   |

