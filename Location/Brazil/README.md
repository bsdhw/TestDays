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

Total: 238

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 15        | 8.02%   |
| helloSystem 0.4.0    | 15        | 8.02%   |
| helloSystem 0.6.0    | 14        | 7.49%   |
| helloSystem 0.5.0    | 14        | 7.49%   |
| FreeBSD 13.0         | 7         | 3.74%   |
| OPNsense 21.1.3      | 6         | 3.21%   |
| OPNsense 21.1        | 6         | 3.21%   |
| OPNsense 20.7.8      | 6         | 3.21%   |
| FreeBSD 14.0-CURRENT | 6         | 3.21%   |
| OPNsense 21.1.2      | 5         | 2.67%   |
| OPNsense 21.1.1      | 5         | 2.67%   |
| FreeBSD 13.0-p3      | 4         | 2.14%   |
| FreeBSD 12.1         | 4         | 2.14%   |
| OPNsense 22.1.8      | 3         | 1.6%    |
| OPNsense 21.7.7      | 3         | 1.6%    |
| OPNsense 21.7.1      | 3         | 1.6%    |
| OPNsense 21.1.9      | 3         | 1.6%    |
| OPNsense 21.1.7      | 3         | 1.6%    |
| OPNsense 21.1.6      | 3         | 1.6%    |
| OPNsense 21.1.4      | 3         | 1.6%    |
| helloSystem 0.8.0    | 3         | 1.6%    |
| FreeBSD 13.0-p7      | 3         | 1.6%    |
| FreeBSD 13.0-p4      | 3         | 1.6%    |
| TrueNAS 12.2-p9      | 2         | 1.07%   |
| OPNsense 22.1.7      | 2         | 1.07%   |
| OPNsense 22.1        | 2         | 1.07%   |
| OPNsense 21.1.8      | 2         | 1.07%   |
| OPNsense 21.1.5      | 2         | 1.07%   |
| NomadBSD 5806f915    | 2         | 1.07%   |
| FreeNAS 11.3-p9      | 2         | 1.07%   |
| FreeBSD 13.0-STABLE  | 2         | 1.07%   |
| FreeBSD 13.0-CURRENT | 2         | 1.07%   |
| FreeBSD 12.2-p3      | 2         | 1.07%   |
| FreeBSD 12.2         | 2         | 1.07%   |
| FreeBSD 12.1-p7      | 2         | 1.07%   |
| TrueNAS 12.2-p6      | 1         | 0.53%   |
| TrueNAS 12.2-p12     | 1         | 0.53%   |
| TrueNAS 12.2-p11     | 1         | 0.53%   |
| TrueNAS 12.2-p10     | 1         | 0.53%   |
| pfSense 2.4.5        | 1         | 0.53%   |
| OS108 9.99.68        | 1         | 0.53%   |
| OPNsense 22.1.6      | 1         | 0.53%   |
| OPNsense 22.1.3      | 1         | 0.53%   |
| OPNsense 22.1.2      | 1         | 0.53%   |
| OPNsense 21.7.3      | 1         | 0.53%   |
| OPNsense 21.7.2      | 1         | 0.53%   |
| OPNsense 21.7        | 1         | 0.53%   |
| OPNsense 20.7        | 1         | 0.53%   |
| OpenBSD 7.0          | 1         | 0.53%   |
| OpenBSD 6.9          | 1         | 0.53%   |
| OpenBSD 6.8          | 1         | 0.53%   |
| NetBSD 9.2           | 1         | 0.53%   |
| helloSystem 0.3.0    | 1         | 0.53%   |
| GhostBSD 20.04.02    | 1         | 0.53%   |
| FreeNAS 11.3-p11     | 1         | 0.53%   |
| FreeBSD 13.1         | 1         | 0.53%   |
| FreeBSD 13.0-RC2     | 1         | 0.53%   |
| FreeBSD 12.2-p1      | 1         | 0.53%   |
| FreeBSD 12.1-p11     | 1         | 0.53%   |
| FreeBSD 12.1-p10     | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 57        | 35.4%   |
| OPNsense    | 48        | 29.81%  |
| FreeBSD     | 42        | 26.09%  |
| OpenBSD     | 3         | 1.86%   |
| TrueNAS     | 2         | 1.24%   |
| NomadBSD    | 2         | 1.24%   |
| FreeNAS     | 2         | 1.24%   |
| pfSense     | 1         | 0.62%   |
| OS108       | 1         | 0.62%   |
| NetBSD      | 1         | 0.62%   |
| GhostBSD    | 1         | 0.62%   |
| DragonFly   | 1         | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 154       | 98.72%  |
| i386  | 2         | 1.28%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 57        | 35.63%  |
| Console      | 57        | 35.63%  |
| KDE5         | 12        | 7.5%    |
| XFCE         | 9         | 5.63%   |
| Openbox      | 5         | 3.13%   |
| MATE         | 5         | 3.13%   |
| GNOME        | 5         | 3.13%   |
| TWM          | 3         | 1.88%   |
| i3           | 2         | 1.25%   |
| fvwm         | 2         | 1.25%   |
| Window Maker | 1         | 0.63%   |
| spectrwm     | 1         | 0.63%   |
| LXQt         | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 98        | 62.82%  |
| Console | 58        | 37.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 69        | 43.4%   |
| SLiM    | 64        | 40.25%  |
| SDDM    | 11        | 6.92%   |
| LightDM | 6         | 3.77%   |
| GDM     | 5         | 3.14%   |
| XDM     | 4         | 2.52%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 63        | 39.62%  |
| Unknown         | 61        | 38.36%  |
| C               | 18        | 11.32%  |
| pt_BR           | 14        | 8.81%   |
| fr_FR           | 1         | 0.63%   |
| en_US.ISO8859-1 | 1         | 0.63%   |
| en_GB           | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 125       | 78.62%  |
| BIOS | 34        | 21.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 80        | 49.69%  |
| Ufs     | 68        | 42.24%  |
| Cd9660  | 9         | 5.59%   |
| Ffs     | 3         | 1.86%   |
| Hammer2 | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 142       | 89.87%  |
| MBR     | 14        | 8.86%   |
| Unknown | 2         | 1.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 16.03%  |
| ASUSTek Computer        | 22        | 14.1%   |
| Lenovo                  | 15        | 9.62%   |
| Hewlett-Packard         | 10        | 6.41%   |
| Intel                   | 8         | 5.13%   |
| Acer                    | 8         | 5.13%   |
| Gigabyte Technology     | 6         | 3.85%   |
| AMI                     | 6         | 3.85%   |
| Unknown                 | 6         | 3.85%   |
| Samsung Electronics     | 5         | 3.21%   |
| Itautec                 | 4         | 2.56%   |
| Apple                   | 4         | 2.56%   |
| Positivo                | 3         | 1.92%   |
| MSI                     | 3         | 1.92%   |
| Avell High Performance  | 3         | 1.92%   |
| Sony                    | 2         | 1.28%   |
| Semp Toshiba            | 2         | 1.28%   |
| Pegatron                | 2         | 1.28%   |
| PCWare                  | 2         | 1.28%   |
| Gateway                 | 2         | 1.28%   |
| ECS                     | 2         | 1.28%   |
| ASRock                  | 2         | 1.28%   |
| Yanling                 | 1         | 0.64%   |
| ULTRATOP                | 1         | 0.64%   |
| Procomp Ind. Eletronica | 1         | 0.64%   |
| Philco                  | 1         | 0.64%   |
| Notebook                | 1         | 0.64%   |
| LG Electronics          | 1         | 0.64%   |
| KLLISRE                 | 1         | 0.64%   |
| HC                      | 1         | 0.64%   |
| GALAX                   | 1         | 0.64%   |
| ECS-USA                 | 1         | 0.64%   |
| CNCTION-IAF-E3845       | 1         | 0.64%   |
| Clevo                   | 1         | 0.64%   |
| Biostar                 | 1         | 0.64%   |
| Acidanthera             | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 4.49%   |
| Intel Q3XXG4-P V1.0                         | 5         | 3.21%   |
| AMI Aptio CRB                               | 5         | 3.21%   |
| ASUS All Series                             | 4         | 2.56%   |
| Dell Inspiron 3442                          | 3         | 1.92%   |
| Pegatron IPM41-D3                           | 2         | 1.28%   |
| Gigabyte H61M-S2-B3                         | 2         | 1.28%   |
| Gateway NE56R                               | 2         | 1.28%   |
| ASUS PRIME B450M-GAMING/BR                  | 2         | 1.28%   |
| ASUS P8H61-M LX3 PLUS R2.0                  | 2         | 1.28%   |
| ASUS M5A78L-M LX/BR                         | 2         | 1.28%   |
| Acer Aspire 5750                            | 2         | 1.28%   |
| Yanling NS-1U8L                             | 1         | 0.64%   |
| ULTRATOP C2017-LIVA-ZE                      | 1         | 0.64%   |
| Sony VPCYB45JB                              | 1         | 0.64%   |
| Sony VPCEG17FB                              | 1         | 0.64%   |
| Semp Toshiba STI NA 1401                    | 1         | 0.64%   |
| Semp Toshiba STI                            | 1         | 0.64%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.64%   |
| Samsung 530XBB                              | 1         | 0.64%   |
| Samsung 340XAA/350XAA/550XAA                | 1         | 0.64%   |
| Samsung 300E5M/300E5L                       | 1         | 0.64%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 0.64%   |
| Procomp Ind. Eletronica G41MXE              | 1         | 0.64%   |
| Positivo POS-PIQ77CL                        | 1         | 0.64%   |
| Positivo POS-EAA75DE                        | 1         | 0.64%   |
| Positivo C14CR01                            | 1         | 0.64%   |
| Philco 10B                                  | 1         | 0.64%   |
| PCWare PW-945GCX                            | 1         | 0.64%   |
| PCWare IPX1800G2                            | 1         | 0.64%   |
| Notebook N85_N87HCHNHZ                      | 1         | 0.64%   |
| MSI U-100                                   | 1         | 0.64%   |
| MSI MS-7877                                 | 1         | 0.64%   |
| MSI MS-7698                                 | 1         | 0.64%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.64%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.64%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 0.64%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 0.64%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 0.64%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 0.64%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 0.64%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 0.64%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 0.64%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 0.64%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 0.64%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT           | 1         | 0.64%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 0.64%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 0.64%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 0.64%   |
| Lenovo G550 2958                            | 1         | 0.64%   |
| KLLISRE X99-B5 V1.0                         | 1         | 0.64%   |
| Itautec Infoway w7535                       | 1         | 0.64%   |
| Itautec Infoway w7530                       | 1         | 0.64%   |
| Itautec Infoway ST-4344                     | 1         | 0.64%   |
| Itautec Infoway                             | 1         | 0.64%   |
| Intel H61                                   | 1         | 0.64%   |
| Intel H55                                   | 1         | 0.64%   |
| Intel DH61WW AAG23116-206                   | 1         | 0.64%   |
| HP Z230 Tower Workstation                   | 1         | 0.64%   |
| HP ProLiant ML350 G6                        | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 11        | 7.05%   |
| Lenovo ThinkPad                | 10        | 6.41%   |
| Acer Aspire                    | 7         | 4.49%   |
| Unknown                        | 7         | 4.49%   |
| AMI Aptio                      | 6         | 3.85%   |
| Intel Q3XXG4-P                 | 5         | 3.21%   |
| HP ProLiant                    | 5         | 3.21%   |
| Itautec Infoway                | 4         | 2.56%   |
| Dell PowerEdge                 | 4         | 2.56%   |
| Dell OptiPlex                  | 4         | 2.56%   |
| ASUS All                       | 4         | 2.56%   |
| Lenovo IdeaPad                 | 3         | 1.92%   |
| Dell Vostro                    | 3         | 1.92%   |
| ASUS PRIME                     | 3         | 1.92%   |
| ASUS M5A78L-M                  | 3         | 1.92%   |
| Semp Toshiba STI               | 2         | 1.28%   |
| Pegatron IPM41-D3              | 2         | 1.28%   |
| Gigabyte H61M-S2-B3            | 2         | 1.28%   |
| Gateway NE56R                  | 2         | 1.28%   |
| Dell Latitude                  | 2         | 1.28%   |
| Avell High Performance A62     | 2         | 1.28%   |
| ASUS P8H61-M                   | 2         | 1.28%   |
| Yanling NS-1U8L                | 1         | 0.64%   |
| ULTRATOP C2017-LIVA-ZE         | 1         | 0.64%   |
| Sony VPCYB45JB                 | 1         | 0.64%   |
| Sony VPCEG17FB                 | 1         | 0.64%   |
| Samsung RV411                  | 1         | 0.64%   |
| Samsung 530XBB                 | 1         | 0.64%   |
| Samsung 340XAA                 | 1         | 0.64%   |
| Samsung 300E5M                 | 1         | 0.64%   |
| Samsung 270E5K                 | 1         | 0.64%   |
| Procomp Ind. Eletronica G41MXE | 1         | 0.64%   |
| Positivo POS-PIQ77CL           | 1         | 0.64%   |
| Positivo POS-EAA75DE           | 1         | 0.64%   |
| Positivo C14CR01               | 1         | 0.64%   |
| Philco 10B                     | 1         | 0.64%   |
| PCWare PW-945GCX               | 1         | 0.64%   |
| PCWare IPX1800G2               | 1         | 0.64%   |
| Notebook N85                   | 1         | 0.64%   |
| MSI U-100                      | 1         | 0.64%   |
| MSI MS-7877                    | 1         | 0.64%   |
| MSI MS-7698                    | 1         | 0.64%   |
| LG 14Z980-G.BH51P1             | 1         | 0.64%   |
| Lenovo IdeaPadFlex             | 1         | 0.64%   |
| Lenovo G550                    | 1         | 0.64%   |
| KLLISRE X99-B5                 | 1         | 0.64%   |
| Intel H61                      | 1         | 0.64%   |
| Intel H55                      | 1         | 0.64%   |
| Intel DH61WW                   | 1         | 0.64%   |
| HP Z230                        | 1         | 0.64%   |
| HP EliteDesk                   | 1         | 0.64%   |
| HP EliteBook                   | 1         | 0.64%   |
| HP Compaq                      | 1         | 0.64%   |
| HP 14                          | 1         | 0.64%   |
| HC HCAR357-MI                  | 1         | 0.64%   |
| Gigabyte G41MT-S2              | 1         | 0.64%   |
| Gigabyte C847N                 | 1         | 0.64%   |
| Gigabyte AB350M-Gaming         | 1         | 0.64%   |
| Gigabyte 970A-UD3P             | 1         | 0.64%   |
| GALAX B365M                    | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 18        | 11.54%  |
| 2016    | 18        | 11.54%  |
| 2013    | 17        | 10.9%   |
| 2019    | 16        | 10.26%  |
| 2020    | 14        | 8.97%   |
| 2011    | 13        | 8.33%   |
| 2010    | 10        | 6.41%   |
| 2009    | 10        | 6.41%   |
| 2017    | 7         | 4.49%   |
| 2015    | 7         | 4.49%   |
| 2014    | 7         | 4.49%   |
| 2012    | 7         | 4.49%   |
| 2021    | 5         | 3.21%   |
| 2008    | 3         | 1.92%   |
| Unknown | 2         | 1.28%   |
| 2022    | 1         | 0.64%   |
| 2007    | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 78        | 50%     |
| Notebook    | 61        | 39.1%   |
| Mini pc     | 7         | 4.49%   |
| Server      | 5         | 3.21%   |
| All in one  | 3         | 1.92%   |
| Convertible | 2         | 1.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 156       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 36.71%  |
| 8.01-16.0   | 58        | 36.71%  |
| 16.01-24.0  | 23        | 14.56%  |
| 2.01-3.0    | 9         | 5.7%    |
| 32.01-64.0  | 6         | 3.8%    |
| 24.01-32.0  | 2         | 1.27%   |
| 3.01-4.0    | 1         | 0.63%   |
| 64.01-256.0 | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 103       | 64.78%  |
| 0.51-1.0   | 41        | 25.79%  |
| 1.01-2.0   | 8         | 5.03%   |
| 4.01-8.0   | 2         | 1.26%   |
| Unknown    | 2         | 1.26%   |
| 32.01-64.0 | 1         | 0.63%   |
| 24.01-32.0 | 1         | 0.63%   |
| 16.01-24.0 | 1         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 67.08%  |
| 2      | 31        | 19.25%  |
| 0      | 10        | 6.21%   |
| 3      | 6         | 3.73%   |
| 5      | 2         | 1.24%   |
| 4      | 2         | 1.24%   |
| 7      | 1         | 0.62%   |
| 6      | 1         | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 69.87%  |
| Yes       | 47        | 30.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 93.59%  |
| No        | 10        | 6.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 50%     |
| No        | 78        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 108       | 69.23%  |
| Yes       | 48        | 30.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 156       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| SГЈo Paulo              | 19        | 10.86%  |
| Rio de Janeiro            | 12        | 6.86%   |
| Curitiba                  | 8         | 4.57%   |
| SÃ£o Paulo              | 6         | 3.43%   |
| Manaus                    | 4         | 2.29%   |
| SГЈo JosГ© dos Campos | 3         | 1.71%   |
| Sao Paulo                 | 3         | 1.71%   |
| Porto Alegre              | 3         | 1.71%   |
| JoГЈo Pessoa            | 3         | 1.71%   |
| Campinas                  | 3         | 1.71%   |
| Belo Horizonte            | 3         | 1.71%   |
| Teresina                  | 2         | 1.14%   |
| Serra                     | 2         | 1.14%   |
| Sao Vicente               | 2         | 1.14%   |
| RondonГіpolis           | 2         | 1.14%   |
| Rio Claro                 | 2         | 1.14%   |
| Pirapora                  | 2         | 1.14%   |
| Novo Hamburgo             | 2         | 1.14%   |
| Maraba                    | 2         | 1.14%   |
| JundiaГ­                | 2         | 1.14%   |
| Ipojuca                   | 2         | 1.14%   |
| Franca                    | 2         | 1.14%   |
| CuiabГЎ                 | 2         | 1.14%   |
| BrasГ­lia               | 2         | 1.14%   |
| BrasÃ­lia               | 2         | 1.14%   |
| Boa Vista do Jauato       | 2         | 1.14%   |
| VitГіria da Conquista   | 1         | 0.57%   |
| VitГіria                | 1         | 0.57%   |
| Visconde do Rio Branco    | 1         | 0.57%   |
| Urupes                    | 1         | 0.57%   |
| Unai                      | 1         | 0.57%   |
| Uberaba                   | 1         | 0.57%   |
| Teresopolis               | 1         | 0.57%   |
| Taubate                   | 1         | 0.57%   |
| Tangara                   | 1         | 0.57%   |
| Sao Jose                  | 1         | 0.57%   |
| Sao Jeronimo da Serra     | 1         | 0.57%   |
| Santa Maria               | 1         | 0.57%   |
| Rio Grande da Serra       | 1         | 0.57%   |
| Rio das Ostras            | 1         | 0.57%   |
| Reriutaba                 | 1         | 0.57%   |
| Porto UniГЈo            | 1         | 0.57%   |
| Piracicaba                | 1         | 0.57%   |
| Piloezinhos               | 1         | 0.57%   |
| Pelotas                   | 1         | 0.57%   |
| Patos de Minas            | 1         | 0.57%   |
| Pato Branco               | 1         | 0.57%   |
| Paracuru                  | 1         | 0.57%   |
| Osasco                    | 1         | 0.57%   |
| Novo Horizonte do Norte   | 1         | 0.57%   |
| Morungaba                 | 1         | 0.57%   |
| Monte Belo                | 1         | 0.57%   |
| Marica                    | 1         | 0.57%   |
| Mage                      | 1         | 0.57%   |
| Macatuba                  | 1         | 0.57%   |
| Londrina                  | 1         | 0.57%   |
| Lavras                    | 1         | 0.57%   |
| Lajeado                   | 1         | 0.57%   |
| Jundiaí                  | 1         | 0.57%   |
| JundiaÃ­                | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 46     | 19.29%  |
| Seagate             | 33        | 82     | 16.75%  |
| Kingston            | 30        | 39     | 15.23%  |
| Samsung Electronics | 19        | 20     | 9.64%   |
| Toshiba             | 12        | 12     | 6.09%   |
| SanDisk             | 9         | 9      | 4.57%   |
| A-DATA Technology   | 8         | 8      | 4.06%   |
| Crucial             | 7         | 9      | 3.55%   |
| LITEON              | 4         | 4      | 2.03%   |
| KingSpec            | 4         | 4      | 2.03%   |
| Hoodisk             | 4         | 4      | 2.03%   |
| Hitachi             | 4         | 6      | 2.03%   |
| China               | 4         | 7      | 2.03%   |
| SK hynix            | 3         | 3      | 1.52%   |
| Silicon Motion      | 3         | 3      | 1.52%   |
| Hewlett-Packard     | 2         | 3      | 1.02%   |
| XrayDisk            | 1         | 1      | 0.51%   |
| Transcend           | 1         | 2      | 0.51%   |
| SSSTC               | 1         | 1      | 0.51%   |
| Smart               | 1         | 1      | 0.51%   |
| Patriot             | 1         | 4      | 0.51%   |
| NTC                 | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| Kston               | 1         | 1      | 0.51%   |
| Hikvision           | 1         | 1      | 0.51%   |
| HGST                | 1         | 2      | 0.51%   |
| Gigabyte Technology | 1         | 1      | 0.51%   |
| Faspeed             | 1         | 1      | 0.51%   |
| Drevo               | 1         | 3      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 8         | 3.76%   |
| Kingston SA400S37120G 120GB         | 7         | 3.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.88%   |
| Kingston SA400S37480G 480GB         | 4         | 1.88%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3         | 1.41%   |
| Toshiba MQ01ABD100 1TB              | 3         | 1.41%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.41%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.41%   |
| SanDisk SDSSDA240G 240GB            | 3         | 1.41%   |
| Samsung HD322HJ 320GB               | 3         | 1.41%   |
| Kingston SA400S37960G 960GB         | 3         | 1.41%   |
| A-DATA SU630 240GB                  | 3         | 1.41%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.94%   |
| Silicon Motion NE-256 256GB         | 2         | 0.94%   |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 0.94%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.94%   |
| SanDisk SSD PLUS 120GB              | 2         | 0.94%   |
| Samsung HD502HJ 500GB               | 2         | 0.94%   |
| Samsung HD161HJ 160GB               | 2         | 0.94%   |
| Kingston SUV400S37120G 120GB        | 2         | 0.94%   |
| KingSpec MT-128 128GB               | 2         | 0.94%   |
| Hoodisk SSD 64GB                    | 2         | 0.94%   |
| Hoodisk SSD 32GB                    | 2         | 0.94%   |
| China SATA SSD 120GB                | 2         | 0.94%   |
| XrayDisk SSD 128GB                  | 1         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 0.47%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.47%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.47%   |
| WDC WD5000B 500GB                   | 1         | 0.47%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 0.47%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 0.47%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 0.47%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 0.47%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 0.47%   |
| WDC WD400BD-75LRA0 40GB             | 1         | 0.47%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.47%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 0.47%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 0.47%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 0.47%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 1         | 0.47%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 0.47%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1         | 0.47%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 1         | 0.47%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 0.47%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.47%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.47%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.47%   |
| WDC WD1600AVJS-63WNA0 160GB         | 1         | 0.47%   |
| WDC WD1200BEVT-22ZCT0 120GB         | 1         | 0.47%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.47%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.47%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 0.47%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.47%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.47%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 41     | 34.34%  |
| Seagate             | 33        | 82     | 33.33%  |
| Samsung Electronics | 14        | 15     | 14.14%  |
| Toshiba             | 11        | 11     | 11.11%  |
| Hitachi             | 4         | 6      | 4.04%   |
| Hewlett-Packard     | 2         | 3      | 2.02%   |
| HGST                | 1         | 2      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 29        | 38     | 34.12%  |
| SanDisk             | 9         | 9      | 10.59%  |
| Crucial             | 6         | 8      | 7.06%   |
| WDC                 | 5         | 5      | 5.88%   |
| Samsung Electronics | 4         | 4      | 4.71%   |
| LITEON              | 4         | 4      | 4.71%   |
| KingSpec            | 4         | 4      | 4.71%   |
| Hoodisk             | 4         | 4      | 4.71%   |
| China               | 4         | 7      | 4.71%   |
| A-DATA Technology   | 4         | 4      | 4.71%   |
| SK hynix            | 2         | 2      | 2.35%   |
| XrayDisk            | 1         | 1      | 1.18%   |
| Transcend           | 1         | 2      | 1.18%   |
| Smart               | 1         | 1      | 1.18%   |
| Patriot             | 1         | 4      | 1.18%   |
| NTC                 | 1         | 1      | 1.18%   |
| Kston               | 1         | 1      | 1.18%   |
| Hikvision           | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 1      | 1.18%   |
| Faspeed             | 1         | 1      | 1.18%   |
| Drevo               | 1         | 3      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 84        | 160    | 48%     |
| SSD  | 77        | 105    | 44%     |
| NVMe | 14        | 14     | 8%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 136       | 265    | 90.67%  |
| NVMe | 14        | 14     | 9.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 116       | 169    | 72.5%   |
| 0.51-1.0   | 33        | 49     | 20.63%  |
| 1.01-2.0   | 7         | 15     | 4.38%   |
| 3.01-4.0   | 4         | 32     | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 41        | 24.26%  |
| 101-250        | 40        | 23.67%  |
| 251-500        | 31        | 18.34%  |
| 21-50          | 18        | 10.65%  |
| 51-100         | 16        | 9.47%   |
| 501-1000       | 14        | 8.28%   |
| 1001-2000      | 5         | 2.96%   |
| 2001-3000      | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |
| Unknown        | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 133       | 84.71%  |
| 21-50     | 12        | 7.64%   |
| 101-250   | 5         | 3.18%   |
| 501-1000  | 4         | 2.55%   |
| 2001-3000 | 1         | 0.64%   |
| 51-100    | 1         | 0.64%   |
| Unknown   | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3         | 3      | 5.56%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 2      | 3.7%    |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 3.7%    |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 3.7%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.85%   |
| WDC WD5000B 500GB                   | 1         | 1      | 1.85%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.85%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 1.85%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 1.85%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 1.85%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 1.85%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 1.85%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 1.85%   |
| Transcend TS32GMSM610 32GB          | 1         | 2      | 1.85%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.85%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.85%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 1.85%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 1.85%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 1.85%   |
| Seagate ST9320325ASG 320GB          | 1         | 1      | 1.85%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 1.85%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.85%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.85%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.85%   |
| Seagate ST500DM002-1BC142 500GB     | 1         | 1      | 1.85%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.85%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.85%   |
| Seagate ST31000528AS 1TB            | 1         | 1      | 1.85%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 1.85%   |
| Seagate ST2000DM001-1E6164 2TB      | 1         | 1      | 1.85%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 9      | 1.85%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1      | 1.85%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1      | 1.85%   |
| SanDisk SSD PLUS 240 GB             | 1         | 1      | 1.85%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 1.85%   |
| Samsung Electronics HD642JJ 640GB   | 1         | 1      | 1.85%   |
| Samsung Electronics HD502HJ 500GB   | 1         | 1      | 1.85%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1      | 1.85%   |
| KingSpec P3-128 128GB               | 1         | 1      | 1.85%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 1.85%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 1.85%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 2      | 1.85%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 2      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 24     | 31.37%  |
| WDC                 | 13        | 15     | 25.49%  |
| Samsung Electronics | 7         | 8      | 13.73%  |
| Toshiba             | 6         | 6      | 11.76%  |
| Hitachi             | 4         | 6      | 7.84%   |
| Transcend           | 1         | 2      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| SanDisk             | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 24     | 34.78%  |
| WDC                 | 13        | 15     | 28.26%  |
| Samsung Electronics | 7         | 8      | 15.22%  |
| Toshiba             | 6         | 6      | 13.04%  |
| Hitachi             | 4         | 6      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 59     | 89.13%  |
| SSD  | 5         | 6      | 10.87%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 118       | 207    | 69.82%  |
| Malfunc  | 46        | 65     | 27.22%  |
| Detected | 4         | 6      | 2.37%   |
| Failed   | 1         | 1      | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 130       | 75.58%  |
| AMD                            | 19        | 11.05%  |
| Silicon Motion                 | 5         | 2.91%   |
| Nvidia                         | 3         | 1.74%   |
| ADATA Technology               | 3         | 1.74%   |
| Broadcom / LSI                 | 2         | 1.16%   |
| Toshiba                        | 1         | 0.58%   |
| Solid State Storage Technology | 1         | 0.58%   |
| SK hynix                       | 1         | 0.58%   |
| Samsung Electronics            | 1         | 0.58%   |
| Realtek Semiconductor          | 1         | 0.58%   |
| Micron/Crucial Technology      | 1         | 0.58%   |
| Kingston Technology Company    | 1         | 0.58%   |
| Integrated Technology Express  | 1         | 0.58%   |
| Hewlett-Packard                | 1         | 0.58%   |
| Adaptec                        | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14        | 7%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 6%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 5%      |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 4.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 4.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 3.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 3%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.5%    |
| Unknown                                                                                 | 5         | 2.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.5%    |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 1%      |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1%      |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1%      |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1%      |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.5%    |
| SK hynix BC511                                                                          | 1         | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.5%    |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.5%    |
| Nvidia MCP61 IDE                                                                        | 1         | 0.5%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.5%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.5%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.5%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.5%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                                 | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.5%    |
| Integrated Express IT8213 IDE Controller                                                | 1         | 0.5%    |
| HP Smart Array G6 controllers                                                           | 1         | 0.5%    |
| Broadcom / LSI MegaRAID SAS-3 3008 [Fury]                                               | 1         | 0.5%    |
| Broadcom / LSI MegaRAID SAS 1078                                                        | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 67.61%  |
| IDE  | 33        | 18.75%  |
| NVMe | 15        | 8.52%   |
| RAID | 8         | 4.55%   |
| SCSI | 1         | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 136       | 87.18%  |
| AMD    | 20        | 12.82%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 5         | 3.18%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4         | 2.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.91%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 1.27%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.27%   |
| Intel CPU Version                           | 2         | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.27%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.27%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.27%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2         | 1.27%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.27%   |
| Intel Core i3-2100 CPU                      | 2         | 1.27%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.27%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 1.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.27%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 2         | 1.27%   |
| AMD FX-8320E Eight-Core Processor           | 2         | 1.27%   |
| Intel Xeon E-2224 CPU @ 3.40GHz             | 1         | 0.64%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.64%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.64%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.64%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 0.64%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.64%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz         | 1         | 0.64%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz         | 1         | 0.64%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.64%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.64%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.64%   |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1         | 0.64%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.64%   |
| Intel Genuine CPU                           | 1         | 0.64%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.64%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.64%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.64%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.64%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 21.15%  |
| Intel Core i3           | 25        | 16.03%  |
| Intel Core i7           | 18        | 11.54%  |
| Intel Celeron           | 18        | 11.54%  |
| Intel Xeon              | 11        | 7.05%   |
| Intel Core 2 Duo        | 8         | 5.13%   |
| Intel Pentium Dual-Core | 6         | 3.85%   |
| AMD FX                  | 6         | 3.85%   |
| Intel Atom              | 5         | 3.21%   |
| Intel Pentium           | 4         | 2.56%   |
| AMD Ryzen 5             | 4         | 2.56%   |
| Other                   | 3         | 1.92%   |
| Intel Core 2 Quad       | 2         | 1.28%   |
| AMD E                   | 2         | 1.28%   |
| Intel Genuine           | 1         | 0.64%   |
| Intel Core M            | 1         | 0.64%   |
| Intel Core 2            | 1         | 0.64%   |
| AMD Turion II Neo       | 1         | 0.64%   |
| AMD Ryzen 7             | 1         | 0.64%   |
| AMD Ryzen 3             | 1         | 0.64%   |
| AMD PRO A8              | 1         | 0.64%   |
| AMD Phenom              | 1         | 0.64%   |
| AMD E1                  | 1         | 0.64%   |
| AMD C-60                | 1         | 0.64%   |
| AMD A10                 | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 83        | 52.87%  |
| 4       | 44        | 28.03%  |
| 8       | 10        | 6.37%   |
| 6       | 9         | 5.73%   |
| Unknown | 6         | 3.82%   |
| 12      | 3         | 1.91%   |
| 1       | 2         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 152       | 97.44%  |
| 2      | 4         | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 77        | 49.04%  |
| 2       | 74        | 47.13%  |
| Unknown | 6         | 3.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 15.92%  |
| SandyBridge   | 19        | 12.1%   |
| Penryn        | 17        | 10.83%  |
| Haswell       | 15        | 9.55%   |
| IvyBridge     | 13        | 8.28%   |
| Silvermont    | 12        | 7.64%   |
| Broadwell     | 8         | 5.1%    |
| Westmere      | 6         | 3.82%   |
| Piledriver    | 5         | 3.18%   |
| Zen+          | 4         | 2.55%   |
| Skylake       | 4         | 2.55%   |
| Bobcat        | 4         | 2.55%   |
| Nehalem       | 3         | 1.91%   |
| Goldmont      | 3         | 1.91%   |
| Core          | 3         | 1.91%   |
| Bonnell       | 3         | 1.91%   |
| Steamroller   | 2         | 1.27%   |
| K10           | 2         | 1.27%   |
| Goldmont plus | 2         | 1.27%   |
| CometLake     | 2         | 1.27%   |
| Zen 2         | 1         | 0.64%   |
| Zen           | 1         | 0.64%   |
| TigerLake     | 1         | 0.64%   |
| Bulldozer     | 1         | 0.64%   |
| Unknown       | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 114       | 65.14%  |
| Nvidia                     | 28        | 16%     |
| AMD                        | 25        | 14.29%  |
| Matrox Electronics Systems | 7         | 4%      |
| ASPEED Technology          | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 17        | 9.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 12        | 6.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 9         | 5.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 8         | 4.49%   |
| Intel HD Graphics 5500                                                             | 7         | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 6         | 3.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 5         | 2.81%   |
| Intel UHD Graphics 620                                                             | 5         | 2.81%   |
| Intel Core Processor Integrated Graphics Controller                                | 5         | 2.81%   |
| Nvidia GK208B [GeForce GT 710]                                                     | 3         | 1.69%   |
| Matrox Electronics Systems MGA G200EH                                              | 3         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 3         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 3         | 1.69%   |
| Intel HD Graphics 630                                                              | 3         | 1.69%   |
| Intel HD Graphics 620                                                              | 3         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                          | 3         | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                             | 3         | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                         | 3         | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 3         | 1.69%   |
| Nvidia TU117M                                                                      | 2         | 1.12%   |
| Nvidia GP108M [GeForce MX250]                                                      | 2         | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                 | 2         | 1.12%   |
| Nvidia GM108M [GeForce MX130]                                                      | 2         | 1.12%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 2         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller        | 2         | 1.12%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                         | 2         | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 2         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.12%   |
| Intel HD Graphics 500                                                              | 2         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 2         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 2         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                               | 2         | 1.12%   |
| AMD RV710 [Radeon HD 4350/4550]                                                    | 2         | 1.12%   |
| AMD RS780L [Radeon 3000]                                                           | 2         | 1.12%   |
| AMD Kaveri [Radeon R7 Graphics]                                                    | 2         | 1.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                         | 1         | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                         | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX230]                                                      | 1         | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                | 1         | 0.56%   |
| Nvidia GM108M [GeForce MX110]                                                      | 1         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                      | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 950M]                                                   | 1         | 0.56%   |
| Nvidia GK208M [GeForce GT 740M]                                                    | 1         | 0.56%   |
| Nvidia GK208BM [GeForce 920M]                                                      | 1         | 0.56%   |
| Nvidia GK107GL [Quadro K2000]                                                      | 1         | 0.56%   |
| Nvidia GF119M [GeForce 410M]                                                       | 1         | 0.56%   |
| Nvidia GF119 [GeForce GT 610]                                                      | 1         | 0.56%   |
| Nvidia GF108 [GeForce GT 430]                                                      | 1         | 0.56%   |
| Nvidia GF106 [GeForce GTS 450]                                                     | 1         | 0.56%   |
| Nvidia G86 [GeForce 8500 GT]                                                       | 1         | 0.56%   |
| Nvidia C79 [GeForce 9400]                                                          | 1         | 0.56%   |
| Nvidia C79 [GeForce 9400M]                                                         | 1         | 0.56%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller           | 1         | 0.56%   |
| Matrox Electronics Systems G200eR2                                                 | 1         | 0.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 1         | 0.56%   |
| Intel HD Graphics 5300                                                             | 1         | 0.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 1         | 0.56%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                      | 1         | 0.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 0.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller            | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 56.69%  |
| 1 x AMD        | 21        | 13.38%  |
| 1 x Nvidia     | 14        | 8.92%   |
| Intel + Nvidia | 14        | 8.92%   |
| 2 x Intel      | 7         | 4.46%   |
| 1 x Matrox     | 7         | 4.46%   |
| Intel + AMD    | 4         | 2.55%   |
| 1 x ASPEED     | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 144       | 91.72%  |
| Proprietary | 12        | 7.64%   |
| Unknown     | 1         | 0.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 83.65%  |
| 3.01-4.0   | 8         | 5.03%   |
| 0.01-0.5   | 7         | 4.4%    |
| 0.51-1.0   | 5         | 3.14%   |
| 1.01-2.0   | 4         | 2.52%   |
| 7.01-8.0   | 1         | 0.63%   |
| 2.01-3.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 19.1%   |
| Samsung Electronics | 14        | 15.73%  |
| Goldstar            | 11        | 12.36%  |
| LG Display          | 10        | 11.24%  |
| BOE                 | 7         | 7.87%   |
| Chimei Innolux      | 5         | 5.62%   |
| AOC                 | 5         | 5.62%   |
| Lenovo              | 3         | 3.37%   |
| InfoVision          | 3         | 3.37%   |
| Dell                | 3         | 3.37%   |
| Philips             | 2         | 2.25%   |
| Hewlett-Packard     | 2         | 2.25%   |
| Apple               | 2         | 2.25%   |
| VIE                 | 1         | 1.12%   |
| PANDA               | 1         | 1.12%   |
| Panasonic           | 1         | 1.12%   |
| LG Electronics      | 1         | 1.12%   |
| ASUSTek Computer    | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.35%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 3.26%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.17%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 1.09%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 1.09%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.09%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 1.09%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.09%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.09%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                     | 1         | 1.09%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                     | 1         | 1.09%   |
| LG Electronics LCD Monitor 23MP55                                     | 1         | 1.09%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.09%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch              | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.09%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.09%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.09%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.09%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.09%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch            | 1         | 1.09%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                   | 1         | 1.09%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 1.09%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                   | 1         | 1.09%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch            | 1         | 1.09%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                 | 1         | 1.09%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                 | 1         | 1.09%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                  | 1         | 1.09%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                  | 1         | 1.09%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                 | 1         | 1.09%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                 | 1         | 1.09%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 1         | 1.09%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.09%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.09%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch       | 1         | 1.09%   |
| BOE LCD Monitor BOE08D6 1920x1080 310x170mm 13.9-inch                 | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 40.45%  |
| 1920x1080 (FHD)    | 30        | 33.71%  |
| 1600x900 (HD+)     | 6         | 6.74%   |
| 1440x900 (WXGA+)   | 3         | 3.37%   |
| 1280x1024 (SXGA)   | 3         | 3.37%   |
| 1280x800 (WXGA)    | 2         | 2.25%   |
| 1024x768 (XGA)     | 2         | 2.25%   |
| 3640x1920          | 1         | 1.12%   |
| 2560x1440 (QHD)    | 1         | 1.12%   |
| 1680x1050 (WSXGA+) | 1         | 1.12%   |
| 1360x768           | 1         | 1.12%   |
| 1280x720 (HD)      | 1         | 1.12%   |
| 1024x600           | 1         | 1.12%   |
| Unknown            | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 25        | 27.78%  |
| 15      | 20        | 22.22%  |
| 19      | 7         | 7.78%   |
| 24      | 6         | 6.67%   |
| 23      | 5         | 5.56%   |
| 21      | 5         | 5.56%   |
| 18      | 5         | 5.56%   |
| 12      | 4         | 4.44%   |
| Unknown | 4         | 4.44%   |
| 20      | 3         | 3.33%   |
| 14      | 2         | 2.22%   |
| 31      | 1         | 1.11%   |
| 17      | 1         | 1.11%   |
| 11      | 1         | 1.11%   |
| 10      | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 48.31%  |
| 401-500     | 18        | 20.22%  |
| 501-600     | 11        | 12.36%  |
| 201-300     | 11        | 12.36%  |
| Unknown     | 4         | 4.49%   |
| 601-700     | 1         | 1.12%   |
| 351-400     | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 67        | 81.71%  |
| 16/10   | 7         | 8.54%   |
| 4/3     | 3         | 3.66%   |
| 5/4     | 2         | 2.44%   |
| Unknown | 2         | 2.44%   |
| 3/2     | 1         | 1.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 24        | 26.67%  |
| 91-100         | 19        | 21.11%  |
| 201-250        | 16        | 17.78%  |
| 151-200        | 10        | 11.11%  |
| 141-150        | 6         | 6.67%   |
| 61-70          | 4         | 4.44%   |
| Unknown        | 4         | 4.44%   |
| 101-110        | 2         | 2.22%   |
| 71-80          | 1         | 1.11%   |
| 51-60          | 1         | 1.11%   |
| 351-500        | 1         | 1.11%   |
| 41-50          | 1         | 1.11%   |
| 111-120        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 37        | 42.05%  |
| 51-100  | 29        | 32.95%  |
| 121-160 | 14        | 15.91%  |
| Unknown | 4         | 4.55%   |
| 161-240 | 3         | 3.41%   |
| 1-50    | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 49.04%  |
| 0     | 70        | 44.59%  |
| 2     | 10        | 6.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 89        | 38.7%   |
| Intel                 | 61        | 26.52%  |
| Qualcomm Atheros      | 35        | 15.22%  |
| Broadcom              | 23        | 10%     |
| JMicron Technology    | 5         | 2.17%   |
| Ralink                | 4         | 1.74%   |
| TP-Link               | 2         | 0.87%   |
| Ralink Technology     | 2         | 0.87%   |
| Nvidia                | 2         | 0.87%   |
| MediaTek              | 2         | 0.87%   |
| Samsung Electronics   | 1         | 0.43%   |
| ICS Advent            | 1         | 0.43%   |
| D-Link System         | 1         | 0.43%   |
| Arduino SA            | 1         | 0.43%   |
| 3Com                  | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 23.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 7.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 3.44%   |
| Intel I211 Gigabit Network Connection                             | 8         | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.29%   |
| Intel Wireless 7265                                               | 6         | 2.29%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 1.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.91%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 1.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.53%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.53%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.53%   |
| Intel 82576 Gigabit Network Connection                            | 4         | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.15%   |
| Intel 82583V Gigabit Network Connection                           | 3         | 1.15%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.15%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.76%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2         | 0.76%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.76%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.76%   |
| MediaTek USB Ethernet-RNDIS                                       | 2         | 0.76%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.76%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.38%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.38%   |
| Realtek RTL8187SE Wireless LAN Controller                         | 1         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.38%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.38%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.38%   |
| Intel Wireless 8260                                               | 1         | 0.38%   |
| Intel Wireless 7260                                               | 1         | 0.38%   |
| Intel Wireless 3165                                               | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 28        | 32.94%  |
| Intel                 | 27        | 31.76%  |
| Realtek Semiconductor | 16        | 18.82%  |
| Broadcom              | 5         | 5.88%   |
| Ralink                | 4         | 4.71%   |
| TP-Link               | 2         | 2.35%   |
| Ralink Technology     | 2         | 2.35%   |
| D-Link System         | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 9         | 10.47%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 6.98%   |
| Intel Wireless 7265                                                  | 6         | 6.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 5         | 5.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 5.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 4.65%   |
| Intel Wireless 8265 / 8275                                           | 4         | 4.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 3.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.33%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 2.33%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2         | 2.33%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.16%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.16%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 1.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.16%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.16%   |
| Intel Wireless 8260                                                  | 1         | 1.16%   |
| Intel Wireless 7260                                                  | 1         | 1.16%   |
| Intel Wireless 3165                                                  | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.16%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.16%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.16%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 83        | 49.11%  |
| Intel                 | 47        | 27.81%  |
| Broadcom              | 19        | 11.24%  |
| Qualcomm Atheros      | 9         | 5.33%   |
| JMicron Technology    | 5         | 2.96%   |
| Nvidia                | 2         | 1.18%   |
| Samsung Electronics   | 1         | 0.59%   |
| MediaTek              | 1         | 0.59%   |
| ICS Advent            | 1         | 0.59%   |
| 3Com                  | 1         | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 62        | 35.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 19        | 10.92%  |
| Intel I211 Gigabit Network Connection                                         | 8         | 4.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 2.3%    |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.3%    |
| Intel 82576 Gigabit Network Connection                                        | 4         | 2.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 1.72%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.72%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.72%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.72%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.15%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 2         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.15%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 1.15%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 1.15%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.57%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.57%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.57%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.57%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.57%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82578DC Gigabit Network Connection                                      | 1         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 0.57%   |
| Intel 82575GB Gigabit Network Connection                                      | 1         | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.57%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.57%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.57%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1         | 0.57%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 0.57%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.57%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.57%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1         | 0.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 0.57%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1         | 0.57%   |
| 3Com 3c905 100BaseTX [Boomerang]                                              | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 146       | 64.6%   |
| WiFi     | 78        | 34.51%  |
| Modem    | 2         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 141       | 69.8%   |
| WiFi     | 61        | 30.2%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 50.96%  |
| 1     | 40        | 25.48%  |
| 4     | 18        | 11.46%  |
| 3     | 12        | 7.64%   |
| 6     | 3         | 1.91%   |
| 5     | 3         | 1.91%   |
| 8     | 1         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 149       | 93.71%  |
| Yes  | 10        | 6.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 41.67%  |
| Qualcomm Atheros Communications | 12        | 25%     |
| Apple                           | 4         | 8.33%   |
| Realtek Semiconductor           | 3         | 6.25%   |
| Broadcom                        | 3         | 6.25%   |
| Lite-On Technology              | 2         | 4.17%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| IMC Networks                    | 1         | 2.08%   |
| Cambridge Silicon Radio         | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 20.83%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 10.42%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 8.33%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 6.25%   |
| Realtek  Bluetooth Adapter                                  | 2         | 4.17%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 4.17%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 2         | 4.17%   |
| Intel AX201 Bluetooth                                       | 2         | 4.17%   |
| Intel AX200 Bluetooth                                       | 2         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 4.17%   |
| Apple Bluetooth Host Controller                             | 2         | 4.17%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 2.08%   |
| Lite-On Atheros Bluetooth                                   | 1         | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.08%   |
| IMC Networks Bluetooth Module                               | 1         | 2.08%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 2.08%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.08%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.08%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.08%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 115       | 68.86%  |
| AMD                                             | 25        | 14.97%  |
| Nvidia                                          | 18        | 10.78%  |
| C-Media Electronics                             | 3         | 1.8%    |
| M-Audio                                         | 1         | 0.6%    |
| Logitech                                        | 1         | 0.6%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.6%    |
| Lenovo                                          | 1         | 0.6%    |
| Generalplus Technology                          | 1         | 0.6%    |
| DSEA A/S                                        | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 7.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 5.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 4.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 4.08%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 4.08%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 4.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 4.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.04%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 2.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.53%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.53%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.02%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.02%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.02%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2         | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.51%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.51%   |
| Logitech H390 headset with microphone                                      | 1         | 0.51%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1         | 0.51%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.51%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.51%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 0.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.51%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.51%   |
| DSEA A/S Sennheiser 3D G4ME1                                               | 1         | 0.51%   |
| C-Media Electronics Audio Adapter                                          | 1         | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.51%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.51%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 37        | 22.02%  |
| Kingston            | 25        | 14.88%  |
| Smart               | 24        | 14.29%  |
| Samsung Electronics | 16        | 9.52%   |
| SK hynix            | 9         | 5.36%   |
| Teikon              | 8         | 4.76%   |
| Crucial             | 8         | 4.76%   |
| A-DATA Technology   | 6         | 3.57%   |
| Micron Technology   | 5         | 2.98%   |
| Smart Brazil        | 3         | 1.79%   |
| High Bridge         | 3         | 1.79%   |
| Hewlett-Packard     | 3         | 1.79%   |
| Apacer              | 3         | 1.79%   |
| Nanya Technology    | 2         | 1.19%   |
| Corsair             | 2         | 1.19%   |
| Unknown (ABCD)      | 1         | 0.6%    |
| Transcend           | 1         | 0.6%    |
| Tigo                | 1         | 0.6%    |
| RZX                 | 1         | 0.6%    |
| PUSKILL             | 1         | 0.6%    |
| PNY                 | 1         | 0.6%    |
| Multilaser          | 1         | 0.6%    |
| Kreton              | 1         | 0.6%    |
| Goldenmars          | 1         | 0.6%    |
| G.Skill             | 1         | 0.6%    |
| CSX                 | 1         | 0.6%    |
| Atermiter           | 1         | 0.6%    |
| 019400000A07        | 1         | 0.6%    |
| 0194000000CE        | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 37        | 21.14%  |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.29%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s              | 2         | 1.14%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 2         | 1.14%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.14%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 1         | 0.57%   |
| Transcend RAM TS256MSK64W3N 2GB DIMM DDR3 1066MT/s               | 1         | 0.57%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| Teikon RAM TMTS8G58DFRBFHC-16 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.57%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.57%   |
| Teikon RAM TMT41GU6BFR8C-PBHJ 8GB DIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.57%   |
| Teikon RAM TML251S6EFR8A-PBHC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.57%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.57%   |
| Smart RAM SH564568FH8NZQNSCR 2GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s            | 1         | 0.57%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s              | 1         | 0.57%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
| Smart RAM SG564568FG8N6KF-Z1 2GB DIMM DDR2 800MT/s               | 1         | 0.57%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s            | 1         | 0.57%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.57%   |
| Smart RAM Module 8GB DIMM DDR4 2667MT/s                          | 1         | 0.57%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2400MT/s  | 1         | 0.57%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s     | 1         | 0.57%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s           | 1         | 0.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.57%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s            | 1         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.57%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.57%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.57%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.57%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5674EB0-YK0 2GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 1         | 0.57%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 0.57%   |
| Samsung RAM M393B2K70BM1-CF8 16GB DIMM DDR3 1066MT/s             | 1         | 0.57%   |
| Samsung RAM M393B1K73CHD-CF8 8192MB DIMM DDR3 1066MT/s           | 1         | 0.57%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s              | 1         | 0.57%   |
| Samsung RAM K4E6E304EB-EGCG 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.57%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |
| RZX RAM D3D9M1333G/4G 4GB DIMM DDR3 1333MT/s                     | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 84        | 59.15%  |
| DDR4    | 33        | 23.24%  |
| SDRAM   | 9         | 6.34%   |
| DDR2    | 8         | 5.63%   |
| Unknown | 7         | 4.93%   |
| LPDDR4  | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 76        | 53.9%   |
| SODIMM       | 64        | 45.39%  |
| Row Of Chips | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 60        | 37.74%  |
| 2048  | 43        | 27.04%  |
| 8192  | 42        | 26.42%  |
| 16384 | 12        | 7.55%   |
| 1024  | 2         | 1.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 29.87%  |
| 1333    | 32        | 20.78%  |
| 2400    | 15        | 9.74%   |
| Unknown | 13        | 8.44%   |
| 2667    | 11        | 7.14%   |
| 1334    | 8         | 5.19%   |
| 2133    | 7         | 4.55%   |
| 800     | 6         | 3.9%    |
| 1066    | 4         | 2.6%    |
| 2666    | 3         | 1.95%   |
| 1067    | 3         | 1.95%   |
| 3200    | 1         | 0.65%   |
| 1867    | 1         | 0.65%   |
| 1866    | 1         | 0.65%   |
| 667     | 1         | 0.65%   |
| 533     | 1         | 0.65%   |
| 400     | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 14        | 23.73%  |
| Acer                          | 8         | 13.56%  |
| Realtek Semiconductor         | 7         | 11.86%  |
| Microdia                      | 5         | 8.47%   |
| Silicon Motion                | 4         | 6.78%   |
| Logitech                      | 3         | 5.08%   |
| Syntek                        | 2         | 3.39%   |
| Suyin                         | 2         | 3.39%   |
| Sunplus Innovation Technology | 2         | 3.39%   |
| IMC Networks                  | 2         | 3.39%   |
| Apple                         | 2         | 3.39%   |
| Alcor Micro                   | 2         | 3.39%   |
| Quanta                        | 1         | 1.69%   |
| Luxvisions Innotech Limited   | 1         | 1.69%   |
| Lite-On Technology            | 1         | 1.69%   |
| Lenovo                        | 1         | 1.69%   |
| Aveo Technology               | 1         | 1.69%   |
| Unknown                       | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Acer Integrated Camera                        | 4         | 6.67%   |
| Silicon Motion Web Camera                     | 3         | 5%      |
| Realtek Integrated_Webcam_HD                  | 3         | 5%      |
| Chicony HD WebCam                             | 3         | 5%      |
| Syntek EasyCamera                             | 2         | 3.33%   |
| Realtek Integrated Webcam                     | 2         | 3.33%   |
| Microdia Dell Laptop Integrated Webcam HD     | 2         | 3.33%   |
| Logitech Webcam C270                          | 2         | 3.33%   |
| Chicony Sony Visual Communication Camera      | 2         | 3.33%   |
| Apple FaceTime HD Camera                      | 2         | 3.33%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 3.33%   |
| Acer HD Webcam                                | 2         | 3.33%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.67%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.67%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.67%   |
| Sunplus HD WebCam                             | 1         | 1.67%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.67%   |
| Realtek LG Camera                             | 1         | 1.67%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.67%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.67%   |
| Quanta HD Webcam                              | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.67%   |
| Microdia Integrated Webcam HD                 | 1         | 1.67%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.67%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.67%   |
| Lite-On Integrated Camera                     | 1         | 1.67%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.67%   |
| IMC Networks USB Camera                       | 1         | 1.67%   |
| IMC Networks EasyCamera                       | 1         | 1.67%   |
| Chicony Webcam                                | 1         | 1.67%   |
| Chicony VGA WebCam                            | 1         | 1.67%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.67%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.67%   |
| Chicony Integrated Camera                     | 1         | 1.67%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.67%   |
| Chicony HP HD Camera                          | 1         | 1.67%   |
| Chicony EasyCamera                            | 1         | 1.67%   |
| Chicony 1.3M Webcam                           | 1         | 1.67%   |
| Aveo USB2.0 Camera                            | 1         | 1.67%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.67%   |
| Acer Lenovo EasyCamera                        | 1         | 1.67%   |
| Unknown                                       | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 60        | 38.22%  |
| 1     | 50        | 31.85%  |
| 2     | 21        | 13.38%  |
| 3     | 16        | 10.19%  |
| 5     | 5         | 3.18%   |
| 4     | 5         | 3.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 90        | 53.25%  |
| Card reader              | 25        | 14.79%  |
| Net/wireless             | 19        | 11.24%  |
| Bluetooth                | 17        | 10.06%  |
| Fingerprint reader       | 11        | 6.51%   |
| Sound                    | 5         | 2.96%   |
| Network                  | 1         | 0.59%   |
| Firewire controller      | 1         | 0.59%   |

