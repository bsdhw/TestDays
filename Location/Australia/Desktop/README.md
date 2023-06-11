BSD in Australia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for BSD in Australia.

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

Total: 263

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Aspire TC-230               | [d7eacfafe1](https://bsd-hardware.info/?probe=d7eacfafe1) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | 00V62H A01                  | [a87429607b](https://bsd-hardware.info/?probe=a87429607b) | Jun 01, 2023 |
| Intel         | QHSW02                      | [ed6d01bc2b](https://bsd-hardware.info/?probe=ed6d01bc2b) | May 31, 2023 |
| Intel         | QHSW02                      | [9f3d95a494](https://bsd-hardware.info/?probe=9f3d95a494) | May 31, 2023 |
| Protectli     | FW4B Ver                    | [1587da94da](https://bsd-hardware.info/?probe=1587da94da) | May 30, 2023 |
| Dell          | 0HD5W2 A00                  | [bd3ea7e1d6](https://bsd-hardware.info/?probe=bd3ea7e1d6) | May 28, 2023 |
| Intel         | J1900                       | [4d849f4f34](https://bsd-hardware.info/?probe=4d849f4f34) | May 27, 2023 |
| CWWK          | CW-AD4L-N V1                | [310da4e6e5](https://bsd-hardware.info/?probe=310da4e6e5) | May 26, 2023 |
| Dell          | 096JG8 A01                  | [f350405f61](https://bsd-hardware.info/?probe=f350405f61) | May 26, 2023 |
| Inventec      | R CLASS A02                 | [85f3673aa8](https://bsd-hardware.info/?probe=85f3673aa8) | May 24, 2023 |
| Intel         | J1900                       | [52081bc55b](https://bsd-hardware.info/?probe=52081bc55b) | May 24, 2023 |
| Dell          | 0M9KCM A02                  | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| Dell          | 096JG8 A01                  | [3abf2c7ee2](https://bsd-hardware.info/?probe=3abf2c7ee2) | May 19, 2023 |
| Dell          | 096JG8 A01                  | [6f7bcae20b](https://bsd-hardware.info/?probe=6f7bcae20b) | May 19, 2023 |
| Protectli     | FW2B                        | [aa52b30ddf](https://bsd-hardware.info/?probe=aa52b30ddf) | May 14, 2023 |
| Dell          | 07F37C A00                  | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Dell          | 096JG8 A01                  | [633fa55df0](https://bsd-hardware.info/?probe=633fa55df0) | May 07, 2023 |
| Dell          | 0YC03K A04                  | [979aea14cc](https://bsd-hardware.info/?probe=979aea14cc) | May 06, 2023 |
| Unknown       | Unknown                     | [28253dd080](https://bsd-hardware.info/?probe=28253dd080) | Apr 28, 2023 |
| HP            | 82B4                        | [b75bb5fe83](https://bsd-hardware.info/?probe=b75bb5fe83) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | [28c2a703c7](https://bsd-hardware.info/?probe=28c2a703c7) | Apr 18, 2023 |
| Gigabyte      | B560M DS3H V2               | [737250a1c8](https://bsd-hardware.info/?probe=737250a1c8) | Apr 15, 2023 |
| Dell          | 0HD5W2 A00                  | [1835073ded](https://bsd-hardware.info/?probe=1835073ded) | Apr 14, 2023 |
| MW            | GMLK-2_5G4L                 | [41bf2600a5](https://bsd-hardware.info/?probe=41bf2600a5) | Apr 13, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [036b48e4c3](https://bsd-hardware.info/?probe=036b48e4c3) | Apr 13, 2023 |
| Acer          | Veriton X4630G              | [93987b345d](https://bsd-hardware.info/?probe=93987b345d) | Apr 12, 2023 |
| Acer          | Veriton M6620G              | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| MW            | GMLK-2_5G4L                 | [459fdd8cdd](https://bsd-hardware.info/?probe=459fdd8cdd) | Mar 28, 2023 |
| HP            | 82B4                        | [6edc033f79](https://bsd-hardware.info/?probe=6edc033f79) | Mar 25, 2023 |
| Unknown       | Unknown                     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | [7db8753b08](https://bsd-hardware.info/?probe=7db8753b08) | Mar 17, 2023 |
| Intel         | MAHOBAY                     | [b2176fafcf](https://bsd-hardware.info/?probe=b2176fafcf) | Mar 07, 2023 |
| ASUSTek       | PRIME A320M-E               | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| AMD           | Kabini CRB                  | [c9e69ff953](https://bsd-hardware.info/?probe=c9e69ff953) | Mar 03, 2023 |
| Protectli     | VP2410 10                   | [74eedb42ea](https://bsd-hardware.info/?probe=74eedb42ea) | Mar 03, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Acer          | Aspire TC-230               | [f3f963fb6a](https://bsd-hardware.info/?probe=f3f963fb6a) | Feb 22, 2023 |
| Gigabyte      | A320M-H-CF                  | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| ASUSTek       | H110I-PLUS D3               | [1f347f15e2](https://bsd-hardware.info/?probe=1f347f15e2) | Feb 19, 2023 |
| Protectli     | FW4B Ver                    | [81911bb61f](https://bsd-hardware.info/?probe=81911bb61f) | Feb 17, 2023 |
| ASUSTek       | H110I-PLUS D3               | [4d3dee18a0](https://bsd-hardware.info/?probe=4d3dee18a0) | Feb 16, 2023 |
| ASRock        | Z97 Killer                  | [67d58b9cde](https://bsd-hardware.info/?probe=67d58b9cde) | Feb 14, 2023 |
| Acer          | Aspire TC-230               | [a8ce4299ae](https://bsd-hardware.info/?probe=a8ce4299ae) | Feb 13, 2023 |
| PC Engines    | APU2                        | [3bc47445d4](https://bsd-hardware.info/?probe=3bc47445d4) | Jan 26, 2023 |
| IBM           | 9210MML                     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| Dell          | OptiPlex 3040               | [9c925f4e7f](https://bsd-hardware.info/?probe=9c925f4e7f) | Jan 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [0d3e0df928](https://bsd-hardware.info/?probe=0d3e0df928) | Jan 20, 2023 |
| Gigabyte      | H110-D3A-CF                 | [6bb5667269](https://bsd-hardware.info/?probe=6bb5667269) | Jan 17, 2023 |
| HP            | 8299                        | [d7afab37f3](https://bsd-hardware.info/?probe=d7afab37f3) | Jan 15, 2023 |
| HP            | 8299                        | [7a5bbc7546](https://bsd-hardware.info/?probe=7a5bbc7546) | Jan 15, 2023 |
| Dell          | OptiPlex 3040               | [07abf8e8b2](https://bsd-hardware.info/?probe=07abf8e8b2) | Jan 14, 2023 |
| Gigabyte      | H110-D3A-CF                 | [9c1f7ead89](https://bsd-hardware.info/?probe=9c1f7ead89) | Jan 06, 2023 |
| Techvision    | TVI7309X B0                 | [b1ee757669](https://bsd-hardware.info/?probe=b1ee757669) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | [5d360961d4](https://bsd-hardware.info/?probe=5d360961d4) | Jan 02, 2023 |
| Intel         | CRESCENTBAY                 | [d5f8e71171](https://bsd-hardware.info/?probe=d5f8e71171) | Jan 02, 2023 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| HP            | 8299                        | [6715ee2886](https://bsd-hardware.info/?probe=6715ee2886) | Dec 24, 2022 |
| Dell          | 0NW6H5 A00                  | [b19a4d1696](https://bsd-hardware.info/?probe=b19a4d1696) | Dec 23, 2022 |
| HP            | 8299                        | [d9eec3c9f5](https://bsd-hardware.info/?probe=d9eec3c9f5) | Dec 23, 2022 |
| Unknown       | Unknown                     | [0f03a7f2ce](https://bsd-hardware.info/?probe=0f03a7f2ce) | Dec 22, 2022 |
| Acer          | Veriton X2640G V:1.0        | [f241237f76](https://bsd-hardware.info/?probe=f241237f76) | Dec 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [a8ec4c3ae4](https://bsd-hardware.info/?probe=a8ec4c3ae4) | Dec 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [4667028e67](https://bsd-hardware.info/?probe=4667028e67) | Dec 20, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [92593f4e79](https://bsd-hardware.info/?probe=92593f4e79) | Dec 17, 2022 |
| ASUSTek       | STRIX Z270I GAMING          | [d44c580408](https://bsd-hardware.info/?probe=d44c580408) | Dec 16, 2022 |
| Dell          | 08NPPY A00                  | [e199c0ec3d](https://bsd-hardware.info/?probe=e199c0ec3d) | Dec 15, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [d7d0ebf605](https://bsd-hardware.info/?probe=d7d0ebf605) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| Unknown       | Unknown                     | [85520bf6bf](https://bsd-hardware.info/?probe=85520bf6bf) | Dec 14, 2022 |
| HP            | 82A2                        | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | [4bf1aae972](https://bsd-hardware.info/?probe=4bf1aae972) | Dec 02, 2022 |
| Shuttle       | FS81                        | [f714ba647f](https://bsd-hardware.info/?probe=f714ba647f) | Nov 28, 2022 |
| Protectli     | FW2B                        | [d15326180f](https://bsd-hardware.info/?probe=d15326180f) | Nov 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9945b6b3e7](https://bsd-hardware.info/?probe=9945b6b3e7) | Nov 09, 2022 |
| HP            | ProLiant MicroServer        | [798219138a](https://bsd-hardware.info/?probe=798219138a) | Nov 07, 2022 |
| HP            | ProLiant MicroServer        | [394e873da0](https://bsd-hardware.info/?probe=394e873da0) | Nov 07, 2022 |
| ASRock        | H570M-ITX/ac                | [06a8abdbf4](https://bsd-hardware.info/?probe=06a8abdbf4) | Oct 29, 2022 |
| Dell          | 0HD5W2 A00                  | [7b330abf44](https://bsd-hardware.info/?probe=7b330abf44) | Oct 26, 2022 |
| Unknown       | Unknown                     | [1f2cd1f9ea](https://bsd-hardware.info/?probe=1f2cd1f9ea) | Oct 24, 2022 |
| MSI           | MAG B550M MORTAR            | [607fcd2571](https://bsd-hardware.info/?probe=607fcd2571) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | [d32449b8c4](https://bsd-hardware.info/?probe=d32449b8c4) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f80953ee2f](https://bsd-hardware.info/?probe=f80953ee2f) | Oct 16, 2022 |
| Dell          | 0HD5W2 A00                  | [f27ffa7217](https://bsd-hardware.info/?probe=f27ffa7217) | Oct 16, 2022 |
| MW            | GMLK-2_5G4L                 | [ae4868c65b](https://bsd-hardware.info/?probe=ae4868c65b) | Oct 15, 2022 |
| PC Engines    | apu1                        | [06debf0076](https://bsd-hardware.info/?probe=06debf0076) | Oct 14, 2022 |
| Unknown       | Unknown                     | [6c330d9bab](https://bsd-hardware.info/?probe=6c330d9bab) | Oct 14, 2022 |
| Unknown       | YL-1900L4-V2                | [1f55db62cc](https://bsd-hardware.info/?probe=1f55db62cc) | Oct 12, 2022 |
| ASRock        | H570M-ITX/ac                | [ea8b1fd760](https://bsd-hardware.info/?probe=ea8b1fd760) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [9d3b9cb318](https://bsd-hardware.info/?probe=9d3b9cb318) | Oct 11, 2022 |
| Unknown       | Unknown                     | [7718c8e9ca](https://bsd-hardware.info/?probe=7718c8e9ca) | Oct 05, 2022 |
| Protectli     | FW4B Ver                    | [63b36c077a](https://bsd-hardware.info/?probe=63b36c077a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e001150f93](https://bsd-hardware.info/?probe=e001150f93) | Oct 03, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| Unknown       | Unknown                     | [9f998deaa4](https://bsd-hardware.info/?probe=9f998deaa4) | Sep 25, 2022 |
| Unknown       | Unknown                     | [ffa40a08e8](https://bsd-hardware.info/?probe=ffa40a08e8) | Sep 23, 2022 |
| Protectli     | FW4B Ver                    | [58caab8946](https://bsd-hardware.info/?probe=58caab8946) | Sep 14, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [05b5d1e01a](https://bsd-hardware.info/?probe=05b5d1e01a) | Sep 12, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | [50ac5c0aaf](https://bsd-hardware.info/?probe=50ac5c0aaf) | Sep 10, 2022 |
| Dell          | 0200DY A02                  | [cd90f548c8](https://bsd-hardware.info/?probe=cd90f548c8) | Sep 06, 2022 |
| Protectli     | FW4B Ver                    | [91664c3bc1](https://bsd-hardware.info/?probe=91664c3bc1) | Sep 05, 2022 |
| MW            | GMLK-2_5G4L                 | [bb379f7083](https://bsd-hardware.info/?probe=bb379f7083) | Sep 03, 2022 |
| Gigabyte      | H81M-DS2                    | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Unknown       | YL-J3160L4                  | [aad241ba36](https://bsd-hardware.info/?probe=aad241ba36) | Aug 08, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Protectli     | VP2410                      | [f9b42e4a75](https://bsd-hardware.info/?probe=f9b42e4a75) | Jul 27, 2022 |
| Protectli     | VP2410                      | [db66cc446e](https://bsd-hardware.info/?probe=db66cc446e) | Jul 27, 2022 |
| HP            | 8055                        | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| AZW           | GK55                        | [40d9df6faa](https://bsd-hardware.info/?probe=40d9df6faa) | Jul 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [f68c3695ea](https://bsd-hardware.info/?probe=f68c3695ea) | Jul 08, 2022 |
| Dell          | 00V62H A00                  | [a3aff65df2](https://bsd-hardware.info/?probe=a3aff65df2) | Jun 27, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| HP            | ProLiant ML10 v2            | [72254b033d](https://bsd-hardware.info/?probe=72254b033d) | Jun 06, 2022 |
| Dell          | 0MGK50 A02                  | [1de9982d19](https://bsd-hardware.info/?probe=1de9982d19) | Jun 05, 2022 |
| AOpen         | iBTMx-DS R1.03 55DED10A0... | [94bdba6302](https://bsd-hardware.info/?probe=94bdba6302) | Jun 04, 2022 |
| Protectli     | FW4B Ver                    | [f1838b29ff](https://bsd-hardware.info/?probe=f1838b29ff) | Jun 01, 2022 |
| MW            | GMLK-2_5G4L                 | [fdab123532](https://bsd-hardware.info/?probe=fdab123532) | May 07, 2022 |
| MW            | GMLK-2_5G4L                 | [59083ac5ac](https://bsd-hardware.info/?probe=59083ac5ac) | May 06, 2022 |
| MSI           | 2A9C                        | [506b970279](https://bsd-hardware.info/?probe=506b970279) | May 03, 2022 |
| HP            | 0B4Ch D                     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| ASUSTek       | AM1M-A                      | [76a2d4f148](https://bsd-hardware.info/?probe=76a2d4f148) | Apr 22, 2022 |
| MSI           | 2A9C                        | [595c9a1da2](https://bsd-hardware.info/?probe=595c9a1da2) | Apr 18, 2022 |
| MSI           | 2A9C                        | [7f44d30f83](https://bsd-hardware.info/?probe=7f44d30f83) | Apr 15, 2022 |
| Lenovo        | SHARKBAY NOK                | [e32f0f2130](https://bsd-hardware.info/?probe=e32f0f2130) | Apr 08, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c807e1d8eb](https://bsd-hardware.info/?probe=c807e1d8eb) | Apr 07, 2022 |
| Protectli     | FW4B                        | [a2f902524b](https://bsd-hardware.info/?probe=a2f902524b) | Apr 06, 2022 |
| Protectli     | FW4B                        | [af9f2d81b5](https://bsd-hardware.info/?probe=af9f2d81b5) | Apr 06, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1800a41f61](https://bsd-hardware.info/?probe=1800a41f61) | Mar 28, 2022 |
| Inventec      | D CLASS A02                 | [2ea328c95d](https://bsd-hardware.info/?probe=2ea328c95d) | Mar 28, 2022 |
| Gigabyte      | Z87N-WIFI                   | [8f20a3214b](https://bsd-hardware.info/?probe=8f20a3214b) | Mar 25, 2022 |
| Intel         | Q3XXG4-P V1.0               | [1e9ea7cdbc](https://bsd-hardware.info/?probe=1e9ea7cdbc) | Mar 19, 2022 |
| Dell          | 00V62H A00                  | [8da46f8dd0](https://bsd-hardware.info/?probe=8da46f8dd0) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| MSI           | MS-B1831                    | [346c445c21](https://bsd-hardware.info/?probe=346c445c21) | Mar 12, 2022 |
| MSI           | MS-B1831                    | [572bb2c98c](https://bsd-hardware.info/?probe=572bb2c98c) | Mar 02, 2022 |
| Protectli     | VP2410 10                   | [8d5986c1f4](https://bsd-hardware.info/?probe=8d5986c1f4) | Feb 26, 2022 |
| MSI           | MAG B550M BAZOOKA           | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| MSI           | MAG B550M BAZOOKA           | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| Protectli     | VP2410 10                   | [1d9eaaaf62](https://bsd-hardware.info/?probe=1d9eaaaf62) | Feb 18, 2022 |
| HARDKERNEL    | ODROID-H2                   | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
| MSI           | MS-B1831                    | [5bdc589f33](https://bsd-hardware.info/?probe=5bdc589f33) | Feb 10, 2022 |
| HP            | ProLiant MicroServer Gen... | [0cc80ca4ec](https://bsd-hardware.info/?probe=0cc80ca4ec) | Feb 07, 2022 |
| MSI           | MS-B1831                    | [c8072d090e](https://bsd-hardware.info/?probe=c8072d090e) | Feb 06, 2022 |
| Protectli     | FW4B Ver                    | [6eecbfde04](https://bsd-hardware.info/?probe=6eecbfde04) | Feb 05, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | [8751a2776e](https://bsd-hardware.info/?probe=8751a2776e) | Jan 31, 2022 |
| Dell          | 0NW6H5 A00                  | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NW6H5 A00                  | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
| Lenovo        | SHARKBAY NOK                | [6ea3284f28](https://bsd-hardware.info/?probe=6ea3284f28) | Jan 29, 2022 |
| Lenovo        | ThinkCentre M58 7360BB6     | [f53622f02b](https://bsd-hardware.info/?probe=f53622f02b) | Jan 27, 2022 |
| HP            | ProLiant MicroServer        | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| Cisco         | ASA5512 A0                  | [99d276f574](https://bsd-hardware.info/?probe=99d276f574) | Jan 18, 2022 |
| Dell          | 0XCR8D A03                  | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| Gigabyte      | Z77N-WIFI                   | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Protectli     | FW4B Ver                    | [e0eb7a3239](https://bsd-hardware.info/?probe=e0eb7a3239) | Jan 13, 2022 |
| HP            | 1998                        | [1d46974005](https://bsd-hardware.info/?probe=1d46974005) | Jan 03, 2022 |
| HP            | ProLiant MicroServer        | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | X99-E-10G WS                | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Intel         | SKYBAY                      | [40d8768e52](https://bsd-hardware.info/?probe=40d8768e52) | Dec 20, 2021 |
| Protectli     | FW6 Ver                     | [52ba0807f9](https://bsd-hardware.info/?probe=52ba0807f9) | Dec 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [bc910b229a](https://bsd-hardware.info/?probe=bc910b229a) | Dec 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | [ab56e6eca2](https://bsd-hardware.info/?probe=ab56e6eca2) | Nov 23, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [645f845f43](https://bsd-hardware.info/?probe=645f845f43) | Nov 21, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [8a8efba0b3](https://bsd-hardware.info/?probe=8a8efba0b3) | Nov 19, 2021 |
| Dell          | 0T10XW A01                  | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| AAEON         | EMB-H61A V1.0               | [f13f63617f](https://bsd-hardware.info/?probe=f13f63617f) | Nov 11, 2021 |
| Protectli     | FW4B Ver                    | [fc32ac51e4](https://bsd-hardware.info/?probe=fc32ac51e4) | Nov 10, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [4d9532acfa](https://bsd-hardware.info/?probe=4d9532acfa) | Nov 07, 2021 |
| ASRock        | X370 Gaming X               | [2a874a33dd](https://bsd-hardware.info/?probe=2a874a33dd) | Nov 05, 2021 |
| Gateway       | DX4840                      | [1d2e9e175c](https://bsd-hardware.info/?probe=1d2e9e175c) | Nov 01, 2021 |
| Dell          | 0NW6H5 A00                  | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| HP            | 18E9                        | [9c9a3a0297](https://bsd-hardware.info/?probe=9c9a3a0297) | Oct 27, 2021 |
| ASUSTek       | P10S WS                     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| HP            | ProLiant ML150 G6           | [06b8fc5c06](https://bsd-hardware.info/?probe=06b8fc5c06) | Oct 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
| Protectli     | FW4B                        | [e20e889703](https://bsd-hardware.info/?probe=e20e889703) | Oct 16, 2021 |
| Acer          | Veriton X4610G              | [2ca4d093d3](https://bsd-hardware.info/?probe=2ca4d093d3) | Oct 01, 2021 |
| ASRock        | B560M Pro4/ac               | [1b057f3b7d](https://bsd-hardware.info/?probe=1b057f3b7d) | Sep 23, 2021 |
| ASRock        | B560M Pro4/ac               | [fcf75fc410](https://bsd-hardware.info/?probe=fcf75fc410) | Sep 23, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [be32d2981b](https://bsd-hardware.info/?probe=be32d2981b) | Sep 19, 2021 |
| Gigabyte      | EP45-UD3R                   | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [49f080ea2e](https://bsd-hardware.info/?probe=49f080ea2e) | Sep 12, 2021 |
| Dell          | 0NW6H5 A00                  | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
| Protectli     | FW4B                        | [941392a0bb](https://bsd-hardware.info/?probe=941392a0bb) | Sep 11, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| ASRock        | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| HP            | ProLiant MicroServer        | [114ef9a519](https://bsd-hardware.info/?probe=114ef9a519) | Aug 30, 2021 |
| ASRock        | 990FX Killer                | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| ASRock        | Z390 Pro4                   | [aca402061b](https://bsd-hardware.info/?probe=aca402061b) | Aug 18, 2021 |
| Foxconn       | 2ADA                        | [e96976b2cc](https://bsd-hardware.info/?probe=e96976b2cc) | Aug 18, 2021 |
| HP            | 1825                        | [970bb6f787](https://bsd-hardware.info/?probe=970bb6f787) | Aug 17, 2021 |
| Acer          | Veriton X4610G              | [619dedc13e](https://bsd-hardware.info/?probe=619dedc13e) | Aug 11, 2021 |
| Dell          | 0XPDFK A01                  | [97781253f2](https://bsd-hardware.info/?probe=97781253f2) | Aug 03, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [8e67b63c6a](https://bsd-hardware.info/?probe=8e67b63c6a) | Jul 19, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [cfb68fd411](https://bsd-hardware.info/?probe=cfb68fd411) | Jul 14, 2021 |
| HP            | ProLiant MicroServer Gen... | [519168441f](https://bsd-hardware.info/?probe=519168441f) | Jul 10, 2021 |
| Dell          | 0NW6H5 A00                  | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
| ASRock        | Z390 Pro4                   | [dc4eb674ea](https://bsd-hardware.info/?probe=dc4eb674ea) | Jul 03, 2021 |
| Protectli     | FW2B Ver                    | [7b6f704247](https://bsd-hardware.info/?probe=7b6f704247) | Jun 30, 2021 |
| Dell          | 0GTK4K A02                  | [53f4f785ba](https://bsd-hardware.info/?probe=53f4f785ba) | Jun 22, 2021 |
| Dell          | 0GTK4K A02                  | [bb610333d0](https://bsd-hardware.info/?probe=bb610333d0) | Jun 22, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [2a6f8cdb64](https://bsd-hardware.info/?probe=2a6f8cdb64) | Jun 20, 2021 |
| Gigabyte      | J1900N-D3V                  | [c2cdbdb012](https://bsd-hardware.info/?probe=c2cdbdb012) | Jun 15, 2021 |
| Protectli     | VP2410 10                   | [27a4d07d70](https://bsd-hardware.info/?probe=27a4d07d70) | Jun 12, 2021 |
| Protectli     | VP2410 10                   | [5dd0792386](https://bsd-hardware.info/?probe=5dd0792386) | Jun 12, 2021 |
| Unknown       | J3160-4L                    | [3e773132b3](https://bsd-hardware.info/?probe=3e773132b3) | Jun 06, 2021 |
| Protectli     | FW4B Ver                    | [700ba3f063](https://bsd-hardware.info/?probe=700ba3f063) | May 31, 2021 |
| ASUSTek       | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [33b86a7df2](https://bsd-hardware.info/?probe=33b86a7df2) | May 22, 2021 |
| Unknown       | Unknown                     | [7ea373882a](https://bsd-hardware.info/?probe=7ea373882a) | May 19, 2021 |
| Unknown       | Unknown                     | [72eb276213](https://bsd-hardware.info/?probe=72eb276213) | May 05, 2021 |
| Shuttle       | DH370                       | [ad380cb985](https://bsd-hardware.info/?probe=ad380cb985) | May 04, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [6a62687665](https://bsd-hardware.info/?probe=6a62687665) | May 03, 2021 |
| Gigabyte      | J1900N-D3V                  | [3e211c52ea](https://bsd-hardware.info/?probe=3e211c52ea) | Apr 21, 2021 |
| ASUSTek       | PRIME H310M-K               | [cb97f230b8](https://bsd-hardware.info/?probe=cb97f230b8) | Apr 09, 2021 |
| Dell          | 0WMJ54 A01                  | [bc3913fead](https://bsd-hardware.info/?probe=bc3913fead) | Apr 06, 2021 |
| HARDKERNEL    | ODROID-H2                   | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
| Unknown       | Unknown                     | [e66fe7a153](https://bsd-hardware.info/?probe=e66fe7a153) | Mar 21, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [bf9f69e68b](https://bsd-hardware.info/?probe=bf9f69e68b) | Mar 11, 2021 |
| Dell          | 0NW6H5 A00                  | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| PC Engines    | apu4                        | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Dell          | 0NW6H5 A00                  | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | [8fda503f16](https://bsd-hardware.info/?probe=8fda503f16) | Feb 27, 2021 |
| ASUSTek       | B75M-PLUS                   | [8379cc790c](https://bsd-hardware.info/?probe=8379cc790c) | Feb 25, 2021 |
| Dell          | 0XCR8D A03                  | [8aa33e35ad](https://bsd-hardware.info/?probe=8aa33e35ad) | Feb 21, 2021 |
| HARDKERNEL    | ODROID-H2                   | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| ASUSTek       | P5E3                        | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| HP            | 802E                        | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [40793aaedb](https://bsd-hardware.info/?probe=40793aaedb) | Jan 26, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [a2c7bfe3a1](https://bsd-hardware.info/?probe=a2c7bfe3a1) | Jan 26, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [a344f83f2e](https://bsd-hardware.info/?probe=a344f83f2e) | Jan 25, 2021 |
| Acer          | Veriton S6610G              | [64587ce287](https://bsd-hardware.info/?probe=64587ce287) | Jan 23, 2021 |
| HP            | ProLiant MicroServer        | [a78907417f](https://bsd-hardware.info/?probe=a78907417f) | Jan 22, 2021 |
| Dell          | 0NW6H5 A00                  | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
| HP            | ProLiant MicroServer        | [f51f3873ce](https://bsd-hardware.info/?probe=f51f3873ce) | Dec 25, 2020 |
| ASRock        | A320M-HDV R4.0              | [5e8506d20e](https://bsd-hardware.info/?probe=5e8506d20e) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| ASRock        | X370 Gaming-ITX/ac          | [33724c243d](https://bsd-hardware.info/?probe=33724c243d) | Dec 06, 2020 |
| Dell          | 0M5DCD A00                  | [ec13cfdd0d](https://bsd-hardware.info/?probe=ec13cfdd0d) | Oct 29, 2020 |
| Dell          | 042P49 A02                  | [c34a9c7091](https://bsd-hardware.info/?probe=c34a9c7091) | Oct 29, 2020 |
| HP            | ProLiant MicroServer        | [c1c3ffb720](https://bsd-hardware.info/?probe=c1c3ffb720) | Oct 29, 2020 |
| Unknown       | Unknown                     | [a28ef1d2b8](https://bsd-hardware.info/?probe=a28ef1d2b8) | Oct 20, 2020 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [af179a268f](https://bsd-hardware.info/?probe=af179a268f) | Oct 19, 2020 |
| Unknown       | Unknown                     | [864589fce0](https://bsd-hardware.info/?probe=864589fce0) | Oct 02, 2020 |
| Dell          | 0D6H9T A00                  | [764aaaa200](https://bsd-hardware.info/?probe=764aaaa200) | Jun 04, 2020 |
| Dell          | 0D6H9T A00                  | [158ff0f1b6](https://bsd-hardware.info/?probe=158ff0f1b6) | Jun 04, 2020 |
| HP            | ProLiant ML10 v2            | [aea3696f41](https://bsd-hardware.info/?probe=aea3696f41) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 22.7.10  | 8        | 3.76%   |
| OPNsense 22.1     | 8        | 3.76%   |
| OPNsense 22.7.6   | 7        | 3.29%   |
| OPNsense 23.1.8   | 6        | 2.82%   |
| OPNsense 23.1.5   | 6        | 2.82%   |
| OPNsense 22.7.4   | 5        | 2.35%   |
| OPNsense 21.7.7   | 5        | 2.35%   |
| OPNsense 21.7.2   | 5        | 2.35%   |
| OPNsense 21.1.4   | 5        | 2.35%   |
| OPNsense 20.7.8   | 5        | 2.35%   |
| OPNsense 23.1.7   | 4        | 1.88%   |
| OPNsense 23.1.1   | 4        | 1.88%   |
| OPNsense 22.7.9   | 4        | 1.88%   |
| OPNsense 22.1.6   | 4        | 1.88%   |
| OPNsense 22.1.4   | 4        | 1.88%   |
| OPNsense 22.1.10  | 4        | 1.88%   |
| OPNsense 21.7.3   | 4        | 1.88%   |
| OPNsense 21.1.5   | 4        | 1.88%   |
| OPNsense 21.1.2   | 4        | 1.88%   |
| OPNsense 21.1     | 4        | 1.88%   |
| helloSystem 0.7.0 | 4        | 1.88%   |
| helloSystem 0.5.0 | 4        | 1.88%   |
| OPNsense 23.1.4   | 3        | 1.41%   |
| OPNsense 23.1     | 3        | 1.41%   |
| OPNsense 22.7.5   | 3        | 1.41%   |
| OPNsense 22.7.3   | 3        | 1.41%   |
| OPNsense 21.7.4   | 3        | 1.41%   |
| OPNsense 21.7.1   | 3        | 1.41%   |
| OPNsense 21.1.8   | 3        | 1.41%   |
| OPNsense 21.1.6   | 3        | 1.41%   |
| OPNsense 21.1.3   | 3        | 1.41%   |
| OPNsense 21.1.1   | 3        | 1.41%   |
| helloSystem 0.8.1 | 3        | 1.41%   |
| helloSystem 0.6.0 | 3        | 1.41%   |
| FreeBSD 13.1-p5   | 3        | 1.41%   |
| FreeBSD 12.1-p10  | 3        | 1.41%   |
| OPNsense 23.1.9   | 2        | 0.94%   |
| OPNsense 22.7     | 2        | 0.94%   |
| OPNsense 22.1.8   | 2        | 0.94%   |
| OPNsense 21.7.5   | 2        | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 111      | 67.68%  |
| FreeBSD     | 21       | 12.8%   |
| helloSystem | 16       | 9.76%   |
| TrueNAS     | 5        | 3.05%   |
| OpenBSD     | 3        | 1.83%   |
| GhostBSD    | 3        | 1.83%   |
| FreeNAS     | 2        | 1.22%   |
| XigmaNAS    | 1        | 0.61%   |
| NomadBSD    | 1        | 0.61%   |
| NetBSD      | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 162      | 99.39%  |
| i386  | 1        | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 127      | 76.97%  |
| helloDesktop | 19       | 11.52%  |
| KDE5         | 6        | 3.64%   |
| XFCE         | 5        | 3.03%   |
| TWM          | 2        | 1.21%   |
| GNOME        | 2        | 1.21%   |
| Openbox      | 1        | 0.61%   |
| MATE         | 1        | 0.61%   |
| Lumina       | 1        | 0.61%   |
| i3           | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 133      | 81.1%   |
| X11     | 30       | 18.29%  |
| Wayland | 1        | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 133      | 81.6%   |
| SLiM    | 18       | 11.04%  |
| LightDM | 6        | 3.68%   |
| XDM     | 3        | 1.84%   |
| SDDM    | 3        | 1.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 121      | 73.33%  |
| en_US   | 21       | 12.73%  |
| C       | 12       | 7.27%   |
| en_AU   | 8        | 4.85%   |
| fr_FR   | 1        | 0.61%   |
| fr      | 1        | 0.61%   |
| en      | 1        | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 131      | 80.37%  |
| BIOS | 32       | 19.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 94       | 56.63%  |
| Zfs    | 62       | 37.35%  |
| Cd9660 | 7        | 4.22%   |
| Ffs    | 3        | 1.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 151      | 92.64%  |
| MBR     | 10       | 6.13%   |
| BSD     | 1        | 0.61%   |
| Unknown | 1        | 0.61%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell                       | 23       | 14.11%  |
| Hewlett-Packard            | 17       | 10.43%  |
| Protectli                  | 15       | 9.2%    |
| ASUSTek Computer           | 15       | 9.2%    |
| Unknown                    | 15       | 9.2%    |
| Gigabyte Technology        | 12       | 7.36%   |
| Lenovo                     | 10       | 6.13%   |
| ASRock                     | 10       | 6.13%   |
| Intel                      | 8        | 4.91%   |
| Acer                       | 6        | 3.68%   |
| MSI                        | 4        | 2.45%   |
| Techvision                 | 3        | 1.84%   |
| PC Engines                 | 3        | 1.84%   |
| Shuttle                    | 2        | 1.23%   |
| MW                         | 2        | 1.23%   |
| Inventec                   | 2        | 1.23%   |
| Yanling                    | 1        | 0.61%   |
| Unknown                    | 1        | 0.61%   |
| ShenZhen MinWin Technology | 1        | 0.61%   |
| SeeedStudio                | 1        | 0.61%   |
| Radxa                      | 1        | 0.61%   |
| IBM                        | 1        | 0.61%   |
| HARDKERNEL                 | 1        | 0.61%   |
| Gateway                    | 1        | 0.61%   |
| Foxconn                    | 1        | 0.61%   |
| CWWK                       | 1        | 0.61%   |
| Cisco                      | 1        | 0.61%   |
| AZW                        | 1        | 0.61%   |
| AOpen                      | 1        | 0.61%   |
| AMD                        | 1        | 0.61%   |
| ADI Engineering            | 1        | 0.61%   |
| AAEON                      | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 16       | 9.82%   |
| Protectli FW4B                     | 9        | 5.52%   |
| HP ProLiant MicroServer            | 4        | 2.45%   |
| Dell OptiPlex 9020                 | 4        | 2.45%   |
| Dell OptiPlex 7040                 | 4        | 2.45%   |
| Techvision TVI7309X                | 3        | 1.84%   |
| Protectli VP2410                   | 3        | 1.84%   |
| Protectli FW2B                     | 2        | 1.23%   |
| MW GMLK-2_5G4L                     | 2        | 1.23%   |
| Intel Q3XXG4-P V1.0                | 2        | 1.23%   |
| HP ProLiant MicroServer Gen8       | 2        | 1.23%   |
| Dell OptiPlex 3040                 | 2        | 1.23%   |
| Dell OptiPlex 3010                 | 2        | 1.23%   |
| ASUS STRIX Z270I GAMING            | 2        | 1.23%   |
| ASUS All Series                    | 2        | 1.23%   |
| Yanling YL-KBR6L                   | 1        | 0.61%   |
| Shuttle DS81D                      | 1        | 0.61%   |
| Shuttle DH370                      | 1        | 0.61%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 1        | 0.61%   |
| SeeedStudio ODYSSEY-X86J4125       | 1        | 0.61%   |
| Radxa ROCK Pi X                    | 1        | 0.61%   |
| Protectli FW6                      | 1        | 0.61%   |
| PC Engines apu4                    | 1        | 0.61%   |
| PC Engines APU2                    | 1        | 0.61%   |
| PC Engines apu1                    | 1        | 0.61%   |
| MSI Pro 3130 Small Form Factor PC  | 1        | 0.61%   |
| MSI MS-7C95                        | 1        | 0.61%   |
| MSI MS-7C94                        | 1        | 0.61%   |
| MSI CML-U PRO Cubi 5 (MS-B183)     | 1        | 0.61%   |
| Lenovo ThinkCentre M93p 10AAS3UM00 | 1        | 0.61%   |
| Lenovo ThinkCentre M93p 10AAS2A100 | 1        | 0.61%   |
| Lenovo ThinkCentre M92p 3238CE1    | 1        | 0.61%   |
| Lenovo ThinkCentre M73 10AY009MAU  | 1        | 0.61%   |
| Lenovo ThinkCentre M73 10AXS01800  | 1        | 0.61%   |
| Lenovo ThinkCentre M700 10HYS0Q400 | 1        | 0.61%   |
| Lenovo ThinkCentre M700 10HY002XAU | 1        | 0.61%   |
| Lenovo ThinkCentre M58 7360BB6     | 1        | 0.61%   |
| Lenovo IdeaPad 5 15ITL05 82FG      | 1        | 0.61%   |
| Lenovo H50-50 90B6007BUK           | 1        | 0.61%   |
| Inventec R CLASS                   | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 20       | 12.27%  |
| Unknown                        | 16       | 9.82%   |
| Protectli FW4B                 | 9        | 5.52%   |
| Lenovo ThinkCentre             | 8        | 4.91%   |
| HP ProLiant                    | 8        | 4.91%   |
| Acer Veriton                   | 5        | 3.07%   |
| HP EliteDesk                   | 4        | 2.45%   |
| Techvision TVI7309X            | 3        | 1.84%   |
| Protectli VP2410               | 3        | 1.84%   |
| HP prodesk                     | 3        | 1.84%   |
| ASUS ROG                       | 3        | 1.84%   |
| ASUS PRIME                     | 3        | 1.84%   |
| Protectli FW2B                 | 2        | 1.23%   |
| MW GMLK-2                      | 2        | 1.23%   |
| Intel Q3XXG4-P                 | 2        | 1.23%   |
| ASUS STRIX                     | 2        | 1.23%   |
| ASUS All                       | 2        | 1.23%   |
| ASRock X370                    | 2        | 1.23%   |
| Yanling YL-KBR6L               | 1        | 0.61%   |
| Shuttle DS81D                  | 1        | 0.61%   |
| Shuttle DH370                  | 1        | 0.61%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.61%   |
| SeeedStudio ODYSSEY-X86J4125   | 1        | 0.61%   |
| Radxa ROCK                     | 1        | 0.61%   |
| Protectli FW6                  | 1        | 0.61%   |
| PC Engines apu4                | 1        | 0.61%   |
| PC Engines APU2                | 1        | 0.61%   |
| PC Engines apu1                | 1        | 0.61%   |
| MSI Pro                        | 1        | 0.61%   |
| MSI MS-7C95                    | 1        | 0.61%   |
| MSI MS-7C94                    | 1        | 0.61%   |
| MSI CML-U                      | 1        | 0.61%   |
| Lenovo IdeaPad                 | 1        | 0.61%   |
| Lenovo H50-50                  | 1        | 0.61%   |
| Inventec R                     | 1        | 0.61%   |
| Inventec D                     | 1        | 0.61%   |
| Intel QHSW02                   | 1        | 0.61%   |
| Intel NCB-4210WG               | 1        | 0.61%   |
| Intel MAHOBAY                  | 1        | 0.61%   |
| Intel J1900                    | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 20       | 12.27%  |
| 2018    | 18       | 11.04%  |
| 2016    | 16       | 9.82%   |
| 2013    | 15       | 9.2%    |
| 2021    | 14       | 8.59%   |
| 2014    | 13       | 7.98%   |
| 2022    | 11       | 6.75%   |
| 2020    | 11       | 6.75%   |
| 2017    | 9        | 5.52%   |
| 2011    | 8        | 4.91%   |
| 2012    | 7        | 4.29%   |
| 2015    | 6        | 3.68%   |
| 2009    | 4        | 2.45%   |
| 2010    | 3        | 1.84%   |
| 2008    | 3        | 1.84%   |
| Unknown | 3        | 1.84%   |
| 2023    | 1        | 0.61%   |
| 2006    | 1        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 163      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 155      | 95.09%  |
| Yes  | 8        | 4.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 77       | 46.39%  |
| 16.01-24.0  | 42       | 25.3%   |
| 4.01-8.0    | 25       | 15.06%  |
| 32.01-64.0  | 11       | 6.63%   |
| 2.01-3.0    | 4        | 2.41%   |
| 24.01-32.0  | 3        | 1.81%   |
| 64.01-256.0 | 3        | 1.81%   |
| 0.51-1.0    | 1        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 90       | 52.94%  |
| 0.51-1.0   | 48       | 28.24%  |
| 1.01-2.0   | 15       | 8.82%   |
| 4.01-8.0   | 5        | 2.94%   |
| 2.01-3.0   | 4        | 2.35%   |
| 3.01-4.0   | 2        | 1.18%   |
| 16.01-24.0 | 2        | 1.18%   |
| 8.01-16.0  | 2        | 1.18%   |
| 32.01-64.0 | 1        | 0.59%   |
| Unknown    | 1        | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 70.3%   |
| 2      | 17       | 10.3%   |
| 0      | 11       | 6.67%   |
| 3      | 10       | 6.06%   |
| 4      | 4        | 2.42%   |
| 5      | 3        | 1.82%   |
| 7      | 2        | 1.21%   |
| 10     | 1        | 0.61%   |
| 6      | 1        | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 131      | 80.37%  |
| Yes       | 32       | 19.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 161      | 98.77%  |
| No        | 2        | 1.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 78.66%  |
| Yes       | 35       | 21.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 85.37%  |
| Yes       | 24       | 14.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 163      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 51       | 29.31%  |
| Melbourne      | 27       | 15.52%  |
| Perth          | 19       | 10.92%  |
| Brisbane       | 19       | 10.92%  |
| Adelaide       | 9        | 5.17%   |
| Canberra       | 4        | 2.3%    |
| Hobart         | 3        | 1.72%   |
| Marrickville   | 2        | 1.15%   |
| Ipswich        | 2        | 1.15%   |
| Unknown        | 2        | 1.15%   |
| Wollongong     | 1        | 0.57%   |
| Wheelers Hill  | 1        | 0.57%   |
| Wallan         | 1        | 0.57%   |
| Townsville     | 1        | 0.57%   |
| Southport      | 1        | 0.57%   |
| Shell Cove     | 1        | 0.57%   |
| Ryde           | 1        | 0.57%   |
| Roxby Downs    | 1        | 0.57%   |
| Rosanna        | 1        | 0.57%   |
| Ringwood       | 1        | 0.57%   |
| North Shore    | 1        | 0.57%   |
| Noble Park     | 1        | 0.57%   |
| Nickol         | 1        | 0.57%   |
| Mount Waverley | 1        | 0.57%   |
| Morwell        | 1        | 0.57%   |
| Mooroolbark    | 1        | 0.57%   |
| Malvern        | 1        | 0.57%   |
| Kurunjang      | 1        | 0.57%   |
| Kooyong        | 1        | 0.57%   |
| Kellyville     | 1        | 0.57%   |
| Gold Coast     | 1        | 0.57%   |
| Glen Iris      | 1        | 0.57%   |
| Geelong        | 1        | 0.57%   |
| Engadine       | 1        | 0.57%   |
| East Malvern   | 1        | 0.57%   |
| Dowerin        | 1        | 0.57%   |
| Dandenong      | 1        | 0.57%   |
| Corio          | 1        | 0.57%   |
| Campbelltown   | 1        | 0.57%   |
| Brunswick      | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 50     | 17%     |
| Seagate             | 29       | 37     | 14.5%   |
| WDC                 | 23       | 67     | 11.5%   |
| Kingston            | 13       | 21     | 6.5%    |
| Crucial             | 12       | 14     | 6%      |
| Intel               | 10       | 17     | 5%      |
| Hoodisk             | 10       | 19     | 5%      |
| Toshiba             | 8        | 12     | 4%      |
| SanDisk             | 7        | 10     | 3.5%    |
| China               | 5        | 5      | 2.5%    |
| Protectli           | 4        | 4      | 2%      |
| Micron Technology   | 4        | 5      | 2%      |
| OCZ                 | 3        | 4      | 1.5%    |
| Hewlett-Packard     | 3        | 6      | 1.5%    |
| A-DATA Technology   | 3        | 8      | 1.5%    |
| Phison              | 2        | 2      | 1%      |
| KIOXIA              | 2        | 2      | 1%      |
| KingDian            | 2        | 2      | 1%      |
| Gigabyte Technology | 2        | 2      | 1%      |
| Dogfish             | 2        | 3      | 1%      |
| BIWIN               | 2        | 2      | 1%      |
| XUNZHE              | 1        | 1      | 0.5%    |
| Vaseky              | 1        | 4      | 0.5%    |
| Transcend           | 1        | 1      | 0.5%    |
| SPCC                | 1        | 5      | 0.5%    |
| SK hynix            | 1        | 1      | 0.5%    |
| Silicon Motion      | 1        | 1      | 0.5%    |
| ShiJi               | 1        | 1      | 0.5%    |
| Qunion              | 1        | 1      | 0.5%    |
| PNY                 | 1        | 1      | 0.5%    |
| Plextor             | 1        | 2      | 0.5%    |
| Patriot             | 1        | 1      | 0.5%    |
| NVMe                | 1        | 1      | 0.5%    |
| Maxtor              | 1        | 1      | 0.5%    |
| LITEONIT            | 1        | 1      | 0.5%    |
| KingSpec            | 1        | 1      | 0.5%    |
| Hitachi             | 1        | 1      | 0.5%    |
| HGST                | 1        | 1      | 0.5%    |
| Fordisk             | 1        | 1      | 0.5%    |
| Fanxiang            | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hoodisk SSD 128GB                | 7        | 3.14%   |
| Samsung SSD 850 EVO 500GB        | 4        | 1.79%   |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 1.35%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 1.35%   |
| Samsung SSD 840 EVO 120GB        | 3        | 1.35%   |
| Kingston SA400S37120G 120GB      | 3        | 1.35%   |
| Crucial CT250P2SSD8 250GB        | 3        | 1.35%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 1.35%   |
| WDC WDS250G2B0A-00SM50 250GB     | 2        | 0.9%    |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.9%    |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.9%    |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.9%    |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 0.9%    |
| Toshiba MK6475GSX 640GB          | 2        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.9%    |
| Samsung SSD 980 500GB            | 2        | 0.9%    |
| Samsung SSD 970 EVO Plus 250GB   | 2        | 0.9%    |
| Samsung SSD 860 EVO 500GB        | 2        | 0.9%    |
| Samsung MZ7LN128HCHP-000H1 128GB | 2        | 0.9%    |
| Protectli 120GB mSATA            | 2        | 0.9%    |
| KIOXIA KXG60ZNV256G 256GB        | 2        | 0.9%    |
| Kingston SA400S37480G 480GB      | 2        | 0.9%    |
| Kingston SA400S37240G 240GB      | 2        | 0.9%    |
| China SATA SSD 16GB              | 2        | 0.9%    |
| XUNZHE MSATA 128GB               | 1        | 0.45%   |
| WDC WDS500G1R0B-68A4Z0 500GB     | 1        | 0.45%   |
| WDC WDS250G2B0C-00PXH0 250GB     | 1        | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB     | 1        | 0.45%   |
| WDC WD80EFAX-68KNBN0 8TB         | 1        | 0.45%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.45%   |
| WDC WD5000BPKT-00PK4T0 500GB     | 1        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.45%   |
| WDC WD4000AAKS-00TMA0 400GB      | 1        | 0.45%   |
| WDC WD30EZRX-00SPEB0 3TB         | 1        | 0.45%   |
| WDC WD30EZRX-00MMMB0 3TB         | 1        | 0.45%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.45%   |
| WDC WD20EARX-008FB0 2TB          | 1        | 0.45%   |
| WDC WD20EARS-00MVWB0 2TB         | 1        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 37     | 44.62%  |
| WDC                 | 19       | 60     | 29.23%  |
| Toshiba             | 6        | 8      | 9.23%   |
| Samsung Electronics | 3        | 5      | 4.62%   |
| Hewlett-Packard     | 3        | 6      | 4.62%   |
| NVMe                | 1        | 1      | 1.54%   |
| Maxtor              | 1        | 1      | 1.54%   |
| Hitachi             | 1        | 1      | 1.54%   |
| HGST                | 1        | 1      | 1.54%   |
| China               | 1        | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 22       | 33     | 20.56%  |
| Kingston            | 12       | 19     | 11.21%  |
| Hoodisk             | 10       | 19     | 9.35%   |
| Intel               | 8        | 15     | 7.48%   |
| Crucial             | 8        | 10     | 7.48%   |
| SanDisk             | 7        | 10     | 6.54%   |
| WDC                 | 4        | 6      | 3.74%   |
| Protectli           | 4        | 4      | 3.74%   |
| Micron Technology   | 4        | 5      | 3.74%   |
| China               | 4        | 4      | 3.74%   |
| OCZ                 | 3        | 4      | 2.8%    |
| Toshiba             | 2        | 4      | 1.87%   |
| KingDian            | 2        | 2      | 1.87%   |
| Dogfish             | 2        | 3      | 1.87%   |
| XUNZHE              | 1        | 1      | 0.93%   |
| Vaseky              | 1        | 4      | 0.93%   |
| Transcend           | 1        | 1      | 0.93%   |
| SK hynix            | 1        | 1      | 0.93%   |
| ShiJi               | 1        | 1      | 0.93%   |
| Qunion              | 1        | 1      | 0.93%   |
| Plextor             | 1        | 2      | 0.93%   |
| Phison              | 1        | 1      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| Fordisk             | 1        | 1      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |
| BIWIN               | 1        | 1      | 0.93%   |
| A-DATA Technology   | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 100      | 157    | 56.5%   |
| HDD  | 49       | 121    | 27.68%  |
| NVMe | 28       | 42     | 15.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 136      | 278    | 82.93%  |
| NVMe | 28       | 42     | 17.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 115      | 187    | 72.78%  |
| 0.51-1.0   | 19       | 29     | 12.03%  |
| 1.01-2.0   | 11       | 30     | 6.96%   |
| 3.01-4.0   | 7        | 13     | 4.43%   |
| 2.01-3.0   | 3        | 12     | 1.9%    |
| 4.01-10.0  | 2        | 5      | 1.27%   |
| 10.01-20.0 | 1        | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 76       | 46.06%  |
| 251-500    | 24       | 14.55%  |
| 1-20       | 22       | 13.33%  |
| 51-100     | 15       | 9.09%   |
| 501-1000   | 13       | 7.88%   |
| 21-50      | 9        | 5.45%   |
| 1001-2000  | 4        | 2.42%   |
| 2001-3000  | 2        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 152      | 89.94%  |
| 21-50     | 12       | 7.1%    |
| 101-250   | 2        | 1.18%   |
| 51-100    | 2        | 1.18%   |
| 1001-2000 | 1        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB           | 2        | 2      | 10%     |
| WDC WDS240G2G0A-00JH30 240GB              | 1        | 1      | 5%      |
| WDC WD30EFRX-68EUZN0 3TB                  | 1        | 1      | 5%      |
| WDC WD20EZRX-00D8PB0 2TB                  | 1        | 2      | 5%      |
| WDC WD20EARX-008FB0 2TB                   | 1        | 4      | 5%      |
| WDC WD20EARS-00MVWB0 2TB                  | 1        | 1      | 5%      |
| Toshiba KSG60ZSE256G SATA 256GB           | 1        | 1      | 5%      |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB           | 1        | 1      | 5%      |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 5%      |
| Seagate ST2000LM015-2E8174 2TB            | 1        | 1      | 5%      |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 1      | 5%      |
| Seagate ST1000DM003-1CH162 1TB            | 1        | 1      | 5%      |
| SanDisk SDSSDA240G 240GB                  | 1        | 1      | 5%      |
| Samsung Electronics HM500LI 500GB         | 1        | 2      | 5%      |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1        | 1      | 5%      |
| Hitachi HDS721010KLA330 1TB               | 1        | 1      | 5%      |
| Hewlett-Packard VB0250EAVER 250GB         | 1        | 1      | 5%      |
| BIWIN SSD 8GB                             | 1        | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 42.11%  |
| WDC                 | 4        | 9      | 21.05%  |
| Toshiba             | 1        | 1      | 5.26%   |
| SanDisk             | 1        | 1      | 5.26%   |
| Samsung Electronics | 1        | 2      | 5.26%   |
| Micron Technology   | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| Hewlett-Packard     | 1        | 1      | 5.26%   |
| BIWIN               | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 57.14%  |
| WDC                 | 3        | 8      | 21.43%  |
| Samsung Electronics | 1        | 2      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| Hewlett-Packard     | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 20     | 73.68%  |
| SSD  | 5        | 5      | 26.32%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 140      | 294    | 87.5%   |
| Malfunc  | 19       | 25     | 11.88%  |
| Detected | 1        | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 136      | 67%     |
| AMD                         | 26       | 12.81%  |
| Samsung Electronics         | 11       | 5.42%   |
| Phison Electronics          | 5        | 2.46%   |
| Micron/Crucial Technology   | 4        | 1.97%   |
| Silicon Motion              | 3        | 1.48%   |
| Broadcom / LSI              | 3        | 1.48%   |
| Toshiba                     | 2        | 0.99%   |
| Kingston Technology Company | 2        | 0.99%   |
| ASMedia Technology          | 2        | 0.99%   |
| Silicon Image               | 1        | 0.49%   |
| SanDisk                     | 1        | 0.49%   |
| Realtek Semiconductor       | 1        | 0.49%   |
| QLogic                      | 1        | 0.49%   |
| Marvell Technology Group    | 1        | 0.49%   |
| JMicron Technology          | 1        | 0.49%   |
| Hewlett-Packard             | 1        | 0.49%   |
| ADATA Technology            | 1        | 0.49%   |
| Adaptec                     | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18       | 7.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 6.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13       | 5.65%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9        | 3.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 3.91%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 3.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6        | 2.61%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 5        | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4        | 1.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.74%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.3%    |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.3%    |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 1.3%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.3%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.3%    |
| Toshiba XG6 NVMe SSD Controller                                                         | 2        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.87%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2        | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 0.87%   |
| Silicon Image AAR-1220SA SATA RAID Controller                                           | 1        | 0.43%   |
| SanDisk unknown                                                                         | 1        | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 147      | 70.33%  |
| NVMe | 29       | 13.88%  |
| IDE  | 18       | 8.61%   |
| RAID | 10       | 4.78%   |
| SAS  | 3        | 1.44%   |
| SCSI | 2        | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 137      | 84.05%  |
| AMD    | 26       | 15.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 11       | 6.67%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 7        | 4.24%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 5        | 3.03%   |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 2.42%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 2.42%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 3        | 1.82%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 3        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.82%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2        | 1.21%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 1.21%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.21%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.21%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 1.21%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 2        | 1.21%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 2        | 1.21%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 1.21%   |
| AMD Turion II Neo N40L Dual-Core Processor  | 2        | 1.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.21%   |
| AMD GX-412TC SOC                            | 2        | 1.21%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.21%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.61%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.61%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.61%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.61%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.61%   |
| Intel Xeon                                  | 1        | 0.61%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.61%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1        | 0.61%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.61%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 41       | 25%     |
| Intel Core i5           | 40       | 24.39%  |
| Intel Core i3           | 14       | 8.54%   |
| Intel Core i7           | 13       | 7.93%   |
| Intel Xeon              | 12       | 7.32%   |
| Intel Pentium           | 6        | 3.66%   |
| Other                   | 5        | 3.05%   |
| AMD Turion II Neo       | 4        | 2.44%   |
| AMD Ryzen 5             | 4        | 2.44%   |
| AMD Ryzen 3             | 4        | 2.44%   |
| Intel Core 2 Quad       | 3        | 1.83%   |
| AMD GX                  | 3        | 1.83%   |
| AMD FX                  | 3        | 1.83%   |
| Intel Atom              | 2        | 1.22%   |
| AMD G                   | 2        | 1.22%   |
| AMD Athlon              | 2        | 1.22%   |
| Intel Pentium Silver    | 1        | 0.61%   |
| Intel Pentium Dual-Core | 1        | 0.61%   |
| Intel Pentium 4         | 1        | 0.61%   |
| AMD Ryzen 9             | 1        | 0.61%   |
| AMD E2                  | 1        | 0.61%   |
| AMD A4                  | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 96       | 58.54%  |
| 2       | 44       | 26.83%  |
| 8       | 10       | 6.1%    |
| 6       | 6        | 3.66%   |
| 12      | 3        | 1.83%   |
| Unknown | 3        | 1.83%   |
| 32      | 1        | 0.61%   |
| 1       | 1        | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 161      | 98.77%  |
| 2      | 2        | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 116      | 70.73%  |
| 2       | 45       | 27.44%  |
| Unknown | 3        | 1.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 21       | 12.8%   |
| Haswell       | 21       | 12.8%   |
| KabyLake      | 19       | 11.59%  |
| Skylake       | 17       | 10.37%  |
| IvyBridge     | 12       | 7.32%   |
| SandyBridge   | 9        | 5.49%   |
| Goldmont plus | 9        | 5.49%   |
| Unknown       | 8        | 4.88%   |
| Broadwell     | 5        | 3.05%   |
| Nehalem       | 4        | 2.44%   |
| K10           | 4        | 2.44%   |
| Zen 3         | 3        | 1.83%   |
| Zen           | 3        | 1.83%   |
| Westmere      | 3        | 1.83%   |
| Puma          | 3        | 1.83%   |
| Piledriver    | 3        | 1.83%   |
| Penryn        | 3        | 1.83%   |
| Bobcat        | 3        | 1.83%   |
| Zen+          | 2        | 1.22%   |
| Zen 2         | 2        | 1.22%   |
| TigerLake     | 2        | 1.22%   |
| Jaguar        | 2        | 1.22%   |
| CometLake     | 2        | 1.22%   |
| NetBurst      | 1        | 0.61%   |
| K8 Hammer     | 1        | 0.61%   |
| Goldmont      | 1        | 0.61%   |
| Core          | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 113      | 69.75%  |
| AMD                        | 25       | 15.43%  |
| Nvidia                     | 16       | 9.88%   |
| Matrox Electronics Systems | 6        | 3.7%    |
| Tseng Labs                 | 1        | 0.62%   |
| ASPEED Technology          | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18       | 10.91%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14       | 8.48%   |
| Intel HD Graphics 530                                                                    | 10       | 6.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9        | 5.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 4.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6        | 3.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 3.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 3.03%   |
| Intel HD Graphics 630                                                                    | 5        | 3.03%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4        | 2.42%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 1.82%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3        | 1.82%   |
| Intel HD Graphics 610                                                                    | 3        | 1.82%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.21%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.21%   |
| Intel UHD Graphics 620                                                                   | 2        | 1.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 1.21%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.21%   |
| Intel HD Graphics 5500                                                                   | 2        | 1.21%   |
| Intel HD Graphics 510                                                                    | 2        | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 1.21%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.21%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.21%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.61%   |
| Nvidia GT218 [GeForce 405]                                                               | 1        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.61%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.61%   |
| Nvidia GF100GL [Quadro 4000]                                                             | 1        | 0.61%   |
| Nvidia G92 [GeForce GT 330]                                                              | 1        | 0.61%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 0.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 105      | 63.64%  |
| 1 x AMD        | 22       | 13.33%  |
| 1 x Nvidia     | 14       | 8.48%   |
| Other          | 7        | 4.24%   |
| 1 x Matrox     | 6        | 3.64%   |
| 2 x Intel      | 3        | 1.82%   |
| Intel + AMD    | 3        | 1.82%   |
| Intel + Nvidia | 2        | 1.21%   |
| 2 x AMD        | 1        | 0.61%   |
| 1 x Tseng Labs | 1        | 0.61%   |
| 1 x ASPEED     | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 149      | 91.41%  |
| Proprietary | 7        | 4.29%   |
| Unknown     | 7        | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 148      | 90.24%  |
| 1.01-2.0   | 7        | 4.27%   |
| 0.51-1.0   | 4        | 2.44%   |
| 7.01-8.0   | 2        | 1.22%   |
| 3.01-4.0   | 2        | 1.22%   |
| 0.01-0.5   | 1        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 10.71%  |
| Philips             | 3        | 10.71%  |
| Hewlett-Packard     | 3        | 10.71%  |
| Dell                | 3        | 10.71%  |
| Acer                | 3        | 10.71%  |
| ViewSonic           | 2        | 7.14%   |
| ASUSTek Computer    | 2        | 7.14%   |
| AOC                 | 2        | 7.14%   |
| ___                 | 1        | 3.57%   |
| Toshiba             | 1        | 3.57%   |
| Konka               | 1        | 3.57%   |
| Goldstar            | 1        | 3.57%   |
| Compal              | 1        | 3.57%   |
| BenQ                | 1        | 3.57%   |
| AU Optronics        | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2        | 6.9%    |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 3.45%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1        | 3.45%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch             | 1        | 3.45%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1        | 3.45%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch | 1        | 3.45%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1        | 3.45%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1        | 3.45%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 3.45%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 3.45%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 3.45%   |
| Konka TV_MONITOR KOA0030 2288x1430 1150x650mm 52.0-inch              | 1        | 3.45%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1        | 3.45%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1        | 3.45%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch           | 1        | 3.45%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1        | 3.45%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1        | 3.45%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1        | 3.45%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1        | 3.45%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1        | 3.45%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1        | 3.45%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch       | 1        | 3.45%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 3.45%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1        | 3.45%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1        | 3.45%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1        | 3.45%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                    | 1        | 3.45%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1        | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 55.56%  |
| 2560x1440 (QHD)    | 4        | 14.81%  |
| 1680x1050 (WSXGA+) | 2        | 7.41%   |
| 3840x1600          | 1        | 3.7%    |
| 2560x1080          | 1        | 3.7%    |
| 2288x1430          | 1        | 3.7%    |
| 2048x1152          | 1        | 3.7%    |
| 1920x1200 (WUXGA)  | 1        | 3.7%    |
| 1440x900 (WXGA+)   | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 25%     |
| 24      | 5        | 17.86%  |
| 23      | 3        | 10.71%  |
| 21      | 3        | 10.71%  |
| 22      | 2        | 7.14%   |
| 52      | 1        | 3.57%   |
| 47      | 1        | 3.57%   |
| 37      | 1        | 3.57%   |
| 31      | 1        | 3.57%   |
| 28      | 1        | 3.57%   |
| 19      | 1        | 3.57%   |
| 15      | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 55.56%  |
| 401-500     | 5        | 18.52%  |
| 601-700     | 2        | 7.41%   |
| 1001-1500   | 2        | 7.41%   |
| 801-900     | 1        | 3.7%    |
| 301-350     | 1        | 3.7%    |
| Unknown     | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 21       | 80.77%  |
| 16/10 | 3        | 11.54%  |
| 21/9  | 2        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 40.74%  |
| 301-350        | 7        | 25.93%  |
| 251-300        | 2        | 7.41%   |
| 501-1000       | 2        | 7.41%   |
| More than 1000 | 1        | 3.7%    |
| 351-500        | 1        | 3.7%    |
| 151-200        | 1        | 3.7%    |
| 91-100         | 1        | 3.7%    |
| Unknown        | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 59.26%  |
| 101-120 | 8        | 29.63%  |
| 1-50    | 1        | 3.7%    |
| 121-160 | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 133      | 81.6%   |
| 1     | 28       | 17.18%  |
| 2     | 2        | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 117      | 54.67%  |
| Realtek Semiconductor    | 59       | 27.57%  |
| Broadcom                 | 14       | 6.54%   |
| Qualcomm Atheros         | 11       | 5.14%   |
| U-Blox                   | 2        | 0.93%   |
| TP-Link                  | 2        | 0.93%   |
| D-Link System            | 2        | 0.93%   |
| Seeed Technology         | 1        | 0.47%   |
| Ralink Technology        | 1        | 0.47%   |
| Ralink                   | 1        | 0.47%   |
| Mellanox Technologies    | 1        | 0.47%   |
| Marvell Technology Group | 1        | 0.47%   |
| IMC Networks             | 1        | 0.47%   |
| Aquantia                 | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 52       | 20.39%  |
| Intel I211 Gigabit Network Connection                                         | 30       | 11.76%  |
| Intel I210 Gigabit Network Connection                                         | 10       | 3.92%   |
| Intel Ethernet Connection I217-LM                                             | 9        | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 3.53%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 2.75%   |
| Intel Ethernet Controller I225-V                                              | 6        | 2.35%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 2.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 2.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 2.35%   |
| Intel Ethernet Controller I226-V                                              | 5        | 1.96%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 1.96%   |
| Intel Wireless 7260                                                           | 4        | 1.57%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3        | 1.18%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 1.18%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.18%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 1.18%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.18%   |
| U-Blox [u-blox 7]                                                             | 2        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.78%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.78%   |
| Intel Wireless 8260                                                           | 2        | 0.78%   |
| Intel Wireless 3165                                                           | 2        | 0.78%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.78%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 0.78%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.78%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.78%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.39%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1        | 0.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.39%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 17       | 45.95%  |
| Qualcomm Atheros      | 9        | 24.32%  |
| Realtek Semiconductor | 6        | 16.22%  |
| TP-Link               | 2        | 5.41%   |
| Ralink Technology     | 1        | 2.7%    |
| Ralink                | 1        | 2.7%    |
| IMC Networks          | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 4        | 10.53%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 3        | 7.89%   |
| Intel Wireless 8265 / 8275                                      | 2        | 5.26%   |
| Intel Wireless 8260                                             | 2        | 5.26%   |
| Intel Wireless 3165                                             | 2        | 5.26%   |
| Intel Centrino Wireless-N 2230                                  | 2        | 5.26%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 2.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 1        | 2.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 2.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 1        | 2.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 2.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 2.63%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1        | 2.63%   |
| Ralink RT5572 Wireless Adapter                                  | 1        | 2.63%   |
| Ralink RT5392 PCIe Wireless Network Adapter                     | 1        | 2.63%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1        | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1        | 2.63%   |
| Intel Wi-Fi 6 AX201                                             | 1        | 2.63%   |
| Intel Wi-Fi 6 AX200                                             | 1        | 2.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1        | 2.63%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 2.63%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 111      | 59.04%  |
| Realtek Semiconductor    | 56       | 29.79%  |
| Broadcom                 | 14       | 7.45%   |
| Qualcomm Atheros         | 3        | 1.6%    |
| D-Link System            | 2        | 1.06%   |
| Marvell Technology Group | 1        | 0.53%   |
| Aquantia                 | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 52       | 24.53%  |
| Intel I211 Gigabit Network Connection                                         | 30       | 14.15%  |
| Intel I210 Gigabit Network Connection                                         | 10       | 4.72%   |
| Intel Ethernet Connection I217-LM                                             | 9        | 4.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9        | 4.25%   |
| Intel 82574L Gigabit Network Connection                                       | 7        | 3.3%    |
| Intel Ethernet Controller I225-V                                              | 6        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 2.83%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 2.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6        | 2.83%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 2.83%   |
| Intel Ethernet Controller I226-V                                              | 5        | 2.36%   |
| Intel 82576 Gigabit Network Connection                                        | 5        | 2.36%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.42%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 1.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 3        | 1.42%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 1.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.94%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 0.94%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.94%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.94%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.47%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.47%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.47%   |
| Intel Ethernet Controller X550                                                | 1        | 0.47%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.47%   |
| Intel Ethernet Connection I354                                                | 1        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.47%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.47%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.47%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1        | 0.47%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 80.1%   |
| WiFi     | 35       | 17.41%  |
| Modem    | 3        | 1.49%   |
| Unknown  | 2        | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 158      | 94.05%  |
| WiFi     | 10       | 5.95%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 49       | 29.7%   |
| 1     | 35       | 21.21%  |
| 4     | 34       | 20.61%  |
| 3     | 19       | 11.52%  |
| 5     | 12       | 7.27%   |
| 6     | 11       | 6.67%   |
| 7     | 2        | 1.21%   |
| 10    | 1        | 0.61%   |
| 9     | 1        | 0.61%   |
| 8     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 139      | 82.74%  |
| Yes  | 29       | 17.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 57.69%  |
| Cambridge Silicon Radio         | 3        | 11.54%  |
| Realtek Semiconductor           | 2        | 7.69%   |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| Broadcom                        | 2        | 7.69%   |
| ASUSTek Computer                | 2        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 8        | 30.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3        | 11.54%  |
| Realtek Bluetooth Adapter                                   | 2        | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 7.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 7.69%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2        | 7.69%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 3.85%   |
| Intel AX201 Bluetooth                                       | 1        | 3.85%   |
| Intel AX200 Bluetooth                                       | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 112      | 72.73%  |
| AMD                 | 23       | 14.94%  |
| Nvidia              | 13       | 8.44%   |
| Texas Instruments   | 2        | 1.3%    |
| Focusrite-Novation  | 2        | 1.3%    |
| Logitech            | 1        | 0.65%   |
| C-Media Electronics | 1        | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18       | 9.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18       | 9.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13       | 6.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10       | 5.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 4.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 8        | 4.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6        | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6        | 3.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 3.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 2.65%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4        | 2.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 2.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 2.12%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 2.12%   |
| Intel Broadwell-U Audio Controller                                                                | 3        | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.59%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 1.06%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.06%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2        | 1.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 1.06%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.53%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1        | 0.53%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1        | 0.53%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.53%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.53%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.53%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1        | 0.53%   |
| Logitech Headset H390                                                                             | 1        | 0.53%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 27       | 15.34%  |
| Samsung Electronics | 26       | 14.77%  |
| Micron Technology   | 18       | 10.23%  |
| Unknown             | 17       | 9.66%   |
| SK hynix            | 16       | 9.09%   |
| Crucial             | 15       | 8.52%   |
| Corsair             | 15       | 8.52%   |
| G.Skill             | 8        | 4.55%   |
| Team                | 3        | 1.7%    |
| GeIL                | 3        | 1.7%    |
| Apacer              | 3        | 1.7%    |
| Unknown             | 3        | 1.7%    |
| Unknown (ABCD)      | 2        | 1.14%   |
| Transcend           | 2        | 1.14%   |
| Ramaxel Technology  | 2        | 1.14%   |
| Patriot             | 2        | 1.14%   |
| Kimtigo             | 2        | 1.14%   |
| Vasekey             | 1        | 0.57%   |
| Uroad               | 1        | 0.57%   |
| Timetec             | 1        | 0.57%   |
| Smart Modular       | 1        | 0.57%   |
| Silicon Power       | 1        | 0.57%   |
| PNY                 | 1        | 0.57%   |
| Nanya Technology    | 1        | 0.57%   |
| Kingmax             | 1        | 0.57%   |
| Innodisk            | 1        | 0.57%   |
| Hewlett-Packard     | 1        | 0.57%   |
| Heoriady            | 1        | 0.57%   |
| Elpida              | 1        | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4        | 2.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 4        | 2.2%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 1.65%   |
| Unknown                                                        | 3        | 1.65%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2        | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2        | 1.1%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2        | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 1.1%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 1.1%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2        | 1.1%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 2        | 1.1%    |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s             | 2        | 1.1%    |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s          | 2        | 1.1%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2        | 1.1%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 2        | 1.1%    |
| GeIL RAM CL19-19-19 D4-2666 8GB DIMM DDR4 2667MT/s             | 2        | 1.1%    |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2        | 1.1%    |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                      | 2        | 1.1%    |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1        | 0.55%   |
| Uroad RAM WJD4G8M16N12800 4GB DIMM DDR3 1600MT/s               | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.55%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.55%   |
| Unknown RAM Module 8GB 1600MT/s                                | 1        | 0.55%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1        | 0.55%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.55%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                      | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                        | 1        | 0.55%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.55%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 1        | 0.55%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.55%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                    | 1        | 0.55%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                    | 1        | 0.55%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s            | 1        | 0.55%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s          | 1        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 81       | 52.6%   |
| DDR4    | 58       | 37.66%  |
| Unknown | 8        | 5.19%   |
| LPDDR4  | 2        | 1.3%    |
| DDR2    | 2        | 1.3%    |
| DDR     | 2        | 1.3%    |
| DDR5    | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 105      | 68.63%  |
| SODIMM  | 43       | 28.1%   |
| Unknown | 4        | 2.61%   |
| RIMM    | 1        | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 68       | 41.98%  |
| 4096  | 53       | 32.72%  |
| 2048  | 18       | 11.11%  |
| 16384 | 17       | 10.49%  |
| 32768 | 3        | 1.85%   |
| 1024  | 3        | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 58       | 36.25%  |
| 1333    | 27       | 16.88%  |
| 2400    | 19       | 11.88%  |
| 2133    | 19       | 11.88%  |
| 2667    | 14       | 8.75%   |
| 3200    | 6        | 3.75%   |
| 800     | 5        | 3.13%   |
| 1066    | 3        | 1.88%   |
| 3600    | 2        | 1.25%   |
| 59392   | 1        | 0.63%   |
| 5600    | 1        | 0.63%   |
| 3000    | 1        | 0.63%   |
| 2666    | 1        | 0.63%   |
| 1867    | 1        | 0.63%   |
| 400     | 1        | 0.63%   |
| Unknown | 1        | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 3390 | 1        | 100%    |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Microdia | 1        | 50%     |
| Logitech | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia REDRAGON Live Camera Audio | 1        | 50%     |
| Logitech C922 Pro Stream Webcam     | 1        | 50%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Shenzhen Goodix Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Shenzhen Goodix Fingerprint Reader | 1        | 100%    |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 51.22%  |
| 0     | 54       | 32.93%  |
| 2     | 19       | 11.59%  |
| 3     | 4        | 2.44%   |
| 4     | 2        | 1.22%   |
| 5     | 1        | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 100      | 74.63%  |
| Bluetooth                | 10       | 7.46%   |
| Net/wireless             | 9        | 6.72%   |
| Sound                    | 4        | 2.99%   |
| Card reader              | 4        | 2.99%   |
| Firewire controller      | 3        | 2.24%   |
| Network                  | 2        | 1.49%   |
| Storage/raid             | 1        | 0.75%   |
| Dvb card                 | 1        | 0.75%   |

