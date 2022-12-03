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

Total: 189

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Dell          | 0NC2VH A01                  | [21e1806645](https://bsd-hardware.info/?probe=21e1806645) | Jan 29, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [50b7edb511](https://bsd-hardware.info/?probe=50b7edb511) | Jan 29, 2022 |
| Dell          | 0NC2VH A01                  | [8587a16b51](https://bsd-hardware.info/?probe=8587a16b51) | Jan 29, 2022 |
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
| Dell          | 0NC2VH A01                  | [1f3657128e](https://bsd-hardware.info/?probe=1f3657128e) | Oct 30, 2021 |
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
| Dell          | 0NC2VH A01                  | [8125c50b2a](https://bsd-hardware.info/?probe=8125c50b2a) | Sep 11, 2021 |
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
| Dell          | 0NC2VH A01                  | [d713cecb20](https://bsd-hardware.info/?probe=d713cecb20) | Jul 10, 2021 |
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
| Dell          | 0NC2VH A01                  | [bb7f6e1db9](https://bsd-hardware.info/?probe=bb7f6e1db9) | Mar 10, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [c88b021c05](https://bsd-hardware.info/?probe=c88b021c05) | Mar 09, 2021 |
| Gigabyte      | H270N-WIFI-CF               | [7201058b50](https://bsd-hardware.info/?probe=7201058b50) | Mar 08, 2021 |
| Unknown       | Unknown                     | [635419dc18](https://bsd-hardware.info/?probe=635419dc18) | Mar 07, 2021 |
| ASUSTek       | X99-E-10G WS                | [4e73497945](https://bsd-hardware.info/?probe=4e73497945) | Mar 06, 2021 |
| PC Engines    | apu4                        | [2a3c8a81d5](https://bsd-hardware.info/?probe=2a3c8a81d5) | Mar 02, 2021 |
| Dell          | 0NC2VH A01                  | [ec20bc7cea](https://bsd-hardware.info/?probe=ec20bc7cea) | Feb 28, 2021 |
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
| Dell          | 0NC2VH A01                  | [4afdd92b10](https://bsd-hardware.info/?probe=4afdd92b10) | Jan 20, 2021 |
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


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OPNsense 22.1       | 8        | 5.13%   |
| OPNsense 22.7.6     | 6        | 3.85%   |
| OPNsense 22.7.4     | 5        | 3.21%   |
| OPNsense 21.7.7     | 5        | 3.21%   |
| OPNsense 21.7.2     | 5        | 3.21%   |
| OPNsense 21.1.4     | 5        | 3.21%   |
| OPNsense 20.7.8     | 5        | 3.21%   |
| OPNsense 22.1.6     | 4        | 2.56%   |
| OPNsense 22.1.4     | 4        | 2.56%   |
| OPNsense 22.1.10    | 4        | 2.56%   |
| OPNsense 21.7.3     | 4        | 2.56%   |
| OPNsense 21.1.5     | 4        | 2.56%   |
| OPNsense 21.1.2     | 4        | 2.56%   |
| OPNsense 21.1       | 4        | 2.56%   |
| helloSystem 0.7.0   | 4        | 2.56%   |
| helloSystem 0.5.0   | 4        | 2.56%   |
| OPNsense 22.7.5     | 3        | 1.92%   |
| OPNsense 22.7.3     | 3        | 1.92%   |
| OPNsense 21.7.4     | 3        | 1.92%   |
| OPNsense 21.7.1     | 3        | 1.92%   |
| OPNsense 21.1.8     | 3        | 1.92%   |
| OPNsense 21.1.6     | 3        | 1.92%   |
| OPNsense 21.1.3     | 3        | 1.92%   |
| OPNsense 21.1.1     | 3        | 1.92%   |
| helloSystem 0.6.0   | 3        | 1.92%   |
| FreeBSD 12.1-p10    | 3        | 1.92%   |
| OPNsense 22.7       | 2        | 1.28%   |
| OPNsense 22.1.8     | 2        | 1.28%   |
| OPNsense 21.7.5     | 2        | 1.28%   |
| GhostBSD 20.04.02   | 2        | 1.28%   |
| FreeBSD 13.1        | 2        | 1.28%   |
| FreeBSD 13.0-STABLE | 2        | 1.28%   |
| FreeBSD 13.0-p4     | 2        | 1.28%   |
| FreeBSD 12.2        | 2        | 1.28%   |
| XigmaNAS 12.3-p6    | 1        | 0.64%   |
| TrueNAS 13.1-p2     | 1        | 0.64%   |
| TrueNAS 12.2-p9     | 1        | 0.64%   |
| TrueNAS 12.2-p3     | 1        | 0.64%   |
| TrueNAS 12.2-p14    | 1        | 0.64%   |
| TrueNAS 12.2-p10    | 1        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 76       | 63.87%  |
| FreeBSD     | 18       | 15.13%  |
| helloSystem | 11       | 9.24%   |
| TrueNAS     | 5        | 4.2%    |
| OpenBSD     | 2        | 1.68%   |
| GhostBSD    | 2        | 1.68%   |
| FreeNAS     | 2        | 1.68%   |
| XigmaNAS    | 1        | 0.84%   |
| NomadBSD    | 1        | 0.84%   |
| NetBSD      | 1        | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 118      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 92       | 76.67%  |
| helloDesktop | 13       | 10.83%  |
| KDE5         | 4        | 3.33%   |
| XFCE         | 3        | 2.5%    |
| TWM          | 2        | 1.67%   |
| GNOME        | 2        | 1.67%   |
| Openbox      | 1        | 0.83%   |
| MATE         | 1        | 0.83%   |
| Lumina       | 1        | 0.83%   |
| i3           | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 96       | 81.36%  |
| X11     | 21       | 17.8%   |
| Wayland | 1        | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 97       | 82.2%   |
| SLiM    | 13       | 11.02%  |
| XDM     | 3        | 2.54%   |
| LightDM | 3        | 2.54%   |
| SDDM    | 2        | 1.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 84       | 70.59%  |
| en_US   | 19       | 15.97%  |
| C       | 9        | 7.56%   |
| en_AU   | 7        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 91       | 77.12%  |
| BIOS | 27       | 22.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 68       | 57.14%  |
| Zfs    | 47       | 39.5%   |
| Ffs    | 2        | 1.68%   |
| Cd9660 | 2        | 1.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 107      | 90.68%  |
| MBR     | 9        | 7.63%   |
| BSD     | 1        | 0.85%   |
| Unknown | 1        | 0.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Hewlett-Packard            | 14       | 11.86%  |
| Dell                       | 14       | 11.86%  |
| Protectli                  | 13       | 11.02%  |
| ASUSTek Computer           | 11       | 9.32%   |
| Unknown                    | 11       | 9.32%   |
| ASRock                     | 9        | 7.63%   |
| Gigabyte Technology        | 8        | 6.78%   |
| Lenovo                     | 7        | 5.93%   |
| MSI                        | 4        | 3.39%   |
| Intel                      | 4        | 3.39%   |
| Shuttle                    | 2        | 1.69%   |
| PC Engines                 | 2        | 1.69%   |
| MW                         | 2        | 1.69%   |
| Acer                       | 2        | 1.69%   |
| Yanling                    | 1        | 0.85%   |
| Unknown                    | 1        | 0.85%   |
| ShenZhen MinWin Technology | 1        | 0.85%   |
| SeeedStudio                | 1        | 0.85%   |
| Radxa                      | 1        | 0.85%   |
| Inventec                   | 1        | 0.85%   |
| IBM                        | 1        | 0.85%   |
| HARDKERNEL                 | 1        | 0.85%   |
| Gateway                    | 1        | 0.85%   |
| Foxconn                    | 1        | 0.85%   |
| Cisco                      | 1        | 0.85%   |
| AZW                        | 1        | 0.85%   |
| AOpen                      | 1        | 0.85%   |
| ADI Engineering            | 1        | 0.85%   |
| AAEON                      | 1        | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 12       | 10.17%  |
| Protectli FW4B                     | 8        | 6.78%   |
| HP ProLiant MicroServer            | 4        | 3.39%   |
| Dell OptiPlex 9020                 | 3        | 2.54%   |
| Protectli VP2410                   | 2        | 1.69%   |
| Protectli FW2B                     | 2        | 1.69%   |
| MW GMLK-2_5G4L                     | 2        | 1.69%   |
| Intel Q3XXG4-P V1.0                | 2        | 1.69%   |
| HP ProLiant MicroServer Gen8       | 2        | 1.69%   |
| Dell OptiPlex 3010                 | 2        | 1.69%   |
| ASUS All Series                    | 2        | 1.69%   |
| Yanling YL-KBR6L                   | 1        | 0.85%   |
| Shuttle DS81D                      | 1        | 0.85%   |
| Shuttle DH370                      | 1        | 0.85%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 1        | 0.85%   |
| SeeedStudio ODYSSEY-X86J4125       | 1        | 0.85%   |
| Radxa ROCK Pi X                    | 1        | 0.85%   |
| Protectli FW6                      | 1        | 0.85%   |
| PC Engines apu4                    | 1        | 0.85%   |
| PC Engines apu1                    | 1        | 0.85%   |
| MSI Pro 3130 Small Form Factor PC  | 1        | 0.85%   |
| MSI MS-7C95                        | 1        | 0.85%   |
| MSI MS-7C94                        | 1        | 0.85%   |
| MSI CML-U PRO Cubi 5 (MS-B183)     | 1        | 0.85%   |
| Lenovo ThinkCentre M93p 10AAS3UM00 | 1        | 0.85%   |
| Lenovo ThinkCentre M92p 3238CE1    | 1        | 0.85%   |
| Lenovo ThinkCentre M73 10AY009MAU  | 1        | 0.85%   |
| Lenovo ThinkCentre M73 10AXS01800  | 1        | 0.85%   |
| Lenovo ThinkCentre M700 10HY002XAU | 1        | 0.85%   |
| Lenovo ThinkCentre M58 7360BB6     | 1        | 0.85%   |
| Lenovo IdeaPad 5 15ITL05 82FG      | 1        | 0.85%   |
| Inventec D CLASS                   | 1        | 0.85%   |
| Intel NCB-4210WG                   | 1        | 0.85%   |
| Intel DN2820FYK H24582-201         | 1        | 0.85%   |
| IBM 9210MML                        | 1        | 0.85%   |
| HP Z400 Workstation                | 1        | 0.85%   |
| HP Z240 SFF Workstation            | 1        | 0.85%   |
| HP ProLiant ML150 G6               | 1        | 0.85%   |
| HP ProLiant ML10 v2                | 1        | 0.85%   |
| HP prodesk 400 g2 sff business pc  | 1        | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 12       | 10.17%  |
| Unknown                        | 12       | 10.17%  |
| Protectli FW4B                 | 8        | 6.78%   |
| HP ProLiant                    | 8        | 6.78%   |
| Lenovo ThinkCentre             | 6        | 5.08%   |
| HP EliteDesk                   | 3        | 2.54%   |
| ASUS ROG                       | 3        | 2.54%   |
| Protectli VP2410               | 2        | 1.69%   |
| Protectli FW2B                 | 2        | 1.69%   |
| MW GMLK-2                      | 2        | 1.69%   |
| Intel Q3XXG4-P                 | 2        | 1.69%   |
| ASUS PRIME                     | 2        | 1.69%   |
| ASUS All                       | 2        | 1.69%   |
| ASRock X370                    | 2        | 1.69%   |
| Acer Veriton                   | 2        | 1.69%   |
| Yanling YL-KBR6L               | 1        | 0.85%   |
| Shuttle DS81D                  | 1        | 0.85%   |
| Shuttle DH370                  | 1        | 0.85%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.85%   |
| SeeedStudio ODYSSEY-X86J4125   | 1        | 0.85%   |
| Radxa ROCK                     | 1        | 0.85%   |
| Protectli FW6                  | 1        | 0.85%   |
| PC Engines apu4                | 1        | 0.85%   |
| PC Engines apu1                | 1        | 0.85%   |
| MSI Pro                        | 1        | 0.85%   |
| MSI MS-7C95                    | 1        | 0.85%   |
| MSI MS-7C94                    | 1        | 0.85%   |
| MSI CML-U                      | 1        | 0.85%   |
| Lenovo IdeaPad                 | 1        | 0.85%   |
| Inventec D                     | 1        | 0.85%   |
| Intel NCB-4210WG               | 1        | 0.85%   |
| Intel DN2820FYK                | 1        | 0.85%   |
| IBM 9210MML                    | 1        | 0.85%   |
| HP Z400                        | 1        | 0.85%   |
| HP Z240                        | 1        | 0.85%   |
| HP prodesk                     | 1        | 0.85%   |
| HARDKERNEL ODROID-H2           | 1        | 0.85%   |
| Gigabyte Z87N-WIFI             | 1        | 0.85%   |
| Gigabyte Z77N-WIFI             | 1        | 0.85%   |
| Gigabyte Z68MA-D2H-B3          | 1        | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 15       | 12.71%  |
| 2013    | 14       | 11.86%  |
| 2020    | 12       | 10.17%  |
| 2021    | 11       | 9.32%   |
| 2018    | 11       | 9.32%   |
| 2016    | 10       | 8.47%   |
| 2011    | 8        | 6.78%   |
| 2014    | 7        | 5.93%   |
| 2017    | 6        | 5.08%   |
| 2015    | 5        | 4.24%   |
| 2012    | 5        | 4.24%   |
| 2022    | 4        | 3.39%   |
| 2009    | 4        | 3.39%   |
| 2010    | 2        | 1.69%   |
| Unknown | 2        | 1.69%   |
| 2008    | 1        | 0.85%   |
| 2006    | 1        | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 118      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 111      | 94.07%  |
| Yes  | 7        | 5.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 58       | 47.93%  |
| 16.01-24.0  | 26       | 21.49%  |
| 4.01-8.0    | 20       | 16.53%  |
| 32.01-64.0  | 8        | 6.61%   |
| 24.01-32.0  | 3        | 2.48%   |
| 64.01-256.0 | 3        | 2.48%   |
| 2.01-3.0    | 2        | 1.65%   |
| 0.51-1.0    | 1        | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 67       | 54.47%  |
| 0.51-1.0   | 32       | 26.02%  |
| 1.01-2.0   | 9        | 7.32%   |
| 4.01-8.0   | 5        | 4.07%   |
| 3.01-4.0   | 2        | 1.63%   |
| 2.01-3.0   | 2        | 1.63%   |
| 16.01-24.0 | 2        | 1.63%   |
| 8.01-16.0  | 2        | 1.63%   |
| 32.01-64.0 | 1        | 0.81%   |
| Unknown    | 1        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 65.83%  |
| 2      | 14       | 11.67%  |
| 3      | 9        | 7.5%    |
| 0      | 9        | 7.5%    |
| 4      | 4        | 3.33%   |
| 5      | 2        | 1.67%   |
| 10     | 1        | 0.83%   |
| 7      | 1        | 0.83%   |
| 6      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 81.36%  |
| Yes       | 22       | 18.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 98.31%  |
| No        | 2        | 1.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 79.83%  |
| Yes       | 24       | 20.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 105      | 88.24%  |
| Yes       | 14       | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 118      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 33       | 25.98%  |
| Melbourne      | 20       | 15.75%  |
| Perth          | 15       | 11.81%  |
| Brisbane       | 14       | 11.02%  |
| Adelaide       | 6        | 4.72%   |
| Marrickville   | 2        | 1.57%   |
| Ipswich        | 2        | 1.57%   |
| Hobart         | 2        | 1.57%   |
| Canberra       | 2        | 1.57%   |
| Wollongong     | 1        | 0.79%   |
| Wheelers Hill  | 1        | 0.79%   |
| Wallan         | 1        | 0.79%   |
| Townsville     | 1        | 0.79%   |
| Southport      | 1        | 0.79%   |
| Shell Cove     | 1        | 0.79%   |
| Ryde           | 1        | 0.79%   |
| Rosanna        | 1        | 0.79%   |
| Ringwood       | 1        | 0.79%   |
| North Shore    | 1        | 0.79%   |
| Noble Park     | 1        | 0.79%   |
| Mount Waverley | 1        | 0.79%   |
| Mooroolbark    | 1        | 0.79%   |
| Malvern        | 1        | 0.79%   |
| Kurunjang      | 1        | 0.79%   |
| Kellyville     | 1        | 0.79%   |
| Gold Coast     | 1        | 0.79%   |
| Glen Iris      | 1        | 0.79%   |
| Geelong        | 1        | 0.79%   |
| Engadine       | 1        | 0.79%   |
| East Malvern   | 1        | 0.79%   |
| Dowerin        | 1        | 0.79%   |
| Dandenong      | 1        | 0.79%   |
| Corio          | 1        | 0.79%   |
| Brunswick      | 1        | 0.79%   |
| Blackburn      | 1        | 0.79%   |
| Bayswater      | 1        | 0.79%   |
| Balwyn North   | 1        | 0.79%   |
| Ashfield       | 1        | 0.79%   |
| Ascot Vale     | 1        | 0.79%   |
| Unknown        | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 15.86%  |
| Samsung Electronics | 22       | 32     | 15.17%  |
| WDC                 | 20       | 55     | 13.79%  |
| Kingston            | 9        | 16     | 6.21%   |
| Crucial             | 8        | 8      | 5.52%   |
| Intel               | 7        | 13     | 4.83%   |
| Hoodisk             | 6        | 13     | 4.14%   |
| Toshiba             | 5        | 9      | 3.45%   |
| SanDisk             | 5        | 7      | 3.45%   |
| Protectli           | 3        | 3      | 2.07%   |
| Hewlett-Packard     | 3        | 6      | 2.07%   |
| A-DATA Technology   | 3        | 8      | 2.07%   |
| Phison              | 2        | 2      | 1.38%   |
| Micron Technology   | 2        | 3      | 1.38%   |
| KingDian            | 2        | 2      | 1.38%   |
| Gigabyte Technology | 2        | 2      | 1.38%   |
| Dogfish             | 2        | 2      | 1.38%   |
| China               | 2        | 2      | 1.38%   |
| BIWIN               | 2        | 2      | 1.38%   |
| XUNZHE              | 1        | 1      | 0.69%   |
| Vaseky              | 1        | 3      | 0.69%   |
| Transcend           | 1        | 1      | 0.69%   |
| SPCC                | 1        | 5      | 0.69%   |
| Silicon Motion      | 1        | 1      | 0.69%   |
| ShiJi               | 1        | 1      | 0.69%   |
| PNY                 | 1        | 1      | 0.69%   |
| Plextor             | 1        | 2      | 0.69%   |
| Patriot             | 1        | 1      | 0.69%   |
| OCZ                 | 1        | 2      | 0.69%   |
| NVMe                | 1        | 1      | 0.69%   |
| Maxtor              | 1        | 1      | 0.69%   |
| LITEONIT            | 1        | 1      | 0.69%   |
| KingSpec            | 1        | 1      | 0.69%   |
| Hitachi             | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| Fordisk             | 1        | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hoodisk SSD 128GB                | 6        | 3.7%    |
| Kingston SA400S37120G 120GB      | 3        | 1.85%   |
| Crucial CT250P2SSD8 250GB        | 3        | 1.85%   |
| Crucial CT250MX500SSD1 250GB     | 3        | 1.85%   |
| WDC WDS250G2B0A-00SM50 250GB     | 2        | 1.23%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 1.23%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 1.23%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 1.23%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 1.23%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.23%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.23%   |
| Samsung SSD 840 EVO 120GB        | 2        | 1.23%   |
| Samsung MZ7LN128HCHP-000H1 128GB | 2        | 1.23%   |
| Protectli 120GB mSATA            | 2        | 1.23%   |
| Kingston SA400S37480G 480GB      | 2        | 1.23%   |
| XUNZHE MSATA 128GB               | 1        | 0.62%   |
| WDC WDS500G1R0B-68A4Z0 500GB     | 1        | 0.62%   |
| WDC WDS250G2B0C-00PXH0 250GB     | 1        | 0.62%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1        | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB     | 1        | 0.62%   |
| WDC WD80EFAX-68KNBN0 8TB         | 1        | 0.62%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.62%   |
| WDC WD5000BPKT-00PK4T0 500GB     | 1        | 0.62%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.62%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.62%   |
| WDC WD4000AAKS-00TMA0 400GB      | 1        | 0.62%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.62%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.62%   |
| WDC WD20EARX-008FB0 2TB          | 1        | 0.62%   |
| WDC WD20EARS-00MVWB0 2TB         | 1        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.62%   |
| WDC WD10EURX-63UY4Y0 1TB         | 1        | 0.62%   |
| WDC WD10EARX-00N0YB0 1TB         | 1        | 0.62%   |
| WDC WD10EADS-00P8B0 1TB          | 1        | 0.62%   |
| Vaseky V850-64G                  | 1        | 0.62%   |
| Transcend TS16EPTMM1600L 16GB    | 1        | 0.62%   |
| Toshiba THNSNJ128GMCU 128GB      | 1        | 0.62%   |
| Toshiba MQ04UBF100 1TB           | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 43.4%   |
| WDC                 | 16       | 48     | 30.19%  |
| Toshiba             | 4        | 6      | 7.55%   |
| Samsung Electronics | 3        | 5      | 5.66%   |
| Hewlett-Packard     | 3        | 6      | 5.66%   |
| NVMe                | 1        | 1      | 1.89%   |
| Maxtor              | 1        | 1      | 1.89%   |
| Hitachi             | 1        | 1      | 1.89%   |
| HGST                | 1        | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 23     | 20.27%  |
| Kingston            | 9        | 16     | 12.16%  |
| Intel               | 6        | 12     | 8.11%   |
| Hoodisk             | 6        | 13     | 8.11%   |
| SanDisk             | 5        | 7      | 6.76%   |
| WDC                 | 4        | 6      | 5.41%   |
| Crucial             | 4        | 4      | 5.41%   |
| Protectli           | 3        | 3      | 4.05%   |
| Micron Technology   | 2        | 3      | 2.7%    |
| KingDian            | 2        | 2      | 2.7%    |
| Dogfish             | 2        | 2      | 2.7%    |
| China               | 2        | 2      | 2.7%    |
| XUNZHE              | 1        | 1      | 1.35%   |
| Vaseky              | 1        | 3      | 1.35%   |
| Transcend           | 1        | 1      | 1.35%   |
| Toshiba             | 1        | 3      | 1.35%   |
| ShiJi               | 1        | 1      | 1.35%   |
| Plextor             | 1        | 2      | 1.35%   |
| Phison              | 1        | 1      | 1.35%   |
| Patriot             | 1        | 1      | 1.35%   |
| OCZ                 | 1        | 2      | 1.35%   |
| LITEONIT            | 1        | 1      | 1.35%   |
| KingSpec            | 1        | 1      | 1.35%   |
| Fordisk             | 1        | 1      | 1.35%   |
| BIWIN               | 1        | 1      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 70       | 113    | 54.26%  |
| HDD  | 41       | 99     | 31.78%  |
| NVMe | 18       | 28     | 13.95%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 100      | 212    | 84.75%  |
| NVMe | 18       | 28     | 15.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 84       | 140    | 71.79%  |
| 0.51-1.0   | 14       | 23     | 11.97%  |
| 1.01-2.0   | 10       | 25     | 8.55%   |
| 3.01-4.0   | 4        | 9      | 3.42%   |
| 2.01-3.0   | 2        | 8      | 1.71%   |
| 4.01-10.0  | 2        | 5      | 1.71%   |
| 10.01-20.0 | 1        | 2      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 54       | 45.76%  |
| 251-500    | 16       | 13.56%  |
| 1-20       | 16       | 13.56%  |
| 51-100     | 12       | 10.17%  |
| 501-1000   | 10       | 8.47%   |
| 21-50      | 6        | 5.08%   |
| 2001-3000  | 2        | 1.69%   |
| 1001-2000  | 2        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 112      | 91.06%  |
| 21-50     | 8        | 6.5%    |
| 101-250   | 1        | 0.81%   |
| 1001-2000 | 1        | 0.81%   |
| 51-100    | 1        | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB              | 1        | 1      | 6.67%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1        | 2      | 6.67%   |
| WDC WD20EARX-008FB0 2TB                   | 1        | 3      | 6.67%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1        | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB           | 1        | 1      | 6.67%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 6.67%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 6.67%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 1      | 6.67%   |
| Seagate ST1000DM003-1CH162 1TB            | 1        | 1      | 6.67%   |
| SanDisk SDSSDA240G 240GB                  | 1        | 1      | 6.67%   |
| Samsung Electronics HM500LI 500GB         | 1        | 2      | 6.67%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1        | 1      | 6.67%   |
| Hitachi HDS721010KLA330 1TB               | 1        | 1      | 6.67%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1        | 1      | 6.67%   |
| BIWIN SSD 8GB                             | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 35.71%  |
| WDC                 | 3        | 7      | 21.43%  |
| SanDisk             | 1        | 1      | 7.14%   |
| Samsung Electronics | 1        | 2      | 7.14%   |
| Micron Technology   | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |
| Hewlett-Packard     | 1        | 1      | 7.14%   |
| BIWIN               | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 50%     |
| WDC                 | 2        | 6      | 20%     |
| Samsung Electronics | 1        | 2      | 10%     |
| Hitachi             | 1        | 1      | 10%     |
| Hewlett-Packard     | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 15     | 71.43%  |
| SSD  | 4        | 4      | 28.57%  |

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
| Works    | 100      | 220    | 86.96%  |
| Malfunc  | 14       | 19     | 12.17%  |
| Detected | 1        | 1      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 98       | 66.67%  |
| AMD                       | 20       | 13.61%  |
| Samsung Electronics       | 5        | 3.4%    |
| Phison Electronics        | 5        | 3.4%    |
| Micron/Crucial Technology | 4        | 2.72%   |
| Silicon Motion            | 2        | 1.36%   |
| Broadcom / LSI            | 2        | 1.36%   |
| ASMedia Technology        | 2        | 1.36%   |
| Silicon Image             | 1        | 0.68%   |
| SanDisk                   | 1        | 0.68%   |
| Realtek Semiconductor     | 1        | 0.68%   |
| QLogic                    | 1        | 0.68%   |
| Marvell Technology Group  | 1        | 0.68%   |
| JMicron Technology        | 1        | 0.68%   |
| Hewlett-Packard           | 1        | 0.68%   |
| ADATA Technology          | 1        | 0.68%   |
| Adaptec                   | 1        | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 7.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12       | 7.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 6.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 5.39%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 4.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 4.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 4.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 2.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.4%    |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 1.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.8%    |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.2%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.2%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2        | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.2%    |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.2%    |
| AMD FCH SATA Controller D                                                               | 2        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.2%    |
| Unknown                                                                                 | 2        | 1.2%    |
| Silicon Image AAR-1220SA Serial ATA HostRAID Controller                                 | 1        | 0.6%    |
| SanDisk unknown                                                                         | 1        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.6%    |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.6%    |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                             | 1        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 110      | 70.97%  |
| NVMe | 19       | 12.26%  |
| IDE  | 16       | 10.32%  |
| RAID | 6        | 3.87%   |
| SAS  | 2        | 1.29%   |
| SCSI | 2        | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 98       | 83.05%  |
| AMD    | 20       | 16.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 10       | 8.4%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 6        | 5.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.52%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 2.52%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2        | 1.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.68%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 1.68%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 1.68%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 2        | 1.68%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.68%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 2        | 1.68%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 1.68%   |
| AMD Turion II Neo N40L Dual-Core Processor  | 2        | 1.68%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.68%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.68%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.84%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.84%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.84%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.84%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.84%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.84%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.84%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.84%   |
| Intel Xeon                                  | 1        | 0.84%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.84%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.84%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1        | 0.84%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.84%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.84%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.84%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.84%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.84%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.84%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 0.84%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1        | 0.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.84%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 32       | 26.89%  |
| Intel Core i5           | 25       | 21.01%  |
| Intel Xeon              | 11       | 9.24%   |
| Intel Core i3           | 11       | 9.24%   |
| Intel Core i7           | 6        | 5.04%   |
| Intel Pentium           | 4        | 3.36%   |
| AMD Turion II Neo       | 4        | 3.36%   |
| AMD Ryzen 5             | 4        | 3.36%   |
| Intel Core 2 Quad       | 3        | 2.52%   |
| AMD Ryzen 3             | 3        | 2.52%   |
| AMD FX                  | 3        | 2.52%   |
| Other                   | 2        | 1.68%   |
| Intel Atom              | 2        | 1.68%   |
| AMD G                   | 2        | 1.68%   |
| Intel Pentium Silver    | 1        | 0.84%   |
| Intel Pentium Dual-Core | 1        | 0.84%   |
| Intel Pentium 4         | 1        | 0.84%   |
| AMD Ryzen 9             | 1        | 0.84%   |
| AMD GX                  | 1        | 0.84%   |
| AMD E2                  | 1        | 0.84%   |
| AMD Athlon              | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 64       | 53.78%  |
| 2       | 33       | 27.73%  |
| 8       | 10       | 8.4%    |
| 6       | 5        | 4.2%    |
| 12      | 3        | 2.52%   |
| Unknown | 3        | 2.52%   |
| 32      | 1        | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 98.31%  |
| 2      | 2        | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 88       | 73.95%  |
| 2       | 28       | 23.53%  |
| Unknown | 3        | 2.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 19       | 16.1%   |
| Haswell       | 14       | 11.86%  |
| KabyLake      | 11       | 9.32%   |
| IvyBridge     | 9        | 7.63%   |
| Skylake       | 8        | 6.78%   |
| SandyBridge   | 8        | 6.78%   |
| Goldmont plus | 7        | 5.93%   |
| Nehalem       | 4        | 3.39%   |
| K10           | 4        | 3.39%   |
| Unknown       | 4        | 3.39%   |
| Zen 3         | 3        | 2.54%   |
| Westmere      | 3        | 2.54%   |
| Piledriver    | 3        | 2.54%   |
| Penryn        | 3        | 2.54%   |
| Broadwell     | 3        | 2.54%   |
| Bobcat        | 3        | 2.54%   |
| Zen 2         | 2        | 1.69%   |
| Zen           | 2        | 1.69%   |
| Zen+          | 1        | 0.85%   |
| TigerLake     | 1        | 0.85%   |
| Puma          | 1        | 0.85%   |
| NetBurst      | 1        | 0.85%   |
| Jaguar        | 1        | 0.85%   |
| Goldmont      | 1        | 0.85%   |
| Core          | 1        | 0.85%   |
| CometLake     | 1        | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 78       | 66.67%  |
| AMD                        | 18       | 15.38%  |
| Nvidia                     | 14       | 11.97%  |
| Matrox Electronics Systems | 5        | 4.27%   |
| Tseng Labs                 | 1        | 0.85%   |
| ASPEED Technology          | 1        | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13       | 10.92%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 9.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 5.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 5.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 5.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 4.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 4.2%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4        | 3.36%   |
| Intel HD Graphics 530                                                                    | 3        | 2.52%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.68%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 1.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.68%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.68%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 1.68%   |
| Intel UHD Graphics 620                                                                   | 2        | 1.68%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 1.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.68%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.68%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 0.84%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.84%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.84%   |
| Nvidia GF100GL [Quadro 4000]                                                             | 1        | 0.84%   |
| Nvidia G92 [GeForce GT 330]                                                              | 1        | 0.84%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 0.84%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.84%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.84%   |
| Intel Iris Plus Graphics 650                                                             | 1        | 0.84%   |
| Intel HD Graphics P530                                                                   | 1        | 0.84%   |
| Intel HD Graphics 610                                                                    | 1        | 0.84%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.84%   |
| Intel HD Graphics 510                                                                    | 1        | 0.84%   |
| Intel HD Graphics 500                                                                    | 1        | 0.84%   |
| Intel HD Graphics                                                                        | 1        | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 72       | 60%     |
| 1 x AMD        | 17       | 14.17%  |
| 1 x Nvidia     | 12       | 10%     |
| Other          | 5        | 4.17%   |
| 1 x Matrox     | 5        | 4.17%   |
| 2 x Intel      | 3        | 2.5%    |
| Intel + Nvidia | 2        | 1.67%   |
| 2 x AMD        | 1        | 0.83%   |
| 1 x Tseng Labs | 1        | 0.83%   |
| Intel + AMD    | 1        | 0.83%   |
| 1 x ASPEED     | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 107      | 90.68%  |
| Proprietary | 6        | 5.08%   |
| Unknown     | 5        | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 107      | 89.92%  |
| 1.01-2.0   | 6        | 5.04%   |
| 0.51-1.0   | 3        | 2.52%   |
| 7.01-8.0   | 2        | 1.68%   |
| 3.01-4.0   | 1        | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 13.64%  |
| Samsung Electronics | 2        | 9.09%   |
| Philips             | 2        | 9.09%   |
| Hewlett-Packard     | 2        | 9.09%   |
| ASUSTek Computer    | 2        | 9.09%   |
| AOC                 | 2        | 9.09%   |
| Acer                | 2        | 9.09%   |
| ___                 | 1        | 4.55%   |
| ViewSonic           | 1        | 4.55%   |
| Toshiba             | 1        | 4.55%   |
| Goldstar            | 1        | 4.55%   |
| Compal              | 1        | 4.55%   |
| BenQ                | 1        | 4.55%   |
| AU Optronics        | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2        | 8.7%    |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 4.35%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1        | 4.35%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1        | 4.35%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1        | 4.35%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1        | 4.35%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 4.35%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 4.35%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1        | 4.35%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1        | 4.35%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1        | 4.35%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1        | 4.35%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1        | 4.35%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1        | 4.35%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1        | 4.35%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1        | 4.35%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch       | 1        | 4.35%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 4.35%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1        | 4.35%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1        | 4.35%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1        | 4.35%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 59.09%  |
| 2560x1440 (QHD)    | 4        | 18.18%  |
| 3840x1600          | 1        | 4.55%   |
| 2560x1080          | 1        | 4.55%   |
| 2048x1152          | 1        | 4.55%   |
| 1920x1200 (WUXGA)  | 1        | 4.55%   |
| 1680x1050 (WSXGA+) | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 27.27%  |
| 24      | 4        | 18.18%  |
| 23      | 3        | 13.64%  |
| 21      | 2        | 9.09%   |
| 47      | 1        | 4.55%   |
| 37      | 1        | 4.55%   |
| 31      | 1        | 4.55%   |
| 28      | 1        | 4.55%   |
| 22      | 1        | 4.55%   |
| 15      | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 59.09%  |
| 401-500     | 3        | 13.64%  |
| 601-700     | 2        | 9.09%   |
| 801-900     | 1        | 4.55%   |
| 301-350     | 1        | 4.55%   |
| 1001-1500   | 1        | 4.55%   |
| Unknown     | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 81.82%  |
| 21/9  | 2        | 9.09%   |
| 16/10 | 2        | 9.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 40.91%  |
| 301-350        | 6        | 27.27%  |
| 251-300        | 2        | 9.09%   |
| 501-1000       | 2        | 9.09%   |
| 351-500        | 1        | 4.55%   |
| 91-100         | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 54.55%  |
| 101-120 | 7        | 31.82%  |
| 1-50    | 1        | 4.55%   |
| 121-160 | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 96       | 81.36%  |
| 1     | 21       | 17.8%   |
| 2     | 1        | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 83       | 53.9%   |
| Realtek Semiconductor    | 44       | 28.57%  |
| Broadcom                 | 13       | 8.44%   |
| Qualcomm Atheros         | 4        | 2.6%    |
| U-Blox                   | 2        | 1.3%    |
| TP-Link                  | 1        | 0.65%   |
| Seeed Technology         | 1        | 0.65%   |
| Ralink Technology        | 1        | 0.65%   |
| Ralink                   | 1        | 0.65%   |
| Marvell Technology Group | 1        | 0.65%   |
| IMC Networks             | 1        | 0.65%   |
| D-Link System            | 1        | 0.65%   |
| Aquantia                 | 1        | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39       | 21.43%  |
| Intel I211 Gigabit Network Connection                                         | 23       | 12.64%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 4.95%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.3%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 3.3%    |
| Intel 82574L Gigabit Network Connection                                       | 5        | 2.75%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.65%   |
| Intel Wireless 7260                                                           | 3        | 1.65%   |
| Intel Ethernet Controller I226-V                                              | 3        | 1.65%   |
| Intel Ethernet Connection I217-V                                              | 3        | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.65%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.65%   |
| U-Blox [u-blox 7]                                                             | 2        | 1.1%    |
| Intel Wireless 8265 / 8275                                                    | 2        | 1.1%    |
| Intel Ethernet Controller I225-V                                              | 2        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.1%    |
| Intel Centrino Wireless-N 2230                                                | 2        | 1.1%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.1%    |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.1%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.1%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.55%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.55%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.55%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 13       | 52%     |
| Realtek Semiconductor | 5        | 20%     |
| Qualcomm Atheros      | 3        | 12%     |
| TP-Link               | 1        | 4%      |
| Ralink Technology     | 1        | 4%      |
| Ralink                | 1        | 4%      |
| IMC Networks          | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                            | 3        | 12%     |
| Intel Wireless 8265 / 8275                                     | 2        | 8%      |
| Intel Centrino Wireless-N 2230                                 | 2        | 8%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 4%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 4%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 4%      |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 4%      |
| Ralink RT5572 Wireless Adapter                                 | 1        | 4%      |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 4%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 4%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 4%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 4%      |
| Intel Wireless 8260                                            | 1        | 4%      |
| Intel Wireless 3165                                            | 1        | 4%      |
| Intel Wi-Fi 6 AX201                                            | 1        | 4%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 4%      |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 4%      |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 78       | 56.52%  |
| Realtek Semiconductor    | 42       | 30.43%  |
| Broadcom                 | 13       | 9.42%   |
| Qualcomm Atheros         | 2        | 1.45%   |
| Marvell Technology Group | 1        | 0.72%   |
| D-Link System            | 1        | 0.72%   |
| Aquantia                 | 1        | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 39       | 25.49%  |
| Intel I211 Gigabit Network Connection                                         | 23       | 15.03%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 5.88%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.92%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 3.92%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.27%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.61%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.96%   |
| Intel Ethernet Controller I226-V                                              | 3        | 1.96%   |
| Intel Ethernet Connection I217-V                                              | 3        | 1.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.96%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.96%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.31%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.31%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.31%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.31%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.31%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.65%   |
| Intel Ethernet Controller X550                                                | 1        | 0.65%   |
| Intel Ethernet Connection I354                                                | 1        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.65%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1        | 0.65%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.65%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.65%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.65%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.65%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.65%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 80.56%  |
| WiFi     | 24       | 16.67%  |
| Modem    | 3        | 2.08%   |
| Unknown  | 1        | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 115      | 92%     |
| WiFi     | 10       | 8%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 37       | 30.83%  |
| 1     | 27       | 22.5%   |
| 4     | 24       | 20%     |
| 3     | 14       | 11.67%  |
| 6     | 8        | 6.67%   |
| 5     | 7        | 5.83%   |
| 7     | 2        | 1.67%   |
| 9     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 82.79%  |
| Yes  | 21       | 17.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 78.57%  |
| Cambridge Silicon Radio | 2        | 14.29%  |
| Broadcom                | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 5        | 35.71%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.14%   |
| Intel AX201 Bluetooth                               | 1        | 7.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 80       | 72.07%  |
| AMD                | 16       | 14.41%  |
| Nvidia             | 12       | 10.81%  |
| Texas Instruments  | 1        | 0.9%    |
| Logitech           | 1        | 0.9%    |
| Focusrite-Novation | 1        | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13       | 9.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12       | 8.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9        | 6.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 5.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 5.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 3.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 3.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 3.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 2.94%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 2.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.21%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.47%   |
| Intel Jasper Lake HD Audio                                                                        | 2        | 1.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.47%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.47%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.47%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.47%   |
| Unknown                                                                                           | 2        | 1.47%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.74%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1        | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.74%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.74%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1        | 0.74%   |
| Logitech Headset H390                                                                             | 1        | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.74%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 21       | 16.28%  |
| Kingston            | 20       | 15.5%   |
| Unknown             | 15       | 11.63%  |
| SK hynix            | 13       | 10.08%  |
| Micron Technology   | 12       | 9.3%    |
| Corsair             | 11       | 8.53%   |
| Crucial             | 8        | 6.2%    |
| G.Skill             | 6        | 4.65%   |
| Unknown             | 3        | 2.33%   |
| Unknown (ABCD)      | 2        | 1.55%   |
| Transcend           | 2        | 1.55%   |
| Team                | 2        | 1.55%   |
| Apacer              | 2        | 1.55%   |
| Vasekey             | 1        | 0.78%   |
| Timetec             | 1        | 0.78%   |
| Smart Modular       | 1        | 0.78%   |
| Ramaxel Technology  | 1        | 0.78%   |
| PNY                 | 1        | 0.78%   |
| Patriot             | 1        | 0.78%   |
| Nanya Technology    | 1        | 0.78%   |
| Kingmax             | 1        | 0.78%   |
| Innodisk            | 1        | 0.78%   |
| Hewlett-Packard     | 1        | 0.78%   |
| GeIL                | 1        | 0.78%   |
| Elpida              | 1        | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 3        | 2.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3        | 2.22%   |
| Unknown                                                           | 3        | 2.22%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2        | 1.48%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 2        | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2        | 1.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2        | 1.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2        | 1.48%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 1.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2        | 1.48%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 1.48%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2        | 1.48%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2        | 1.48%   |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1        | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 0.74%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                           | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1        | 0.74%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1        | 0.74%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.74%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.74%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.74%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s               | 1        | 0.74%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.74%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.74%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.74%   |
| SK hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1        | 0.74%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s            | 1        | 0.74%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s              | 1        | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 63       | 56.25%  |
| DDR4    | 36       | 32.14%  |
| Unknown | 8        | 7.14%   |
| LPDDR4  | 2        | 1.79%   |
| DDR     | 2        | 1.79%   |
| DDR2    | 1        | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 78       | 70.27%  |
| SODIMM  | 28       | 25.23%  |
| Unknown | 4        | 3.6%    |
| RIMM    | 1        | 0.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 51       | 43.22%  |
| 4096  | 36       | 30.51%  |
| 2048  | 15       | 12.71%  |
| 16384 | 11       | 9.32%   |
| 1024  | 3        | 2.54%   |
| 32768 | 2        | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 43       | 37.07%  |
| 1333  | 24       | 20.69%  |
| 2400  | 13       | 11.21%  |
| 2133  | 11       | 9.48%   |
| 2667  | 8        | 6.9%    |
| 800   | 4        | 3.45%   |
| 1066  | 3        | 2.59%   |
| 3600  | 2        | 1.72%   |
| 3200  | 2        | 1.72%   |
| 2666  | 2        | 1.72%   |
| 59392 | 1        | 0.86%   |
| 3000  | 1        | 0.86%   |
| 1867  | 1        | 0.86%   |
| 400   | 1        | 0.86%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1        | 100%    |

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
| 1     | 59       | 49.58%  |
| 0     | 46       | 38.66%  |
| 2     | 9        | 7.56%   |
| 4     | 2        | 1.68%   |
| 3     | 2        | 1.68%   |
| 5     | 1        | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 65       | 73.86%  |
| Bluetooth                | 6        | 6.82%   |
| Net/wireless             | 4        | 4.55%   |
| Sound                    | 3        | 3.41%   |
| Firewire controller      | 3        | 3.41%   |
| Card reader              | 3        | 3.41%   |
| Network                  | 2        | 2.27%   |
| Storage/raid             | 1        | 1.14%   |
| Dvb card                 | 1        | 1.14%   |

