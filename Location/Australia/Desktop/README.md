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

Total: 144

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OPNsense 22.1       | 8        | 6.84%   |
| OPNsense 21.7.7     | 5        | 4.27%   |
| OPNsense 21.7.2     | 5        | 4.27%   |
| OPNsense 21.1.4     | 5        | 4.27%   |
| OPNsense 20.7.8     | 5        | 4.27%   |
| OPNsense 22.1.4     | 4        | 3.42%   |
| OPNsense 21.7.3     | 4        | 3.42%   |
| OPNsense 21.1.5     | 4        | 3.42%   |
| OPNsense 21.1.2     | 4        | 3.42%   |
| OPNsense 21.1       | 4        | 3.42%   |
| helloSystem 0.5.0   | 4        | 3.42%   |
| OPNsense 22.1.6     | 3        | 2.56%   |
| OPNsense 21.7.4     | 3        | 2.56%   |
| OPNsense 21.7.1     | 3        | 2.56%   |
| OPNsense 21.1.8     | 3        | 2.56%   |
| OPNsense 21.1.6     | 3        | 2.56%   |
| OPNsense 21.1.3     | 3        | 2.56%   |
| OPNsense 21.1.1     | 3        | 2.56%   |
| helloSystem 0.6.0   | 3        | 2.56%   |
| FreeBSD 12.1-p10    | 3        | 2.56%   |
| OPNsense 21.7.5     | 2        | 1.71%   |
| helloSystem 0.7.0   | 2        | 1.71%   |
| GhostBSD 20.04.02   | 2        | 1.71%   |
| FreeBSD 13.0-STABLE | 2        | 1.71%   |
| FreeBSD 13.0-p4     | 2        | 1.71%   |
| FreeBSD 12.2        | 2        | 1.71%   |
| TrueNAS 12.2-p9     | 1        | 0.85%   |
| TrueNAS 12.2-p3     | 1        | 0.85%   |
| TrueNAS 12.2-p10    | 1        | 0.85%   |
| OPNsense 22.1.5     | 1        | 0.85%   |
| OPNsense 22.1.3     | 1        | 0.85%   |
| OPNsense 22.1.2     | 1        | 0.85%   |
| OPNsense 22.1.1     | 1        | 0.85%   |
| OPNsense 21.7.8     | 1        | 0.85%   |
| OPNsense 21.7.6     | 1        | 0.85%   |
| OPNsense 21.7       | 1        | 0.85%   |
| OPNsense 20.7       | 1        | 0.85%   |
| OPNsense 20.1.7     | 1        | 0.85%   |
| OpenBSD 6.8         | 1        | 0.85%   |
| NomadBSD 5806f915   | 1        | 0.85%   |
| NetBSD 9.99.94      | 1        | 0.85%   |
| helloSystem 0.4.0   | 1        | 0.85%   |
| GhostBSD 22.04.22   | 1        | 0.85%   |
| FreeNAS 11.4-p4     | 1        | 0.85%   |
| FreeNAS 11.3-p9     | 1        | 0.85%   |
| FreeBSD 13.0-RC1    | 1        | 0.85%   |
| FreeBSD 13.0-p5     | 1        | 0.85%   |
| FreeBSD 13.0-p3     | 1        | 0.85%   |
| FreeBSD 12.2-p11    | 1        | 0.85%   |
| FreeBSD 12.2-p10    | 1        | 0.85%   |
| FreeBSD 12.1-p12    | 1        | 0.85%   |
| FreeBSD 11.4        | 1        | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 56       | 62.92%  |
| FreeBSD     | 14       | 15.73%  |
| helloSystem | 9        | 10.11%  |
| TrueNAS     | 3        | 3.37%   |
| GhostBSD    | 2        | 2.25%   |
| FreeNAS     | 2        | 2.25%   |
| OpenBSD     | 1        | 1.12%   |
| NomadBSD    | 1        | 1.12%   |
| NetBSD      | 1        | 1.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 89       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 67       | 73.63%  |
| helloDesktop | 10       | 10.99%  |
| KDE5         | 4        | 4.4%    |
| XFCE         | 3        | 3.3%    |
| GNOME        | 2        | 2.2%    |
| TWM          | 1        | 1.1%    |
| Openbox      | 1        | 1.1%    |
| MATE         | 1        | 1.1%    |
| Lumina       | 1        | 1.1%    |
| i3           | 1        | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 70       | 78.65%  |
| X11     | 18       | 20.22%  |
| Wayland | 1        | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 71       | 79.78%  |
| SLiM    | 11       | 12.36%  |
| LightDM | 3        | 3.37%   |
| XDM     | 2        | 2.25%   |
| SDDM    | 2        | 2.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 63       | 70%     |
| en_US   | 15       | 16.67%  |
| en_AU   | 7        | 7.78%   |
| C       | 5        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 66       | 74.16%  |
| BIOS | 23       | 25.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 52       | 57.78%  |
| Zfs    | 35       | 38.89%  |
| Cd9660 | 2        | 2.22%   |
| Ffs    | 1        | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 79       | 88.76%  |
| MBR     | 9        | 10.11%  |
| Unknown | 1        | 1.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Hewlett-Packard            | 12       | 13.48%  |
| Dell                       | 11       | 12.36%  |
| Protectli                  | 10       | 11.24%  |
| ASUSTek Computer           | 8        | 8.99%   |
| ASRock                     | 8        | 8.99%   |
| Gigabyte Technology        | 7        | 7.87%   |
| Lenovo                     | 5        | 5.62%   |
| Unknown                    | 5        | 5.62%   |
| MSI                        | 3        | 3.37%   |
| Intel                      | 3        | 3.37%   |
| Acer                       | 2        | 2.25%   |
| Yanling                    | 1        | 1.12%   |
| Unknown                    | 1        | 1.12%   |
| Shuttle                    | 1        | 1.12%   |
| ShenZhen MinWin Technology | 1        | 1.12%   |
| SeeedStudio                | 1        | 1.12%   |
| Radxa                      | 1        | 1.12%   |
| PC Engines                 | 1        | 1.12%   |
| MW                         | 1        | 1.12%   |
| Inventec                   | 1        | 1.12%   |
| HARDKERNEL                 | 1        | 1.12%   |
| Gateway                    | 1        | 1.12%   |
| Foxconn                    | 1        | 1.12%   |
| Cisco                      | 1        | 1.12%   |
| ADI Engineering            | 1        | 1.12%   |
| AAEON                      | 1        | 1.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Protectli FW4B                     | 7        | 7.87%   |
| Unknown                            | 6        | 6.74%   |
| HP ProLiant MicroServer            | 3        | 3.37%   |
| Dell OptiPlex 9020                 | 3        | 3.37%   |
| HP ProLiant MicroServer Gen8       | 2        | 2.25%   |
| Dell OptiPlex 3010                 | 2        | 2.25%   |
| ASUS All Series                    | 2        | 2.25%   |
| Yanling YL-KBR6L                   | 1        | 1.12%   |
| Shuttle DH370                      | 1        | 1.12%   |
| ShenZhen MinWin MW-NANO-APL-4L     | 1        | 1.12%   |
| SeeedStudio ODYSSEY-X86J4125       | 1        | 1.12%   |
| Radxa ROCK Pi X                    | 1        | 1.12%   |
| Protectli VP2410                   | 1        | 1.12%   |
| Protectli FW6                      | 1        | 1.12%   |
| Protectli FW2B                     | 1        | 1.12%   |
| PC Engines apu4                    | 1        | 1.12%   |
| MW GMLK-2_5G4L                     | 1        | 1.12%   |
| MSI Pro 3130 Small Form Factor PC  | 1        | 1.12%   |
| MSI MS-7C95                        | 1        | 1.12%   |
| MSI CML-U PRO Cubi 5 (MS-B183)     | 1        | 1.12%   |
| Lenovo ThinkCentre M93p 10AAS3UM00 | 1        | 1.12%   |
| Lenovo ThinkCentre M92p 3238CE1    | 1        | 1.12%   |
| Lenovo ThinkCentre M73 10AY009MAU  | 1        | 1.12%   |
| Lenovo ThinkCentre M700 10HY002XAU | 1        | 1.12%   |
| Lenovo ThinkCentre M58 7360BB6     | 1        | 1.12%   |
| Inventec D CLASS                   | 1        | 1.12%   |
| Intel Q3XXG4-P V1.0                | 1        | 1.12%   |
| Intel NCB-4210WG                   | 1        | 1.12%   |
| Intel DN2820FYK H24582-201         | 1        | 1.12%   |
| HP Z400 Workstation                | 1        | 1.12%   |
| HP Z240 SFF Workstation            | 1        | 1.12%   |
| HP ProLiant ML150 G6               | 1        | 1.12%   |
| HP ProLiant ML10 v2                | 1        | 1.12%   |
| HP prodesk 400 g2 sff business pc  | 1        | 1.12%   |
| HP EliteDesk 800 G1 SFF            | 1        | 1.12%   |
| HP EliteDesk 800 G1 DM             | 1        | 1.12%   |
| HARDKERNEL ODROID-H2               | 1        | 1.12%   |
| Gigabyte Z87N-WIFI                 | 1        | 1.12%   |
| Gigabyte Z77N-WIFI                 | 1        | 1.12%   |
| Gigabyte Z68MA-D2H-B3              | 1        | 1.12%   |
| Gigabyte J1900N-D3V                | 1        | 1.12%   |
| Gigabyte H270N-WIFI                | 1        | 1.12%   |
| Gigabyte EP45-UD3R                 | 1        | 1.12%   |
| Gigabyte 970A-D3P                  | 1        | 1.12%   |
| Gateway DX4840                     | 1        | 1.12%   |
| Foxconn p6-2171a                   | 1        | 1.12%   |
| Dell Precision WorkStation T3500   | 1        | 1.12%   |
| Dell PowerEdge T40                 | 1        | 1.12%   |
| Dell OptiPlex 990                  | 1        | 1.12%   |
| Dell OptiPlex 7060                 | 1        | 1.12%   |
| Dell OptiPlex 390                  | 1        | 1.12%   |
| Dell OptiPlex 3020                 | 1        | 1.12%   |
| Cisco SALEEN                       | 1        | 1.12%   |
| ASUS PRIME H310M-K                 | 1        | 1.12%   |
| ASUS PRIME A320M-A                 | 1        | 1.12%   |
| ASUS P8H61-M LE/USB3               | 1        | 1.12%   |
| ASUS P5E3                          | 1        | 1.12%   |
| ASUS P10S WS                       | 1        | 1.12%   |
| ASUS B75M-PLUS                     | 1        | 1.12%   |
| ASRock Z390 Pro4                   | 1        | 1.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Dell OptiPlex                  | 9        | 10.11%  |
| Protectli FW4B                 | 7        | 7.87%   |
| HP ProLiant                    | 7        | 7.87%   |
| Unknown                        | 6        | 6.74%   |
| Lenovo ThinkCentre             | 5        | 5.62%   |
| HP EliteDesk                   | 2        | 2.25%   |
| ASUS PRIME                     | 2        | 2.25%   |
| ASUS All                       | 2        | 2.25%   |
| ASRock X370                    | 2        | 2.25%   |
| Acer Veriton                   | 2        | 2.25%   |
| Yanling YL-KBR6L               | 1        | 1.12%   |
| Shuttle DH370                  | 1        | 1.12%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.12%   |
| SeeedStudio ODYSSEY-X86J4125   | 1        | 1.12%   |
| Radxa ROCK                     | 1        | 1.12%   |
| Protectli VP2410               | 1        | 1.12%   |
| Protectli FW6                  | 1        | 1.12%   |
| Protectli FW2B                 | 1        | 1.12%   |
| PC Engines apu4                | 1        | 1.12%   |
| MW GMLK-2                      | 1        | 1.12%   |
| MSI Pro                        | 1        | 1.12%   |
| MSI MS-7C95                    | 1        | 1.12%   |
| MSI CML-U                      | 1        | 1.12%   |
| Inventec D                     | 1        | 1.12%   |
| Intel Q3XXG4-P                 | 1        | 1.12%   |
| Intel NCB-4210WG               | 1        | 1.12%   |
| Intel DN2820FYK                | 1        | 1.12%   |
| HP Z400                        | 1        | 1.12%   |
| HP Z240                        | 1        | 1.12%   |
| HP prodesk                     | 1        | 1.12%   |
| HARDKERNEL ODROID-H2           | 1        | 1.12%   |
| Gigabyte Z87N-WIFI             | 1        | 1.12%   |
| Gigabyte Z77N-WIFI             | 1        | 1.12%   |
| Gigabyte Z68MA-D2H-B3          | 1        | 1.12%   |
| Gigabyte J1900N-D3V            | 1        | 1.12%   |
| Gigabyte H270N-WIFI            | 1        | 1.12%   |
| Gigabyte EP45-UD3R             | 1        | 1.12%   |
| Gigabyte 970A-D3P              | 1        | 1.12%   |
| Gateway DX4840                 | 1        | 1.12%   |
| Foxconn p6-2171a               | 1        | 1.12%   |
| Dell Precision                 | 1        | 1.12%   |
| Dell PowerEdge                 | 1        | 1.12%   |
| Cisco SALEEN                   | 1        | 1.12%   |
| ASUS P8H61-M                   | 1        | 1.12%   |
| ASUS P5E3                      | 1        | 1.12%   |
| ASUS P10S                      | 1        | 1.12%   |
| ASUS B75M-PLUS                 | 1        | 1.12%   |
| ASRock Z390                    | 1        | 1.12%   |
| ASRock B560M                   | 1        | 1.12%   |
| ASRock B365M                   | 1        | 1.12%   |
| ASRock A320M-HDV               | 1        | 1.12%   |
| ASRock 990FX                   | 1        | 1.12%   |
| ASRock 970                     | 1        | 1.12%   |
| ADI Engineering RCC-VE         | 1        | 1.12%   |
| AAEON AEC-6646                 | 1        | 1.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 13       | 14.61%  |
| 2013    | 11       | 12.36%  |
| 2020    | 9        | 10.11%  |
| 2018    | 9        | 10.11%  |
| 2011    | 7        | 7.87%   |
| 2021    | 6        | 6.74%   |
| 2017    | 6        | 6.74%   |
| 2016    | 6        | 6.74%   |
| 2012    | 6        | 6.74%   |
| 2014    | 5        | 5.62%   |
| 2009    | 4        | 4.49%   |
| 2015    | 3        | 3.37%   |
| 2010    | 2        | 2.25%   |
| Unknown | 2        | 2.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 89       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 94.38%  |
| Yes  | 5        | 5.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 46       | 50.55%  |
| 16.01-24.0  | 19       | 20.88%  |
| 4.01-8.0    | 14       | 15.38%  |
| 32.01-64.0  | 5        | 5.49%   |
| 24.01-32.0  | 3        | 3.3%    |
| 2.01-3.0    | 2        | 2.2%    |
| 64.01-256.0 | 2        | 2.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 49       | 52.13%  |
| 0.51-1.0   | 27       | 28.72%  |
| 4.01-8.0   | 5        | 5.32%   |
| 1.01-2.0   | 5        | 5.32%   |
| 16.01-24.0 | 2        | 2.13%   |
| 8.01-16.0  | 2        | 2.13%   |
| 32.01-64.0 | 1        | 1.06%   |
| 3.01-4.0   | 1        | 1.06%   |
| 2.01-3.0   | 1        | 1.06%   |
| Unknown    | 1        | 1.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 64.44%  |
| 2      | 13       | 14.44%  |
| 3      | 6        | 6.67%   |
| 0      | 5        | 5.56%   |
| 4      | 4        | 4.44%   |
| 5      | 2        | 2.22%   |
| 7      | 1        | 1.11%   |
| 6      | 1        | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 75.28%  |
| Yes       | 22       | 24.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 88       | 98.88%  |
| No        | 1        | 1.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 81.11%  |
| Yes       | 17       | 18.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 88.89%  |
| Yes       | 10       | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 89       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 24       | 25.26%  |
| Melbourne      | 12       | 12.63%  |
| Brisbane       | 11       | 11.58%  |
| Perth          | 10       | 10.53%  |
| Adelaide       | 3        | 3.16%   |
| Marrickville   | 2        | 2.11%   |
| Hobart         | 2        | 2.11%   |
| Canberra       | 2        | 2.11%   |
| Wollongong     | 1        | 1.05%   |
| Wheelers Hill  | 1        | 1.05%   |
| Townsville     | 1        | 1.05%   |
| Southport      | 1        | 1.05%   |
| Shell Cove     | 1        | 1.05%   |
| Ryde           | 1        | 1.05%   |
| Rosanna        | 1        | 1.05%   |
| Ringwood       | 1        | 1.05%   |
| North Shore    | 1        | 1.05%   |
| Noble Park     | 1        | 1.05%   |
| Mount Waverley | 1        | 1.05%   |
| Mooroolbark    | 1        | 1.05%   |
| Malvern        | 1        | 1.05%   |
| Kurunjang      | 1        | 1.05%   |
| Kellyville     | 1        | 1.05%   |
| Ipswich        | 1        | 1.05%   |
| Gold Coast     | 1        | 1.05%   |
| Geelong        | 1        | 1.05%   |
| Engadine       | 1        | 1.05%   |
| East Malvern   | 1        | 1.05%   |
| Dowerin        | 1        | 1.05%   |
| Dandenong      | 1        | 1.05%   |
| Corio          | 1        | 1.05%   |
| Brunswick      | 1        | 1.05%   |
| Blackburn      | 1        | 1.05%   |
| Bayswater      | 1        | 1.05%   |
| Balwyn North   | 1        | 1.05%   |
| Ashfield       | 1        | 1.05%   |
| Ascot Vale     | 1        | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 17.12%  |
| Samsung Electronics | 19       | 27     | 17.12%  |
| WDC                 | 17       | 50     | 15.32%  |
| Kingston            | 9        | 16     | 8.11%   |
| Intel               | 6        | 10     | 5.41%   |
| Toshiba             | 5        | 9      | 4.5%    |
| Hoodisk             | 5        | 8      | 4.5%    |
| Crucial             | 4        | 4      | 3.6%    |
| SanDisk             | 3        | 5      | 2.7%    |
| Protectli           | 3        | 3      | 2.7%    |
| Hewlett-Packard     | 3        | 6      | 2.7%    |
| Gigabyte Technology | 2        | 2      | 1.8%    |
| A-DATA Technology   | 2        | 7      | 1.8%    |
| XUNZHE              | 1        | 1      | 0.9%    |
| Vaseky              | 1        | 1      | 0.9%    |
| Transcend           | 1        | 1      | 0.9%    |
| SPCC                | 1        | 5      | 0.9%    |
| Phison              | 1        | 1      | 0.9%    |
| Micron Technology   | 1        | 2      | 0.9%    |
| MAXTOR              | 1        | 1      | 0.9%    |
| KingSpec            | 1        | 1      | 0.9%    |
| KingDian            | 1        | 1      | 0.9%    |
| Hitachi             | 1        | 1      | 0.9%    |
| HGST                | 1        | 1      | 0.9%    |
| Fordisk             | 1        | 1      | 0.9%    |
| China               | 1        | 1      | 0.9%    |
| Biwin               | 1        | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Hoodisk SSD 128GB                    | 5        | 4.07%   |
| Kingston SA400S37120G 120GB          | 3        | 2.44%   |
| WDC WD40EFRX-68N32N0 4TB             | 2        | 1.63%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 1.63%   |
| WDC WD20EZAZ-00GGJB0 2TB             | 2        | 1.63%   |
| Seagate ST500LM021-1KJ152 500GB      | 2        | 1.63%   |
| Samsung SSD 850 EVO 500GB            | 2        | 1.63%   |
| Samsung SSD 840 EVO 120GB            | 2        | 1.63%   |
| Samsung MZ7LN128HCHP-000H1 128GB     | 2        | 1.63%   |
| Protectli 120GB mSATA                | 2        | 1.63%   |
| Kingston SA400S37480G 480GB          | 2        | 1.63%   |
| Crucial CT250MX500SSD1 250GB         | 2        | 1.63%   |
| XUNZHE MSATA 128GB                   | 1        | 0.81%   |
| WDC WDS500G1R0B-68A4Z0 500GB         | 1        | 0.81%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1        | 0.81%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1        | 0.81%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1        | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1        | 0.81%   |
| WDC WD80EFAX-68KNBN0 8TB             | 1        | 0.81%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1        | 0.81%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 1        | 0.81%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.81%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1        | 0.81%   |
| WDC WD4000AAKS-00TMA0 400GB          | 1        | 0.81%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 0.81%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.81%   |
| WDC WD20EARX-008FB0 2TB              | 1        | 0.81%   |
| WDC WD20EARS-00MVWB0 2TB             | 1        | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.81%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.81%   |
| WDC WD10EARX-00N0YB0 1TB             | 1        | 0.81%   |
| WDC WD10EADS-00P8B0 1TB              | 1        | 0.81%   |
| Vaseky V850-64G                      | 1        | 0.81%   |
| Transcend TS16EPTMM1600L 16GB        | 1        | 0.81%   |
| Toshiba THNSNJ128GMCU 128GB          | 1        | 0.81%   |
| Toshiba MQ04UBF100 1TB               | 1        | 0.81%   |
| Toshiba MQ04UBD200 2TB               | 1        | 0.81%   |
| Toshiba MQ03UBB200 2TB               | 1        | 0.81%   |
| Toshiba MQ01UBB200 2TB               | 1        | 0.81%   |
| Toshiba MQ01ABD100 1TB               | 1        | 0.81%   |
| Toshiba DT01ACA200 2TB               | 1        | 0.81%   |
| SPCC M.2 PCIe SSD 256GB              | 1        | 0.81%   |
| Seagate ST9500325AS 500GB            | 1        | 0.81%   |
| Seagate ST9250410ASG 250GB           | 1        | 0.81%   |
| Seagate ST9250410AS 250GB            | 1        | 0.81%   |
| Seagate ST500LT012-1DG142 500GB      | 1        | 0.81%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 0.81%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 0.81%   |
| Seagate ST4000LM024-2AN17V 4TB       | 1        | 0.81%   |
| Seagate ST3320620AS 320GB            | 1        | 0.81%   |
| Seagate ST3250310AS 250GB            | 1        | 0.81%   |
| Seagate ST31000528AS 1TB             | 1        | 0.81%   |
| Seagate ST31000524AS 1TB             | 1        | 0.81%   |
| Seagate ST2000VN000-1HJ164 2TB       | 1        | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB       | 1        | 0.81%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 0.81%   |
| Seagate ST1000DM003-1SB102 1TB       | 1        | 0.81%   |
| SanDisk SSD U100 128GB               | 1        | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 19       | 20     | 41.3%   |
| WDC                 | 14       | 44     | 30.43%  |
| Toshiba             | 4        | 6      | 8.7%    |
| Samsung Electronics | 3        | 5      | 6.52%   |
| Hewlett-Packard     | 3        | 6      | 6.52%   |
| MAXTOR              | 1        | 1      | 2.17%   |
| Hitachi             | 1        | 1      | 2.17%   |
| HGST                | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 20     | 25.45%  |
| Kingston            | 9        | 16     | 16.36%  |
| Intel               | 5        | 9      | 9.09%   |
| Hoodisk             | 5        | 8      | 9.09%   |
| WDC                 | 3        | 5      | 5.45%   |
| SanDisk             | 3        | 5      | 5.45%   |
| Protectli           | 3        | 3      | 5.45%   |
| Crucial             | 3        | 3      | 5.45%   |
| XUNZHE              | 1        | 1      | 1.82%   |
| Vaseky              | 1        | 1      | 1.82%   |
| Transcend           | 1        | 1      | 1.82%   |
| Toshiba             | 1        | 3      | 1.82%   |
| Phison              | 1        | 1      | 1.82%   |
| Micron Technology   | 1        | 2      | 1.82%   |
| KingSpec            | 1        | 1      | 1.82%   |
| KingDian            | 1        | 1      | 1.82%   |
| Fordisk             | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 51       | 82     | 51.52%  |
| HDD  | 37       | 84     | 37.37%  |
| NVMe | 11       | 20     | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 79       | 166    | 87.78%  |
| NVMe | 11       | 20     | 12.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 65       | 109    | 70.65%  |
| 0.51-1.0   | 12       | 19     | 13.04%  |
| 1.01-2.0   | 10       | 25     | 10.87%  |
| 3.01-4.0   | 3        | 7      | 3.26%   |
| 2.01-3.0   | 1        | 2      | 1.09%   |
| 4.01-10.0  | 1        | 4      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 41       | 46.07%  |
| 251-500    | 13       | 14.61%  |
| 1-20       | 12       | 13.48%  |
| 501-1000   | 9        | 10.11%  |
| 51-100     | 6        | 6.74%   |
| 21-50      | 4        | 4.49%   |
| 2001-3000  | 2        | 2.25%   |
| 1001-2000  | 2        | 2.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 83       | 90.22%  |
| 21-50     | 6        | 6.52%   |
| 101-250   | 1        | 1.09%   |
| 1001-2000 | 1        | 1.09%   |
| 51-100    | 1        | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 8.33%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 2      | 8.33%   |
| WDC WD20EARX-008FB0 2TB           | 1        | 3      | 8.33%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB   | 1        | 1      | 8.33%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 8.33%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 8.33%   |
| SanDisk SDSSDA240G 240GB          | 1        | 1      | 8.33%   |
| Samsung Electronics HM500LI 500GB | 1        | 2      | 8.33%   |
| Hitachi HDS721010KLA330 1TB       | 1        | 1      | 8.33%   |
| Hewlett-Packard VB0250EAVER 250GB | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 36.36%  |
| WDC                 | 3        | 7      | 27.27%  |
| SanDisk             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 2      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |
| Hewlett-Packard     | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 44.44%  |
| WDC                 | 2        | 6      | 22.22%  |
| Samsung Electronics | 1        | 2      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |
| Hewlett-Packard     | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 14     | 81.82%  |
| SSD  | 2        | 2      | 18.18%  |

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
| Works   | 78       | 170    | 87.64%  |
| Malfunc | 11       | 16     | 12.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 74       | 70.48%  |
| AMD                       | 15       | 14.29%  |
| Phison Electronics        | 3        | 2.86%   |
| Samsung Electronics       | 2        | 1.9%    |
| Silicon Motion            | 1        | 0.95%   |
| Silicon Image             | 1        | 0.95%   |
| Sandisk                   | 1        | 0.95%   |
| Realtek Semiconductor     | 1        | 0.95%   |
| QLogic                    | 1        | 0.95%   |
| Micron/Crucial Technology | 1        | 0.95%   |
| JMicron Technology        | 1        | 0.95%   |
| Hewlett-Packard           | 1        | 0.95%   |
| Broadcom / LSI            | 1        | 0.95%   |
| ADATA Technology          | 1        | 0.95%   |
| Adaptec                   | 1        | 0.95%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 8.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 8.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 9        | 7.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 5.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 4.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4        | 3.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4        | 3.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.25%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.44%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.44%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.63%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.63%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.81%   |
| Silicon Image AAR-1220SA Serial ATA HostRAID Controller                                 | 1        | 0.81%   |
| Sandisk unknown                                                                         | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.81%   |
| QLogic QLA2100 64-bit Fibre Channel Adapter                                             | 1        | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.81%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.81%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 1        | 0.81%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                        | 1        | 0.81%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.81%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.81%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.81%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.81%   |
| HP Smart Array G6 controllers                                                           | 1        | 0.81%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 0.81%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.81%   |
| AMD FCH IDE Controller                                                                  | 1        | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.81%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 0.81%   |
| Unknown                                                                                 | 1        | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 82       | 71.93%  |
| IDE  | 13       | 11.4%   |
| NVMe | 11       | 9.65%   |
| RAID | 5        | 4.39%   |
| SCSI | 2        | 1.75%   |
| SAS  | 1        | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 74       | 83.15%  |
| AMD    | 15       | 16.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz           | 8        | 8.99%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 3.37%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 3.37%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 2        | 2.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.25%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 2.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 2.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 2.25%   |
| AMD Turion II Neo N54L Dual-Core Processor  | 2        | 2.25%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.25%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 1        | 1.12%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.12%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1        | 1.12%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 1.12%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1        | 1.12%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1        | 1.12%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz         | 1        | 1.12%   |
| Intel Xeon                                  | 1        | 1.12%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.12%   |
| Intel Pentium CPU G6950 @ 2.80GHz           | 1        | 1.12%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 1.12%   |
| Intel Pentium CPU G4400T @ 2.90GHz          | 1        | 1.12%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 1.12%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.12%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 1.12%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1        | 1.12%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.12%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.12%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.12%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.12%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 1        | 1.12%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.12%   |
| Intel Core i5-2500 CPU @ 3.30GH             | 1        | 1.12%   |
| Intel Core i5-2500 CPU                      | 1        | 1.12%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.12%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.12%   |
| Intel Core i3-7167U CPU @ 2.80GHz           | 1        | 1.12%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1        | 1.12%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.12%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.12%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.12%   |
| Intel Core i3-2120 CPU @ 3.30GH             | 1        | 1.12%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 1        | 1.12%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 1.12%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 1        | 1.12%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 1.12%   |
| Intel Core 2 Quad CPU Q6600 @               | 1        | 1.12%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1        | 1.12%   |
| Intel Celeron CPU N2820 @ 2.13GHz           | 1        | 1.12%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 1.12%   |
| Intel Celeron CPU J3060 @ 1.60GHz           | 1        | 1.12%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.12%   |
| Intel Celeron CPU G3900 @ 2.80GHz           | 1        | 1.12%   |
| Intel Celeron CPU G1610T @ 2.30GHz          | 1        | 1.12%   |
| Intel Celeron CPU 3215U @ 1.70GHz           | 1        | 1.12%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1        | 1.12%   |
| Intel Atom CPU C2358 @ 1.74GHz              | 1        | 1.12%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 22.47%  |
| Intel Celeron           | 19       | 21.35%  |
| Intel Core i3           | 11       | 12.36%  |
| Intel Xeon              | 10       | 11.24%  |
| Intel Core i7           | 5        | 5.62%   |
| Intel Pentium           | 4        | 4.49%   |
| AMD Turion II Neo       | 3        | 3.37%   |
| AMD Ryzen 5             | 3        | 3.37%   |
| AMD FX                  | 3        | 3.37%   |
| Intel Core 2 Quad       | 2        | 2.25%   |
| Intel Atom              | 2        | 2.25%   |
| AMD Ryzen 3             | 2        | 2.25%   |
| Intel Pentium Dual-Core | 1        | 1.12%   |
| AMD GX                  | 1        | 1.12%   |
| AMD G                   | 1        | 1.12%   |
| AMD E2                  | 1        | 1.12%   |
| AMD Athlon              | 1        | 1.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 47       | 52.81%  |
| 2       | 26       | 29.21%  |
| 8       | 7        | 7.87%   |
| 6       | 5        | 5.62%   |
| 12      | 2        | 2.25%   |
| Unknown | 2        | 2.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 97.75%  |
| 2      | 2        | 2.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 64       | 71.91%  |
| 2       | 23       | 25.84%  |
| Unknown | 2        | 2.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Silvermont    | 13       | 14.61%  |
| Haswell       | 11       | 12.36%  |
| KabyLake      | 10       | 11.24%  |
| IvyBridge     | 9        | 10.11%  |
| SandyBridge   | 8        | 8.99%   |
| Skylake       | 5        | 5.62%   |
| Nehalem       | 4        | 4.49%   |
| Goldmont plus | 4        | 4.49%   |
| Westmere      | 3        | 3.37%   |
| Piledriver    | 3        | 3.37%   |
| K10           | 3        | 3.37%   |
| Zen           | 2        | 2.25%   |
| Penryn        | 2        | 2.25%   |
| Broadwell     | 2        | 2.25%   |
| Bobcat        | 2        | 2.25%   |
| Zen+          | 1        | 1.12%   |
| Zen 3         | 1        | 1.12%   |
| Zen 2         | 1        | 1.12%   |
| Puma          | 1        | 1.12%   |
| Jaguar        | 1        | 1.12%   |
| Goldmont      | 1        | 1.12%   |
| Core          | 1        | 1.12%   |
| CometLake     | 1        | 1.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 54       | 60.67%  |
| AMD                        | 15       | 16.85%  |
| Nvidia                     | 13       | 14.61%  |
| Matrox Electronics Systems | 5        | 5.62%   |
| Tseng Labs                 | 1        | 1.12%   |
| ASPEED Technology          | 1        | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10       | 10.99%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 8.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 6.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 5.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 5.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 4.4%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3        | 3.3%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 2.2%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 2.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.2%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 2.2%    |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2        | 2.2%    |
| Intel UHD Graphics 620                                                                   | 2        | 2.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 2.2%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 2.2%    |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 1.1%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.1%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1        | 1.1%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.1%    |
| Nvidia GF100GL [Quadro 4000]                                                             | 1        | 1.1%    |
| Nvidia G92 [GeForce GT 330]                                                              | 1        | 1.1%    |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 1.1%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 1.1%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.1%    |
| Intel Iris Plus Graphics 650                                                             | 1        | 1.1%    |
| Intel HD Graphics P530                                                                   | 1        | 1.1%    |
| Intel HD Graphics 610                                                                    | 1        | 1.1%    |
| Intel HD Graphics 510                                                                    | 1        | 1.1%    |
| Intel HD Graphics 500                                                                    | 1        | 1.1%    |
| Intel HD Graphics                                                                        | 1        | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1        | 1.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                               | 1        | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.1%    |
| AMD Wrestler [Radeon HD 7340]                                                            | 1        | 1.1%    |
| AMD Wrestler [Radeon HD 6250]                                                            | 1        | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.1%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.1%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1        | 1.1%    |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1        | 1.1%    |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 1.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 1.1%    |
| AMD Cezanne                                                                              | 1        | 1.1%    |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 1        | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 51       | 56.04%  |
| 1 x AMD        | 14       | 15.38%  |
| 1 x Nvidia     | 12       | 13.19%  |
| 1 x Matrox     | 5        | 5.49%   |
| Other          | 3        | 3.3%    |
| 2 x Intel      | 1        | 1.1%    |
| 2 x AMD        | 1        | 1.1%    |
| 1 x Tseng Labs | 1        | 1.1%    |
| Intel + Nvidia | 1        | 1.1%    |
| Intel + AMD    | 1        | 1.1%    |
| 1 x ASPEED     | 1        | 1.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 80       | 89.89%  |
| Proprietary | 6        | 6.74%   |
| Unknown     | 3        | 3.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 87.78%  |
| 1.01-2.0   | 6        | 6.67%   |
| 7.01-8.0   | 2        | 2.22%   |
| 0.51-1.0   | 2        | 2.22%   |
| 3.01-4.0   | 1        | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 16.67%  |
| Samsung Electronics | 2        | 11.11%  |
| Philips             | 2        | 11.11%  |
| Hewlett-Packard     | 2        | 11.11%  |
| AOC                 | 2        | 11.11%  |
| Acer                | 2        | 11.11%  |
| ___                 | 1        | 5.56%   |
| ViewSonic           | 1        | 5.56%   |
| Toshiba             | 1        | 5.56%   |
| Goldstar            | 1        | 5.56%   |
| BenQ                | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 5.26%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1        | 5.26%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1        | 5.26%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1        | 5.26%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1        | 5.26%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 5.26%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 5.26%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1        | 5.26%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1        | 5.26%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1        | 5.26%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1        | 5.26%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1        | 5.26%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1        | 5.26%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1        | 5.26%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 5.26%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1        | 5.26%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1        | 5.26%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1        | 5.26%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 66.67%  |
| 3840x1600          | 1        | 5.56%   |
| 2560x1440 (QHD)    | 1        | 5.56%   |
| 2560x1080          | 1        | 5.56%   |
| 2048x1152          | 1        | 5.56%   |
| 1920x1200 (WUXGA)  | 1        | 5.56%   |
| 1680x1050 (WSXGA+) | 1        | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 4        | 22.22%  |
| 27      | 3        | 16.67%  |
| 23      | 3        | 16.67%  |
| 21      | 2        | 11.11%  |
| 47      | 1        | 5.56%   |
| 37      | 1        | 5.56%   |
| 31      | 1        | 5.56%   |
| 28      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 55.56%  |
| 401-500     | 3        | 16.67%  |
| 601-700     | 2        | 11.11%  |
| 801-900     | 1        | 5.56%   |
| 1001-1500   | 1        | 5.56%   |
| Unknown     | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 77.78%  |
| 21/9  | 2        | 11.11%  |
| 16/10 | 2        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 50%     |
| 301-350        | 3        | 16.67%  |
| 251-300        | 2        | 11.11%  |
| 501-1000       | 2        | 11.11%  |
| 351-500        | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 66.67%  |
| 101-120 | 4        | 22.22%  |
| 1-50    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 71       | 79.78%  |
| 1     | 17       | 19.1%   |
| 2     | 1        | 1.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 58       | 50.43%  |
| Realtek Semiconductor    | 33       | 28.7%   |
| Broadcom                 | 12       | 10.43%  |
| Qualcomm Atheros         | 4        | 3.48%   |
| U-Blox                   | 2        | 1.74%   |
| TP-Link                  | 1        | 0.87%   |
| Seeed Technology         | 1        | 0.87%   |
| Ralink                   | 1        | 0.87%   |
| Marvell Technology Group | 1        | 0.87%   |
| IMC Networks             | 1        | 0.87%   |
| D-Link System            | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 30       | 21.9%   |
| Intel I211 Gigabit Network Connection                                         | 16       | 11.68%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 6.57%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.38%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 3.65%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 3.65%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.92%   |
| Intel Wireless 7260                                                           | 3        | 2.19%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 2.19%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 2.19%   |
| U-Blox [u-blox 7]                                                             | 2        | 1.46%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 1.46%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.46%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.46%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 1.46%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.73%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.73%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.73%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1        | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.73%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.73%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 0.73%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 0.73%   |
| Intel Ethernet Controller X550                                                | 1        | 0.73%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.73%   |
| Intel Ethernet Connection I354                                                | 1        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.73%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.73%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.73%   |
| Intel DH8900CC Null Device                                                    | 1        | 0.73%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.73%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.73%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 0.73%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.73%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.73%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.73%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 50%     |
| Realtek Semiconductor | 3        | 16.67%  |
| Qualcomm Atheros      | 3        | 16.67%  |
| TP-Link               | 1        | 5.56%   |
| Ralink                | 1        | 5.56%   |
| IMC Networks          | 1        | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                            | 3        | 16.67%  |
| Intel Wireless 8265 / 8275                                     | 2        | 11.11%  |
| Intel Centrino Wireless-N 2230                                 | 2        | 11.11%  |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1        | 5.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1        | 5.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 5.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1        | 5.56%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1        | 5.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1        | 5.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 5.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 5.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1        | 5.56%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1        | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 56       | 53.85%  |
| Realtek Semiconductor    | 32       | 30.77%  |
| Broadcom                 | 12       | 11.54%  |
| Qualcomm Atheros         | 2        | 1.92%   |
| Marvell Technology Group | 1        | 0.96%   |
| D-Link System            | 1        | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 30       | 26.09%  |
| Intel I211 Gigabit Network Connection                                         | 16       | 13.91%  |
| Intel I210 Gigabit Network Connection                                         | 9        | 7.83%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 5.22%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 4.35%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 5        | 4.35%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 3.48%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 2.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 2.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 2.61%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.74%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.74%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 1.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.87%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.87%   |
| Intel Ethernet Controller X550                                                | 1        | 0.87%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.87%   |
| Intel Ethernet Connection I354                                                | 1        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                          | 1        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.87%   |
| Intel Ethernet Connection (11) I219-V                                         | 1        | 0.87%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.87%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.87%   |
| D-Link System DGE-530T Gigabit Ethernet Adapter (rev 11)                      | 1        | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.87%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1        | 0.87%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 88       | 80.73%  |
| WiFi     | 17       | 15.6%   |
| Modem    | 3        | 2.75%   |
| Unknown  | 1        | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 87       | 90.63%  |
| WiFi     | 9        | 9.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 30       | 33.33%  |
| 1     | 21       | 23.33%  |
| 4     | 15       | 16.67%  |
| 3     | 11       | 12.22%  |
| 6     | 7        | 7.78%   |
| 5     | 3        | 3.33%   |
| 7     | 2        | 2.22%   |
| 9     | 1        | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 86.02%  |
| Yes  | 13       | 13.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 7        | 70%     |
| Cambridge Silicon Radio | 2        | 20%     |
| Broadcom                | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 30%     |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 20%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 58       | 68.24%  |
| AMD               | 14       | 16.47%  |
| Nvidia            | 11       | 12.94%  |
| Texas Instruments | 1        | 1.18%   |
| Logitech          | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10       | 9.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9        | 8.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8        | 7.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7        | 6.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 3.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4        | 3.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4        | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 3.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 3.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3        | 2.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.88%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 2.88%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.92%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.92%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.92%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 1        | 0.96%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.96%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.96%   |
| Nvidia GF100 High Definition Audio Controller                                                     | 1        | 0.96%   |
| Logitech Headset H390                                                                             | 1        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.96%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 0.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 0.96%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1        | 0.96%   |
| AMD FCH Azalia Controller                                                                         | 1        | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1        | 0.96%   |
| Unknown                                                                                           | 1        | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 17       | 16.67%  |
| Kingston            | 17       | 16.67%  |
| Unknown             | 12       | 11.76%  |
| Micron Technology   | 12       | 11.76%  |
| SK Hynix            | 9        | 8.82%   |
| Corsair             | 8        | 7.84%   |
| Crucial             | 5        | 4.9%    |
| G.Skill             | 4        | 3.92%   |
| Transcend           | 2        | 1.96%   |
| Team                | 2        | 1.96%   |
| Unknown             | 2        | 1.96%   |
| Unknown (ABCD)      | 1        | 0.98%   |
| Smart Modular       | 1        | 0.98%   |
| Ramaxel Technology  | 1        | 0.98%   |
| PNY                 | 1        | 0.98%   |
| Patriot             | 1        | 0.98%   |
| Nanya Technology    | 1        | 0.98%   |
| Kingmax             | 1        | 0.98%   |
| Innodisk            | 1        | 0.98%   |
| Hewlett-Packard     | 1        | 0.98%   |
| GeIL                | 1        | 0.98%   |
| Elpida              | 1        | 0.98%   |
| Apacer              | 1        | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 3        | 2.78%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 2        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 2        | 1.85%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 1.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2        | 1.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s               | 2        | 1.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 2        | 1.85%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 2        | 1.85%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                 | 2        | 1.85%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s              | 2        | 1.85%   |
| Unknown                                                           | 2        | 1.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 0.93%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 1        | 0.93%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 0.93%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                      | 1        | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM 800MT/s                               | 1        | 0.93%   |
| Unknown RAM Module 1GB DIMM DDR 59392MT/s                         | 1        | 0.93%   |
| Unknown RAM Module 1GB DIMM 800MT/s                               | 1        | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 0.93%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1        | 0.93%   |
| Transcend RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 0.93%   |
| Team RAM Vulcan-1600 8GB DIMM DDR3 1600MT/s                       | 1        | 0.93%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                | 1        | 0.93%   |
| Smart Modular RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.93%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 0.93%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1        | 0.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 0.93%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1        | 0.93%   |
| SK Hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 0.93%   |
| SK Hynix RAM HMA81GU7DJR8N-VK 8GB DIMM DDR4 2666MT/s              | 1        | 0.93%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1        | 0.93%   |
| Samsung RAM M471B1G73DH0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 0.93%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s             | 1        | 0.93%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 1        | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s             | 1        | 0.93%   |
| Samsung RAM M393B1K70DH0-CH9 8192MB DIMM DDR3 800MT/s             | 1        | 0.93%   |
| Samsung RAM M391B5673EH1-CF8 2GB DIMM DDR3 1066MT/s               | 1        | 0.93%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1        | 0.93%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1333MT/s               | 1        | 0.93%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.93%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 0.93%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2666MT/s               | 1        | 0.93%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s             | 1        | 0.93%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 2133MT/s            | 1        | 0.93%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                    | 1        | 0.93%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                | 1        | 0.93%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s             | 1        | 0.93%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s              | 1        | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s             | 1        | 0.93%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s               | 1        | 0.93%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s               | 1        | 0.93%   |
| Micron RAM 18JSF25672AZ-1G1F1 2GB DIMM DDR3 1066MT/s              | 1        | 0.93%   |
| Micron RAM 18JDF25672PZ-1G4F1 2048MB DIMM DDR3 800MT/s            | 1        | 0.93%   |
| Micron RAM 18ASF1G72AZ-2G1B1 8GB DIMM DDR4 2133MT/s               | 1        | 0.93%   |
| Micron RAM 16ATF4G64HZ-2G6E1 32GB SODIMM DDR4 2667MT/s            | 1        | 0.93%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s               | 1        | 0.93%   |
| Kingston RAM CBD26D4S9S1ME-8 8GB SODIMM DDR4 2667MT/s             | 1        | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 50       | 58.82%  |
| DDR4    | 25       | 29.41%  |
| Unknown | 7        | 8.24%   |
| LPDDR4  | 1        | 1.18%   |
| DDR2    | 1        | 1.18%   |
| DDR     | 1        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 62       | 73.81%  |
| SODIMM  | 18       | 21.43%  |
| Unknown | 3        | 3.57%   |
| RIMM    | 1        | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 41.76%  |
| 4096  | 30       | 32.97%  |
| 2048  | 13       | 14.29%  |
| 16384 | 7        | 7.69%   |
| 1024  | 2        | 2.2%    |
| 32768 | 1        | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 33       | 37.08%  |
| 1333  | 20       | 22.47%  |
| 2400  | 10       | 11.24%  |
| 2133  | 8        | 8.99%   |
| 2667  | 7        | 7.87%   |
| 800   | 4        | 4.49%   |
| 1066  | 3        | 3.37%   |
| 2666  | 2        | 2.25%   |
| 59392 | 1        | 1.12%   |
| 1867  | 1        | 1.12%   |

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
| 1     | 47       | 52.22%  |
| 0     | 35       | 38.89%  |
| 2     | 6        | 6.67%   |
| 5     | 1        | 1.11%   |
| 4     | 1        | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 48       | 76.19%  |
| Net/wireless             | 4        | 6.35%   |
| Firewire controller      | 3        | 4.76%   |
| Bluetooth                | 3        | 4.76%   |
| Sound                    | 2        | 3.17%   |
| Card reader              | 2        | 3.17%   |
| Network                  | 1        | 1.59%   |

