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

Total: 161

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| MSI           | 2A9C                        | [9417bdd744](https://bsd-hardware.info/?probe=9417bdd744) | Apr 18, 2022 |
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
| Unknown       | Unknown                     | [760e148164](https://bsd-hardware.info/?probe=760e148164) | Feb 19, 2021 |
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
| OPNsense 22.1       | 8        | 6.11%   |
| OPNsense 21.7.7     | 5        | 3.82%   |
| OPNsense 21.7.2     | 5        | 3.82%   |
| OPNsense 21.1.4     | 5        | 3.82%   |
| OPNsense 20.7.8     | 5        | 3.82%   |
| OPNsense 22.1.6     | 4        | 3.05%   |
| OPNsense 22.1.4     | 4        | 3.05%   |
| OPNsense 21.7.3     | 4        | 3.05%   |
| OPNsense 21.1.5     | 4        | 3.05%   |
| OPNsense 21.1.2     | 4        | 3.05%   |
| OPNsense 21.1       | 4        | 3.05%   |
| helloSystem 0.7.0   | 4        | 3.05%   |
| helloSystem 0.5.0   | 4        | 3.05%   |
| OPNsense 22.1.10    | 3        | 2.29%   |
| OPNsense 21.7.4     | 3        | 2.29%   |
| OPNsense 21.7.1     | 3        | 2.29%   |
| OPNsense 21.1.8     | 3        | 2.29%   |
| OPNsense 21.1.6     | 3        | 2.29%   |
| OPNsense 21.1.3     | 3        | 2.29%   |
| OPNsense 21.1.1     | 3        | 2.29%   |
| helloSystem 0.6.0   | 3        | 2.29%   |
| FreeBSD 12.1-p10    | 3        | 2.29%   |
| OPNsense 22.1.8     | 2        | 1.53%   |
| OPNsense 21.7.5     | 2        | 1.53%   |
| GhostBSD 20.04.02   | 2        | 1.53%   |
| FreeBSD 13.1        | 2        | 1.53%   |
| FreeBSD 13.0-STABLE | 2        | 1.53%   |
| FreeBSD 13.0-p4     | 2        | 1.53%   |
| FreeBSD 12.2        | 2        | 1.53%   |
| TrueNAS 12.2-p9     | 1        | 0.76%   |
| TrueNAS 12.2-p3     | 1        | 0.76%   |
| TrueNAS 12.2-p14    | 1        | 0.76%   |
| TrueNAS 12.2-p10    | 1        | 0.76%   |
| OPNsense 22.7       | 1        | 0.76%   |
| OPNsense 22.1.7     | 1        | 0.76%   |
| OPNsense 22.1.5     | 1        | 0.76%   |
| OPNsense 22.1.3     | 1        | 0.76%   |
| OPNsense 22.1.2     | 1        | 0.76%   |
| OPNsense 22.1.1     | 1        | 0.76%   |
| OPNsense 21.7.8     | 1        | 0.76%   |
| OPNsense 21.7.6     | 1        | 0.76%   |
| OPNsense 21.7       | 1        | 0.76%   |
| OPNsense 20.7       | 1        | 0.76%   |
| OPNsense 20.1.7     | 1        | 0.76%   |
| OpenBSD 6.8         | 1        | 0.76%   |
| NomadBSD 5806f915   | 1        | 0.76%   |
| NetBSD 9.99.94      | 1        | 0.76%   |
| helloSystem 0.4.0   | 1        | 0.76%   |
| GhostBSD 22.04.22   | 1        | 0.76%   |
| FreeNAS 11.4-p4     | 1        | 0.76%   |
| FreeNAS 11.3-p9     | 1        | 0.76%   |
| FreeBSD 13.1-p1     | 1        | 0.76%   |
| FreeBSD 13.0-RC1    | 1        | 0.76%   |
| FreeBSD 13.0-p5     | 1        | 0.76%   |
| FreeBSD 13.0-p3     | 1        | 0.76%   |
| FreeBSD 12.2-p11    | 1        | 0.76%   |
| FreeBSD 12.2-p10    | 1        | 0.76%   |
| FreeBSD 12.1-p12    | 1        | 0.76%   |
| FreeBSD 11.4        | 1        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 62       | 61.39%  |
| FreeBSD     | 17       | 16.83%  |
| helloSystem | 11       | 10.89%  |
| TrueNAS     | 4        | 3.96%   |
| GhostBSD    | 2        | 1.98%   |
| FreeNAS     | 2        | 1.98%   |
| OpenBSD     | 1        | 0.99%   |
| NomadBSD    | 1        | 0.99%   |
| NetBSD      | 1        | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 100      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 75       | 73.53%  |
| helloDesktop | 12       | 11.76%  |
| KDE5         | 4        | 3.92%   |
| XFCE         | 3        | 2.94%   |
| TWM          | 2        | 1.96%   |
| GNOME        | 2        | 1.96%   |
| Openbox      | 1        | 0.98%   |
| MATE         | 1        | 0.98%   |
| Lumina       | 1        | 0.98%   |
| i3           | 1        | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 79       | 79%     |
| X11     | 20       | 20%     |
| Wayland | 1        | 1%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 79       | 79%     |
| SLiM    | 13       | 13%     |
| XDM     | 3        | 3%      |
| LightDM | 3        | 3%      |
| SDDM    | 2        | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 68.32%  |
| en_US   | 17       | 16.83%  |
| C       | 8        | 7.92%   |
| en_AU   | 7        | 6.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 76       | 76%     |
| BIOS | 24       | 24%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 58       | 57.43%  |
| Zfs    | 40       | 39.6%   |
| Cd9660 | 2        | 1.98%   |
| Ffs    | 1        | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 90       | 90%     |
| MBR     | 9        | 9%      |
| Unknown | 1        | 1%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Hewlett-Packard            | 13       | 13%     |
| Dell                       | 12       | 12%     |
| Protectli                  | 11       | 11%     |
| ASUSTek Computer           | 10       | 10%     |
| Gigabyte Technology        | 8        | 8%      |
| ASRock                     | 8        | 8%      |
| Unknown                    | 6        | 6%      |
| Lenovo                     | 5        | 5%      |
| Intel                      | 4        | 4%      |
| MSI                        | 3        | 3%      |
| MW                         | 2        | 2%      |
| Acer                       | 2        | 2%      |
| Yanling                    | 1        | 1%      |
| Unknown                    | 1        | 1%      |
| Shuttle                    | 1        | 1%      |
| ShenZhen MinWin Technology | 1        | 1%      |
| SeeedStudio                | 1        | 1%      |
| Radxa                      | 1        | 1%      |
| PC Engines                 | 1        | 1%      |
| Inventec                   | 1        | 1%      |
| HARDKERNEL                 | 1        | 1%      |
| Gateway                    | 1        | 1%      |
| Foxconn                    | 1        | 1%      |
| Cisco                      | 1        | 1%      |
| AZW                        | 1        | 1%      |
| AOpen                      | 1        | 1%      |
| ADI Engineering            | 1        | 1%      |
| AAEON                      | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Protectli FW4B                     | 7        | 7%      |
| Unknown                            | 7        | 7%      |
| HP ProLiant MicroServer            | 3        | 3%      |
| Dell OptiPlex 9020                 | 3        | 3%      |
| Protectli VP2410                   | 2        | 2%      |
| MW GMLK-2_5G4L                     | 2        | 2%      |
| Intel Q3XXG4-P V1.0                | 2        | 2%      |
| HP ProLiant MicroServer Gen8       | 2        | 2%      |
| Dell OptiPlex 3010                 | 2        | 2%      |
| ASUS All Series                    | 2        | 2%      |
| Yanling YL-KBR6L                   | 1        | 1%      |
| Shuttle DH370                      | 1        | 1%      |
| ShenZhen MinWin MW-NANO-APL-4L     | 1        | 1%      |
| SeeedStudio ODYSSEY-X86J4125       | 1        | 1%      |
| Radxa ROCK Pi X                    | 1        | 1%      |
| Protectli FW6                      | 1        | 1%      |
| Protectli FW2B                     | 1        | 1%      |
| PC Engines apu4                    | 1        | 1%      |
| MSI Pro 3130 Small Form Factor PC  | 1        | 1%      |
| MSI MS-7C95                        | 1        | 1%      |
| MSI CML-U PRO Cubi 5 (MS-B183)     | 1        | 1%      |
| Lenovo ThinkCentre M93p 10AAS3UM00 | 1        | 1%      |
| Lenovo ThinkCentre M92p 3238CE1    | 1        | 1%      |
| Lenovo ThinkCentre M73 10AY009MAU  | 1        | 1%      |
| Lenovo ThinkCentre M700 10HY002XAU | 1        | 1%      |
| Lenovo ThinkCentre M58 7360BB6     | 1        | 1%      |
| Inventec D CLASS                   | 1        | 1%      |
| Intel NCB-4210WG                   | 1        | 1%      |
| Intel DN2820FYK H24582-201         | 1        | 1%      |
| HP Z400 Workstation                | 1        | 1%      |
| HP Z240 SFF Workstation            | 1        | 1%      |
| HP ProLiant ML150 G6               | 1        | 1%      |
| HP ProLiant ML10 v2                | 1        | 1%      |
| HP prodesk 400 g2 sff business pc  | 1        | 1%      |
| HP EliteDesk 800 G2 DM 35W         | 1        | 1%      |
| HP EliteDesk 800 G1 SFF            | 1        | 1%      |
| HP EliteDesk 800 G1 DM             | 1        | 1%      |
| HARDKERNEL ODROID-H2               | 1        | 1%      |
| Gigabyte Z87N-WIFI                 | 1        | 1%      |
| Gigabyte Z77N-WIFI                 | 1        | 1%      |
| Gigabyte Z68MA-D2H-B3              | 1        | 1%      |
| Gigabyte J1900N-D3V                | 1        | 1%      |
| Gigabyte H81M-DS2                  | 1        | 1%      |
| Gigabyte H270N-WIFI                | 1        | 1%      |
| Gigabyte EP45-UD3R                 | 1        | 1%      |
| Gigabyte 970A-D3P                  | 1        | 1%      |
| Gateway DX4840                     | 1        | 1%      |
| Foxconn p6-2171a                   | 1        | 1%      |
| Dell Precision WorkStation T3500   | 1        | 1%      |
| Dell PowerEdge T40                 | 1        | 1%      |
| Dell OptiPlex 990                  | 1        | 1%      |
| Dell OptiPlex 7060                 | 1        | 1%      |
| Dell OptiPlex 390                  | 1        | 1%      |
| Dell OptiPlex 3040                 | 1        | 1%      |
| Dell OptiPlex 3020                 | 1        | 1%      |
| Cisco SALEEN                       | 1        | 1%      |
| AZW GK55                           | 1        | 1%      |
| ASUS ROG STRIX Z390-F GAMING       | 1        | 1%      |
| ASUS ROG STRIX X570-F GAMING       | 1        | 1%      |
| ASUS PRIME H310M-K                 | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 10       | 10%     |
| Protectli FW4B                 | 7        | 7%      |
| HP ProLiant                    | 7        | 7%      |
| Unknown                        | 7        | 7%      |
| Lenovo ThinkCentre             | 5        | 5%      |
| HP EliteDesk                   | 3        | 3%      |
| Protectli VP2410               | 2        | 2%      |
| MW GMLK-2                      | 2        | 2%      |
| Intel Q3XXG4-P                 | 2        | 2%      |
| ASUS ROG                       | 2        | 2%      |
| ASUS PRIME                     | 2        | 2%      |
| ASUS All                       | 2        | 2%      |
| ASRock X370                    | 2        | 2%      |
| Acer Veriton                   | 2        | 2%      |
| Yanling YL-KBR6L               | 1        | 1%      |
| Shuttle DH370                  | 1        | 1%      |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1%      |
| SeeedStudio ODYSSEY-X86J4125   | 1        | 1%      |
| Radxa ROCK                     | 1        | 1%      |
| Protectli FW6                  | 1        | 1%      |
| Protectli FW2B                 | 1        | 1%      |
| PC Engines apu4                | 1        | 1%      |
| MSI Pro                        | 1        | 1%      |
| MSI MS-7C95                    | 1        | 1%      |
| MSI CML-U                      | 1        | 1%      |
| Inventec D                     | 1        | 1%      |
| Intel NCB-4210WG               | 1        | 1%      |
| Intel DN2820FYK                | 1        | 1%      |
| HP Z400                        | 1        | 1%      |
| HP Z240                        | 1        | 1%      |
| HP prodesk                     | 1        | 1%      |
| HARDKERNEL ODROID-H2           | 1        | 1%      |
| Gigabyte Z87N-WIFI             | 1        | 1%      |
| Gigabyte Z77N-WIFI             | 1        | 1%      |
| Gigabyte Z68MA-D2H-B3          | 1        | 1%      |
| Gigabyte J1900N-D3V            | 1        | 1%      |
| Gigabyte H81M-DS2              | 1        | 1%      |
| Gigabyte H270N-WIFI            | 1        | 1%      |
| Gigabyte EP45-UD3R             | 1        | 1%      |
| Gigabyte 970A-D3P              | 1        | 1%      |
| Gateway DX4840                 | 1        | 1%      |
| Foxconn p6-2171a               | 1        | 1%      |
| Dell Precision                 | 1        | 1%      |
| Dell PowerEdge                 | 1        | 1%      |
| Cisco SALEEN                   | 1        | 1%      |
| AZW GK55                       | 1        | 1%      |
| ASUS P8H61-M                   | 1        | 1%      |
| ASUS P5E3                      | 1        | 1%      |
| ASUS P10S                      | 1        | 1%      |
| ASUS B75M-PLUS                 | 1        | 1%      |
| ASRock Z390                    | 1        | 1%      |
| ASRock B560M                   | 1        | 1%      |
| ASRock B365M                   | 1        | 1%      |
| ASRock A320M-HDV               | 1        | 1%      |
| ASRock 990FX                   | 1        | 1%      |
| ASRock 970                     | 1        | 1%      |
| AOpen DE3250                   | 1        | 1%      |
| ADI Engineering RCC-VE         | 1        | 1%      |
| AAEON AEC-6646                 | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 14       | 14%     |
| 2013    | 12       | 12%     |
| 2020    | 11       | 11%     |
| 2018    | 10       | 10%     |
| 2021    | 9        | 9%      |
| 2016    | 8        | 8%      |
| 2011    | 7        | 7%      |
| 2012    | 6        | 6%      |
| 2017    | 5        | 5%      |
| 2015    | 5        | 5%      |
| 2014    | 5        | 5%      |
| 2009    | 4        | 4%      |
| 2010    | 2        | 2%      |
| Unknown | 2        | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 100      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 95       | 95%     |
| Yes  | 5        | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 51       | 49.51%  |
| 16.01-24.0  | 22       | 21.36%  |
| 4.01-8.0    | 16       | 15.53%  |
| 32.01-64.0  | 7        | 6.8%    |
| 24.01-32.0  | 3        | 2.91%   |
| 2.01-3.0    | 2        | 1.94%   |
| 64.01-256.0 | 2        | 1.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 56       | 53.33%  |
| 0.51-1.0   | 28       | 26.67%  |
| 1.01-2.0   | 7        | 6.67%   |
| 4.01-8.0   | 5        | 4.76%   |
| 3.01-4.0   | 2        | 1.9%    |
| 16.01-24.0 | 2        | 1.9%    |
| 8.01-16.0  | 2        | 1.9%    |
| 32.01-64.0 | 1        | 0.95%   |
| 2.01-3.0   | 1        | 0.95%   |
| Unknown    | 1        | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 60.78%  |
| 2      | 13       | 12.75%  |
| 3      | 9        | 8.82%   |
| 0      | 9        | 8.82%   |
| 4      | 4        | 3.92%   |
| 5      | 2        | 1.96%   |
| 10     | 1        | 0.98%   |
| 7      | 1        | 0.98%   |
| 6      | 1        | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 78%     |
| Yes       | 22       | 22%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 99       | 99%     |
| No        | 1        | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 78.22%  |
| Yes       | 22       | 21.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 88.12%  |
| Yes       | 12       | 11.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 100      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 27       | 25%     |
| Melbourne      | 16       | 14.81%  |
| Perth          | 13       | 12.04%  |
| Brisbane       | 13       | 12.04%  |
| Adelaide       | 3        | 2.78%   |
| Marrickville   | 2        | 1.85%   |
| Hobart         | 2        | 1.85%   |
| Canberra       | 2        | 1.85%   |
| Wollongong     | 1        | 0.93%   |
| Wheelers Hill  | 1        | 0.93%   |
| Wallan         | 1        | 0.93%   |
| Townsville     | 1        | 0.93%   |
| Southport      | 1        | 0.93%   |
| Shell Cove     | 1        | 0.93%   |
| Ryde           | 1        | 0.93%   |
| Rosanna        | 1        | 0.93%   |
| Ringwood       | 1        | 0.93%   |
| North Shore    | 1        | 0.93%   |
| Noble Park     | 1        | 0.93%   |
| Mount Waverley | 1        | 0.93%   |
| Mooroolbark    | 1        | 0.93%   |
| Malvern        | 1        | 0.93%   |
| Kurunjang      | 1        | 0.93%   |
| Kellyville     | 1        | 0.93%   |
| Ipswich        | 1        | 0.93%   |
| Gold Coast     | 1        | 0.93%   |
| Geelong        | 1        | 0.93%   |
| Engadine       | 1        | 0.93%   |
| East Malvern   | 1        | 0.93%   |
| Dowerin        | 1        | 0.93%   |
| Dandenong      | 1        | 0.93%   |
| Corio          | 1        | 0.93%   |
| Brunswick      | 1        | 0.93%   |
| Blackburn      | 1        | 0.93%   |
| Bayswater      | 1        | 0.93%   |
| Balwyn North   | 1        | 0.93%   |
| Ashfield       | 1        | 0.93%   |
| Ascot Vale     | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 18.4%   |
| WDC                 | 19       | 54     | 15.2%   |
| Samsung Electronics | 19       | 29     | 15.2%   |
| Kingston            | 9        | 16     | 7.2%    |
| Intel               | 7        | 13     | 5.6%    |
| Hoodisk             | 6        | 10     | 4.8%    |
| Toshiba             | 5        | 9      | 4%      |
| Crucial             | 5        | 5      | 4%      |
| SanDisk             | 4        | 6      | 3.2%    |
| Protectli           | 3        | 3      | 2.4%    |
| Hewlett-Packard     | 3        | 6      | 2.4%    |
| Phison              | 2        | 2      | 1.6%    |
| Gigabyte Technology | 2        | 2      | 1.6%    |
| A-DATA Technology   | 2        | 7      | 1.6%    |
| XUNZHE              | 1        | 1      | 0.8%    |
| Vaseky              | 1        | 1      | 0.8%    |
| Transcend           | 1        | 1      | 0.8%    |
| SPCC                | 1        | 5      | 0.8%    |
| Plextor             | 1        | 1      | 0.8%    |
| Patriot             | 1        | 1      | 0.8%    |
| Micron Technology   | 1        | 2      | 0.8%    |
| Maxtor              | 1        | 1      | 0.8%    |
| LITEONIT            | 1        | 1      | 0.8%    |
| KingSpec            | 1        | 1      | 0.8%    |
| KingDian            | 1        | 1      | 0.8%    |
| Hitachi             | 1        | 1      | 0.8%    |
| HGST                | 1        | 1      | 0.8%    |
| Fordisk             | 1        | 1      | 0.8%    |
| China               | 1        | 1      | 0.8%    |
| BIWIN               | 1        | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Hoodisk SSD 128GB                    | 6        | 4.23%   |
| Kingston SA400S37120G 120GB          | 3        | 2.11%   |
| WDC WD40EFRX-68N32N0 4TB             | 2        | 1.41%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2        | 1.41%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 1.41%   |
| WDC WD20EZAZ-00GGJB0 2TB             | 2        | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB      | 2        | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 1.41%   |
| Samsung SSD 850 EVO 500GB            | 2        | 1.41%   |
| Samsung SSD 840 EVO 120GB            | 2        | 1.41%   |
| Samsung MZ7LN128HCHP-000H1 128GB     | 2        | 1.41%   |
| Protectli 120GB mSATA                | 2        | 1.41%   |
| Kingston SA400S37480G 480GB          | 2        | 1.41%   |
| Crucial CT250MX500SSD1 250GB         | 2        | 1.41%   |
| XUNZHE MSATA 128GB                   | 1        | 0.7%    |
| WDC WDS500G1R0B-68A4Z0 500GB         | 1        | 0.7%    |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 0.7%    |
| WDC WDS250G2B0A-00SM50 250GB         | 1        | 0.7%    |
| WDC WDS240G2G0B-00EPW0 240GB         | 1        | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB         | 1        | 0.7%    |
| WDC WD80EFAX-68KNBN0 8TB             | 1        | 0.7%    |
| WDC WD7500BPKX-00HPJT0 752GB         | 1        | 0.7%    |
| WDC WD5000BPKT-00PK4T0 500GB         | 1        | 0.7%    |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.7%    |
| WDC WD40EFRX-68WT0N0 4TB             | 1        | 0.7%    |
| WDC WD4000AAKS-00TMA0 400GB          | 1        | 0.7%    |
| WDC WD30EFRX-68AX9N0 3TB             | 1        | 0.7%    |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.7%    |
| WDC WD20EARX-008FB0 2TB              | 1        | 0.7%    |
| WDC WD20EARS-00MVWB0 2TB             | 1        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.7%    |
| WDC WD10EURX-63UY4Y0 1TB             | 1        | 0.7%    |
| WDC WD10EARX-00N0YB0 1TB             | 1        | 0.7%    |
| WDC WD10EADS-00P8B0 1TB              | 1        | 0.7%    |
| Vaseky V850-64G                      | 1        | 0.7%    |
| Transcend TS16EPTMM1600L 16GB        | 1        | 0.7%    |
| Toshiba THNSNJ128GMCU 128GB          | 1        | 0.7%    |
| Toshiba MQ04UBF100 1TB               | 1        | 0.7%    |
| Toshiba MQ04UBD200 2TB               | 1        | 0.7%    |
| Toshiba MQ03UBB200 2TB               | 1        | 0.7%    |
| Toshiba MQ01UBB200 2TB               | 1        | 0.7%    |
| Toshiba MQ01ABD100 1TB               | 1        | 0.7%    |
| Toshiba DT01ACA200 2TB               | 1        | 0.7%    |
| SPCC M.2 PCIe SSD 256GB              | 1        | 0.7%    |
| Seagate ST9500325AS 500GB            | 1        | 0.7%    |
| Seagate ST9250410ASG 250GB           | 1        | 0.7%    |
| Seagate ST9250410AS 250GB            | 1        | 0.7%    |
| Seagate ST8000DM004-2CX188 8TB       | 1        | 0.7%    |
| Seagate ST500LT012-1DG142 500GB      | 1        | 0.7%    |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 0.7%    |
| Seagate ST500DM002-1BD142 500GB      | 1        | 0.7%    |
| Seagate ST4000NM0035-1V4107 4TB      | 1        | 0.7%    |
| Seagate ST4000NM0035 4TB             | 1        | 0.7%    |
| Seagate ST4000LM024-2AN17V 4TB       | 1        | 0.7%    |
| Seagate ST3320620AS 320GB            | 1        | 0.7%    |
| Seagate ST3250310AS 250GB            | 1        | 0.7%    |
| Seagate ST31000528AS 1TB             | 1        | 0.7%    |
| Seagate ST31000524AS 1TB             | 1        | 0.7%    |
| Seagate ST3000NM0005-1V410N 3TB      | 1        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 23       | 30     | 44.23%  |
| WDC                 | 16       | 48     | 30.77%  |
| Toshiba             | 4        | 6      | 7.69%   |
| Samsung Electronics | 3        | 5      | 5.77%   |
| Hewlett-Packard     | 3        | 6      | 5.77%   |
| Maxtor              | 1        | 1      | 1.92%   |
| Hitachi             | 1        | 1      | 1.92%   |
| HGST                | 1        | 1      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 22     | 22.95%  |
| Kingston            | 9        | 16     | 14.75%  |
| Intel               | 6        | 12     | 9.84%   |
| Hoodisk             | 6        | 10     | 9.84%   |
| SanDisk             | 4        | 6      | 6.56%   |
| WDC                 | 3        | 5      | 4.92%   |
| Protectli           | 3        | 3      | 4.92%   |
| Crucial             | 3        | 3      | 4.92%   |
| XUNZHE              | 1        | 1      | 1.64%   |
| Vaseky              | 1        | 1      | 1.64%   |
| Transcend           | 1        | 1      | 1.64%   |
| Toshiba             | 1        | 3      | 1.64%   |
| Plextor             | 1        | 1      | 1.64%   |
| Phison              | 1        | 1      | 1.64%   |
| Patriot             | 1        | 1      | 1.64%   |
| Micron Technology   | 1        | 2      | 1.64%   |
| LITEONIT            | 1        | 1      | 1.64%   |
| KingSpec            | 1        | 1      | 1.64%   |
| KingDian            | 1        | 1      | 1.64%   |
| Fordisk             | 1        | 1      | 1.64%   |
| China               | 1        | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 57       | 93     | 52.29%  |
| HDD  | 40       | 98     | 36.7%   |
| NVMe | 12       | 22     | 11.01%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 86       | 191    | 87.76%  |
| NVMe | 12       | 22     | 12.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 71       | 120    | 68.93%  |
| 0.51-1.0   | 13       | 22     | 12.62%  |
| 1.01-2.0   | 10       | 25     | 9.71%   |
| 3.01-4.0   | 4        | 9      | 3.88%   |
| 2.01-3.0   | 2        | 8      | 1.94%   |
| 4.01-10.0  | 2        | 5      | 1.94%   |
| 10.01-20.0 | 1        | 2      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 46       | 46%     |
| 251-500    | 14       | 14%     |
| 1-20       | 13       | 13%     |
| 501-1000   | 9        | 9%      |
| 51-100     | 9        | 9%      |
| 21-50      | 5        | 5%      |
| 2001-3000  | 2        | 2%      |
| 1001-2000  | 2        | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 94       | 91.26%  |
| 21-50     | 6        | 5.83%   |
| 101-250   | 1        | 0.97%   |
| 1001-2000 | 1        | 0.97%   |
| 51-100    | 1        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 7.69%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 2      | 7.69%   |
| WDC WD20EARX-008FB0 2TB           | 1        | 3      | 7.69%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 7.69%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 7.69%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 7.69%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 1      | 7.69%   |
| SanDisk SDSSDA240G 240GB          | 1        | 1      | 7.69%   |
| Samsung Electronics HM500LI 500GB | 1        | 2      | 7.69%   |
| Hitachi HDS721010KLA330 1TB       | 1        | 1      | 7.69%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 41.67%  |
| WDC                 | 3        | 7      | 25%     |
| SanDisk             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 2      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| Hewlett-Packard     | 1        | 1      | 8.33%   |

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
| HDD  | 10       | 15     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 85       | 196    | 87.63%  |
| Malfunc | 12       | 17     | 12.37%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 84       | 70.59%  |
| AMD                       | 16       | 13.45%  |
| Phison Electronics        | 4        | 3.36%   |
| Samsung Electronics       | 2        | 1.68%   |
| Micron/Crucial Technology | 2        | 1.68%   |
| Broadcom / LSI            | 2        | 1.68%   |
| Silicon Motion            | 1        | 0.84%   |
| Silicon Image             | 1        | 0.84%   |
| SanDisk                   | 1        | 0.84%   |
| Realtek Semiconductor     | 1        | 0.84%   |
| QLogic                    | 1        | 0.84%   |
| JMicron Technology        | 1        | 0.84%   |
| Hewlett-Packard           | 1        | 0.84%   |
| ADATA Technology          | 1        | 0.84%   |
| Adaptec                   | 1        | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 8.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 8.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 10       | 7.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 5.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 5.11%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 7        | 5.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 4.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 4.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.92%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 2.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.19%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.19%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.46%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 2        | 1.46%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.46%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.73%   |
| Silicon Image AAR-1220SA Serial ATA HostRAID Controller                                 | 1        | 0.73%   |
| SanDisk unknown                                                                         | 1        | 0.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.73%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                             | 1        | 0.73%   |
| Phison NVMe Storage Controller                                                          | 1        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.73%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.73%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 1        | 0.73%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 1        | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.73%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.73%   |
| HP Smart Array G6 controllers                                                           | 1        | 0.73%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.73%   |
| AMD FCH IDE Controller                                                                  | 1        | 0.73%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.73%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.73%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 0.73%   |
| Unknown                                                                                 | 1        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 93       | 73.23%  |
| IDE  | 13       | 10.24%  |
| NVMe | 12       | 9.45%   |
| RAID | 5        | 3.94%   |
| SAS  | 2        | 1.57%   |
| SCSI | 2        | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 84       | 84%     |
| AMD    | 16       | 16%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 9        | 8.91%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 6        | 5.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.97%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2        | 1.98%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.98%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 1.98%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 1.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.98%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 1.98%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 1.98%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 0.99%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.99%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 0.99%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.99%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 0.99%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.99%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 0.99%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 0.99%   |
| Intel Xeon                                  | 1        | 0.99%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.99%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1        | 0.99%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.99%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 0.99%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.99%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.99%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.99%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 0.99%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1        | 0.99%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.99%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 0.99%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.99%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GH             | 1        | 0.99%   |
| Intel Core i5-2500 CPU                      | 1        | 0.99%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.99%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 0.99%   |
| Intel Core i3-7167U CPU @ 2.80GHz           | 1        | 0.99%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1        | 0.99%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 0.99%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GH             | 1        | 0.99%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1        | 0.99%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 0.99%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 0.99%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 0.99%   |
| Intel Core 2 Quad CPU Q6600 @               | 1        | 0.99%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1        | 0.99%   |
| Intel Celeron CPU N2930 @ 1.83GHz           | 1        | 0.99%   |
| Intel Celeron CPU N2820 @ 2.13GHz           | 1        | 0.99%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 0.99%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 1        | 0.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 25       | 24.75%  |
| Intel Core i5           | 23       | 22.77%  |
| Intel Xeon              | 11       | 10.89%  |
| Intel Core i3           | 11       | 10.89%  |
| Intel Core i7           | 6        | 5.94%   |
| Intel Pentium           | 4        | 3.96%   |
| AMD Turion II Neo       | 3        | 2.97%   |
| AMD Ryzen 5             | 3        | 2.97%   |
| AMD Ryzen 3             | 3        | 2.97%   |
| AMD FX                  | 3        | 2.97%   |
| Intel Core 2 Quad       | 2        | 1.98%   |
| Intel Atom              | 2        | 1.98%   |
| Intel Pentium Dual-Core | 1        | 0.99%   |
| AMD GX                  | 1        | 0.99%   |
| AMD G                   | 1        | 0.99%   |
| AMD E2                  | 1        | 0.99%   |
| AMD Athlon              | 1        | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 55       | 54.46%  |
| 2       | 28       | 27.72%  |
| 8       | 9        | 8.91%   |
| 6       | 5        | 4.95%   |
| 12      | 2        | 1.98%   |
| Unknown | 2        | 1.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 98%     |
| 2      | 2        | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 74       | 73.27%  |
| 2       | 25       | 24.75%  |
| Unknown | 2        | 1.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 15       | 15%     |
| Haswell       | 12       | 12%     |
| KabyLake      | 11       | 11%     |
| IvyBridge     | 9        | 9%      |
| SandyBridge   | 8        | 8%      |
| Skylake       | 7        | 7%      |
| Goldmont plus | 7        | 7%      |
| Nehalem       | 4        | 4%      |
| Westmere      | 3        | 3%      |
| Piledriver    | 3        | 3%      |
| K10           | 3        | 3%      |
| Broadwell     | 3        | 3%      |
| Zen 2         | 2        | 2%      |
| Zen           | 2        | 2%      |
| Penryn        | 2        | 2%      |
| Bobcat        | 2        | 2%      |
| Zen+          | 1        | 1%      |
| Zen 3         | 1        | 1%      |
| Puma          | 1        | 1%      |
| Jaguar        | 1        | 1%      |
| Goldmont      | 1        | 1%      |
| Core          | 1        | 1%      |
| CometLake     | 1        | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 64       | 63.37%  |
| AMD                        | 16       | 15.84%  |
| Nvidia                     | 14       | 13.86%  |
| Matrox Electronics Systems | 5        | 4.95%   |
| Tseng Labs                 | 1        | 0.99%   |
| ASPEED Technology          | 1        | 0.99%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11       | 10.68%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 8.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 6.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 5.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 5.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 4.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 2.91%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3        | 2.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.94%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 1.94%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 1.94%   |
| Intel UHD Graphics 620                                                                   | 2        | 1.94%   |
| Intel HD Graphics 530                                                                    | 2        | 1.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 1.94%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 0.97%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.97%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 0.97%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 0.97%   |
| Nvidia GF100GL [Quadro 4000]                                                             | 1        | 0.97%   |
| Nvidia G92 [GeForce GT 330]                                                              | 1        | 0.97%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 0.97%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.97%   |
| Intel Iris Plus Graphics 650                                                             | 1        | 0.97%   |
| Intel HD Graphics P530                                                                   | 1        | 0.97%   |
| Intel HD Graphics 610                                                                    | 1        | 0.97%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.97%   |
| Intel HD Graphics 510                                                                    | 1        | 0.97%   |
| Intel HD Graphics 500                                                                    | 1        | 0.97%   |
| Intel HD Graphics                                                                        | 1        | 0.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 0.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 0.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 0.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 0.97%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 0.97%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1        | 0.97%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 0.97%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 0.97%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1        | 0.97%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1        | 0.97%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 0.97%   |
| AMD Cezanne                                                                              | 1        | 0.97%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                                            | 1        | 0.97%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 1        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 60       | 58.82%  |
| 1 x AMD        | 15       | 14.71%  |
| 1 x Nvidia     | 12       | 11.76%  |
| 1 x Matrox     | 5        | 4.9%    |
| Other          | 3        | 2.94%   |
| Intel + Nvidia | 2        | 1.96%   |
| 2 x Intel      | 1        | 0.98%   |
| 2 x AMD        | 1        | 0.98%   |
| 1 x Tseng Labs | 1        | 0.98%   |
| Intel + AMD    | 1        | 0.98%   |
| 1 x ASPEED     | 1        | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 91       | 91%     |
| Proprietary | 6        | 6%      |
| Unknown     | 3        | 3%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 88.12%  |
| 1.01-2.0   | 6        | 5.94%   |
| 0.51-1.0   | 3        | 2.97%   |
| 7.01-8.0   | 2        | 1.98%   |
| 3.01-4.0   | 1        | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 14.29%  |
| Samsung Electronics | 2        | 9.52%   |
| Philips             | 2        | 9.52%   |
| Hewlett-Packard     | 2        | 9.52%   |
| ASUSTek Computer    | 2        | 9.52%   |
| AOC                 | 2        | 9.52%   |
| Acer                | 2        | 9.52%   |
| ___                 | 1        | 4.76%   |
| ViewSonic           | 1        | 4.76%   |
| Toshiba             | 1        | 4.76%   |
| Goldstar            | 1        | 4.76%   |
| Compal              | 1        | 4.76%   |
| BenQ                | 1        | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2        | 9.09%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 4.55%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1        | 4.55%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1        | 4.55%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1        | 4.55%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1        | 4.55%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 4.55%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 4.55%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1        | 4.55%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1        | 4.55%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1        | 4.55%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1        | 4.55%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1        | 4.55%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1        | 4.55%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1        | 4.55%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1        | 4.55%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 4.55%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1        | 4.55%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1        | 4.55%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1        | 4.55%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 57.14%  |
| 2560x1440 (QHD)    | 4        | 19.05%  |
| 3840x1600          | 1        | 4.76%   |
| 2560x1080          | 1        | 4.76%   |
| 2048x1152          | 1        | 4.76%   |
| 1920x1200 (WUXGA)  | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 28.57%  |
| 24      | 4        | 19.05%  |
| 23      | 3        | 14.29%  |
| 21      | 2        | 9.52%   |
| 47      | 1        | 4.76%   |
| 37      | 1        | 4.76%   |
| 31      | 1        | 4.76%   |
| 28      | 1        | 4.76%   |
| 22      | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 61.9%   |
| 401-500     | 3        | 14.29%  |
| 601-700     | 2        | 9.52%   |
| 801-900     | 1        | 4.76%   |
| 1001-1500   | 1        | 4.76%   |
| Unknown     | 1        | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 17       | 80.95%  |
| 21/9  | 2        | 9.52%   |
| 16/10 | 2        | 9.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 42.86%  |
| 301-350        | 6        | 28.57%  |
| 251-300        | 2        | 9.52%   |
| 501-1000       | 2        | 9.52%   |
| 351-500        | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 57.14%  |
| 101-120 | 7        | 33.33%  |
| 1-50    | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 79       | 79%     |
| 1     | 20       | 20%     |
| 2     | 1        | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 68       | 51.52%  |
| Realtek Semiconductor    | 38       | 28.79%  |
| Broadcom                 | 12       | 9.09%   |
| Qualcomm Atheros         | 4        | 3.03%   |
| U-Blox                   | 2        | 1.52%   |
| TP-Link                  | 1        | 0.76%   |
| Seeed Technology         | 1        | 0.76%   |
| Ralink Technology        | 1        | 0.76%   |
| Ralink                   | 1        | 0.76%   |
| Marvell Technology Group | 1        | 0.76%   |
| IMC Networks             | 1        | 0.76%   |
| D-Link System            | 1        | 0.76%   |
| Aquantia                 | 1        | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 34       | 21.79%  |
| Intel I211 Gigabit Network Connection                                         | 20       | 12.82%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 5.77%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.85%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.21%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 3.21%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.56%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 2.56%   |
| Intel Wireless 7260                                                           | 3        | 1.92%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 1.92%   |
| U-Blox [u-blox 7]                                                             | 2        | 1.28%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 1.28%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.28%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.28%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.28%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.28%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 1.28%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.28%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.64%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.64%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.64%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1        | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.64%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.64%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.64%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.64%   |
| Intel Wireless 8260                                                           | 1        | 0.64%   |
| Intel Wireless 3165                                                           | 1        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 0.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 0.64%   |
| Intel Ethernet Controller X550                                                | 1        | 0.64%   |
| Intel Ethernet Connection I354                                                | 1        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.64%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.64%   |
| Intel DH8900CC Null Device                                                    | 1        | 0.64%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.64%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.64%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.64%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 0.64%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.64%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.64%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.64%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 47.83%  |
| Realtek Semiconductor | 5        | 21.74%  |
| Qualcomm Atheros      | 3        | 13.04%  |
| TP-Link               | 1        | 4.35%   |
| Ralink Technology     | 1        | 4.35%   |
| Ralink                | 1        | 4.35%   |
| IMC Networks          | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                            | 3        | 13.04%  |
| Intel Wireless 8265 / 8275                                     | 2        | 8.7%    |
| Intel Centrino Wireless-N 2230                                 | 2        | 8.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 4.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 4.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 4.35%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 4.35%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 4.35%   |
| Ralink RT5572 Wireless Adapter                                 | 1        | 4.35%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 4.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 4.35%   |
| Intel Wireless 8260                                            | 1        | 4.35%   |
| Intel Wireless 3165                                            | 1        | 4.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 4.35%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 4.35%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 64       | 54.7%   |
| Realtek Semiconductor    | 36       | 30.77%  |
| Broadcom                 | 12       | 10.26%  |
| Qualcomm Atheros         | 2        | 1.71%   |
| Marvell Technology Group | 1        | 0.85%   |
| D-Link System            | 1        | 0.85%   |
| Aquantia                 | 1        | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 34       | 26.36%  |
| Intel I211 Gigabit Network Connection                                         | 20       | 15.5%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 6.98%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.65%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.88%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 3.88%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 3.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 2.33%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.55%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.55%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 1.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.55%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.78%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.78%   |
| Intel Ethernet Controller X550                                                | 1        | 0.78%   |
| Intel Ethernet Connection I354                                                | 1        | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.78%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.78%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.78%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.78%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.78%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.78%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 99       | 79.2%   |
| WiFi     | 22       | 17.6%   |
| Modem    | 3        | 2.4%    |
| Unknown  | 1        | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 98       | 91.59%  |
| WiFi     | 9        | 8.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 33       | 32.35%  |
| 1     | 23       | 22.55%  |
| 4     | 19       | 18.63%  |
| 3     | 13       | 12.75%  |
| 6     | 7        | 6.86%   |
| 5     | 4        | 3.92%   |
| 7     | 2        | 1.96%   |
| 9     | 1        | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 86.54%  |
| Yes  | 14       | 13.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 75%     |
| Cambridge Silicon Radio | 2        | 16.67%  |
| Broadcom                | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 5        | 41.67%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 16.67%  |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 68       | 69.39%  |
| AMD                | 15       | 15.31%  |
| Nvidia             | 12       | 12.24%  |
| Texas Instruments  | 1        | 1.02%   |
| Logitech           | 1        | 1.02%   |
| Focusrite-Novation | 1        | 1.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11       | 9.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 8.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 6.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 5.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5        | 4.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 4.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 3.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 3.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 2.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.5%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.67%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.67%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.83%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1        | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.83%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.83%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1        | 0.83%   |
| Logitech Headset H390                                                                             | 1        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.83%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.83%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.83%   |
| Focusrite-Novation Scarlett Solo USB                                                              | 1        | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 0.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 0.83%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1        | 0.83%   |
| AMD FCH Azalia Controller                                                                         | 1        | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1        | 0.83%   |
| Unknown                                                                                           | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 19       | 16.96%  |
| Samsung Electronics | 18       | 16.07%  |
| Unknown             | 12       | 10.71%  |
| Micron Technology   | 12       | 10.71%  |
| SK hynix            | 10       | 8.93%   |
| Corsair             | 8        | 7.14%   |
| Crucial             | 7        | 6.25%   |
| G.Skill             | 5        | 4.46%   |
| Unknown             | 3        | 2.68%   |
| Unknown (ABCD)      | 2        | 1.79%   |
| Transcend           | 2        | 1.79%   |
| Team                | 2        | 1.79%   |
| Apacer              | 2        | 1.79%   |
| Smart Modular       | 1        | 0.89%   |
| Ramaxel Technology  | 1        | 0.89%   |
| PNY                 | 1        | 0.89%   |
| Patriot             | 1        | 0.89%   |
| Nanya Technology    | 1        | 0.89%   |
| Kingmax             | 1        | 0.89%   |
| Innodisk            | 1        | 0.89%   |
| Hewlett-Packard     | 1        | 0.89%   |
| GeIL                | 1        | 0.89%   |
| Elpida              | 1        | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3        | 2.54%   |
| Unknown                                                           | 3        | 2.54%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2        | 1.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2        | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 2        | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2        | 1.69%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2        | 1.69%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 1.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2        | 1.69%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 1.69%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2        | 1.69%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2        | 1.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.85%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 0.85%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.85%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.85%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.85%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1        | 0.85%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1        | 0.85%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1        | 0.85%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.85%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.85%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s               | 1        | 0.85%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.85%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.85%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.85%   |
| SK hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1        | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 0.85%   |
| Samsung RAM M471B1G73DH0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 0.85%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s             | 1        | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 1        | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 1        | 0.85%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s             | 1        | 0.85%   |
| Samsung RAM M391B5673EH1-CF8 2GB DIMM DDR3 1066MT/s               | 1        | 0.85%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1        | 0.85%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1333MT/s               | 1        | 0.85%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.85%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.85%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2666MT/s               | 1        | 0.85%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s             | 1        | 0.85%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s            | 1        | 0.85%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                    | 1        | 0.85%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                | 1        | 0.85%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s             | 1        | 0.85%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s              | 1        | 0.85%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s             | 1        | 0.85%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s               | 1        | 0.85%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s               | 1        | 0.85%   |
| Micron RAM 18JSF25672AZ-1G1F1 2GB DIMM DDR3 1066MT/s              | 1        | 0.85%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s            | 1        | 0.85%   |
| Micron RAM 18ASF1G72AZ-2G1B1 8GB DIMM DDR4 2133MT/s               | 1        | 0.85%   |
| Micron RAM 16ATF4G64HZ-2G6E1 32GB SODIMM DDR4 2667MT/s            | 1        | 0.85%   |
| Kingston RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1        | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 55       | 57.89%  |
| DDR4    | 29       | 30.53%  |
| Unknown | 7        | 7.37%   |
| LPDDR4  | 2        | 2.11%   |
| DDR2    | 1        | 1.05%   |
| DDR     | 1        | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 68       | 72.34%  |
| SODIMM  | 22       | 23.4%   |
| Unknown | 3        | 3.19%   |
| RIMM    | 1        | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 42.57%  |
| 4096  | 31       | 30.69%  |
| 2048  | 14       | 13.86%  |
| 16384 | 10       | 9.9%    |
| 1024  | 2        | 1.98%   |
| 32768 | 1        | 0.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 37       | 37.37%  |
| 1333  | 21       | 21.21%  |
| 2400  | 12       | 12.12%  |
| 2133  | 9        | 9.09%   |
| 2667  | 7        | 7.07%   |
| 800   | 4        | 4.04%   |
| 1066  | 3        | 3.03%   |
| 2666  | 2        | 2.02%   |
| 59392 | 1        | 1.01%   |
| 3600  | 1        | 1.01%   |
| 3200  | 1        | 1.01%   |
| 1867  | 1        | 1.01%   |

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

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 1     | 51       | 50.5%   |
| 0     | 39       | 38.61%  |
| 2     | 8        | 7.92%   |
| 5     | 1        | 0.99%   |
| 4     | 1        | 0.99%   |
| 3     | 1        | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 55       | 75.34%  |
| Bluetooth                | 5        | 6.85%   |
| Net/wireless             | 4        | 5.48%   |
| Firewire controller      | 3        | 4.11%   |
| Card reader              | 3        | 4.11%   |
| Sound                    | 2        | 2.74%   |
| Network                  | 1        | 1.37%   |

