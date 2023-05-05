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

Total: 351

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [28253dd080](https://bsd-hardware.info/?probe=28253dd080) | Apr 28, 2023 |
| Sophos        | XG                          | Firewall    | [5202fd70b1](https://bsd-hardware.info/?probe=5202fd70b1) | Apr 23, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| HP            | 82B4                        | Desktop     | [b75bb5fe83](https://bsd-hardware.info/?probe=b75bb5fe83) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [28c2a703c7](https://bsd-hardware.info/?probe=28c2a703c7) | Apr 18, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [737250a1c8](https://bsd-hardware.info/?probe=737250a1c8) | Apr 15, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [1835073ded](https://bsd-hardware.info/?probe=1835073ded) | Apr 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41bf2600a5](https://bsd-hardware.info/?probe=41bf2600a5) | Apr 13, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [036b48e4c3](https://bsd-hardware.info/?probe=036b48e4c3) | Apr 13, 2023 |
| Acer          | Veriton X4630G              | Desktop     | [93987b345d](https://bsd-hardware.info/?probe=93987b345d) | Apr 12, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Dell          | 08VT7V A00                  | Server      | [e801f9c0de](https://bsd-hardware.info/?probe=e801f9c0de) | Apr 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [ee06e14aa2](https://bsd-hardware.info/?probe=ee06e14aa2) | Mar 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [459fdd8cdd](https://bsd-hardware.info/?probe=459fdd8cdd) | Mar 28, 2023 |
| HP            | 82B4                        | Desktop     | [6edc033f79](https://bsd-hardware.info/?probe=6edc033f79) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7db8753b08](https://bsd-hardware.info/?probe=7db8753b08) | Mar 17, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e023282dcd](https://bsd-hardware.info/?probe=e023282dcd) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [b2176fafcf](https://bsd-hardware.info/?probe=b2176fafcf) | Mar 07, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [c9e69ff953](https://bsd-hardware.info/?probe=c9e69ff953) | Mar 03, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [74eedb42ea](https://bsd-hardware.info/?probe=74eedb42ea) | Mar 03, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [f3f963fb6a](https://bsd-hardware.info/?probe=f3f963fb6a) | Feb 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [1f347f15e2](https://bsd-hardware.info/?probe=1f347f15e2) | Feb 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [81911bb61f](https://bsd-hardware.info/?probe=81911bb61f) | Feb 17, 2023 |
| ASUSTek       | H110I-PLUS D3               | Desktop     | [4d3dee18a0](https://bsd-hardware.info/?probe=4d3dee18a0) | Feb 16, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [67d58b9cde](https://bsd-hardware.info/?probe=67d58b9cde) | Feb 14, 2023 |
| Acer          | Aspire TC-230               | Desktop     | [a8ce4299ae](https://bsd-hardware.info/?probe=a8ce4299ae) | Feb 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [4d69517a13](https://bsd-hardware.info/?probe=4d69517a13) | Feb 07, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [31989714d5](https://bsd-hardware.info/?probe=31989714d5) | Feb 04, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [5459c67905](https://bsd-hardware.info/?probe=5459c67905) | Feb 04, 2023 |
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
| OPNsense 22.1     | 9         | 3.15%   |
| OPNsense 22.7.10  | 8         | 2.8%    |
| OPNsense 21.7.7   | 8         | 2.8%    |
| helloSystem 0.5.0 | 8         | 2.8%    |
| OPNsense 22.7.6   | 7         | 2.45%   |
| OPNsense 22.1.6   | 7         | 2.45%   |
| OPNsense 23.1.5   | 6         | 2.1%    |
| OPNsense 22.7.4   | 6         | 2.1%    |
| OPNsense 21.7.1   | 6         | 2.1%    |
| OPNsense 21.1.5   | 6         | 2.1%    |
| OPNsense 21.1.4   | 6         | 2.1%    |
| OPNsense 21.1.3   | 6         | 2.1%    |
| OPNsense 20.7.8   | 6         | 2.1%    |
| helloSystem 0.4.0 | 6         | 2.1%    |
| OPNsense 22.1.10  | 5         | 1.75%   |
| OPNsense 21.7.3   | 5         | 1.75%   |
| OPNsense 21.7.2   | 5         | 1.75%   |
| OPNsense 21.1.6   | 5         | 1.75%   |
| OPNsense 21.1.2   | 5         | 1.75%   |
| helloSystem 0.6.0 | 5         | 1.75%   |
| FreeBSD 13.0      | 5         | 1.75%   |
| FreeBSD 12.2      | 5         | 1.75%   |
| FreeBSD 12.1-p10  | 5         | 1.75%   |
| OPNsense 23.1.4   | 4         | 1.4%    |
| OPNsense 23.1.1   | 4         | 1.4%    |
| OPNsense 23.1     | 4         | 1.4%    |
| OPNsense 22.7.9   | 4         | 1.4%    |
| OPNsense 22.1.4   | 4         | 1.4%    |
| OPNsense 21.1.1   | 4         | 1.4%    |
| OPNsense 21.1     | 4         | 1.4%    |
| OpenBSD 7.2       | 4         | 1.4%    |
| OpenBSD 6.8       | 4         | 1.4%    |
| helloSystem 0.7.0 | 4         | 1.4%    |
| FreeBSD 13.1-p5   | 4         | 1.4%    |
| FreeBSD 13.1      | 4         | 1.4%    |
| OPNsense 22.7.5   | 3         | 1.05%   |
| OPNsense 22.7.3   | 3         | 1.05%   |
| OPNsense 22.7     | 3         | 1.05%   |
| OPNsense 21.7.5   | 3         | 1.05%   |
| OPNsense 21.7.4   | 3         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 135       | 59.21%  |
| FreeBSD     | 42        | 18.42%  |
| helloSystem | 27        | 11.84%  |
| OpenBSD     | 9         | 3.95%   |
| TrueNAS     | 5         | 2.19%   |
| NomadBSD    | 2         | 0.88%   |
| GhostBSD    | 2         | 0.88%   |
| FreeNAS     | 2         | 0.88%   |
| XigmaNAS    | 1         | 0.44%   |
| NetBSD      | 1         | 0.44%   |
| FuguIta     | 1         | 0.44%   |
| ClonOS      | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 225       | 99.12%  |
| i386  | 1         | 0.44%   |
| arm64 | 1         | 0.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 158       | 68.7%   |
| helloDesktop | 33        | 14.35%  |
| KDE5         | 9         | 3.91%   |
| XFCE         | 7         | 3.04%   |
| GNOME        | 6         | 2.61%   |
| TWM          | 4         | 1.74%   |
| fvwm         | 4         | 1.74%   |
| i3           | 3         | 1.3%    |
| Openbox      | 2         | 0.87%   |
| MATE         | 1         | 0.43%   |
| Lumina       | 1         | 0.43%   |
| Fluxbox      | 1         | 0.43%   |
| AwesomeWM    | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 164       | 71.93%  |
| X11     | 62        | 27.19%  |
| Wayland | 2         | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 177       | 77.63%  |
| SLiM    | 30        | 13.16%  |
| SDDM    | 8         | 3.51%   |
| LightDM | 5         | 2.19%   |
| XDM     | 4         | 1.75%   |
| Ly      | 2         | 0.88%   |
| PCDM    | 1         | 0.44%   |
| GDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 158       | 68.1%   |
| en_US           | 36        | 15.52%  |
| C               | 20        | 8.62%   |
| en_AU           | 13        | 5.6%    |
| fr_FR           | 1         | 0.43%   |
| fr              | 1         | 0.43%   |
| en_AU.US-ASCII  | 1         | 0.43%   |
| en_AU.ISO8859-1 | 1         | 0.43%   |
| en              | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 185       | 81.5%   |
| BIOS | 42        | 18.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 122       | 52.81%  |
| Zfs    | 92        | 39.83%  |
| Ffs    | 10        | 4.33%   |
| Cd9660 | 7         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 206       | 90.75%  |
| MBR     | 19        | 8.37%   |
| BSD     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Hewlett-Packard            | 29        | 12.78%  |
| Lenovo                     | 26        | 11.45%  |
| Dell                       | 25        | 11.01%  |
| ASUSTek Computer           | 19        | 8.37%   |
| Unknown                    | 17        | 7.49%   |
| Intel                      | 15        | 6.61%   |
| Protectli                  | 14        | 6.17%   |
| Gigabyte Technology        | 12        | 5.29%   |
| ASRock                     | 10        | 4.41%   |
| Acer                       | 8         | 3.52%   |
| Apple                      | 7         | 3.08%   |
| MSI                        | 4         | 1.76%   |
| Toshiba                    | 3         | 1.32%   |
| Techvision                 | 3         | 1.32%   |
| Sophos                     | 3         | 1.32%   |
| PC Engines                 | 3         | 1.32%   |
| Shuttle                    | 2         | 0.88%   |
| MW                         | 2         | 0.88%   |
| AMI                        | 2         | 0.88%   |
| Yanling                    | 1         | 0.44%   |
| Unknown                    | 1         | 0.44%   |
| Supermicro                 | 1         | 0.44%   |
| ShenZhen MinWin Technology | 1         | 0.44%   |
| SeeedStudio                | 1         | 0.44%   |
| Samsung Electronics        | 1         | 0.44%   |
| Raspberry Pi Foundation    | 1         | 0.44%   |
| Radxa                      | 1         | 0.44%   |
| Microsoft                  | 1         | 0.44%   |
| Inventec                   | 1         | 0.44%   |
| Intel Client Systems       | 1         | 0.44%   |
| IBM                        | 1         | 0.44%   |
| HARDKERNEL                 | 1         | 0.44%   |
| Gateway                    | 1         | 0.44%   |
| Framework                  | 1         | 0.44%   |
| Foxconn                    | 1         | 0.44%   |
| Firewalla                  | 1         | 0.44%   |
| Cisco                      | 1         | 0.44%   |
| AZW                        | 1         | 0.44%   |
| AOpen                      | 1         | 0.44%   |
| AMD                        | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 18        | 7.93%   |
| Protectli FW4B                                                                           | 8         | 3.52%   |
| HP t730 Thin Client                                                                      | 7         | 3.08%   |
| HP ProLiant MicroServer                                                                  | 4         | 1.76%   |
| Techvision TVI7309X                                                                      | 3         | 1.32%   |
| Protectli VP2410                                                                         | 3         | 1.32%   |
| Dell PowerEdge R320                                                                      | 3         | 1.32%   |
| Dell OptiPlex 9020                                                                       | 3         | 1.32%   |
| Sophos XG                                                                                | 2         | 0.88%   |
| Protectli FW2B                                                                           | 2         | 0.88%   |
| MW GMLK-2_5G4L                                                                           | 2         | 0.88%   |
| Intel Q3XXG4-P V1.0                                                                      | 2         | 0.88%   |
| Intel NUC10i5FNH                                                                         | 2         | 0.88%   |
| HP ProLiant MicroServer Gen8                                                             | 2         | 0.88%   |
| Dell OptiPlex 7040                                                                       | 2         | 0.88%   |
| Dell OptiPlex 3040                                                                       | 2         | 0.88%   |
| Dell OptiPlex 3010                                                                       | 2         | 0.88%   |
| ASUS STRIX Z270I GAMING                                                                  | 2         | 0.88%   |
| ASUS All Series                                                                          | 2         | 0.88%   |
| Yanling YL-KBR6L                                                                         | 1         | 0.44%   |
| Toshiba Satellite L50-A                                                                  | 1         | 0.44%   |
| Toshiba PORTEGE Z10t-A                                                                   | 1         | 0.44%   |
| Toshiba KIRA                                                                             | 1         | 0.44%   |
| Supermicro Super Server                                                                  | 1         | 0.44%   |
| Sophos SG                                                                                | 1         | 0.44%   |
| Shuttle DS81D                                                                            | 1         | 0.44%   |
| Shuttle DH370                                                                            | 1         | 0.44%   |
| ShenZhen MinWin MW-NANO-APL-4L                                                           | 1         | 0.44%   |
| SeeedStudio ODYSSEY-X86J4125                                                             | 1         | 0.44%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.44%   |
| RPi Raspberry Pi                                                                         | 1         | 0.44%   |
| Radxa ROCK Pi X                                                                          | 1         | 0.44%   |
| Protectli FW6                                                                            | 1         | 0.44%   |
| PC Engines apu4                                                                          | 1         | 0.44%   |
| PC Engines APU2                                                                          | 1         | 0.44%   |
| PC Engines apu1                                                                          | 1         | 0.44%   |
| MSI Pro 3130 Small Form Factor PC                                                        | 1         | 0.44%   |
| MSI MS-7C95                                                                              | 1         | 0.44%   |
| MSI MS-7C94                                                                              | 1         | 0.44%   |
| MSI CML-U PRO Cubi 5 (MS-B183)                                                           | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 18        | 7.93%   |
| Dell OptiPlex                  | 15        | 6.61%   |
| Lenovo ThinkPad                | 14        | 6.17%   |
| Protectli FW4B                 | 8         | 3.52%   |
| Lenovo ThinkCentre             | 8         | 3.52%   |
| HP ProLiant                    | 8         | 3.52%   |
| HP t730                        | 7         | 3.08%   |
| Dell PowerEdge                 | 7         | 3.08%   |
| Acer Veriton                   | 5         | 2.2%    |
| HP EliteDesk                   | 4         | 1.76%   |
| Techvision TVI7309X            | 3         | 1.32%   |
| Protectli VP2410               | 3         | 1.32%   |
| HP ProDesk                     | 3         | 1.32%   |
| ASUS ROG                       | 3         | 1.32%   |
| ASUS PRIME                     | 3         | 1.32%   |
| Sophos XG                      | 2         | 0.88%   |
| Protectli FW2B                 | 2         | 0.88%   |
| MW GMLK-2                      | 2         | 0.88%   |
| Intel Q3XXG4-P                 | 2         | 0.88%   |
| Intel NUC10i5FNH               | 2         | 0.88%   |
| ASUS STRIX                     | 2         | 0.88%   |
| ASUS All                       | 2         | 0.88%   |
| ASRock X370                    | 2         | 0.88%   |
| Yanling YL-KBR6L               | 1         | 0.44%   |
| Toshiba Satellite              | 1         | 0.44%   |
| Toshiba PORTEGE                | 1         | 0.44%   |
| Toshiba KIRA                   | 1         | 0.44%   |
| Supermicro Super               | 1         | 0.44%   |
| Sophos SG                      | 1         | 0.44%   |
| Shuttle DS81D                  | 1         | 0.44%   |
| Shuttle DH370                  | 1         | 0.44%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.44%   |
| SeeedStudio ODYSSEY-X86J4125   | 1         | 0.44%   |
| Samsung 350V5C                 | 1         | 0.44%   |
| RPi Raspberry                  | 1         | 0.44%   |
| Radxa ROCK                     | 1         | 0.44%   |
| Protectli FW6                  | 1         | 0.44%   |
| PC Engines apu4                | 1         | 0.44%   |
| PC Engines APU2                | 1         | 0.44%   |
| PC Engines apu1                | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 25        | 11.01%  |
| 2020    | 24        | 10.57%  |
| 2018    | 23        | 10.13%  |
| 2021    | 19        | 8.37%   |
| 2015    | 19        | 8.37%   |
| 2014    | 17        | 7.49%   |
| 2013    | 17        | 7.49%   |
| 2016    | 16        | 7.05%   |
| 2017    | 14        | 6.17%   |
| 2022    | 12        | 5.29%   |
| 2012    | 11        | 4.85%   |
| 2011    | 11        | 4.85%   |
| 2009    | 5         | 2.2%    |
| 2010    | 4         | 1.76%   |
| Unknown | 4         | 1.76%   |
| 2008    | 2         | 0.88%   |
| 2007    | 2         | 0.88%   |
| 2023    | 1         | 0.44%   |
| 2006    | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 151       | 66.52%  |
| Notebook       | 39        | 17.18%  |
| Mini pc        | 19        | 8.37%   |
| Server         | 10        | 4.41%   |
| Firewall       | 4         | 1.76%   |
| All in one     | 2         | 0.88%   |
| System on chip | 1         | 0.44%   |
| Tablet         | 1         | 0.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 217       | 95.59%  |
| Yes  | 10        | 4.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 102       | 43.78%  |
| 16.01-24.0  | 56        | 24.03%  |
| 4.01-8.0    | 35        | 15.02%  |
| 32.01-64.0  | 17        | 7.3%    |
| 64.01-256.0 | 9         | 3.86%   |
| 2.01-3.0    | 5         | 2.15%   |
| 3.01-4.0    | 3         | 1.29%   |
| 24.01-32.0  | 3         | 1.29%   |
| 1.01-2.0    | 2         | 0.86%   |
| 0.51-1.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 115       | 48.12%  |
| 0.51-1.0   | 68        | 28.45%  |
| 1.01-2.0   | 28        | 11.72%  |
| 4.01-8.0   | 9         | 3.77%   |
| 2.01-3.0   | 8         | 3.35%   |
| 8.01-16.0  | 3         | 1.26%   |
| 3.01-4.0   | 2         | 0.84%   |
| 16.01-24.0 | 2         | 0.84%   |
| 32.01-64.0 | 1         | 0.42%   |
| 24.01-32.0 | 1         | 0.42%   |
| 0          | 1         | 0.42%   |
| Unknown    | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 162       | 70.74%  |
| 2      | 23        | 10.04%  |
| 0      | 18        | 7.86%   |
| 3      | 11        | 4.8%    |
| 4      | 7         | 3.06%   |
| 5      | 4         | 1.75%   |
| 7      | 2         | 0.87%   |
| 10     | 1         | 0.44%   |
| 6      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 187       | 82.38%  |
| Yes       | 40        | 17.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 95.15%  |
| No        | 11        | 4.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 62.72%  |
| Yes       | 85        | 37.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 72.81%  |
| Yes       | 62        | 27.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 227       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 60        | 24.79%  |
| Melbourne      | 40        | 16.53%  |
| Perth          | 28        | 11.57%  |
| Brisbane       | 27        | 11.16%  |
| Adelaide       | 14        | 5.79%   |
| Canberra       | 7         | 2.89%   |
| Hobart         | 5         | 2.07%   |
| Blackburn      | 3         | 1.24%   |
| Southport      | 2         | 0.83%   |
| Ryde           | 2         | 0.83%   |
| Morwell        | 2         | 0.83%   |
| Marrickville   | 2         | 0.83%   |
| Kellyville     | 2         | 0.83%   |
| Ipswich        | 2         | 0.83%   |
| East Malvern   | 2         | 0.83%   |
| Burwood        | 2         | 0.83%   |
| Unknown        | 2         | 0.83%   |
| Wollongong     | 1         | 0.41%   |
| Whitebridge    | 1         | 0.41%   |
| Wheelers Hill  | 1         | 0.41%   |
| Warrnambool    | 1         | 0.41%   |
| Wallan         | 1         | 0.41%   |
| Townsville     | 1         | 0.41%   |
| South Yarra    | 1         | 0.41%   |
| Shell Cove     | 1         | 0.41%   |
| Roxby Downs    | 1         | 0.41%   |
| Rosanna        | 1         | 0.41%   |
| Ringwood       | 1         | 0.41%   |
| Nyngan         | 1         | 0.41%   |
| Northcote      | 1         | 0.41%   |
| North Shore    | 1         | 0.41%   |
| Noble Park     | 1         | 0.41%   |
| Mount Waverley | 1         | 0.41%   |
| Mount Eliza    | 1         | 0.41%   |
| Mooroolbark    | 1         | 0.41%   |
| Mandurah       | 1         | 0.41%   |
| Malvern        | 1         | 0.41%   |
| Kurunjang      | 1         | 0.41%   |
| Gold Coast     | 1         | 0.41%   |
| Glen Iris      | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 58     | 16.15%  |
| Seagate             | 34        | 50     | 13.08%  |
| WDC                 | 28        | 76     | 10.77%  |
| Kingston            | 18        | 26     | 6.92%   |
| Crucial             | 18        | 22     | 6.92%   |
| Intel               | 17        | 27     | 6.54%   |
| Toshiba             | 14        | 20     | 5.38%   |
| SanDisk             | 12        | 20     | 4.62%   |
| Hoodisk             | 8         | 17     | 3.08%   |
| A-DATA Technology   | 5         | 10     | 1.92%   |
| Protectli           | 4         | 4      | 1.54%   |
| OCZ                 | 4         | 5      | 1.54%   |
| Micron Technology   | 4         | 6      | 1.54%   |
| Phison              | 3         | 3      | 1.15%   |
| NVMe                | 3         | 4      | 1.15%   |
| Hewlett-Packard     | 3         | 6      | 1.15%   |
| Dogfish             | 3         | 3      | 1.15%   |
| China               | 3         | 3      | 1.15%   |
| Transcend           | 2         | 3      | 0.77%   |
| Silicon Motion      | 2         | 2      | 0.77%   |
| KingDian            | 2         | 2      | 0.77%   |
| Hitachi             | 2         | 5      | 0.77%   |
| HGST                | 2         | 2      | 0.77%   |
| Gigabyte Technology | 2         | 2      | 0.77%   |
| BIWIN               | 2         | 2      | 0.77%   |
| Apple               | 2         | 2      | 0.77%   |
| XUNZHE              | 1         | 1      | 0.38%   |
| Vaseky              | 1         | 4      | 0.38%   |
| Union Memory        | 1         | 1      | 0.38%   |
| SPCC                | 1         | 5      | 0.38%   |
| SK hynix            | 1         | 3      | 0.38%   |
| ShiJi               | 1         | 1      | 0.38%   |
| Qunion              | 1         | 1      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| Plextor             | 1         | 2      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| Maxtor              | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| Lenovo              | 1         | 1      | 0.38%   |
| KingSpec            | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Hoodisk SSD 128GB                           | 6         | 2.11%   |
| Samsung SSD 850 EVO 500GB                   | 4         | 1.4%    |
| Crucial CT250MX500SSD1 250GB                | 4         | 1.4%    |
| WDC WD30EFRX-68EUZN0 3TB                    | 3         | 1.05%   |
| Samsung SSD 860 EVO 500GB                   | 3         | 1.05%   |
| Samsung SSD 840 EVO 250GB                   | 3         | 1.05%   |
| Samsung SSD 840 EVO 120GB                   | 3         | 1.05%   |
| Kingston SA400S37480G 480GB                 | 3         | 1.05%   |
| Kingston SA400S37240G 240GB                 | 3         | 1.05%   |
| Kingston SA400S37120G 120GB                 | 3         | 1.05%   |
| Intel SSDSCKKW240H6 240GB                   | 3         | 1.05%   |
| Crucial CT250P2SSD8 250GB                   | 3         | 1.05%   |
| WDC WDS250G2B0A-00SM50 250GB                | 2         | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB                | 2         | 0.7%    |
| WDC WDS120G2G0B-00EPW0 120GB                | 2         | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB                    | 2         | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB                    | 2         | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB                    | 2         | 0.7%    |
| WDC WD20EZAZ-00GGJB0 2TB                    | 2         | 0.7%    |
| Toshiba THNSF5256GPUK 256GB                 | 2         | 0.7%    |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.7%    |
| Seagate ST9500325AS 500GB                   | 2         | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB             | 2         | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 0.7%    |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 2         | 0.7%    |
| SanDisk SDSA6MM-032G-1006 32GB              | 2         | 0.7%    |
| Samsung SSD 970 EVO Plus 250GB              | 2         | 0.7%    |
| Samsung MZ7LN128HCHP-000H1 128GB            | 2         | 0.7%    |
| Protectli 120GB mSATA                       | 2         | 0.7%    |
| Micron MTFDDAK256MAM-1K1 256GB              | 2         | 0.7%    |
| Dogfish SSD 64GB                            | 2         | 0.7%    |
| Crucial CT500MX500SSD1 500GB                | 2         | 0.7%    |
| China SATA SSD 16GB                         | 2         | 0.7%    |
| A-DATA IM2S3134N-064GM 64GB                 | 2         | 0.7%    |
| XUNZHE MSATA 128GB                          | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB                | 1         | 0.35%   |
| WDC WDS500G1R0B-68A4Z0 500GB                | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB                | 1         | 0.35%   |
| WDC WDS250G2B0C-00PXH0 250GB                | 1         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB                | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 48     | 43.84%  |
| WDC                 | 19        | 60     | 26.03%  |
| Toshiba             | 6         | 8      | 8.22%   |
| Samsung Electronics | 3         | 5      | 4.11%   |
| NVMe                | 3         | 3      | 4.11%   |
| Hewlett-Packard     | 3         | 6      | 4.11%   |
| Hitachi             | 2         | 5      | 2.74%   |
| HGST                | 2         | 2      | 2.74%   |
| Maxtor              | 1         | 1      | 1.37%   |
| Jetflash            | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 41     | 19.33%  |
| Kingston            | 17        | 24     | 11.33%  |
| Intel               | 15        | 25     | 10%     |
| Crucial             | 13        | 15     | 8.67%   |
| SanDisk             | 12        | 20     | 8%      |
| WDC                 | 9         | 15     | 6%      |
| Hoodisk             | 8         | 17     | 5.33%   |
| Toshiba             | 4         | 7      | 2.67%   |
| Protectli           | 4         | 4      | 2.67%   |
| OCZ                 | 4         | 5      | 2.67%   |
| Micron Technology   | 4         | 6      | 2.67%   |
| Dogfish             | 3         | 3      | 2%      |
| China               | 3         | 3      | 2%      |
| A-DATA Technology   | 3         | 3      | 2%      |
| Transcend           | 2         | 3      | 1.33%   |
| Phison              | 2         | 2      | 1.33%   |
| KingDian            | 2         | 2      | 1.33%   |
| XUNZHE              | 1         | 1      | 0.67%   |
| Vaseky              | 1         | 4      | 0.67%   |
| ShiJi               | 1         | 1      | 0.67%   |
| Qunion              | 1         | 1      | 0.67%   |
| Plextor             | 1         | 2      | 0.67%   |
| Patriot             | 1         | 1      | 0.67%   |
| NVMe                | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| Lenovo              | 1         | 1      | 0.67%   |
| KingSpec            | 1         | 1      | 0.67%   |
| FORESEE             | 1         | 1      | 0.67%   |
| Fordisk             | 1         | 1      | 0.67%   |
| Corsair             | 1         | 1      | 0.67%   |
| BIWIN               | 1         | 1      | 0.67%   |
| Apple               | 1         | 1      | 0.67%   |
| Apacer              | 1         | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 136       | 215    | 58.12%  |
| HDD  | 59        | 140    | 25.21%  |
| NVMe | 39        | 56     | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 355    | 82.11%  |
| NVMe | 39        | 56     | 17.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 156       | 251    | 76.47%  |
| 0.51-1.0   | 21        | 32     | 10.29%  |
| 1.01-2.0   | 14        | 40     | 6.86%   |
| 3.01-4.0   | 7         | 13     | 3.43%   |
| 2.01-3.0   | 3         | 12     | 1.47%   |
| 4.01-10.0  | 2         | 5      | 0.98%   |
| 10.01-20.0 | 1         | 2      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 97        | 42.17%  |
| 251-500        | 39        | 16.96%  |
| 1-20           | 30        | 13.04%  |
| 51-100         | 24        | 10.43%  |
| 21-50          | 17        | 7.39%   |
| 501-1000       | 15        | 6.52%   |
| 1001-2000      | 5         | 2.17%   |
| 2001-3000      | 2         | 0.87%   |
| More than 3000 | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 211       | 89.41%  |
| 21-50     | 17        | 7.2%    |
| 51-100    | 5         | 2.12%   |
| 101-250   | 2         | 0.85%   |
| 1001-2000 | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 2         | 5      | 7.14%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 3.57%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 2      | 3.57%   |
| WDC WD20EARX-008FB0 2TB                   | 1         | 4      | 3.57%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 3.57%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1      | 3.57%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 3.57%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1      | 3.57%   |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1      | 3.57%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1      | 3.57%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 1      | 3.57%   |
| Samsung Electronics HM500LI 500GB         | 1         | 2      | 3.57%   |
| Phison SATA SSD 32GB                      | 1         | 1      | 3.57%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1         | 1      | 3.57%   |
| Kingston SNS4151S316G 16GB                | 1         | 1      | 3.57%   |
| Kingston SA400S37480G 480GB               | 1         | 1      | 3.57%   |
| Intel SSDSC2BW120H6 120GB                 | 1         | 1      | 3.57%   |
| Intel SSDSC2BF180A4L 180GB                | 1         | 1      | 3.57%   |
| Hitachi HDS721010KLA330 1TB               | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                | 1         | 1      | 3.57%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1         | 1      | 3.57%   |
| Crucial CT275MX300SSD4 275GB              | 1         | 1      | 3.57%   |
| BIWIN SSD 8GB                             | 1         | 1      | 3.57%   |
| Apple SSD SM256E 256GB                    | 1         | 1      | 3.57%   |
| Apacer AS330 240GB                        | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 22.22%  |
| WDC                 | 5         | 13     | 18.52%  |
| Kingston            | 2         | 2      | 7.41%   |
| Intel               | 2         | 2      | 7.41%   |
| Toshiba             | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 2      | 3.7%    |
| Phison              | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |
| Crucial             | 1         | 1      | 3.7%    |
| BIWIN               | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |
| Apacer              | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 46.15%  |
| WDC                 | 3         | 8      | 23.08%  |
| Samsung Electronics | 1         | 2      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| Hewlett-Packard     | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 17     | 51.85%  |
| HDD  | 13        | 19     | 48.15%  |

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
| Works    | 187       | 370    | 85.78%  |
| Malfunc  | 27        | 36     | 12.39%  |
| Detected | 4         | 5      | 1.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 180       | 65.69%  |
| AMD                         | 33        | 12.04%  |
| Samsung Electronics         | 13        | 4.74%   |
| Broadcom / LSI              | 10        | 3.65%   |
| Phison Electronics          | 5         | 1.82%   |
| Micron/Crucial Technology   | 5         | 1.82%   |
| Toshiba                     | 4         | 1.46%   |
| Silicon Motion              | 4         | 1.46%   |
| SanDisk                     | 3         | 1.09%   |
| Seagate Technology          | 2         | 0.73%   |
| Kingston Technology Company | 2         | 0.73%   |
| ASMedia Technology          | 2         | 0.73%   |
| Union Memory (Shenzhen)     | 1         | 0.36%   |
| Silicon Image               | 1         | 0.36%   |
| Realtek Semiconductor       | 1         | 0.36%   |
| QLogic                      | 1         | 0.36%   |
| Nvidia                      | 1         | 0.36%   |
| Micron Technology           | 1         | 0.36%   |
| Marvell Technology Group    | 1         | 0.36%   |
| JMicron Technology          | 1         | 0.36%   |
| Hewlett-Packard             | 1         | 0.36%   |
| ADATA Technology            | 1         | 0.36%   |
| Adaptec                     | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 6.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 6.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14        | 4.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13        | 4.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 10        | 3.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 2.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 2.59%   |
| AMD FCH IDE Controller                                                                  | 8         | 2.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 1.62%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 5         | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.62%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.29%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.97%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.97%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3         | 0.97%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.65%   |
| Seagate FireCuda 520 SSD                                                                | 2         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.65%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.65%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.65%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 2         | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 197       | 68.4%   |
| NVMe | 41        | 14.24%  |
| IDE  | 28        | 9.72%   |
| RAID | 14        | 4.86%   |
| SAS  | 5         | 1.74%   |
| SCSI | 3         | 1.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 193       | 85.02%  |
| AMD    | 33        | 14.54%  |
| ARM    | 1         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz          | 10        | 4.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 7         | 3.04%   |
| AMD RX-427BB with AMD Radeon R7 Graphics   | 7         | 3.04%   |
| Intel Celeron N5105 @ 2.00GHz              | 4         | 1.74%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 3         | 1.3%    |
| Intel Core i5-6500T CPU @ 2.50GHz          | 3         | 1.3%    |
| Intel Core i5-4570T CPU @ 2.90GHz          | 3         | 1.3%    |
| Intel Core i5-3470 CPU @ 3.20GHz           | 3         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz          | 3         | 1.3%    |
| Intel Celeron CPU J1900 @ 1.99GHz          | 3         | 1.3%    |
| Intel Xeon CPU E5504 @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 2         | 0.87%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 2         | 0.87%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2         | 0.87%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 2         | 0.87%   |
| Intel Core i7-3667U CPU @ 2.00GHz          | 2         | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 2         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 2         | 0.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 2         | 0.87%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 2         | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 2         | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 2         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 0.87%   |
| Intel Core i3-6100U CPU @ 2.30GHz          | 2         | 0.87%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 2         | 0.87%   |
| Intel Celeron CPU J3060 @ 1.60GHz          | 2         | 0.87%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 2         | 0.87%   |
| Intel Atom CPU C3508 @ 1.60GHz             | 2         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 2         | 0.87%   |
| AMD Turion II Neo N54L Dual-Core Processor | 2         | 0.87%   |
| AMD Turion II Neo N40L Dual-Core Processor | 2         | 0.87%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2         | 0.87%   |
| AMD GX-412TC SOC                           | 2         | 0.87%   |
| AMD FX-8350 Eight-Core Processor           | 2         | 0.87%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz       | 1         | 0.43%   |
| Intel Xeon E-2224G CPU @ 3.50GHz           | 1         | 0.43%   |
| Intel Xeon CPU W3680 @ 3.33GHz             | 1         | 0.43%   |
| Intel Xeon CPU E5506 @ 2.13GHz             | 1         | 0.43%   |
| Intel Xeon CPU E5310 @ 1.60GHz             | 1         | 0.43%   |
| Intel Xeon CPU E5-2450L v2 @ 1.70GHz       | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 50        | 21.93%  |
| Intel Celeron           | 45        | 19.74%  |
| Intel Core i7           | 31        | 13.6%   |
| Intel Xeon              | 23        | 10.09%  |
| Intel Core i3           | 17        | 7.46%   |
| Other                   | 13        | 5.7%    |
| Intel Pentium           | 8         | 3.51%   |
| Intel Atom              | 5         | 2.19%   |
| AMD Turion II Neo       | 4         | 1.75%   |
| AMD Ryzen 5             | 4         | 1.75%   |
| AMD Ryzen 3             | 4         | 1.75%   |
| Intel Core 2 Quad       | 3         | 1.32%   |
| AMD GX                  | 3         | 1.32%   |
| AMD FX                  | 3         | 1.32%   |
| AMD G                   | 2         | 0.88%   |
| AMD Athlon              | 2         | 0.88%   |
| Intel Xeon Silver       | 1         | 0.44%   |
| Intel Pentium Silver    | 1         | 0.44%   |
| Intel Pentium Dual-Core | 1         | 0.44%   |
| Intel Pentium 4         | 1         | 0.44%   |
| Intel Core Duo          | 1         | 0.44%   |
| Intel Core 2 Duo        | 1         | 0.44%   |
| ARM Cortex              | 1         | 0.44%   |
| AMD Ryzen 9             | 1         | 0.44%   |
| AMD E2                  | 1         | 0.44%   |
| AMD A6                  | 1         | 0.44%   |
| AMD A4                  | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 117       | 51.32%  |
| 2       | 74        | 32.46%  |
| 8       | 13        | 5.7%    |
| 6       | 11        | 4.82%   |
| Unknown | 6         | 2.63%   |
| 12      | 3         | 1.32%   |
| 32      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |
| 10      | 1         | 0.44%   |
| 1       | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 220       | 96.92%  |
| 2       | 5         | 2.2%    |
| Unknown | 2         | 0.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 133       | 58.33%  |
| 2       | 89        | 39.04%  |
| Unknown | 6         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 12.72%  |
| Haswell       | 28        | 12.28%  |
| Silvermont    | 23        | 10.09%  |
| IvyBridge     | 23        | 10.09%  |
| Skylake       | 22        | 9.65%   |
| SandyBridge   | 17        | 7.46%   |
| Goldmont plus | 10        | 4.39%   |
| Unknown       | 9         | 3.95%   |
| Steamroller   | 7         | 3.07%   |
| Broadwell     | 7         | 3.07%   |
| Nehalem       | 5         | 2.19%   |
| Westmere      | 4         | 1.75%   |
| Puma          | 4         | 1.75%   |
| Penryn        | 4         | 1.75%   |
| K10           | 4         | 1.75%   |
| Zen 3         | 3         | 1.32%   |
| Zen           | 3         | 1.32%   |
| TigerLake     | 3         | 1.32%   |
| Piledriver    | 3         | 1.32%   |
| Goldmont      | 3         | 1.32%   |
| CometLake     | 3         | 1.32%   |
| Bobcat        | 3         | 1.32%   |
| Zen+          | 2         | 0.88%   |
| Zen 2         | 2         | 0.88%   |
| Jaguar        | 2         | 0.88%   |
| Core          | 2         | 0.88%   |
| P6            | 1         | 0.44%   |
| NetBurst      | 1         | 0.44%   |
| Bonnell       | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 152       | 64.96%  |
| AMD                        | 36        | 15.38%  |
| Nvidia                     | 26        | 11.11%  |
| Matrox Electronics Systems | 13        | 5.56%   |
| ASPEED Technology          | 5         | 2.14%   |
| Tseng Labs                 | 1         | 0.43%   |
| Silicon Motion             | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 6.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 6.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 4.2%    |
| Intel HD Graphics 530                                                                    | 8         | 3.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 2.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 7         | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.52%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 2.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.1%    |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 2.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 2.1%    |
| Matrox Electronics Systems G200eR2                                                       | 4         | 1.68%   |
| Intel HD Graphics 630                                                                    | 4         | 1.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.68%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 1.68%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.26%   |
| Intel HD Graphics 610                                                                    | 3         | 1.26%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.26%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.84%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.84%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.84%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.84%   |
| Intel HD Graphics 620                                                                    | 2         | 0.84%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.84%   |
| Intel HD Graphics 510                                                                    | 2         | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.84%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 0.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.84%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 133       | 58.08%  |
| 1 x AMD            | 31        | 13.54%  |
| 1 x Nvidia         | 17        | 7.42%   |
| 1 x Matrox         | 13        | 5.68%   |
| Intel + Nvidia     | 9         | 3.93%   |
| Other              | 8         | 3.49%   |
| 2 x Intel          | 5         | 2.18%   |
| Intel + AMD        | 5         | 2.18%   |
| 1 x ASPEED         | 5         | 2.18%   |
| 2 x AMD            | 1         | 0.44%   |
| 1 x Tseng Labs     | 1         | 0.44%   |
| 1 x Silicon Motion | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 210       | 92.11%  |
| Unknown     | 10        | 4.39%   |
| Proprietary | 8         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 92.98%  |
| 1.01-2.0   | 8         | 3.51%   |
| 0.51-1.0   | 4         | 1.75%   |
| 7.01-8.0   | 2         | 0.88%   |
| 3.01-4.0   | 1         | 0.44%   |
| 0.01-0.5   | 1         | 0.44%   |

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
| 0     | 172       | 75.44%  |
| 1     | 54        | 23.68%  |
| 2     | 2         | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 161       | 52.61%  |
| Realtek Semiconductor             | 78        | 25.49%  |
| Broadcom                          | 31        | 10.13%  |
| Qualcomm Atheros                  | 17        | 5.56%   |
| U-Blox                            | 2         | 0.65%   |
| TP-Link                           | 2         | 0.65%   |
| Ericsson Business Mobile Networks | 2         | 0.65%   |
| D-Link System                     | 2         | 0.65%   |
| Sierra Wireless                   | 1         | 0.33%   |
| Seeed Technology                  | 1         | 0.33%   |
| Ralink Technology                 | 1         | 0.33%   |
| Ralink                            | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| Microsoft                         | 1         | 0.33%   |
| Mellanox Technologies             | 1         | 0.33%   |
| Marvell Technology Group          | 1         | 0.33%   |
| IMC Networks                      | 1         | 0.33%   |
| Emulex                            | 1         | 0.33%   |
| Aquantia                          | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68        | 17.57%  |
| Intel I211 Gigabit Network Connection                                         | 32        | 8.27%   |
| Intel I210 Gigabit Network Connection                                         | 13        | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 3.1%    |
| Intel 82574L Gigabit Network Connection                                       | 11        | 2.84%   |
| Intel Wireless 8260                                                           | 9         | 2.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 9         | 2.33%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 1.81%   |
| Intel Wireless 7260                                                           | 6         | 1.55%   |
| Intel Ethernet Controller I225-V                                              | 6         | 1.55%   |
| Intel 82580 Gigabit Network Connection                                        | 6         | 1.55%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 1.55%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 1.55%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 1.29%   |
| Intel I350 Gigabit Network Connection                                         | 5         | 1.29%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 1.03%   |
| Intel Wireless 7265                                                           | 4         | 1.03%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.03%   |
| Intel Ethernet Connection I217-V                                              | 4         | 1.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 0.78%   |
| Intel Wireless 3165                                                           | 3         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 0.78%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 0.78%   |
| U-Blox [u-blox 7]                                                             | 2         | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.52%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 2         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 56.18%  |
| Qualcomm Atheros      | 15        | 16.85%  |
| Realtek Semiconductor | 9         | 10.11%  |
| Broadcom              | 9         | 10.11%  |
| TP-Link               | 2         | 2.25%   |
| Sierra Wireless       | 1         | 1.12%   |
| Ralink Technology     | 1         | 1.12%   |
| Ralink                | 1         | 1.12%   |
| IMC Networks          | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                             | 9         | 9.89%   |
| Intel Wireless 7260                                             | 6         | 6.59%   |
| Intel Wireless 8265 / 8275                                      | 5         | 5.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 4         | 4.4%    |
| Intel Wireless 7265                                             | 4         | 4.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 3         | 3.3%    |
| Intel Wireless 3165                                             | 3         | 3.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 3         | 3.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                  | 3         | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 2.2%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 2         | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 2.2%    |
| Intel Wi-Fi 6 AX201                                             | 2         | 2.2%    |
| Intel Wi-Fi 6 AX200                                             | 2         | 2.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 2.2%    |
| Intel Centrino Wireless-N 2230                                  | 2         | 2.2%    |
| Broadcom BCM43224 802.11a/b/g/n                                 | 2         | 2.2%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1         | 1.1%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 1         | 1.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1         | 1.1%    |
| Sierra Wireless EM7455                                          | 1         | 1.1%    |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 1         | 1.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1         | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.1%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1         | 1.1%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1         | 1.1%    |
| Ralink RT5572 Wireless Adapter                                  | 1         | 1.1%    |
| Ralink RT5392 PCIe Wireless Network Adapter                     | 1         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 1         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 1.1%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 1         | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1         | 1.1%    |
| Intel WiFi Link 5100                                            | 1         | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 1         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1         | 1.1%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection         | 1         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 141       | 55.51%  |
| Realtek Semiconductor    | 74        | 29.13%  |
| Broadcom                 | 27        | 10.63%  |
| Qualcomm Atheros         | 5         | 1.97%   |
| D-Link System            | 2         | 0.79%   |
| Nvidia                   | 1         | 0.39%   |
| Microsoft                | 1         | 0.39%   |
| Marvell Technology Group | 1         | 0.39%   |
| Emulex                   | 1         | 0.39%   |
| Aquantia                 | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 68        | 23.53%  |
| Intel I211 Gigabit Network Connection                                         | 32        | 11.07%  |
| Intel I210 Gigabit Network Connection                                         | 13        | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 12        | 4.15%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 3.81%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 9         | 3.11%   |
| Intel Ethernet Connection I217-LM                                             | 7         | 2.42%   |
| Intel Ethernet Controller I225-V                                              | 6         | 2.08%   |
| Intel 82580 Gigabit Network Connection                                        | 6         | 2.08%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 2.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 2.08%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6         | 2.08%   |
| Intel I350 Gigabit Network Connection                                         | 5         | 1.73%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.73%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.73%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.38%   |
| Intel Ethernet Connection I217-V                                              | 4         | 1.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.04%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3         | 1.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 3         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.69%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.69%   |
| Intel Ethernet Connection X553 1GbE                                           | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                              | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.69%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 2         | 0.69%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2         | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.69%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2         | 0.69%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2         | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 216       | 70.13%  |
| WiFi     | 85        | 27.6%   |
| Modem    | 5         | 1.62%   |
| Unknown  | 2         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 205       | 83%     |
| WiFi     | 41        | 16.6%   |
| Modem    | 1         | 0.4%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 89        | 38.86%  |
| 1     | 41        | 17.9%   |
| 4     | 37        | 16.16%  |
| 3     | 22        | 9.61%   |
| 6     | 15        | 6.55%   |
| 5     | 15        | 6.55%   |
| 9     | 3         | 1.31%   |
| 7     | 3         | 1.31%   |
| 10    | 2         | 0.87%   |
| 8     | 1         | 0.44%   |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 84.05%  |
| Yes  | 37        | 15.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 58.73%  |
| Apple                           | 7         | 11.11%  |
| Broadcom                        | 5         | 7.94%   |
| Realtek Semiconductor           | 4         | 6.35%   |
| Qualcomm Atheros Communications | 3         | 4.76%   |
| Cambridge Silicon Radio         | 3         | 4.76%   |
| ASUSTek Computer                | 2         | 3.17%   |
| IMC Networks                    | 1         | 1.59%   |
| Foxconn / Hon Hai               | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 21        | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 5         | 7.94%   |
| Intel AX201 Bluetooth                                  | 5         | 7.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 3         | 4.76%   |
| Apple Broadcom Built-in Bluetooth                      | 3         | 4.76%   |
| Apple Bluetooth Host Controller                        | 3         | 4.76%   |
| Realtek Bluetooth Adapter                              | 2         | 3.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 2         | 3.17%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 2         | 3.17%   |
| Intel AX200 Bluetooth                                  | 2         | 3.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 2         | 3.17%   |
| ASUS Qualcomm Bluetooth 4.1                            | 2         | 3.17%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                         | 1         | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                 | 1         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                       | 1         | 1.59%   |
| Intel AX210 Bluetooth                                  | 1         | 1.59%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.59%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 1.59%   |
| Broadcom Bluetooth 4.0                                 | 1         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                   | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 149       | 72.33%  |
| AMD                         | 31        | 15.05%  |
| Nvidia                      | 20        | 9.71%   |
| Texas Instruments           | 2         | 0.97%   |
| Focusrite-Novation          | 2         | 0.97%   |
| Logitech                    | 1         | 0.49%   |
| FiiO Electronics Technology | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 7.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 6.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 5.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 4.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 4.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 3.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 3.94%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 3.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 3.15%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 7         | 2.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.97%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.97%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.18%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.79%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1         | 0.39%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 20.76%  |
| Kingston            | 31        | 13.14%  |
| SK hynix            | 25        | 10.59%  |
| Micron Technology   | 24        | 10.17%  |
| Crucial             | 20        | 8.47%   |
| Corsair             | 19        | 8.05%   |
| Unknown             | 18        | 7.63%   |
| G.Skill             | 8         | 3.39%   |
| Apacer              | 4         | 1.69%   |
| A-DATA Technology   | 4         | 1.69%   |
| Transcend           | 3         | 1.27%   |
| Timetec             | 3         | 1.27%   |
| Team                | 3         | 1.27%   |
| GeIL                | 3         | 1.27%   |
| Unknown             | 3         | 1.27%   |
| Unknown (ABCD)      | 2         | 0.85%   |
| Ramaxel Technology  | 2         | 0.85%   |
| Patriot             | 2         | 0.85%   |
| Elpida              | 2         | 0.85%   |
| Vasekey             | 1         | 0.42%   |
| Smart Modular       | 1         | 0.42%   |
| Silicon Power       | 1         | 0.42%   |
| PNY                 | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| Kingmax             | 1         | 0.42%   |
| Kimtigo             | 1         | 0.42%   |
| Innodisk            | 1         | 0.42%   |
| Hewlett-Packard     | 1         | 0.42%   |
| Heoriady            | 1         | 0.42%   |
| ASint Technology    | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 2.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 1.22%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 3         | 1.22%   |
| Unknown                                                        | 3         | 1.22%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 2         | 0.82%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2         | 0.82%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                    | 2         | 0.82%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 2         | 0.82%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 2         | 0.82%   |
| GeIL RAM CL19-19-19 D4-2666 8GB DIMM DDR4 2667MT/s             | 2         | 0.82%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s           | 2         | 0.82%   |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                      | 2         | 0.82%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 2         | 0.82%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s        | 2         | 0.82%   |
| A-DATA RAM Module 4GB DIMM DDR4 1866MT/s                       | 2         | 0.82%   |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8GB 1600MT/s                                | 1         | 0.41%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1         | 0.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1         | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                        | 1         | 0.41%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 117       | 56.52%  |
| DDR4    | 71        | 34.3%   |
| Unknown | 9         | 4.35%   |
| LPDDR3  | 4         | 1.93%   |
| LPDDR4  | 3         | 1.45%   |
| DDR     | 2         | 0.97%   |
| DDR2    | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 112       | 53.85%  |
| SODIMM       | 82        | 39.42%  |
| Unknown      | 6         | 2.88%   |
| Chip         | 4         | 1.92%   |
| Row Of Chips | 3         | 1.44%   |
| RIMM         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 86        | 39.45%  |
| 4096  | 77        | 35.32%  |
| 2048  | 23        | 10.55%  |
| 16384 | 22        | 10.09%  |
| 32768 | 7         | 3.21%   |
| 1024  | 3         | 1.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 79        | 36.74%  |
| 1333  | 37        | 17.21%  |
| 2400  | 22        | 10.23%  |
| 2667  | 21        | 9.77%   |
| 2133  | 20        | 9.3%    |
| 3200  | 7         | 3.26%   |
| 1867  | 7         | 3.26%   |
| 1066  | 5         | 2.33%   |
| 800   | 5         | 2.33%   |
| 3600  | 2         | 0.93%   |
| 2666  | 2         | 0.93%   |
| 1866  | 2         | 0.93%   |
| 59392 | 1         | 0.47%   |
| 4267  | 1         | 0.47%   |
| 3000  | 1         | 0.47%   |
| 1067  | 1         | 0.47%   |
| 667   | 1         | 0.47%   |
| 400   | 1         | 0.47%   |

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
| Chicony Electronics           | 9         | 33.33%  |
| Bison Electronics             | 4         | 14.81%  |
| IMC Networks                  | 3         | 11.11%  |
| Apple                         | 3         | 11.11%  |
| Sunplus Innovation Technology | 2         | 7.41%   |
| Microdia                      | 2         | 7.41%   |
| Z-Star Microelectronics       | 1         | 3.7%    |
| Suyin                         | 1         | 3.7%    |
| Luxvisions Innotech Limited   | 1         | 3.7%    |
| Logitech                      | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 17.86%  |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 10.71%  |
| IMC Networks Integrated Webcam                      | 2         | 7.14%   |
| Bison Integrated Camera                             | 2         | 7.14%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 3.57%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 3.57%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 3.57%   |
| Sunplus HD WebCam                                   | 1         | 3.57%   |
| Microdia REDRAGON Live Camera Audio                 | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.57%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 3.57%   |
| IMC Networks EasyCamera                             | 1         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - 3M                     | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 3.57%   |
| Chicony Lenovo Integrated Camera                    | 1         | 3.57%   |
| Bison Lenovo Integrated Webcam                      | 1         | 3.57%   |
| Bison Lenovo EasyCamera                             | 1         | 3.57%   |

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
| Shenzhen Goodix Fingerprint Reader                     | 1         | 11.11%  |

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
| 1     | 98        | 42.79%  |
| 0     | 67        | 29.26%  |
| 2     | 37        | 16.16%  |
| 3     | 21        | 9.17%   |
| 4     | 3         | 1.31%   |
| 5     | 2         | 0.87%   |
| 6     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 145       | 61.44%  |
| Bluetooth                | 27        | 11.44%  |
| Net/wireless             | 20        | 8.47%   |
| Card reader              | 15        | 6.36%   |
| Firewire controller      | 7         | 2.97%   |
| Fingerprint reader       | 6         | 2.54%   |
| Sound                    | 5         | 2.12%   |
| Network                  | 3         | 1.27%   |
| Graphics card            | 3         | 1.27%   |
| Net/ethernet             | 2         | 0.85%   |
| Dvb card                 | 2         | 0.85%   |
| Storage/raid             | 1         | 0.42%   |

