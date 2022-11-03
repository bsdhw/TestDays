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

Total: 184

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OPNsense 22.1       | 8        | 5.26%   |
| OPNsense 22.7.6     | 6        | 3.95%   |
| OPNsense 22.7.4     | 5        | 3.29%   |
| OPNsense 21.7.7     | 5        | 3.29%   |
| OPNsense 21.7.2     | 5        | 3.29%   |
| OPNsense 21.1.4     | 5        | 3.29%   |
| OPNsense 20.7.8     | 5        | 3.29%   |
| OPNsense 22.1.6     | 4        | 2.63%   |
| OPNsense 22.1.4     | 4        | 2.63%   |
| OPNsense 22.1.10    | 4        | 2.63%   |
| OPNsense 21.7.3     | 4        | 2.63%   |
| OPNsense 21.1.5     | 4        | 2.63%   |
| OPNsense 21.1.2     | 4        | 2.63%   |
| OPNsense 21.1       | 4        | 2.63%   |
| helloSystem 0.7.0   | 4        | 2.63%   |
| helloSystem 0.5.0   | 4        | 2.63%   |
| OPNsense 22.7.5     | 3        | 1.97%   |
| OPNsense 22.7.3     | 3        | 1.97%   |
| OPNsense 21.7.4     | 3        | 1.97%   |
| OPNsense 21.7.1     | 3        | 1.97%   |
| OPNsense 21.1.8     | 3        | 1.97%   |
| OPNsense 21.1.6     | 3        | 1.97%   |
| OPNsense 21.1.3     | 3        | 1.97%   |
| OPNsense 21.1.1     | 3        | 1.97%   |
| helloSystem 0.6.0   | 3        | 1.97%   |
| FreeBSD 12.1-p10    | 3        | 1.97%   |
| OPNsense 22.7       | 2        | 1.32%   |
| OPNsense 22.1.8     | 2        | 1.32%   |
| OPNsense 21.7.5     | 2        | 1.32%   |
| GhostBSD 20.04.02   | 2        | 1.32%   |
| FreeBSD 13.1        | 2        | 1.32%   |
| FreeBSD 13.0-STABLE | 2        | 1.32%   |
| FreeBSD 13.0-p4     | 2        | 1.32%   |
| FreeBSD 12.2        | 2        | 1.32%   |
| TrueNAS 12.2-p9     | 1        | 0.66%   |
| TrueNAS 12.2-p3     | 1        | 0.66%   |
| TrueNAS 12.2-p14    | 1        | 0.66%   |
| TrueNAS 12.2-p10    | 1        | 0.66%   |
| OPNsense 22.1.7     | 1        | 0.66%   |
| OPNsense 22.1.5     | 1        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 74       | 64.35%  |
| FreeBSD     | 18       | 15.65%  |
| helloSystem | 11       | 9.57%   |
| TrueNAS     | 4        | 3.48%   |
| OpenBSD     | 2        | 1.74%   |
| GhostBSD    | 2        | 1.74%   |
| FreeNAS     | 2        | 1.74%   |
| NomadBSD    | 1        | 0.87%   |
| NetBSD      | 1        | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 114      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 88       | 75.86%  |
| helloDesktop | 13       | 11.21%  |
| KDE5         | 4        | 3.45%   |
| XFCE         | 3        | 2.59%   |
| TWM          | 2        | 1.72%   |
| GNOME        | 2        | 1.72%   |
| Openbox      | 1        | 0.86%   |
| MATE         | 1        | 0.86%   |
| Lumina       | 1        | 0.86%   |
| i3           | 1        | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 92       | 80.7%   |
| X11     | 21       | 18.42%  |
| Wayland | 1        | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 93       | 81.58%  |
| SLiM    | 13       | 11.4%   |
| XDM     | 3        | 2.63%   |
| LightDM | 3        | 2.63%   |
| SDDM    | 2        | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 71.3%   |
| en_US   | 17       | 14.78%  |
| C       | 9        | 7.83%   |
| en_AU   | 7        | 6.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 88       | 77.19%  |
| BIOS | 26       | 22.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 66       | 57.39%  |
| Zfs    | 45       | 39.13%  |
| Ffs    | 2        | 1.74%   |
| Cd9660 | 2        | 1.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 103      | 90.35%  |
| MBR     | 9        | 7.89%   |
| BSD     | 1        | 0.88%   |
| Unknown | 1        | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell                       | 14       | 12.28%  |
| Hewlett-Packard            | 13       | 11.4%   |
| Protectli                  | 12       | 10.53%  |
| ASUSTek Computer           | 11       | 9.65%   |
| Unknown                    | 11       | 9.65%   |
| ASRock                     | 9        | 7.89%   |
| Gigabyte Technology        | 8        | 7.02%   |
| Lenovo                     | 6        | 5.26%   |
| MSI                        | 4        | 3.51%   |
| Intel                      | 4        | 3.51%   |
| PC Engines                 | 2        | 1.75%   |
| MW                         | 2        | 1.75%   |
| Acer                       | 2        | 1.75%   |
| Yanling                    | 1        | 0.88%   |
| Unknown                    | 1        | 0.88%   |
| Shuttle                    | 1        | 0.88%   |
| ShenZhen MinWin Technology | 1        | 0.88%   |
| SeeedStudio                | 1        | 0.88%   |
| Radxa                      | 1        | 0.88%   |
| Inventec                   | 1        | 0.88%   |
| IBM                        | 1        | 0.88%   |
| HARDKERNEL                 | 1        | 0.88%   |
| Gateway                    | 1        | 0.88%   |
| Foxconn                    | 1        | 0.88%   |
| Cisco                      | 1        | 0.88%   |
| AZW                        | 1        | 0.88%   |
| AOpen                      | 1        | 0.88%   |
| ADI Engineering            | 1        | 0.88%   |
| AAEON                      | 1        | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 12       | 10.53%  |
| Protectli FW4B                     | 8        | 7.02%   |
| HP ProLiant MicroServer            | 3        | 2.63%   |
| Dell OptiPlex 9020                 | 3        | 2.63%   |
| Protectli VP2410                   | 2        | 1.75%   |
| MW GMLK-2_5G4L                     | 2        | 1.75%   |
| Intel Q3XXG4-P V1.0                | 2        | 1.75%   |
| HP ProLiant MicroServer Gen8       | 2        | 1.75%   |
| Dell OptiPlex 3010                 | 2        | 1.75%   |
| ASUS All Series                    | 2        | 1.75%   |
| Yanling YL-KBR6L                   | 1        | 0.88%   |
| Shuttle DH370                      | 1        | 0.88%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 1        | 0.88%   |
| SeeedStudio ODYSSEY-X86J4125       | 1        | 0.88%   |
| Radxa ROCK Pi X                    | 1        | 0.88%   |
| Protectli FW6                      | 1        | 0.88%   |
| Protectli FW2B                     | 1        | 0.88%   |
| PC Engines apu4                    | 1        | 0.88%   |
| PC Engines apu1                    | 1        | 0.88%   |
| MSI Pro 3130 Small Form Factor PC  | 1        | 0.88%   |
| MSI MS-7C95                        | 1        | 0.88%   |
| MSI MS-7C94                        | 1        | 0.88%   |
| MSI CML-U PRO Cubi 5 (MS-B183)     | 1        | 0.88%   |
| Lenovo ThinkCentre M93p 10AAS3UM00 | 1        | 0.88%   |
| Lenovo ThinkCentre M92p 3238CE1    | 1        | 0.88%   |
| Lenovo ThinkCentre M73 10AY009MAU  | 1        | 0.88%   |
| Lenovo ThinkCentre M700 10HY002XAU | 1        | 0.88%   |
| Lenovo ThinkCentre M58 7360BB6     | 1        | 0.88%   |
| Lenovo IdeaPad 5 15ITL05 82FG      | 1        | 0.88%   |
| Inventec D CLASS                   | 1        | 0.88%   |
| Intel NCB-4210WG                   | 1        | 0.88%   |
| Intel DN2820FYK H24582-201         | 1        | 0.88%   |
| IBM 9210MML                        | 1        | 0.88%   |
| HP Z400 Workstation                | 1        | 0.88%   |
| HP Z240 SFF Workstation            | 1        | 0.88%   |
| HP ProLiant ML150 G6               | 1        | 0.88%   |
| HP ProLiant ML10 v2                | 1        | 0.88%   |
| HP prodesk 400 g2 sff business pc  | 1        | 0.88%   |
| HP EliteDesk 800 G2 DM 35W         | 1        | 0.88%   |
| HP EliteDesk 800 G1 SFF            | 1        | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 12       | 10.53%  |
| Unknown                        | 12       | 10.53%  |
| Protectli FW4B                 | 8        | 7.02%   |
| HP ProLiant                    | 7        | 6.14%   |
| Lenovo ThinkCentre             | 5        | 4.39%   |
| HP EliteDesk                   | 3        | 2.63%   |
| ASUS ROG                       | 3        | 2.63%   |
| Protectli VP2410               | 2        | 1.75%   |
| MW GMLK-2                      | 2        | 1.75%   |
| Intel Q3XXG4-P                 | 2        | 1.75%   |
| ASUS PRIME                     | 2        | 1.75%   |
| ASUS All                       | 2        | 1.75%   |
| ASRock X370                    | 2        | 1.75%   |
| Acer Veriton                   | 2        | 1.75%   |
| Yanling YL-KBR6L               | 1        | 0.88%   |
| Shuttle DH370                  | 1        | 0.88%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.88%   |
| SeeedStudio ODYSSEY-X86J4125   | 1        | 0.88%   |
| Radxa ROCK                     | 1        | 0.88%   |
| Protectli FW6                  | 1        | 0.88%   |
| Protectli FW2B                 | 1        | 0.88%   |
| PC Engines apu4                | 1        | 0.88%   |
| PC Engines apu1                | 1        | 0.88%   |
| MSI Pro                        | 1        | 0.88%   |
| MSI MS-7C95                    | 1        | 0.88%   |
| MSI MS-7C94                    | 1        | 0.88%   |
| MSI CML-U                      | 1        | 0.88%   |
| Lenovo IdeaPad                 | 1        | 0.88%   |
| Inventec D                     | 1        | 0.88%   |
| Intel NCB-4210WG               | 1        | 0.88%   |
| Intel DN2820FYK                | 1        | 0.88%   |
| IBM 9210MML                    | 1        | 0.88%   |
| HP Z400                        | 1        | 0.88%   |
| HP Z240                        | 1        | 0.88%   |
| HP prodesk                     | 1        | 0.88%   |
| HARDKERNEL ODROID-H2           | 1        | 0.88%   |
| Gigabyte Z87N-WIFI             | 1        | 0.88%   |
| Gigabyte Z77N-WIFI             | 1        | 0.88%   |
| Gigabyte Z68MA-D2H-B3          | 1        | 0.88%   |
| Gigabyte J1900N-D3V            | 1        | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 14       | 12.28%  |
| 2013    | 13       | 11.4%   |
| 2020    | 12       | 10.53%  |
| 2021    | 11       | 9.65%   |
| 2018    | 11       | 9.65%   |
| 2016    | 9        | 7.89%   |
| 2011    | 7        | 6.14%   |
| 2017    | 6        | 5.26%   |
| 2014    | 6        | 5.26%   |
| 2012    | 6        | 5.26%   |
| 2015    | 5        | 4.39%   |
| 2022    | 4        | 3.51%   |
| 2009    | 4        | 3.51%   |
| 2010    | 2        | 1.75%   |
| Unknown | 2        | 1.75%   |
| 2008    | 1        | 0.88%   |
| 2006    | 1        | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 114      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 108      | 94.74%  |
| Yes  | 6        | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 55       | 47.01%  |
| 16.01-24.0  | 25       | 21.37%  |
| 4.01-8.0    | 20       | 17.09%  |
| 32.01-64.0  | 8        | 6.84%   |
| 24.01-32.0  | 3        | 2.56%   |
| 64.01-256.0 | 3        | 2.56%   |
| 2.01-3.0    | 2        | 1.71%   |
| 0.51-1.0    | 1        | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 64       | 53.78%  |
| 0.51-1.0   | 31       | 26.05%  |
| 1.01-2.0   | 9        | 7.56%   |
| 4.01-8.0   | 5        | 4.2%    |
| 3.01-4.0   | 2        | 1.68%   |
| 2.01-3.0   | 2        | 1.68%   |
| 16.01-24.0 | 2        | 1.68%   |
| 8.01-16.0  | 2        | 1.68%   |
| 32.01-64.0 | 1        | 0.84%   |
| Unknown    | 1        | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 75       | 64.66%  |
| 2      | 14       | 12.07%  |
| 3      | 9        | 7.76%   |
| 0      | 9        | 7.76%   |
| 4      | 4        | 3.45%   |
| 5      | 2        | 1.72%   |
| 10     | 1        | 0.86%   |
| 7      | 1        | 0.86%   |
| 6      | 1        | 0.86%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 80.7%   |
| Yes       | 22       | 19.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 112      | 98.25%  |
| No        | 2        | 1.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 79.13%  |
| Yes       | 24       | 20.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 87.83%  |
| Yes       | 14       | 12.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 114      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 33       | 26.83%  |
| Melbourne      | 19       | 15.45%  |
| Perth          | 14       | 11.38%  |
| Brisbane       | 13       | 10.57%  |
| Adelaide       | 6        | 4.88%   |
| Marrickville   | 2        | 1.63%   |
| Ipswich        | 2        | 1.63%   |
| Hobart         | 2        | 1.63%   |
| Canberra       | 2        | 1.63%   |
| Wollongong     | 1        | 0.81%   |
| Wheelers Hill  | 1        | 0.81%   |
| Wallan         | 1        | 0.81%   |
| Townsville     | 1        | 0.81%   |
| Southport      | 1        | 0.81%   |
| Shell Cove     | 1        | 0.81%   |
| Ryde           | 1        | 0.81%   |
| Rosanna        | 1        | 0.81%   |
| Ringwood       | 1        | 0.81%   |
| North Shore    | 1        | 0.81%   |
| Noble Park     | 1        | 0.81%   |
| Mount Waverley | 1        | 0.81%   |
| Mooroolbark    | 1        | 0.81%   |
| Malvern        | 1        | 0.81%   |
| Kurunjang      | 1        | 0.81%   |
| Kellyville     | 1        | 0.81%   |
| Gold Coast     | 1        | 0.81%   |
| Geelong        | 1        | 0.81%   |
| Engadine       | 1        | 0.81%   |
| East Malvern   | 1        | 0.81%   |
| Dowerin        | 1        | 0.81%   |
| Dandenong      | 1        | 0.81%   |
| Corio          | 1        | 0.81%   |
| Brunswick      | 1        | 0.81%   |
| Blackburn      | 1        | 0.81%   |
| Bayswater      | 1        | 0.81%   |
| Balwyn North   | 1        | 0.81%   |
| Ashfield       | 1        | 0.81%   |
| Ascot Vale     | 1        | 0.81%   |
| Unknown        | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 16.31%  |
| Samsung Electronics | 21       | 31     | 14.89%  |
| WDC                 | 20       | 55     | 14.18%  |
| Kingston            | 9        | 16     | 6.38%   |
| Crucial             | 8        | 8      | 5.67%   |
| Intel               | 7        | 13     | 4.96%   |
| Hoodisk             | 6        | 13     | 4.26%   |
| Toshiba             | 5        | 9      | 3.55%   |
| SanDisk             | 5        | 7      | 3.55%   |
| Protectli           | 3        | 3      | 2.13%   |
| Hewlett-Packard     | 3        | 6      | 2.13%   |
| Phison              | 2        | 2      | 1.42%   |
| Micron Technology   | 2        | 3      | 1.42%   |
| Gigabyte Technology | 2        | 2      | 1.42%   |
| China               | 2        | 2      | 1.42%   |
| BIWIN               | 2        | 2      | 1.42%   |
| A-DATA Technology   | 2        | 7      | 1.42%   |
| XUNZHE              | 1        | 1      | 0.71%   |
| Vaseky              | 1        | 3      | 0.71%   |
| Transcend           | 1        | 1      | 0.71%   |
| SPCC                | 1        | 5      | 0.71%   |
| Silicon Motion      | 1        | 1      | 0.71%   |
| ShiJi               | 1        | 1      | 0.71%   |
| PNY                 | 1        | 1      | 0.71%   |
| Plextor             | 1        | 2      | 0.71%   |
| Patriot             | 1        | 1      | 0.71%   |
| OCZ                 | 1        | 2      | 0.71%   |
| NVMe                | 1        | 1      | 0.71%   |
| Maxtor              | 1        | 1      | 0.71%   |
| LITEONIT            | 1        | 1      | 0.71%   |
| KingSpec            | 1        | 1      | 0.71%   |
| KingDian            | 1        | 1      | 0.71%   |
| Hitachi             | 1        | 1      | 0.71%   |
| HGST                | 1        | 1      | 0.71%   |
| Fordisk             | 1        | 1      | 0.71%   |
| Dogfish             | 1        | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hoodisk SSD 128GB                | 6        | 3.8%    |
| Kingston SA400S37120G 120GB      | 3        | 1.9%    |
| Crucial CT250P2SSD8 250GB        | 3        | 1.9%    |
| Crucial CT250MX500SSD1 250GB     | 3        | 1.9%    |
| WDC WDS250G2B0A-00SM50 250GB     | 2        | 1.27%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 1.27%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2        | 1.27%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 1.27%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 1.27%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 1.27%   |
| Samsung SSD 850 EVO 500GB        | 2        | 1.27%   |
| Samsung SSD 840 EVO 120GB        | 2        | 1.27%   |
| Samsung MZ7LN128HCHP-000H1 128GB | 2        | 1.27%   |
| Protectli 120GB mSATA            | 2        | 1.27%   |
| Kingston SA400S37480G 480GB      | 2        | 1.27%   |
| XUNZHE MSATA 128GB               | 1        | 0.63%   |
| WDC WDS500G1R0B-68A4Z0 500GB     | 1        | 0.63%   |
| WDC WDS250G2B0C-00PXH0 250GB     | 1        | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB     | 1        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB     | 1        | 0.63%   |
| WDC WD80EFAX-68KNBN0 8TB         | 1        | 0.63%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.63%   |
| WDC WD5000BPKT-00PK4T0 500GB     | 1        | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.63%   |
| WDC WD4000AAKS-00TMA0 400GB      | 1        | 0.63%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 0.63%   |
| WDC WD20EARX-00PASB0 2TB         | 1        | 0.63%   |
| WDC WD20EARX-008FB0 2TB          | 1        | 0.63%   |
| WDC WD20EARS-00MVWB0 2TB         | 1        | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1        | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB         | 1        | 0.63%   |
| WDC WD10EURX-63UY4Y0 1TB         | 1        | 0.63%   |
| WDC WD10EARX-00N0YB0 1TB         | 1        | 0.63%   |
| WDC WD10EADS-00P8B0 1TB          | 1        | 0.63%   |
| Vaseky V850-64G                  | 1        | 0.63%   |
| Transcend TS16EPTMM1600L 16GB    | 1        | 0.63%   |
| Toshiba THNSNJ128GMCU 128GB      | 1        | 0.63%   |
| Toshiba MQ04UBF100 1TB           | 1        | 0.63%   |

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
| Samsung Electronics | 14       | 22     | 20%     |
| Kingston            | 9        | 16     | 12.86%  |
| Intel               | 6        | 12     | 8.57%   |
| Hoodisk             | 6        | 13     | 8.57%   |
| SanDisk             | 5        | 7      | 7.14%   |
| WDC                 | 4        | 6      | 5.71%   |
| Crucial             | 4        | 4      | 5.71%   |
| Protectli           | 3        | 3      | 4.29%   |
| Micron Technology   | 2        | 3      | 2.86%   |
| China               | 2        | 2      | 2.86%   |
| XUNZHE              | 1        | 1      | 1.43%   |
| Vaseky              | 1        | 3      | 1.43%   |
| Transcend           | 1        | 1      | 1.43%   |
| Toshiba             | 1        | 3      | 1.43%   |
| ShiJi               | 1        | 1      | 1.43%   |
| Plextor             | 1        | 2      | 1.43%   |
| Phison              | 1        | 1      | 1.43%   |
| Patriot             | 1        | 1      | 1.43%   |
| OCZ                 | 1        | 2      | 1.43%   |
| LITEONIT            | 1        | 1      | 1.43%   |
| KingSpec            | 1        | 1      | 1.43%   |
| KingDian            | 1        | 1      | 1.43%   |
| Fordisk             | 1        | 1      | 1.43%   |
| Dogfish             | 1        | 1      | 1.43%   |
| BIWIN               | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 66       | 109    | 52.8%   |
| HDD  | 41       | 99     | 32.8%   |
| NVMe | 18       | 28     | 14.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 96       | 208    | 84.21%  |
| NVMe | 18       | 28     | 15.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 80       | 136    | 70.8%   |
| 0.51-1.0   | 14       | 23     | 12.39%  |
| 1.01-2.0   | 10       | 25     | 8.85%   |
| 3.01-4.0   | 4        | 9      | 3.54%   |
| 2.01-3.0   | 2        | 8      | 1.77%   |
| 4.01-10.0  | 2        | 5      | 1.77%   |
| 10.01-20.0 | 1        | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 53       | 46.49%  |
| 251-500    | 16       | 14.04%  |
| 1-20       | 15       | 13.16%  |
| 501-1000   | 10       | 8.77%   |
| 51-100     | 10       | 8.77%   |
| 21-50      | 6        | 5.26%   |
| 2001-3000  | 2        | 1.75%   |
| 1001-2000  | 2        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 108      | 90.76%  |
| 21-50     | 8        | 6.72%   |
| 101-250   | 1        | 0.84%   |
| 1001-2000 | 1        | 0.84%   |
| 51-100    | 1        | 0.84%   |

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
| Works    | 96       | 216    | 86.49%  |
| Malfunc  | 14       | 19     | 12.61%  |
| Detected | 1        | 1      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 95       | 67.86%  |
| AMD                       | 19       | 13.57%  |
| Samsung Electronics       | 5        | 3.57%   |
| Phison Electronics        | 5        | 3.57%   |
| Micron/Crucial Technology | 4        | 2.86%   |
| Silicon Motion            | 2        | 1.43%   |
| Broadcom / LSI            | 2        | 1.43%   |
| Silicon Image             | 1        | 0.71%   |
| SanDisk                   | 1        | 0.71%   |
| Realtek Semiconductor     | 1        | 0.71%   |
| QLogic                    | 1        | 0.71%   |
| JMicron Technology        | 1        | 0.71%   |
| Hewlett-Packard           | 1        | 0.71%   |
| ADATA Technology          | 1        | 0.71%   |
| Adaptec                   | 1        | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11       | 6.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 6.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 6.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 5.03%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 5.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 4.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 4.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 3.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 3.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 2.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.52%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3        | 1.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.89%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 1.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.26%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 1.26%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.26%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.26%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2        | 1.26%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.26%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.26%   |
| Unknown                                                                                 | 2        | 1.26%   |
| Silicon Image AAR-1220SA Serial ATA HostRAID Controller                                 | 1        | 0.63%   |
| SanDisk unknown                                                                         | 1        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.63%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.63%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                             | 1        | 0.63%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 106      | 71.14%  |
| NVMe | 19       | 12.75%  |
| IDE  | 15       | 10.07%  |
| RAID | 5        | 3.36%   |
| SAS  | 2        | 1.34%   |
| SCSI | 2        | 1.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 83.33%  |
| AMD    | 19       | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 10       | 8.7%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 6        | 5.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.61%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 2.61%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2        | 1.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.74%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 1.74%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 1.74%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.74%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 1.74%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.74%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.74%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.87%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.87%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.87%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.87%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.87%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.87%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.87%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.87%   |
| Intel Xeon                                  | 1        | 0.87%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.87%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.87%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1        | 0.87%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.87%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.87%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.87%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.87%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.87%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.87%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 0.87%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1        | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1        | 0.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.87%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.87%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 30       | 26.09%  |
| Intel Core i5           | 24       | 20.87%  |
| Intel Xeon              | 11       | 9.57%   |
| Intel Core i3           | 11       | 9.57%   |
| Intel Core i7           | 6        | 5.22%   |
| Intel Pentium           | 4        | 3.48%   |
| AMD Ryzen 5             | 4        | 3.48%   |
| Intel Core 2 Quad       | 3        | 2.61%   |
| AMD Turion II Neo       | 3        | 2.61%   |
| AMD Ryzen 3             | 3        | 2.61%   |
| AMD FX                  | 3        | 2.61%   |
| Other                   | 2        | 1.74%   |
| Intel Atom              | 2        | 1.74%   |
| AMD G                   | 2        | 1.74%   |
| Intel Pentium Silver    | 1        | 0.87%   |
| Intel Pentium Dual-Core | 1        | 0.87%   |
| Intel Pentium 4         | 1        | 0.87%   |
| AMD Ryzen 9             | 1        | 0.87%   |
| AMD GX                  | 1        | 0.87%   |
| AMD E2                  | 1        | 0.87%   |
| AMD Athlon              | 1        | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 64       | 55.65%  |
| 2       | 29       | 25.22%  |
| 8       | 10       | 8.7%    |
| 6       | 5        | 4.35%   |
| 12      | 3        | 2.61%   |
| Unknown | 3        | 2.61%   |
| 32      | 1        | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 112      | 98.25%  |
| 2      | 2        | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 85       | 73.91%  |
| 2       | 27       | 23.48%  |
| Unknown | 3        | 2.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 18       | 15.79%  |
| Haswell       | 12       | 10.53%  |
| KabyLake      | 11       | 9.65%   |
| IvyBridge     | 9        | 7.89%   |
| Skylake       | 8        | 7.02%   |
| SandyBridge   | 8        | 7.02%   |
| Goldmont plus | 7        | 6.14%   |
| Nehalem       | 4        | 3.51%   |
| Unknown       | 4        | 3.51%   |
| Zen 3         | 3        | 2.63%   |
| Westmere      | 3        | 2.63%   |
| Piledriver    | 3        | 2.63%   |
| Penryn        | 3        | 2.63%   |
| K10           | 3        | 2.63%   |
| Broadwell     | 3        | 2.63%   |
| Bobcat        | 3        | 2.63%   |
| Zen 2         | 2        | 1.75%   |
| Zen           | 2        | 1.75%   |
| Zen+          | 1        | 0.88%   |
| TigerLake     | 1        | 0.88%   |
| Puma          | 1        | 0.88%   |
| NetBurst      | 1        | 0.88%   |
| Jaguar        | 1        | 0.88%   |
| Goldmont      | 1        | 0.88%   |
| Core          | 1        | 0.88%   |
| CometLake     | 1        | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 75       | 66.37%  |
| AMD                        | 17       | 15.04%  |
| Nvidia                     | 14       | 12.39%  |
| Matrox Electronics Systems | 5        | 4.42%   |
| Tseng Labs                 | 1        | 0.88%   |
| ASPEED Technology          | 1        | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12       | 10.43%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 7.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 6.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 5.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 5.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 4.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 4.35%   |
| Intel HD Graphics 530                                                                    | 3        | 2.61%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3        | 2.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.74%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 1.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.74%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.74%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 1.74%   |
| Intel UHD Graphics 620                                                                   | 2        | 1.74%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 1.74%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 1.74%   |
| AMD Cezanne                                                                              | 2        | 1.74%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.74%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 0.87%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.87%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.87%   |
| Nvidia GF100GL [Quadro 4000]                                                             | 1        | 0.87%   |
| Nvidia G92 [GeForce GT 330]                                                              | 1        | 0.87%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 0.87%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 0.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.87%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.87%   |
| Intel Iris Plus Graphics 650                                                             | 1        | 0.87%   |
| Intel HD Graphics P530                                                                   | 1        | 0.87%   |
| Intel HD Graphics 610                                                                    | 1        | 0.87%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.87%   |
| Intel HD Graphics 510                                                                    | 1        | 0.87%   |
| Intel HD Graphics 500                                                                    | 1        | 0.87%   |
| Intel HD Graphics                                                                        | 1        | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 69       | 59.48%  |
| 1 x AMD        | 16       | 13.79%  |
| 1 x Nvidia     | 12       | 10.34%  |
| Other          | 5        | 4.31%   |
| 1 x Matrox     | 5        | 4.31%   |
| 2 x Intel      | 3        | 2.59%   |
| Intel + Nvidia | 2        | 1.72%   |
| 2 x AMD        | 1        | 0.86%   |
| 1 x Tseng Labs | 1        | 0.86%   |
| Intel + AMD    | 1        | 0.86%   |
| 1 x ASPEED     | 1        | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 103      | 90.35%  |
| Proprietary | 6        | 5.26%   |
| Unknown     | 5        | 4.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 89.57%  |
| 1.01-2.0   | 6        | 5.22%   |
| 0.51-1.0   | 3        | 2.61%   |
| 7.01-8.0   | 2        | 1.74%   |
| 3.01-4.0   | 1        | 0.87%   |

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
| 0     | 92       | 80.7%   |
| 1     | 21       | 18.42%  |
| 2     | 1        | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 81       | 54%     |
| Realtek Semiconductor    | 43       | 28.67%  |
| Broadcom                 | 12       | 8%      |
| Qualcomm Atheros         | 4        | 2.67%   |
| U-Blox                   | 2        | 1.33%   |
| TP-Link                  | 1        | 0.67%   |
| Seeed Technology         | 1        | 0.67%   |
| Ralink Technology        | 1        | 0.67%   |
| Ralink                   | 1        | 0.67%   |
| Marvell Technology Group | 1        | 0.67%   |
| IMC Networks             | 1        | 0.67%   |
| D-Link System            | 1        | 0.67%   |
| Aquantia                 | 1        | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38       | 21.35%  |
| Intel I211 Gigabit Network Connection                                         | 22       | 12.36%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 5.06%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.37%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 2.81%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 2.81%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.25%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.69%   |
| Intel Wireless 7260                                                           | 3        | 1.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.69%   |
| Unknown                                                                       | 3        | 1.69%   |
| U-Blox [u-blox 7]                                                             | 2        | 1.12%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 1.12%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.12%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.12%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.12%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.12%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.12%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.56%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.56%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.56%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.56%   |

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
| Intel                    | 76       | 56.72%  |
| Realtek Semiconductor    | 41       | 30.6%   |
| Broadcom                 | 12       | 8.96%   |
| Qualcomm Atheros         | 2        | 1.49%   |
| Marvell Technology Group | 1        | 0.75%   |
| D-Link System            | 1        | 0.75%   |
| Aquantia                 | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 38       | 25.5%   |
| Intel I211 Gigabit Network Connection                                         | 22       | 14.77%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 6.04%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.03%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.36%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 3.36%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 2.01%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.01%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 2.01%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 2.01%   |
| Unknown                                                                       | 3        | 2.01%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.34%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.34%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.34%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.34%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.34%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.34%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.67%   |
| Intel Ethernet Controller X550                                                | 1        | 0.67%   |
| Intel Ethernet Connection I354                                                | 1        | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.67%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.67%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1        | 0.67%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.67%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.67%   |
| Intel 82573E Gigabit Ethernet Controller (Copper)                             | 1        | 0.67%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.67%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.67%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 80%     |
| WiFi     | 24       | 17.14%  |
| Modem    | 3        | 2.14%   |
| Unknown  | 1        | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 91.74%  |
| WiFi     | 10       | 8.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 35       | 30.17%  |
| 1     | 25       | 21.55%  |
| 4     | 24       | 20.69%  |
| 3     | 14       | 12.07%  |
| 6     | 8        | 6.9%    |
| 5     | 7        | 6.03%   |
| 7     | 2        | 1.72%   |
| 9     | 1        | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 82.2%   |
| Yes  | 21       | 17.8%   |

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
| Intel              | 77       | 71.3%   |
| AMD                | 16       | 14.81%  |
| Nvidia             | 12       | 11.11%  |
| Texas Instruments  | 1        | 0.93%   |
| Logitech           | 1        | 0.93%   |
| Focusrite-Novation | 1        | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 8.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 7.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 6.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 5.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 3.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5        | 3.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 3.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 3.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 3.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 3.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 3.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 3.05%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 3.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.29%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.53%   |
| Intel Jasper Lake HD Audio                                                                        | 2        | 1.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.53%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.53%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.53%   |
| Unknown                                                                                           | 2        | 1.53%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.76%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1        | 0.76%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.76%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.76%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1        | 0.76%   |
| Logitech Headset H390                                                                             | 1        | 0.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.76%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 20       | 16%     |
| Kingston            | 20       | 16%     |
| Unknown             | 14       | 11.2%   |
| SK hynix            | 12       | 9.6%    |
| Micron Technology   | 12       | 9.6%    |
| Corsair             | 11       | 8.8%    |
| Crucial             | 7        | 5.6%    |
| G.Skill             | 6        | 4.8%    |
| Unknown             | 3        | 2.4%    |
| Unknown (ABCD)      | 2        | 1.6%    |
| Transcend           | 2        | 1.6%    |
| Team                | 2        | 1.6%    |
| Apacer              | 2        | 1.6%    |
| Vasekey             | 1        | 0.8%    |
| Timetec             | 1        | 0.8%    |
| Smart Modular       | 1        | 0.8%    |
| Ramaxel Technology  | 1        | 0.8%    |
| PNY                 | 1        | 0.8%    |
| Patriot             | 1        | 0.8%    |
| Nanya Technology    | 1        | 0.8%    |
| Kingmax             | 1        | 0.8%    |
| Innodisk            | 1        | 0.8%    |
| Hewlett-Packard     | 1        | 0.8%    |
| GeIL                | 1        | 0.8%    |
| Elpida              | 1        | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3        | 2.29%   |
| Unknown                                                           | 3        | 2.29%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2        | 1.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2        | 1.53%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2        | 1.53%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2        | 1.53%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 1.53%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2        | 1.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 1.53%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2        | 1.53%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2        | 1.53%   |
| Vasekey RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 1        | 0.76%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                           | 1        | 0.76%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1        | 0.76%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1        | 0.76%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.76%   |
| Timetec RAM SD3-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.76%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s               | 1        | 0.76%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.76%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.76%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.76%   |
| SK hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.76%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1        | 0.76%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s            | 1        | 0.76%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s              | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 60       | 55.56%  |
| DDR4    | 36       | 33.33%  |
| Unknown | 7        | 6.48%   |
| LPDDR4  | 2        | 1.85%   |
| DDR     | 2        | 1.85%   |
| DDR2    | 1        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 77       | 71.96%  |
| SODIMM  | 26       | 24.3%   |
| Unknown | 3        | 2.8%    |
| RIMM    | 1        | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 49       | 42.98%  |
| 4096  | 34       | 29.82%  |
| 2048  | 15       | 13.16%  |
| 16384 | 11       | 9.65%   |
| 1024  | 3        | 2.63%   |
| 32768 | 2        | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 40       | 35.71%  |
| 1333  | 23       | 20.54%  |
| 2400  | 13       | 11.61%  |
| 2133  | 11       | 9.82%   |
| 2667  | 8        | 7.14%   |
| 800   | 4        | 3.57%   |
| 1066  | 3        | 2.68%   |
| 3600  | 2        | 1.79%   |
| 3200  | 2        | 1.79%   |
| 2666  | 2        | 1.79%   |
| 59392 | 1        | 0.89%   |
| 3000  | 1        | 0.89%   |
| 1867  | 1        | 0.89%   |
| 400   | 1        | 0.89%   |

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
| 1     | 57       | 49.57%  |
| 0     | 45       | 39.13%  |
| 2     | 9        | 7.83%   |
| 3     | 2        | 1.74%   |
| 5     | 1        | 0.87%   |
| 4     | 1        | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 62       | 74.7%   |
| Bluetooth                | 6        | 7.23%   |
| Net/wireless             | 4        | 4.82%   |
| Firewire controller      | 3        | 3.61%   |
| Card reader              | 3        | 3.61%   |
| Sound                    | 2        | 2.41%   |
| Network                  | 2        | 2.41%   |
| Dvb card                 | 1        | 1.2%    |

