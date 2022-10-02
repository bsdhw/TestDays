BSD in Australia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 263

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| Sophos        | XG                          | Firewall    | [1540138670](https://bsd-hardware.info/?probe=1540138670) | Sep 13, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [d448c2dd6c](https://bsd-hardware.info/?probe=d448c2dd6c) | Aug 19, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [eee1d83783](https://bsd-hardware.info/?probe=eee1d83783) | Aug 14, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9130257c6a](https://bsd-hardware.info/?probe=9130257c6a) | Aug 09, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [aad241ba36](https://bsd-hardware.info/?probe=aad241ba36) | Aug 08, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [f9b42e4a75](https://bsd-hardware.info/?probe=f9b42e4a75) | Jul 27, 2022 |
| Protectli     | VP2410                      | Desktop     | [db66cc446e](https://bsd-hardware.info/?probe=db66cc446e) | Jul 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ee70a58bd6](https://bsd-hardware.info/?probe=ee70a58bd6) | Jul 26, 2022 |
| HP            | 8055                        | Desktop     | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| AZW           | GK55                        | Desktop     | [40d9df6faa](https://bsd-hardware.info/?probe=40d9df6faa) | Jul 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f68c3695ea](https://bsd-hardware.info/?probe=f68c3695ea) | Jul 08, 2022 |
| Firewalla     | FirewallaGold               | Firewall    | [e7d2dca92d](https://bsd-hardware.info/?probe=e7d2dca92d) | Jul 02, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [a3aff65df2](https://bsd-hardware.info/?probe=a3aff65df2) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| HP            | ProLiant ML10 v2            | Desktop     | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [1de9982d19](https://bsd-hardware.info/?probe=1de9982d19) | Jun 05, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | Desktop     | [94bdba6302](https://bsd-hardware.info/?probe=94bdba6302) | Jun 04, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | ZBook 14                    | Notebook    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| ASUSTek       | P9D-C Series                | Server      | [ac16999995](https://bsd-hardware.info/?probe=ac16999995) | Apr 22, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| MSI           | 2A9C                        | Desktop     | [9417bdd744](https://bsd-hardware.info/?probe=9417bdd744) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | Desktop     | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| HP            | Notebook                    | Notebook    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | Notebook    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [46c59d0de8](https://bsd-hardware.info/?probe=46c59d0de8) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | Desktop     | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | Desktop     | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Dell          | 0F0XJ6 A06                  | Server      | [e0599f5c69](https://bsd-hardware.info/?probe=e0599f5c69) | Mar 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | Desktop     | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| HP            | 8103 A01                    | Mini pc     | [23b35e5b18](https://bsd-hardware.info/?probe=23b35e5b18) | Mar 10, 2022 |
| Dell          | G5 5590                     | Notebook    | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| HP            | 8103 A01                    | Mini pc     | [d9222c59e5](https://bsd-hardware.info/?probe=d9222c59e5) | Feb 12, 2022 |
| MSI           | MS-B1831                    | Desktop     | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | Desktop     | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Dell          | Latitude E7450              | Notebook    | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0CN7CM A09                  | Server      | [3ec53e21df](https://bsd-hardware.info/?probe=3ec53e21df) | Jan 29, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d180b0d394](https://bsd-hardware.info/?probe=d180b0d394) | Jan 25, 2022 |
| HP            | 8103 A01                    | Mini pc     | [147f49ca42](https://bsd-hardware.info/?probe=147f49ca42) | Jan 22, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [2f22679aa6](https://bsd-hardware.info/?probe=2f22679aa6) | Jan 10, 2022 |
| HP            | 1998                        | Desktop     | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | Desktop     | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [c55f468566](https://bsd-hardware.info/?probe=c55f468566) | Dec 12, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [82c010f13c](https://bsd-hardware.info/?probe=82c010f13c) | Dec 09, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| HP            | 8103 A01                    | Mini pc     | [12763190f5](https://bsd-hardware.info/?probe=12763190f5) | Nov 16, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8e779b15f3](https://bsd-hardware.info/?probe=8e779b15f3) | Nov 15, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | Desktop     | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| HP            | 8103 A01                    | Mini pc     | [a6c494cc8f](https://bsd-hardware.info/?probe=a6c494cc8f) | Nov 08, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | Desktop     | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | Desktop     | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d2ffea0e21](https://bsd-hardware.info/?probe=d2ffea0e21) | Oct 29, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [06db2a9c2f](https://bsd-hardware.info/?probe=06db2a9c2f) | Oct 29, 2021 |
| HP            | 18E9                        | Desktop     | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | Desktop     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | Desktop     | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3fafbcecc5](https://bsd-hardware.info/?probe=3fafbcecc5) | Sep 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [c08c97aacc](https://bsd-hardware.info/?probe=c08c97aacc) | Sep 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [2494d9d2db](https://bsd-hardware.info/?probe=2494d9d2db) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [28bbeb8b2e](https://bsd-hardware.info/?probe=28bbeb8b2e) | Sep 26, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | Desktop     | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| HP            | 8103 A01                    | Mini pc     | [341ca2f887](https://bsd-hardware.info/?probe=341ca2f887) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Intel         | SandyBridge Platform        | Notebook    | [f0aaf635c3](https://bsd-hardware.info/?probe=f0aaf635c3) | Sep 02, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | Desktop     | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| HP            | 8103 A01                    | Mini pc     | [f02d97dbeb](https://bsd-hardware.info/?probe=f02d97dbeb) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | Desktop     | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7b20265c8e](https://bsd-hardware.info/?probe=7b20265c8e) | Aug 14, 2021 |
| Acer          | Veriton X4610G              | Desktop     | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| Microsoft     | Surface Go                  | Tablet      | [1dfbc72509](https://bsd-hardware.info/?probe=1dfbc72509) | Jul 30, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | Desktop     | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0NRF6V A01                  | Server      | [70fffc6930](https://bsd-hardware.info/?probe=70fffc6930) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| HP            | 8103 A01                    | Mini pc     | [ffd1dd6fb1](https://bsd-hardware.info/?probe=ffd1dd6fb1) | Jun 14, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | Desktop     | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| HP            | 8103 A01                    | Mini pc     | [8549e8b3c4](https://bsd-hardware.info/?probe=8549e8b3c4) | Jun 09, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| HP            | 8103 A01                    | Mini pc     | [1b26a44944](https://bsd-hardware.info/?probe=1b26a44944) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Dell          | 0CN7CM A09                  | Server      | [92a93d51c5](https://bsd-hardware.info/?probe=92a93d51c5) | May 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [a09fbe5fcc](https://bsd-hardware.info/?probe=a09fbe5fcc) | May 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | Desktop     | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| Sophos        | SG                          | Firewall    | [88ea908224](https://bsd-hardware.info/?probe=88ea908224) | Apr 14, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [821c81e652](https://bsd-hardware.info/?probe=821c81e652) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| ASUSTek       | TP500LNG                    | Notebook    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Dell          | G5 5590                     | Notebook    | [18863bc535](https://bsd-hardware.info/?probe=18863bc535) | Apr 05, 2021 |
| Sophos        | SG                          | Firewall    | [76a33ea7ea](https://bsd-hardware.info/?probe=76a33ea7ea) | Mar 28, 2021 |
| Sophos        | SG                          | Firewall    | [487e450695](https://bsd-hardware.info/?probe=487e450695) | Mar 23, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [32dfd5e52a](https://bsd-hardware.info/?probe=32dfd5e52a) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [70304f9c5d](https://bsd-hardware.info/?probe=70304f9c5d) | Mar 11, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [953b768755](https://bsd-hardware.info/?probe=953b768755) | Mar 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [d436c0a897](https://bsd-hardware.info/?probe=d436c0a897) | Feb 27, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [13c1f72630](https://bsd-hardware.info/?probe=13c1f72630) | Feb 24, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2833c6695](https://bsd-hardware.info/?probe=a2833c6695) | Feb 08, 2021 |
| ASUSTek       | P5E3                        | Desktop     | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a201c5f713](https://bsd-hardware.info/?probe=a201c5f713) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [d0a5d1cb86](https://bsd-hardware.info/?probe=d0a5d1cb86) | Feb 08, 2021 |
| Lenovo        | ThinkPad E420 1141CTO       | Notebook    | [a51cf81e58](https://bsd-hardware.info/?probe=a51cf81e58) | Feb 06, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | Desktop     | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| HP            | 802E                        | Desktop     | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Lenovo        | 312D SDK0J40700 WIN 3258... | Mini pc     | [d15116d2eb](https://bsd-hardware.info/?probe=d15116d2eb) | Jan 25, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | Desktop     | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| Toshiba       | KIRA                        | Notebook    | [1ee77fde0b](https://bsd-hardware.info/?probe=1ee77fde0b) | Jan 18, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [de7d8622aa](https://bsd-hardware.info/?probe=de7d8622aa) | Dec 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7f6ebffad8](https://bsd-hardware.info/?probe=7f6ebffad8) | Dec 18, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [ddc907ccf4](https://bsd-hardware.info/?probe=ddc907ccf4) | Dec 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1414d7ae80](https://bsd-hardware.info/?probe=1414d7ae80) | Dec 16, 2020 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [4e217288fe](https://bsd-hardware.info/?probe=4e217288fe) | Dec 16, 2020 |
| ASUSTek       | K72F                        | Notebook    | [321cd9d139](https://bsd-hardware.info/?probe=321cd9d139) | Dec 08, 2020 |
| ASUSTek       | K72F                        | Notebook    | [b36ff0b052](https://bsd-hardware.info/?probe=b36ff0b052) | Dec 08, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| HP            | Setzer                      | Notebook    | [da7914cdd5](https://bsd-hardware.info/?probe=da7914cdd5) | Nov 22, 2020 |
| Lenovo        | ThinkPad T450 20BVA020AU    | Notebook    | [5d8bce59e8](https://bsd-hardware.info/?probe=5d8bce59e8) | Nov 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 0TW856 A02                  | Server      | [f181777604](https://bsd-hardware.info/?probe=f181777604) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | Desktop     | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 2320JXM       | Notebook    | [cdbf62a168](https://bsd-hardware.info/?probe=cdbf62a168) | Oct 29, 2020 |
| Lenovo        | ThinkPad X60s 17033JM       | Notebook    | [67e701adb7](https://bsd-hardware.info/?probe=67e701adb7) | Oct 21, 2020 |
| Unknown       | Unknown                     | Desktop     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Acer          | Peppy                       | Notebook    | [d68bd5cbb5](https://bsd-hardware.info/?probe=d68bd5cbb5) | Oct 02, 2020 |
| Acer          | Peppy                       | Notebook    | [26058cddbf](https://bsd-hardware.info/?probe=26058cddbf) | Oct 02, 2020 |
| Unknown       | Unknown                     | Desktop     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Apple         | MacBookAir5,1               | Notebook    | [6cced6fcf0](https://bsd-hardware.info/?probe=6cced6fcf0) | Sep 23, 2020 |
| Lenovo        | ThinkPad T460p 20FXCTO1W... | Notebook    | [b62876dd94](https://bsd-hardware.info/?probe=b62876dd94) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [e4d2dcda5b](https://bsd-hardware.info/?probe=e4d2dcda5b) | Jul 31, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [764aaaa200](https://bsd-hardware.info/?probe=764aaaa200) | Jun 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [158ff0f1b6](https://bsd-hardware.info/?probe=158ff0f1b6) | Jun 04, 2020 |
| Lenovo        | ThinkPad X220 4291C35       | Notebook    | [f22c83f68b](https://bsd-hardware.info/?probe=f22c83f68b) | May 31, 2020 |
| HP            | ProLiant ML10 v2            | Desktop     | [aea3696f41](https://bsd-hardware.info/?probe=aea3696f41) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 22.1     | 9         | 4.17%   |
| OPNsense 21.7.7   | 8         | 3.7%    |
| OPNsense 22.1.6   | 7         | 3.24%   |
| helloSystem 0.5.0 | 7         | 3.24%   |
| OPNsense 21.7.1   | 6         | 2.78%   |
| OPNsense 21.1.5   | 6         | 2.78%   |
| OPNsense 21.1.4   | 6         | 2.78%   |
| OPNsense 21.1.3   | 6         | 2.78%   |
| OPNsense 20.7.8   | 6         | 2.78%   |
| helloSystem 0.4.0 | 6         | 2.78%   |
| OPNsense 22.7.4   | 5         | 2.31%   |
| OPNsense 22.1.10  | 5         | 2.31%   |
| OPNsense 21.7.3   | 5         | 2.31%   |
| OPNsense 21.7.2   | 5         | 2.31%   |
| OPNsense 21.1.6   | 5         | 2.31%   |
| OPNsense 21.1.2   | 5         | 2.31%   |
| helloSystem 0.6.0 | 5         | 2.31%   |
| FreeBSD 13.0      | 5         | 2.31%   |
| FreeBSD 12.2      | 5         | 2.31%   |
| FreeBSD 12.1-p10  | 5         | 2.31%   |
| OPNsense 22.1.4   | 4         | 1.85%   |
| OPNsense 21.1.1   | 4         | 1.85%   |
| OPNsense 21.1     | 4         | 1.85%   |
| OpenBSD 6.8       | 4         | 1.85%   |
| helloSystem 0.7.0 | 4         | 1.85%   |
| FreeBSD 13.1      | 4         | 1.85%   |
| OPNsense 22.7.3   | 3         | 1.39%   |
| OPNsense 21.7.5   | 3         | 1.39%   |
| OPNsense 21.7.4   | 3         | 1.39%   |
| OPNsense 21.1.8   | 3         | 1.39%   |
| FreeBSD 13.0-p4   | 3         | 1.39%   |
| OPNsense 22.7     | 2         | 0.93%   |
| OPNsense 22.1.8   | 2         | 0.93%   |
| OPNsense 22.1.5   | 2         | 0.93%   |
| OPNsense 22.1.3   | 2         | 0.93%   |
| OPNsense 22.1.2   | 2         | 0.93%   |
| OPNsense 22.1.1   | 2         | 0.93%   |
| OPNsense 21.7     | 2         | 0.93%   |
| OPNsense 20.7     | 2         | 0.93%   |
| GhostBSD 20.04.02 | 2         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 95        | 55.56%  |
| FreeBSD     | 38        | 22.22%  |
| helloSystem | 21        | 12.28%  |
| OpenBSD     | 5         | 2.92%   |
| TrueNAS     | 4         | 2.34%   |
| NomadBSD    | 2         | 1.17%   |
| GhostBSD    | 2         | 1.17%   |
| FreeNAS     | 2         | 1.17%   |
| NetBSD      | 1         | 0.58%   |
| FuguIta     | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 168       | 98.82%  |
| i386  | 1         | 0.59%   |
| arm64 | 1         | 0.59%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 114       | 65.9%   |
| helloDesktop | 23        | 13.29%  |
| KDE5         | 7         | 4.05%   |
| XFCE         | 6         | 3.47%   |
| GNOME        | 6         | 3.47%   |
| TWM          | 4         | 2.31%   |
| fvwm         | 4         | 2.31%   |
| i3           | 3         | 1.73%   |
| Openbox      | 2         | 1.16%   |
| MATE         | 1         | 0.58%   |
| Lumina       | 1         | 0.58%   |
| Fluxbox      | 1         | 0.58%   |
| AwesomeWM    | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 119       | 70%     |
| X11     | 49        | 28.82%  |
| Wayland | 2         | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 129       | 75.44%  |
| SLiM    | 24        | 14.04%  |
| SDDM    | 7         | 4.09%   |
| XDM     | 4         | 2.34%   |
| LightDM | 3         | 1.75%   |
| Ly      | 2         | 1.17%   |
| PCDM    | 1         | 0.58%   |
| GDM     | 1         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 113       | 64.94%  |
| en_US           | 30        | 17.24%  |
| C               | 17        | 9.77%   |
| en_AU           | 12        | 6.9%    |
| en_AU.US-ASCII  | 1         | 0.57%   |
| en_AU.ISO8859-1 | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 132       | 77.65%  |
| BIOS | 38        | 22.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 94        | 54.65%  |
| Zfs    | 70        | 40.7%   |
| Ffs    | 6         | 3.49%   |
| Cd9660 | 2         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 150       | 88.24%  |
| MBR     | 18        | 10.59%  |
| BSD     | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 25        | 14.71%  |
| Lenovo                     | 22        | 12.94%  |
| Dell                       | 19        | 11.18%  |
| ASUSTek Computer           | 13        | 7.65%   |
| Protectli                  | 12        | 7.06%   |
| Intel                      | 12        | 7.06%   |
| Unknown                    | 9         | 5.29%   |
| Gigabyte Technology        | 8         | 4.71%   |
| ASRock                     | 8         | 4.71%   |
| Apple                      | 6         | 3.53%   |
| Toshiba                    | 3         | 1.76%   |
| MSI                        | 3         | 1.76%   |
| Acer                       | 3         | 1.76%   |
| Sophos                     | 2         | 1.18%   |
| MW                         | 2         | 1.18%   |
| AMI                        | 2         | 1.18%   |
| Yanling                    | 1         | 0.59%   |
| Unknown                    | 1         | 0.59%   |
| Supermicro                 | 1         | 0.59%   |
| Shuttle                    | 1         | 0.59%   |
| ShenZhen MinWin Technology | 1         | 0.59%   |
| SeeedStudio                | 1         | 0.59%   |
| Samsung Electronics        | 1         | 0.59%   |
| Raspberry Pi Foundation    | 1         | 0.59%   |
| Radxa                      | 1         | 0.59%   |
| PC Engines                 | 1         | 0.59%   |
| Microsoft                  | 1         | 0.59%   |
| Inventec                   | 1         | 0.59%   |
| HARDKERNEL                 | 1         | 0.59%   |
| Gateway                    | 1         | 0.59%   |
| Foxconn                    | 1         | 0.59%   |
| Firewalla                  | 1         | 0.59%   |
| Cisco                      | 1         | 0.59%   |
| AZW                        | 1         | 0.59%   |
| AOpen                      | 1         | 0.59%   |
| ADI Engineering            | 1         | 0.59%   |
| AAEON                      | 1         | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 10        | 5.88%   |
| Protectli FW4B                                                                           | 8         | 4.71%   |
| HP t730 Thin Client                                                                      | 7         | 4.12%   |
| HP ProLiant MicroServer                                                                  | 3         | 1.76%   |
| Dell OptiPlex 9020                                                                       | 3         | 1.76%   |
| Protectli VP2410                                                                         | 2         | 1.18%   |
| MW GMLK-2_5G4L                                                                           | 2         | 1.18%   |
| Intel Q3XXG4-P V1.0                                                                      | 2         | 1.18%   |
| Intel NUC10i5FNH                                                                         | 2         | 1.18%   |
| HP ProLiant MicroServer Gen8                                                             | 2         | 1.18%   |
| Dell OptiPlex 3010                                                                       | 2         | 1.18%   |
| ASUS All Series                                                                          | 2         | 1.18%   |
| Yanling YL-KBR6L                                                                         | 1         | 0.59%   |
| Toshiba Satellite L50-A                                                                  | 1         | 0.59%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.59%   |
| Toshiba KIRA                                                                             | 1         | 0.59%   |
| Supermicro Super Server                                                                  | 1         | 0.59%   |
| Sophos XG                                                                                | 1         | 0.59%   |
| Sophos SG                                                                                | 1         | 0.59%   |
| Shuttle DH370                                                                            | 1         | 0.59%   |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.59%   |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.59%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.59%   |
| RPi Raspberry Pi                                                                         | 1         | 0.59%   |
| Radxa ROCK Pi X                                                                          | 1         | 0.59%   |
| Protectli FW6                                                                            | 1         | 0.59%   |
| Protectli FW2B                                                                           | 1         | 0.59%   |
| PC Engines apu4                                                                          | 1         | 0.59%   |
| MSI Pro 3130 Small Form Factor PC                                                        | 1         | 0.59%   |
| MSI MS-7C95                                                                              | 1         | 0.59%   |
| MSI CML-U PRO Cubi 5 (MS-B183)                                                           | 1         | 0.59%   |
| Microsoft Surface Go                                                                     | 1         | 0.59%   |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]-                                                  | 1         | 0.59%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 0.59%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 0.59%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 0.59%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 4th 20FC0019AU                                                 | 1         | 0.59%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB001XAU                                                 | 1         | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 14        | 8.24%   |
| Dell OptiPlex                  | 11        | 6.47%   |
| Unknown                        | 10        | 5.88%   |
| Protectli FW4B                 | 8         | 4.71%   |
| HP t730                        | 7         | 4.12%   |
| HP ProLiant                    | 7         | 4.12%   |
| Lenovo ThinkCentre             | 6         | 3.53%   |
| Dell PowerEdge                 | 5         | 2.94%   |
| HP EliteDesk                   | 3         | 1.76%   |
| Protectli VP2410               | 2         | 1.18%   |
| MW GMLK-2                      | 2         | 1.18%   |
| Intel Q3XXG4-P                 | 2         | 1.18%   |
| Intel NUC10i5FNH               | 2         | 1.18%   |
| ASUS ROG                       | 2         | 1.18%   |
| ASUS PRIME                     | 2         | 1.18%   |
| ASUS All                       | 2         | 1.18%   |
| ASRock X370                    | 2         | 1.18%   |
| Acer Veriton                   | 2         | 1.18%   |
| Yanling YL-KBR6L               | 1         | 0.59%   |
| Toshiba Satellite              | 1         | 0.59%   |
| Toshiba PORTEGE                | 1         | 0.59%   |
| Toshiba KIRA                   | 1         | 0.59%   |
| Supermicro Super               | 1         | 0.59%   |
| Sophos XG                      | 1         | 0.59%   |
| Sophos SG                      | 1         | 0.59%   |
| Shuttle DH370                  | 1         | 0.59%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.59%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.59%   |
| Samsung 350V5C                 | 1         | 0.59%   |
| RPi Raspberry                  | 1         | 0.59%   |
| Radxa ROCK                     | 1         | 0.59%   |
| Protectli FW6                  | 1         | 0.59%   |
| Protectli FW2B                 | 1         | 0.59%   |
| PC Engines apu4                | 1         | 0.59%   |
| MSI Pro                        | 1         | 0.59%   |
| MSI MS-7C95                    | 1         | 0.59%   |
| MSI CML-U                      | 1         | 0.59%   |
| Microsoft Surface              | 1         | 0.59%   |
| Lenovo ThinkSystem             | 1         | 0.59%   |
| Lenovo G40-70                  | 1         | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 22        | 12.94%  |
| 2020    | 21        | 12.35%  |
| 2015    | 18        | 10.59%  |
| 2013    | 16        | 9.41%   |
| 2021    | 14        | 8.24%   |
| 2018    | 14        | 8.24%   |
| 2017    | 10        | 5.88%   |
| 2016    | 10        | 5.88%   |
| 2014    | 10        | 5.88%   |
| 2012    | 10        | 5.88%   |
| 2011    | 9         | 5.29%   |
| 2009    | 5         | 2.94%   |
| 2010    | 4         | 2.35%   |
| Unknown | 3         | 1.76%   |
| 2022    | 2         | 1.18%   |
| 2007    | 2         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 104       | 61.18%  |
| Notebook       | 34        | 20%     |
| Mini pc        | 18        | 10.59%  |
| Server         | 7         | 4.12%   |
| Firewall       | 3         | 1.76%   |
| All in one     | 2         | 1.18%   |
| System on chip | 1         | 0.59%   |
| Tablet         | 1         | 0.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 163       | 95.88%  |
| Yes  | 7         | 4.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 81        | 46.02%  |
| 16.01-24.0  | 37        | 21.02%  |
| 4.01-8.0    | 28        | 15.91%  |
| 32.01-64.0  | 12        | 6.82%   |
| 64.01-256.0 | 6         | 3.41%   |
| 2.01-3.0    | 4         | 2.27%   |
| 3.01-4.0    | 3         | 1.7%    |
| 24.01-32.0  | 3         | 1.7%    |
| 1.01-2.0    | 2         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 88        | 49.16%  |
| 0.51-1.0   | 49        | 27.37%  |
| 1.01-2.0   | 18        | 10.06%  |
| 4.01-8.0   | 8         | 4.47%   |
| 2.01-3.0   | 5         | 2.79%   |
| 8.01-16.0  | 3         | 1.68%   |
| 3.01-4.0   | 2         | 1.12%   |
| 16.01-24.0 | 2         | 1.12%   |
| 32.01-64.0 | 1         | 0.56%   |
| 24.01-32.0 | 1         | 0.56%   |
| 0          | 1         | 0.56%   |
| Unknown    | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 68.02%  |
| 2      | 19        | 11.05%  |
| 0      | 15        | 8.72%   |
| 3      | 10        | 5.81%   |
| 4      | 6         | 3.49%   |
| 5      | 2         | 1.16%   |
| 10     | 1         | 0.58%   |
| 7      | 1         | 0.58%   |
| 6      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 81.18%  |
| Yes       | 32        | 18.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 95.29%  |
| No        | 8         | 4.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 60.82%  |
| Yes       | 67        | 39.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 73.1%   |
| Yes       | 46        | 26.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 170       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 41        | 22.4%   |
| Melbourne      | 31        | 16.94%  |
| Brisbane       | 23        | 12.57%  |
| Perth          | 22        | 12.02%  |
| Adelaide       | 6         | 3.28%   |
| Canberra       | 5         | 2.73%   |
| Hobart         | 3         | 1.64%   |
| Blackburn      | 3         | 1.64%   |
| Southport      | 2         | 1.09%   |
| Ryde           | 2         | 1.09%   |
| Morwell        | 2         | 1.09%   |
| Marrickville   | 2         | 1.09%   |
| Kellyville     | 2         | 1.09%   |
| East Malvern   | 2         | 1.09%   |
| Burwood        | 2         | 1.09%   |
| Wollongong     | 1         | 0.55%   |
| Wheelers Hill  | 1         | 0.55%   |
| Wallan         | 1         | 0.55%   |
| Townsville     | 1         | 0.55%   |
| South Yarra    | 1         | 0.55%   |
| Shell Cove     | 1         | 0.55%   |
| Rosanna        | 1         | 0.55%   |
| Ringwood       | 1         | 0.55%   |
| Northcote      | 1         | 0.55%   |
| North Shore    | 1         | 0.55%   |
| Noble Park     | 1         | 0.55%   |
| Mount Waverley | 1         | 0.55%   |
| Mount Eliza    | 1         | 0.55%   |
| Mooroolbark    | 1         | 0.55%   |
| Mandurah       | 1         | 0.55%   |
| Malvern        | 1         | 0.55%   |
| Kurunjang      | 1         | 0.55%   |
| Ipswich        | 1         | 0.55%   |
| Gold Coast     | 1         | 0.55%   |
| Geelong        | 1         | 0.55%   |
| Engadine       | 1         | 0.55%   |
| Dowerin        | 1         | 0.55%   |
| Darlinghurst   | 1         | 0.55%   |
| Dandenong      | 1         | 0.55%   |
| Croydon        | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 39     | 14.95%  |
| Samsung Electronics | 28        | 39     | 14.43%  |
| WDC                 | 24        | 60     | 12.37%  |
| Intel               | 15        | 22     | 7.73%   |
| Kingston            | 14        | 21     | 7.22%   |
| Toshiba             | 13        | 19     | 6.7%    |
| SanDisk             | 10        | 17     | 5.15%   |
| Crucial             | 8         | 10     | 4.12%   |
| Hoodisk             | 6         | 12     | 3.09%   |
| Protectli           | 3         | 3      | 1.55%   |
| Phison              | 3         | 3      | 1.55%   |
| Hewlett-Packard     | 3         | 6      | 1.55%   |
| A-DATA Technology   | 3         | 8      | 1.55%   |
| Transcend           | 2         | 3      | 1.03%   |
| Micron Technology   | 2         | 4      | 1.03%   |
| Hitachi             | 2         | 5      | 1.03%   |
| HGST                | 2         | 2      | 1.03%   |
| Gigabyte Technology | 2         | 2      | 1.03%   |
| Dogfish             | 2         | 2      | 1.03%   |
| Apple               | 2         | 2      | 1.03%   |
| XUNZHE              | 1         | 1      | 0.52%   |
| Vaseky              | 1         | 2      | 0.52%   |
| Union Memory        | 1         | 1      | 0.52%   |
| SPCC                | 1         | 5      | 0.52%   |
| SK hynix            | 1         | 3      | 0.52%   |
| Silicon Motion      | 1         | 1      | 0.52%   |
| ShiJi               | 1         | 1      | 0.52%   |
| Plextor             | 1         | 2      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| Maxtor              | 1         | 1      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| Lenovo              | 1         | 1      | 0.52%   |
| KingSpec            | 1         | 1      | 0.52%   |
| KingDian            | 1         | 1      | 0.52%   |
| Jetflash            | 1         | 1      | 0.52%   |
| Fujitsu             | 1         | 1      | 0.52%   |
| Fordisk             | 1         | 1      | 0.52%   |
| China               | 1         | 1      | 0.52%   |
| BIWIN               | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 6         | 2.83%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 1.42%   |
| Kingston SA400S37480G 480GB                 | 3         | 1.42%   |
| Kingston SA400S37120G 120GB                 | 3         | 1.42%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 1.42%   |
| WDC WDS120G2G0B-00EPW0 120GB                | 2         | 0.94%   |
| WDC WD40EFRX-68N32N0 4TB                    | 2         | 0.94%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 2         | 0.94%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 2         | 0.94%   |
| WDC WD20EZAZ-00GGJB0 2TB                    | 2         | 0.94%   |
| Toshiba THNSF5256GPUK 256GB                 | 2         | 0.94%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.94%   |
| Seagate ST9500325AS 500GB                   | 2         | 0.94%   |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 0.94%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 0.94%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 2         | 0.94%   |
| SanDisk SDSA6MM-032G-1006 32GB              | 2         | 0.94%   |
| Samsung SSD 860 EVO 500GB                   | 2         | 0.94%   |
| Samsung SSD 850 EVO 500GB                   | 2         | 0.94%   |
| Samsung SSD 840 EVO 120GB                   | 2         | 0.94%   |
| Samsung MZ7LN128HCHP-000H1 128GB            | 2         | 0.94%   |
| Protectli 120GB mSATA                       | 2         | 0.94%   |
| Micron MTFDDAK256MAM-1K1 256GB              | 2         | 0.94%   |
| Kingston SA400S37240G 240GB                 | 2         | 0.94%   |
| Crucial CT250MX500SSD1 250GB                | 2         | 0.94%   |
| XUNZHE MSATA 128GB                          | 1         | 0.47%   |
| WDC WDS500G2B0B-00YS70 500GB                | 1         | 0.47%   |
| WDC WDS500G1R0B-68A4Z0 500GB                | 1         | 0.47%   |
| WDC WDS480G2G0A-00JH30 480GB                | 1         | 0.47%   |
| WDC WDS250G2B0C-00PXH0 250GB                | 1         | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB                | 1         | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB                | 1         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB                | 1         | 0.47%   |
| WDC WD80EFAX-68KNBN0 8TB                    | 1         | 0.47%   |
| WDC WD7500BPKX-00HPJT0 752GB                | 1         | 0.47%   |
| WDC WD5000BPKT-00PK4T0 500GB                | 1         | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 1         | 0.47%   |
| WDC WD4000AAKS-00TMA0 400GB                 | 1         | 0.47%   |
| WDC WD30EFRX-68AX9N0 3TB                    | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 37     | 42.86%  |
| WDC                 | 17        | 49     | 26.98%  |
| Toshiba             | 6         | 8      | 9.52%   |
| Samsung Electronics | 3         | 5      | 4.76%   |
| Hewlett-Packard     | 3         | 6      | 4.76%   |
| Hitachi             | 2         | 5      | 3.17%   |
| HGST                | 2         | 2      | 3.17%   |
| Maxtor              | 1         | 1      | 1.59%   |
| Jetflash            | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 31     | 20.75%  |
| Kingston            | 14        | 21     | 13.21%  |
| Intel               | 13        | 20     | 12.26%  |
| SanDisk             | 10        | 17     | 9.43%   |
| WDC                 | 7         | 10     | 6.6%    |
| Hoodisk             | 6         | 12     | 5.66%   |
| Crucial             | 5         | 5      | 4.72%   |
| Toshiba             | 3         | 6      | 2.83%   |
| Protectli           | 3         | 3      | 2.83%   |
| Transcend           | 2         | 3      | 1.89%   |
| Phison              | 2         | 2      | 1.89%   |
| Micron Technology   | 2         | 4      | 1.89%   |
| Dogfish             | 2         | 2      | 1.89%   |
| XUNZHE              | 1         | 1      | 0.94%   |
| Vaseky              | 1         | 2      | 0.94%   |
| ShiJi               | 1         | 1      | 0.94%   |
| Plextor             | 1         | 2      | 0.94%   |
| Patriot             | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| LITEONIT            | 1         | 1      | 0.94%   |
| Lenovo              | 1         | 1      | 0.94%   |
| KingSpec            | 1         | 1      | 0.94%   |
| KingDian            | 1         | 1      | 0.94%   |
| Fordisk             | 1         | 1      | 0.94%   |
| China               | 1         | 1      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |
| Apacer              | 1         | 1      | 0.94%   |
| A-DATA Technology   | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 98        | 153    | 56.32%  |
| HDD  | 51        | 115    | 29.31%  |
| NVMe | 25        | 40     | 14.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 136       | 268    | 84.47%  |
| NVMe | 25        | 40     | 15.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 189    | 76.62%  |
| 0.51-1.0   | 15        | 24     | 9.74%   |
| 1.01-2.0   | 12        | 31     | 7.79%   |
| 3.01-4.0   | 4         | 9      | 2.6%    |
| 2.01-3.0   | 2         | 8      | 1.3%    |
| 4.01-10.0  | 2         | 5      | 1.3%    |
| 10.01-20.0 | 1         | 2      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 42.94%  |
| 251-500        | 27        | 15.88%  |
| 1-20           | 22        | 12.94%  |
| 51-100         | 18        | 10.59%  |
| 21-50          | 12        | 7.06%   |
| 501-1000       | 12        | 7.06%   |
| 1001-2000      | 3         | 1.76%   |
| 2001-3000      | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 159       | 89.83%  |
| 21-50     | 12        | 6.78%   |
| 51-100    | 3         | 1.69%   |
| 101-250   | 2         | 1.13%   |
| 1001-2000 | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 1      | 4.55%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1         | 2      | 4.55%   |
| WDC WD20EARX-008FB0 2TB           | 1         | 3      | 4.55%   |
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 4.55%   |
| Seagate ST3250310AS 250GB         | 1         | 1      | 4.55%   |
| Seagate ST2000DL003-9VT166 2TB    | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1CH162 1TB    | 1         | 1      | 4.55%   |
| SanDisk SDSSDA240G 240GB          | 1         | 1      | 4.55%   |
| Samsung Electronics HM500LI 500GB | 1         | 2      | 4.55%   |
| Phison SATA SSD 32GB              | 1         | 1      | 4.55%   |
| Kingston SNS4151S316G 16GB        | 1         | 1      | 4.55%   |
| Kingston SA400S37480G 480GB       | 1         | 1      | 4.55%   |
| Intel SSDSC2BW120H6 120GB         | 1         | 1      | 4.55%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 4.55%   |
| Hitachi HDS721010KLA330 1TB       | 1         | 1      | 4.55%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 4.55%   |
| Hewlett-Packard VB0250EAVER 250GB | 1         | 1      | 4.55%   |
| Crucial CT275MX300SSD4 275GB      | 1         | 1      | 4.55%   |
| Apple SSD SM256E 256GB            | 1         | 1      | 4.55%   |
| Apacer AS330 240GB                | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 23.81%  |
| WDC                 | 3         | 7      | 14.29%  |
| Kingston            | 2         | 2      | 9.52%   |
| Intel               | 2         | 2      | 9.52%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 2      | 4.76%   |
| Phison              | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Hewlett-Packard     | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |
| Apple               | 1         | 1      | 4.76%   |
| Apacer              | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 45.45%  |
| WDC                 | 2         | 6      | 18.18%  |
| Samsung Electronics | 1         | 2      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |
| Hewlett-Packard     | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 16     | 52.38%  |
| SSD  | 10        | 10     | 47.62%  |

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
| Works    | 139       | 281    | 86.34%  |
| Malfunc  | 21        | 26     | 13.04%  |
| Detected | 1         | 1      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 135       | 69.23%  |
| AMD                       | 24        | 12.31%  |
| Broadcom / LSI            | 7         | 3.59%   |
| Toshiba                   | 4         | 2.05%   |
| Samsung Electronics       | 4         | 2.05%   |
| Phison Electronics        | 4         | 2.05%   |
| Silicon Motion            | 2         | 1.03%   |
| Seagate Technology        | 2         | 1.03%   |
| Micron/Crucial Technology | 2         | 1.03%   |
| Union Memory (Shenzhen)   | 1         | 0.51%   |
| Silicon Image             | 1         | 0.51%   |
| SanDisk                   | 1         | 0.51%   |
| Realtek Semiconductor     | 1         | 0.51%   |
| QLogic                    | 1         | 0.51%   |
| Nvidia                    | 1         | 0.51%   |
| Micron Technology         | 1         | 0.51%   |
| JMicron Technology        | 1         | 0.51%   |
| Hewlett-Packard           | 1         | 0.51%   |
| ADATA Technology          | 1         | 0.51%   |
| Adaptec                   | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 6.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 6.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 5.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 3.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.57%   |
| AMD FCH IDE Controller                                                                  | 8         | 3.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.79%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.34%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.34%   |
| Unknown                                                                                 | 3         | 1.34%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.89%   |
| Seagate FireCuda 520 SSD                                                                | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.89%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 0.89%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.89%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2         | 0.89%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.89%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.89%   |
| Union Memory (Shenzhen) NVMe 256G SSD device                                            | 1         | 0.45%   |
| Toshiba NVMe Controller                                                                 | 1         | 0.45%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 148       | 69.81%  |
| NVMe | 24        | 11.32%  |
| IDE  | 24        | 11.32%  |
| RAID | 10        | 4.72%   |
| SAS  | 3         | 1.42%   |
| SCSI | 3         | 1.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 145       | 85.29%  |
| AMD    | 24        | 14.12%  |
| ARM    | 1         | 0.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 10        | 5.81%   |
| AMD RX-427BB with AMD Radeon R7 Graphics    | 7         | 4.07%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 6         | 3.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.74%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2         | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.16%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 2         | 1.16%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 2         | 1.16%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 1.16%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.16%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2         | 1.16%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.16%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 2         | 1.16%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2         | 1.16%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.16%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz        | 1         | 0.58%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1         | 0.58%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5310 @ 1.60GHz              | 1         | 0.58%   |
| Intel Xeon CPU E5-2430L v2 @ 2.40GHz        | 1         | 0.58%   |
| Intel Xeon CPU E5-2430 v2 @ 2.50GHz         | 1         | 0.58%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz          | 1         | 0.58%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 0.58%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1         | 0.58%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1         | 0.58%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 0.58%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH          | 1         | 0.58%   |
| Intel Xeon                                  | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 22.81%  |
| Intel Celeron           | 34        | 19.88%  |
| Intel Core i7           | 22        | 12.87%  |
| Intel Xeon              | 19        | 11.11%  |
| Intel Core i3           | 14        | 8.19%   |
| Other                   | 8         | 4.68%   |
| Intel Pentium           | 6         | 3.51%   |
| Intel Atom              | 4         | 2.34%   |
| Intel Core 2 Quad       | 3         | 1.75%   |
| AMD Turion II Neo       | 3         | 1.75%   |
| AMD Ryzen 5             | 3         | 1.75%   |
| AMD Ryzen 3             | 3         | 1.75%   |
| AMD FX                  | 3         | 1.75%   |
| Intel Xeon Silver       | 1         | 0.58%   |
| Intel Pentium Dual-Core | 1         | 0.58%   |
| Intel Core Duo          | 1         | 0.58%   |
| Intel Core 2 Duo        | 1         | 0.58%   |
| ARM Cortex              | 1         | 0.58%   |
| AMD GX                  | 1         | 0.58%   |
| AMD G                   | 1         | 0.58%   |
| AMD E2                  | 1         | 0.58%   |
| AMD Athlon              | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 85        | 49.71%  |
| 2       | 58        | 33.92%  |
| 8       | 11        | 6.43%   |
| 6       | 9         | 5.26%   |
| Unknown | 5         | 2.92%   |
| 12      | 2         | 1.17%   |
| 1       | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 163       | 95.88%  |
| 2       | 5         | 2.94%   |
| Unknown | 2         | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 102       | 59.65%  |
| 2       | 64        | 37.43%  |
| Unknown | 5         | 2.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 22        | 12.94%  |
| Haswell       | 21        | 12.35%  |
| Silvermont    | 20        | 11.76%  |
| IvyBridge     | 20        | 11.76%  |
| Skylake       | 15        | 8.82%   |
| SandyBridge   | 11        | 6.47%   |
| Goldmont plus | 8         | 4.71%   |
| Steamroller   | 7         | 4.12%   |
| Broadwell     | 6         | 3.53%   |
| Nehalem       | 5         | 2.94%   |
| Westmere      | 4         | 2.35%   |
| Penryn        | 4         | 2.35%   |
| Piledriver    | 3         | 1.76%   |
| K10           | 3         | 1.76%   |
| Unknown       | 3         | 1.76%   |
| Zen 2         | 2         | 1.18%   |
| Zen           | 2         | 1.18%   |
| Puma          | 2         | 1.18%   |
| Goldmont      | 2         | 1.18%   |
| Core          | 2         | 1.18%   |
| Bobcat        | 2         | 1.18%   |
| Zen+          | 1         | 0.59%   |
| Zen 3         | 1         | 0.59%   |
| P6            | 1         | 0.59%   |
| Jaguar        | 1         | 0.59%   |
| CometLake     | 1         | 0.59%   |
| Bonnell       | 1         | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 112       | 62.57%  |
| AMD                        | 29        | 16.2%   |
| Nvidia                     | 23        | 12.85%  |
| Matrox Electronics Systems | 9         | 5.03%   |
| ASPEED Technology          | 4         | 2.23%   |
| Tseng Labs                 | 1         | 0.56%   |
| Silicon Motion             | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 8.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 4.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 4.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.4%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 3.85%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 3.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.2%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 2.2%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3         | 1.65%   |
| Intel HD Graphics 530                                                                    | 3         | 1.65%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 1.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.1%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.1%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 1.1%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.1%    |
| Matrox Electronics Systems G200eR2                                                       | 2         | 1.1%    |
| Intel UHD Graphics 620                                                                   | 2         | 1.1%    |
| Intel HD Graphics 620                                                                    | 2         | 1.1%    |
| Intel HD Graphics 6000                                                                   | 2         | 1.1%    |
| Intel HD Graphics 5500                                                                   | 2         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.1%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.1%    |
| Tseng Labs ET4000/W32p rev C                                                             | 1         | 0.55%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.55%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.55%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.55%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.55%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 96        | 55.81%  |
| 1 x AMD            | 25        | 14.53%  |
| 1 x Nvidia         | 15        | 8.72%   |
| 1 x Matrox         | 9         | 5.23%   |
| Intel + Nvidia     | 8         | 4.65%   |
| Other              | 4         | 2.33%   |
| 2 x Intel          | 4         | 2.33%   |
| Intel + AMD        | 4         | 2.33%   |
| 1 x ASPEED         | 4         | 2.33%   |
| 2 x AMD            | 1         | 0.58%   |
| 1 x Tseng Labs     | 1         | 0.58%   |
| 1 x Silicon Motion | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 158       | 92.4%   |
| Proprietary | 8         | 4.68%   |
| Unknown     | 5         | 2.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 157       | 91.81%  |
| 1.01-2.0   | 7         | 4.09%   |
| 0.51-1.0   | 3         | 1.75%   |
| 7.01-8.0   | 2         | 1.17%   |
| 3.01-4.0   | 1         | 0.58%   |
| 0.01-0.5   | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 13.04%  |
| LG Display          | 5         | 10.87%  |
| Samsung Electronics | 4         | 8.7%    |
| Dell                | 4         | 8.7%    |
| Hewlett-Packard     | 3         | 6.52%   |
| Acer                | 3         | 6.52%   |
| ViewSonic           | 2         | 4.35%   |
| Sharp               | 2         | 4.35%   |
| Philips             | 2         | 4.35%   |
| Chimei Innolux      | 2         | 4.35%   |
| ASUSTek Computer    | 2         | 4.35%   |
| AOC                 | 2         | 4.35%   |
| ___                 | 1         | 2.17%   |
| Toshiba             | 1         | 2.17%   |
| Panasonic           | 1         | 2.17%   |
| Lenovo              | 1         | 2.17%   |
| Goldstar            | 1         | 2.17%   |
| Compal              | 1         | 2.17%   |
| BOE                 | 1         | 2.17%   |
| BenQ                | 1         | 2.17%   |
| Apple               | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2         | 4.26%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.13%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 2.13%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 2.13%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 2.13%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 2.13%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 2.13%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 2.13%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 2.13%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 2.13%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 2.13%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 2.13%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 2.13%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 2.13%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 2.13%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 2.13%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 2.13%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 2.13%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 2.13%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 2.13%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1         | 2.13%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1         | 2.13%   |
| Dell U2212HM DELD048 1920x1080 480x270mm 21.7-inch                   | 1         | 2.13%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1         | 2.13%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1         | 2.13%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1         | 2.13%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.13%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 2.13%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 1         | 2.13%   |
| Apple iMac APPB005 2560x1440 600x340mm 27.2-inch                     | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 45.65%  |
| 2560x1440 (QHD)    | 7         | 15.22%  |
| 1366x768 (WXGA)    | 7         | 15.22%  |
| 1680x1050 (WSXGA+) | 2         | 4.35%   |
| 1600x900 (HD+)     | 2         | 4.35%   |
| 3840x1600          | 1         | 2.17%   |
| 2880x1620          | 1         | 2.17%   |
| 2560x1080          | 1         | 2.17%   |
| 2048x1152          | 1         | 2.17%   |
| 1920x1200 (WUXGA)  | 1         | 2.17%   |
| 1800x1200          | 1         | 2.17%   |
| 1280x720 (HD)      | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 8         | 17.39%  |
| 27      | 7         | 15.22%  |
| 24      | 4         | 8.7%    |
| 21      | 4         | 8.7%    |
| 15      | 4         | 8.7%    |
| 23      | 3         | 6.52%   |
| 11      | 3         | 6.52%   |
| 12      | 2         | 4.35%   |
| 47      | 1         | 2.17%   |
| 37      | 1         | 2.17%   |
| 31      | 1         | 2.17%   |
| 28      | 1         | 2.17%   |
| 22      | 1         | 2.17%   |
| 20      | 1         | 2.17%   |
| 19      | 1         | 2.17%   |
| 17      | 1         | 2.17%   |
| 10      | 1         | 2.17%   |
| 9       | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 14        | 30.43%  |
| 301-350     | 11        | 23.91%  |
| 201-300     | 8         | 17.39%  |
| 401-500     | 7         | 15.22%  |
| 601-700     | 2         | 4.35%   |
| 801-900     | 1         | 2.17%   |
| 351-400     | 1         | 2.17%   |
| 1001-1500   | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 86.67%  |
| 16/10 | 3         | 6.67%   |
| 21/9  | 2         | 4.44%   |
| 3/2   | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 11        | 23.91%  |
| 81-90          | 7         | 15.22%  |
| 301-350        | 7         | 15.22%  |
| 51-60          | 3         | 6.52%   |
| 91-100         | 3         | 6.52%   |
| 61-70          | 2         | 4.35%   |
| 41-50          | 2         | 4.35%   |
| 251-300        | 2         | 4.35%   |
| 151-200        | 2         | 4.35%   |
| 501-1000       | 2         | 4.35%   |
| 71-80          | 1         | 2.17%   |
| 351-500        | 1         | 2.17%   |
| 121-130        | 1         | 2.17%   |
| 101-110        | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 15        | 33.33%  |
| 101-120 | 12        | 26.67%  |
| 121-160 | 11        | 24.44%  |
| 161-240 | 5         | 11.11%  |
| 1-50    | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 125       | 73.1%   |
| 1     | 44        | 25.73%  |
| 2     | 2         | 1.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 52.17%  |
| Realtek Semiconductor             | 59        | 25.65%  |
| Broadcom                          | 26        | 11.3%   |
| Qualcomm Atheros                  | 9         | 3.91%   |
| U-Blox                            | 2         | 0.87%   |
| Ericsson Business Mobile Networks | 2         | 0.87%   |
| TP-Link                           | 1         | 0.43%   |
| Sierra Wireless                   | 1         | 0.43%   |
| Seeed Technology                  | 1         | 0.43%   |
| Ralink Technology                 | 1         | 0.43%   |
| Ralink                            | 1         | 0.43%   |
| Nvidia                            | 1         | 0.43%   |
| Microsoft                         | 1         | 0.43%   |
| Marvell Technology Group          | 1         | 0.43%   |
| IMC Networks                      | 1         | 0.43%   |
| Emulex                            | 1         | 0.43%   |
| D-Link System                     | 1         | 0.43%   |
| Aquantia                          | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 52        | 17.87%  |
| Intel I211 Gigabit Network Connection                                         | 25        | 8.59%   |
| Intel I210 Gigabit Network Connection                                         | 12        | 4.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.09%   |
| Intel Wireless 8260                                                           | 8         | 2.75%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 2.41%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 2.06%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.72%   |
| Intel Wireless 7260                                                           | 5         | 1.72%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.72%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 1.72%   |
| Intel Wireless 7265                                                           | 4         | 1.37%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1.37%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.37%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 1.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.03%   |
| U-Blox [u-blox 7]                                                             | 2         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.69%   |
| Intel Wireless 3165                                                           | 2         | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 0.69%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.69%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.69%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.69%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.69%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 58.57%  |
| Realtek Semiconductor | 8         | 11.43%  |
| Qualcomm Atheros      | 8         | 11.43%  |
| Broadcom              | 8         | 11.43%  |
| TP-Link               | 1         | 1.43%   |
| Sierra Wireless       | 1         | 1.43%   |
| Ralink Technology     | 1         | 1.43%   |
| Ralink                | 1         | 1.43%   |
| IMC Networks          | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 8         | 11.27%  |
| Intel Wireless 8265 / 8275                                     | 5         | 7.04%   |
| Intel Wireless 7260                                            | 5         | 7.04%   |
| Intel Wireless 7265                                            | 4         | 5.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.82%   |
| Intel Wireless 3165                                            | 2         | 2.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 2.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.82%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 2.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 2.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 2.82%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.41%   |
| Sierra Wireless EM7455                                         | 1         | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 1.41%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.41%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 1.41%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1         | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.41%   |
| Intel WiFi Link 5100                                           | 1         | 1.41%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.41%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.41%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 1.41%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 105       | 54.4%   |
| Realtek Semiconductor    | 56        | 29.02%  |
| Broadcom                 | 22        | 11.4%   |
| Qualcomm Atheros         | 4         | 2.07%   |
| Nvidia                   | 1         | 0.52%   |
| Microsoft                | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| Emulex                   | 1         | 0.52%   |
| D-Link System            | 1         | 0.52%   |
| Aquantia                 | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 52        | 24.3%   |
| Intel I211 Gigabit Network Connection                                         | 25        | 11.68%  |
| Intel I210 Gigabit Network Connection                                         | 12        | 5.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 4.21%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 3.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 3.27%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 2.8%    |
| Intel 82576 Gigabit Network Connection                                        | 5         | 2.34%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 2.34%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.87%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.4%    |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.4%    |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.4%    |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.4%    |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.4%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.93%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.93%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.93%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.93%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.93%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.93%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.93%   |
| Unknown                                                                       | 2         | 0.93%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.47%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.47%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.47%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.47%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.47%   |
| Intel Ethernet Controller X550                                                | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 162       | 68.94%  |
| WiFi     | 67        | 28.51%  |
| Modem    | 5         | 2.13%   |
| Unknown  | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 155       | 80.73%  |
| WiFi     | 36        | 18.75%  |
| Modem    | 1         | 0.52%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 41.28%  |
| 1     | 31        | 18.02%  |
| 4     | 27        | 15.7%   |
| 3     | 17        | 9.88%   |
| 6     | 11        | 6.4%    |
| 5     | 8         | 4.65%   |
| 9     | 3         | 1.74%   |
| 7     | 3         | 1.74%   |
| 0     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 85.06%  |
| Yes  | 26        | 14.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 60.87%  |
| Apple                           | 6         | 13.04%  |
| Broadcom                        | 4         | 8.7%    |
| Cambridge Silicon Radio         | 3         | 6.52%   |
| Realtek Semiconductor           | 2         | 4.35%   |
| Qualcomm Atheros Communications | 2         | 4.35%   |
| Foxconn / Hon Hai               | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 39.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 10.87%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4.35%   |
| Intel AX201 Bluetooth                               | 2         | 4.35%   |
| Apple Bluetooth Host Controller                     | 2         | 4.35%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 4.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.17%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1             | 1         | 2.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.17%   |
| Intel AX200 Bluetooth                               | 1         | 2.17%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 2.17%   |
| Broadcom Broadcom Bluetooth 4.0                     | 1         | 2.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.17%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 112       | 70.89%  |
| AMD                         | 25        | 15.82%  |
| Nvidia                      | 17        | 10.76%  |
| Texas Instruments           | 1         | 0.63%   |
| Logitech                    | 1         | 0.63%   |
| Focusrite-Novation          | 1         | 0.63%   |
| FiiO Electronics Technology | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 6.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 5.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 5.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.1%    |
| AMD FCH Azalia Controller                                                                         | 9         | 4.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 4.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 4.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 3.57%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.53%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.53%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.02%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.02%   |
| Unknown                                                                                           | 2         | 1.02%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.51%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.51%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 23.76%  |
| Kingston            | 26        | 14.36%  |
| SK hynix            | 19        | 10.5%   |
| Micron Technology   | 19        | 10.5%   |
| Unknown             | 14        | 7.73%   |
| Corsair             | 13        | 7.18%   |
| Crucial             | 11        | 6.08%   |
| G.Skill             | 5         | 2.76%   |
| Transcend           | 3         | 1.66%   |
| TIMETEC             | 3         | 1.66%   |
| A-DATA Technology   | 3         | 1.66%   |
| Unknown             | 3         | 1.66%   |
| Unknown (ABCD)      | 2         | 1.1%    |
| Team                | 2         | 1.1%    |
| Ramaxel Technology  | 2         | 1.1%    |
| Elpida              | 2         | 1.1%    |
| Apacer              | 2         | 1.1%    |
| Vasekey             | 1         | 0.55%   |
| Smart Modular       | 1         | 0.55%   |
| PNY                 | 1         | 0.55%   |
| Patriot             | 1         | 0.55%   |
| Nanya Technology    | 1         | 0.55%   |
| Kingmax             | 1         | 0.55%   |
| Innodisk            | 1         | 0.55%   |
| Hewlett-Packard     | 1         | 0.55%   |
| GeIL                | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 2.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 2.11%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3         | 1.58%   |
| Unknown                                                           | 3         | 1.58%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2         | 1.05%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2         | 1.05%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 2         | 1.05%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                       | 2         | 1.05%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.05%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.05%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1.05%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 2         | 1.05%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2         | 1.05%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2         | 1.05%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2         | 1.05%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2         | 1.05%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2         | 1.05%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s         | 2         | 1.05%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1         | 0.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.53%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1         | 0.53%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1         | 0.53%   |
| Transcend RAM TS256MSK64W6X 2GB DIMM DDR3 1066MT/s                | 1         | 0.53%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.53%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.53%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.53%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s               | 1         | 0.53%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                   | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 93        | 59.62%  |
| DDR4    | 47        | 30.13%  |
| Unknown | 8         | 5.13%   |
| LPDDR3  | 4         | 2.56%   |
| LPDDR4  | 2         | 1.28%   |
| DDR2    | 1         | 0.64%   |
| DDR     | 1         | 0.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 80        | 50.96%  |
| SODIMM       | 65        | 41.4%   |
| Unknown      | 5         | 3.18%   |
| Chip         | 4         | 2.55%   |
| Row Of Chips | 2         | 1.27%   |
| RIMM         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 66        | 39.76%  |
| 4096  | 58        | 34.94%  |
| 2048  | 20        | 12.05%  |
| 16384 | 16        | 9.64%   |
| 32768 | 4         | 2.41%   |
| 1024  | 2         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 64        | 39.26%  |
| 1333  | 28        | 17.18%  |
| 2400  | 18        | 11.04%  |
| 2667  | 15        | 9.2%    |
| 2133  | 12        | 7.36%   |
| 1867  | 7         | 4.29%   |
| 1066  | 5         | 3.07%   |
| 800   | 4         | 2.45%   |
| 2666  | 3         | 1.84%   |
| 3200  | 2         | 1.23%   |
| 59392 | 1         | 0.61%   |
| 3600  | 1         | 0.61%   |
| 1866  | 1         | 0.61%   |
| 1067  | 1         | 0.61%   |
| 667   | 1         | 0.61%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 37.5%   |
| Acer                          | 4         | 16.67%  |
| Apple                         | 3         | 12.5%   |
| Sunplus Innovation Technology | 2         | 8.33%   |
| IMC Networks                  | 2         | 8.33%   |
| Z-Star Microelectronics       | 1         | 4.17%   |
| Suyin                         | 1         | 4.17%   |
| Microdia                      | 1         | 4.17%   |
| Luxvisions Innotech Limited   | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 20%     |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 12%     |
| Acer Integrated Camera                              | 2         | 8%      |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 4%      |
| Suyin Lenovo Integrated Webcam                      | 1         | 4%      |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 4%      |
| Sunplus HD WebCam                                   | 1         | 4%      |
| Microdia Integrated_Webcam_HD                       | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4%      |
| IMC Networks Integrated Webcam                      | 1         | 4%      |
| IMC Networks EasyCamera                             | 1         | 4%      |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4%      |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 4%      |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 4%      |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 4%      |
| Chicony Lenovo Integrated Camera                    | 1         | 4%      |
| Acer Lenovo Integrated Webcam                       | 1         | 4%      |
| Acer Lenovo EasyCamera                              | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 87.5%   |
| Upek             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 37.5%   |
| Validity Sensors Synaptics WBDI                        | 3         | 37.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 12.5%   |

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
| 1     | 73        | 42.44%  |
| 0     | 55        | 31.98%  |
| 2     | 23        | 13.37%  |
| 3     | 16        | 9.3%    |
| 5     | 2         | 1.16%   |
| 4     | 2         | 1.16%   |
| 6     | 1         | 0.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 103       | 59.54%  |
| Bluetooth                | 20        | 11.56%  |
| Net/wireless             | 14        | 8.09%   |
| Card reader              | 14        | 8.09%   |
| Firewire controller      | 6         | 3.47%   |
| Fingerprint reader       | 6         | 3.47%   |
| Sound                    | 3         | 1.73%   |
| Network                  | 2         | 1.16%   |
| Net/ethernet             | 2         | 1.16%   |
| Graphics card            | 2         | 1.16%   |
| Dvb card                 | 1         | 0.58%   |

