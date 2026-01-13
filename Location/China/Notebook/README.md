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

Total: 138

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0d4d6a5811](https://bsd-hardware.info/?probe=0d4d6a5811) | Dec 25, 2025 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [30220e13a3](https://bsd-hardware.info/?probe=30220e13a3) | Dec 20, 2025 |
| HUAWEI        | MRGFG-XX                    | [1d96ab83c2](https://bsd-hardware.info/?probe=1d96ab83c2) | Nov 30, 2025 |
| Dell          | Latitude E5470              | [a7cb7055f2](https://bsd-hardware.info/?probe=a7cb7055f2) | Nov 08, 2025 |
| Acidanther... | MacBookPro12,1              | [794c5d7f0a](https://bsd-hardware.info/?probe=794c5d7f0a) | Sep 02, 2025 |
| Lenovo        | Legion R7000 APH9 83EG      | [4cf383ef70](https://bsd-hardware.info/?probe=4cf383ef70) | Jul 01, 2025 |
| IPASON        | J115M                       | [50a1fff202](https://bsd-hardware.info/?probe=50a1fff202) | Jun 28, 2025 |
| IPASON        | J115M                       | [af32dd4cbb](https://bsd-hardware.info/?probe=af32dd4cbb) | Jun 27, 2025 |
| Lenovo        | Legion R7000 APH9 83EG      | [6ed522ac59](https://bsd-hardware.info/?probe=6ed522ac59) | Jun 26, 2025 |
| Lenovo        | Legion Y9000K 2021H 82K6    | [943c47444a](https://bsd-hardware.info/?probe=943c47444a) | Jun 12, 2025 |
| Google        | Atlas                       | [812b61c436](https://bsd-hardware.info/?probe=812b61c436) | May 20, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a63d7e5fbd](https://bsd-hardware.info/?probe=a63d7e5fbd) | May 14, 2025 |
| ASUSTek       | K84HR                       | [d153180727](https://bsd-hardware.info/?probe=d153180727) | May 11, 2025 |
| Lenovo        | ThinkPad X61s 76673EJ       | [cfe34864ff](https://bsd-hardware.info/?probe=cfe34864ff) | Apr 24, 2025 |
| Unknown       | Unknown                     | [348e031ae2](https://bsd-hardware.info/?probe=348e031ae2) | Feb 14, 2025 |
| Haier         | T6-C                        | [06b37e1a45](https://bsd-hardware.info/?probe=06b37e1a45) | Jan 26, 2025 |
| HUAWEI        | MRGFG-XX                    | [e23afd3be3](https://bsd-hardware.info/?probe=e23afd3be3) | Dec 29, 2024 |
| HUAWEI        | MRGFG-XX                    | [6095e2193f](https://bsd-hardware.info/?probe=6095e2193f) | Dec 29, 2024 |
| GPD           | MicroPC                     | [dac20acac9](https://bsd-hardware.info/?probe=dac20acac9) | Nov 22, 2024 |
| Lenovo        | ThinkPad T430 2344DUC       | [63d0cde972](https://bsd-hardware.info/?probe=63d0cde972) | Nov 19, 2024 |
| Samsung       | 535U3C                      | [615b4a9430](https://bsd-hardware.info/?probe=615b4a9430) | Nov 18, 2024 |
| HP            | ProBook 455 15.6 inch G9... | [e76040ded0](https://bsd-hardware.info/?probe=e76040ded0) | Oct 25, 2024 |
| Lenovo        | ThinkPad X250 20CLA455CD    | [875eeb5304](https://bsd-hardware.info/?probe=875eeb5304) | Oct 14, 2024 |
| Unknown       | Unknown                     | [a76921a478](https://bsd-hardware.info/?probe=a76921a478) | Sep 16, 2024 |
| Acer          | E5-572G-57VZ                | [f4c2bf9852](https://bsd-hardware.info/?probe=f4c2bf9852) | Jul 27, 2024 |
| ASUSTek       | X550CC                      | [edd7342aa3](https://bsd-hardware.info/?probe=edd7342aa3) | Jul 16, 2024 |
| Lenovo        | ThinkPad X250 20CLA455CD    | [8efeb91994](https://bsd-hardware.info/?probe=8efeb91994) | Jun 07, 2024 |
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


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| helloSystem 0.7.0      | 9         | 7.96%   |
| FreeBSD 13.1           | 9         | 7.96%   |
| helloSystem 0.8.0      | 8         | 7.08%   |
| helloSystem 0.8.1      | 7         | 6.19%   |
| helloSystem 0.5.0      | 5         | 4.42%   |
| FreeBSD 14.0-CURRENT   | 5         | 4.42%   |
| helloSystem 0.9.0      | 4         | 3.54%   |
| FreeBSD 14.2           | 4         | 3.54%   |
| FreeBSD 13.2           | 4         | 3.54%   |
| FreeBSD 12.2           | 4         | 3.54%   |
| helloSystem 0.6.0      | 3         | 2.65%   |
| helloSystem 0.4.0      | 3         | 2.65%   |
| FreeBSD 14.1           | 3         | 2.65%   |
| OPNsense 21.1.1        | 2         | 1.77%   |
| NomadBSD 5806f915      | 2         | 1.77%   |
| GhostBSD 21.08.27      | 2         | 1.77%   |
| FreeBSD 14.0           | 2         | 1.77%   |
| FreeBSD 13.0-p7        | 2         | 1.77%   |
| FreeBSD 13.0-p4        | 2         | 1.77%   |
| FreeBSD 13.0           | 2         | 1.77%   |
| OPNsense 25.1.1        | 1         | 0.88%   |
| OPNsense 24.7.4        | 1         | 0.88%   |
| OPNsense 22.7          | 1         | 0.88%   |
| OPNsense 21.1          | 1         | 0.88%   |
| OPNsense 20.7.8        | 1         | 0.88%   |
| OpenBSD 7.6            | 1         | 0.88%   |
| OpenBSD 7.3            | 1         | 0.88%   |
| OpenBSD 7.0            | 1         | 0.88%   |
| NomadBSD 1.3.1         | 1         | 0.88%   |
| NetBSD 9.3             | 1         | 0.88%   |
| GhostBSD 25.02-R14.3p4 | 1         | 0.88%   |
| FreeBSD 15.0-CURRENT   | 1         | 0.88%   |
| FreeBSD 15.0           | 1         | 0.88%   |
| FreeBSD 14.3           | 1         | 0.88%   |
| FreeBSD 14.2-BETA2     | 1         | 0.88%   |
| FreeBSD 14.1-p5        | 1         | 0.88%   |
| FreeBSD 14.0-p2        | 1         | 0.88%   |
| FreeBSD 14.0-BETA5     | 1         | 0.88%   |
| FreeBSD 13.5           | 1         | 0.88%   |
| FreeBSD 13.2-p10       | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 52        | 49.06%  |
| helloSystem | 37        | 34.91%  |
| OPNsense    | 6         | 5.66%   |
| OpenBSD     | 3         | 2.83%   |
| NomadBSD    | 3         | 2.83%   |
| GhostBSD    | 3         | 2.83%   |
| NetBSD      | 1         | 0.94%   |
| DragonFly   | 1         | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 38        | 33.93%  |
| XFCE          | 17        | 15.18%  |
| Console       | 15        | 13.39%  |
| KDE5          | 12        | 10.71%  |
| GNOME         | 7         | 6.25%   |
| TWM           | 4         | 3.57%   |
| MATE          | 4         | 3.57%   |
| i3            | 4         | 3.57%   |
| Openbox       | 3         | 2.68%   |
| Hyprland      | 3         | 2.68%   |
| AwesomeWM     | 2         | 1.79%   |
| GNOME Classic | 1         | 0.89%   |
| fvwm          | 1         | 0.89%   |
| DWM           | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 88        | 83.02%  |
| Console | 14        | 13.21%  |
| Wayland | 4         | 3.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 48        | 44.04%  |
| Console | 27        | 24.77%  |
| SDDM    | 11        | 10.09%  |
| LightDM | 11        | 10.09%  |
| GDM     | 7         | 6.42%   |
| XDM     | 3         | 2.75%   |
| Ly      | 2         | 1.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 30        | 26.79%  |
| C            | 28        | 25%     |
| zh_CN        | 27        | 24.11%  |
| Unknown      | 24        | 21.43%  |
| en           | 2         | 1.79%   |
| zh_CN.GB2312 | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 87.62%  |
| BIOS | 13        | 12.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 60        | 55.05%  |
| Ufs     | 29        | 26.61%  |
| Cd9660  | 16        | 14.68%  |
| Ffs     | 3         | 2.75%   |
| Hammer2 | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 98        | 93.33%  |
| MBR     | 6         | 5.71%   |
| Unknown | 1         | 0.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 37.5%   |
| Dell                | 9         | 8.65%   |
| ASUSTek Computer    | 8         | 7.69%   |
| Hewlett-Packard     | 7         | 6.73%   |
| Unknown             | 6         | 5.77%   |
| HUAWEI              | 4         | 3.85%   |
| Google              | 4         | 3.85%   |
| Notebook            | 3         | 2.88%   |
| Acer                | 3         | 2.88%   |
| Timi                | 2         | 1.92%   |
| Sony                | 2         | 1.92%   |
| Samsung Electronics | 2         | 1.92%   |
| Panasonic           | 2         | 1.92%   |
| MECHREVO S1 Series  | 2         | 1.92%   |
| HASEE Computer      | 2         | 1.92%   |
| WOOKING             | 1         | 0.96%   |
| Toshiba             | 1         | 0.96%   |
| NEC Computers       | 1         | 0.96%   |
| IPASON              | 1         | 0.96%   |
| Intel               | 1         | 0.96%   |
| Haier               | 1         | 0.96%   |
| GPD                 | 1         | 0.96%   |
| Apple               | 1         | 0.96%   |
| Acidanthera         | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 6.73%   |
| MECHREVO S1 Series S1 Series                | 2         | 1.92%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD  | 2         | 1.92%   |
| HUAWEI MRGFG-XX                             | 2         | 1.92%   |
| Google Kohaku                               | 2         | 1.92%   |
| WOOKING X5                                  | 1         | 0.96%   |
| Toshiba Satellite Pro L510                  | 1         | 0.96%   |
| Timi RedmiBook Pro 15                       | 1         | 0.96%   |
| Timi A34R                                   | 1         | 0.96%   |
| Sony SVS1511AJB                             | 1         | 0.96%   |
| Sony SVP13225SCBI                           | 1         | 0.96%   |
| Samsung 535U3C                              | 1         | 0.96%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV    | 1         | 0.96%   |
| Panasonic CF-NX1GDHYS                       | 1         | 0.96%   |
| Panasonic CF-B11JWCYS                       | 1         | 0.96%   |
| Notebook W65KJ1_KK1                         | 1         | 0.96%   |
| Notebook W650DC,DD                          | 1         | 0.96%   |
| Notebook N960Kx                             | 1         | 0.96%   |
| NEC Computers PC-VK17HBBCD                  | 1         | 0.96%   |
| Lenovo ZhaoYang K4e-IML 81VQ                | 1         | 0.96%   |
| Lenovo XiaoXinPro-13ARE 2020 82DM           | 1         | 0.96%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.96%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7         | 1         | 0.96%   |
| Lenovo ThinkPad X61s 76673EJ                | 1         | 0.96%   |
| Lenovo ThinkPad X270 20HNA04GCD             | 1         | 0.96%   |
| Lenovo ThinkPad X250 20CLA455CD             | 1         | 0.96%   |
| Lenovo ThinkPad X230 2324A14                | 1         | 0.96%   |
| Lenovo ThinkPad X230 23062S2                | 1         | 0.96%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TLA055CD | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002LUS    | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS1QC00    | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 3448AWU           | 1         | 0.96%   |
| Lenovo ThinkPad T580 20L9000ECD             | 1         | 0.96%   |
| Lenovo ThinkPad T480 20L5000UUS             | 1         | 0.96%   |
| Lenovo ThinkPad T470p 20J6A012CD            | 1         | 0.96%   |
| Lenovo ThinkPad T430 2349GCU                | 1         | 0.96%   |
| Lenovo ThinkPad T430 2344DUC                | 1         | 0.96%   |
| Lenovo ThinkPad T430 2342AG4                | 1         | 0.96%   |
| Lenovo ThinkPad SL410 28747GC               | 1         | 0.96%   |
| Lenovo ThinkPad R14 Gen 4 21E5A05RCD        | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 24        | 23.08%  |
| Unknown                    | 7         | 6.73%   |
| Dell Latitude              | 5         | 4.81%   |
| Lenovo Legion              | 3         | 2.88%   |
| HP ProBook                 | 3         | 2.88%   |
| MECHREVO S1 Series S1      | 2         | 1.92%   |
| Lenovo IdeaPad             | 2         | 1.92%   |
| HUAWEI MRGFG-XX            | 2         | 1.92%   |
| Google Kohaku              | 2         | 1.92%   |
| Dell Inspiron              | 2         | 1.92%   |
| ASUS ASUS                  | 2         | 1.92%   |
| WOOKING X5                 | 1         | 0.96%   |
| Toshiba Satellite          | 1         | 0.96%   |
| Timi RedmiBook             | 1         | 0.96%   |
| Timi A34R                  | 1         | 0.96%   |
| Sony SVS1511AJB            | 1         | 0.96%   |
| Sony SVP13225SCBI          | 1         | 0.96%   |
| Samsung 535U3C             | 1         | 0.96%   |
| Samsung 3570R              | 1         | 0.96%   |
| Panasonic CF-NX1GDHYS      | 1         | 0.96%   |
| Panasonic CF-B11JWCYS      | 1         | 0.96%   |
| Notebook W65KJ1            | 1         | 0.96%   |
| Notebook W650DC            | 1         | 0.96%   |
| Notebook N960Kx            | 1         | 0.96%   |
| NEC Computers PC-VK17HBBCD | 1         | 0.96%   |
| Lenovo ZhaoYang            | 1         | 0.96%   |
| Lenovo XiaoXinPro-13ARE    | 1         | 0.96%   |
| Lenovo XiaoXinPro-13API    | 1         | 0.96%   |
| Lenovo XiaoXinAir          | 1         | 0.96%   |
| Lenovo Rescuer-15ISK       | 1         | 0.96%   |
| Lenovo G480                | 1         | 0.96%   |
| Lenovo G470                | 1         | 0.96%   |
| Lenovo B590                | 1         | 0.96%   |
| Lenovo B470                | 1         | 0.96%   |
| Lenovo B41-80              | 1         | 0.96%   |
| IPASON MaxBook             | 1         | 0.96%   |
| Intel H81U                 | 1         | 0.96%   |
| HUAWEI NBLL-WXX9           | 1         | 0.96%   |
| HUAWEI HLY-WX9XX           | 1         | 0.96%   |
| HP Pavilion                | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 12        | 11.54%  |
| 2012 | 12        | 11.54%  |
| 2021 | 11        | 10.58%  |
| 2019 | 9         | 8.65%   |
| 2017 | 9         | 8.65%   |
| 2013 | 9         | 8.65%   |
| 2018 | 8         | 7.69%   |
| 2016 | 7         | 6.73%   |
| 2023 | 5         | 4.81%   |
| 2020 | 5         | 4.81%   |
| 2024 | 4         | 3.85%   |
| 2015 | 4         | 3.85%   |
| 2011 | 4         | 3.85%   |
| 2009 | 2         | 1.92%   |
| 2014 | 1         | 0.96%   |
| 2010 | 1         | 0.96%   |
| 2008 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 96.15%  |
| Yes  | 4         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 40        | 38.46%  |
| 4.01-8.0    | 25        | 24.04%  |
| 16.01-24.0  | 21        | 20.19%  |
| 32.01-64.0  | 9         | 8.65%   |
| 24.01-32.0  | 5         | 4.81%   |
| 64.01-256.0 | 2         | 1.92%   |
| 3.01-4.0    | 1         | 0.96%   |
| 2.01-3.0    | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 57        | 54.81%  |
| 0.51-1.0 | 23        | 22.12%  |
| 1.01-2.0 | 20        | 19.23%  |
| 2.01-3.0 | 3         | 2.88%   |
| Unknown  | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 60.19%  |
| 2      | 22        | 20.37%  |
| 0      | 18        | 16.67%  |
| 3      | 3         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 81.9%   |
| Yes       | 19        | 18.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 77.88%  |
| No        | 23        | 22.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 95.19%  |
| No        | 5         | 4.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 76.92%  |
| No        | 24        | 23.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| China   | 104       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Shanghai              | 10        | 9.17%   |
| Guangzhou             | 10        | 9.17%   |
| Hangzhou              | 8         | 7.34%   |
| Chengdu               | 7         | 6.42%   |
| Shenzhen              | 6         | 5.5%    |
| Beijing               | 6         | 5.5%    |
| Xi'an                 | 4         | 3.67%   |
| Wuhan                 | 3         | 2.75%   |
| Zhengzhou             | 2         | 1.83%   |
| Yuzhong Chengguanzhen | 2         | 1.83%   |
| Qiqihar               | 2         | 1.83%   |
| Nanjing               | 2         | 1.83%   |
| Foshan                | 2         | 1.83%   |
| Chongqing             | 2         | 1.83%   |
| Changzhou             | 2         | 1.83%   |
| Zibo                  | 1         | 0.92%   |
| Zhumadian             | 1         | 0.92%   |
| Zhaoqing              | 1         | 0.92%   |
| Zhangjiakou           | 1         | 0.92%   |
| Yichun                | 1         | 0.92%   |
| Xiamen                | 1         | 0.92%   |
| Wuxi                  | 1         | 0.92%   |
| Wenzhou               | 1         | 0.92%   |
| Weifang               | 1         | 0.92%   |
| Tangshan              | 1         | 0.92%   |
| Taizhou               | 1         | 0.92%   |
| Shizishan             | 1         | 0.92%   |
| Shantou               | 1         | 0.92%   |
| Qinnan                | 1         | 0.92%   |
| Qingdao               | 1         | 0.92%   |
| Putian                | 1         | 0.92%   |
| Pudong                | 1         | 0.92%   |
| Ningbo                | 1         | 0.92%   |
| Nanning               | 1         | 0.92%   |
| Muping                | 1         | 0.92%   |
| Liuxiang              | 1         | 0.92%   |
| Linyi                 | 1         | 0.92%   |
| Lanzhou               | 1         | 0.92%   |
| Jinniu                | 1         | 0.92%   |
| Jinan                 | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 22     | 18.18%  |
| WDC                 | 14        | 17     | 12.73%  |
| Seagate             | 10        | 12     | 9.09%   |
| Toshiba             | 7         | 8      | 6.36%   |
| HGST                | 4         | 4      | 3.64%   |
| Silicon Motion      | 3         | 3      | 2.73%   |
| SanDisk             | 3         | 3      | 2.73%   |
| Lenovo              | 3         | 3      | 2.73%   |
| Kingston            | 3         | 3      | 2.73%   |
| Intel               | 3         | 6      | 2.73%   |
| Hikvision           | 3         | 3      | 2.73%   |
| SK hynix            | 2         | 2      | 1.82%   |
| Plextor             | 2         | 3      | 1.82%   |
| Netac               | 2         | 2      | 1.82%   |
| KIOXIA              | 2         | 2      | 1.82%   |
| Hitachi             | 2         | 3      | 1.82%   |
| FORESEE             | 2         | 2      | 1.82%   |
| Crucial             | 2         | 2      | 1.82%   |
| China               | 2         | 3      | 1.82%   |
| Apple               | 2         | 2      | 1.82%   |
| UMIS                | 1         | 1      | 0.91%   |
| Topmore             | 1         | 1      | 0.91%   |
| Teclast             | 1         | 1      | 0.91%   |
| SSSTC               | 1         | 1      | 0.91%   |
| SemsoTai            | 1         | 1      | 0.91%   |
| Pioneer             | 1         | 1      | 0.91%   |
| Phison              | 1         | 1      | 0.91%   |
| Lexar               | 1         | 1      | 0.91%   |
| KIOXIA-EXCERIA      | 1         | 3      | 0.91%   |
| KingSpec            | 1         | 1      | 0.91%   |
| Hewlett-Packard     | 1         | 1      | 0.91%   |
| Getrich             | 1         | 1      | 0.91%   |
| faspeed             | 1         | 1      | 0.91%   |
| Fanxiang            | 1         | 2      | 0.91%   |
| CSD                 | 1         | 1      | 0.91%   |
| Colorful            | 1         | 1      | 0.91%   |
| BR                  | 1         | 1      | 0.91%   |
| BIWIN               | 1         | 1      | 0.91%   |
| A-DATA Technology   | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM048-2E7172 1TB          | 2         | 1.74%   |
| SanDisk SSD U100 24GB                   | 2         | 1.74%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 1.74%   |
| Samsung SSD 870 EVO 1TB                 | 2         | 1.74%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.74%   |
| Samsung SSD 850 EVO 120GB               | 2         | 1.74%   |
| Samsung MZVLB512HBJQ-000L2 512GB        | 2         | 1.74%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 2         | 1.74%   |
| Hikvision HS-SSD-C2000ECO 1024G         | 2         | 1.74%   |
| HGST HTS541010B7E610 1TB                | 2         | 1.74%   |
| FORESEE P900F256GB                      | 2         | 1.74%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.87%   |
| WDC WDS120G2G0A-00JH30 120GB            | 1         | 0.87%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.87%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 1         | 0.87%   |
| WDC WD5000LPCX-00VHAT0 500GB            | 1         | 0.87%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 0.87%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.87%   |
| WDC WD2500BEVS-08VAT2 250GB             | 1         | 0.87%   |
| WDC WD20SPZX-75UA7T0 2TB                | 1         | 0.87%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.87%   |
| WDC WD10JPVX-00JC3T0 1TB                | 1         | 0.87%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.87%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB    | 1         | 0.87%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 0.87%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.87%   |
| UMIS RPJYJ512MKN1QWQ 512GB              | 1         | 0.87%   |
| Toshiba THNSNK128GVN8 128GB             | 1         | 0.87%   |
| Toshiba THNSNF128GCSS 128GB             | 1         | 0.87%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 0.87%   |
| Toshiba MQ02ABF050H-SSHD-8GB            | 1         | 0.87%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.87%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.87%   |
| Toshiba KXG6APNV2T04 2TB                | 1         | 0.87%   |
| Topmore capricornus 2TB                 | 1         | 0.87%   |
| Teclast 256GB SSD                       | 1         | 0.87%   |
| SSSTC CL1-3D256 256GB                   | 1         | 0.87%   |
| SK hynix PC300 HFS512GD9MND-5510A 512GB | 1         | 0.87%   |
| SK hynix BC511 NVMe 512GB               | 1         | 0.87%   |
| Silicon Motion T70 2242 1TB             | 1         | 0.87%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 33.33%  |
| WDC     | 9         | 9      | 30%     |
| Toshiba | 4         | 4      | 13.33%  |
| HGST    | 4         | 4      | 13.33%  |
| Hitachi | 2         | 3      | 6.67%   |
| CSD     | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 11     | 22.92%  |
| Lenovo              | 3         | 3      | 6.25%   |
| Kingston            | 3         | 3      | 6.25%   |
| Intel               | 3         | 6      | 6.25%   |
| WDC                 | 2         | 2      | 4.17%   |
| Toshiba             | 2         | 2      | 4.17%   |
| SanDisk             | 2         | 2      | 4.17%   |
| Plextor             | 2         | 3      | 4.17%   |
| Netac               | 2         | 2      | 4.17%   |
| China               | 2         | 3      | 4.17%   |
| Apple               | 2         | 2      | 4.17%   |
| Teclast             | 1         | 1      | 2.08%   |
| SemsoTai            | 1         | 1      | 2.08%   |
| Phison              | 1         | 1      | 2.08%   |
| Lexar               | 1         | 1      | 2.08%   |
| KIOXIA-EXCERIA      | 1         | 3      | 2.08%   |
| KingSpec            | 1         | 1      | 2.08%   |
| Hewlett-Packard     | 1         | 1      | 2.08%   |
| Getrich             | 1         | 1      | 2.08%   |
| faspeed             | 1         | 1      | 2.08%   |
| Fanxiang            | 1         | 2      | 2.08%   |
| Crucial             | 1         | 1      | 2.08%   |
| BR                  | 1         | 1      | 2.08%   |
| BIWIN               | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 45        | 56     | 43.69%  |
| NVMe | 30        | 38     | 29.13%  |
| HDD  | 28        | 33     | 27.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 89     | 68.42%  |
| NVMe | 30        | 38     | 31.58%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 67     | 71.43%  |
| 0.51-1.0   | 17        | 19     | 24.29%  |
| 1.01-2.0   | 3         | 3      | 4.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 27        | 25%     |
| 251-500    | 26        | 24.07%  |
| 101-250    | 24        | 22.22%  |
| 501-1000   | 10        | 9.26%   |
| 51-100     | 8         | 7.41%   |
| 21-50      | 5         | 4.63%   |
| 1001-2000  | 5         | 4.63%   |
| Unknown    | 3         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 87        | 81.31%  |
| 21-50   | 9         | 8.41%   |
| 251-500 | 3         | 2.8%    |
| 51-100  | 3         | 2.8%    |
| Unknown | 3         | 2.8%    |
| 101-250 | 2         | 1.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB    | 1         | 1      | 10%     |
| WDC WD3200BPVT-22JJ5T0 320GB    | 1         | 1      | 10%     |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 10%     |
| Toshiba MQ02ABF050H-SSHD-8GB    | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 10%     |
| Seagate ST500LM021-1KJ152 500GB | 1         | 2      | 10%     |
| Seagate ST320LT007-9ZV142 320GB | 1         | 1      | 10%     |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 10%     |
| Fanxiang S101-240GB             | 1         | 1      | 10%     |
| China JWX 16GB MSATA            | 1         | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 3      | 30%     |
| Seagate  | 3         | 4      | 30%     |
| Toshiba  | 1         | 1      | 10%     |
| Hitachi  | 1         | 1      | 10%     |
| Fanxiang | 1         | 1      | 10%     |
| China    | 1         | 2      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 42.86%  |
| WDC     | 2         | 2      | 28.57%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 70%     |
| SSD  | 3         | 4      | 30%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| CSD T65SX160N 4H0204656BY 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| CSD    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 80        | 114    | 87.91%  |
| Malfunc | 10        | 12     | 10.99%  |
| Failed  | 1         | 1      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 72        | 55.81%  |
| Samsung Electronics                     | 14        | 10.85%  |
| Sandisk                                 | 11        | 8.53%   |
| Silicon Motion                          | 6         | 4.65%   |
| AMD                                     | 4         | 3.1%    |
| MAXIO Technology (Hangzhou)             | 3         | 2.33%   |
| INNOGRIT                                | 3         | 2.33%   |
| Toshiba                                 | 2         | 1.55%   |
| Solid State Storage Technology          | 2         | 1.55%   |
| SK hynix                                | 2         | 1.55%   |
| Shenzhen Unionmemory Information System | 2         | 1.55%   |
| Micron Technology                       | 2         | 1.55%   |
| Marvell Technology Group                | 2         | 1.55%   |
| KIOXIA                                  | 2         | 1.55%   |
| Shenzhen Longsys Electronics            | 1         | 0.78%   |
| Micron/Crucial Technology               | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                       | Notebooks | Percent |
|---------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                          | 15        | 11.19%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                            | 13        | 9.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                | 9         | 6.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                               | 7         | 5.22%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                        | 4         | 2.99%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                           | 3         | 2.24%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                | 3         | 2.24%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                    | 3         | 2.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                          | 3         | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]               | 3         | 2.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                       | 3         | 2.24%   |
| Intel Comet Lake SATA AHCI Controller                                                       | 3         | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                              | 3         | 2.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                | 3         | 2.24%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                              | 2         | 1.49%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                               | 2         | 1.49%   |
| Shenzhen Unionmemory Information System RPJYJ512MKN1QWQ PCIe 4.0 NVMe SSD 512GB (DRAM-less) | 2         | 1.49%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                   | 2         | 1.49%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                  | 2         | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                              | 2         | 1.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                 | 2         | 1.49%   |
| Micron 3400 NVMe SSD [Hendrix]                                                              | 2         | 1.49%   |
| Marvell Group 88NV1160 PCIe x2 NVMe SSD Controller (DRAM-less)                              | 2         | 1.49%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                  | 2         | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                           | 2         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                       | 2         | 1.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]              | 2         | 1.49%   |
| AMD FCH SATA Controller [AHCI mode]                                                         | 2         | 1.49%   |
| Toshiba XG6 NVMe SSD Controller                                                             | 1         | 0.75%   |
| Toshiba XG3 NVMe SSD Controller                                                             | 1         | 0.75%   |
| SK hynix PC300 NVMe Solid State Drive 512GB                                                 | 1         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                                     | 1         | 0.75%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                                      | 1         | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                                  | 1         | 0.75%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                                       | 1         | 0.75%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                       | 1         | 0.75%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                               | 1         | 0.75%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                    | 1         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                         | 1         | 0.75%   |
| Intel Tiger Lake SATA AHCI Controller                                                       | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 72        | 59.5%   |
| NVMe | 41        | 33.88%  |
| RAID | 4         | 3.31%   |
| IDE  | 4         | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 92        | 88.46%  |
| AMD    | 12        | 11.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 4.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 3.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.88%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 2.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.88%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.92%   |
| Intel 13th Gen Core i7-1360P                  | 2         | 1.92%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.92%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.92%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.96%   |
| Intel Pentium CPU G4600 @ 3.60GHz             | 1         | 0.96%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 0.96%   |
| Intel CPU Version                             | 1         | 0.96%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.96%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.96%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 0.96%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.96%   |
| Intel Core i7-2637M CPU                       | 1         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.96%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.96%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 38.46%  |
| Intel Core i7           | 16        | 15.38%  |
| Other                   | 14        | 13.46%  |
| Intel Core i3           | 9         | 8.65%   |
| Intel Celeron           | 7         | 6.73%   |
| AMD Ryzen 7             | 4         | 3.85%   |
| AMD Ryzen 5             | 4         | 3.85%   |
| Intel Pentium           | 2         | 1.92%   |
| Intel Core 2 Duo        | 2         | 1.92%   |
| Intel Xeon              | 1         | 0.96%   |
| Intel Core m3           | 1         | 0.96%   |
| Intel Celeron Dual-Core | 1         | 0.96%   |
| AMD Ryzen 9             | 1         | 0.96%   |
| AMD Ryzen 3             | 1         | 0.96%   |
| AMD A6                  | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 50%     |
| 4       | 30        | 28.85%  |
| 8       | 8         | 7.69%   |
| 6       | 5         | 4.81%   |
| 16      | 3         | 2.88%   |
| 10      | 2         | 1.92%   |
| Unknown | 2         | 1.92%   |
| 24      | 1         | 0.96%   |
| 12      | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 76        | 73.08%  |
| 1       | 26        | 25%     |
| Unknown | 2         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 24.04%  |
| IvyBridge     | 13        | 12.5%   |
| SandyBridge   | 11        | 10.58%  |
| Skylake       | 10        | 9.62%   |
| Unknown       | 9         | 8.65%   |
| TigerLake     | 6         | 5.77%   |
| Haswell       | 6         | 5.77%   |
| Broadwell     | 4         | 3.85%   |
| Zen 3         | 3         | 2.88%   |
| Zen 2         | 3         | 2.88%   |
| Penryn        | 3         | 2.88%   |
| CometLake     | 3         | 2.88%   |
| Zen+          | 2         | 1.92%   |
| Westmere      | 1         | 0.96%   |
| Silvermont    | 1         | 0.96%   |
| Piledriver    | 1         | 0.96%   |
| K10           | 1         | 0.96%   |
| Goldmont plus | 1         | 0.96%   |
| Core          | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 60.42%  |
| Nvidia | 36        | 25%     |
| AMD    | 21        | 14.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 13        | 8.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 6.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 4.14%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                 | 6         | 4.14%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                               | 6         | 4.14%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                              | 6         | 4.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 2.76%   |
| Nvidia GP108M [GeForce MX150]                                                         | 3         | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 3         | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 2.07%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                              | 3         | 2.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 3         | 2.07%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 3         | 2.07%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 3         | 2.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 3         | 2.07%   |
| Nvidia TU117M [GeForce MX450]                                                         | 2         | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.38%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 2         | 1.38%   |
| Nvidia GF108M [NVS 5400M]                                                             | 2         | 1.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 1.38%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 1.38%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                 | 2         | 1.38%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 2         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 1.38%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.69%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 0.69%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                 | 1         | 0.69%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.69%   |
| Nvidia GM108M [GeForce 940M]                                                          | 1         | 0.69%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 0.69%   |
| Nvidia GM108M [GeForce 920MX]                                                         | 1         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 0.69%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 0.69%   |
| Nvidia GK208M [GeForce GT 720M]                                                       | 1         | 0.69%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 45.19%  |
| Intel + Nvidia | 30        | 28.85%  |
| 1 x AMD        | 11        | 10.58%  |
| Intel + AMD    | 8         | 7.69%   |
| 1 x Nvidia     | 4         | 3.85%   |
| 2 x Intel      | 2         | 1.92%   |
| AMD + Nvidia   | 2         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 86.54%  |
| Proprietary | 10        | 9.62%   |
| Unknown     | 4         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 83.96%  |
| 0.01-0.5   | 7         | 6.6%    |
| 0.51-1.0   | 4         | 3.77%   |
| 7.01-8.0   | 3         | 2.83%   |
| 1.01-2.0   | 2         | 1.89%   |
| 8.01-16.0  | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 15.79%  |
| LG Display              | 11        | 14.47%  |
| Chimei Innolux          | 11        | 14.47%  |
| BOE                     | 11        | 14.47%  |
| Samsung Electronics     | 5         | 6.58%   |
| CSO                     | 4         | 5.26%   |
| Lenovo                  | 3         | 3.95%   |
| PANDA                   | 2         | 2.63%   |
| Dell                    | 2         | 2.63%   |
| Chi Mei Optoelectronics | 2         | 2.63%   |
| ViewSonic               | 1         | 1.32%   |
| TMX                     | 1         | 1.32%   |
| SKY                     | 1         | 1.32%   |
| Panasonic               | 1         | 1.32%   |
| LGD                     | 1         | 1.32%   |
| InfoVision              | 1         | 1.32%   |
| HPN                     | 1         | 1.32%   |
| HKC                     | 1         | 1.32%   |
| Hewlett-Packard         | 1         | 1.32%   |
| Daewoo                  | 1         | 1.32%   |
| CSOT                    | 1         | 1.32%   |
| Apple                   | 1         | 1.32%   |
| Unknown                 | 1         | 1.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch               | 2         | 2.63%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 2.63%   |
| ViewSonic VX2779-2K-PRO VSC6240 2560x1440 600x330mm 27.0-inch         | 1         | 1.32%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.32%   |
| SKY F24B40Q SKY0001 2560x1440 530x300mm 24.0-inch                     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 340x190mm 15.3-inch  | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SEC3246 1366x768 290x160mm 13.0-inch  | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 290x170mm 13.2-inch | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch  | 1         | 1.32%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 340x190mm 15.3-inch           | 1         | 1.32%   |
| LGD LCD Monitor 3840x1080                                             | 1         | 1.32%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch           | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 1         | 1.32%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch           | 1         | 1.32%   |
| HPN LCD Monitor OMEN 25i                                              | 1         | 1.32%   |
| HKC V2718W HKC2729 1920x1080 600x330mm 27.0-inch                      | 1         | 1.32%   |
| Hewlett-Packard LCD Monitor Inc. OMEN 25i                             | 1         | 1.32%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                     | 1         | 1.32%   |
| Dell SE2018HV DELF09B 1600x900 430x240mm 19.4-inch                    | 1         | 1.32%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                     | 1         | 1.32%   |
| CSOT LCD Monitor CSO1415 3120x2080 300x200mm 14.2-inch                | 1         | 1.32%   |
| CSO LCD Monitor CSO1415 3120x2080 300x200mm 14.2-inch                 | 1         | 1.32%   |
| CSO LCD Monitor CSO1408 3120x2080 300x200mm 14.2-inch                 | 1         | 1.32%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                 | 1         | 1.32%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                 | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 360x200mm 16.2-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1602 1920x1080 360x200mm 16.2-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch       | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch      | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 28        | 38.36%  |
| 1366x768 (WXGA)   | 22        | 30.14%  |
| 1600x900 (HD+)    | 5         | 6.85%   |
| 2560x1440 (QHD)   | 4         | 5.48%   |
| 3120x2080         | 3         | 4.11%   |
| 3840x2160 (4K)    | 2         | 2.74%   |
| 2560x1600         | 2         | 2.74%   |
| 3840x1080         | 1         | 1.37%   |
| 3200x2000         | 1         | 1.37%   |
| 2880x1800         | 1         | 1.37%   |
| 2240x1400         | 1         | 1.37%   |
| 1920x1200 (WUXGA) | 1         | 1.37%   |
| 1280x1024 (SXGA)  | 1         | 1.37%   |
| Unknown           | 1         | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 29        | 39.73%  |
| 15      | 24        | 32.88%  |
| 14      | 5         | 6.85%   |
| 12      | 4         | 5.48%   |
| 27      | 2         | 2.74%   |
| 24      | 2         | 2.74%   |
| 16      | 2         | 2.74%   |
| 23      | 1         | 1.37%   |
| 21      | 1         | 1.37%   |
| 19      | 1         | 1.37%   |
| 17      | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 63.01%  |
| 201-300     | 16        | 21.92%  |
| 501-600     | 5         | 6.85%   |
| 351-400     | 3         | 4.11%   |
| 401-500     | 2         | 2.74%   |
| Unknown     | 1         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 85.71%  |
| 16/10   | 6         | 8.57%   |
| 3/2     | 3         | 4.29%   |
| Unknown | 1         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 26        | 35.62%  |
| 91-100         | 23        | 31.51%  |
| 71-80          | 5         | 6.85%   |
| 61-70          | 4         | 5.48%   |
| 201-250        | 3         | 4.11%   |
| 111-120        | 3         | 4.11%   |
| 101-110        | 3         | 4.11%   |
| 301-350        | 2         | 2.74%   |
| 151-200        | 2         | 2.74%   |
| 121-130        | 1         | 1.37%   |
| Unknown        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 47.22%  |
| 101-120       | 17        | 23.61%  |
| 161-240       | 9         | 12.5%   |
| 51-100        | 6         | 8.33%   |
| More than 240 | 5         | 6.94%   |
| Unknown       | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 76        | 71.03%  |
| 0     | 27        | 25.23%  |
| 2     | 4         | 3.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 47.06%  |
| Realtek Semiconductor | 49        | 32.03%  |
| Qualcomm Atheros      | 19        | 12.42%  |
| Broadcom              | 7         | 4.58%   |
| Qualcomm Technologies | 2         | 1.31%   |
| Qualcomm              | 1         | 0.65%   |
| OPPO Electronics      | 1         | 0.65%   |
| MediaTek              | 1         | 0.65%   |
| Edimax Technology     | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37        | 19.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 3.17%   |
| Intel Wireless 8265 / 8275                                             | 6         | 3.17%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 2.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 5         | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 2.12%   |
| Intel Wireless 8260                                                    | 4         | 2.12%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 2.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.59%   |
| Intel Wireless 7265                                                    | 3         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.59%   |
| Intel 82583V Gigabit Network Connection                                | 3         | 1.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 1.06%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 2         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.06%   |
| Intel Wireless 7260                                                    | 2         | 1.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.06%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.06%   |
| Intel Centrino Wireless-N 2200                                         | 2         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 2         | 1.06%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 2         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.53%   |
| Qualcomm FP3                                                           | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 63.11%  |
| Qualcomm Atheros      | 17        | 16.5%   |
| Realtek Semiconductor | 11        | 10.68%  |
| Broadcom              | 6         | 5.83%   |
| Qualcomm Technologies | 2         | 1.94%   |
| MediaTek              | 1         | 0.97%   |
| Edimax Technology     | 1         | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 6         | 5.71%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 5.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 5         | 4.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 5         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 5         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 3.81%   |
| Intel Wireless 8260                                                  | 4         | 3.81%   |
| Intel Wi-Fi 6 AX200                                                  | 4         | 3.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 3.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 2.86%   |
| Intel Wireless 7265                                                  | 3         | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 2.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2         | 1.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2         | 1.9%    |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 1.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 1.9%    |
| Intel Wireless 7260                                                  | 2         | 1.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.9%    |
| Intel Centrino Wireless-N 2200                                       | 2         | 1.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 2         | 1.9%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 2         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 1         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 0.95%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1         | 0.95%   |
| Intel Wireless 3165                                                  | 1         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 0.95%   |
| Intel Jasper Lake PCH CNVi WiFi                                      | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 43        | 51.81%  |
| Intel                 | 31        | 37.35%  |
| Qualcomm Atheros      | 5         | 6.02%   |
| Broadcom              | 2         | 2.41%   |
| Qualcomm              | 1         | 1.2%    |
| OPPO Electronics      | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 37        | 44.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 7.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.57%   |
| Intel 82583V Gigabit Network Connection                                | 3         | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 2.38%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.38%   |
| Qualcomm FP3                                                           | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.19%   |
| OPPO OPPO Find X3 Neo 5G RNDIS Control RNDIS Ethernet Data             | 1         | 1.19%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.19%   |
| Intel Ethernet Controller I226-V                                       | 1         | 1.19%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.19%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 1.19%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.19%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1.19%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.19%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1         | 1.19%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.19%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 55%     |
| Ethernet | 81        | 45%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 50.42%  |
| Ethernet | 59        | 49.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 71.15%  |
| 1     | 24        | 23.08%  |
| 6     | 4         | 3.85%   |
| 8     | 1         | 0.96%   |
| 3     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 93.33%  |
| Yes  | 7         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 61.73%  |
| Broadcom                        | 8         | 9.88%   |
| Foxconn / Hon Hai               | 5         | 6.17%   |
| Qualcomm Atheros Communications | 4         | 4.94%   |
| Lite-On Technology              | 4         | 4.94%   |
| Apple                           | 3         | 3.7%    |
| Realtek Semiconductor           | 2         | 2.47%   |
| Cambridge Silicon Radio         | 2         | 2.47%   |
| Skylight Digital                | 1         | 1.23%   |
| IMC Networks                    | 1         | 1.23%   |
| Alps Electric                   | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 19        | 23.17%  |
| Intel AX201 Bluetooth                                | 14        | 17.07%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 6         | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 5         | 6.1%    |
| Intel Wireless-AC 3168 Bluetooth                     | 4         | 4.88%   |
| Intel AX200 Bluetooth                                | 4         | 4.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 3         | 3.66%   |
| Apple Bluetooth Host Controller                      | 3         | 3.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 2         | 2.44%   |
| Intel AX211 Bluetooth                                | 2         | 2.44%   |
| Foxconn / Hon Hai Qualcomm WCN685x Bluetooth Adapter | 2         | 2.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 2         | 2.44%   |
| Skylight Digital Realtek Bluetooth Adapter           | 1         | 1.22%   |
| Realtek Bluetooth Adapter                            | 1         | 1.22%   |
| Realtek Bluetooth 4.0 Adapter                        | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE  | 1         | 1.22%   |
| Lite-On Realtek Bluetooth Adapter                    | 1         | 1.22%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS          | 1         | 1.22%   |
| Lite-On BCM43142A0 Bluetooth Module                  | 1         | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                     | 1         | 1.22%   |
| Intel AX210 Bluetooth                                | 1         | 1.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS     | 1         | 1.22%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 1         | 1.22%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device      | 1         | 1.22%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth           | 1         | 1.22%   |
| Broadcom BCM20702 Bluetooth 4.0 USB Device           | 1         | 1.22%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]     | 1         | 1.22%   |
| Alps Electric UGTZ4 Bluetooth                        | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 89        | 78.07%  |
| AMD              | 13        | 11.4%   |
| Nvidia           | 11        | 9.65%   |
| ASUSTek Computer | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 14.29%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 10.53%  |
| AMD Ryzen HD Audio Controller                                                                     | 9         | 6.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 6.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 4.51%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 6         | 4.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 3.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.01%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 3.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 3.01%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 2.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.5%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.5%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.5%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.75%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 0.75%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.75%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.75%   |
| ASUSTek Computer C-Media CM6549 Extension                                                         | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 41        | 33.06%  |
| SK hynix             | 25        | 20.16%  |
| Micron Technology    | 13        | 10.48%  |
| Kingston             | 12        | 9.68%   |
| Ramaxel Technology   | 5         | 4.03%   |
| Unknown              | 5         | 4.03%   |
| Unknown              | 4         | 3.23%   |
| Elpida               | 3         | 2.42%   |
| Crucial              | 3         | 2.42%   |
| Transcend            | 2         | 1.61%   |
| A-DATA Technology    | 2         | 1.61%   |
| Unknown (ABCD)       | 1         | 0.81%   |
| Unknown (8AFD)       | 1         | 0.81%   |
| Unknown (08B5)       | 1         | 0.81%   |
| Team                 | 1         | 0.81%   |
| SemsoTai             | 1         | 0.81%   |
| Nanya Technology     | 1         | 0.81%   |
| Lenovo               | 1         | 0.81%   |
| KingTiger            | 1         | 0.81%   |
| Guangzhou MiaoYuanJi | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 3.7%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 4         | 2.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 2.96%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 4         | 2.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.22%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 2.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.48%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 2         | 1.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.48%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 1.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.48%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.48%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 1.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s         | 1         | 0.74%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s      | 1         | 0.74%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.74%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s           | 1         | 0.74%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 0.74%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1066MT/s           | 1         | 0.74%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s            | 1         | 0.74%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 42.72%  |
| DDR3    | 40        | 38.83%  |
| LPDDR3  | 6         | 5.83%   |
| LPDDR4  | 5         | 4.85%   |
| DDR5    | 3         | 2.91%   |
| LPDDR5  | 2         | 1.94%   |
| Unknown | 2         | 1.94%   |
| DDR2    | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 81.19%  |
| Row Of Chips | 16        | 15.84%  |
| Unknown      | 2         | 1.98%   |
| Chip         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 37.29%  |
| 4096  | 39        | 33.05%  |
| 2048  | 16        | 13.56%  |
| 16384 | 13        | 11.02%  |
| 32768 | 3         | 2.54%   |
| 1024  | 2         | 1.69%   |
| 6144  | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 21.93%  |
| 3200    | 16        | 14.04%  |
| 2667    | 14        | 12.28%  |
| 2400    | 12        | 10.53%  |
| 1333    | 11        | 9.65%   |
| 2133    | 10        | 8.77%   |
| 1334    | 4         | 3.51%   |
| 4267    | 3         | 2.63%   |
| 1867    | 3         | 2.63%   |
| 1067    | 3         | 2.63%   |
| 6400    | 2         | 1.75%   |
| 800     | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |
| 5600    | 1         | 0.88%   |
| 5200    | 1         | 0.88%   |
| 4800    | 1         | 0.88%   |
| 3733    | 1         | 0.88%   |
| 1066    | 1         | 0.88%   |
| 667     | 1         | 0.88%   |
| 533     | 1         | 0.88%   |

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
| Chicony Electronics                    | 27        | 32.93%  |
| Bison Electronics                      | 14        | 17.07%  |
| Realtek Semiconductor                  | 7         | 8.54%   |
| Sunplus Innovation Technology          | 6         | 7.32%   |
| IMC Networks                           | 4         | 4.88%   |
| Unknown (3730304233343731345430)       | 3         | 3.66%   |
| Syntek                                 | 3         | 3.66%   |
| Luxvisions Innotech Limited            | 3         | 3.66%   |
| Silicon Motion                         | 2         | 2.44%   |
| Quanta                                 | 2         | 2.44%   |
| Microdia                               | 2         | 2.44%   |
| Lite-On Technology                     | 2         | 2.44%   |
| Supreme Electronics                    | 1         | 1.22%   |
| Lenovo                                 | 1         | 1.22%   |
| Importek                               | 1         | 1.22%   |
| Genesys Logic                          | 1         | 1.22%   |
| Foxconn / Hon Hai                      | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.22%   |
| ALi                                    | 1         | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 9         | 10.47%  |
| Bison Integrated Camera                              | 5         | 5.81%   |
| Unknown (3730304233343731345430) USB Camera          | 3         | 3.49%   |
| Realtek Integrated_Webcam_HD                         | 3         | 3.49%   |
| Chicony USB2.0 VGA UVC WebCam                        | 3         | 3.49%   |
| Chicony Lenovo EasyCamera                            | 3         | 3.49%   |
| Bison ThinkPad Integrated Camera                     | 3         | 3.49%   |
| Syntek Lenovo EasyCamera                             | 2         | 2.33%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 2         | 2.33%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.33%   |
| Silicon Motion Realtek USB 2.0 PC Camera             | 2         | 2.33%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.33%   |
| IMC Networks Integrated Camera                       | 2         | 2.33%   |
| Chicony Realtek DMFT RGB                             | 2         | 2.33%   |
| Chicony Integrated IR Camera                         | 2         | 2.33%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 2.33%   |
| Chicony HD WebCam                                    | 2         | 2.33%   |
| Chicony 8M Camera                                    | 2         | 2.33%   |
| Chicony 720p HD Camera                               | 2         | 2.33%   |
| Bison Lenovo Integrated Webcam                       | 2         | 2.33%   |
| Bison Lenovo EasyCamera                              | 2         | 2.33%   |
| Syntek Integrated Camera                             | 1         | 1.16%   |
| Supreme Realtek PC Camera                            | 1         | 1.16%   |
| Sunplus MTD camera                                   | 1         | 1.16%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.16%   |
| Realtek USB 2.0 PC Camera                            | 1         | 1.16%   |
| Realtek Integrated Webcam                            | 1         | 1.16%   |
| Realtek HD WebCam                                    | 1         | 1.16%   |
| Realtek Front Camera                                 | 1         | 1.16%   |
| Quanta Realtek DMFT RGB                              | 1         | 1.16%   |
| Quanta ov9734_techfront_camera                       | 1         | 1.16%   |
| Microdia Laptop_Integrated_Webcam_0.3M               | 1         | 1.16%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.16%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.16%   |
| Lite-On Integrated Camera                            | 1         | 1.16%   |
| Lite-On HP HD Camera                                 | 1         | 1.16%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.16%   |
| Importek USB 2.0 Camera                              | 1         | 1.16%   |
| IMC Networks Realtek PC Camera                       | 1         | 1.16%   |
| IMC Networks Integrated Webcam                       | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 50%     |
| Synaptics                  | 5         | 27.78%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| Upek                       | 1         | 5.56%   |
| Fingerprint Cards          | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                            | 4         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 11.11%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 5.56%   |
| Fingerprint Cards FPC Fingerprint Reader                                   | 1         | 5.56%   |

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
| 2     | 32        | 30.48%  |
| 1     | 32        | 30.48%  |
| 3     | 24        | 22.86%  |
| 0     | 10        | 9.52%   |
| 4     | 6         | 5.71%   |
| 5     | 1         | 0.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 84        | 46.41%  |
| Bluetooth                | 32        | 17.68%  |
| Net/wireless             | 23        | 12.71%  |
| Card reader              | 20        | 11.05%  |
| Fingerprint reader       | 18        | 9.94%   |
| Sound                    | 4         | 2.21%   |

