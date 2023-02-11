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

Total: 317

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | Desktop     | [3bc47445d4](https://bsd-hardware.info/?probe=3bc47445d4) | Jan 26, 2023 |
| IBM           | 9210MML                     | Desktop     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | Desktop     | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [106cf811d8](https://bsd-hardware.info/?probe=106cf811d8) | Jan 25, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [7b811598b5](https://bsd-hardware.info/?probe=7b811598b5) | Jan 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Dell          | 0R5KP9 A04                  | Server      | [03a26b8a34](https://bsd-hardware.info/?probe=03a26b8a34) | Jan 20, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| HP            | 8299                        | Desktop     | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| HP            | 8299                        | Desktop     | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | OptiPlex 3040               | Desktop     | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| HP            | 8299                        | Desktop     | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| HP            | 8299                        | Desktop     | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Shuttle       | FS81                        | Desktop     | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| Protectli     | FW2B                        | Desktop     | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [953b768755](https://bsd-hardware.info/?probe=953b768755) | Mar 03, 2021 |
| PC Engines    | apu4                        | Desktop     | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
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
| Dell          | 0NW6H5 A00                  | Desktop     | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 22.1     | 9         | 3.53%   |
| OPNsense 22.7.10  | 8         | 3.14%   |
| OPNsense 21.7.7   | 8         | 3.14%   |
| helloSystem 0.5.0 | 8         | 3.14%   |
| OPNsense 22.7.6   | 7         | 2.75%   |
| OPNsense 22.1.6   | 7         | 2.75%   |
| OPNsense 22.7.4   | 6         | 2.35%   |
| OPNsense 21.7.1   | 6         | 2.35%   |
| OPNsense 21.1.5   | 6         | 2.35%   |
| OPNsense 21.1.4   | 6         | 2.35%   |
| OPNsense 21.1.3   | 6         | 2.35%   |
| OPNsense 20.7.8   | 6         | 2.35%   |
| helloSystem 0.4.0 | 6         | 2.35%   |
| OPNsense 22.1.10  | 5         | 1.96%   |
| OPNsense 21.7.3   | 5         | 1.96%   |
| OPNsense 21.7.2   | 5         | 1.96%   |
| OPNsense 21.1.6   | 5         | 1.96%   |
| OPNsense 21.1.2   | 5         | 1.96%   |
| helloSystem 0.6.0 | 5         | 1.96%   |
| FreeBSD 13.0      | 5         | 1.96%   |
| FreeBSD 12.2      | 5         | 1.96%   |
| FreeBSD 12.1-p10  | 5         | 1.96%   |
| OPNsense 22.7.9   | 4         | 1.57%   |
| OPNsense 22.1.4   | 4         | 1.57%   |
| OPNsense 21.1.1   | 4         | 1.57%   |
| OPNsense 21.1     | 4         | 1.57%   |
| OpenBSD 6.8       | 4         | 1.57%   |
| helloSystem 0.7.0 | 4         | 1.57%   |
| FreeBSD 13.1-p5   | 4         | 1.57%   |
| FreeBSD 13.1      | 4         | 1.57%   |
| OPNsense 22.7.5   | 3         | 1.18%   |
| OPNsense 22.7.3   | 3         | 1.18%   |
| OPNsense 22.7     | 3         | 1.18%   |
| OPNsense 21.7.5   | 3         | 1.18%   |
| OPNsense 21.7.4   | 3         | 1.18%   |
| OPNsense 21.1.8   | 3         | 1.18%   |
| FreeBSD 13.0-p4   | 3         | 1.18%   |
| OPNsense 22.7.11  | 2         | 0.78%   |
| OPNsense 22.1.8   | 2         | 0.78%   |
| OPNsense 22.1.5   | 2         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 118       | 58.71%  |
| FreeBSD     | 40        | 19.9%   |
| helloSystem | 22        | 10.95%  |
| OpenBSD     | 7         | 3.48%   |
| TrueNAS     | 5         | 2.49%   |
| NomadBSD    | 2         | 1%      |
| GhostBSD    | 2         | 1%      |
| FreeNAS     | 2         | 1%      |
| XigmaNAS    | 1         | 0.5%    |
| NetBSD      | 1         | 0.5%    |
| FuguIta     | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 198       | 99%     |
| i386  | 1         | 0.5%    |
| arm64 | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 140       | 68.97%  |
| helloDesktop | 26        | 12.81%  |
| XFCE         | 7         | 3.45%   |
| KDE5         | 7         | 3.45%   |
| GNOME        | 6         | 2.96%   |
| TWM          | 4         | 1.97%   |
| fvwm         | 4         | 1.97%   |
| i3           | 3         | 1.48%   |
| Openbox      | 2         | 0.99%   |
| MATE         | 1         | 0.49%   |
| Lumina       | 1         | 0.49%   |
| Fluxbox      | 1         | 0.49%   |
| AwesomeWM    | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 146       | 72.64%  |
| X11     | 53        | 26.37%  |
| Wayland | 2         | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 157       | 78.11%  |
| SLiM    | 25        | 12.44%  |
| SDDM    | 7         | 3.48%   |
| XDM     | 4         | 1.99%   |
| LightDM | 4         | 1.99%   |
| Ly      | 2         | 1%      |
| PCDM    | 1         | 0.5%    |
| GDM     | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 139       | 68.14%  |
| en_US           | 33        | 16.18%  |
| C               | 18        | 8.82%   |
| en_AU           | 12        | 5.88%   |
| en_AU.US-ASCII  | 1         | 0.49%   |
| en_AU.ISO8859-1 | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 158       | 79%     |
| BIOS | 42        | 21%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 109       | 53.69%  |
| Zfs    | 84        | 41.38%  |
| Ffs    | 8         | 3.94%   |
| Cd9660 | 2         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 179       | 89.5%   |
| MBR     | 19        | 9.5%    |
| BSD     | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 28        | 14%     |
| Lenovo                     | 26        | 13%     |
| Dell                       | 23        | 11.5%   |
| ASUSTek Computer           | 15        | 7.5%    |
| Unknown                    | 14        | 7%      |
| Protectli                  | 13        | 6.5%    |
| Intel                      | 13        | 6.5%    |
| Gigabyte Technology        | 9         | 4.5%    |
| ASRock                     | 9         | 4.5%    |
| Apple                      | 7         | 3.5%    |
| MSI                        | 4         | 2%      |
| Acer                       | 4         | 2%      |
| Toshiba                    | 3         | 1.5%    |
| PC Engines                 | 3         | 1.5%    |
| Sophos                     | 2         | 1%      |
| Shuttle                    | 2         | 1%      |
| MW                         | 2         | 1%      |
| AMI                        | 2         | 1%      |
| Yanling                    | 1         | 0.5%    |
| Unknown                    | 1         | 0.5%    |
| Techvision                 | 1         | 0.5%    |
| Supermicro                 | 1         | 0.5%    |
| ShenZhen MinWin Technology | 1         | 0.5%    |
| SeeedStudio                | 1         | 0.5%    |
| Samsung Electronics        | 1         | 0.5%    |
| Raspberry Pi Foundation    | 1         | 0.5%    |
| Radxa                      | 1         | 0.5%    |
| Microsoft                  | 1         | 0.5%    |
| Inventec                   | 1         | 0.5%    |
| IBM                        | 1         | 0.5%    |
| HARDKERNEL                 | 1         | 0.5%    |
| Gateway                    | 1         | 0.5%    |
| Foxconn                    | 1         | 0.5%    |
| Firewalla                  | 1         | 0.5%    |
| Cisco                      | 1         | 0.5%    |
| AZW                        | 1         | 0.5%    |
| AOpen                      | 1         | 0.5%    |
| ADI Engineering            | 1         | 0.5%    |
| AAEON                      | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 15        | 7.5%    |
| Protectli FW4B                                                                           | 8         | 4%      |
| HP t730 Thin Client                                                                      | 7         | 3.5%    |
| HP ProLiant MicroServer                                                                  | 4         | 2%      |
| Dell OptiPlex 9020                                                                       | 3         | 1.5%    |
| Protectli VP2410                                                                         | 2         | 1%      |
| Protectli FW2B                                                                           | 2         | 1%      |
| MW GMLK-2_5G4L                                                                           | 2         | 1%      |
| Intel Q3XXG4-P V1.0                                                                      | 2         | 1%      |
| Intel NUC10i5FNH                                                                         | 2         | 1%      |
| HP ProLiant MicroServer Gen8                                                             | 2         | 1%      |
| Dell PowerEdge R320                                                                      | 2         | 1%      |
| Dell OptiPlex 3040                                                                       | 2         | 1%      |
| Dell OptiPlex 3010                                                                       | 2         | 1%      |
| ASUS All Series                                                                          | 2         | 1%      |
| Yanling YL-KBR6L                                                                         | 1         | 0.5%    |
| Toshiba Satellite L50-A                                                                  | 1         | 0.5%    |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.5%    |
| Toshiba KIRA                                                                             | 1         | 0.5%    |
| Techvision TVI7309X                                                                      | 1         | 0.5%    |
| Supermicro Super Server                                                                  | 1         | 0.5%    |
| Sophos XG                                                                                | 1         | 0.5%    |
| Sophos SG                                                                                | 1         | 0.5%    |
| Shuttle DS81D                                                                            | 1         | 0.5%    |
| Shuttle DH370                                                                            | 1         | 0.5%    |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.5%    |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.5%    |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.5%    |
| RPi Raspberry Pi                                                                         | 1         | 0.5%    |
| Radxa ROCK Pi X                                                                          | 1         | 0.5%    |
| Protectli FW6                                                                            | 1         | 0.5%    |
| PC Engines apu4                                                                          | 1         | 0.5%    |
| PC Engines APU2                                                                          | 1         | 0.5%    |
| PC Engines apu1                                                                          | 1         | 0.5%    |
| MSI Pro 3130 Small Form Factor PC                                                        | 1         | 0.5%    |
| MSI MS-7C95                                                                              | 1         | 0.5%    |
| MSI MS-7C94                                                                              | 1         | 0.5%    |
| MSI CML-U PRO Cubi 5 (MS-B183)                                                           | 1         | 0.5%    |
| Microsoft Surface Go                                                                     | 1         | 0.5%    |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]-                                                  | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 15        | 7.5%    |
| Lenovo ThinkPad                | 14        | 7%      |
| Dell OptiPlex                  | 14        | 7%      |
| Protectli FW4B                 | 8         | 4%      |
| Lenovo ThinkCentre             | 8         | 4%      |
| HP ProLiant                    | 8         | 4%      |
| HP t730                        | 7         | 3.5%    |
| Dell PowerEdge                 | 6         | 3%      |
| HP EliteDesk                   | 4         | 2%      |
| ASUS ROG                       | 3         | 1.5%    |
| Acer Veriton                   | 3         | 1.5%    |
| Protectli VP2410               | 2         | 1%      |
| Protectli FW2B                 | 2         | 1%      |
| MW GMLK-2                      | 2         | 1%      |
| Intel Q3XXG4-P                 | 2         | 1%      |
| Intel NUC10i5FNH               | 2         | 1%      |
| HP prodesk                     | 2         | 1%      |
| ASUS PRIME                     | 2         | 1%      |
| ASUS All                       | 2         | 1%      |
| ASRock X370                    | 2         | 1%      |
| Yanling YL-KBR6L               | 1         | 0.5%    |
| Toshiba Satellite              | 1         | 0.5%    |
| Toshiba PORTEGE                | 1         | 0.5%    |
| Toshiba KIRA                   | 1         | 0.5%    |
| Techvision TVI7309X            | 1         | 0.5%    |
| Supermicro Super               | 1         | 0.5%    |
| Sophos XG                      | 1         | 0.5%    |
| Sophos SG                      | 1         | 0.5%    |
| Shuttle DS81D                  | 1         | 0.5%    |
| Shuttle DH370                  | 1         | 0.5%    |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.5%    |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.5%    |
| Samsung 350V5C                 | 1         | 0.5%    |
| RPi Raspberry                  | 1         | 0.5%    |
| Radxa ROCK                     | 1         | 0.5%    |
| Protectli FW6                  | 1         | 0.5%    |
| PC Engines apu4                | 1         | 0.5%    |
| PC Engines APU2                | 1         | 0.5%    |
| PC Engines apu1                | 1         | 0.5%    |
| MSI Pro                        | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 24        | 12%     |
| 2020    | 21        | 10.5%   |
| 2021    | 17        | 8.5%    |
| 2018    | 17        | 8.5%    |
| 2015    | 17        | 8.5%    |
| 2013    | 17        | 8.5%    |
| 2016    | 15        | 7.5%    |
| 2014    | 15        | 7.5%    |
| 2017    | 14        | 7%      |
| 2011    | 10        | 5%      |
| 2012    | 9         | 4.5%    |
| 2022    | 8         | 4%      |
| 2009    | 5         | 2.5%    |
| 2010    | 4         | 2%      |
| Unknown | 3         | 1.5%    |
| 2007    | 2         | 1%      |
| 2008    | 1         | 0.5%    |
| 2006    | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 132       | 66%     |
| Notebook       | 34        | 17%     |
| Mini pc        | 19        | 9.5%    |
| Server         | 8         | 4%      |
| Firewall       | 3         | 1.5%    |
| All in one     | 2         | 1%      |
| System on chip | 1         | 0.5%    |
| Tablet         | 1         | 0.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 190       | 95%     |
| Yes  | 10        | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 93        | 45.15%  |
| 16.01-24.0  | 45        | 21.84%  |
| 4.01-8.0    | 32        | 15.53%  |
| 32.01-64.0  | 16        | 7.77%   |
| 64.01-256.0 | 7         | 3.4%    |
| 2.01-3.0    | 4         | 1.94%   |
| 3.01-4.0    | 3         | 1.46%   |
| 24.01-32.0  | 3         | 1.46%   |
| 1.01-2.0    | 2         | 0.97%   |
| 0.51-1.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 105       | 49.53%  |
| 0.51-1.0   | 57        | 26.89%  |
| 1.01-2.0   | 24        | 11.32%  |
| 4.01-8.0   | 8         | 3.77%   |
| 2.01-3.0   | 7         | 3.3%    |
| 8.01-16.0  | 3         | 1.42%   |
| 3.01-4.0   | 2         | 0.94%   |
| 16.01-24.0 | 2         | 0.94%   |
| 32.01-64.0 | 1         | 0.47%   |
| 24.01-32.0 | 1         | 0.47%   |
| 0          | 1         | 0.47%   |
| Unknown    | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 71.29%  |
| 2      | 21        | 10.4%   |
| 0      | 16        | 7.92%   |
| 3      | 10        | 4.95%   |
| 4      | 6         | 2.97%   |
| 5      | 2         | 0.99%   |
| 10     | 1         | 0.5%    |
| 7      | 1         | 0.5%    |
| 6      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 82.5%   |
| Yes       | 35        | 17.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 95.5%   |
| No        | 9         | 4.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 127       | 63.18%  |
| Yes       | 74        | 36.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 149       | 74.13%  |
| Yes       | 52        | 25.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 200       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 51        | 23.72%  |
| Melbourne      | 35        | 16.28%  |
| Brisbane       | 26        | 12.09%  |
| Perth          | 25        | 11.63%  |
| Adelaide       | 12        | 5.58%   |
| Canberra       | 6         | 2.79%   |
| Hobart         | 3         | 1.4%    |
| Blackburn      | 3         | 1.4%    |
| Southport      | 2         | 0.93%   |
| Ryde           | 2         | 0.93%   |
| Morwell        | 2         | 0.93%   |
| Marrickville   | 2         | 0.93%   |
| Kellyville     | 2         | 0.93%   |
| Ipswich        | 2         | 0.93%   |
| East Malvern   | 2         | 0.93%   |
| Burwood        | 2         | 0.93%   |
| Unknown        | 2         | 0.93%   |
| Wollongong     | 1         | 0.47%   |
| Wheelers Hill  | 1         | 0.47%   |
| Wallan         | 1         | 0.47%   |
| Townsville     | 1         | 0.47%   |
| South Yarra    | 1         | 0.47%   |
| Shell Cove     | 1         | 0.47%   |
| Roxby Downs    | 1         | 0.47%   |
| Rosanna        | 1         | 0.47%   |
| Ringwood       | 1         | 0.47%   |
| Northcote      | 1         | 0.47%   |
| North Shore    | 1         | 0.47%   |
| Noble Park     | 1         | 0.47%   |
| Mount Waverley | 1         | 0.47%   |
| Mount Eliza    | 1         | 0.47%   |
| Mooroolbark    | 1         | 0.47%   |
| Mandurah       | 1         | 0.47%   |
| Malvern        | 1         | 0.47%   |
| Kurunjang      | 1         | 0.47%   |
| Gold Coast     | 1         | 0.47%   |
| Glen Iris      | 1         | 0.47%   |
| Geelong        | 1         | 0.47%   |
| Engadine       | 1         | 0.47%   |
| Dowerin        | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 44     | 14.47%  |
| Seagate             | 31        | 44     | 13.6%   |
| WDC                 | 25        | 67     | 10.96%  |
| Kingston            | 17        | 25     | 7.46%   |
| Intel               | 16        | 26     | 7.02%   |
| Toshiba             | 14        | 20     | 6.14%   |
| Crucial             | 13        | 16     | 5.7%    |
| SanDisk             | 11        | 19     | 4.82%   |
| Hoodisk             | 8         | 16     | 3.51%   |
| OCZ                 | 4         | 5      | 1.75%   |
| A-DATA Technology   | 4         | 9      | 1.75%   |
| Protectli           | 3         | 3      | 1.32%   |
| Phison              | 3         | 3      | 1.32%   |
| Micron Technology   | 3         | 5      | 1.32%   |
| Hewlett-Packard     | 3         | 6      | 1.32%   |
| Dogfish             | 3         | 3      | 1.32%   |
| China               | 3         | 3      | 1.32%   |
| Transcend           | 2         | 3      | 0.88%   |
| Silicon Motion      | 2         | 2      | 0.88%   |
| KingDian            | 2         | 2      | 0.88%   |
| Hitachi             | 2         | 5      | 0.88%   |
| HGST                | 2         | 2      | 0.88%   |
| Gigabyte Technology | 2         | 2      | 0.88%   |
| BIWIN               | 2         | 2      | 0.88%   |
| Apple               | 2         | 2      | 0.88%   |
| XUNZHE              | 1         | 1      | 0.44%   |
| Vaseky              | 1         | 3      | 0.44%   |
| Union Memory        | 1         | 1      | 0.44%   |
| SPCC                | 1         | 5      | 0.44%   |
| SK hynix            | 1         | 3      | 0.44%   |
| ShiJi               | 1         | 1      | 0.44%   |
| PNY                 | 1         | 1      | 0.44%   |
| Plextor             | 1         | 2      | 0.44%   |
| Patriot             | 1         | 1      | 0.44%   |
| NVMe                | 1         | 1      | 0.44%   |
| Maxtor              | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| Lenovo              | 1         | 1      | 0.44%   |
| KingSpec            | 1         | 1      | 0.44%   |
| Jetflash            | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 6         | 2.43%   |
| Samsung SSD 850 EVO 500GB                   | 3         | 1.21%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 1.21%   |
| Kingston SA400S37480G 480GB                 | 3         | 1.21%   |
| Kingston SA400S37240G 240GB                 | 3         | 1.21%   |
| Kingston SA400S37120G 120GB                 | 3         | 1.21%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 1.21%   |
| Crucial CT250P2SSD8 250GB                   | 3         | 1.21%   |
| Crucial CT250MX500SSD1 250GB                | 3         | 1.21%   |
| WDC WDS250G2B0A-00SM50 250GB                | 2         | 0.81%   |
| WDC WDS120G2G0B-00EPW0 120GB                | 2         | 0.81%   |
| WDC WD40EFRX-68N32N0 4TB                    | 2         | 0.81%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 2         | 0.81%   |
| WDC WD20EZRX-00D8PB0 2TB                    | 2         | 0.81%   |
| WDC WD20EZAZ-00GGJB0 2TB                    | 2         | 0.81%   |
| Toshiba THNSF5256GPUK 256GB                 | 2         | 0.81%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.81%   |
| Seagate ST9500325AS 500GB                   | 2         | 0.81%   |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 0.81%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 2         | 0.81%   |
| SanDisk SDSA6MM-032G-1006 32GB              | 2         | 0.81%   |
| Samsung SSD 860 EVO 500GB                   | 2         | 0.81%   |
| Samsung SSD 840 EVO 120GB                   | 2         | 0.81%   |
| Samsung MZ7LN128HCHP-000H1 128GB            | 2         | 0.81%   |
| Protectli 120GB mSATA                       | 2         | 0.81%   |
| Micron MTFDDAK256MAM-1K1 256GB              | 2         | 0.81%   |
| Dogfish SSD 64GB                            | 2         | 0.81%   |
| Crucial CT500MX500SSD1 500GB                | 2         | 0.81%   |
| China SATA SSD 16GB                         | 2         | 0.81%   |
| XUNZHE MSATA 128GB                          | 1         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB                | 1         | 0.4%    |
| WDC WDS500G1R0B-68A4Z0 500GB                | 1         | 0.4%    |
| WDC WDS480G2G0A-00JH30 480GB                | 1         | 0.4%    |
| WDC WDS250G2B0C-00PXH0 250GB                | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB                | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB                | 1         | 0.4%    |
| WDC WD80EFAX-68KNBN0 8TB                    | 1         | 0.4%    |
| WDC WD7500BPKX-00HPJT0 752GB                | 1         | 0.4%    |
| WDC WD5000BPKT-00PK4T0 500GB                | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 42     | 43.94%  |
| WDC                 | 17        | 55     | 25.76%  |
| Toshiba             | 6         | 8      | 9.09%   |
| Samsung Electronics | 3         | 5      | 4.55%   |
| Hewlett-Packard     | 3         | 6      | 4.55%   |
| Hitachi             | 2         | 5      | 3.03%   |
| HGST                | 2         | 2      | 3.03%   |
| NVMe                | 1         | 1      | 1.52%   |
| Maxtor              | 1         | 1      | 1.52%   |
| Jetflash            | 1         | 1      | 1.52%   |
| Fujitsu             | 1         | 1      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 34     | 19.23%  |
| Kingston            | 16        | 23     | 12.31%  |
| Intel               | 14        | 24     | 10.77%  |
| SanDisk             | 11        | 19     | 8.46%   |
| WDC                 | 8         | 11     | 6.15%   |
| Hoodisk             | 8         | 16     | 6.15%   |
| Crucial             | 8         | 9      | 6.15%   |
| Toshiba             | 4         | 7      | 3.08%   |
| OCZ                 | 4         | 5      | 3.08%   |
| Protectli           | 3         | 3      | 2.31%   |
| Micron Technology   | 3         | 5      | 2.31%   |
| Dogfish             | 3         | 3      | 2.31%   |
| China               | 3         | 3      | 2.31%   |
| Transcend           | 2         | 3      | 1.54%   |
| Phison              | 2         | 2      | 1.54%   |
| KingDian            | 2         | 2      | 1.54%   |
| A-DATA Technology   | 2         | 2      | 1.54%   |
| XUNZHE              | 1         | 1      | 0.77%   |
| Vaseky              | 1         | 3      | 0.77%   |
| ShiJi               | 1         | 1      | 0.77%   |
| Plextor             | 1         | 2      | 0.77%   |
| Patriot             | 1         | 1      | 0.77%   |
| LITEONIT            | 1         | 1      | 0.77%   |
| Lenovo              | 1         | 1      | 0.77%   |
| KingSpec            | 1         | 1      | 0.77%   |
| Fordisk             | 1         | 1      | 0.77%   |
| BIWIN               | 1         | 1      | 0.77%   |
| Apple               | 1         | 1      | 0.77%   |
| Apacer              | 1         | 1      | 0.77%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 120       | 186    | 58.54%  |
| HDD  | 53        | 127    | 25.85%  |
| NVMe | 32        | 48     | 15.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 160       | 313    | 83.33%  |
| NVMe | 32        | 48     | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 140       | 224    | 78.21%  |
| 0.51-1.0   | 16        | 25     | 8.94%   |
| 1.01-2.0   | 13        | 38     | 7.26%   |
| 3.01-4.0   | 5         | 11     | 2.79%   |
| 2.01-3.0   | 2         | 8      | 1.12%   |
| 4.01-10.0  | 2         | 5      | 1.12%   |
| 10.01-20.0 | 1         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 42.57%  |
| 251-500        | 32        | 15.84%  |
| 1-20           | 26        | 12.87%  |
| 51-100         | 20        | 9.9%    |
| 21-50          | 17        | 8.42%   |
| 501-1000       | 14        | 6.93%   |
| 1001-2000      | 4         | 1.98%   |
| 2001-3000      | 2         | 0.99%   |
| More than 3000 | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 188       | 89.95%  |
| 21-50     | 14        | 6.7%    |
| 51-100    | 4         | 1.91%   |
| 101-250   | 2         | 0.96%   |
| 1001-2000 | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 1      | 3.85%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 2      | 3.85%   |
| WDC WD20EARX-008FB0 2TB                   | 1         | 4      | 3.85%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.85%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 3.85%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.85%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1      | 3.85%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 3.85%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 1      | 3.85%   |
| Samsung Electronics HM500LI 500GB         | 1         | 2      | 3.85%   |
| Phison SATA SSD 32GB                      | 1         | 1      | 3.85%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1         | 1      | 3.85%   |
| Kingston SNS4151S316G 16GB                | 1         | 1      | 3.85%   |
| Kingston SA400S37480G 480GB               | 1         | 1      | 3.85%   |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 3.85%   |
| Intel SSDSC2BF180A4L 180GB                | 1         | 1      | 3.85%   |
| Hitachi HDS721010KLA330 1TB               | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 3.85%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1         | 1      | 3.85%   |
| Crucial CT275MX300SSD4 275GB              | 1         | 1      | 3.85%   |
| BIWIN SSD 8GB                             | 1         | 1      | 3.85%   |
| Apple SSD SM256E 256GB                    | 1         | 1      | 3.85%   |
| Apacer AS330 240GB                        | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 24%     |
| WDC                 | 3         | 8      | 12%     |
| Kingston            | 2         | 2      | 8%      |
| Intel               | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 2      | 4%      |
| Phison              | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| Hitachi             | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| BIWIN               | 1         | 1      | 4%      |
| Apple               | 1         | 1      | 4%      |
| Apacer              | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| WDC                 | 2         | 7      | 16.67%  |
| Samsung Electronics | 1         | 2      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |
| Hewlett-Packard     | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 13        | 13     | 52%     |
| HDD  | 12        | 18     | 48%     |

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
| Works    | 163       | 328    | 85.79%  |
| Malfunc  | 25        | 31     | 13.16%  |
| Detected | 2         | 2      | 1.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 160       | 67.23%  |
| AMD                         | 29        | 12.18%  |
| Broadcom / LSI              | 8         | 3.36%   |
| Samsung Electronics         | 7         | 2.94%   |
| Phison Electronics          | 5         | 2.1%    |
| Toshiba                     | 4         | 1.68%   |
| Micron/Crucial Technology   | 4         | 1.68%   |
| Silicon Motion              | 3         | 1.26%   |
| Seagate Technology          | 2         | 0.84%   |
| Kingston Technology Company | 2         | 0.84%   |
| ASMedia Technology          | 2         | 0.84%   |
| Union Memory (Shenzhen)     | 1         | 0.42%   |
| Silicon Image               | 1         | 0.42%   |
| SanDisk                     | 1         | 0.42%   |
| Realtek Semiconductor       | 1         | 0.42%   |
| QLogic                      | 1         | 0.42%   |
| Nvidia                      | 1         | 0.42%   |
| Micron Technology           | 1         | 0.42%   |
| Marvell Technology Group    | 1         | 0.42%   |
| JMicron Technology          | 1         | 0.42%   |
| Hewlett-Packard             | 1         | 0.42%   |
| ADATA Technology            | 1         | 0.42%   |
| Adaptec                     | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 6.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 17        | 6.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14        | 5.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 4.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 2.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.97%   |
| AMD FCH IDE Controller                                                                  | 8         | 2.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 2.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 2.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 2.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.86%   |
| Unknown                                                                                 | 5         | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 1.12%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.12%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.12%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.12%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 3         | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 1.12%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.74%   |
| Seagate FireCuda 520 SSD                                                                | 2         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.74%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 177       | 69.96%  |
| NVMe | 32        | 12.65%  |
| IDE  | 26        | 10.28%  |
| RAID | 12        | 4.74%   |
| SAS  | 3         | 1.19%   |
| SCSI | 3         | 1.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 170       | 85%     |
| AMD    | 29        | 14.5%   |
| ARM    | 1         | 0.5%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz          | 10        | 4.93%   |
| AMD RX-427BB with AMD Radeon R7 Graphics   | 7         | 3.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 6         | 2.96%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 3         | 1.48%   |
| Intel Core i5-4570T CPU @ 2.90GHz          | 3         | 1.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3         | 1.48%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 3         | 1.48%   |
| Intel Xeon CPU E5504 @ 2.00GHz             | 2         | 0.99%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 2         | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 0.99%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2         | 0.99%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 2         | 0.99%   |
| Intel Core i7-3667U CPU @ 2.00GHz          | 2         | 0.99%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 2         | 0.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 2         | 0.99%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 2         | 0.99%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 2         | 0.99%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 2         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 2         | 0.99%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 2         | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 0.99%   |
| Intel Core i3-6100U CPU @ 2.30GHz          | 2         | 0.99%   |
| Intel Celeron N5105 @ 2.00GHz              | 2         | 0.99%   |
| Intel Celeron CPU J3060 @ 1.60GHz          | 2         | 0.99%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 2         | 0.99%   |
| AMD Turion II Neo N54L Dual-Core Processor | 2         | 0.99%   |
| AMD Turion II Neo N40L Dual-Core Processor | 2         | 0.99%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2         | 0.99%   |
| AMD GX-412TC SOC                           | 2         | 0.99%   |
| AMD FX-8350 Eight-Core Processor           | 2         | 0.99%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz       | 1         | 0.49%   |
| Intel Xeon E-2224G CPU @ 3.50GHz           | 1         | 0.49%   |
| Intel Xeon CPU W3680 @ 3.33GHz             | 1         | 0.49%   |
| Intel Xeon CPU E5506 @ 2.13GHz             | 1         | 0.49%   |
| Intel Xeon CPU E5310 @ 1.60GHz             | 1         | 0.49%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz        | 1         | 0.49%   |
| Intel Xeon CPU E5-2430L v2 @ 2.40GHz       | 1         | 0.49%   |
| Intel Xeon CPU E5-2430 v2 @ 2.50GHz        | 1         | 0.49%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz         | 1         | 0.49%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz        | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 45        | 22.39%  |
| Intel Celeron           | 41        | 20.4%   |
| Intel Core i7           | 25        | 12.44%  |
| Intel Xeon              | 20        | 9.95%   |
| Intel Core i3           | 16        | 7.96%   |
| Other                   | 11        | 5.47%   |
| Intel Pentium           | 7         | 3.48%   |
| Intel Atom              | 4         | 1.99%   |
| AMD Turion II Neo       | 4         | 1.99%   |
| AMD Ryzen 5             | 4         | 1.99%   |
| Intel Core 2 Quad       | 3         | 1.49%   |
| AMD Ryzen 3             | 3         | 1.49%   |
| AMD FX                  | 3         | 1.49%   |
| AMD GX                  | 2         | 1%      |
| AMD G                   | 2         | 1%      |
| Intel Xeon Silver       | 1         | 0.5%    |
| Intel Pentium Silver    | 1         | 0.5%    |
| Intel Pentium Dual-Core | 1         | 0.5%    |
| Intel Pentium 4         | 1         | 0.5%    |
| Intel Core Duo          | 1         | 0.5%    |
| Intel Core 2 Duo        | 1         | 0.5%    |
| ARM Cortex              | 1         | 0.5%    |
| AMD Ryzen 9             | 1         | 0.5%    |
| AMD E2                  | 1         | 0.5%    |
| AMD Athlon              | 1         | 0.5%    |
| AMD A6                  | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 99        | 49.25%  |
| 2       | 69        | 34.33%  |
| 8       | 13        | 6.47%   |
| 6       | 9         | 4.48%   |
| Unknown | 6         | 2.99%   |
| 12      | 3         | 1.49%   |
| 32      | 1         | 0.5%    |
| 1       | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 193       | 96.5%   |
| 2       | 5         | 2.5%    |
| Unknown | 2         | 1%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 119       | 59.2%   |
| 2       | 76        | 37.81%  |
| Unknown | 6         | 2.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 12.94%  |
| Haswell       | 25        | 12.44%  |
| Silvermont    | 23        | 11.44%  |
| Skylake       | 20        | 9.95%   |
| IvyBridge     | 20        | 9.95%   |
| SandyBridge   | 13        | 6.47%   |
| Goldmont plus | 9         | 4.48%   |
| Steamroller   | 7         | 3.48%   |
| Broadwell     | 7         | 3.48%   |
| Unknown       | 6         | 2.99%   |
| Nehalem       | 5         | 2.49%   |
| Westmere      | 4         | 1.99%   |
| Penryn        | 4         | 1.99%   |
| K10           | 4         | 1.99%   |
| Zen 3         | 3         | 1.49%   |
| Puma          | 3         | 1.49%   |
| Piledriver    | 3         | 1.49%   |
| Bobcat        | 3         | 1.49%   |
| Zen 2         | 2         | 1%      |
| Zen           | 2         | 1%      |
| TigerLake     | 2         | 1%      |
| Goldmont      | 2         | 1%      |
| Core          | 2         | 1%      |
| Zen+          | 1         | 0.5%    |
| P6            | 1         | 0.5%    |
| NetBurst      | 1         | 0.5%    |
| Jaguar        | 1         | 0.5%    |
| CometLake     | 1         | 0.5%    |
| Bonnell       | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 136       | 66.02%  |
| AMD                        | 31        | 15.05%  |
| Nvidia                     | 23        | 11.17%  |
| Matrox Electronics Systems | 10        | 4.85%   |
| ASPEED Technology          | 4         | 1.94%   |
| Tseng Labs                 | 1         | 0.49%   |
| Silicon Motion             | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 7.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 6.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 4.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.81%   |
| Intel HD Graphics 530                                                                    | 7         | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 3.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.9%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.9%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 1.9%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3         | 1.43%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.43%   |
| Intel HD Graphics 630                                                                    | 3         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.43%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.95%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.95%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.95%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.95%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.95%   |
| Intel HD Graphics 620                                                                    | 2         | 0.95%   |
| Intel HD Graphics 610                                                                    | 2         | 0.95%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.95%   |
| Intel HD Graphics 510                                                                    | 2         | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.95%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.95%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1         | 0.48%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.48%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 119       | 58.91%  |
| 1 x AMD            | 27        | 13.37%  |
| 1 x Nvidia         | 15        | 7.43%   |
| 1 x Matrox         | 10        | 4.95%   |
| Intel + Nvidia     | 8         | 3.96%   |
| Other              | 7         | 3.47%   |
| 2 x Intel          | 5         | 2.48%   |
| Intel + AMD        | 4         | 1.98%   |
| 1 x ASPEED         | 4         | 1.98%   |
| 2 x AMD            | 1         | 0.5%    |
| 1 x Tseng Labs     | 1         | 0.5%    |
| 1 x Silicon Motion | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 185       | 92.04%  |
| Proprietary | 8         | 3.98%   |
| Unknown     | 8         | 3.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 187       | 93.03%  |
| 1.01-2.0   | 7         | 3.48%   |
| 0.51-1.0   | 3         | 1.49%   |
| 7.01-8.0   | 2         | 1%      |
| 3.01-4.0   | 1         | 0.5%    |
| 0.01-0.5   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 14%     |
| LG Display          | 5         | 10%     |
| Samsung Electronics | 4         | 8%      |
| Hewlett-Packard     | 4         | 8%      |
| Dell                | 4         | 8%      |
| Philips             | 3         | 6%      |
| Acer                | 3         | 6%      |
| ViewSonic           | 2         | 4%      |
| Sharp               | 2         | 4%      |
| Lenovo              | 2         | 4%      |
| Chimei Innolux      | 2         | 4%      |
| ASUSTek Computer    | 2         | 4%      |
| AOC                 | 2         | 4%      |
| ___                 | 1         | 2%      |
| Toshiba             | 1         | 2%      |
| Panasonic           | 1         | 2%      |
| Goldstar            | 1         | 2%      |
| Compal              | 1         | 2%      |
| BOE                 | 1         | 2%      |
| BenQ                | 1         | 2%      |
| Apple               | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2         | 3.92%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.96%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1         | 1.96%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch              | 1         | 1.96%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1         | 1.96%   |
| Sharp LQ133T1JX03 SHP140F 2560x1440 290x170mm 13.2-inch              | 1         | 1.96%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 210x140mm 9.9-inch               | 1         | 1.96%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1         | 1.96%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch | 1         | 1.96%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 1.96%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1         | 1.96%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1         | 1.96%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD04A9 1920x1080 310x170mm 13.9-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x170mm 13.9-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD01DD 1600x900 380x210mm 17.1-inch          | 1         | 1.96%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch              | 1         | 1.96%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                  | 1         | 1.96%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1         | 1.96%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1         | 1.96%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1         | 1.96%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch           | 1         | 1.96%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1         | 1.96%   |
| Dell U2212HM DELD048 1920x1080 480x270mm 21.7-inch                   | 1         | 1.96%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1         | 1.96%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1         | 1.96%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1         | 1.96%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 1.96%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                 | 1         | 1.96%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1         | 1.96%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 260x140mm 11.6-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 48.98%  |
| 2560x1440 (QHD)    | 7         | 14.29%  |
| 1366x768 (WXGA)    | 7         | 14.29%  |
| 1680x1050 (WSXGA+) | 2         | 4.08%   |
| 1600x900 (HD+)     | 2         | 4.08%   |
| 3840x1600          | 1         | 2.04%   |
| 2880x1620          | 1         | 2.04%   |
| 2560x1080          | 1         | 2.04%   |
| 2048x1152          | 1         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 2.04%   |
| 1800x1200          | 1         | 2.04%   |
| 1280x720 (HD)      | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 8         | 16%     |
| 13      | 8         | 16%     |
| 24      | 5         | 10%     |
| 21      | 5         | 10%     |
| 15      | 5         | 10%     |
| 23      | 3         | 6%      |
| 11      | 3         | 6%      |
| 12      | 2         | 4%      |
| 47      | 1         | 2%      |
| 37      | 1         | 2%      |
| 31      | 1         | 2%      |
| 28      | 1         | 2%      |
| 22      | 1         | 2%      |
| 20      | 1         | 2%      |
| 19      | 1         | 2%      |
| 17      | 1         | 2%      |
| 10      | 1         | 2%      |
| 9       | 1         | 2%      |
| Unknown | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 16        | 32%     |
| 301-350     | 12        | 24%     |
| 401-500     | 8         | 16%     |
| 201-300     | 8         | 16%     |
| 601-700     | 2         | 4%      |
| 801-900     | 1         | 2%      |
| 351-400     | 1         | 2%      |
| 1001-1500   | 1         | 2%      |
| Unknown     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 87.5%   |
| 16/10 | 3         | 6.25%   |
| 21/9  | 2         | 4.17%   |
| 3/2   | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 12        | 24.49%  |
| 301-350        | 8         | 16.33%  |
| 81-90          | 7         | 14.29%  |
| 91-100         | 4         | 8.16%   |
| 51-60          | 3         | 6.12%   |
| 61-70          | 2         | 4.08%   |
| 41-50          | 2         | 4.08%   |
| 251-300        | 2         | 4.08%   |
| 151-200        | 2         | 4.08%   |
| 501-1000       | 2         | 4.08%   |
| 71-80          | 1         | 2.04%   |
| 351-500        | 1         | 2.04%   |
| 121-130        | 1         | 2.04%   |
| 101-110        | 1         | 2.04%   |
| Unknown        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 17        | 34.69%  |
| 101-120 | 13        | 26.53%  |
| 121-160 | 12        | 24.49%  |
| 161-240 | 5         | 10.2%   |
| 1-50    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 152       | 75.62%  |
| 1     | 47        | 23.38%  |
| 2     | 2         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 141       | 52.81%  |
| Realtek Semiconductor             | 69        | 25.84%  |
| Broadcom                          | 29        | 10.86%  |
| Qualcomm Atheros                  | 11        | 4.12%   |
| U-Blox                            | 2         | 0.75%   |
| TP-Link                           | 2         | 0.75%   |
| Ericsson Business Mobile Networks | 2         | 0.75%   |
| Sierra Wireless                   | 1         | 0.37%   |
| Seeed Technology                  | 1         | 0.37%   |
| Ralink Technology                 | 1         | 0.37%   |
| Ralink                            | 1         | 0.37%   |
| Nvidia                            | 1         | 0.37%   |
| Microsoft                         | 1         | 0.37%   |
| Marvell Technology Group          | 1         | 0.37%   |
| IMC Networks                      | 1         | 0.37%   |
| Emulex                            | 1         | 0.37%   |
| D-Link System                     | 1         | 0.37%   |
| Aquantia                          | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 61        | 18.1%   |
| Intel I211 Gigabit Network Connection                                         | 28        | 8.31%   |
| Intel I210 Gigabit Network Connection                                         | 13        | 3.86%   |
| Intel Wireless 8260                                                           | 9         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.67%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 2.37%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 2.08%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.08%   |
| Intel Wireless 7260                                                           | 6         | 1.78%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 1.78%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.48%   |
| Intel Ethernet Controller I225-V                                              | 5         | 1.48%   |
| Intel 82580 Gigabit Network Connection                                        | 5         | 1.48%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.48%   |
| Intel Wireless 7265                                                           | 4         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.89%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 0.89%   |
| Intel Ethernet Controller I226-V                                              | 3         | 0.89%   |
| Intel Ethernet Connection I217-V                                              | 3         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.89%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 0.89%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.89%   |
| U-Blox [u-blox 7]                                                             | 2         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.59%   |
| Intel Wireless 3165                                                           | 2         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 0.59%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.59%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 57.69%  |
| Qualcomm Atheros      | 10        | 12.82%  |
| Broadcom              | 9         | 11.54%  |
| Realtek Semiconductor | 8         | 10.26%  |
| TP-Link               | 2         | 2.56%   |
| Sierra Wireless       | 1         | 1.28%   |
| Ralink Technology     | 1         | 1.28%   |
| Ralink                | 1         | 1.28%   |
| IMC Networks          | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                             | 9         | 11.25%  |
| Intel Wireless 7260                                             | 6         | 7.5%    |
| Intel Wireless 8265 / 8275                                      | 5         | 6.25%   |
| Intel Wireless 7265                                             | 4         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 3         | 3.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 3         | 3.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 2         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 2         | 2.5%    |
| Intel Wireless 3165                                             | 2         | 2.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 2.5%    |
| Intel Centrino Wireless-N 2230                                  | 2         | 2.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                 | 2         | 2.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1         | 1.25%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 1         | 1.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1         | 1.25%   |
| Sierra Wireless EM7455                                          | 1         | 1.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 1         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1         | 1.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1         | 1.25%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1         | 1.25%   |
| Ralink RT5572 Wireless Adapter                                  | 1         | 1.25%   |
| Ralink RT5392 PCIe Wireless Network Adapter                     | 1         | 1.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1         | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1         | 1.25%   |
| Intel WiFi Link 5100                                            | 1         | 1.25%   |
| Intel Wi-Fi 6 AX201                                             | 1         | 1.25%   |
| Intel Wi-Fi 6 AX200                                             | 1         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection         | 1         | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 124       | 55.11%  |
| Realtek Semiconductor    | 66        | 29.33%  |
| Broadcom                 | 25        | 11.11%  |
| Qualcomm Atheros         | 4         | 1.78%   |
| Nvidia                   | 1         | 0.44%   |
| Microsoft                | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| Emulex                   | 1         | 0.44%   |
| D-Link System            | 1         | 0.44%   |
| Aquantia                 | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 61        | 24.3%   |
| Intel I211 Gigabit Network Connection                                         | 28        | 11.16%  |
| Intel I210 Gigabit Network Connection                                         | 13        | 5.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 3.19%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 2.79%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.79%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 2.39%   |
| Intel Ethernet Controller I225-V                                              | 5         | 1.99%   |
| Intel 82580 Gigabit Network Connection                                        | 5         | 1.99%   |
| Intel 82576 Gigabit Network Connection                                        | 5         | 1.99%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.2%    |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.2%    |
| Intel Ethernet Controller I226-V                                              | 3         | 1.2%    |
| Intel Ethernet Connection I217-V                                              | 3         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.2%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3         | 1.2%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.8%    |
| Intel Ethernet Connection I219-V                                              | 2         | 0.8%    |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                                         | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.8%    |
| Intel Ethernet 10G 2P X520 Adapter                                            | 2         | 0.8%    |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.8%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2         | 0.8%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.8%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.8%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.4%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 191       | 70.48%  |
| WiFi     | 74        | 27.31%  |
| Modem    | 5         | 1.85%   |
| Unknown  | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 183       | 82.81%  |
| WiFi     | 37        | 16.74%  |
| Modem    | 1         | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 39.11%  |
| 1     | 37        | 18.32%  |
| 4     | 33        | 16.34%  |
| 3     | 21        | 10.4%   |
| 6     | 12        | 5.94%   |
| 5     | 12        | 5.94%   |
| 9     | 3         | 1.49%   |
| 7     | 3         | 1.49%   |
| 8     | 1         | 0.5%    |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 82.93%  |
| Yes  | 35        | 17.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 60.38%  |
| Apple                           | 7         | 13.21%  |
| Broadcom                        | 5         | 9.43%   |
| Cambridge Silicon Radio         | 3         | 5.66%   |
| Realtek Semiconductor           | 2         | 3.77%   |
| Qualcomm Atheros Communications | 2         | 3.77%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 37.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 9.43%   |
| Intel AX201 Bluetooth                               | 3         | 5.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.66%   |
| Apple Bluetooth Host Controller                     | 3         | 5.66%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 3.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 3.77%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 3.77%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.89%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1             | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.89%   |
| Intel AX200 Bluetooth                               | 1         | 1.89%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 1.89%   |
| Broadcom Broadcom Bluetooth 4.0                     | 1         | 1.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.89%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 1.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.89%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 133       | 73.48%  |
| AMD                         | 26        | 14.36%  |
| Nvidia                      | 17        | 9.39%   |
| Focusrite-Novation          | 2         | 1.1%    |
| Texas Instruments           | 1         | 0.55%   |
| Logitech                    | 1         | 0.55%   |
| FiiO Electronics Technology | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 7.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 4.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 4%      |
| AMD FCH Azalia Controller                                                                         | 9         | 4%      |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.56%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 3.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.22%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.78%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.78%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.33%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.33%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.89%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.89%   |
| Unknown                                                                                           | 2         | 0.89%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.44%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 23.33%  |
| Kingston            | 28        | 13.33%  |
| SK hynix            | 22        | 10.48%  |
| Micron Technology   | 20        | 9.52%   |
| Unknown             | 18        | 8.57%   |
| Corsair             | 17        | 8.1%    |
| Crucial             | 14        | 6.67%   |
| G.Skill             | 6         | 2.86%   |
| Transcend           | 3         | 1.43%   |
| Timetec             | 3         | 1.43%   |
| Team                | 3         | 1.43%   |
| Apacer              | 3         | 1.43%   |
| A-DATA Technology   | 3         | 1.43%   |
| Unknown             | 3         | 1.43%   |
| Unknown (ABCD)      | 2         | 0.95%   |
| Ramaxel Technology  | 2         | 0.95%   |
| GeIL                | 2         | 0.95%   |
| Elpida              | 2         | 0.95%   |
| Vasekey             | 1         | 0.48%   |
| Smart Modular       | 1         | 0.48%   |
| Silicon Power       | 1         | 0.48%   |
| PNY                 | 1         | 0.48%   |
| Patriot             | 1         | 0.48%   |
| Nanya Technology    | 1         | 0.48%   |
| Kingmax             | 1         | 0.48%   |
| Kimtigo             | 1         | 0.48%   |
| Innodisk            | 1         | 0.48%   |
| Hewlett-Packard     | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 2.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 3         | 1.37%   |
| Unknown                                                        | 3         | 1.37%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 0.91%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                    | 2         | 0.91%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.91%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.91%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.91%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.91%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.91%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 2         | 0.91%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.91%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.91%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 2         | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2         | 0.91%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2         | 0.91%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 2         | 0.91%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 2         | 0.91%   |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1         | 0.46%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 8GB 1600MT/s                                | 1         | 0.46%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 0.46%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1         | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1         | 0.46%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 1         | 0.46%   |
| Transcend RAM TS256MSK64W6X 2GB DIMM DDR3 1066MT/s             | 1         | 0.46%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 105       | 57.38%  |
| DDR4    | 60        | 32.79%  |
| Unknown | 9         | 4.92%   |
| LPDDR3  | 4         | 2.19%   |
| LPDDR4  | 2         | 1.09%   |
| DDR     | 2         | 1.09%   |
| DDR2    | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 96        | 52.17%  |
| SODIMM       | 75        | 40.76%  |
| Unknown      | 6         | 3.26%   |
| Chip         | 4         | 2.17%   |
| Row Of Chips | 2         | 1.09%   |
| RIMM         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 40.41%  |
| 4096  | 67        | 34.72%  |
| 2048  | 20        | 10.36%  |
| 16384 | 19        | 9.84%   |
| 32768 | 6         | 3.11%   |
| 1024  | 3         | 1.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 72        | 37.7%   |
| 1333  | 33        | 17.28%  |
| 2400  | 20        | 10.47%  |
| 2133  | 18        | 9.42%   |
| 2667  | 16        | 8.38%   |
| 1867  | 7         | 3.66%   |
| 3200  | 5         | 2.62%   |
| 1066  | 5         | 2.62%   |
| 800   | 4         | 2.09%   |
| 2666  | 3         | 1.57%   |
| 3600  | 2         | 1.05%   |
| 59392 | 1         | 0.52%   |
| 3000  | 1         | 0.52%   |
| 1866  | 1         | 0.52%   |
| 1067  | 1         | 0.52%   |
| 667   | 1         | 0.52%   |
| 400   | 1         | 0.52%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 34.62%  |
| Acer                          | 4         | 15.38%  |
| Apple                         | 3         | 11.54%  |
| Sunplus Innovation Technology | 2         | 7.69%   |
| Microdia                      | 2         | 7.69%   |
| IMC Networks                  | 2         | 7.69%   |
| Z-Star Microelectronics       | 1         | 3.85%   |
| Suyin                         | 1         | 3.85%   |
| Luxvisions Innotech Limited   | 1         | 3.85%   |
| Logitech                      | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 18.52%  |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 11.11%  |
| Acer Integrated Camera                              | 2         | 7.41%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 3.7%    |
| Suyin Lenovo Integrated Webcam                      | 1         | 3.7%    |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 3.7%    |
| Sunplus HD WebCam                                   | 1         | 3.7%    |
| Microdia USB 2.0 Camera                             | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 1         | 3.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.7%    |
| Logitech C922 Pro Stream Webcam                     | 1         | 3.7%    |
| IMC Networks Integrated Webcam                      | 1         | 3.7%    |
| IMC Networks EasyCamera                             | 1         | 3.7%    |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 3.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 3.7%    |
| Chicony Lenovo Integrated Camera                    | 1         | 3.7%    |
| Acer Lenovo Integrated Webcam                       | 1         | 3.7%    |
| Acer Lenovo EasyCamera                              | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 77.78%  |
| Upek                       | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 43.56%  |
| 0     | 62        | 30.69%  |
| 2     | 29        | 14.36%  |
| 3     | 17        | 8.42%   |
| 4     | 3         | 1.49%   |
| 5     | 2         | 0.99%   |
| 6     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 124       | 61.08%  |
| Bluetooth                | 22        | 10.84%  |
| Net/wireless             | 16        | 7.88%   |
| Card reader              | 14        | 6.9%    |
| Firewire controller      | 7         | 3.45%   |
| Fingerprint reader       | 6         | 2.96%   |
| Sound                    | 4         | 1.97%   |
| Network                  | 3         | 1.48%   |
| Net/ethernet             | 2         | 0.99%   |
| Graphics card            | 2         | 0.99%   |
| Dvb card                 | 2         | 0.99%   |
| Storage/raid             | 1         | 0.49%   |

