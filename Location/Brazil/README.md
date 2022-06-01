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

Total: 231

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.4.0    | 15        | 8.33%   |
| helloSystem 0.6.0    | 14        | 7.78%   |
| helloSystem 0.5.0    | 14        | 7.78%   |
| helloSystem 0.7.0    | 13        | 7.22%   |
| FreeBSD 13.0         | 7         | 3.89%   |
| OPNsense 21.1.3      | 6         | 3.33%   |
| OPNsense 21.1        | 6         | 3.33%   |
| OPNsense 20.7.8      | 6         | 3.33%   |
| FreeBSD 14.0-CURRENT | 6         | 3.33%   |
| OPNsense 21.1.2      | 5         | 2.78%   |
| OPNsense 21.1.1      | 5         | 2.78%   |
| FreeBSD 13.0-p3      | 4         | 2.22%   |
| FreeBSD 12.1         | 4         | 2.22%   |
| OPNsense 21.7.7      | 3         | 1.67%   |
| OPNsense 21.7.1      | 3         | 1.67%   |
| OPNsense 21.1.9      | 3         | 1.67%   |
| OPNsense 21.1.7      | 3         | 1.67%   |
| OPNsense 21.1.6      | 3         | 1.67%   |
| OPNsense 21.1.4      | 3         | 1.67%   |
| FreeBSD 13.0-p7      | 3         | 1.67%   |
| FreeBSD 13.0-p4      | 3         | 1.67%   |
| TrueNAS 12.2-p9      | 2         | 1.11%   |
| OPNsense 22.1.7      | 2         | 1.11%   |
| OPNsense 22.1        | 2         | 1.11%   |
| OPNsense 21.1.8      | 2         | 1.11%   |
| OPNsense 21.1.5      | 2         | 1.11%   |
| NomadBSD 5806f915    | 2         | 1.11%   |
| helloSystem 0.8.0    | 2         | 1.11%   |
| FreeNAS 11.3-p9      | 2         | 1.11%   |
| FreeBSD 13.0-STABLE  | 2         | 1.11%   |
| FreeBSD 13.0-CURRENT | 2         | 1.11%   |
| FreeBSD 12.2-p3      | 2         | 1.11%   |
| FreeBSD 12.2         | 2         | 1.11%   |
| FreeBSD 12.1-p7      | 2         | 1.11%   |
| TrueNAS 12.2-p6      | 1         | 0.56%   |
| TrueNAS 12.2-p12     | 1         | 0.56%   |
| TrueNAS 12.2-p11     | 1         | 0.56%   |
| TrueNAS 12.2-p10     | 1         | 0.56%   |
| pfSense 2.4.5        | 1         | 0.56%   |
| OS108 9.99.68        | 1         | 0.56%   |
| OPNsense 22.1.6      | 1         | 0.56%   |
| OPNsense 22.1.3      | 1         | 0.56%   |
| OPNsense 22.1.2      | 1         | 0.56%   |
| OPNsense 21.7.3      | 1         | 0.56%   |
| OPNsense 21.7.2      | 1         | 0.56%   |
| OPNsense 21.7        | 1         | 0.56%   |
| OPNsense 20.7        | 1         | 0.56%   |
| OpenBSD 7.0          | 1         | 0.56%   |
| OpenBSD 6.9          | 1         | 0.56%   |
| OpenBSD 6.8          | 1         | 0.56%   |
| NetBSD 9.2           | 1         | 0.56%   |
| helloSystem 0.3.0    | 1         | 0.56%   |
| GhostBSD 20.04.02    | 1         | 0.56%   |
| FreeNAS 11.3-p11     | 1         | 0.56%   |
| FreeBSD 13.0-RC2     | 1         | 0.56%   |
| FreeBSD 12.2-p1      | 1         | 0.56%   |
| FreeBSD 12.1-p11     | 1         | 0.56%   |
| FreeBSD 12.1-p10     | 1         | 0.56%   |
| DragonFly 5.8        | 1         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 54        | 34.62%  |
| OPNsense    | 47        | 30.13%  |
| FreeBSD     | 41        | 26.28%  |
| OpenBSD     | 3         | 1.92%   |
| TrueNAS     | 2         | 1.28%   |
| NomadBSD    | 2         | 1.28%   |
| FreeNAS     | 2         | 1.28%   |
| pfSense     | 1         | 0.64%   |
| OS108       | 1         | 0.64%   |
| NetBSD      | 1         | 0.64%   |
| GhostBSD    | 1         | 0.64%   |
| DragonFly   | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 149       | 98.68%  |
| i386  | 2         | 1.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 56        | 36.13%  |
| helloDesktop | 55        | 35.48%  |
| KDE5         | 12        | 7.74%   |
| XFCE         | 8         | 5.16%   |
| Openbox      | 5         | 3.23%   |
| MATE         | 5         | 3.23%   |
| GNOME        | 4         | 2.58%   |
| TWM          | 3         | 1.94%   |
| i3           | 2         | 1.29%   |
| fvwm         | 2         | 1.29%   |
| Window Maker | 1         | 0.65%   |
| spectrwm     | 1         | 0.65%   |
| LXQt         | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 94        | 62.25%  |
| Console | 57        | 37.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 68        | 44.16%  |
| SLiM    | 60        | 38.96%  |
| SDDM    | 11        | 7.14%   |
| LightDM | 6         | 3.9%    |
| GDM     | 5         | 3.25%   |
| XDM     | 4         | 2.6%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 60        | 38.96%  |
| Unknown         | 60        | 38.96%  |
| C               | 17        | 11.04%  |
| pt_BR           | 14        | 9.09%   |
| fr_FR           | 1         | 0.65%   |
| en_US.ISO8859-1 | 1         | 0.65%   |
| en_GB           | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 77.92%  |
| BIOS | 34        | 22.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 76        | 48.72%  |
| Ufs     | 67        | 42.95%  |
| Cd9660  | 9         | 5.77%   |
| Ffs     | 3         | 1.92%   |
| Hammer2 | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 137       | 89.54%  |
| MBR     | 14        | 9.15%   |
| Unknown | 2         | 1.31%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 16.56%  |
| ASUSTek Computer        | 20        | 13.25%  |
| Lenovo                  | 13        | 8.61%   |
| Hewlett-Packard         | 10        | 6.62%   |
| Intel                   | 8         | 5.3%    |
| Acer                    | 8         | 5.3%    |
| Gigabyte Technology     | 6         | 3.97%   |
| AMI                     | 6         | 3.97%   |
| Unknown                 | 6         | 3.97%   |
| Samsung Electronics     | 5         | 3.31%   |
| Itautec                 | 4         | 2.65%   |
| Apple                   | 4         | 2.65%   |
| Positivo                | 3         | 1.99%   |
| MSI                     | 3         | 1.99%   |
| Avell High Performance  | 3         | 1.99%   |
| Sony                    | 2         | 1.32%   |
| Semp Toshiba            | 2         | 1.32%   |
| Pegatron                | 2         | 1.32%   |
| PCWare                  | 2         | 1.32%   |
| Gateway                 | 2         | 1.32%   |
| ECS                     | 2         | 1.32%   |
| ASRock                  | 2         | 1.32%   |
| Yanling                 | 1         | 0.66%   |
| ULTRATOP                | 1         | 0.66%   |
| Procomp Ind. Eletronica | 1         | 0.66%   |
| Philco                  | 1         | 0.66%   |
| Notebook                | 1         | 0.66%   |
| LG Electronics          | 1         | 0.66%   |
| KLLISRE                 | 1         | 0.66%   |
| HC                      | 1         | 0.66%   |
| GALAX                   | 1         | 0.66%   |
| ECS-USA                 | 1         | 0.66%   |
| CNCTION-IAF-E3845       | 1         | 0.66%   |
| Clevo                   | 1         | 0.66%   |
| Acidanthera             | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 4.64%   |
| Intel Q3XXG4-P V1.0                         | 5         | 3.31%   |
| AMI Aptio CRB                               | 5         | 3.31%   |
| ASUS All Series                             | 4         | 2.65%   |
| Dell Inspiron 3442                          | 3         | 1.99%   |
| Pegatron IPM41-D3                           | 2         | 1.32%   |
| Gigabyte H61M-S2-B3                         | 2         | 1.32%   |
| Gateway NE56R                               | 2         | 1.32%   |
| ASUS PRIME B450M-GAMING/BR                  | 2         | 1.32%   |
| ASUS P8H61-M LX3 PLUS R2.0                  | 2         | 1.32%   |
| ASUS M5A78L-M LX/BR                         | 2         | 1.32%   |
| Acer Aspire 5750                            | 2         | 1.32%   |
| Yanling NS-1U8L                             | 1         | 0.66%   |
| ULTRATOP C2017-LIVA-ZE                      | 1         | 0.66%   |
| Sony VPCYB45JB                              | 1         | 0.66%   |
| Sony VPCEG17FB                              | 1         | 0.66%   |
| Semp Toshiba STI NA 1401                    | 1         | 0.66%   |
| Semp Toshiba STI                            | 1         | 0.66%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.66%   |
| Samsung 530XBB                              | 1         | 0.66%   |
| Samsung 340XAA/350XAA/550XAA                | 1         | 0.66%   |
| Samsung 300E5M/300E5L                       | 1         | 0.66%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 1         | 0.66%   |
| Procomp Ind. Eletronica G41MXE              | 1         | 0.66%   |
| Positivo POS-PIQ77CL                        | 1         | 0.66%   |
| Positivo POS-EAA75DE                        | 1         | 0.66%   |
| Positivo C14CR01                            | 1         | 0.66%   |
| Philco 10B                                  | 1         | 0.66%   |
| PCWare PW-945GCX                            | 1         | 0.66%   |
| PCWare IPX1800G2                            | 1         | 0.66%   |
| Notebook N85_N87HCHNHZ                      | 1         | 0.66%   |
| MSI U-100                                   | 1         | 0.66%   |
| MSI MS-7877                                 | 1         | 0.66%   |
| MSI MS-7698                                 | 1         | 0.66%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.66%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.66%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 0.66%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 0.66%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 0.66%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 0.66%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 0.66%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 0.66%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 0.66%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 0.66%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 0.66%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 0.66%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 0.66%   |
| Lenovo G550 2958                            | 1         | 0.66%   |
| KLLISRE X99-B5 V1.0                         | 1         | 0.66%   |
| Itautec Infoway w7535                       | 1         | 0.66%   |
| Itautec Infoway w7530                       | 1         | 0.66%   |
| Itautec Infoway ST-4344                     | 1         | 0.66%   |
| Itautec Infoway                             | 1         | 0.66%   |
| Intel H61                                   | 1         | 0.66%   |
| Intel H55                                   | 1         | 0.66%   |
| Intel DH61WW AAG23116-206                   | 1         | 0.66%   |
| HP Z230 Tower Workstation                   | 1         | 0.66%   |
| HP ProLiant ML350 G6                        | 1         | 0.66%   |
| HP ProLiant ML310e Gen8 v2                  | 1         | 0.66%   |
| HP ProLiant MicroServer Gen8                | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell Inspiron                  | 11        | 7.28%   |
| Lenovo ThinkPad                | 9         | 5.96%   |
| Acer Aspire                    | 7         | 4.64%   |
| Unknown                        | 7         | 4.64%   |
| AMI Aptio                      | 6         | 3.97%   |
| Intel Q3XXG4-P                 | 5         | 3.31%   |
| HP ProLiant                    | 5         | 3.31%   |
| Itautec Infoway                | 4         | 2.65%   |
| Dell PowerEdge                 | 4         | 2.65%   |
| Dell OptiPlex                  | 4         | 2.65%   |
| ASUS All                       | 4         | 2.65%   |
| Lenovo IdeaPad                 | 3         | 1.99%   |
| Dell Vostro                    | 3         | 1.99%   |
| ASUS PRIME                     | 3         | 1.99%   |
| ASUS M5A78L-M                  | 3         | 1.99%   |
| Semp Toshiba STI               | 2         | 1.32%   |
| Pegatron IPM41-D3              | 2         | 1.32%   |
| Gigabyte H61M-S2-B3            | 2         | 1.32%   |
| Gateway NE56R                  | 2         | 1.32%   |
| Dell Latitude                  | 2         | 1.32%   |
| Avell High Performance A62     | 2         | 1.32%   |
| ASUS P8H61-M                   | 2         | 1.32%   |
| Yanling NS-1U8L                | 1         | 0.66%   |
| ULTRATOP C2017-LIVA-ZE         | 1         | 0.66%   |
| Sony VPCYB45JB                 | 1         | 0.66%   |
| Sony VPCEG17FB                 | 1         | 0.66%   |
| Samsung RV411                  | 1         | 0.66%   |
| Samsung 530XBB                 | 1         | 0.66%   |
| Samsung 340XAA                 | 1         | 0.66%   |
| Samsung 300E5M                 | 1         | 0.66%   |
| Samsung 270E5K                 | 1         | 0.66%   |
| Procomp Ind. Eletronica G41MXE | 1         | 0.66%   |
| Positivo POS-PIQ77CL           | 1         | 0.66%   |
| Positivo POS-EAA75DE           | 1         | 0.66%   |
| Positivo C14CR01               | 1         | 0.66%   |
| Philco 10B                     | 1         | 0.66%   |
| PCWare PW-945GCX               | 1         | 0.66%   |
| PCWare IPX1800G2               | 1         | 0.66%   |
| Notebook N85                   | 1         | 0.66%   |
| MSI U-100                      | 1         | 0.66%   |
| MSI MS-7877                    | 1         | 0.66%   |
| MSI MS-7698                    | 1         | 0.66%   |
| LG 14Z980-G.BH51P1             | 1         | 0.66%   |
| Lenovo G550                    | 1         | 0.66%   |
| KLLISRE X99-B5                 | 1         | 0.66%   |
| Intel H61                      | 1         | 0.66%   |
| Intel H55                      | 1         | 0.66%   |
| Intel DH61WW                   | 1         | 0.66%   |
| HP Z230                        | 1         | 0.66%   |
| HP EliteDesk                   | 1         | 0.66%   |
| HP EliteBook                   | 1         | 0.66%   |
| HP Compaq                      | 1         | 0.66%   |
| HP 14                          | 1         | 0.66%   |
| HC HCAR357-MI                  | 1         | 0.66%   |
| Gigabyte G41MT-S2              | 1         | 0.66%   |
| Gigabyte C847N                 | 1         | 0.66%   |
| Gigabyte AB350M-Gaming         | 1         | 0.66%   |
| Gigabyte 970A-UD3P             | 1         | 0.66%   |
| GALAX B365M                    | 1         | 0.66%   |
| ECS-USA GeForce6100PM-M2       | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 18        | 11.92%  |
| 2016    | 17        | 11.26%  |
| 2013    | 17        | 11.26%  |
| 2019    | 16        | 10.6%   |
| 2020    | 14        | 9.27%   |
| 2011    | 13        | 8.61%   |
| 2009    | 10        | 6.62%   |
| 2010    | 8         | 5.3%    |
| 2017    | 7         | 4.64%   |
| 2015    | 7         | 4.64%   |
| 2012    | 7         | 4.64%   |
| 2014    | 6         | 3.97%   |
| 2021    | 4         | 2.65%   |
| 2008    | 3         | 1.99%   |
| Unknown | 2         | 1.32%   |
| 2022    | 1         | 0.66%   |
| 2007    | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 75        | 49.67%  |
| Notebook    | 60        | 39.74%  |
| Mini pc     | 7         | 4.64%   |
| Server      | 5         | 3.31%   |
| All in one  | 3         | 1.99%   |
| Convertible | 1         | 0.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 151       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 56        | 36.84%  |
| 8.01-16.0   | 55        | 36.18%  |
| 16.01-24.0  | 22        | 14.47%  |
| 2.01-3.0    | 9         | 5.92%   |
| 32.01-64.0  | 6         | 3.95%   |
| 24.01-32.0  | 2         | 1.32%   |
| 3.01-4.0    | 1         | 0.66%   |
| 64.01-256.0 | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 101       | 65.58%  |
| 0.51-1.0   | 39        | 25.32%  |
| 1.01-2.0   | 7         | 4.55%   |
| 4.01-8.0   | 2         | 1.3%    |
| Unknown    | 2         | 1.3%    |
| 32.01-64.0 | 1         | 0.65%   |
| 24.01-32.0 | 1         | 0.65%   |
| 16.01-24.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 66.03%  |
| 2      | 31        | 19.87%  |
| 0      | 10        | 6.41%   |
| 3      | 6         | 3.85%   |
| 5      | 2         | 1.28%   |
| 4      | 2         | 1.28%   |
| 7      | 1         | 0.64%   |
| 6      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 69.54%  |
| Yes       | 46        | 30.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 94.04%  |
| No        | 9         | 5.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 50.33%  |
| No        | 75        | 49.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 69.54%  |
| Yes       | 46        | 30.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 151       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| SГЈo Paulo              | 19        | 11.18%  |
| Rio de Janeiro            | 12        | 7.06%   |
| Curitiba                  | 7         | 4.12%   |
| SÃ£o Paulo              | 6         | 3.53%   |
| Manaus                    | 4         | 2.35%   |
| SГЈo JosГ© dos Campos | 3         | 1.76%   |
| Porto Alegre              | 3         | 1.76%   |
| JoГЈo Pessoa            | 3         | 1.76%   |
| Campinas                  | 3         | 1.76%   |
| Belo Horizonte            | 3         | 1.76%   |
| Teresina                  | 2         | 1.18%   |
| Serra                     | 2         | 1.18%   |
| Sao Vicente               | 2         | 1.18%   |
| RondonГіpolis           | 2         | 1.18%   |
| Rio Claro                 | 2         | 1.18%   |
| Pirapora                  | 2         | 1.18%   |
| Maraba                    | 2         | 1.18%   |
| JundiaГ­                | 2         | 1.18%   |
| Ipojuca                   | 2         | 1.18%   |
| Franca                    | 2         | 1.18%   |
| CuiabГЎ                 | 2         | 1.18%   |
| BrasГ­lia               | 2         | 1.18%   |
| BrasÃ­lia               | 2         | 1.18%   |
| Boa Vista do Jauato       | 2         | 1.18%   |
| VitГіria da Conquista   | 1         | 0.59%   |
| VitГіria                | 1         | 0.59%   |
| Visconde do Rio Branco    | 1         | 0.59%   |
| Urupes                    | 1         | 0.59%   |
| Unai                      | 1         | 0.59%   |
| Uberaba                   | 1         | 0.59%   |
| Teresopolis               | 1         | 0.59%   |
| Taubate                   | 1         | 0.59%   |
| Tangara                   | 1         | 0.59%   |
| Sao Paulo                 | 1         | 0.59%   |
| Sao Jose                  | 1         | 0.59%   |
| Sao Jeronimo da Serra     | 1         | 0.59%   |
| Santa Maria               | 1         | 0.59%   |
| Rio Grande da Serra       | 1         | 0.59%   |
| Rio das Ostras            | 1         | 0.59%   |
| Reriutaba                 | 1         | 0.59%   |
| Porto UniГЈo            | 1         | 0.59%   |
| Piracicaba                | 1         | 0.59%   |
| Piloezinhos               | 1         | 0.59%   |
| Pelotas                   | 1         | 0.59%   |
| Patos de Minas            | 1         | 0.59%   |
| Pato Branco               | 1         | 0.59%   |
| Paracuru                  | 1         | 0.59%   |
| Osasco                    | 1         | 0.59%   |
| Novo Horizonte do Norte   | 1         | 0.59%   |
| Novo Hamburgo             | 1         | 0.59%   |
| Morungaba                 | 1         | 0.59%   |
| Monte Belo                | 1         | 0.59%   |
| Marica                    | 1         | 0.59%   |
| Mage                      | 1         | 0.59%   |
| Macatuba                  | 1         | 0.59%   |
| Londrina                  | 1         | 0.59%   |
| Lavras                    | 1         | 0.59%   |
| Lajeado                   | 1         | 0.59%   |
| Jundiaí                  | 1         | 0.59%   |
| JundiaÃ­                | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 43     | 18.23%  |
| Seagate             | 33        | 82     | 17.19%  |
| Kingston            | 30        | 38     | 15.63%  |
| Samsung Electronics | 19        | 20     | 9.9%    |
| Toshiba             | 12        | 12     | 6.25%   |
| SanDisk             | 9         | 9      | 4.69%   |
| A-DATA Technology   | 8         | 8      | 4.17%   |
| Crucial             | 7         | 9      | 3.65%   |
| LITEON              | 4         | 4      | 2.08%   |
| Hoodisk             | 4         | 4      | 2.08%   |
| Hitachi             | 4         | 6      | 2.08%   |
| China               | 4         | 6      | 2.08%   |
| SK Hynix            | 3         | 3      | 1.56%   |
| Silicon Motion      | 3         | 3      | 1.56%   |
| KingSpec            | 3         | 3      | 1.56%   |
| Hewlett-Packard     | 2         | 3      | 1.04%   |
| XrayDisk            | 1         | 1      | 0.52%   |
| Transcend           | 1         | 2      | 0.52%   |
| SSSTC               | 1         | 1      | 0.52%   |
| SMART               | 1         | 1      | 0.52%   |
| Patriot             | 1         | 4      | 0.52%   |
| NTC                 | 1         | 1      | 0.52%   |
| Kston               | 1         | 1      | 0.52%   |
| Hikvision           | 1         | 1      | 0.52%   |
| HGST                | 1         | 2      | 0.52%   |
| Gigabyte Technology | 1         | 1      | 0.52%   |
| faspeed             | 1         | 1      | 0.52%   |
| Drevo               | 1         | 3      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 8         | 3.85%   |
| Kingston SA400S37120G 120GB         | 7         | 3.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.92%   |
| Kingston SA400S37480G 480GB         | 4         | 1.92%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3         | 1.44%   |
| Toshiba MQ01ABD100 1TB              | 3         | 1.44%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 1.44%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 1.44%   |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 1.44%   |
| SanDisk SDSSDA240G 240GB            | 3         | 1.44%   |
| Samsung HD322HJ 320GB               | 3         | 1.44%   |
| Kingston SA400S37960G 960GB         | 3         | 1.44%   |
| A-DATA SU630 240GB                  | 3         | 1.44%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.96%   |
| Silicon Motion NE-256 256GB         | 2         | 0.96%   |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.96%   |
| SanDisk SSD PLUS 120GB              | 2         | 0.96%   |
| Samsung HD502HJ 500GB               | 2         | 0.96%   |
| Samsung HD161HJ 160GB               | 2         | 0.96%   |
| Kingston SUV400S37120G 120GB        | 2         | 0.96%   |
| KingSpec MT-128 128GB               | 2         | 0.96%   |
| Hoodisk SSD 64GB                    | 2         | 0.96%   |
| Hoodisk SSD 32GB                    | 2         | 0.96%   |
| China SATA SSD 120GB                | 2         | 0.96%   |
| XrayDisk SSD 128GB                  | 1         | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 0.48%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.48%   |
| WDC WD5000B 500GB                   | 1         | 0.48%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 0.48%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 0.48%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 0.48%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 0.48%   |
| WDC WD400BD-75LRA0 40GB             | 1         | 0.48%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 0.48%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 0.48%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 0.48%   |
| WDC WD3200AAJS-60Z0A0 320GB         | 1         | 0.48%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 0.48%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1         | 0.48%   |
| WDC WD2500AAKX-75U6AA0 250GB        | 1         | 0.48%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.48%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.48%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.48%   |
| WDC WD1600AVJS-63WNA0 160GB         | 1         | 0.48%   |
| WDC WD1200BEVT-22ZCT0 120GB         | 1         | 0.48%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.48%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 0.48%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 0.48%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.48%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.48%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1         | 0.48%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 82     | 34.38%  |
| WDC                 | 31        | 38     | 32.29%  |
| Samsung Electronics | 14        | 15     | 14.58%  |
| Toshiba             | 11        | 11     | 11.46%  |
| Hitachi             | 4         | 6      | 4.17%   |
| Hewlett-Packard     | 2         | 3      | 2.08%   |
| HGST                | 1         | 2      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 29        | 37     | 34.52%  |
| SanDisk             | 9         | 9      | 10.71%  |
| Crucial             | 6         | 8      | 7.14%   |
| WDC                 | 5         | 5      | 5.95%   |
| Samsung Electronics | 4         | 4      | 4.76%   |
| LITEON              | 4         | 4      | 4.76%   |
| Hoodisk             | 4         | 4      | 4.76%   |
| China               | 4         | 6      | 4.76%   |
| A-DATA Technology   | 4         | 4      | 4.76%   |
| KingSpec            | 3         | 3      | 3.57%   |
| SK Hynix            | 2         | 2      | 2.38%   |
| XrayDisk            | 1         | 1      | 1.19%   |
| Transcend           | 1         | 2      | 1.19%   |
| SMART               | 1         | 1      | 1.19%   |
| Patriot             | 1         | 4      | 1.19%   |
| NTC                 | 1         | 1      | 1.19%   |
| Kston               | 1         | 1      | 1.19%   |
| Hikvision           | 1         | 1      | 1.19%   |
| Gigabyte Technology | 1         | 1      | 1.19%   |
| faspeed             | 1         | 1      | 1.19%   |
| Drevo               | 1         | 3      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 157    | 47.65%  |
| SSD  | 76        | 102    | 44.71%  |
| NVMe | 13        | 13     | 7.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 259    | 91.03%  |
| NVMe | 13        | 13     | 8.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 164    | 72.44%  |
| 0.51-1.0   | 32        | 48     | 20.51%  |
| 1.01-2.0   | 7         | 15     | 4.49%   |
| 3.01-4.0   | 4         | 32     | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 41        | 25%     |
| 101-250        | 38        | 23.17%  |
| 251-500        | 30        | 18.29%  |
| 21-50          | 18        | 10.98%  |
| 51-100         | 15        | 9.15%   |
| 501-1000       | 13        | 7.93%   |
| 1001-2000      | 5         | 3.05%   |
| 2001-3000      | 2         | 1.22%   |
| More than 3000 | 1         | 0.61%   |
| Unknown        | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 129       | 84.87%  |
| 21-50     | 11        | 7.24%   |
| 101-250   | 5         | 3.29%   |
| 501-1000  | 4         | 2.63%   |
| 2001-3000 | 1         | 0.66%   |
| 51-100    | 1         | 0.66%   |
| Unknown   | 1         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3         | 3      | 5.77%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 2      | 3.85%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 3.85%   |
| Samsung Electronics HD161HJ 160GB   | 2         | 2      | 3.85%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000B 500GB                   | 1         | 1      | 1.92%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1         | 1      | 1.92%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.92%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 1.92%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 1.92%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1         | 1      | 1.92%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1         | 1      | 1.92%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 1.92%   |
| WDC WD10PURX-64E5EY0 1TB            | 1         | 1      | 1.92%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 1.92%   |
| Transcend TS32GMSM610 32GB          | 1         | 2      | 1.92%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.92%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.92%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 1.92%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 1.92%   |
| SK Hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 1.92%   |
| Seagate ST9320325ASG 320GB          | 1         | 1      | 1.92%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 1.92%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.92%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.92%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.92%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.92%   |
| Seagate ST500DM002-1BC142 500GB     | 1         | 1      | 1.92%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.92%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.92%   |
| Seagate ST31000528AS 1TB            | 1         | 1      | 1.92%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 1.92%   |
| Seagate ST2000DM001-1E6164 2TB      | 1         | 1      | 1.92%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 9      | 1.92%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1      | 1.92%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1      | 1.92%   |
| SanDisk SSD PLUS 240 GB             | 1         | 1      | 1.92%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 1.92%   |
| Samsung Electronics HD642JJ 640GB   | 1         | 1      | 1.92%   |
| Samsung Electronics HD502HJ 500GB   | 1         | 1      | 1.92%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1      | 1.92%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 1.92%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 1.92%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 2      | 1.92%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 2      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 24     | 32.65%  |
| WDC                 | 12        | 14     | 24.49%  |
| Samsung Electronics | 7         | 8      | 14.29%  |
| Toshiba             | 6         | 6      | 12.24%  |
| Hitachi             | 4         | 6      | 8.16%   |
| Transcend           | 1         | 2      | 2.04%   |
| SK Hynix            | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 24     | 35.56%  |
| WDC                 | 12        | 14     | 26.67%  |
| Samsung Electronics | 7         | 8      | 15.56%  |
| Toshiba             | 6         | 6      | 13.33%  |
| Hitachi             | 4         | 6      | 8.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 58     | 90.91%  |
| SSD  | 4         | 5      | 9.09%   |

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
| Works    | 115       | 202    | 70.12%  |
| Malfunc  | 44        | 63     | 26.83%  |
| Detected | 4         | 6      | 2.44%   |
| Failed   | 1         | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 127       | 76.05%  |
| AMD                            | 18        | 10.78%  |
| Silicon Motion                 | 4         | 2.4%    |
| Nvidia                         | 3         | 1.8%    |
| ADATA Technology               | 3         | 1.8%    |
| Broadcom / LSI                 | 2         | 1.2%    |
| Toshiba                        | 1         | 0.6%    |
| Solid State Storage Technology | 1         | 0.6%    |
| SK Hynix                       | 1         | 0.6%    |
| Samsung Electronics            | 1         | 0.6%    |
| Realtek Semiconductor          | 1         | 0.6%    |
| Micron/Crucial Technology      | 1         | 0.6%    |
| Kingston Technology Company    | 1         | 0.6%    |
| Integrated Technology Express  | 1         | 0.6%    |
| Hewlett-Packard                | 1         | 0.6%    |
| Adaptec                        | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 6.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 6.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 5.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 4.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 4.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 4.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 3.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.61%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.58%   |
| Unknown                                                                                 | 5         | 2.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 2.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.55%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 1.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.55%   |
| Nvidia MCP79 AHCI Controller                                                            | 2         | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.03%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2         | 1.03%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.52%   |
| SK Hynix BC511                                                                          | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.52%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.52%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.52%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.52%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.52%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1         | 0.52%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.52%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.52%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset SATA RAID Controller                                 | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.52%   |
| Integrated Express IT8213 IDE Controller                                                | 1         | 0.52%   |
| HP Smart Array G6 controllers                                                           | 1         | 0.52%   |
| Broadcom / LSI MegaRAID SAS-3 3008 [Fury]                                               | 1         | 0.52%   |
| Broadcom / LSI MegaRAID SAS 1078                                                        | 1         | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [Non-RAID5 mode]                                  | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 67.84%  |
| IDE  | 32        | 18.71%  |
| NVMe | 14        | 8.19%   |
| RAID | 8         | 4.68%   |
| SCSI | 1         | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 87.42%  |
| AMD    | 19        | 12.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 5         | 3.29%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.97%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 1.32%   |
| Intel CPU Version                           | 2         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.32%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.32%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.32%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.32%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.32%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.32%   |
| Intel Core i3-2100 CPU                      | 2         | 1.32%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.32%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2         | 1.32%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.32%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 2         | 1.32%   |
| AMD FX-8320E Eight-Core Processor           | 2         | 1.32%   |
| Intel Xeon E-2224 CPU @ 3.40GHz             | 1         | 0.66%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.66%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1         | 0.66%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.66%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 0.66%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz         | 1         | 0.66%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.66%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.66%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.66%   |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1         | 0.66%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.66%   |
| Intel Genuine CPU                           | 1         | 0.66%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.66%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.66%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.66%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.66%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.66%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.66%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.66%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 0.66%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 21.19%  |
| Intel Core i3           | 24        | 15.89%  |
| Intel Core i7           | 18        | 11.92%  |
| Intel Celeron           | 18        | 11.92%  |
| Intel Xeon              | 11        | 7.28%   |
| Intel Core 2 Duo        | 8         | 5.3%    |
| AMD FX                  | 6         | 3.97%   |
| Intel Pentium Dual-Core | 5         | 3.31%   |
| Intel Atom              | 5         | 3.31%   |
| Intel Pentium           | 4         | 2.65%   |
| AMD Ryzen 5             | 4         | 2.65%   |
| Other                   | 2         | 1.32%   |
| Intel Core 2 Quad       | 2         | 1.32%   |
| AMD E                   | 2         | 1.32%   |
| Intel Genuine           | 1         | 0.66%   |
| Intel Core M            | 1         | 0.66%   |
| Intel Core 2            | 1         | 0.66%   |
| AMD Turion II Neo       | 1         | 0.66%   |
| AMD Ryzen 7             | 1         | 0.66%   |
| AMD Ryzen 3             | 1         | 0.66%   |
| AMD PRO A8              | 1         | 0.66%   |
| AMD Phenom              | 1         | 0.66%   |
| AMD E1                  | 1         | 0.66%   |
| AMD C-60                | 1         | 0.66%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 80        | 52.63%  |
| 4       | 42        | 27.63%  |
| 8       | 10        | 6.58%   |
| 6       | 9         | 5.92%   |
| Unknown | 6         | 3.95%   |
| 12      | 3         | 1.97%   |
| 1       | 2         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 97.35%  |
| 2      | 4         | 2.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 75        | 49.34%  |
| 2       | 71        | 46.71%  |
| Unknown | 6         | 3.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 16.45%  |
| SandyBridge   | 19        | 12.5%   |
| Penryn        | 16        | 10.53%  |
| Haswell       | 15        | 9.87%   |
| Silvermont    | 12        | 7.89%   |
| IvyBridge     | 12        | 7.89%   |
| Broadwell     | 8         | 5.26%   |
| Westmere      | 5         | 3.29%   |
| Piledriver    | 5         | 3.29%   |
| Zen+          | 4         | 2.63%   |
| Skylake       | 4         | 2.63%   |
| Bobcat        | 4         | 2.63%   |
| Nehalem       | 3         | 1.97%   |
| Goldmont      | 3         | 1.97%   |
| Core          | 3         | 1.97%   |
| Bonnell       | 3         | 1.97%   |
| K10           | 2         | 1.32%   |
| Goldmont plus | 2         | 1.32%   |
| CometLake     | 2         | 1.32%   |
| Zen 2         | 1         | 0.66%   |
| Zen           | 1         | 0.66%   |
| Steamroller   | 1         | 0.66%   |
| Bulldozer     | 1         | 0.66%   |
| Unknown       | 1         | 0.66%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 111       | 65.29%  |
| Nvidia                     | 28        | 16.47%  |
| AMD                        | 23        | 13.53%  |
| Matrox Electronics Systems | 7         | 4.12%   |
| ASPEED Technology          | 1         | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Computers | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 17        | 9.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 12        | 6.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 8         | 4.62%   |
| Intel 4 Series Chipset Integrated Graphics Controller                              | 8         | 4.62%   |
| Intel HD Graphics 5500                                                             | 7         | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                   | 6         | 3.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                   | 5         | 2.89%   |
| Intel UHD Graphics 620                                                             | 5         | 2.89%   |
| Intel Core Processor Integrated Graphics Controller                                | 4         | 2.31%   |
| Nvidia GK208B [GeForce GT 710]                                                     | 3         | 1.73%   |
| Matrox Electronics Systems MGA G200EH                                              | 3         | 1.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 3         | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 3         | 1.73%   |
| Intel HD Graphics 630                                                              | 3         | 1.73%   |
| Intel HD Graphics 620                                                              | 3         | 1.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                          | 3         | 1.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                             | 3         | 1.73%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                         | 3         | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                            | 3         | 1.73%   |
| Nvidia TU117M                                                                      | 2         | 1.16%   |
| Nvidia GP108M [GeForce MX250]                                                      | 2         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                 | 2         | 1.16%   |
| Nvidia GM108M [GeForce MX130]                                                      | 2         | 1.16%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                      | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller        | 2         | 1.16%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                         | 2         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 2         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.16%   |
| Intel HD Graphics 500                                                              | 2         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 2         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 2         | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                               | 2         | 1.16%   |
| AMD RV710 [Radeon HD 4350/4550]                                                    | 2         | 1.16%   |
| AMD RS780L [Radeon 3000]                                                           | 2         | 1.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                         | 1         | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                         | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX230]                                                      | 1         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                | 1         | 0.58%   |
| Nvidia GM108M [GeForce MX110]                                                      | 1         | 0.58%   |
| Nvidia GM108M [GeForce 940MX]                                                      | 1         | 0.58%   |
| Nvidia GM107M [GeForce GTX 950M]                                                   | 1         | 0.58%   |
| Nvidia GK208M [GeForce GT 740M]                                                    | 1         | 0.58%   |
| Nvidia GK208BM [GeForce 920M]                                                      | 1         | 0.58%   |
| Nvidia GK107GL [Quadro K2000]                                                      | 1         | 0.58%   |
| Nvidia GF119M [GeForce 410M]                                                       | 1         | 0.58%   |
| Nvidia GF119 [GeForce GT 610]                                                      | 1         | 0.58%   |
| Nvidia GF108 [GeForce GT 430]                                                      | 1         | 0.58%   |
| Nvidia GF106 [GeForce GTS 450]                                                     | 1         | 0.58%   |
| Nvidia G86 [GeForce 8500 GT]                                                       | 1         | 0.58%   |
| Nvidia C79 [GeForce 9400]                                                          | 1         | 0.58%   |
| Nvidia C79 [GeForce 9400M]                                                         | 1         | 0.58%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller           | 1         | 0.58%   |
| Matrox Electronics Systems G200eR2                                                 | 1         | 0.58%   |
| Intel HD Graphics 5300                                                             | 1         | 0.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 1         | 0.58%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                      | 1         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 0.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller            | 1         | 0.58%   |
| Intel 82Q33 Express Integrated Graphics Controller                                 | 1         | 0.58%   |
| Intel 82945G/GZ Integrated Graphics Controller                                     | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 56.58%  |
| 1 x AMD        | 19        | 12.5%   |
| 1 x Nvidia     | 14        | 9.21%   |
| Intel + Nvidia | 14        | 9.21%   |
| 2 x Intel      | 7         | 4.61%   |
| 1 x Matrox     | 7         | 4.61%   |
| Intel + AMD    | 4         | 2.63%   |
| 1 x ASPEED     | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 139       | 91.45%  |
| Proprietary | 12        | 7.89%   |
| Unknown     | 1         | 0.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 83.77%  |
| 3.01-4.0   | 8         | 5.19%   |
| 0.01-0.5   | 7         | 4.55%   |
| 1.01-2.0   | 4         | 2.6%    |
| 0.51-1.0   | 4         | 2.6%    |
| 7.01-8.0   | 1         | 0.65%   |
| 2.01-3.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 17        | 19.77%  |
| Samsung Electronics | 13        | 15.12%  |
| Goldstar            | 11        | 12.79%  |
| LG Display          | 10        | 11.63%  |
| BOE                 | 6         | 6.98%   |
| Chimei Innolux      | 5         | 5.81%   |
| AOC                 | 5         | 5.81%   |
| InfoVision          | 3         | 3.49%   |
| Dell                | 3         | 3.49%   |
| Philips             | 2         | 2.33%   |
| Lenovo              | 2         | 2.33%   |
| Hewlett-Packard     | 2         | 2.33%   |
| Apple               | 2         | 2.33%   |
| VIE                 | 1         | 1.16%   |
| PANDA               | 1         | 1.16%   |
| Panasonic           | 1         | 1.16%   |
| LG Electronics      | 1         | 1.16%   |
| ASUSTek Computer    | 1         | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.49%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 3.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.25%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 1.12%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.12%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 1.12%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.12%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.12%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                     | 1         | 1.12%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                     | 1         | 1.12%   |
| LG Electronics LCD Monitor 23MP55                                     | 1         | 1.12%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.12%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.12%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch              | 1         | 1.12%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.12%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.12%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.12%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch            | 1         | 1.12%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                   | 1         | 1.12%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 1.12%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                   | 1         | 1.12%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch            | 1         | 1.12%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                 | 1         | 1.12%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                 | 1         | 1.12%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                  | 1         | 1.12%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                  | 1         | 1.12%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                 | 1         | 1.12%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                 | 1         | 1.12%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 1         | 1.12%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.12%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.12%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch       | 1         | 1.12%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 1         | 1.12%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                 | 1         | 1.12%   |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                  | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 36        | 41.86%  |
| 1920x1080 (FHD)    | 29        | 33.72%  |
| 1600x900 (HD+)     | 5         | 5.81%   |
| 1440x900 (WXGA+)   | 3         | 3.49%   |
| 1280x1024 (SXGA)   | 3         | 3.49%   |
| 1024x768 (XGA)     | 2         | 2.33%   |
| 3640x1920          | 1         | 1.16%   |
| 2560x1440 (QHD)    | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1360x768           | 1         | 1.16%   |
| 1280x800 (WXGA)    | 1         | 1.16%   |
| 1280x720 (HD)      | 1         | 1.16%   |
| 1024x600           | 1         | 1.16%   |
| Unknown            | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 24        | 27.59%  |
| 15      | 20        | 22.99%  |
| 24      | 6         | 6.9%    |
| 19      | 6         | 6.9%    |
| 23      | 5         | 5.75%   |
| 21      | 5         | 5.75%   |
| 18      | 5         | 5.75%   |
| 12      | 4         | 4.6%    |
| Unknown | 4         | 4.6%    |
| 20      | 3         | 3.45%   |
| 31      | 1         | 1.15%   |
| 17      | 1         | 1.15%   |
| 14      | 1         | 1.15%   |
| 11      | 1         | 1.15%   |
| 10      | 1         | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 48.84%  |
| 401-500     | 17        | 19.77%  |
| 501-600     | 11        | 12.79%  |
| 201-300     | 10        | 11.63%  |
| Unknown     | 4         | 4.65%   |
| 601-700     | 1         | 1.16%   |
| 351-400     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 65        | 82.28%  |
| 16/10   | 6         | 7.59%   |
| 4/3     | 3         | 3.8%    |
| 5/4     | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 3/2     | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 25.29%  |
| 91-100         | 19        | 21.84%  |
| 201-250        | 16        | 18.39%  |
| 151-200        | 9         | 10.34%  |
| 141-150        | 6         | 6.9%    |
| 61-70          | 4         | 4.6%    |
| Unknown        | 4         | 4.6%    |
| 101-110        | 2         | 2.3%    |
| 71-80          | 1         | 1.15%   |
| 51-60          | 1         | 1.15%   |
| 351-500        | 1         | 1.15%   |
| 41-50          | 1         | 1.15%   |
| 111-120        | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 36        | 42.35%  |
| 51-100  | 28        | 32.94%  |
| 121-160 | 13        | 15.29%  |
| Unknown | 4         | 4.71%   |
| 161-240 | 3         | 3.53%   |
| 1-50    | 1         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 48.03%  |
| 0     | 69        | 45.39%  |
| 2     | 10        | 6.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 87        | 38.67%  |
| Intel                 | 59        | 26.22%  |
| Qualcomm Atheros      | 34        | 15.11%  |
| Broadcom              | 23        | 10.22%  |
| JMicron Technology    | 5         | 2.22%   |
| Ralink                | 4         | 1.78%   |
| TP-Link               | 2         | 0.89%   |
| Ralink Technology     | 2         | 0.89%   |
| Nvidia                | 2         | 0.89%   |
| MediaTek              | 2         | 0.89%   |
| Samsung Electronics   | 1         | 0.44%   |
| ICS Advent            | 1         | 0.44%   |
| D-Link System         | 1         | 0.44%   |
| Arduino SA            | 1         | 0.44%   |
| 3Com                  | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 23.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 7.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 3.52%   |
| Intel I211 Gigabit Network Connection                             | 8         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.34%   |
| Intel Wireless 7265                                               | 6         | 2.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.95%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 1.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.56%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.56%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.56%   |
| Intel 82576 Gigabit Network Connection                            | 4         | 1.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.17%   |
| Intel 82583V Gigabit Network Connection                           | 3         | 1.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.78%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 2         | 0.78%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.78%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.78%   |
| MediaTek USB Ethernet-RNDIS                                       | 2         | 0.78%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.78%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.39%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.39%   |
| Realtek RTL8187SE Wireless LAN Controller                         | 1         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.39%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.39%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.39%   |
| Intel Wireless 8260                                               | 1         | 0.39%   |
| Intel Wireless 7260                                               | 1         | 0.39%   |
| Intel Wireless 3165                                               | 1         | 0.39%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 28        | 33.73%  |
| Intel                 | 25        | 30.12%  |
| Realtek Semiconductor | 16        | 19.28%  |
| Broadcom              | 5         | 6.02%   |
| Ralink                | 4         | 4.82%   |
| TP-Link               | 2         | 2.41%   |
| Ralink Technology     | 2         | 2.41%   |
| D-Link System         | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 9         | 10.71%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 7.14%   |
| Intel Wireless 7265                                                  | 6         | 7.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 5         | 5.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 5.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 4.76%   |
| Intel Wireless 8265 / 8275                                           | 4         | 4.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 3.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 2.38%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2         | 2.38%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.19%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 1.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.19%   |
| Realtek RTL8187SE Wireless LAN Controller                            | 1         | 1.19%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 1.19%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.19%   |
| Intel Wireless 8260                                                  | 1         | 1.19%   |
| Intel Wireless 7260                                                  | 1         | 1.19%   |
| Intel Wireless 3165                                                  | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.19%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.19%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.19%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 1.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 81        | 49.09%  |
| Intel                 | 46        | 27.88%  |
| Broadcom              | 19        | 11.52%  |
| Qualcomm Atheros      | 8         | 4.85%   |
| JMicron Technology    | 5         | 3.03%   |
| Nvidia                | 2         | 1.21%   |
| Samsung Electronics   | 1         | 0.61%   |
| MediaTek              | 1         | 0.61%   |
| ICS Advent            | 1         | 0.61%   |
| 3Com                  | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 60        | 35.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 19        | 11.18%  |
| Intel I211 Gigabit Network Connection                                         | 8         | 4.71%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 4         | 2.35%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.35%   |
| Intel 82576 Gigabit Network Connection                                        | 4         | 2.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 1.76%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.76%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.76%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 1.76%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.76%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.18%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.18%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 1.18%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 1.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 2         | 1.18%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 1.18%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.59%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.59%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.59%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.59%   |
| Intel I350 Gigabit Network Connection                                         | 1         | 0.59%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.59%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.59%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.59%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.59%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.59%   |
| Intel 82578DC Gigabit Network Connection                                      | 1         | 0.59%   |
| Intel 82575GB Gigabit Network Connection                                      | 1         | 0.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1         | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.59%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.59%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1         | 0.59%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 0.59%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.59%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 1         | 0.59%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1         | 0.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                           | 1         | 0.59%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1         | 0.59%   |
| 3Com 3c905 100BaseTX [Boomerang]                                              | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 142       | 64.55%  |
| WiFi     | 76        | 34.55%  |
| Modem    | 2         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 138       | 70.05%  |
| WiFi     | 59        | 29.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 51.97%  |
| 1     | 36        | 23.68%  |
| 4     | 18        | 11.84%  |
| 3     | 12        | 7.89%   |
| 6     | 3         | 1.97%   |
| 5     | 3         | 1.97%   |
| 8     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 144       | 93.51%  |
| Yes  | 10        | 6.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 41.3%   |
| Qualcomm Atheros Communications | 12        | 26.09%  |
| Apple                           | 4         | 8.7%    |
| Realtek Semiconductor           | 3         | 6.52%   |
| Lite-On Technology              | 2         | 4.35%   |
| Foxconn / Hon Hai               | 2         | 4.35%   |
| Broadcom                        | 2         | 4.35%   |
| IMC Networks                    | 1         | 2.17%   |
| Cambridge Silicon Radio         | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 10        | 21.74%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 8.7%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 6.52%   |
| Realtek  Bluetooth Adapter                                  | 2         | 4.35%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 4.35%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 2         | 4.35%   |
| Intel AX201 Bluetooth                                       | 2         | 4.35%   |
| Intel AX200 Bluetooth                                       | 2         | 4.35%   |
| Apple Bluetooth Host Controller                             | 2         | 4.35%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 2.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 2.17%   |
| Lite-On Atheros Bluetooth                                   | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.17%   |
| IMC Networks Bluetooth Module                               | 1         | 2.17%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 2.17%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 2.17%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.17%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 111       | 68.94%  |
| AMD                                             | 23        | 14.29%  |
| Nvidia                                          | 18        | 11.18%  |
| C-Media Electronics                             | 3         | 1.86%   |
| M-Audio                                         | 1         | 0.62%   |
| Logitech                                        | 1         | 0.62%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.62%   |
| Lenovo                                          | 1         | 0.62%   |
| Generalplus Technology                          | 1         | 0.62%   |
| DSEA A/S                                        | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 7.41%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 5.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 5.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 4.23%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 4.23%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 4.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 4.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 3.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.12%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 2.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 3         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.06%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.06%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 1.06%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.06%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.53%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.53%   |
| Logitech H390 headset with microphone                                      | 1         | 0.53%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1         | 0.53%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.53%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.53%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 0.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.53%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.53%   |
| DSEA A/S Sennheiser 3D G4ME1                                               | 1         | 0.53%   |
| C-Media Electronics Audio Adapter                                          | 1         | 0.53%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.53%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.53%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 35        | 21.34%  |
| Smart               | 24        | 14.63%  |
| Kingston            | 24        | 14.63%  |
| Samsung Electronics | 14        | 8.54%   |
| SK Hynix            | 9         | 5.49%   |
| Teikon              | 8         | 4.88%   |
| Crucial             | 8         | 4.88%   |
| A-DATA Technology   | 6         | 3.66%   |
| Micron Technology   | 5         | 3.05%   |
| Smart Brazil        | 3         | 1.83%   |
| High Bridge         | 3         | 1.83%   |
| Hewlett-Packard     | 3         | 1.83%   |
| Apacer              | 3         | 1.83%   |
| Nanya Technology    | 2         | 1.22%   |
| Unknown             | 2         | 1.22%   |
| Unknown (ABCD)      | 1         | 0.61%   |
| Transcend           | 1         | 0.61%   |
| Tigo                | 1         | 0.61%   |
| RZX                 | 1         | 0.61%   |
| PUSKILL             | 1         | 0.61%   |
| PNY                 | 1         | 0.61%   |
| Multilaser          | 1         | 0.61%   |
| Kreton              | 1         | 0.61%   |
| Goldenmars          | 1         | 0.61%   |
| G.Skill             | 1         | 0.61%   |
| CSX                 | 1         | 0.61%   |
| Corsair             | 1         | 0.61%   |
| Atermiter           | 1         | 0.61%   |
| 019400000A07        | 1         | 0.61%   |
| 0194000000CE        | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                                | 4         | 2.27%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 1.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 1.14%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 2         | 1.14%   |
| Unknown RAM Module 2GB DIMM                                      | 2         | 1.14%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s              | 2         | 1.14%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 2         | 1.14%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Unknown                                                          | 2         | 1.14%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.57%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                         | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR2                              | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                             | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.57%   |
| Unknown RAM DDR3 8GB 1600MHz 8GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
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

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 81        | 59.12%  |
| DDR4    | 32        | 23.36%  |
| SDRAM   | 8         | 5.84%   |
| DDR2    | 8         | 5.84%   |
| Unknown | 7         | 5.11%   |
| LPDDR4  | 1         | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 73        | 53.68%  |
| SODIMM       | 62        | 45.59%  |
| Row Of Chips | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 58        | 37.66%  |
| 2048  | 42        | 27.27%  |
| 8192  | 40        | 25.97%  |
| 16384 | 12        | 7.79%   |
| 1024  | 2         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 45        | 30.41%  |
| 1333    | 32        | 21.62%  |
| 2400    | 14        | 9.46%   |
| Unknown | 12        | 8.11%   |
| 2667    | 11        | 7.43%   |
| 2133    | 7         | 4.73%   |
| 1334    | 6         | 4.05%   |
| 800     | 6         | 4.05%   |
| 1066    | 4         | 2.7%    |
| 2666    | 3         | 2.03%   |
| 1067    | 3         | 2.03%   |
| 1867    | 1         | 0.68%   |
| 1866    | 1         | 0.68%   |
| 667     | 1         | 0.68%   |
| 533     | 1         | 0.68%   |
| 400     | 1         | 0.68%   |

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
| Chicony Electronics           | 14        | 24.56%  |
| Realtek Semiconductor         | 7         | 12.28%  |
| Acer                          | 7         | 12.28%  |
| Microdia                      | 5         | 8.77%   |
| Silicon Motion                | 4         | 7.02%   |
| Logitech                      | 3         | 5.26%   |
| Syntek                        | 2         | 3.51%   |
| Suyin                         | 2         | 3.51%   |
| Sunplus Innovation Technology | 2         | 3.51%   |
| IMC Networks                  | 2         | 3.51%   |
| Apple                         | 2         | 3.51%   |
| Alcor Micro                   | 2         | 3.51%   |
| Unknown                       | 1         | 1.75%   |
| Quanta                        | 1         | 1.75%   |
| Luxvisions Innotech Limited   | 1         | 1.75%   |
| Lite-On Technology            | 1         | 1.75%   |
| Aveo Technology               | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Silicon Motion Web Camera                     | 3         | 5.17%   |
| Realtek Integrated_Webcam_HD                  | 3         | 5.17%   |
| Chicony HD WebCam                             | 3         | 5.17%   |
| Acer Integrated Camera                        | 3         | 5.17%   |
| Syntek EasyCamera                             | 2         | 3.45%   |
| Realtek Integrated Webcam                     | 2         | 3.45%   |
| Microdia Dell Laptop Integrated Webcam HD     | 2         | 3.45%   |
| Logitech Webcam C270                          | 2         | 3.45%   |
| Chicony Sony Visual Communication Camera      | 2         | 3.45%   |
| Apple FaceTime HD Camera                      | 2         | 3.45%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 3.45%   |
| Acer HD Webcam                                | 2         | 3.45%   |
| Unknown Realtek PC Camera                     | 1         | 1.72%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.72%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.72%   |
| Sunplus Integrated_Webcam_HD                  | 1         | 1.72%   |
| Sunplus HD WebCam                             | 1         | 1.72%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.72%   |
| Realtek LG Camera                             | 1         | 1.72%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.72%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.72%   |
| Quanta HD Webcam                              | 1         | 1.72%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.72%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.72%   |
| Microdia Integrated Webcam HD                 | 1         | 1.72%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.72%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.72%   |
| Lite-On Integrated Camera                     | 1         | 1.72%   |
| IMC Networks USB Camera                       | 1         | 1.72%   |
| IMC Networks EasyCamera                       | 1         | 1.72%   |
| Chicony Webcam                                | 1         | 1.72%   |
| Chicony VGA WebCam                            | 1         | 1.72%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.72%   |
| Chicony Integrated Camera                     | 1         | 1.72%   |
| Chicony HP HD Webcam [Fixed]                  | 1         | 1.72%   |
| Chicony HP HD Camera                          | 1         | 1.72%   |
| Chicony EasyCamera                            | 1         | 1.72%   |
| Chicony 1.3M Webcam                           | 1         | 1.72%   |
| Aveo USB2.0 Camera                            | 1         | 1.72%   |
| Acer SunplusIT Integrated Camera              | 1         | 1.72%   |
| Acer Lenovo EasyCamera                        | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| Synaptics                  | 2         | 22.22%  |
| Upek                       | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |
| Samsung Electronics        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                             | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                          | 1         | 11.11%  |
| Samsung Fingerprint Device                                  | 1         | 11.11%  |

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
| 0     | 58        | 38.16%  |
| 1     | 49        | 32.24%  |
| 2     | 20        | 13.16%  |
| 3     | 16        | 10.53%  |
| 5     | 5         | 3.29%   |
| 4     | 4         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 87        | 53.37%  |
| Card reader              | 25        | 15.34%  |
| Net/wireless             | 19        | 11.66%  |
| Bluetooth                | 16        | 9.82%   |
| Fingerprint reader       | 9         | 5.52%   |
| Sound                    | 5         | 3.07%   |
| Network                  | 1         | 0.61%   |
| Firewire controller      | 1         | 0.61%   |

