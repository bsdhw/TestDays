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

Total: 252

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Pegatron      | IPM41-D3                    | Desktop     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
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
| Gateway       | NE56R                       | Notebook    | [f4031498db](https://bsd-hardware.info/?probe=f4031498db) | Apr 15, 2021 |
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
| Intel         | Q3XXG4-P V1.0               | Desktop     | [190d0ed47e](https://bsd-hardware.info/?probe=190d0ed47e) | Feb 16, 2021 |
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
| Positivo      | POS-EAA75DE                 | Desktop     | [65147f9da6](https://bsd-hardware.info/?probe=65147f9da6) | Feb 05, 2021 |
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
| ASUSTek       | Z8P                         | Desktop     | [f59746efd0](https://bsd-hardware.info/?probe=f59746efd0) | Sep 09, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [4876488739](https://bsd-hardware.info/?probe=4876488739) | Sep 02, 2020 |
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
| helloSystem 0.7.0    | 18        | 9%      |
| helloSystem 0.4.0    | 15        | 7.5%    |
| helloSystem 0.6.0    | 14        | 7%      |
| helloSystem 0.5.0    | 14        | 7%      |
| FreeBSD 13.0         | 8         | 4%      |
| OPNsense 21.1.3      | 6         | 3%      |
| OPNsense 21.1        | 6         | 3%      |
| OPNsense 20.7.8      | 6         | 3%      |
| FreeBSD 14.0-CURRENT | 6         | 3%      |
| OPNsense 22.1.10     | 5         | 2.5%    |
| OPNsense 21.1.2      | 5         | 2.5%    |
| OPNsense 21.1.1      | 5         | 2.5%    |
| helloSystem 0.8.0    | 5         | 2.5%    |
| FreeBSD 13.0-p3      | 4         | 2%      |
| FreeBSD 12.1         | 4         | 2%      |
| OPNsense 22.1.8      | 3         | 1.5%    |
| OPNsense 21.7.7      | 3         | 1.5%    |
| OPNsense 21.7.1      | 3         | 1.5%    |
| OPNsense 21.1.9      | 3         | 1.5%    |
| OPNsense 21.1.7      | 3         | 1.5%    |
| OPNsense 21.1.6      | 3         | 1.5%    |
| OPNsense 21.1.4      | 3         | 1.5%    |
| FreeBSD 13.0-p7      | 3         | 1.5%    |
| FreeBSD 13.0-p4      | 3         | 1.5%    |
| TrueNAS 12.2-p9      | 2         | 1%      |
| OPNsense 22.1.7      | 2         | 1%      |
| OPNsense 22.1        | 2         | 1%      |
| OPNsense 21.1.8      | 2         | 1%      |
| OPNsense 21.1.5      | 2         | 1%      |
| NomadBSD 5806f915    | 2         | 1%      |
| FreeNAS 11.3-p9      | 2         | 1%      |
| FreeBSD 13.0-STABLE  | 2         | 1%      |
| FreeBSD 13.0-CURRENT | 2         | 1%      |
| FreeBSD 12.2-p3      | 2         | 1%      |
| FreeBSD 12.2         | 2         | 1%      |
| FreeBSD 12.1-p7      | 2         | 1%      |
| TrueNAS 12.2-p6      | 1         | 0.5%    |
| TrueNAS 12.2-p12     | 1         | 0.5%    |
| TrueNAS 12.2-p11     | 1         | 0.5%    |
| TrueNAS 12.2-p10     | 1         | 0.5%    |
| pfSense 2.4.5        | 1         | 0.5%    |
| OS108 9.99.68        | 1         | 0.5%    |
| OPNsense 22.1.6      | 1         | 0.5%    |
| OPNsense 22.1.5      | 1         | 0.5%    |
| OPNsense 22.1.3      | 1         | 0.5%    |
| OPNsense 22.1.2      | 1         | 0.5%    |
| OPNsense 21.7.3      | 1         | 0.5%    |
| OPNsense 21.7.2      | 1         | 0.5%    |
| OPNsense 21.7        | 1         | 0.5%    |
| OPNsense 20.7        | 1         | 0.5%    |
| OpenBSD 7.0          | 1         | 0.5%    |
| OpenBSD 6.9          | 1         | 0.5%    |
| OpenBSD 6.8          | 1         | 0.5%    |
| NetBSD 9.2           | 1         | 0.5%    |
| helloSystem 0.3.0    | 1         | 0.5%    |
| GhostBSD 22.07.10    | 1         | 0.5%    |
| GhostBSD 20.04.02    | 1         | 0.5%    |
| FreeNAS 11.3-p11     | 1         | 0.5%    |
| FreeBSD 13.1         | 1         | 0.5%    |
| FreeBSD 13.0-RC2     | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 61        | 35.88%  |
| OPNsense    | 51        | 30%     |
| FreeBSD     | 43        | 25.29%  |
| OpenBSD     | 3         | 1.76%   |
| TrueNAS     | 2         | 1.18%   |
| NomadBSD    | 2         | 1.18%   |
| GhostBSD    | 2         | 1.18%   |
| FreeNAS     | 2         | 1.18%   |
| pfSense     | 1         | 0.59%   |
| OS108       | 1         | 0.59%   |
| NetBSD      | 1         | 0.59%   |
| DragonFly   | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 163       | 98.79%  |
| i386  | 2         | 1.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 61        | 36.09%  |
| Console      | 60        | 35.5%   |
| KDE5         | 12        | 7.1%    |
| XFCE         | 10        | 5.92%   |
| MATE         | 6         | 3.55%   |
| Openbox      | 5         | 2.96%   |
| GNOME        | 5         | 2.96%   |
| TWM          | 3         | 1.78%   |
| i3           | 2         | 1.18%   |
| fvwm         | 2         | 1.18%   |
| Window Maker | 1         | 0.59%   |
| spectrwm     | 1         | 0.59%   |
| LXQt         | 1         | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 104       | 63.03%  |
| Console | 61        | 36.97%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 72        | 42.86%  |
| SLiM    | 69        | 41.07%  |
| SDDM    | 11        | 6.55%   |
| LightDM | 7         | 4.17%   |
| GDM     | 5         | 2.98%   |
| XDM     | 4         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 67        | 39.88%  |
| Unknown         | 64        | 38.1%   |
| C               | 19        | 11.31%  |
| pt_BR           | 15        | 8.93%   |
| fr_FR           | 1         | 0.6%    |
| en_US.ISO8859-1 | 1         | 0.6%    |
| en_GB           | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 135       | 79.88%  |
| BIOS | 34        | 20.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 84        | 49.12%  |
| Ufs     | 71        | 41.52%  |
| Cd9660  | 12        | 7.02%   |
| Ffs     | 3         | 1.75%   |
| Hammer2 | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 152       | 90.48%  |
| MBR     | 14        | 8.33%   |
| Unknown | 2         | 1.19%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 26        | 15.76%  |
| ASUSTek Computer        | 24        | 14.55%  |
| Lenovo                  | 17        | 10.3%   |
| Hewlett-Packard         | 10        | 6.06%   |
| Acer                    | 9         | 5.45%   |
| Intel                   | 8         | 4.85%   |
| Samsung Electronics     | 6         | 3.64%   |
| Gigabyte Technology     | 6         | 3.64%   |
| AMI                     | 6         | 3.64%   |
| Unknown                 | 6         | 3.64%   |
| Positivo                | 4         | 2.42%   |
| Itautec                 | 4         | 2.42%   |
| Apple                   | 4         | 2.42%   |
| MSI                     | 3         | 1.82%   |
| Avell High Performance  | 3         | 1.82%   |
| ASRock                  | 3         | 1.82%   |
| Sony                    | 2         | 1.21%   |
| Semp Toshiba            | 2         | 1.21%   |
| Pegatron                | 2         | 1.21%   |
| PCWare                  | 2         | 1.21%   |
| Gateway                 | 2         | 1.21%   |
| ECS                     | 2         | 1.21%   |
| Yanling                 | 1         | 0.61%   |
| ULTRATOP                | 1         | 0.61%   |
| Procomp Ind. Eletronica | 1         | 0.61%   |
| Philco                  | 1         | 0.61%   |
| Notebook                | 1         | 0.61%   |
| LG Electronics          | 1         | 0.61%   |
| KLLISRE                 | 1         | 0.61%   |
| HC                      | 1         | 0.61%   |
| GALAX                   | 1         | 0.61%   |
| ECS-USA                 | 1         | 0.61%   |
| CNCTION-IAF-E3845       | 1         | 0.61%   |
| Clevo                   | 1         | 0.61%   |
| Biostar                 | 1         | 0.61%   |
| Acidanthera             | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 4.24%   |
| Intel Q3XXG4-P V1.0                         | 5         | 3.03%   |
| AMI Aptio CRB                               | 5         | 3.03%   |
| ASUS All Series                             | 4         | 2.42%   |
| Dell Inspiron 3442                          | 3         | 1.82%   |
| Samsung 340XAA/350XAA/550XAA                | 2         | 1.21%   |
| Pegatron IPM41-D3                           | 2         | 1.21%   |
| Gigabyte H61M-S2-B3                         | 2         | 1.21%   |
| Gateway NE56R                               | 2         | 1.21%   |
| ASUS PRIME B450M-GAMING/BR                  | 2         | 1.21%   |
| ASUS P8H61-M LX3 PLUS R2.0                  | 2         | 1.21%   |
| ASUS M5A78L-M LX/BR                         | 2         | 1.21%   |
| Acer Aspire 5750                            | 2         | 1.21%   |
| Yanling NS-1U8L                             | 1         | 0.61%   |
| ULTRATOP C2017-LIVA-ZE                      | 1         | 0.61%   |
| Sony VPCYB45JB                              | 1         | 0.61%   |
| Sony VPCEG17FB                              | 1         | 0.61%   |
| Semp Toshiba STI NA 1401                    | 1         | 0.61%   |
| Semp Toshiba STI                            | 1         | 0.61%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.61%   |
| Samsung 530XBB                              | 1         | 0.61%   |
| Samsung 300E5M/300E5L                       | 1         | 0.61%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 0.61%   |
| Procomp Ind. Eletronica G41MXE              | 1         | 0.61%   |
| Positivo POS-PIQ77CL                        | 1         | 0.61%   |
| Positivo POS-EINM70CS                       | 1         | 0.61%   |
| Positivo POS-EAA75DE                        | 1         | 0.61%   |
| Positivo C14CR01                            | 1         | 0.61%   |
| Philco 10B                                  | 1         | 0.61%   |
| PCWare PW-945GCX                            | 1         | 0.61%   |
| PCWare IPX1800G2                            | 1         | 0.61%   |
| Notebook N85_N87HCHNHZ                      | 1         | 0.61%   |
| MSI U-100                                   | 1         | 0.61%   |
| MSI MS-7877                                 | 1         | 0.61%   |
| MSI MS-7698                                 | 1         | 0.61%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.61%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.61%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 0.61%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 0.61%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 0.61%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 0.61%   |
| Lenovo ThinkPad T61 7661GY9                 | 1         | 0.61%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 0.61%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 0.61%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 0.61%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 0.61%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT           | 1         | 0.61%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 0.61%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 0.61%   |
| Lenovo IdeaPad S145-15API 81V7              | 1         | 0.61%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 0.61%   |
| Lenovo G550 2958                            | 1         | 0.61%   |
| KLLISRE X99-B5 V1.0                         | 1         | 0.61%   |
| Itautec Infoway w7535                       | 1         | 0.61%   |
| Itautec Infoway w7530                       | 1         | 0.61%   |
| Itautec Infoway ST-4344                     | 1         | 0.61%   |
| Itautec Infoway                             | 1         | 0.61%   |
| Intel H61                                   | 1         | 0.61%   |
| Intel H55                                   | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 12        | 7.27%   |
| Lenovo ThinkPad                | 11        | 6.67%   |
| Acer Aspire                    | 8         | 4.85%   |
| Unknown                        | 7         | 4.24%   |
| AMI Aptio                      | 6         | 3.64%   |
| Intel Q3XXG4-P                 | 5         | 3.03%   |
| HP ProLiant                    | 5         | 3.03%   |
| Lenovo IdeaPad                 | 4         | 2.42%   |
| Itautec Infoway                | 4         | 2.42%   |
| Dell PowerEdge                 | 4         | 2.42%   |
| Dell OptiPlex                  | 4         | 2.42%   |
| ASUS All                       | 4         | 2.42%   |
| Dell Vostro                    | 3         | 1.82%   |
| ASUS PRIME                     | 3         | 1.82%   |
| ASUS M5A78L-M                  | 3         | 1.82%   |
| Semp Toshiba STI               | 2         | 1.21%   |
| Samsung 340XAA                 | 2         | 1.21%   |
| Pegatron IPM41-D3              | 2         | 1.21%   |
| Gigabyte H61M-S2-B3            | 2         | 1.21%   |
| Gateway NE56R                  | 2         | 1.21%   |
| Dell Latitude                  | 2         | 1.21%   |
| Avell High Performance A62     | 2         | 1.21%   |
| ASUS P8H61-M                   | 2         | 1.21%   |
| Yanling NS-1U8L                | 1         | 0.61%   |
| ULTRATOP C2017-LIVA-ZE         | 1         | 0.61%   |
| Sony VPCYB45JB                 | 1         | 0.61%   |
| Sony VPCEG17FB                 | 1         | 0.61%   |
| Samsung RV411                  | 1         | 0.61%   |
| Samsung 530XBB                 | 1         | 0.61%   |
| Samsung 300E5M                 | 1         | 0.61%   |
| Samsung 270E5K                 | 1         | 0.61%   |
| Procomp Ind. Eletronica G41MXE | 1         | 0.61%   |
| Positivo POS-PIQ77CL           | 1         | 0.61%   |
| Positivo POS-EINM70CS          | 1         | 0.61%   |
| Positivo POS-EAA75DE           | 1         | 0.61%   |
| Positivo C14CR01               | 1         | 0.61%   |
| Philco 10B                     | 1         | 0.61%   |
| PCWare PW-945GCX               | 1         | 0.61%   |
| PCWare IPX1800G2               | 1         | 0.61%   |
| Notebook N85                   | 1         | 0.61%   |
| MSI U-100                      | 1         | 0.61%   |
| MSI MS-7877                    | 1         | 0.61%   |
| MSI MS-7698                    | 1         | 0.61%   |
| LG 14Z980-G.BH51P1             | 1         | 0.61%   |
| Lenovo IdeaPadFlex             | 1         | 0.61%   |
| Lenovo G550                    | 1         | 0.61%   |
| KLLISRE X99-B5                 | 1         | 0.61%   |
| Intel H61                      | 1         | 0.61%   |
| Intel H55                      | 1         | 0.61%   |
| Intel DH61WW                   | 1         | 0.61%   |
| HP Z230                        | 1         | 0.61%   |
| HP EliteDesk                   | 1         | 0.61%   |
| HP EliteBook                   | 1         | 0.61%   |
| HP Compaq                      | 1         | 0.61%   |
| HP 14                          | 1         | 0.61%   |
| HC HCAR357-MI                  | 1         | 0.61%   |
| Gigabyte G41MT-S2              | 1         | 0.61%   |
| Gigabyte C847N                 | 1         | 0.61%   |
| Gigabyte AB350M-Gaming         | 1         | 0.61%   |
| Gigabyte 970A-UD3P             | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 19        | 11.52%  |
| 2016    | 18        | 10.91%  |
| 2013    | 18        | 10.91%  |
| 2019    | 16        | 9.7%    |
| 2020    | 14        | 8.48%   |
| 2011    | 14        | 8.48%   |
| 2010    | 10        | 6.06%   |
| 2009    | 10        | 6.06%   |
| 2015    | 8         | 4.85%   |
| 2021    | 7         | 4.24%   |
| 2017    | 7         | 4.24%   |
| 2014    | 7         | 4.24%   |
| 2012    | 7         | 4.24%   |
| 2008    | 4         | 2.42%   |
| 2007    | 3         | 1.82%   |
| Unknown | 2         | 1.21%   |
| 2022    | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 81        | 49.09%  |
| Notebook    | 67        | 40.61%  |
| Mini pc     | 7         | 4.24%   |
| Server      | 5         | 3.03%   |
| All in one  | 3         | 1.82%   |
| Convertible | 2         | 1.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 165       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 62        | 37.13%  |
| 4.01-8.0    | 61        | 36.53%  |
| 16.01-24.0  | 24        | 14.37%  |
| 2.01-3.0    | 9         | 5.39%   |
| 32.01-64.0  | 6         | 3.59%   |
| 3.01-4.0    | 2         | 1.2%    |
| 24.01-32.0  | 2         | 1.2%    |
| 64.01-256.0 | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 109       | 64.88%  |
| 0.51-1.0   | 43        | 25.6%   |
| 1.01-2.0   | 8         | 4.76%   |
| 4.01-8.0   | 2         | 1.19%   |
| Unknown    | 2         | 1.19%   |
| 32.01-64.0 | 1         | 0.6%    |
| 24.01-32.0 | 1         | 0.6%    |
| 2.01-3.0   | 1         | 0.6%    |
| 16.01-24.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 66.47%  |
| 2      | 32        | 18.82%  |
| 0      | 12        | 7.06%   |
| 3      | 7         | 4.12%   |
| 5      | 2         | 1.18%   |
| 4      | 2         | 1.18%   |
| 7      | 1         | 0.59%   |
| 6      | 1         | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 68.48%  |
| Yes       | 52        | 31.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 93.94%  |
| No        | 10        | 6.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 50.91%  |
| No        | 81        | 49.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 67.27%  |
| Yes       | 54        | 32.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 165       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| SГЈo Paulo              | 19        | 10.27%  |
| Rio de Janeiro            | 12        | 6.49%   |
| Curitiba                  | 8         | 4.32%   |
| SÃ£o Paulo              | 6         | 3.24%   |
| Sao Paulo                 | 5         | 2.7%    |
| Manaus                    | 4         | 2.16%   |
| Campinas                  | 4         | 2.16%   |
| Belo Horizonte            | 4         | 2.16%   |
| SГЈo JosГ© dos Campos | 3         | 1.62%   |
| Porto Alegre              | 3         | 1.62%   |
| JoГЈo Pessoa            | 3         | 1.62%   |
| Teresina                  | 2         | 1.08%   |
| Serra                     | 2         | 1.08%   |
| Sao Vicente               | 2         | 1.08%   |
| RondonГіpolis           | 2         | 1.08%   |
| Rio Claro                 | 2         | 1.08%   |
| Pirapora                  | 2         | 1.08%   |
| Novo Hamburgo             | 2         | 1.08%   |
| Maraba                    | 2         | 1.08%   |
| JundiaГ­                | 2         | 1.08%   |
| Ipojuca                   | 2         | 1.08%   |
| Franca                    | 2         | 1.08%   |
| CuiabГЎ                 | 2         | 1.08%   |
| BrasГ­lia               | 2         | 1.08%   |
| BrasÃ­lia               | 2         | 1.08%   |
| Boa Vista do Jauato       | 2         | 1.08%   |
| VitГіria da Conquista   | 1         | 0.54%   |
| VitГіria                | 1         | 0.54%   |
| Visconde do Rio Branco    | 1         | 0.54%   |
| Urupes                    | 1         | 0.54%   |
| Unai                      | 1         | 0.54%   |
| Uberaba                   | 1         | 0.54%   |
| Teresopolis               | 1         | 0.54%   |
| Taubate                   | 1         | 0.54%   |
| Tangara                   | 1         | 0.54%   |
| Sao Jose                  | 1         | 0.54%   |
| Sao Jeronimo da Serra     | 1         | 0.54%   |
| Sao Goncalo               | 1         | 0.54%   |
| Sao Bernardo do Campo     | 1         | 0.54%   |
| Santa Maria               | 1         | 0.54%   |
| Rio Grande da Serra       | 1         | 0.54%   |
| Rio das Ostras            | 1         | 0.54%   |
| Reriutaba                 | 1         | 0.54%   |
| Porto UniГЈo            | 1         | 0.54%   |
| Piracicaba                | 1         | 0.54%   |
| Piloezinhos               | 1         | 0.54%   |
| Pelotas                   | 1         | 0.54%   |
| Patos de Minas            | 1         | 0.54%   |
| Pato Branco               | 1         | 0.54%   |
| Paracuru                  | 1         | 0.54%   |
| Osasco                    | 1         | 0.54%   |
| Novo Horizonte do Norte   | 1         | 0.54%   |
| Nilopolis                 | 1         | 0.54%   |
| Morungaba                 | 1         | 0.54%   |
| Monte Belo                | 1         | 0.54%   |
| Marica                    | 1         | 0.54%   |
| Maracanau                 | 1         | 0.54%   |
| Mage                      | 1         | 0.54%   |
| Macatuba                  | 1         | 0.54%   |
| Londrina                  | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 48     | 19.42%  |
| Seagate             | 35        | 86     | 16.99%  |
| Kingston            | 30        | 41     | 14.56%  |
| Samsung Electronics | 20        | 21     | 9.71%   |
| Toshiba             | 13        | 13     | 6.31%   |
| SanDisk             | 9         | 9      | 4.37%   |
| A-DATA Technology   | 8         | 8      | 3.88%   |
| Crucial             | 7         | 9      | 3.4%    |
| KingSpec            | 5         | 5      | 2.43%   |
| LITEON              | 4         | 4      | 1.94%   |
| Hoodisk             | 4         | 4      | 1.94%   |
| Hitachi             | 4         | 7      | 1.94%   |
| China               | 4         | 7      | 1.94%   |
| SK hynix            | 3         | 3      | 1.46%   |
| Silicon Motion      | 3         | 3      | 1.46%   |
| SSSTC               | 2         | 2      | 0.97%   |
| Hewlett-Packard     | 2         | 3      | 0.97%   |
| XrayDisk            | 1         | 1      | 0.49%   |
| Transcend           | 1         | 2      | 0.49%   |
| Smart               | 1         | 1      | 0.49%   |
| Phison              | 1         | 1      | 0.49%   |
| Patriot             | 1         | 4      | 0.49%   |
| NTC                 | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Kston               | 1         | 1      | 0.49%   |
| Hikvision           | 1         | 1      | 0.49%   |
| HGST                | 1         | 2      | 0.49%   |
| Gigabyte Technology | 1         | 1      | 0.49%   |
| Faspeed             | 1         | 1      | 0.49%   |
| Drevo               | 1         | 4      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 8         | 3.59%   |
| Kingston SA400S37120G 120GB         | 7         | 3.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.79%   |
| Kingston SA400S37480G 480GB         | 4         | 1.79%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3         | 1.35%   |
| Toshiba MQ01ABD100 1TB              | 3         | 1.35%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.35%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 1.35%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.35%   |
| SanDisk SDSSDA240G 240GB            | 3         | 1.35%   |
| Samsung HD502HJ 500GB               | 3         | 1.35%   |
| Samsung HD322HJ 320GB               | 3         | 1.35%   |
| Kingston SA400S37960G 960GB         | 3         | 1.35%   |
| A-DATA SU630 240GB                  | 3         | 1.35%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.9%    |
| Silicon Motion NE-256 256GB         | 2         | 0.9%    |
| Seagate ST500LT012-9WS142 500GB     | 2         | 0.9%    |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.9%    |
| SanDisk SSD PLUS 120GB              | 2         | 0.9%    |
| Samsung HD161HJ 160GB               | 2         | 0.9%    |
| Kingston SUV400S37120G 120GB        | 2         | 0.9%    |
| KingSpec MT-128 128GB               | 2         | 0.9%    |
| Hoodisk SSD 64GB                    | 2         | 0.9%    |
| Hoodisk SSD 32GB                    | 2         | 0.9%    |
| China SATA SSD 120GB                | 2         | 0.9%    |
| XrayDisk SSD 128GB                  | 1         | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 0.45%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.45%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.45%   |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 0.45%   |
| WDC WD5000B 500GB                   | 1         | 0.45%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 0.45%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 0.45%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 0.45%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 0.45%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 0.45%   |
| WDC WD400BD-75LRA0 40GB             | 1         | 0.45%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 0.45%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 0.45%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 0.45%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 1         | 0.45%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 0.45%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1         | 0.45%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 1         | 0.45%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 0.45%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.45%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.45%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.45%   |
| WDC WD1600AVJS-63WNA0 160GB         | 1         | 0.45%   |
| WDC WD1200BEVT-22ZCT0 120GB         | 1         | 0.45%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.45%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.45%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 0.45%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 43     | 34.29%  |
| Seagate             | 35        | 86     | 33.33%  |
| Samsung Electronics | 15        | 16     | 14.29%  |
| Toshiba             | 12        | 12     | 11.43%  |
| Hitachi             | 4         | 7      | 3.81%   |
| Hewlett-Packard     | 2         | 3      | 1.9%    |
| HGST                | 1         | 2      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 29        | 40     | 33.72%  |
| SanDisk             | 9         | 9      | 10.47%  |
| Crucial             | 6         | 8      | 6.98%   |
| WDC                 | 5         | 5      | 5.81%   |
| KingSpec            | 5         | 5      | 5.81%   |
| Samsung Electronics | 4         | 4      | 4.65%   |
| LITEON              | 4         | 4      | 4.65%   |
| Hoodisk             | 4         | 4      | 4.65%   |
| China               | 4         | 7      | 4.65%   |
| A-DATA Technology   | 4         | 4      | 4.65%   |
| SK hynix            | 2         | 2      | 2.33%   |
| XrayDisk            | 1         | 1      | 1.16%   |
| Transcend           | 1         | 2      | 1.16%   |
| Smart               | 1         | 1      | 1.16%   |
| Patriot             | 1         | 4      | 1.16%   |
| NTC                 | 1         | 1      | 1.16%   |
| Kston               | 1         | 1      | 1.16%   |
| Hikvision           | 1         | 1      | 1.16%   |
| Gigabyte Technology | 1         | 1      | 1.16%   |
| Faspeed             | 1         | 1      | 1.16%   |
| Drevo               | 1         | 4      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 89        | 169    | 48.63%  |
| SSD  | 78        | 109    | 42.62%  |
| NVMe | 16        | 16     | 8.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 141       | 278    | 89.81%  |
| NVMe | 16        | 16     | 10.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 179    | 72.29%  |
| 0.51-1.0   | 35        | 51     | 21.08%  |
| 1.01-2.0   | 7         | 16     | 4.22%   |
| 3.01-4.0   | 4         | 32     | 2.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 24.72%  |
| 1-20           | 43        | 24.16%  |
| 251-500        | 32        | 17.98%  |
| 21-50          | 19        | 10.67%  |
| 51-100         | 17        | 9.55%   |
| 501-1000       | 14        | 7.87%   |
| 1001-2000      | 5         | 2.81%   |
| 2001-3000      | 2         | 1.12%   |
| More than 3000 | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 141       | 84.94%  |
| 21-50     | 13        | 7.83%   |
| 101-250   | 5         | 3.01%   |
| 501-1000  | 4         | 2.41%   |
| 2001-3000 | 1         | 0.6%    |
| 51-100    | 1         | 0.6%    |
| Unknown   | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3         | 3      | 5.17%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 2      | 3.45%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 3.45%   |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 3.45%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.72%   |
| WDC WD5000B 500GB                   | 1         | 1      | 1.72%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 1      | 1.72%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 1      | 1.72%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 1      | 1.72%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.72%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 1.72%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 1.72%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 1.72%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 1.72%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 1.72%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 1.72%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 1.72%   |
| Transcend TS32GMSM610 32GB          | 1         | 2      | 1.72%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.72%   |
| Toshiba MK6034GSX 64GB              | 1         | 1      | 1.72%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.72%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 1.72%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 1.72%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 1.72%   |
| Seagate ST9320325ASG 320GB          | 1         | 1      | 1.72%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 1.72%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.72%   |
| Seagate ST9120821AS 118GB           | 1         | 1      | 1.72%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.72%   |
| Seagate ST500DM002-1BC142 500GB     | 1         | 1      | 1.72%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.72%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.72%   |
| Seagate ST31000528AS 1TB            | 1         | 1      | 1.72%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 1.72%   |
| Seagate ST2000DM001-1E6164 2TB      | 1         | 1      | 1.72%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 9      | 1.72%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1      | 1.72%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1      | 1.72%   |
| SanDisk SSD PLUS 240 GB             | 1         | 1      | 1.72%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 1.72%   |
| Samsung Electronics HD642JJ 640GB   | 1         | 1      | 1.72%   |
| Samsung Electronics HD502HJ 500GB   | 1         | 1      | 1.72%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1      | 1.72%   |
| Kingston SV300S37A60G 64GB          | 1         | 1      | 1.72%   |
| KingSpec P3-128 128GB               | 1         | 1      | 1.72%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 1.72%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 1.72%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 3      | 1.72%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 2      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 26     | 32.73%  |
| WDC                 | 13        | 15     | 23.64%  |
| Toshiba             | 7         | 7      | 12.73%  |
| Samsung Electronics | 7         | 8      | 12.73%  |
| Hitachi             | 4         | 7      | 7.27%   |
| Transcend           | 1         | 2      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| SanDisk             | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| Kingston            | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 26     | 36.73%  |
| WDC                 | 13        | 15     | 26.53%  |
| Toshiba             | 7         | 7      | 14.29%  |
| Samsung Electronics | 7         | 8      | 14.29%  |
| Hitachi             | 4         | 7      | 8.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 63     | 87.76%  |
| SSD  | 6         | 7      | 12.24%  |

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
| Works    | 124       | 217    | 70.06%  |
| Malfunc  | 48        | 70     | 27.12%  |
| Detected | 4         | 6      | 2.26%   |
| Failed   | 1         | 1      | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 137       | 75.27%  |
| AMD                            | 19        | 10.44%  |
| Silicon Motion                 | 5         | 2.75%   |
| Nvidia                         | 4         | 2.2%    |
| ADATA Technology               | 3         | 1.65%   |
| Solid State Storage Technology | 2         | 1.1%    |
| Broadcom / LSI                 | 2         | 1.1%    |
| Toshiba                        | 1         | 0.55%   |
| SK hynix                       | 1         | 0.55%   |
| Samsung Electronics            | 1         | 0.55%   |
| Realtek Semiconductor          | 1         | 0.55%   |
| Phison Electronics             | 1         | 0.55%   |
| Micron/Crucial Technology      | 1         | 0.55%   |
| Kingston Technology Company    | 1         | 0.55%   |
| Integrated Technology Express  | 1         | 0.55%   |
| Hewlett-Packard                | 1         | 0.55%   |
| Adaptec                        | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15        | 7.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 5.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 5.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 10        | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 4.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 4.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 3.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 3.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 2.82%   |
| Unknown                                                                                 | 6         | 2.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.41%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.94%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 0.94%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 0.94%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.47%   |
| SK hynix BC511                                                                          | 1         | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.47%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.47%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.47%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.47%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.47%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.47%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.47%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.47%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                                 | 1         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.47%   |
| Integrated Express IT8213 IDE Controller                                                | 1         | 0.47%   |
| HP Smart Array G6 controllers                                                           | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 123       | 65.78%  |
| IDE  | 37        | 19.79%  |
| NVMe | 17        | 9.09%   |
| RAID | 9         | 4.81%   |
| SCSI | 1         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 143       | 86.67%  |
| AMD    | 22        | 13.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 5         | 3.01%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4         | 2.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.81%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3         | 1.81%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 1.2%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.2%    |
| Intel CPU Version                           | 2         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.2%    |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.2%    |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.2%    |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.2%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.2%    |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.2%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 1.2%    |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.2%    |
| Intel Core i3-2100 CPU                      | 2         | 1.2%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.2%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 1.2%    |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.2%    |
| AMD FX-8320E Eight-Core Processor           | 2         | 1.2%    |
| Intel Xeon E-2224 CPU @ 3.40GHz             | 1         | 0.6%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.6%    |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.6%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.6%    |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 0.6%    |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.6%    |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz         | 1         | 0.6%    |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz         | 1         | 0.6%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.6%    |
| Intel Pentium M                             | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.6%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.6%    |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.6%    |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1         | 0.6%    |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.6%    |
| Intel Genuine CPU                           | 1         | 0.6%    |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.6%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.6%    |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.6%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.6%    |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.6%    |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 0.6%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 20.61%  |
| Intel Core i3           | 25        | 15.15%  |
| Intel Celeron           | 20        | 12.12%  |
| Intel Core i7           | 19        | 11.52%  |
| Intel Xeon              | 11        | 6.67%   |
| Intel Core 2 Duo        | 9         | 5.45%   |
| Intel Pentium Dual-Core | 6         | 3.64%   |
| AMD FX                  | 6         | 3.64%   |
| Intel Atom              | 5         | 3.03%   |
| AMD Ryzen 5             | 5         | 3.03%   |
| Intel Pentium           | 4         | 2.42%   |
| Other                   | 3         | 1.82%   |
| Intel Core 2 Quad       | 2         | 1.21%   |
| AMD E                   | 2         | 1.21%   |
| Intel Pentium M         | 1         | 0.61%   |
| Intel Pentium Dual      | 1         | 0.61%   |
| Intel Genuine           | 1         | 0.61%   |
| Intel Core M            | 1         | 0.61%   |
| Intel Core 2            | 1         | 0.61%   |
| AMD Turion II Neo       | 1         | 0.61%   |
| AMD Ryzen 7             | 1         | 0.61%   |
| AMD Ryzen 3             | 1         | 0.61%   |
| AMD PRO A8              | 1         | 0.61%   |
| AMD Phenom              | 1         | 0.61%   |
| AMD E1                  | 1         | 0.61%   |
| AMD C-60                | 1         | 0.61%   |
| AMD Athlon II X2        | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 88        | 53.01%  |
| 4       | 45        | 27.11%  |
| 8       | 11        | 6.63%   |
| 6       | 9         | 5.42%   |
| Unknown | 8         | 4.82%   |
| 12      | 3         | 1.81%   |
| 1       | 2         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 161       | 97.58%  |
| 2      | 4         | 2.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 82        | 49.4%   |
| 2       | 76        | 45.78%  |
| Unknown | 8         | 4.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 15.66%  |
| SandyBridge   | 20        | 12.05%  |
| Penryn        | 18        | 10.84%  |
| Haswell       | 15        | 9.04%   |
| IvyBridge     | 13        | 7.83%   |
| Silvermont    | 12        | 7.23%   |
| Broadwell     | 9         | 5.42%   |
| Westmere      | 6         | 3.61%   |
| Zen+          | 5         | 3.01%   |
| Piledriver    | 5         | 3.01%   |
| Core          | 5         | 3.01%   |
| Skylake       | 4         | 2.41%   |
| Bobcat        | 4         | 2.41%   |
| Nehalem       | 3         | 1.81%   |
| K10           | 3         | 1.81%   |
| Goldmont      | 3         | 1.81%   |
| Bonnell       | 3         | 1.81%   |
| Steamroller   | 2         | 1.2%    |
| Goldmont plus | 2         | 1.2%    |
| CometLake     | 2         | 1.2%    |
| Zen 2         | 1         | 0.6%    |
| Zen           | 1         | 0.6%    |
| TigerLake     | 1         | 0.6%    |
| IceLake       | 1         | 0.6%    |
| Bulldozer     | 1         | 0.6%    |
| Unknown       | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 120       | 64.86%  |
| Nvidia                     | 30        | 16.22%  |
| AMD                        | 27        | 14.59%  |
| Matrox Electronics Systems | 7         | 3.78%   |
| ASPEED Technology          | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 18        | 9.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 12        | 6.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 9         | 4.74%   |
| Intel HD Graphics 5500                                                        | 8         | 4.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 4.21%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 3.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 5         | 2.63%   |
| Intel UHD Graphics 620                                                        | 5         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 2.63%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 4         | 2.11%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 1.58%   |
| Matrox Electronics Systems MGA G200EH                                         | 3         | 1.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 1.58%   |
| Intel HD Graphics 630                                                         | 3         | 1.58%   |
| Intel HD Graphics 620                                                         | 3         | 1.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 1.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 3         | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 1.58%   |
| Nvidia TU117M                                                                 | 2         | 1.05%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2         | 1.05%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 1.05%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 2         | 1.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 1.05%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 2         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.05%   |
| Intel HD Graphics 500                                                         | 2         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.05%   |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2         | 1.05%   |
| AMD RS780L [Radeon 3000]                                                      | 2         | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.05%   |
| AMD Kaveri [Radeon R7 Graphics]                                               | 2         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.53%   |
| Nvidia GT218 [GeForce 210]                                                    | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.53%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1         | 0.53%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.53%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.53%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.53%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.53%   |
| Nvidia GK107GL [Quadro K2000]                                                 | 1         | 0.53%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                                 | 1         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.53%   |
| Nvidia GF108 [GeForce GT 430]                                                 | 1         | 0.53%   |
| Nvidia GF106 [GeForce GTS 450]                                                | 1         | 0.53%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1         | 0.53%   |
| Nvidia C79 [GeForce 9400]                                                     | 1         | 0.53%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 0.53%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1         | 0.53%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller      | 1         | 0.53%   |
| Matrox Electronics Systems G200eR2                                            | 1         | 0.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 0.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 0.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 93        | 56.02%  |
| 1 x AMD        | 23        | 13.86%  |
| 1 x Nvidia     | 15        | 9.04%   |
| Intel + Nvidia | 15        | 9.04%   |
| 2 x Intel      | 8         | 4.82%   |
| 1 x Matrox     | 7         | 4.22%   |
| Intel + AMD    | 4         | 2.41%   |
| 1 x ASPEED     | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 153       | 92.17%  |
| Proprietary | 12        | 7.23%   |
| Unknown     | 1         | 0.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 82.84%  |
| 3.01-4.0   | 8         | 4.73%   |
| 0.01-0.5   | 8         | 4.73%   |
| 1.01-2.0   | 6         | 3.55%   |
| 0.51-1.0   | 5         | 2.96%   |
| 7.01-8.0   | 1         | 0.59%   |
| 2.01-3.0   | 1         | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 19        | 20%     |
| Samsung Electronics | 14        | 14.74%  |
| Goldstar            | 12        | 12.63%  |
| LG Display          | 10        | 10.53%  |
| BOE                 | 8         | 8.42%   |
| Chimei Innolux      | 6         | 6.32%   |
| AOC                 | 5         | 5.26%   |
| Lenovo              | 4         | 4.21%   |
| InfoVision          | 3         | 3.16%   |
| Dell                | 3         | 3.16%   |
| Philips             | 2         | 2.11%   |
| Hewlett-Packard     | 2         | 2.11%   |
| Apple               | 2         | 2.11%   |
| VIE                 | 1         | 1.05%   |
| PANDA               | 1         | 1.05%   |
| Panasonic           | 1         | 1.05%   |
| LG Electronics      | 1         | 1.05%   |
| ASUSTek Computer    | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.04%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 3.03%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 2         | 2.02%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.02%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.02%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 1.01%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 1.01%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.01%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 1.01%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.01%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.01%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                     | 1         | 1.01%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                     | 1         | 1.01%   |
| LG Electronics LCD Monitor 23MP55                                     | 1         | 1.01%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.01%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.01%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch              | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.01%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.01%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.01%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.01%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.01%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch            | 1         | 1.01%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                   | 1         | 1.01%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 1.01%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                   | 1         | 1.01%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch            | 1         | 1.01%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.01%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                 | 1         | 1.01%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                 | 1         | 1.01%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                  | 1         | 1.01%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                  | 1         | 1.01%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                 | 1         | 1.01%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                 | 1         | 1.01%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 1         | 1.01%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.01%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.01%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 39        | 41.49%  |
| 1920x1080 (FHD)    | 31        | 32.98%  |
| 1600x900 (HD+)     | 6         | 6.38%   |
| 1440x900 (WXGA+)   | 3         | 3.19%   |
| 1280x800 (WXGA)    | 3         | 3.19%   |
| 1280x1024 (SXGA)   | 3         | 3.19%   |
| 1024x768 (XGA)     | 2         | 2.13%   |
| 3640x1920          | 1         | 1.06%   |
| 2560x1440 (QHD)    | 1         | 1.06%   |
| 1680x1050 (WSXGA+) | 1         | 1.06%   |
| 1360x768           | 1         | 1.06%   |
| 1280x720 (HD)      | 1         | 1.06%   |
| 1024x600           | 1         | 1.06%   |
| Unknown            | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 25        | 25.77%  |
| 15      | 24        | 24.74%  |
| 19      | 7         | 7.22%   |
| 24      | 6         | 6.19%   |
| 23      | 6         | 6.19%   |
| 21      | 5         | 5.15%   |
| 18      | 5         | 5.15%   |
| Unknown | 5         | 5.15%   |
| 12      | 4         | 4.12%   |
| 20      | 3         | 3.09%   |
| 14      | 3         | 3.09%   |
| 31      | 1         | 1.03%   |
| 17      | 1         | 1.03%   |
| 11      | 1         | 1.03%   |
| 10      | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 48.96%  |
| 401-500     | 18        | 18.75%  |
| 501-600     | 12        | 12.5%   |
| 201-300     | 12        | 12.5%   |
| Unknown     | 5         | 5.21%   |
| 601-700     | 1         | 1.04%   |
| 351-400     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 81.61%  |
| 16/10   | 8         | 9.2%    |
| 4/3     | 3         | 3.45%   |
| 5/4     | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| 3/2     | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 25        | 25.77%  |
| 91-100         | 23        | 23.71%  |
| 201-250        | 17        | 17.53%  |
| 151-200        | 10        | 10.31%  |
| 141-150        | 6         | 6.19%   |
| Unknown        | 5         | 5.15%   |
| 61-70          | 4         | 4.12%   |
| 101-110        | 2         | 2.06%   |
| 71-80          | 1         | 1.03%   |
| 51-60          | 1         | 1.03%   |
| 351-500        | 1         | 1.03%   |
| 41-50          | 1         | 1.03%   |
| 111-120        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 41        | 43.16%  |
| 51-100  | 30        | 31.58%  |
| 121-160 | 15        | 15.79%  |
| Unknown | 5         | 5.26%   |
| 161-240 | 3         | 3.16%   |
| 1-50    | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 49.1%   |
| 0     | 73        | 43.71%  |
| 2     | 12        | 7.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 94        | 38.06%  |
| Intel                 | 64        | 25.91%  |
| Qualcomm Atheros      | 38        | 15.38%  |
| Broadcom              | 24        | 9.72%   |
| JMicron Technology    | 5         | 2.02%   |
| Samsung Electronics   | 4         | 1.62%   |
| Ralink                | 4         | 1.62%   |
| D-Link System         | 3         | 1.21%   |
| TP-Link               | 2         | 0.81%   |
| Ralink Technology     | 2         | 0.81%   |
| Nvidia                | 2         | 0.81%   |
| MediaTek              | 2         | 0.81%   |
| ICS Advent            | 1         | 0.4%    |
| Arduino SA            | 1         | 0.4%    |
| 3Com                  | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 23.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 7.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 3.2%    |
| Intel I211 Gigabit Network Connection                             | 8         | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.49%   |
| Intel Wireless 7265                                               | 6         | 2.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 1.78%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 1.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.42%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.42%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.42%   |
| Intel 82576 Gigabit Network Connection                            | 4         | 1.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.07%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.07%   |
| Intel 82583V Gigabit Network Connection                           | 3         | 1.07%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 1.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.07%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.71%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.71%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2         | 0.71%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2         | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.71%   |
| MediaTek USB Ethernet-RNDIS                                       | 2         | 0.71%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.71%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.71%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.36%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.36%   |
| Realtek RTL8187SE Wireless LAN Controller                         | 1         | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.36%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.36%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.36%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.36%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.36%   |
| Intel Wireless 8260                                               | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 31        | 34.07%  |
| Intel                 | 30        | 32.97%  |
| Realtek Semiconductor | 16        | 17.58%  |
| Broadcom              | 5         | 5.49%   |
| Ralink                | 4         | 4.4%    |
| TP-Link               | 2         | 2.2%    |
| Ralink Technology     | 2         | 2.2%    |
| D-Link System         | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 9         | 9.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 7.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 7.61%   |
| Intel Wireless 7265                                                  | 6         | 6.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 5         | 5.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 4.35%   |
| Intel Wireless 8265 / 8275                                           | 4         | 4.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 3.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 2.17%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2         | 2.17%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.17%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.09%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.09%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1         | 1.09%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.09%   |
| Intel Wireless 8260                                                  | 1         | 1.09%   |
| Intel Wireless 7260                                                  | 1         | 1.09%   |
| Intel Wireless 3165                                                  | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.09%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.09%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.09%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 88        | 48.62%  |
| Intel                 | 48        | 26.52%  |
| Broadcom              | 20        | 11.05%  |
| Qualcomm Atheros      | 9         | 4.97%   |
| JMicron Technology    | 5         | 2.76%   |
| Samsung Electronics   | 4         | 2.21%   |
| Nvidia                | 2         | 1.1%    |
| D-Link System         | 2         | 1.1%    |
| MediaTek              | 1         | 0.55%   |
| ICS Advent            | 1         | 0.55%   |
| 3Com                  | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 65        | 34.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 22        | 11.76%  |
| Intel I211 Gigabit Network Connection                                         | 8         | 4.28%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 2.14%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.14%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 2.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 1.6%    |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.6%    |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.6%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 1.07%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.07%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.07%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 1.07%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 1.07%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 1.07%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 1.07%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.53%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.53%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82578DC Gigabit Network Connection                                      | 1         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.53%   |
| Intel 82575GB Gigabit Network Connection                                      | 1         | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.53%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.53%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1         | 0.53%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 0.53%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 0.53%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1         | 0.53%   |
| Broadcom BCM4401-B0 100Base-TX                                                | 1         | 0.53%   |
| 3Com 3c905 100BaseTX [Boomerang]                                              | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 155       | 64.32%  |
| WiFi     | 84        | 34.85%  |
| Modem    | 2         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 146       | 70.19%  |
| WiFi     | 62        | 29.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 52.1%   |
| 1     | 42        | 25.15%  |
| 4     | 19        | 11.38%  |
| 3     | 12        | 7.19%   |
| 6     | 3         | 1.8%    |
| 5     | 3         | 1.8%    |
| 8     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 158       | 93.49%  |
| Yes  | 11        | 6.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 38.89%  |
| Qualcomm Atheros Communications | 14        | 25.93%  |
| Broadcom                        | 4         | 7.41%   |
| Apple                           | 4         | 7.41%   |
| Realtek Semiconductor           | 3         | 5.56%   |
| Lite-On Technology              | 3         | 5.56%   |
| Foxconn / Hon Hai               | 2         | 3.7%    |
| IMC Networks                    | 1         | 1.85%   |
| Dell                            | 1         | 1.85%   |
| Cambridge Silicon Radio         | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 18.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 11.11%  |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 9.26%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 7.41%   |
| Realtek  Bluetooth Adapter                                  | 2         | 3.7%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 3.7%    |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 2         | 3.7%    |
| Intel AX201 Bluetooth                                       | 2         | 3.7%    |
| Intel AX200 Bluetooth                                       | 2         | 3.7%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 3.7%    |
| Apple Bluetooth Host Controller                             | 2         | 3.7%    |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.85%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.85%   |
| IMC Networks Bluetooth Module                               | 1         | 1.85%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.85%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.85%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.85%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.85%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 122       | 69.32%  |
| AMD                                             | 26        | 14.77%  |
| Nvidia                                          | 19        | 10.8%   |
| C-Media Electronics                             | 3         | 1.7%    |
| M-Audio                                         | 1         | 0.57%   |
| Logitech                                        | 1         | 0.57%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.57%   |
| Lenovo                                          | 1         | 0.57%   |
| Generalplus Technology                          | 1         | 0.57%   |
| DSEA A/S                                        | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17        | 8.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.77%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 4.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 4.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 3.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.92%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 1.92%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 1.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.44%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.44%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.96%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.96%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.96%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2         | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.48%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.48%   |
| Logitech H390 headset with microphone                                      | 1         | 0.48%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1         | 0.48%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.48%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.48%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.48%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 0.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.48%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.48%   |
| DSEA A/S Sennheiser 3D G4ME1                                               | 1         | 0.48%   |
| C-Media Electronics Audio Adapter                                          | 1         | 0.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.48%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 39        | 21.79%  |
| Kingston            | 26        | 14.53%  |
| Smart               | 25        | 13.97%  |
| Samsung Electronics | 17        | 9.5%    |
| SK hynix            | 10        | 5.59%   |
| Crucial             | 9         | 5.03%   |
| Teikon              | 8         | 4.47%   |
| A-DATA Technology   | 6         | 3.35%   |
| Micron Technology   | 5         | 2.79%   |
| Smart Brazil        | 4         | 2.23%   |
| High Bridge         | 3         | 1.68%   |
| Hewlett-Packard     | 3         | 1.68%   |
| Apacer              | 3         | 1.68%   |
| Unknown             | 3         | 1.68%   |
| Nanya Technology    | 2         | 1.12%   |
| Corsair             | 2         | 1.12%   |
| Unknown (ABCD)      | 1         | 0.56%   |
| Transcend           | 1         | 0.56%   |
| Tigo                | 1         | 0.56%   |
| RZX                 | 1         | 0.56%   |
| PUSKILL             | 1         | 0.56%   |
| PNY                 | 1         | 0.56%   |
| Multilaser          | 1         | 0.56%   |
| Kreton              | 1         | 0.56%   |
| Goldenmars          | 1         | 0.56%   |
| G.Skill             | 1         | 0.56%   |
| CSX                 | 1         | 0.56%   |
| Atermiter           | 1         | 0.56%   |
| 019400000A07        | 1         | 0.56%   |
| 0194000000CE        | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                                | 4         | 2.07%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.07%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 3         | 1.55%   |
| Unknown                                                          | 3         | 1.55%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 1.04%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 2         | 1.04%   |
| Unknown RAM Module 2GB DIMM                                      | 2         | 1.04%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s              | 2         | 1.04%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 2         | 1.04%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 2         | 1.04%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s     | 2         | 1.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 1.04%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR2                              | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s                       | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.52%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                             | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                     | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.52%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.52%   |
| Unknown RAM DDR3 8GB 1600MHz 8GB DIMM DDR3 1600MT/s              | 1         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2133MT/s | 1         | 0.52%   |
| Transcend RAM TS256MSK64W3N 2GB DIMM DDR3 1066MT/s               | 1         | 0.52%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.52%   |
| Teikon RAM TMTS8G58DFRBFHC-16 8GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.52%   |
| Teikon RAM TMT41GU6BFR8C-PBHJ 8GB DIMM DDR3 1600MT/s             | 1         | 0.52%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.52%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.52%   |
| Smart RAM SH564568FH8NZQNSCR 2GB DIMM DDR3 1600MT/s              | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 86        | 56.58%  |
| DDR4    | 36        | 23.68%  |
| DDR2    | 11        | 7.24%   |
| SDRAM   | 9         | 5.92%   |
| Unknown | 8         | 5.26%   |
| LPDDR4  | 1         | 0.66%   |
| DDR     | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 78        | 52%     |
| SODIMM       | 71        | 47.33%  |
| Row Of Chips | 1         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 63        | 37.28%  |
| 2048  | 46        | 27.22%  |
| 8192  | 44        | 26.04%  |
| 16384 | 13        | 7.69%   |
| 1024  | 3         | 1.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 28.05%  |
| 1333    | 33        | 20.12%  |
| 2400    | 17        | 10.37%  |
| Unknown | 13        | 7.93%   |
| 2667    | 12        | 7.32%   |
| 1334    | 8         | 4.88%   |
| 2133    | 7         | 4.27%   |
| 800     | 6         | 3.66%   |
| 1066    | 4         | 2.44%   |
| 2666    | 3         | 1.83%   |
| 1067    | 3         | 1.83%   |
| 667     | 3         | 1.83%   |
| 1866    | 2         | 1.22%   |
| 533     | 2         | 1.22%   |
| 400     | 2         | 1.22%   |
| 3200    | 1         | 0.61%   |
| 1867    | 1         | 0.61%   |
| 975     | 1         | 0.61%   |

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
| Chicony Electronics           | 15        | 23.81%  |
| Acer                          | 9         | 14.29%  |
| Realtek Semiconductor         | 7         | 11.11%  |
| Silicon Motion                | 5         | 7.94%   |
| Microdia                      | 5         | 7.94%   |
| Logitech                      | 3         | 4.76%   |
| IMC Networks                  | 3         | 4.76%   |
| Syntek                        | 2         | 3.17%   |
| Suyin                         | 2         | 3.17%   |
| Sunplus Innovation Technology | 2         | 3.17%   |
| Apple                         | 2         | 3.17%   |
| Alcor Micro                   | 2         | 3.17%   |
| Unknown                       | 1         | 1.59%   |
| Quanta                        | 1         | 1.59%   |
| Luxvisions Innotech Limited   | 1         | 1.59%   |
| Lite-On Technology            | 1         | 1.59%   |
| Lenovo                        | 1         | 1.59%   |
| Aveo Technology               | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Acer Integrated Camera                        | 5         | 7.81%   |
| Silicon Motion Web Camera                     | 4         | 6.25%   |
| Chicony HD WebCam                             | 4         | 6.25%   |
| Realtek Integrated_Webcam_HD                  | 3         | 4.69%   |
| Syntek EasyCamera                             | 2         | 3.13%   |
| Realtek Integrated Webcam                     | 2         | 3.13%   |
| Microdia Dell Laptop Integrated Webcam HD     | 2         | 3.13%   |
| Logitech Webcam C270                          | 2         | 3.13%   |
| Chicony Sony Visual Communication Camera      | 2         | 3.13%   |
| Apple FaceTime HD Camera                      | 2         | 3.13%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 3.13%   |
| Acer HD Webcam                                | 2         | 3.13%   |
| Unknown Realtek PC Camera                     | 1         | 1.56%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.56%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.56%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.56%   |
| Sunplus HD WebCam                             | 1         | 1.56%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.56%   |
| Realtek LG Camera                             | 1         | 1.56%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.56%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.56%   |
| Quanta HD Webcam                              | 1         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.56%   |
| Microdia Integrated Webcam HD                 | 1         | 1.56%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.56%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.56%   |
| Lite-On Integrated Camera                     | 1         | 1.56%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 1.56%   |
| IMC Networks USB Camera                       | 1         | 1.56%   |
| IMC Networks EasyCamera                       | 1         | 1.56%   |
| Chicony Webcam                                | 1         | 1.56%   |
| Chicony VGA WebCam                            | 1         | 1.56%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.56%   |
| Chicony Integrated Camera                     | 1         | 1.56%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.56%   |
| Chicony HP HD Camera                          | 1         | 1.56%   |
| Chicony EasyCamera                            | 1         | 1.56%   |
| Chicony 1.3M Webcam                           | 1         | 1.56%   |
| Aveo USB2.0 Camera                            | 1         | 1.56%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.56%   |
| Acer Lenovo EasyCamera                        | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| Samsung Electronics        | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 18.18%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                             | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 9.09%   |
| Synaptics product 0x00be                                    | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                          | 1         | 9.09%   |
| Samsung Fingerprint Device                                  | 1         | 9.09%   |

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
| 0     | 63        | 37.95%  |
| 1     | 54        | 32.53%  |
| 2     | 23        | 13.86%  |
| 3     | 16        | 9.64%   |
| 5     | 5         | 3.01%   |
| 4     | 5         | 3.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 94        | 53.41%  |
| Card reader              | 26        | 14.77%  |
| Net/wireless             | 21        | 11.93%  |
| Bluetooth                | 17        | 9.66%   |
| Fingerprint reader       | 11        | 6.25%   |
| Sound                    | 5         | 2.84%   |
| Network                  | 1         | 0.57%   |
| Firewire controller      | 1         | 0.57%   |

