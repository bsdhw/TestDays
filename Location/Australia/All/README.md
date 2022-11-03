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

Total: 279

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRock        | H570M-ITX/ac                | Desktop     | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| PC Engines    | apu1                        | Desktop     | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| Unknown       | YL-1900L4-V2                | Desktop     | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [b164bfcf33](https://bsd-hardware.info/?probe=b164bfcf33) | Oct 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Desktop     | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
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
| OPNsense 22.1     | 9         | 3.91%   |
| OPNsense 21.7.7   | 8         | 3.48%   |
| helloSystem 0.5.0 | 8         | 3.48%   |
| OPNsense 22.1.6   | 7         | 3.04%   |
| OPNsense 22.7.6   | 6         | 2.61%   |
| OPNsense 22.7.4   | 6         | 2.61%   |
| OPNsense 21.7.1   | 6         | 2.61%   |
| OPNsense 21.1.5   | 6         | 2.61%   |
| OPNsense 21.1.4   | 6         | 2.61%   |
| OPNsense 21.1.3   | 6         | 2.61%   |
| OPNsense 20.7.8   | 6         | 2.61%   |
| helloSystem 0.4.0 | 6         | 2.61%   |
| OPNsense 22.1.10  | 5         | 2.17%   |
| OPNsense 21.7.3   | 5         | 2.17%   |
| OPNsense 21.7.2   | 5         | 2.17%   |
| OPNsense 21.1.6   | 5         | 2.17%   |
| OPNsense 21.1.2   | 5         | 2.17%   |
| helloSystem 0.6.0 | 5         | 2.17%   |
| FreeBSD 13.0      | 5         | 2.17%   |
| FreeBSD 12.2      | 5         | 2.17%   |
| FreeBSD 12.1-p10  | 5         | 2.17%   |
| OPNsense 22.1.4   | 4         | 1.74%   |
| OPNsense 21.1.1   | 4         | 1.74%   |
| OPNsense 21.1     | 4         | 1.74%   |
| OpenBSD 6.8       | 4         | 1.74%   |
| helloSystem 0.7.0 | 4         | 1.74%   |
| FreeBSD 13.1      | 4         | 1.74%   |
| OPNsense 22.7.5   | 3         | 1.3%    |
| OPNsense 22.7.3   | 3         | 1.3%    |
| OPNsense 22.7     | 3         | 1.3%    |
| OPNsense 21.7.5   | 3         | 1.3%    |
| OPNsense 21.7.4   | 3         | 1.3%    |
| OPNsense 21.1.8   | 3         | 1.3%    |
| FreeBSD 13.0-p4   | 3         | 1.3%    |
| OPNsense 22.1.8   | 2         | 0.87%   |
| OPNsense 22.1.5   | 2         | 0.87%   |
| OPNsense 22.1.3   | 2         | 0.87%   |
| OPNsense 22.1.2   | 2         | 0.87%   |
| OPNsense 22.1.1   | 2         | 0.87%   |
| OPNsense 21.7     | 2         | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 103       | 56.59%  |
| FreeBSD     | 39        | 21.43%  |
| helloSystem | 22        | 12.09%  |
| OpenBSD     | 6         | 3.3%    |
| TrueNAS     | 4         | 2.2%    |
| NomadBSD    | 2         | 1.1%    |
| GhostBSD    | 2         | 1.1%    |
| FreeNAS     | 2         | 1.1%    |
| NetBSD      | 1         | 0.55%   |
| FuguIta     | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 179       | 98.9%   |
| i386  | 1         | 0.55%   |
| arm64 | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 123       | 66.85%  |
| helloDesktop | 25        | 13.59%  |
| KDE5         | 7         | 3.8%    |
| XFCE         | 6         | 3.26%   |
| GNOME        | 6         | 3.26%   |
| TWM          | 4         | 2.17%   |
| fvwm         | 4         | 2.17%   |
| i3           | 3         | 1.63%   |
| Openbox      | 2         | 1.09%   |
| MATE         | 1         | 0.54%   |
| Lumina       | 1         | 0.54%   |
| Fluxbox      | 1         | 0.54%   |
| AwesomeWM    | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 128       | 70.72%  |
| X11     | 51        | 28.18%  |
| Wayland | 2         | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 139       | 76.37%  |
| SLiM    | 25        | 13.74%  |
| SDDM    | 7         | 3.85%   |
| XDM     | 4         | 2.2%    |
| LightDM | 3         | 1.65%   |
| Ly      | 2         | 1.1%    |
| PCDM    | 1         | 0.55%   |
| GDM     | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 122       | 65.95%  |
| en_US           | 31        | 16.76%  |
| C               | 18        | 9.73%   |
| en_AU           | 12        | 6.49%   |
| en_AU.US-ASCII  | 1         | 0.54%   |
| en_AU.ISO8859-1 | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 142       | 78.45%  |
| BIOS | 39        | 21.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 99        | 54.1%   |
| Zfs    | 75        | 40.98%  |
| Ffs    | 7         | 3.83%   |
| Cd9660 | 2         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 161       | 88.95%  |
| MBR     | 18        | 9.94%   |
| BSD     | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 25        | 13.81%  |
| Lenovo                     | 23        | 12.71%  |
| Dell                       | 20        | 11.05%  |
| ASUSTek Computer           | 14        | 7.73%   |
| Protectli                  | 12        | 6.63%   |
| Intel                      | 12        | 6.63%   |
| Unknown                    | 12        | 6.63%   |
| ASRock                     | 9         | 4.97%   |
| Gigabyte Technology        | 8         | 4.42%   |
| Apple                      | 7         | 3.87%   |
| MSI                        | 4         | 2.21%   |
| Toshiba                    | 3         | 1.66%   |
| Acer                       | 3         | 1.66%   |
| Sophos                     | 2         | 1.1%    |
| PC Engines                 | 2         | 1.1%    |
| MW                         | 2         | 1.1%    |
| AMI                        | 2         | 1.1%    |
| Yanling                    | 1         | 0.55%   |
| Unknown                    | 1         | 0.55%   |
| Supermicro                 | 1         | 0.55%   |
| Shuttle                    | 1         | 0.55%   |
| ShenZhen MinWin Technology | 1         | 0.55%   |
| SeeedStudio                | 1         | 0.55%   |
| Samsung Electronics        | 1         | 0.55%   |
| Raspberry Pi Foundation    | 1         | 0.55%   |
| Radxa                      | 1         | 0.55%   |
| Microsoft                  | 1         | 0.55%   |
| Inventec                   | 1         | 0.55%   |
| IBM                        | 1         | 0.55%   |
| HARDKERNEL                 | 1         | 0.55%   |
| Gateway                    | 1         | 0.55%   |
| Foxconn                    | 1         | 0.55%   |
| Firewalla                  | 1         | 0.55%   |
| Cisco                      | 1         | 0.55%   |
| AZW                        | 1         | 0.55%   |
| AOpen                      | 1         | 0.55%   |
| ADI Engineering            | 1         | 0.55%   |
| AAEON                      | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 13        | 7.18%   |
| Protectli FW4B                                                                           | 8         | 4.42%   |
| HP t730 Thin Client                                                                      | 7         | 3.87%   |
| HP ProLiant MicroServer                                                                  | 3         | 1.66%   |
| Dell OptiPlex 9020                                                                       | 3         | 1.66%   |
| Protectli VP2410                                                                         | 2         | 1.1%    |
| MW GMLK-2_5G4L                                                                           | 2         | 1.1%    |
| Intel Q3XXG4-P V1.0                                                                      | 2         | 1.1%    |
| Intel NUC10i5FNH                                                                         | 2         | 1.1%    |
| HP ProLiant MicroServer Gen8                                                             | 2         | 1.1%    |
| Dell OptiPlex 3010                                                                       | 2         | 1.1%    |
| ASUS All Series                                                                          | 2         | 1.1%    |
| Yanling YL-KBR6L                                                                         | 1         | 0.55%   |
| Toshiba Satellite L50-A                                                                  | 1         | 0.55%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.55%   |
| Toshiba KIRA                                                                             | 1         | 0.55%   |
| Supermicro Super Server                                                                  | 1         | 0.55%   |
| Sophos XG                                                                                | 1         | 0.55%   |
| Sophos SG                                                                                | 1         | 0.55%   |
| Shuttle DH370                                                                            | 1         | 0.55%   |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.55%   |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.55%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.55%   |
| RPi Raspberry Pi                                                                         | 1         | 0.55%   |
| Radxa ROCK Pi X                                                                          | 1         | 0.55%   |
| Protectli FW6                                                                            | 1         | 0.55%   |
| Protectli FW2B                                                                           | 1         | 0.55%   |
| PC Engines apu4                                                                          | 1         | 0.55%   |
| PC Engines apu1                                                                          | 1         | 0.55%   |
| MSI Pro 3130 Small Form Factor PC                                                        | 1         | 0.55%   |
| MSI MS-7C95                                                                              | 1         | 0.55%   |
| MSI MS-7C94                                                                              | 1         | 0.55%   |
| MSI CML-U PRO Cubi 5 (MS-B183)                                                           | 1         | 0.55%   |
| Microsoft Surface Go                                                                     | 1         | 0.55%   |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]-                                                  | 1         | 0.55%   |
| Lenovo ThinkPad X60s 17033JM                                                             | 1         | 0.55%   |
| Lenovo ThinkPad X230 2320JXM                                                             | 1         | 0.55%   |
| Lenovo ThinkPad X220 4291C35                                                             | 1         | 0.55%   |
| Lenovo ThinkPad X131e 33672K5                                                            | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100                                                 | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 14        | 7.73%   |
| Unknown                        | 13        | 7.18%   |
| Dell OptiPlex                  | 12        | 6.63%   |
| Protectli FW4B                 | 8         | 4.42%   |
| HP t730                        | 7         | 3.87%   |
| HP ProLiant                    | 7         | 3.87%   |
| Lenovo ThinkCentre             | 6         | 3.31%   |
| Dell PowerEdge                 | 5         | 2.76%   |
| HP EliteDesk                   | 3         | 1.66%   |
| ASUS ROG                       | 3         | 1.66%   |
| Protectli VP2410               | 2         | 1.1%    |
| MW GMLK-2                      | 2         | 1.1%    |
| Intel Q3XXG4-P                 | 2         | 1.1%    |
| Intel NUC10i5FNH               | 2         | 1.1%    |
| ASUS PRIME                     | 2         | 1.1%    |
| ASUS All                       | 2         | 1.1%    |
| ASRock X370                    | 2         | 1.1%    |
| Acer Veriton                   | 2         | 1.1%    |
| Yanling YL-KBR6L               | 1         | 0.55%   |
| Toshiba Satellite              | 1         | 0.55%   |
| Toshiba PORTEGE                | 1         | 0.55%   |
| Toshiba KIRA                   | 1         | 0.55%   |
| Supermicro Super               | 1         | 0.55%   |
| Sophos XG                      | 1         | 0.55%   |
| Sophos SG                      | 1         | 0.55%   |
| Shuttle DH370                  | 1         | 0.55%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.55%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.55%   |
| Samsung 350V5C                 | 1         | 0.55%   |
| RPi Raspberry                  | 1         | 0.55%   |
| Radxa ROCK                     | 1         | 0.55%   |
| Protectli FW6                  | 1         | 0.55%   |
| Protectli FW2B                 | 1         | 0.55%   |
| PC Engines apu4                | 1         | 0.55%   |
| PC Engines apu1                | 1         | 0.55%   |
| MSI Pro                        | 1         | 0.55%   |
| MSI MS-7C95                    | 1         | 0.55%   |
| MSI MS-7C94                    | 1         | 0.55%   |
| MSI CML-U                      | 1         | 0.55%   |
| Microsoft Surface              | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 22        | 12.15%  |
| 2019    | 22        | 12.15%  |
| 2015    | 18        | 9.94%   |
| 2021    | 16        | 8.84%   |
| 2013    | 16        | 8.84%   |
| 2018    | 15        | 8.29%   |
| 2017    | 11        | 6.08%   |
| 2016    | 11        | 6.08%   |
| 2014    | 11        | 6.08%   |
| 2012    | 10        | 5.52%   |
| 2011    | 9         | 4.97%   |
| 2009    | 5         | 2.76%   |
| 2022    | 4         | 2.21%   |
| 2010    | 4         | 2.21%   |
| Unknown | 3         | 1.66%   |
| 2007    | 2         | 1.1%    |
| 2008    | 1         | 0.55%   |
| 2006    | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 114       | 62.98%  |
| Notebook       | 34        | 18.78%  |
| Mini pc        | 19        | 10.5%   |
| Server         | 7         | 3.87%   |
| Firewall       | 3         | 1.66%   |
| All in one     | 2         | 1.1%    |
| System on chip | 1         | 0.55%   |
| Tablet         | 1         | 0.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 95.58%  |
| Yes  | 8         | 4.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 84        | 44.92%  |
| 16.01-24.0  | 40        | 21.39%  |
| 4.01-8.0    | 30        | 16.04%  |
| 32.01-64.0  | 13        | 6.95%   |
| 64.01-256.0 | 7         | 3.74%   |
| 2.01-3.0    | 4         | 2.14%   |
| 3.01-4.0    | 3         | 1.6%    |
| 24.01-32.0  | 3         | 1.6%    |
| 1.01-2.0    | 2         | 1.07%   |
| 0.51-1.0    | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 93        | 48.95%  |
| 0.51-1.0   | 52        | 27.37%  |
| 1.01-2.0   | 20        | 10.53%  |
| 4.01-8.0   | 8         | 4.21%   |
| 2.01-3.0   | 6         | 3.16%   |
| 8.01-16.0  | 3         | 1.58%   |
| 3.01-4.0   | 2         | 1.05%   |
| 16.01-24.0 | 2         | 1.05%   |
| 32.01-64.0 | 1         | 0.53%   |
| 24.01-32.0 | 1         | 0.53%   |
| 0          | 1         | 0.53%   |
| Unknown    | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 68.85%  |
| 2      | 21        | 11.48%  |
| 0      | 15        | 8.2%    |
| 3      | 10        | 5.46%   |
| 4      | 6         | 3.28%   |
| 5      | 2         | 1.09%   |
| 10     | 1         | 0.55%   |
| 7      | 1         | 0.55%   |
| 6      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 149       | 82.32%  |
| Yes       | 32        | 17.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 95.03%  |
| No        | 9         | 4.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 61.54%  |
| Yes       | 70        | 38.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 73.08%  |
| Yes       | 49        | 26.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 181       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 46        | 23.71%  |
| Melbourne      | 33        | 17.01%  |
| Perth          | 23        | 11.86%  |
| Brisbane       | 23        | 11.86%  |
| Adelaide       | 8         | 4.12%   |
| Canberra       | 5         | 2.58%   |
| Hobart         | 3         | 1.55%   |
| Blackburn      | 3         | 1.55%   |
| Southport      | 2         | 1.03%   |
| Ryde           | 2         | 1.03%   |
| Morwell        | 2         | 1.03%   |
| Marrickville   | 2         | 1.03%   |
| Kellyville     | 2         | 1.03%   |
| Ipswich        | 2         | 1.03%   |
| East Malvern   | 2         | 1.03%   |
| Burwood        | 2         | 1.03%   |
| Wollongong     | 1         | 0.52%   |
| Wheelers Hill  | 1         | 0.52%   |
| Wallan         | 1         | 0.52%   |
| Townsville     | 1         | 0.52%   |
| South Yarra    | 1         | 0.52%   |
| Shell Cove     | 1         | 0.52%   |
| Rosanna        | 1         | 0.52%   |
| Ringwood       | 1         | 0.52%   |
| Northcote      | 1         | 0.52%   |
| North Shore    | 1         | 0.52%   |
| Noble Park     | 1         | 0.52%   |
| Mount Waverley | 1         | 0.52%   |
| Mount Eliza    | 1         | 0.52%   |
| Mooroolbark    | 1         | 0.52%   |
| Mandurah       | 1         | 0.52%   |
| Malvern        | 1         | 0.52%   |
| Kurunjang      | 1         | 0.52%   |
| Gold Coast     | 1         | 0.52%   |
| Geelong        | 1         | 0.52%   |
| Engadine       | 1         | 0.52%   |
| Dowerin        | 1         | 0.52%   |
| Darlinghurst   | 1         | 0.52%   |
| Dandenong      | 1         | 0.52%   |
| Croydon        | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 41     | 14.42%  |
| Seagate             | 29        | 39     | 13.94%  |
| WDC                 | 25        | 61     | 12.02%  |
| Intel               | 15        | 22     | 7.21%   |
| Kingston            | 14        | 21     | 6.73%   |
| Toshiba             | 13        | 19     | 6.25%   |
| Crucial             | 12        | 14     | 5.77%   |
| SanDisk             | 10        | 17     | 4.81%   |
| Hoodisk             | 6         | 13     | 2.88%   |
| Protectli           | 3         | 3      | 1.44%   |
| Phison              | 3         | 3      | 1.44%   |
| Micron Technology   | 3         | 5      | 1.44%   |
| Hewlett-Packard     | 3         | 6      | 1.44%   |
| A-DATA Technology   | 3         | 8      | 1.44%   |
| Transcend           | 2         | 3      | 0.96%   |
| Silicon Motion      | 2         | 2      | 0.96%   |
| OCZ                 | 2         | 3      | 0.96%   |
| Hitachi             | 2         | 5      | 0.96%   |
| HGST                | 2         | 2      | 0.96%   |
| Gigabyte Technology | 2         | 2      | 0.96%   |
| Dogfish             | 2         | 2      | 0.96%   |
| China               | 2         | 2      | 0.96%   |
| BIWIN               | 2         | 2      | 0.96%   |
| Apple               | 2         | 2      | 0.96%   |
| XUNZHE              | 1         | 1      | 0.48%   |
| Vaseky              | 1         | 3      | 0.48%   |
| Union Memory        | 1         | 1      | 0.48%   |
| SPCC                | 1         | 5      | 0.48%   |
| SK hynix            | 1         | 3      | 0.48%   |
| ShiJi               | 1         | 1      | 0.48%   |
| PNY                 | 1         | 1      | 0.48%   |
| Plextor             | 1         | 2      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| NVMe                | 1         | 1      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Lenovo              | 1         | 1      | 0.48%   |
| KingSpec            | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| Jetflash            | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 6         | 2.65%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 1.33%   |
| Kingston SA400S37480G 480GB                 | 3         | 1.33%   |
| Kingston SA400S37120G 120GB                 | 3         | 1.33%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 1.33%   |
| Crucial CT250P2SSD8 250GB                   | 3         | 1.33%   |
| Crucial CT250MX500SSD1 250GB                | 3         | 1.33%   |
| WDC WDS250G2B0A-00SM50 250GB                | 2         | 0.88%   |
| WDC WDS120G2G0B-00EPW0 120GB                | 2         | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB                    | 2         | 0.88%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 2         | 0.88%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 2         | 0.88%   |
| WDC WD20EZAZ-00GGJB0 2TB                    | 2         | 0.88%   |
| Toshiba THNSF5256GPUK 256GB                 | 2         | 0.88%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.88%   |
| Seagate ST9500325AS 500GB                   | 2         | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 0.88%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 2         | 0.88%   |
| SanDisk SDSA6MM-032G-1006 32GB              | 2         | 0.88%   |
| Samsung SSD 860 EVO 500GB                   | 2         | 0.88%   |
| Samsung SSD 850 EVO 500GB                   | 2         | 0.88%   |
| Samsung SSD 840 EVO 120GB                   | 2         | 0.88%   |
| Samsung MZ7LN128HCHP-000H1 128GB            | 2         | 0.88%   |
| Protectli 120GB mSATA                       | 2         | 0.88%   |
| Micron MTFDDAK256MAM-1K1 256GB              | 2         | 0.88%   |
| Kingston SA400S37240G 240GB                 | 2         | 0.88%   |
| XUNZHE MSATA 128GB                          | 1         | 0.44%   |
| WDC WDS500G2B0B-00YS70 500GB                | 1         | 0.44%   |
| WDC WDS500G1R0B-68A4Z0 500GB                | 1         | 0.44%   |
| WDC WDS480G2G0A-00JH30 480GB                | 1         | 0.44%   |
| WDC WDS250G2B0C-00PXH0 250GB                | 1         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB                | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB                | 1         | 0.44%   |
| WDC WD80EFAX-68KNBN0 8TB                    | 1         | 0.44%   |
| WDC WD7500BPKX-00HPJT0 752GB                | 1         | 0.44%   |
| WDC WD5000BPKT-00PK4T0 500GB                | 1         | 0.44%   |
| WDC WD5000AAKX-60U6AA0 500GB                | 1         | 0.44%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 1         | 0.44%   |
| WDC WD4000AAKS-00TMA0 400GB                 | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 37     | 42.19%  |
| WDC                 | 17        | 49     | 26.56%  |
| Toshiba             | 6         | 8      | 9.38%   |
| Samsung Electronics | 3         | 5      | 4.69%   |
| Hewlett-Packard     | 3         | 6      | 4.69%   |
| Hitachi             | 2         | 5      | 3.13%   |
| HGST                | 2         | 2      | 3.13%   |
| NVMe                | 1         | 1      | 1.56%   |
| Maxtor              | 1         | 1      | 1.56%   |
| Jetflash            | 1         | 1      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 31     | 19.47%  |
| Kingston            | 14        | 21     | 12.39%  |
| Intel               | 13        | 20     | 11.5%   |
| SanDisk             | 10        | 17     | 8.85%   |
| WDC                 | 8         | 11     | 7.08%   |
| Crucial             | 7         | 7      | 6.19%   |
| Hoodisk             | 6         | 13     | 5.31%   |
| Toshiba             | 3         | 6      | 2.65%   |
| Protectli           | 3         | 3      | 2.65%   |
| Micron Technology   | 3         | 5      | 2.65%   |
| Transcend           | 2         | 3      | 1.77%   |
| Phison              | 2         | 2      | 1.77%   |
| OCZ                 | 2         | 3      | 1.77%   |
| Dogfish             | 2         | 2      | 1.77%   |
| China               | 2         | 2      | 1.77%   |
| XUNZHE              | 1         | 1      | 0.88%   |
| Vaseky              | 1         | 3      | 0.88%   |
| ShiJi               | 1         | 1      | 0.88%   |
| Plextor             | 1         | 2      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| Lenovo              | 1         | 1      | 0.88%   |
| KingSpec            | 1         | 1      | 0.88%   |
| KingDian            | 1         | 1      | 0.88%   |
| Fordisk             | 1         | 1      | 0.88%   |
| BIWIN               | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 104       | 163    | 55.61%  |
| HDD  | 52        | 116    | 27.81%  |
| NVMe | 31        | 46     | 16.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 279    | 82.18%  |
| NVMe | 31        | 46     | 17.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 199    | 77.02%  |
| 0.51-1.0   | 16        | 25     | 9.94%   |
| 1.01-2.0   | 12        | 31     | 7.45%   |
| 3.01-4.0   | 4         | 9      | 2.48%   |
| 2.01-3.0   | 2         | 8      | 1.24%   |
| 4.01-10.0  | 2         | 5      | 1.24%   |
| 10.01-20.0 | 1         | 2      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 42.54%  |
| 251-500        | 30        | 16.57%  |
| 1-20           | 24        | 13.26%  |
| 51-100         | 18        | 9.94%   |
| 21-50          | 13        | 7.18%   |
| 501-1000       | 13        | 7.18%   |
| 1001-2000      | 3         | 1.66%   |
| 2001-3000      | 2         | 1.1%    |
| More than 3000 | 1         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 170       | 90.43%  |
| 21-50     | 12        | 6.38%   |
| 51-100    | 3         | 1.6%    |
| 101-250   | 2         | 1.06%   |
| 1001-2000 | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 1      | 4.17%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 2      | 4.17%   |
| WDC WD20EARX-008FB0 2TB                   | 1         | 3      | 4.17%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 4.17%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 4.17%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 4.17%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 1      | 4.17%   |
| Samsung Electronics HM500LI 500GB         | 1         | 2      | 4.17%   |
| Phison SATA SSD 32GB                      | 1         | 1      | 4.17%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1         | 1      | 4.17%   |
| Kingston SNS4151S316G 16GB                | 1         | 1      | 4.17%   |
| Kingston SA400S37480G 480GB               | 1         | 1      | 4.17%   |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 4.17%   |
| Intel SSDSC2BF180A4L 180GB                | 1         | 1      | 4.17%   |
| Hitachi HDS721010KLA330 1TB               | 1         | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 4.17%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1         | 1      | 4.17%   |
| Crucial CT275MX300SSD4 275GB              | 1         | 1      | 4.17%   |
| BIWIN SSD 8GB                             | 1         | 1      | 4.17%   |
| Apple SSD SM256E 256GB                    | 1         | 1      | 4.17%   |
| Apacer AS330 240GB                        | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 21.74%  |
| WDC                 | 3         | 7      | 13.04%  |
| Kingston            | 2         | 2      | 8.7%    |
| Intel               | 2         | 2      | 8.7%    |
| SanDisk             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 2      | 4.35%   |
| Phison              | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| BIWIN               | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |
| Apacer              | 1         | 1      | 4.35%   |

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
| SSD  | 12        | 12     | 52.17%  |
| HDD  | 11        | 16     | 47.83%  |

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
| Works    | 147       | 295    | 85.47%  |
| Malfunc  | 23        | 28     | 13.37%  |
| Detected | 2         | 2      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 143       | 67.14%  |
| AMD                       | 27        | 12.68%  |
| Samsung Electronics       | 7         | 3.29%   |
| Broadcom / LSI            | 7         | 3.29%   |
| Phison Electronics        | 5         | 2.35%   |
| Toshiba                   | 4         | 1.88%   |
| Micron/Crucial Technology | 4         | 1.88%   |
| Silicon Motion            | 3         | 1.41%   |
| Seagate Technology        | 2         | 0.94%   |
| Union Memory (Shenzhen)   | 1         | 0.47%   |
| Silicon Image             | 1         | 0.47%   |
| SanDisk                   | 1         | 0.47%   |
| Realtek Semiconductor     | 1         | 0.47%   |
| QLogic                    | 1         | 0.47%   |
| Nvidia                    | 1         | 0.47%   |
| Micron Technology         | 1         | 0.47%   |
| JMicron Technology        | 1         | 0.47%   |
| Hewlett-Packard           | 1         | 0.47%   |
| ADATA Technology          | 1         | 0.47%   |
| Adaptec                   | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 6.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 5.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 4.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 3.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 3.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 3.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 3.31%   |
| AMD FCH IDE Controller                                                                  | 8         | 3.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 2.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 2.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.24%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.24%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.24%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.24%   |
| Unknown                                                                                 | 3         | 1.24%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.83%   |
| Seagate FireCuda 520 SSD                                                                | 2         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.83%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.83%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 0.83%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2         | 0.83%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.83%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 68.7%   |
| NVMe | 31        | 13.48%  |
| IDE  | 25        | 10.87%  |
| RAID | 10        | 4.35%   |
| SAS  | 3         | 1.3%    |
| SCSI | 3         | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 153       | 84.53%  |
| AMD    | 27        | 14.92%  |
| ARM    | 1         | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz          | 10        | 5.46%   |
| AMD RX-427BB with AMD Radeon R7 Graphics   | 7         | 3.83%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 6         | 3.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3         | 1.64%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 3         | 1.64%   |
| Intel Xeon CPU E5504 @ 2.00GHz             | 2         | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 1.09%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2         | 1.09%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 2         | 1.09%   |
| Intel Core i7-3667U CPU @ 2.00GHz          | 2         | 1.09%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 2         | 1.09%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 2         | 1.09%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 2         | 1.09%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 2         | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 2         | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 2         | 1.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 2         | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 1.09%   |
| Intel Core i3-6100U CPU @ 2.30GHz          | 2         | 1.09%   |
| AMD Turion II Neo N54L Dual-Core Processor | 2         | 1.09%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2         | 1.09%   |
| AMD FX-8350 Eight-Core Processor           | 2         | 1.09%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz       | 1         | 0.55%   |
| Intel Xeon E-2224G CPU @ 3.50GHz           | 1         | 0.55%   |
| Intel Xeon CPU W3680 @ 3.33GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5506 @ 2.13GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5310 @ 1.60GHz             | 1         | 0.55%   |
| Intel Xeon CPU E5-2430L v2 @ 2.40GHz       | 1         | 0.55%   |
| Intel Xeon CPU E5-2430 v2 @ 2.50GHz        | 1         | 0.55%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz         | 1         | 0.55%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz        | 1         | 0.55%   |
| Intel Xeon CPU E31230 @ 3.20GHz            | 1         | 0.55%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz       | 1         | 0.55%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz        | 1         | 0.55%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GH         | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 21.98%  |
| Intel Celeron           | 36        | 19.78%  |
| Intel Core i7           | 23        | 12.64%  |
| Intel Xeon              | 19        | 10.44%  |
| Intel Core i3           | 14        | 7.69%   |
| Other                   | 10        | 5.49%   |
| Intel Pentium           | 6         | 3.3%    |
| Intel Atom              | 4         | 2.2%    |
| AMD Ryzen 5             | 4         | 2.2%    |
| Intel Core 2 Quad       | 3         | 1.65%   |
| AMD Turion II Neo       | 3         | 1.65%   |
| AMD Ryzen 3             | 3         | 1.65%   |
| AMD FX                  | 3         | 1.65%   |
| AMD G                   | 2         | 1.1%    |
| Intel Xeon Silver       | 1         | 0.55%   |
| Intel Pentium Silver    | 1         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| Intel Pentium 4         | 1         | 0.55%   |
| Intel Core Duo          | 1         | 0.55%   |
| Intel Core 2 Duo        | 1         | 0.55%   |
| ARM Cortex              | 1         | 0.55%   |
| AMD Ryzen 9             | 1         | 0.55%   |
| AMD GX                  | 1         | 0.55%   |
| AMD E2                  | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |
| AMD A6                  | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 91        | 50%     |
| 2       | 59        | 32.42%  |
| 8       | 12        | 6.59%   |
| 6       | 9         | 4.95%   |
| Unknown | 6         | 3.3%    |
| 12      | 3         | 1.65%   |
| 32      | 1         | 0.55%   |
| 1       | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 174       | 96.13%  |
| 2       | 5         | 2.76%   |
| Unknown | 2         | 1.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 109       | 59.89%  |
| 2       | 67        | 36.81%  |
| Unknown | 6         | 3.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 22        | 12.15%  |
| KabyLake      | 22        | 12.15%  |
| Haswell       | 21        | 11.6%   |
| IvyBridge     | 20        | 11.05%  |
| Skylake       | 16        | 8.84%   |
| SandyBridge   | 12        | 6.63%   |
| Goldmont plus | 8         | 4.42%   |
| Steamroller   | 7         | 3.87%   |
| Broadwell     | 6         | 3.31%   |
| Nehalem       | 5         | 2.76%   |
| Unknown       | 5         | 2.76%   |
| Westmere      | 4         | 2.21%   |
| Penryn        | 4         | 2.21%   |
| Zen 3         | 3         | 1.66%   |
| Piledriver    | 3         | 1.66%   |
| K10           | 3         | 1.66%   |
| Bobcat        | 3         | 1.66%   |
| Zen 2         | 2         | 1.1%    |
| Zen           | 2         | 1.1%    |
| Puma          | 2         | 1.1%    |
| Goldmont      | 2         | 1.1%    |
| Core          | 2         | 1.1%    |
| Zen+          | 1         | 0.55%   |
| TigerLake     | 1         | 0.55%   |
| P6            | 1         | 0.55%   |
| NetBurst      | 1         | 0.55%   |
| Jaguar        | 1         | 0.55%   |
| CometLake     | 1         | 0.55%   |
| Bonnell       | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 120       | 63.83%  |
| AMD                        | 30        | 15.96%  |
| Nvidia                     | 23        | 12.23%  |
| Matrox Electronics Systems | 9         | 4.79%   |
| ASPEED Technology          | 4         | 2.13%   |
| Tseng Labs                 | 1         | 0.53%   |
| Silicon Motion             | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 7.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 4.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 3.66%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 3.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.62%   |
| Intel HD Graphics 530                                                                    | 4         | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.09%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 2.09%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3         | 1.57%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 1.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.05%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.05%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 1.05%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.05%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 1.05%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.05%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.05%   |
| Intel HD Graphics 620                                                                    | 2         | 1.05%   |
| Intel HD Graphics 6000                                                                   | 2         | 1.05%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.05%   |
| AMD Cezanne                                                                              | 2         | 1.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.05%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1         | 0.52%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.52%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.52%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 103       | 56.28%  |
| 1 x AMD            | 26        | 14.21%  |
| 1 x Nvidia         | 15        | 8.2%    |
| 1 x Matrox         | 9         | 4.92%   |
| Intel + Nvidia     | 8         | 4.37%   |
| Other              | 6         | 3.28%   |
| 2 x Intel          | 5         | 2.73%   |
| Intel + AMD        | 4         | 2.19%   |
| 1 x ASPEED         | 4         | 2.19%   |
| 2 x AMD            | 1         | 0.55%   |
| 1 x Tseng Labs     | 1         | 0.55%   |
| 1 x Silicon Motion | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 167       | 91.76%  |
| Proprietary | 8         | 4.4%    |
| Unknown     | 7         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 168       | 92.31%  |
| 1.01-2.0   | 7         | 3.85%   |
| 0.51-1.0   | 3         | 1.65%   |
| 7.01-8.0   | 2         | 1.1%    |
| 3.01-4.0   | 1         | 0.55%   |
| 0.01-0.5   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 14.58%  |
| LG Display          | 5         | 10.42%  |
| Samsung Electronics | 4         | 8.33%   |
| Dell                | 4         | 8.33%   |
| Hewlett-Packard     | 3         | 6.25%   |
| Acer                | 3         | 6.25%   |
| ViewSonic           | 2         | 4.17%   |
| Sharp               | 2         | 4.17%   |
| Philips             | 2         | 4.17%   |
| Lenovo              | 2         | 4.17%   |
| Chimei Innolux      | 2         | 4.17%   |
| ASUSTek Computer    | 2         | 4.17%   |
| AOC                 | 2         | 4.17%   |
| ___                 | 1         | 2.08%   |
| Toshiba             | 1         | 2.08%   |
| Panasonic           | 1         | 2.08%   |
| Goldstar            | 1         | 2.08%   |
| Compal              | 1         | 2.08%   |
| BOE                 | 1         | 2.08%   |
| BenQ                | 1         | 2.08%   |
| Apple               | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2         | 4.08%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.04%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 2.04%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 2.04%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 2.04%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 2.04%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 2.04%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 2.04%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 2.04%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 2.04%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 2.04%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 2.04%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 2.04%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 2.04%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                  | 1         | 2.04%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 2.04%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 2.04%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1         | 2.04%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1         | 2.04%   |
| Dell U2212HM DELD048 1920x1080 480x270mm 21.7-inch                   | 1         | 2.04%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1         | 2.04%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1         | 2.04%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1         | 2.04%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.04%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 2.04%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1         | 2.04%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch       | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 47.92%  |
| 2560x1440 (QHD)    | 7         | 14.58%  |
| 1366x768 (WXGA)    | 7         | 14.58%  |
| 1680x1050 (WSXGA+) | 2         | 4.17%   |
| 1600x900 (HD+)     | 2         | 4.17%   |
| 3840x1600          | 1         | 2.08%   |
| 2880x1620          | 1         | 2.08%   |
| 2560x1080          | 1         | 2.08%   |
| 2048x1152          | 1         | 2.08%   |
| 1920x1200 (WUXGA)  | 1         | 2.08%   |
| 1800x1200          | 1         | 2.08%   |
| 1280x720 (HD)      | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 8         | 16.67%  |
| 13      | 8         | 16.67%  |
| 15      | 5         | 10.42%  |
| 24      | 4         | 8.33%   |
| 21      | 4         | 8.33%   |
| 23      | 3         | 6.25%   |
| 11      | 3         | 6.25%   |
| 12      | 2         | 4.17%   |
| 47      | 1         | 2.08%   |
| 37      | 1         | 2.08%   |
| 31      | 1         | 2.08%   |
| 28      | 1         | 2.08%   |
| 22      | 1         | 2.08%   |
| 20      | 1         | 2.08%   |
| 19      | 1         | 2.08%   |
| 17      | 1         | 2.08%   |
| 10      | 1         | 2.08%   |
| 9       | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 15        | 31.25%  |
| 301-350     | 12        | 25%     |
| 201-300     | 8         | 16.67%  |
| 401-500     | 7         | 14.58%  |
| 601-700     | 2         | 4.17%   |
| 801-900     | 1         | 2.08%   |
| 351-400     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |
| Unknown     | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 41        | 87.23%  |
| 16/10 | 3         | 6.38%   |
| 21/9  | 2         | 4.26%   |
| 3/2   | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 11        | 22.92%  |
| 301-350        | 8         | 16.67%  |
| 81-90          | 7         | 14.58%  |
| 91-100         | 4         | 8.33%   |
| 51-60          | 3         | 6.25%   |
| 61-70          | 2         | 4.17%   |
| 41-50          | 2         | 4.17%   |
| 251-300        | 2         | 4.17%   |
| 151-200        | 2         | 4.17%   |
| 501-1000       | 2         | 4.17%   |
| 71-80          | 1         | 2.08%   |
| 351-500        | 1         | 2.08%   |
| 121-130        | 1         | 2.08%   |
| 101-110        | 1         | 2.08%   |
| Unknown        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 16        | 34.04%  |
| 121-160 | 12        | 25.53%  |
| 101-120 | 12        | 25.53%  |
| 161-240 | 5         | 10.64%  |
| 1-50    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 134       | 73.63%  |
| 1     | 46        | 25.27%  |
| 2     | 2         | 1.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 129       | 52.87%  |
| Realtek Semiconductor             | 63        | 25.82%  |
| Broadcom                          | 27        | 11.07%  |
| Qualcomm Atheros                  | 9         | 3.69%   |
| U-Blox                            | 2         | 0.82%   |
| Ericsson Business Mobile Networks | 2         | 0.82%   |
| TP-Link                           | 1         | 0.41%   |
| Sierra Wireless                   | 1         | 0.41%   |
| Seeed Technology                  | 1         | 0.41%   |
| Ralink Technology                 | 1         | 0.41%   |
| Ralink                            | 1         | 0.41%   |
| Nvidia                            | 1         | 0.41%   |
| Microsoft                         | 1         | 0.41%   |
| Marvell Technology Group          | 1         | 0.41%   |
| IMC Networks                      | 1         | 0.41%   |
| Emulex                            | 1         | 0.41%   |
| D-Link System                     | 1         | 0.41%   |
| Aquantia                          | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 55        | 17.74%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 8.39%   |
| Intel I210 Gigabit Network Connection                                         | 12        | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.9%    |
| Intel Wireless 8260                                                           | 8         | 2.58%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.26%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 2.26%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.94%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.61%   |
| Intel Wireless 7260                                                           | 5         | 1.61%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.61%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 1.61%   |
| Intel Wireless 7265                                                           | 4         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.29%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.97%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.97%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.97%   |
| Unknown                                                                       | 3         | 0.97%   |
| U-Blox [u-blox 7]                                                             | 2         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.65%   |
| Intel Wireless 3165                                                           | 2         | 0.65%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 0.65%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.65%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.65%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.65%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 58.9%   |
| Broadcom              | 9         | 12.33%  |
| Realtek Semiconductor | 8         | 10.96%  |
| Qualcomm Atheros      | 8         | 10.96%  |
| TP-Link               | 1         | 1.37%   |
| Sierra Wireless       | 1         | 1.37%   |
| Ralink Technology     | 1         | 1.37%   |
| Ralink                | 1         | 1.37%   |
| IMC Networks          | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 8         | 10.81%  |
| Intel Wireless 8265 / 8275                                     | 5         | 6.76%   |
| Intel Wireless 7260                                            | 5         | 6.76%   |
| Intel Wireless 7265                                            | 4         | 5.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 4.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 4.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.7%    |
| Intel Wireless 3165                                            | 2         | 2.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.7%    |
| Intel Centrino Wireless-N 2230                                 | 2         | 2.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 2.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.35%   |
| Sierra Wireless EM7455                                         | 1         | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.35%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 1.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 1.35%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 1.35%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.35%   |
| Intel WiFi Link 5100                                           | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.35%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.35%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 113       | 54.85%  |
| Realtek Semiconductor    | 60        | 29.13%  |
| Broadcom                 | 23        | 11.17%  |
| Qualcomm Atheros         | 4         | 1.94%   |
| Nvidia                   | 1         | 0.49%   |
| Microsoft                | 1         | 0.49%   |
| Marvell Technology Group | 1         | 0.49%   |
| Emulex                   | 1         | 0.49%   |
| D-Link System            | 1         | 0.49%   |
| Aquantia                 | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 55        | 23.91%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 11.3%   |
| Intel I210 Gigabit Network Connection                                         | 12        | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.91%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 3.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 7         | 3.04%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 2.61%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 2.17%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.74%   |
| Intel 82580 Gigabit Network Connection                                        | 4         | 1.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.3%    |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.3%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.3%    |
| Unknown                                                                       | 3         | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.87%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.87%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.87%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.87%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.87%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 2         | 0.87%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2         | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.87%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.43%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.43%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 172       | 69.35%  |
| WiFi     | 70        | 28.23%  |
| Modem    | 5         | 2.02%   |
| Unknown  | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 165       | 81.28%  |
| WiFi     | 37        | 18.23%  |
| Modem    | 1         | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 39.89%  |
| 1     | 33        | 18.03%  |
| 4     | 30        | 16.39%  |
| 3     | 18        | 9.84%   |
| 6     | 11        | 6.01%   |
| 5     | 11        | 6.01%   |
| 9     | 3         | 1.64%   |
| 7     | 3         | 1.64%   |
| 0     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 83.78%  |
| Yes  | 30        | 16.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 61.22%  |
| Apple                           | 7         | 14.29%  |
| Broadcom                        | 4         | 8.16%   |
| Cambridge Silicon Radio         | 3         | 6.12%   |
| Realtek Semiconductor           | 2         | 4.08%   |
| Qualcomm Atheros Communications | 2         | 4.08%   |
| Foxconn / Hon Hai               | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 36.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 10.2%   |
| Intel AX201 Bluetooth                               | 3         | 6.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 6.12%   |
| Apple Bluetooth Host Controller                     | 3         | 6.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 4.08%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 4.08%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.04%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1             | 1         | 2.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.04%   |
| Intel AX200 Bluetooth                               | 1         | 2.04%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 2.04%   |
| Broadcom Broadcom Bluetooth 4.0                     | 1         | 2.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.04%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 119       | 71.69%  |
| AMD                         | 26        | 15.66%  |
| Nvidia                      | 17        | 10.24%  |
| Texas Instruments           | 1         | 0.6%    |
| Logitech                    | 1         | 0.6%    |
| Focusrite-Novation          | 1         | 0.6%    |
| FiiO Electronics Technology | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 6.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 6.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 5.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 4.88%   |
| AMD FCH Azalia Controller                                                                         | 9         | 4.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 3.41%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 3.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.95%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.95%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.46%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.98%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.98%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.98%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.98%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.98%   |
| Unknown                                                                                           | 2         | 0.98%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.49%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 23.56%  |
| Kingston            | 26        | 13.61%  |
| SK hynix            | 21        | 10.99%  |
| Micron Technology   | 19        | 9.95%   |
| Unknown             | 16        | 8.38%   |
| Corsair             | 15        | 7.85%   |
| Crucial             | 12        | 6.28%   |
| G.Skill             | 6         | 3.14%   |
| Transcend           | 3         | 1.57%   |
| TIMETEC             | 3         | 1.57%   |
| A-DATA Technology   | 3         | 1.57%   |
| Unknown             | 3         | 1.57%   |
| Unknown (ABCD)      | 2         | 1.05%   |
| Team                | 2         | 1.05%   |
| Ramaxel Technology  | 2         | 1.05%   |
| Elpida              | 2         | 1.05%   |
| Apacer              | 2         | 1.05%   |
| Vasekey             | 1         | 0.52%   |
| Smart Modular       | 1         | 0.52%   |
| PNY                 | 1         | 0.52%   |
| Patriot             | 1         | 0.52%   |
| Nanya Technology    | 1         | 0.52%   |
| Kingmax             | 1         | 0.52%   |
| Innodisk            | 1         | 0.52%   |
| Hewlett-Packard     | 1         | 0.52%   |
| GeIL                | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 2.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 2%      |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3         | 1.5%    |
| Unknown                                                           | 3         | 1.5%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2         | 1%      |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2         | 1%      |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                       | 2         | 1%      |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1%      |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1%      |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 2         | 1%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2         | 1%      |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2         | 1%      |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2         | 1%      |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2         | 1%      |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2         | 1%      |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s         | 2         | 1%      |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 8GB 1600MT/s                                   | 1         | 0.5%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1         | 0.5%    |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1         | 0.5%    |
| Transcend RAM TS256MSK64W6X 2GB DIMM DDR3 1066MT/s                | 1         | 0.5%    |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.5%    |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.5%    |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 97        | 58.43%  |
| DDR4    | 52        | 31.33%  |
| Unknown | 8         | 4.82%   |
| LPDDR3  | 4         | 2.41%   |
| LPDDR4  | 2         | 1.2%    |
| DDR     | 2         | 1.2%    |
| DDR2    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 87        | 52.1%   |
| SODIMM       | 68        | 40.72%  |
| Unknown      | 5         | 2.99%   |
| Chip         | 4         | 2.4%    |
| Row Of Chips | 2         | 1.2%    |
| RIMM         | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 70        | 39.77%  |
| 4096  | 61        | 34.66%  |
| 2048  | 20        | 11.36%  |
| 16384 | 17        | 9.66%   |
| 32768 | 5         | 2.84%   |
| 1024  | 3         | 1.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 66        | 38.15%  |
| 1333  | 30        | 17.34%  |
| 2400  | 18        | 10.4%   |
| 2667  | 15        | 8.67%   |
| 2133  | 14        | 8.09%   |
| 1867  | 7         | 4.05%   |
| 1066  | 5         | 2.89%   |
| 800   | 4         | 2.31%   |
| 3200  | 3         | 1.73%   |
| 2666  | 3         | 1.73%   |
| 3600  | 2         | 1.16%   |
| 59392 | 1         | 0.58%   |
| 3000  | 1         | 0.58%   |
| 1866  | 1         | 0.58%   |
| 1067  | 1         | 0.58%   |
| 667   | 1         | 0.58%   |
| 400   | 1         | 0.58%   |

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


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 77.78%  |
| Upek                       | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 33.33%  |
| Validity Sensors Synaptics WBDI                        | 3         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 11.11%  |

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
| 1     | 76        | 41.53%  |
| 0     | 60        | 32.79%  |
| 2     | 25        | 13.66%  |
| 3     | 17        | 9.29%   |
| 5     | 2         | 1.09%   |
| 4     | 2         | 1.09%   |
| 6     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 108       | 59.34%  |
| Bluetooth                | 21        | 11.54%  |
| Net/wireless             | 14        | 7.69%   |
| Card reader              | 14        | 7.69%   |
| Firewire controller      | 7         | 3.85%   |
| Fingerprint reader       | 6         | 3.3%    |
| Sound                    | 3         | 1.65%   |
| Network                  | 3         | 1.65%   |
| Net/ethernet             | 2         | 1.1%    |
| Graphics card            | 2         | 1.1%    |
| Dvb card                 | 2         | 1.1%    |

