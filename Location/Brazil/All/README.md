BSD in Brazil - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 304

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [dbeaf80924](https://bsd-hardware.info/?probe=dbeaf80924) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [764a816130](https://bsd-hardware.info/?probe=764a816130) | Oct 21, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [09bca1b1ff](https://bsd-hardware.info/?probe=09bca1b1ff) | Oct 20, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Dell          | 0W0W22 A08                  | Server      | [4d371914ed](https://bsd-hardware.info/?probe=4d371914ed) | Sep 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [05e28da420](https://bsd-hardware.info/?probe=05e28da420) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [5ee5edb1d0](https://bsd-hardware.info/?probe=5ee5edb1d0) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [f3c4668e00](https://bsd-hardware.info/?probe=f3c4668e00) | Aug 16, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [ad01fbd5a3](https://bsd-hardware.info/?probe=ad01fbd5a3) | Aug 03, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [c0e6b1eb61](https://bsd-hardware.info/?probe=c0e6b1eb61) | Aug 03, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | Notebook    | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| Positivo      | POS-EINM70CS SIM            | Desktop     | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e503017a9f](https://bsd-hardware.info/?probe=e503017a9f) | Jul 21, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [2f163e2a05](https://bsd-hardware.info/?probe=2f163e2a05) | Jul 21, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [f88fa027ab](https://bsd-hardware.info/?probe=f88fa027ab) | Jul 19, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Gigabyte      | C847N                       | Desktop     | [4be8944950](https://bsd-hardware.info/?probe=4be8944950) | Jul 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [87d68034db](https://bsd-hardware.info/?probe=87d68034db) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | Notebook    | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [a464043744](https://bsd-hardware.info/?probe=a464043744) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [bba161b618](https://bsd-hardware.info/?probe=bba161b618) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7be45ccc7e](https://bsd-hardware.info/?probe=7be45ccc7e) | Jun 08, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | Desktop     | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| Gateway       | NE56R                       | Notebook    | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8460816b1f](https://bsd-hardware.info/?probe=8460816b1f) | Mar 13, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Acer          | Aspire E1-421               | Notebook    | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [8b51036856](https://bsd-hardware.info/?probe=8b51036856) | Mar 06, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| HP            | 83E1                        | Desktop     | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5606f6d091](https://bsd-hardware.info/?probe=5606f6d091) | Feb 05, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a07a15f667](https://bsd-hardware.info/?probe=a07a15f667) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | Desktop     | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Gateway       | NE56R                       | Notebook    | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Sony          | VPCYB45JB                   | Notebook    | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | Desktop     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73076dd5de](https://bsd-hardware.info/?probe=73076dd5de) | Dec 21, 2021 |
| Samsung       | 530XBB                      | Notebook    | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [ad308cc715](https://bsd-hardware.info/?probe=ad308cc715) | Dec 08, 2021 |
| Philco        | 10B                         | Notebook    | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | Notebook    | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [df981410a9](https://bsd-hardware.info/?probe=df981410a9) | Dec 04, 2021 |
| Samsung       | 530XBB                      | Notebook    | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | Desktop     | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| HP            | 14                          | Notebook    | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Unknown       | X79                         | Desktop     | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [2781b31f9b](https://bsd-hardware.info/?probe=2781b31f9b) | Oct 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [20f9d1c3f0](https://bsd-hardware.info/?probe=20f9d1c3f0) | Oct 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [88d44cfe0c](https://bsd-hardware.info/?probe=88d44cfe0c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| Dell          | Latitude 5490               | Notebook    | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | Desktop     | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | Desktop     | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| Avell High... | A60 MUV                     | Notebook    | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | Desktop     | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [a40a382f62](https://bsd-hardware.info/?probe=a40a382f62) | Aug 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f43771bc21](https://bsd-hardware.info/?probe=f43771bc21) | Aug 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | Desktop     | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Yanling       | NS-1U8L                     | Desktop     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [98cefddb1b](https://bsd-hardware.info/?probe=98cefddb1b) | Jul 17, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a857cdfd42](https://bsd-hardware.info/?probe=a857cdfd42) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f6d72c011d](https://bsd-hardware.info/?probe=f6d72c011d) | Jul 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7623c94ba1](https://bsd-hardware.info/?probe=7623c94ba1) | Jun 25, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | Desktop     | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Gateway       | NE56R                       | Notebook    | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| Gateway       | NE56R                       | Notebook    | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | Notebook    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | 0C7TDG A03                  | Server      | [25e20c3f35](https://bsd-hardware.info/?probe=25e20c3f35) | May 19, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [0d13ec7ac2](https://bsd-hardware.info/?probe=0d13ec7ac2) | May 17, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [a5c5f7dba6](https://bsd-hardware.info/?probe=a5c5f7dba6) | May 12, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| AMI           | Aptio CRB 11                | Mini pc     | [e75df3aaa4](https://bsd-hardware.info/?probe=e75df3aaa4) | Apr 20, 2021 |
| Gateway       | NE56R                       | Notebook    | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | Notebook    | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | Desktop     | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | Desktop     | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | Desktop     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | Desktop     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| Avell High... | A62                         | Notebook    | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| ECS           | H55H-CM                     | Desktop     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | Desktop     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4b65be31e6](https://bsd-hardware.info/?probe=4b65be31e6) | Mar 11, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3bdcd1ac80](https://bsd-hardware.info/?probe=3bdcd1ac80) | Mar 05, 2021 |
| ASRock        | 970A-G                      | Desktop     | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Dell          | 0H5FVJ A01                  | Server      | [efe3dbf989](https://bsd-hardware.info/?probe=efe3dbf989) | Mar 03, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| Dell          | 0DFXXD A00                  | Server      | [deb86bda7b](https://bsd-hardware.info/?probe=deb86bda7b) | Feb 26, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| MSI           | E350IS-E45                  | Desktop     | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | Desktop     | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | Notebook    | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | Notebook    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c9a8d5ade5](https://bsd-hardware.info/?probe=c9a8d5ade5) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | Desktop     | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [5b163eb70f](https://bsd-hardware.info/?probe=5b163eb70f) | Feb 19, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [724e753eb9](https://bsd-hardware.info/?probe=724e753eb9) | Feb 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | Notebook    | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Clevo         | C41X0                       | Notebook    | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| Dell          | 07N90W A02                  | Desktop     | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | Desktop     | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| Unknown       | Unknown                     | Notebook    | [6953b9a9e4](https://bsd-hardware.info/?probe=6953b9a9e4) | Nov 22, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Dell          | Latitude 3490               | Notebook    | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [b8fdb26064](https://bsd-hardware.info/?probe=b8fdb26064) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [33266821d4](https://bsd-hardware.info/?probe=33266821d4) | Sep 01, 2020 |
| Lenovo        | ThinkPad T490 20N30029BR    | Notebook    | [41dbfb6fdc](https://bsd-hardware.info/?probe=41dbfb6fdc) | Aug 06, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | Desktop     | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1b84bffd9b](https://bsd-hardware.info/?probe=1b84bffd9b) | Jul 24, 2020 |
| Sony          | VPCEG17FB                   | Notebook    | [7d48bd3606](https://bsd-hardware.info/?probe=7d48bd3606) | Jul 13, 2020 |
| Lenovo        | ThinkPad X250 20CLS18S0Z    | Notebook    | [f668ce4e5b](https://bsd-hardware.info/?probe=f668ce4e5b) | Jul 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [245d470945](https://bsd-hardware.info/?probe=245d470945) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [5e50c0fa57](https://bsd-hardware.info/?probe=5e50c0fa57) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 25        | 10.33%  |
| helloSystem 0.4.0    | 15        | 6.2%    |
| helloSystem 0.6.0    | 14        | 5.79%   |
| helloSystem 0.5.0    | 14        | 5.79%   |
| FreeBSD 13.0         | 8         | 3.31%   |
| OPNsense 22.1.10     | 7         | 2.89%   |
| helloSystem 0.8.0    | 7         | 2.89%   |
| OPNsense 22.7.4      | 6         | 2.48%   |
| OPNsense 21.1.3      | 6         | 2.48%   |
| OPNsense 21.1        | 6         | 2.48%   |
| OPNsense 20.7.8      | 6         | 2.48%   |
| FreeBSD 14.0-CURRENT | 6         | 2.48%   |
| OPNsense 22.7.8      | 5         | 2.07%   |
| OPNsense 22.7.5      | 5         | 2.07%   |
| OPNsense 21.1.2      | 5         | 2.07%   |
| OPNsense 21.1.1      | 5         | 2.07%   |
| OPNsense 22.7.6      | 4         | 1.65%   |
| OPNsense 22.1.8      | 4         | 1.65%   |
| FreeBSD 13.0-p3      | 4         | 1.65%   |
| FreeBSD 12.1         | 4         | 1.65%   |
| OPNsense 21.7.7      | 3         | 1.24%   |
| OPNsense 21.7.1      | 3         | 1.24%   |
| OPNsense 21.1.9      | 3         | 1.24%   |
| OPNsense 21.1.7      | 3         | 1.24%   |
| OPNsense 21.1.6      | 3         | 1.24%   |
| OPNsense 21.1.4      | 3         | 1.24%   |
| FreeBSD 13.0-p7      | 3         | 1.24%   |
| FreeBSD 13.0-p4      | 3         | 1.24%   |
| TrueNAS 12.2-p9      | 2         | 0.83%   |
| OPNsense 22.7.9      | 2         | 0.83%   |
| OPNsense 22.1.7      | 2         | 0.83%   |
| OPNsense 22.1        | 2         | 0.83%   |
| OPNsense 21.1.8      | 2         | 0.83%   |
| OPNsense 21.1.5      | 2         | 0.83%   |
| NomadBSD 5806f915    | 2         | 0.83%   |
| FreeNAS 11.3-p9      | 2         | 0.83%   |
| FreeBSD 13.0-STABLE  | 2         | 0.83%   |
| FreeBSD 13.0-CURRENT | 2         | 0.83%   |
| FreeBSD 12.2-p3      | 2         | 0.83%   |
| FreeBSD 12.2         | 2         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 73        | 35.78%  |
| helloSystem | 70        | 34.31%  |
| FreeBSD     | 44        | 21.57%  |
| OpenBSD     | 4         | 1.96%   |
| GhostBSD    | 3         | 1.47%   |
| TrueNAS     | 2         | 0.98%   |
| NomadBSD    | 2         | 0.98%   |
| FreeNAS     | 2         | 0.98%   |
| pfSense     | 1         | 0.49%   |
| OS108       | 1         | 0.49%   |
| NetBSD      | 1         | 0.49%   |
| DragonFly   | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 197       | 98.99%  |
| i386  | 2         | 1.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 82        | 40.39%  |
| helloDesktop | 71        | 34.98%  |
| KDE5         | 12        | 5.91%   |
| XFCE         | 11        | 5.42%   |
| MATE         | 6         | 2.96%   |
| Openbox      | 5         | 2.46%   |
| GNOME        | 5         | 2.46%   |
| TWM          | 3         | 1.48%   |
| i3           | 2         | 0.99%   |
| fvwm         | 2         | 0.99%   |
| Window Maker | 1         | 0.49%   |
| spectrwm     | 1         | 0.49%   |
| LXQt         | 1         | 0.49%   |
| AwesomeWM    | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 116       | 58.29%  |
| Console | 83        | 41.71%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 96        | 47.52%  |
| SLiM    | 78        | 38.61%  |
| SDDM    | 11        | 5.45%   |
| LightDM | 8         | 3.96%   |
| GDM     | 5         | 2.48%   |
| XDM     | 4         | 1.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 87        | 42.86%  |
| en_US           | 77        | 37.93%  |
| C               | 19        | 9.36%   |
| pt_BR           | 17        | 8.37%   |
| fr_FR           | 1         | 0.49%   |
| en_US.ISO8859-1 | 1         | 0.49%   |
| en_GB           | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 167       | 81.86%  |
| BIOS | 37        | 18.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 96        | 46.6%   |
| Ufs     | 87        | 42.23%  |
| Cd9660  | 18        | 8.74%   |
| Ffs     | 4         | 1.94%   |
| Hammer2 | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 185       | 91.13%  |
| MBR     | 15        | 7.39%   |
| Unknown | 3         | 1.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 38        | 19.1%   |
| ASUSTek Computer        | 29        | 14.57%  |
| Lenovo                  | 20        | 10.05%  |
| Hewlett-Packard         | 11        | 5.53%   |
| Intel                   | 10        | 5.03%   |
| Acer                    | 10        | 5.03%   |
| Gigabyte Technology     | 7         | 3.52%   |
| Unknown                 | 7         | 3.52%   |
| Samsung Electronics     | 6         | 3.02%   |
| AMI                     | 6         | 3.02%   |
| ASRock                  | 5         | 2.51%   |
| Positivo                | 4         | 2.01%   |
| Itautec                 | 4         | 2.01%   |
| Apple                   | 4         | 2.01%   |
| Pegatron                | 3         | 1.51%   |
| PCWare                  | 3         | 1.51%   |
| MSI                     | 3         | 1.51%   |
| Avell High Performance  | 3         | 1.51%   |
| Techvision              | 2         | 1.01%   |
| Sony                    | 2         | 1.01%   |
| Semp Toshiba            | 2         | 1.01%   |
| Gateway                 | 2         | 1.01%   |
| ECS                     | 2         | 1.01%   |
| Yanling                 | 1         | 0.5%    |
| ULTRATOP                | 1         | 0.5%    |
| Supermicro              | 1         | 0.5%    |
| Procomp Ind. Eletronica | 1         | 0.5%    |
| Philco                  | 1         | 0.5%    |
| Notebook                | 1         | 0.5%    |
| maiyunda                | 1         | 0.5%    |
| LG Electronics          | 1         | 0.5%    |
| KLLISRE                 | 1         | 0.5%    |
| HC                      | 1         | 0.5%    |
| GALAX                   | 1         | 0.5%    |
| ECS-USA                 | 1         | 0.5%    |
| CNCTION-IAF-E3845       | 1         | 0.5%    |
| Clevo                   | 1         | 0.5%    |
| Biostar                 | 1         | 0.5%    |
| Acidanthera             | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 4.02%   |
| Intel Q3XXG4-P V1.0                         | 6         | 3.02%   |
| AMI Aptio CRB                               | 5         | 2.51%   |
| Dell Inspiron 3442                          | 4         | 2.01%   |
| ASUS All Series                             | 4         | 2.01%   |
| Techvision TVI7309X                         | 2         | 1.01%   |
| Samsung 340XAA/350XAA/550XAA                | 2         | 1.01%   |
| Pegatron IPM41-D3                           | 2         | 1.01%   |
| Gigabyte H61M-S2-B3                         | 2         | 1.01%   |
| Gateway NE56R                               | 2         | 1.01%   |
| Dell PowerEdge R620                         | 2         | 1.01%   |
| Dell Inspiron 3421                          | 2         | 1.01%   |
| ASUS PRIME B450M-GAMING/BR                  | 2         | 1.01%   |
| ASUS P8H61-M LX3 PLUS R2.0                  | 2         | 1.01%   |
| ASUS M5A78L-M LX/BR                         | 2         | 1.01%   |
| Acer Aspire 5750                            | 2         | 1.01%   |
| Yanling NS-1U8L                             | 1         | 0.5%    |
| ULTRATOP C2017-LIVA-ZE                      | 1         | 0.5%    |
| Supermicro NSMPX-17500                      | 1         | 0.5%    |
| Sony VPCYB45JB                              | 1         | 0.5%    |
| Sony VPCEG17FB                              | 1         | 0.5%    |
| Semp Toshiba STI NA 1401                    | 1         | 0.5%    |
| Semp Toshiba STI                            | 1         | 0.5%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.5%    |
| Samsung 530XBB                              | 1         | 0.5%    |
| Samsung 300E5M/300E5L                       | 1         | 0.5%    |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 0.5%    |
| Procomp Ind. Eletronica G41MXE              | 1         | 0.5%    |
| Positivo POS-PIQ77CL                        | 1         | 0.5%    |
| Positivo POS-EINM70CS                       | 1         | 0.5%    |
| Positivo POS-EAA75DE                        | 1         | 0.5%    |
| Positivo C14CR01                            | 1         | 0.5%    |
| Philco 10B                                  | 1         | 0.5%    |
| Pegatron IPMIP-GS                           | 1         | 0.5%    |
| PCWare PW-945GCX                            | 1         | 0.5%    |
| PCWare IPX1800G2                            | 1         | 0.5%    |
| PCWare IPMH81G1                             | 1         | 0.5%    |
| Notebook N85_N87HCHNHZ                      | 1         | 0.5%    |
| MSI U-100                                   | 1         | 0.5%    |
| MSI MS-7877                                 | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 15        | 7.54%   |
| Lenovo ThinkPad                | 12        | 6.03%   |
| Dell PowerEdge                 | 9         | 4.52%   |
| Acer Aspire                    | 9         | 4.52%   |
| Unknown                        | 8         | 4.02%   |
| Intel Q3XXG4-P                 | 6         | 3.02%   |
| Dell OptiPlex                  | 6         | 3.02%   |
| AMI Aptio                      | 6         | 3.02%   |
| HP ProLiant                    | 5         | 2.51%   |
| Dell Vostro                    | 5         | 2.51%   |
| Lenovo IdeaPad                 | 4         | 2.01%   |
| Itautec Infoway                | 4         | 2.01%   |
| ASUS All                       | 4         | 2.01%   |
| ASUS PRIME                     | 3         | 1.51%   |
| ASUS P8H61-M                   | 3         | 1.51%   |
| ASUS M5A78L-M                  | 3         | 1.51%   |
| Techvision TVI7309X            | 2         | 1.01%   |
| Semp Toshiba STI               | 2         | 1.01%   |
| Samsung 340XAA                 | 2         | 1.01%   |
| Pegatron IPM41-D3              | 2         | 1.01%   |
| Gigabyte H61M-S2-B3            | 2         | 1.01%   |
| Gateway NE56R                  | 2         | 1.01%   |
| Dell Latitude                  | 2         | 1.01%   |
| Avell High Performance A62     | 2         | 1.01%   |
| Yanling NS-1U8L                | 1         | 0.5%    |
| ULTRATOP C2017-LIVA-ZE         | 1         | 0.5%    |
| Supermicro NSMPX-17500         | 1         | 0.5%    |
| Sony VPCYB45JB                 | 1         | 0.5%    |
| Sony VPCEG17FB                 | 1         | 0.5%    |
| Samsung RV411                  | 1         | 0.5%    |
| Samsung 530XBB                 | 1         | 0.5%    |
| Samsung 300E5M                 | 1         | 0.5%    |
| Samsung 270E5K                 | 1         | 0.5%    |
| Procomp Ind. Eletronica G41MXE | 1         | 0.5%    |
| Positivo POS-PIQ77CL           | 1         | 0.5%    |
| Positivo POS-EINM70CS          | 1         | 0.5%    |
| Positivo POS-EAA75DE           | 1         | 0.5%    |
| Positivo C14CR01               | 1         | 0.5%    |
| Philco 10B                     | 1         | 0.5%    |
| Pegatron IPMIP-GS              | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 25        | 12.56%  |
| 2018    | 20        | 10.05%  |
| 2016    | 20        | 10.05%  |
| 2020    | 15        | 7.54%   |
| 2019    | 15        | 7.54%   |
| 2011    | 15        | 7.54%   |
| 2010    | 13        | 6.53%   |
| 2014    | 11        | 5.53%   |
| 2012    | 10        | 5.03%   |
| 2009    | 10        | 5.03%   |
| 2017    | 9         | 4.52%   |
| 2015    | 9         | 4.52%   |
| 2008    | 8         | 4.02%   |
| 2021    | 7         | 3.52%   |
| 2022    | 6         | 3.02%   |
| 2007    | 4         | 2.01%   |
| Unknown | 2         | 1.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 102       | 51.26%  |
| Notebook    | 73        | 36.68%  |
| Server      | 12        | 6.03%   |
| Mini pc     | 7         | 3.52%   |
| All in one  | 3         | 1.51%   |
| Convertible | 2         | 1.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 199       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 78        | 38.42%  |
| 4.01-8.0    | 71        | 34.98%  |
| 16.01-24.0  | 32        | 15.76%  |
| 2.01-3.0    | 9         | 4.43%   |
| 32.01-64.0  | 7         | 3.45%   |
| 3.01-4.0    | 2         | 0.99%   |
| 24.01-32.0  | 2         | 0.99%   |
| 64.01-256.0 | 2         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 128       | 63.05%  |
| 0.51-1.0   | 56        | 27.59%  |
| 1.01-2.0   | 10        | 4.93%   |
| 4.01-8.0   | 2         | 0.99%   |
| 2.01-3.0   | 2         | 0.99%   |
| Unknown    | 2         | 0.99%   |
| 32.01-64.0 | 1         | 0.49%   |
| 24.01-32.0 | 1         | 0.49%   |
| 16.01-24.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 66.67%  |
| 2      | 34        | 16.67%  |
| 0      | 19        | 9.31%   |
| 3      | 8         | 3.92%   |
| 5      | 3         | 1.47%   |
| 4      | 2         | 0.98%   |
| 7      | 1         | 0.49%   |
| 6      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 68.84%  |
| Yes       | 62        | 31.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 94.97%  |
| No        | 10        | 5.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 54.77%  |
| Yes       | 90        | 45.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 68.84%  |
| Yes       | 62        | 31.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 199       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| SГЈo Paulo              | 19        | 8.56%   |
| Rio de Janeiro            | 14        | 6.31%   |
| Curitiba                  | 11        | 4.95%   |
| Sao Paulo                 | 9         | 4.05%   |
| SÃ£o Paulo              | 6         | 2.7%    |
| Belo Horizonte            | 6         | 2.7%    |
| Sao José dos Campos      | 5         | 2.25%   |
| Manaus                    | 4         | 1.8%    |
| Campinas                  | 4         | 1.8%    |
| SГЈo JosГ© dos Campos | 3         | 1.35%   |
| Porto Alegre              | 3         | 1.35%   |
| JoГЈo Pessoa            | 3         | 1.35%   |
| Teresina                  | 2         | 0.9%    |
| Taubate                   | 2         | 0.9%    |
| Serra                     | 2         | 0.9%    |
| Sao Vicente               | 2         | 0.9%    |
| RondonГіpolis           | 2         | 0.9%    |
| Rio das Ostras            | 2         | 0.9%    |
| Rio Claro                 | 2         | 0.9%    |
| Pirapora                  | 2         | 0.9%    |
| Novo Hamburgo             | 2         | 0.9%    |
| Maraba                    | 2         | 0.9%    |
| Londrina                  | 2         | 0.9%    |
| Ipojuca                   | 2         | 0.9%    |
| Franca                    | 2         | 0.9%    |
| Florianópolis            | 2         | 0.9%    |
| CuiabГЎ                 | 2         | 0.9%    |
| Cabo de Santo Agostinho   | 2         | 0.9%    |
| BrasГ­lia               | 2         | 0.9%    |
| Brasília                 | 2         | 0.9%    |
| BrasÃ­lia               | 2         | 0.9%    |
| Boa Vista do Jauato       | 2         | 0.9%    |
| VitГіria da Conquista   | 1         | 0.45%   |
| VitГіria                | 1         | 0.45%   |
| Visconde do Rio Branco    | 1         | 0.45%   |
| Urupes                    | 1         | 0.45%   |
| Unai                      | 1         | 0.45%   |
| Uberaba                   | 1         | 0.45%   |
| Toledo                    | 1         | 0.45%   |
| Timbo                     | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 54     | 18.93%  |
| Seagate             | 37        | 90     | 15.23%  |
| Kingston            | 35        | 49     | 14.4%   |
| Samsung Electronics | 25        | 27     | 10.29%  |
| Toshiba             | 16        | 16     | 6.58%   |
| SanDisk             | 14        | 15     | 5.76%   |
| Crucial             | 9         | 12     | 3.7%    |
| A-DATA Technology   | 9         | 9      | 3.7%    |
| Silicon Motion      | 5         | 6      | 2.06%   |
| KingSpec            | 5         | 5      | 2.06%   |
| Hoodisk             | 5         | 5      | 2.06%   |
| China               | 5         | 8      | 2.06%   |
| LITEON              | 4         | 4      | 1.65%   |
| Hitachi             | 4         | 8      | 1.65%   |
| SK hynix            | 3         | 3      | 1.23%   |
| XrayDisk            | 2         | 2      | 0.82%   |
| SSSTC               | 2         | 2      | 0.82%   |
| Netac               | 2         | 2      | 0.82%   |
| Hewlett-Packard     | 2         | 3      | 0.82%   |
| Transcend           | 1         | 2      | 0.41%   |
| Smart               | 1         | 1      | 0.41%   |
| Silicon             | 1         | 1      | 0.41%   |
| Phison              | 1         | 1      | 0.41%   |
| Patriot             | 1         | 4      | 0.41%   |
| NVMe                | 1         | 1      | 0.41%   |
| NTC                 | 1         | 1      | 0.41%   |
| Kston               | 1         | 1      | 0.41%   |
| Hikvision           | 1         | 1      | 0.41%   |
| HGST                | 1         | 2      | 0.41%   |
| Gigabyte Technology | 1         | 1      | 0.41%   |
| Faspeed             | 1         | 1      | 0.41%   |
| Drevo               | 1         | 4      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 10        | 3.82%   |
| Kingston SA400S37120G 120GB         | 8         | 3.05%   |
| SanDisk SSD PLUS 120GB              | 6         | 2.29%   |
| Toshiba MQ01ABD100 1TB              | 4         | 1.53%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.53%   |
| Seagate ST500DM002-1BD142 500GB     | 4         | 1.53%   |
| Samsung HD502HJ 500GB               | 4         | 1.53%   |
| Kingston SA400S37480G 480GB         | 4         | 1.53%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3         | 1.15%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.15%   |
| SanDisk SDSSDA240G 240GB            | 3         | 1.15%   |
| Samsung HD322HJ 320GB               | 3         | 1.15%   |
| Kingston SUV400S37120G 120GB        | 3         | 1.15%   |
| Kingston SA400S37960G 960GB         | 3         | 1.15%   |
| Hoodisk SSD 64GB                    | 3         | 1.15%   |
| A-DATA SU630 240GB                  | 3         | 1.15%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.76%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2         | 0.76%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2         | 0.76%   |
| Silicon Motion NE-256 256GB         | 2         | 0.76%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 0.76%   |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.76%   |
| SanDisk SDSSDA120G 120GB            | 2         | 0.76%   |
| Samsung HM321HI 320GB               | 2         | 0.76%   |
| Samsung HM320II 320GB               | 2         | 0.76%   |
| Samsung HD161HJ 160GB               | 2         | 0.76%   |
| Samsung HD103SJ 1TB                 | 2         | 0.76%   |
| Samsung HD081GJ 80GB                | 2         | 0.76%   |
| KingSpec MT-128 128GB               | 2         | 0.76%   |
| Hoodisk SSD 32GB                    | 2         | 0.76%   |
| Crucial CT120BX500SSD1 120GB        | 2         | 0.76%   |
| China SATA SSD 120GB                | 2         | 0.76%   |
| XrayDisk SSD 240GB                  | 1         | 0.38%   |
| XrayDisk SSD 128GB                  | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 0.38%   |
| WDC WD800JD-75MSA3 80GB             | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 42        | 49     | 35%     |
| Seagate             | 37        | 90     | 30.83%  |
| Samsung Electronics | 19        | 21     | 15.83%  |
| Toshiba             | 15        | 15     | 12.5%   |
| Hitachi             | 4         | 8      | 3.33%   |
| Hewlett-Packard     | 2         | 3      | 1.67%   |
| HGST                | 1         | 2      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 48     | 32.38%  |
| SanDisk             | 14        | 15     | 13.33%  |
| Crucial             | 8         | 11     | 7.62%   |
| WDC                 | 5         | 5      | 4.76%   |
| Samsung Electronics | 5         | 5      | 4.76%   |
| KingSpec            | 5         | 5      | 4.76%   |
| Hoodisk             | 5         | 5      | 4.76%   |
| China               | 5         | 8      | 4.76%   |
| A-DATA Technology   | 5         | 5      | 4.76%   |
| LITEON              | 4         | 4      | 3.81%   |
| XrayDisk            | 2         | 2      | 1.9%    |
| SK hynix            | 2         | 2      | 1.9%    |
| Transcend           | 1         | 2      | 0.95%   |
| Smart               | 1         | 1      | 0.95%   |
| Silicon             | 1         | 1      | 0.95%   |
| Patriot             | 1         | 4      | 0.95%   |
| NTC                 | 1         | 1      | 0.95%   |
| Netac               | 1         | 1      | 0.95%   |
| Kston               | 1         | 1      | 0.95%   |
| Hikvision           | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Faspeed             | 1         | 1      | 0.95%   |
| Drevo               | 1         | 4      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 102       | 188    | 47.44%  |
| SSD  | 94        | 133    | 43.72%  |
| NVMe | 19        | 20     | 8.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 321    | 89.67%  |
| NVMe | 19        | 20     | 10.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 143       | 219    | 74.48%  |
| 0.51-1.0   | 38        | 54     | 19.79%  |
| 1.01-2.0   | 7         | 16     | 3.65%   |
| 3.01-4.0   | 4         | 32     | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 25.23%  |
| 1-20           | 51        | 23.83%  |
| 251-500        | 40        | 18.69%  |
| 51-100         | 24        | 11.21%  |
| 21-50          | 20        | 9.35%   |
| 501-1000       | 16        | 7.48%   |
| 1001-2000      | 5         | 2.34%   |
| 2001-3000      | 2         | 0.93%   |
| More than 3000 | 1         | 0.47%   |
| Unknown        | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 173       | 86.5%   |
| 21-50     | 14        | 7%      |
| 101-250   | 5         | 2.5%    |
| 501-1000  | 4         | 2%      |
| 51-100    | 2         | 1%      |
| 2001-3000 | 1         | 0.5%    |
| Unknown   | 1         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3         | 3      | 4.35%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 2      | 2.9%    |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 2.9%    |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 2.9%    |
| Samsung Electronics HD502HJ 500GB   | 2         | 2      | 2.9%    |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 2.9%    |
| XrayDisk SSD 240GB                  | 1         | 1      | 1.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.45%   |
| WDC WD5000B 500GB                   | 1         | 1      | 1.45%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 1      | 1.45%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 1      | 1.45%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 1      | 1.45%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.45%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 1.45%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 1.45%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 1.45%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 1.45%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1         | 1      | 1.45%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 1.45%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 1.45%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 1.45%   |
| Transcend TS32GMSM610 32GB          | 1         | 2      | 1.45%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.45%   |
| Toshiba MK6034GSX 64GB              | 1         | 1      | 1.45%   |
| Toshiba MK5076GSX 500GB             | 1         | 1      | 1.45%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.45%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 1.45%   |
| Toshiba MK1255GSX H 120GB           | 1         | 1      | 1.45%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 1.45%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 1.45%   |
| Seagate ST9320325ASG 320GB          | 1         | 2      | 1.45%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.45%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 1.45%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.45%   |
| Seagate ST9120821AS 118GB           | 1         | 1      | 1.45%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.45%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.45%   |
| Seagate ST500DM002-1BC142 500GB     | 1         | 1      | 1.45%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 28     | 28.79%  |
| WDC                 | 14        | 16     | 21.21%  |
| Samsung Electronics | 11        | 12     | 16.67%  |
| Toshiba             | 9         | 9      | 13.64%  |
| Hitachi             | 4         | 8      | 6.06%   |
| Kingston            | 2         | 2      | 3.03%   |
| XrayDisk            | 1         | 1      | 1.52%   |
| Transcend           | 1         | 2      | 1.52%   |
| SK hynix            | 1         | 1      | 1.52%   |
| SanDisk             | 1         | 1      | 1.52%   |
| Netac               | 1         | 1      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| KingSpec            | 1         | 1      | 1.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 28     | 33.33%  |
| WDC                 | 14        | 16     | 24.56%  |
| Samsung Electronics | 11        | 12     | 19.3%   |
| Toshiba             | 9         | 9      | 15.79%  |
| Hitachi             | 4         | 8      | 7.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 73     | 85%     |
| SSD  | 9         | 10     | 15%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 145       | 250    | 69.38%  |
| Malfunc  | 58        | 83     | 27.75%  |
| Detected | 5         | 7      | 2.39%   |
| Failed   | 1         | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 167       | 73.89%  |
| AMD                            | 24        | 10.62%  |
| Silicon Motion                 | 7         | 3.1%    |
| Broadcom / LSI                 | 6         | 2.65%   |
| Nvidia                         | 4         | 1.77%   |
| ADATA Technology               | 4         | 1.77%   |
| Solid State Storage Technology | 2         | 0.88%   |
| Toshiba                        | 1         | 0.44%   |
| SK hynix                       | 1         | 0.44%   |
| Samsung Electronics            | 1         | 0.44%   |
| Realtek Semiconductor          | 1         | 0.44%   |
| Phison Electronics             | 1         | 0.44%   |
| Micron/Crucial Technology      | 1         | 0.44%   |
| Kingston Technology Company    | 1         | 0.44%   |
| JMicron Technology             | 1         | 0.44%   |
| Integrated Technology Express  | 1         | 0.44%   |
| Hewlett-Packard                | 1         | 0.44%   |
| ASMedia Technology             | 1         | 0.44%   |
| Adaptec                        | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18        | 6.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 4.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 4.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11        | 4.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 4.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11        | 4.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 3.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 3.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 3.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7         | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 2.26%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.51%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.13%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.13%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                               | 3         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.13%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 3         | 1.13%   |
| Unknown                                                                                 | 3         | 1.13%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.75%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.75%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.75%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 146       | 63.76%  |
| IDE  | 47        | 20.52%  |
| NVMe | 20        | 8.73%   |
| RAID | 15        | 6.55%   |
| SCSI | 1         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 173       | 86.5%   |
| AMD    | 27        | 13.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 5         | 2.49%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4         | 1.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.49%   |
| Intel Celeron N5105 @ 2.00GHz               | 3         | 1.49%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3         | 1.49%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 1%      |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 2         | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1%      |
| Intel CPU Version                           | 2         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1%      |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1%      |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 1%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1%      |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1%      |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1%      |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 1%      |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1%      |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 1%      |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1%      |
| Intel Core i3-2100 CPU                      | 2         | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1%      |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2         | 1%      |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 1%      |
| Intel Core 2 Duo CPU                        | 2         | 1%      |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1%      |
| AMD FX-8320E Eight-Core Processor           | 2         | 1%      |
| Intel Xeon E-2224 CPU @ 3.40GHz             | 1         | 0.5%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.5%    |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1         | 0.5%    |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.5%    |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.5%    |
| Intel Xeon CPU E5310 @ 1.60GHz              | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 41        | 20.5%   |
| Intel Core i3           | 29        | 14.5%   |
| Intel Celeron           | 24        | 12%     |
| Intel Core i7           | 19        | 9.5%    |
| Intel Xeon              | 18        | 9%      |
| Intel Core 2 Duo        | 14        | 7%      |
| AMD FX                  | 7         | 3.5%    |
| Intel Pentium Dual-Core | 6         | 3%      |
| Intel Pentium           | 6         | 3%      |
| Intel Atom              | 5         | 2.5%    |
| AMD Ryzen 5             | 5         | 2.5%    |
| Other                   | 4         | 2%      |
| Intel Core 2 Quad       | 3         | 1.5%    |
| AMD E                   | 2         | 1%      |
| Intel Pentium M         | 1         | 0.5%    |
| Intel Pentium Dual      | 1         | 0.5%    |
| Intel Genuine           | 1         | 0.5%    |
| Intel Core M            | 1         | 0.5%    |
| Intel Core 2            | 1         | 0.5%    |
| AMD Turion II Neo       | 1         | 0.5%    |
| AMD Ryzen 7             | 1         | 0.5%    |
| AMD Ryzen 5 PRO         | 1         | 0.5%    |
| AMD Ryzen 3             | 1         | 0.5%    |
| AMD PRO A8              | 1         | 0.5%    |
| AMD Phenom              | 1         | 0.5%    |
| AMD E1                  | 1         | 0.5%    |
| AMD C-60                | 1         | 0.5%    |
| AMD C-50                | 1         | 0.5%    |
| AMD Athlon II X2        | 1         | 0.5%    |
| AMD Athlon              | 1         | 0.5%    |
| AMD A10                 | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 102       | 50.75%  |
| 4       | 57        | 28.36%  |
| 8       | 16        | 7.96%   |
| Unknown | 10        | 4.98%   |
| 6       | 9         | 4.48%   |
| 12      | 4         | 1.99%   |
| 1       | 2         | 1%      |
| 16      | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 191       | 95.98%  |
| 2      | 8         | 4.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 103       | 51.5%   |
| 2       | 87        | 43.5%   |
| Unknown | 10        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 13.93%  |
| Penryn        | 22        | 10.95%  |
| SandyBridge   | 21        | 10.45%  |
| IvyBridge     | 19        | 9.45%   |
| Haswell       | 19        | 9.45%   |
| Silvermont    | 12        | 5.97%   |
| Broadwell     | 10        | 4.98%   |
| Westmere      | 8         | 3.98%   |
| Core          | 8         | 3.98%   |
| Zen+          | 7         | 3.48%   |
| Skylake       | 5         | 2.49%   |
| Piledriver    | 5         | 2.49%   |
| Bobcat        | 5         | 2.49%   |
| Unknown       | 5         | 2.49%   |
| Nehalem       | 4         | 1.99%   |
| K10           | 3         | 1.49%   |
| Goldmont plus | 3         | 1.49%   |
| Goldmont      | 3         | 1.49%   |
| Bonnell       | 3         | 1.49%   |
| Steamroller   | 2         | 1%      |
| IceLake       | 2         | 1%      |
| CometLake     | 2         | 1%      |
| Bulldozer     | 2         | 1%      |
| Zen 2         | 1         | 0.5%    |
| Zen           | 1         | 0.5%    |
| TigerLake     | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 141       | 64.38%  |
| Nvidia                     | 33        | 15.07%  |
| AMD                        | 31        | 14.16%  |
| Matrox Electronics Systems | 13        | 5.94%   |
| ASPEED Technology          | 1         | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 18        | 8.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 12        | 5.36%   |
| Intel HD Graphics 5500                                                        | 9         | 4.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 4.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 9         | 4.02%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6         | 2.68%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 2.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 6         | 2.68%   |
| Intel UHD Graphics 620                                                        | 5         | 2.23%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 4         | 1.79%   |
| Matrox Electronics Systems G200eR2                                            | 4         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.79%   |
| Intel HD Graphics 630                                                         | 4         | 1.79%   |
| Intel HD Graphics 620                                                         | 4         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.79%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 1.34%   |
| Matrox Electronics Systems MGA G200EH                                         | 3         | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.34%   |
| Intel JasperLake [UHD Graphics]                                               | 3         | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 1.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 1.34%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 3         | 1.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 1.34%   |
| Nvidia TU117M                                                                 | 2         | 0.89%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2         | 0.89%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 0.89%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 0.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.89%   |
| Intel HD Graphics 500                                                         | 2         | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 0.89%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2         | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 2         | 0.89%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2         | 0.89%   |
| AMD RS780L [Radeon 3000]                                                      | 2         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 114       | 56.72%  |
| 1 x AMD        | 27        | 13.43%  |
| 1 x Nvidia     | 18        | 8.96%   |
| Intel + Nvidia | 15        | 7.46%   |
| 1 x Matrox     | 13        | 6.47%   |
| 2 x Intel      | 8         | 3.98%   |
| Intel + AMD    | 4         | 1.99%   |
| Other          | 1         | 0.5%    |
| 1 x ASPEED     | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 184       | 91.54%  |
| Proprietary | 15        | 7.46%   |
| Unknown     | 2         | 1%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 83.25%  |
| 3.01-4.0   | 8         | 3.94%   |
| 1.01-2.0   | 8         | 3.94%   |
| 0.51-1.0   | 8         | 3.94%   |
| 0.01-0.5   | 8         | 3.94%   |
| 7.01-8.0   | 1         | 0.49%   |
| 2.01-3.0   | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 20        | 18.69%  |
| Samsung Electronics | 16        | 14.95%  |
| Goldstar            | 15        | 14.02%  |
| LG Display          | 11        | 10.28%  |
| BOE                 | 10        | 9.35%   |
| Chimei Innolux      | 7         | 6.54%   |
| AOC                 | 5         | 4.67%   |
| Philips             | 4         | 3.74%   |
| Lenovo              | 4         | 3.74%   |
| InfoVision          | 3         | 2.8%    |
| Dell                | 3         | 2.8%    |
| Hewlett-Packard     | 2         | 1.87%   |
| Apple               | 2         | 1.87%   |
| VIE                 | 1         | 0.93%   |
| PANDA               | 1         | 0.93%   |
| Panasonic           | 1         | 0.93%   |
| LG Electronics      | 1         | 0.93%   |
| ASUSTek Computer    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 3.6%    |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 2.7%    |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 2         | 1.8%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.8%    |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 1.8%    |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 0.9%    |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 1         | 0.9%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 0.9%    |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 0.9%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 0.9%    |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch               | 1         | 0.9%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 0.9%    |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch              | 1         | 0.9%    |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 0.9%    |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                     | 1         | 0.9%    |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                     | 1         | 0.9%    |
| LG Electronics LCD Monitor 23MP55                                     | 1         | 0.9%    |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 0.9%    |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 0.9%    |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 43        | 40.57%  |
| 1920x1080 (FHD)    | 36        | 33.96%  |
| 1600x900 (HD+)     | 8         | 7.55%   |
| 1280x800 (WXGA)    | 3         | 2.83%   |
| 1280x1024 (SXGA)   | 3         | 2.83%   |
| 1680x1050 (WSXGA+) | 2         | 1.89%   |
| 1440x900 (WXGA+)   | 2         | 1.89%   |
| 1360x768           | 2         | 1.89%   |
| 1024x768 (XGA)     | 2         | 1.89%   |
| 3640x1920          | 1         | 0.94%   |
| 2560x1440 (QHD)    | 1         | 0.94%   |
| 1280x720 (HD)      | 1         | 0.94%   |
| 1024x600           | 1         | 0.94%   |
| Unknown            | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 28        | 25.69%  |
| 15      | 26        | 23.85%  |
| 21      | 8         | 7.34%   |
| 23      | 7         | 6.42%   |
| 19      | 7         | 6.42%   |
| 24      | 6         | 5.5%    |
| 18      | 6         | 5.5%    |
| Unknown | 5         | 4.59%   |
| 20      | 4         | 3.67%   |
| 12      | 4         | 3.67%   |
| 14      | 3         | 2.75%   |
| 46      | 1         | 0.92%   |
| 31      | 1         | 0.92%   |
| 17      | 1         | 0.92%   |
| 11      | 1         | 0.92%   |
| 10      | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 48.15%  |
| 401-500     | 24        | 22.22%  |
| 501-600     | 12        | 11.11%  |
| 201-300     | 12        | 11.11%  |
| Unknown     | 5         | 4.63%   |
| 601-700     | 1         | 0.93%   |
| 351-400     | 1         | 0.93%   |
| 1001-1500   | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 83        | 83.84%  |
| 16/10   | 7         | 7.07%   |
| 4/3     | 3         | 3.03%   |
| 5/4     | 2         | 2.02%   |
| 3/2     | 2         | 2.02%   |
| Unknown | 2         | 2.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 28        | 25.69%  |
| 91-100         | 25        | 22.94%  |
| 201-250        | 21        | 19.27%  |
| 151-200        | 11        | 10.09%  |
| 141-150        | 7         | 6.42%   |
| Unknown        | 5         | 4.59%   |
| 61-70          | 4         | 3.67%   |
| 101-110        | 2         | 1.83%   |
| 71-80          | 1         | 0.92%   |
| 51-60          | 1         | 0.92%   |
| 351-500        | 1         | 0.92%   |
| 41-50          | 1         | 0.92%   |
| 111-120        | 1         | 0.92%   |
| 501-1000       | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 48        | 44.86%  |
| 51-100  | 33        | 30.84%  |
| 121-160 | 16        | 14.95%  |
| Unknown | 5         | 4.67%   |
| 161-240 | 3         | 2.8%    |
| 1-50    | 2         | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 95        | 47.03%  |
| 1     | 92        | 45.54%  |
| 2     | 15        | 7.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 114       | 38.38%  |
| Intel                 | 81        | 27.27%  |
| Qualcomm Atheros      | 43        | 14.48%  |
| Broadcom              | 30        | 10.1%   |
| JMicron Technology    | 5         | 1.68%   |
| Samsung Electronics   | 4         | 1.35%   |
| Ralink                | 4         | 1.35%   |
| D-Link System         | 3         | 1.01%   |
| TP-Link               | 2         | 0.67%   |
| Ralink Technology     | 2         | 0.67%   |
| Nvidia                | 2         | 0.67%   |
| MediaTek              | 2         | 0.67%   |
| SysKonnect            | 1         | 0.34%   |
| STMicroelectronics    | 1         | 0.34%   |
| ICS Advent            | 1         | 0.34%   |
| Arduino SA            | 1         | 0.34%   |
| 3Com                  | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 24.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 7.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.64%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.64%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 8         | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.05%   |
| Intel Wireless 7265                                               | 6         | 1.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 1.47%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.17%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.17%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.17%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.17%   |
| Intel 82576 Gigabit Network Connection                            | 4         | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 0.88%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.88%   |
| Intel 82583V Gigabit Network Connection                           | 3         | 0.88%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.59%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2         | 0.59%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.59%   |
| MediaTek USB Ethernet-RNDIS                                       | 2         | 0.59%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.59%   |
| Intel Wireless 8260                                               | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 35        | 36.08%  |
| Intel                 | 32        | 32.99%  |
| Realtek Semiconductor | 16        | 16.49%  |
| Broadcom              | 5         | 5.15%   |
| Ralink                | 4         | 4.12%   |
| TP-Link               | 2         | 2.06%   |
| Ralink Technology     | 2         | 2.06%   |
| D-Link System         | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 10.2%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 9         | 9.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 7.14%   |
| Intel Wireless 7265                                                  | 6         | 6.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 5         | 5.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 4.08%   |
| Intel Wireless 8265 / 8275                                           | 4         | 4.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 3.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 2.04%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2         | 2.04%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2         | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 2.04%   |
| Intel Wireless 8260                                                  | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 2.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.02%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.02%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1         | 1.02%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.02%   |
| Intel Wireless 7260                                                  | 1         | 1.02%   |
| Intel Wireless 3165                                                  | 1         | 1.02%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.02%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.02%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 108       | 47.79%  |
| Intel                 | 64        | 28.32%  |
| Broadcom              | 26        | 11.5%   |
| Qualcomm Atheros      | 11        | 4.87%   |
| JMicron Technology    | 5         | 2.21%   |
| Samsung Electronics   | 4         | 1.77%   |
| Nvidia                | 2         | 0.88%   |
| D-Link System         | 2         | 0.88%   |
| SysKonnect            | 1         | 0.44%   |
| MediaTek              | 1         | 0.44%   |
| ICS Advent            | 1         | 0.44%   |
| 3Com                  | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 82        | 34.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 25        | 10.42%  |
| Intel I211 Gigabit Network Connection                                         | 9         | 3.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 2.08%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 1.67%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 1.67%   |
| Intel Ethernet Controller I225-V                                              | 4         | 1.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 1.67%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 1.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.25%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.25%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.83%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.83%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 2         | 0.83%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 0.83%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.83%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.83%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 0.83%   |
| Intel 82578DC Gigabit Network Connection                                      | 2         | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 0.83%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2         | 0.83%   |
| Broadcom NetXtreme II BCM57800 1/10 Gigabit Ethernet                          | 2         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 0.83%   |
| SysKonnect SK-98xx V2.0 Gigabit Ethernet Adapter [Marvell 88E8001]            | 1         | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 67.02%  |
| WiFi     | 90        | 31.91%  |
| Modem    | 3         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 178       | 73.25%  |
| WiFi     | 65        | 26.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 100       | 49.5%   |
| 1     | 48        | 23.76%  |
| 4     | 26        | 12.87%  |
| 3     | 16        | 7.92%   |
| 6     | 6         | 2.97%   |
| 5     | 5         | 2.48%   |
| 8     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 186       | 91.63%  |
| Yes  | 17        | 8.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 37.1%   |
| Qualcomm Atheros Communications | 16        | 25.81%  |
| Realtek Semiconductor           | 4         | 6.45%   |
| Lite-On Technology              | 4         | 6.45%   |
| Broadcom                        | 4         | 6.45%   |
| Apple                           | 4         | 6.45%   |
| Foxconn / Hon Hai               | 3         | 4.84%   |
| Cambridge Silicon Radio         | 2         | 3.23%   |
| IMC Networks                    | 1         | 1.61%   |
| Dell                            | 1         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 17.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 11.29%  |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 8.06%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 5         | 8.06%   |
| Realtek  Bluetooth Adapter                                  | 3         | 4.84%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 3         | 4.84%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 3.23%   |
| Intel AX201 Bluetooth                                       | 2         | 3.23%   |
| Intel AX200 Bluetooth                                       | 2         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 3.23%   |
| Apple Bluetooth Host Controller                             | 2         | 3.23%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.61%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.61%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.61%   |
| IMC Networks Bluetooth Module                               | 1         | 1.61%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.61%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.61%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.61%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.61%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.61%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 143       | 70.1%   |
| AMD                                             | 31        | 15.2%   |
| Nvidia                                          | 21        | 10.29%  |
| C-Media Electronics                             | 3         | 1.47%   |
| M-Audio                                         | 1         | 0.49%   |
| Logitech                                        | 1         | 0.49%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.49%   |
| Lenovo                                          | 1         | 0.49%   |
| Generalplus Technology                          | 1         | 0.49%   |
| DSEA A/S                                        | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20        | 8.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 6.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 6.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.79%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 4.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 4.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 3.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 3.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 3.72%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 3.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.65%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.65%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.24%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.24%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.83%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.83%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.83%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.83%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 44        | 19.82%  |
| Kingston            | 33        | 14.86%  |
| Smart               | 30        | 13.51%  |
| Samsung Electronics | 22        | 9.91%   |
| Teikon              | 11        | 4.95%   |
| SK hynix            | 11        | 4.95%   |
| Crucial             | 11        | 4.95%   |
| A-DATA Technology   | 8         | 3.6%    |
| Unknown             | 7         | 3.15%   |
| Micron Technology   | 6         | 2.7%    |
| Smart Brazil        | 4         | 1.8%    |
| High Bridge         | 3         | 1.35%   |
| Hewlett-Packard     | 3         | 1.35%   |
| Corsair             | 3         | 1.35%   |
| Apacer              | 3         | 1.35%   |
| Nanya Technology    | 2         | 0.9%    |
| Kllisre             | 2         | 0.9%    |
| G.Skill             | 2         | 0.9%    |
| 019400B300CE        | 2         | 0.9%    |
| Unknown (ABCD)      | 1         | 0.45%   |
| Transcend           | 1         | 0.45%   |
| Toshiba             | 1         | 0.45%   |
| Tigo                | 1         | 0.45%   |
| RZX                 | 1         | 0.45%   |
| PUSKILL             | 1         | 0.45%   |
| PNY                 | 1         | 0.45%   |
| Multilaser          | 1         | 0.45%   |
| Kreton              | 1         | 0.45%   |
| Goldenmars          | 1         | 0.45%   |
| GLOWAY              | 1         | 0.45%   |
| CSX                 | 1         | 0.45%   |
| Atermiter           | 1         | 0.45%   |
| 019400000A07        | 1         | 0.45%   |
| 0194000000CE        | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 7         | 2.93%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 4         | 1.67%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 4         | 1.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3         | 1.26%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 3         | 1.26%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s        | 3         | 1.26%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s        | 3         | 1.26%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s          | 3         | 1.26%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 2         | 0.84%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 2         | 0.84%   |
| Unknown RAM Module 2GB DIMM                                  | 2         | 0.84%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s       | 2         | 0.84%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s       | 2         | 0.84%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s          | 2         | 0.84%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 2         | 0.84%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s        | 2         | 0.84%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 2         | 0.84%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s | 2         | 0.84%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 2         | 0.84%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 2         | 0.84%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2         | 0.84%   |
| 019400B300CE RAM SH5721G4FJ8P6TNSQS 8GB DIMM DDR3 1600MT/s   | 2         | 0.84%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1         | 0.42%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                  | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                   | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                 | 1         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 101       | 54.3%   |
| DDR4    | 44        | 23.66%  |
| DDR2    | 17        | 9.14%   |
| Unknown | 13        | 6.99%   |
| SDRAM   | 9         | 4.84%   |
| LPDDR4  | 1         | 0.54%   |
| DDR     | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 100       | 54.35%  |
| SODIMM       | 81        | 44.02%  |
| Row Of Chips | 1         | 0.54%   |
| FB-DIMM      | 1         | 0.54%   |
| Chip         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 78        | 37.68%  |
| 8192  | 55        | 26.57%  |
| 2048  | 55        | 26.57%  |
| 16384 | 15        | 7.25%   |
| 1024  | 4         | 1.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 58        | 28.71%  |
| 1333    | 40        | 19.8%   |
| 2400    | 19        | 9.41%   |
| 2667    | 14        | 6.93%   |
| Unknown | 14        | 6.93%   |
| 800     | 10        | 4.95%   |
| 2133    | 8         | 3.96%   |
| 1334    | 8         | 3.96%   |
| 1066    | 5         | 2.48%   |
| 667     | 5         | 2.48%   |
| 2666    | 4         | 1.98%   |
| 3200    | 3         | 1.49%   |
| 1067    | 3         | 1.49%   |
| 1867    | 2         | 0.99%   |
| 1866    | 2         | 0.99%   |
| 533     | 2         | 0.99%   |
| 400     | 2         | 0.99%   |
| 2933    | 1         | 0.5%    |
| 975     | 1         | 0.5%    |
| 333     | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model        | Computers | Percent |
|--------------|-----------|---------|
| ELGIN L42PRO | 2         | 100%    |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 16        | 23.19%  |
| Acer                          | 11        | 15.94%  |
| Microdia                      | 8         | 11.59%  |
| Realtek Semiconductor         | 7         | 10.14%  |
| Silicon Motion                | 5         | 7.25%   |
| Logitech                      | 3         | 4.35%   |
| IMC Networks                  | 3         | 4.35%   |
| Syntek                        | 2         | 2.9%    |
| Suyin                         | 2         | 2.9%    |
| Sunplus Innovation Technology | 2         | 2.9%    |
| Apple                         | 2         | 2.9%    |
| Alcor Micro                   | 2         | 2.9%    |
| Unknown                       | 1         | 1.45%   |
| Quanta                        | 1         | 1.45%   |
| Luxvisions Innotech Limited   | 1         | 1.45%   |
| Lite-On Technology            | 1         | 1.45%   |
| Lenovo                        | 1         | 1.45%   |
| Aveo Technology               | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 5         | 7.14%   |
| Acer Integrated Camera                        | 5         | 7.14%   |
| Silicon Motion Web Camera                     | 4         | 5.71%   |
| Realtek Integrated_Webcam_HD                  | 3         | 4.29%   |
| Microdia Integrated_Webcam_HD                 | 3         | 4.29%   |
| Microdia Dell Laptop Integrated Webcam HD     | 3         | 4.29%   |
| Syntek EasyCamera                             | 2         | 2.86%   |
| Realtek Integrated Webcam                     | 2         | 2.86%   |
| Logitech Webcam C270                          | 2         | 2.86%   |
| Chicony Sony Visual Communication Camera      | 2         | 2.86%   |
| Apple FaceTime HD Camera                      | 2         | 2.86%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.86%   |
| Acer HD Webcam                                | 2         | 2.86%   |
| Unknown Realtek PC Camera                     | 1         | 1.43%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.43%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.43%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.43%   |
| Sunplus HD WebCam                             | 1         | 1.43%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.43%   |
| Realtek LG Camera                             | 1         | 1.43%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.43%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.43%   |
| Quanta HD Webcam                              | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.43%   |
| Microdia Integrated Webcam HD                 | 1         | 1.43%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.43%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.43%   |
| Lite-On Integrated Camera                     | 1         | 1.43%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.43%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.43%   |
| IMC Networks USB Camera                       | 1         | 1.43%   |
| IMC Networks EasyCamera                       | 1         | 1.43%   |
| Chicony Webcam                                | 1         | 1.43%   |
| Chicony VGA WebCam                            | 1         | 1.43%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.43%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.43%   |
| Chicony Integrated Camera                     | 1         | 1.43%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.43%   |
| Chicony HP HD Camera                          | 1         | 1.43%   |
| Chicony EasyCamera                            | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 38.46%  |
| Synaptics                  | 3         | 23.08%  |
| Upek                       | 2         | 15.38%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |
| Samsung Electronics        | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                | 2         | 15.38%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 15.38%  |
| Shenzhen Goodix Fingerprint Reader                          | 2         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                             | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 7.69%   |
| Synaptics product 0x00be                                    | 1         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 7.69%   |
| Samsung Fingerprint Device                                  | 1         | 7.69%   |

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
| 0     | 74        | 37%     |
| 1     | 70        | 35%     |
| 2     | 29        | 14.5%   |
| 3     | 16        | 8%      |
| 4     | 6         | 3%      |
| 5     | 5         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 116       | 57.14%  |
| Card reader              | 29        | 14.29%  |
| Net/wireless             | 21        | 10.34%  |
| Bluetooth                | 18        | 8.87%   |
| Fingerprint reader       | 12        | 5.91%   |
| Sound                    | 5         | 2.46%   |
| Network                  | 1         | 0.49%   |
| Firewire controller      | 1         | 0.49%   |

