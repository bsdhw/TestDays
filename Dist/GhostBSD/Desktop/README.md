GhostBSD - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

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

Total: 164

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock        | H61M-VG3                    | [e0ed997df8](https://bsd-hardware.info/?probe=e0ed997df8) | Dec 23, 2024 |
| MSI           | Z490-A PRO                  | [50ca527f2b](https://bsd-hardware.info/?probe=50ca527f2b) | Dec 01, 2024 |
| MSI           | B450-A PRO MAX              | [265f542246](https://bsd-hardware.info/?probe=265f542246) | Nov 12, 2024 |
| HP            | 3397                        | [ddf2d83456](https://bsd-hardware.info/?probe=ddf2d83456) | Oct 27, 2024 |
| ASRock        | B450 Pro4 R2.0              | [a6ccceed97](https://bsd-hardware.info/?probe=a6ccceed97) | Oct 24, 2024 |
| Biostar       | B450MHP                     | [af6e8cf307](https://bsd-hardware.info/?probe=af6e8cf307) | Sep 29, 2024 |
| HP            | 18E7                        | [7bdd288f75](https://bsd-hardware.info/?probe=7bdd288f75) | Sep 03, 2024 |
| Lenovo        | ThinkCentre M715q 10M2S0... | [66a3b3e94e](https://bsd-hardware.info/?probe=66a3b3e94e) | Sep 02, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [aedfdb1704](https://bsd-hardware.info/?probe=aedfdb1704) | Aug 22, 2024 |
| ASUSTek       | EX-H110M-V                  | [9f18579edf](https://bsd-hardware.info/?probe=9f18579edf) | Aug 05, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [7f3e4230e3](https://bsd-hardware.info/?probe=7f3e4230e3) | Aug 05, 2024 |
| ASRock        | X300M-STX                   | [50dd5072a2](https://bsd-hardware.info/?probe=50dd5072a2) | Aug 04, 2024 |
| ASUSTek       | M4A88T-M                    | [133cfcbe40](https://bsd-hardware.info/?probe=133cfcbe40) | Jul 27, 2024 |
| Biostar       | B450MH                      | [425858d6af](https://bsd-hardware.info/?probe=425858d6af) | Jul 18, 2024 |
| ASRock        | J3455-ITX                   | [3b31af23f2](https://bsd-hardware.info/?probe=3b31af23f2) | Jul 05, 2024 |
| Biostar       | A68N-5200                   | [9299915b62](https://bsd-hardware.info/?probe=9299915b62) | Jun 20, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [2ccb52d7b5](https://bsd-hardware.info/?probe=2ccb52d7b5) | Jun 11, 2024 |
| ASUSTek       | Maximus IV GENE-Z           | [5b53bd70e9](https://bsd-hardware.info/?probe=5b53bd70e9) | Jun 08, 2024 |
| MSI           | H110M PRO-D                 | [3f2aaa6b19](https://bsd-hardware.info/?probe=3f2aaa6b19) | May 29, 2024 |
| Dell          | 055H3G A01                  | [5d0cd53384](https://bsd-hardware.info/?probe=5d0cd53384) | May 16, 2024 |
| Biostar       | B450MH                      | [6fc7467762](https://bsd-hardware.info/?probe=6fc7467762) | May 13, 2024 |
| Apple         | Mac-F221BEC8                | [79c4a2608c](https://bsd-hardware.info/?probe=79c4a2608c) | May 07, 2024 |
| Gigabyte      | P55-USB3                    | [9024f0074b](https://bsd-hardware.info/?probe=9024f0074b) | May 07, 2024 |
| MSI           | B360M BAZOOKA               | [d33325e752](https://bsd-hardware.info/?probe=d33325e752) | May 02, 2024 |
| HP            | ProLiant MicroServer Gen... | [15c55873cd](https://bsd-hardware.info/?probe=15c55873cd) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2cbe8253b](https://bsd-hardware.info/?probe=a2cbe8253b) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| ASUSTek       | PRIME Z390-A                | [56ea2c6719](https://bsd-hardware.info/?probe=56ea2c6719) | Apr 01, 2024 |
| ASRock        | 970 Pro3 R2.0               | [cfcf823cca](https://bsd-hardware.info/?probe=cfcf823cca) | Apr 01, 2024 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1010       | [4a359f1f86](https://bsd-hardware.info/?probe=4a359f1f86) | Apr 01, 2024 |
| Lenovo        | 3743 NOK                    | [fd5dc51da2](https://bsd-hardware.info/?probe=fd5dc51da2) | Mar 31, 2024 |
| ASUSTek       | H61M-K                      | [1f6840c3f3](https://bsd-hardware.info/?probe=1f6840c3f3) | Mar 12, 2024 |
| LG Electro... | R590-P.BE54P1               | [120ec3afe6](https://bsd-hardware.info/?probe=120ec3afe6) | Mar 09, 2024 |
| Dell          | 0H634K A00                  | [5392dc85bb](https://bsd-hardware.info/?probe=5392dc85bb) | Feb 21, 2024 |
| Gigabyte      | GA-990FX-GAMING             | [39e4fb5eba](https://bsd-hardware.info/?probe=39e4fb5eba) | Feb 20, 2024 |
| Dell          | 0H634K A00                  | [e933816d9f](https://bsd-hardware.info/?probe=e933816d9f) | Feb 19, 2024 |
| Biostar       | B450NH                      | [2db279db1d](https://bsd-hardware.info/?probe=2db279db1d) | Feb 16, 2024 |
| ASUSTek       | Pro B560M-C                 | [fdeb2cee9d](https://bsd-hardware.info/?probe=fdeb2cee9d) | Feb 14, 2024 |
| Shenzhen M... | F6BFC                       | [ca7e1f0fae](https://bsd-hardware.info/?probe=ca7e1f0fae) | Feb 12, 2024 |
| Dell          | 0H634K A00                  | [a39d975ae9](https://bsd-hardware.info/?probe=a39d975ae9) | Feb 11, 2024 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [37d30255bc](https://bsd-hardware.info/?probe=37d30255bc) | Feb 06, 2024 |
| MSI           | Z370-A PRO                  | [2b442ae151](https://bsd-hardware.info/?probe=2b442ae151) | Jan 20, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ebd5d3e03f](https://bsd-hardware.info/?probe=ebd5d3e03f) | Jan 19, 2024 |
| Casper        | NIRVANA DESKTOP             | [926ae04d23](https://bsd-hardware.info/?probe=926ae04d23) | Dec 31, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [fa4e90491b](https://bsd-hardware.info/?probe=fa4e90491b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [1c769a311c](https://bsd-hardware.info/?probe=1c769a311c) | Dec 29, 2023 |
| ASRock        | 990FX Extreme3              | [6ac792ecf6](https://bsd-hardware.info/?probe=6ac792ecf6) | Dec 05, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| ASRock        | J5040-ITX                   | [dffb96790c](https://bsd-hardware.info/?probe=dffb96790c) | Oct 06, 2023 |
| ASUSTek       | P8Z77-V LX                  | [39fbf2c8dc](https://bsd-hardware.info/?probe=39fbf2c8dc) | Oct 02, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [6427b9defc](https://bsd-hardware.info/?probe=6427b9defc) | Oct 02, 2023 |
| ASRock        | H670M-ITX/ax                | [1b6996f127](https://bsd-hardware.info/?probe=1b6996f127) | Sep 17, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [efe49f9e5d](https://bsd-hardware.info/?probe=efe49f9e5d) | Jul 20, 2023 |
| Intel         | HM570                       | [4e0fd42418](https://bsd-hardware.info/?probe=4e0fd42418) | Jul 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| Soyo          | SY-YL B550M                 | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| Dell          | 0M9KCM A02                  | [932e96060f](https://bsd-hardware.info/?probe=932e96060f) | May 21, 2023 |
| ASUSTek       | ROG ZENITH EXTREME ALPHA    | [a3df9cd649](https://bsd-hardware.info/?probe=a3df9cd649) | May 14, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [773b28fbc7](https://bsd-hardware.info/?probe=773b28fbc7) | Apr 16, 2023 |
| MSI           | X299 PRO                    | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0K17763 WIN ... | [c9279ce424](https://bsd-hardware.info/?probe=c9279ce424) | Mar 13, 2023 |
| MSI           | X299 PRO                    | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| ASUSTek       | SABERTOOTH X58              | [37e1562772](https://bsd-hardware.info/?probe=37e1562772) | Mar 10, 2023 |
| MSI           | X299 PRO                    | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Huanan        | X99-QD4 V1.0                | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| Gigabyte      | H61M-S2PV                   | [b42e3649a3](https://bsd-hardware.info/?probe=b42e3649a3) | Feb 13, 2023 |
| MSI           | X299 PRO                    | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| HP            | 18E7                        | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| MSI           | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| MSI           | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| ASUSTek       | H97-PLUS                    | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ASUSTek       | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Gigabyte      | H510M H                     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Gigabyte      | B365M DS3H                  | [0d7d7288c0](https://bsd-hardware.info/?probe=0d7d7288c0) | Aug 27, 2022 |
| Gigabyte      | B365M DS3H                  | [0a90c3c566](https://bsd-hardware.info/?probe=0a90c3c566) | Aug 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| MSI           | B85M-E45                    | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3ee4c986b4](https://bsd-hardware.info/?probe=3ee4c986b4) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| ASRock        | B450 Gaming K4              | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| Dell          | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| Gigabyte      | AX370-Gaming 3-CF           | [62ab2bc823](https://bsd-hardware.info/?probe=62ab2bc823) | May 07, 2022 |
| HP            | 0B4Ch D                     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Dell          | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| Dell          | 0Y56T3 A00                  | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| MSI           | B250 PC MATE                | [612b0f0a34](https://bsd-hardware.info/?probe=612b0f0a34) | Mar 19, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| ASUSTek       | Z97-A                       | [84d7fb3f1e](https://bsd-hardware.info/?probe=84d7fb3f1e) | Jan 30, 2022 |
| Dell          | 0NNNCT A01                  | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Alienware     | 01NYPT A00                  | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek       | PRIME Z270-K                | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Medion        | MS-7728                     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Gigabyte      | H410M S2 V2                 | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| ASUSTek       | SABERTOOTH X58              | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| ASRock        | X570 Taichi                 | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Gigabyte      | Z77M-D3H                    | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| MSI           | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| ASRock        | Z77 Extreme6                | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| ASUSTek       | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| ASUSTek       | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Lenovo        | Board                       | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| ASUSTek       | V-P7H55E                    | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek       | V-P7H55E                    | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek       | V-P7H55E                    | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Dell          | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP            | 1850                        | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| Gigabyte      | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Acer          | Aspire XC-115               | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo        | Kabini CRB 31900058 STD     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock        | AB350 Pro4                  | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer          | WG43M                       | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell          | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell          | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| MSI           | Z97 GAMING 5                | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| Dell          | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Dell          | 0HY9JP A02                  | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP            | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta        | 2AF5 011                    | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI           | B450 GAMING PLUS            | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| MSI           | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte      | F2A68HM-DS2                 | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte      | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Unknown       | SKYBAY                      | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock        | X370 Gaming K4              | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GhostBSD 20.04.02 | 45       | 34.09%  |
| GhostBSD 24.01.1  | 16       | 12.12%  |
| GhostBSD 24.04.1  | 10       | 7.58%   |
| GhostBSD 21.08.27 | 8        | 6.06%   |
| GhostBSD 23.10.1  | 7        | 5.3%    |
| GhostBSD 24.07.3  | 4        | 3.03%   |
| GhostBSD 23.02.02 | 4        | 3.03%   |
| GhostBSD 22.01.12 | 4        | 3.03%   |
| GhostBSD 23.06.01 | 3        | 2.27%   |
| GhostBSD 22.11.22 | 3        | 2.27%   |
| GhostBSD 22.06.18 | 3        | 2.27%   |
| GhostBSD 24.10.1  | 2        | 1.52%   |
| GhostBSD 22.09.16 | 2        | 1.52%   |
| GhostBSD 22.07.16 | 2        | 1.52%   |
| GhostBSD 22.04.06 | 2        | 1.52%   |
| GhostBSD 24.07.1  | 1        | 0.76%   |
| GhostBSD 23.09.29 | 1        | 0.76%   |
| GhostBSD 23.09.06 | 1        | 0.76%   |
| GhostBSD 23.06.22 | 1        | 0.76%   |
| GhostBSD 23.05.18 | 1        | 0.76%   |
| GhostBSD 23.04.23 | 1        | 0.76%   |
| GhostBSD 23.03.17 | 1        | 0.76%   |
| GhostBSD 22.12.20 | 1        | 0.76%   |
| GhostBSD 22.11.02 | 1        | 0.76%   |
| GhostBSD 22.10.12 | 1        | 0.76%   |
| GhostBSD 22.08.23 | 1        | 0.76%   |
| GhostBSD 22.07.13 | 1        | 0.76%   |
| GhostBSD 22.06.26 | 1        | 0.76%   |
| GhostBSD 22.05.14 | 1        | 0.76%   |
| GhostBSD 22.04.22 | 1        | 0.76%   |
| GhostBSD 22.01.28 | 1        | 0.76%   |
| GhostBSD 19.12    | 1        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GhostBSD | 124      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 124      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 99       | 78.57%  |
| XFCE             | 14       | 11.11%  |
| KDE5             | 7        | 5.56%   |
| openbox          | 1        | 0.79%   |
| Metacity (Marco) | 1        | 0.79%   |
| LXQt             | 1        | 0.79%   |
| i3               | 1        | 0.79%   |
| GNOME            | 1        | 0.79%   |
| Cinnamon         | 1        | 0.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 124      | 99.2%   |
| Wayland | 1        | 0.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 121      | 97.58%  |
| SDDM    | 2        | 1.61%   |
| Console | 1        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 55       | 44%     |
| C       | 23       | 18.4%   |
| de_DE   | 13       | 10.4%   |
| Unknown | 12       | 9.6%    |
| ru_RU   | 5        | 4%      |
| es_ES   | 4        | 3.2%    |
| pl_PL   | 3        | 2.4%    |
| pt_BR   | 2        | 1.6%    |
| fr_FR   | 2        | 1.6%    |
| en_AU   | 2        | 1.6%    |
| UTF-8   | 1        | 0.8%    |
| sk_SK   | 1        | 0.8%    |
| pt_PT   | 1        | 0.8%    |
| en_GB   | 1        | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 97       | 78.23%  |
| BIOS | 27       | 21.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 117      | 93.6%   |
| Ufs  | 8        | 6.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 116      | 93.55%  |
| MBR     | 6        | 4.84%   |
| Unknown | 2        | 1.61%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 29       | 23.39%  |
| Gigabyte Technology                  | 19       | 15.32%  |
| MSI                                  | 16       | 12.9%   |
| ASRock                               | 16       | 12.9%   |
| Dell                                 | 12       | 9.68%   |
| Lenovo                               | 7        | 5.65%   |
| Hewlett-Packard                      | 5        | 4.03%   |
| Fujitsu                              | 3        | 2.42%   |
| Biostar                              | 3        | 2.42%   |
| Huanan                               | 2        | 1.61%   |
| Acer                                 | 2        | 1.61%   |
| Soyo                                 | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.81%   |
| Quanta                               | 1        | 0.81%   |
| Medion                               | 1        | 0.81%   |
| LG Electronics                       | 1        | 0.81%   |
| HUAWEI                               | 1        | 0.81%   |
| Casper                               | 1        | 0.81%   |
| Apple                                | 1        | 0.81%   |
| Alienware                            | 1        | 0.81%   |
| Unknown                              | 1        | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 3        | 2.42%   |
| MSI MS-7817                                                           | 2        | 1.61%   |
| Dell OptiPlex 7050                                                    | 2        | 1.61%   |
| ASUS SABERTOOTH X58                                                   | 2        | 1.61%   |
| ASUS All Series                                                       | 2        | 1.61%   |
| Soyo SY-YL B550M                                                      | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment UM480XT                          | 1        | 0.81%   |
| Quanta 120-1333w                                                      | 1        | 0.81%   |
| MSI MS-7D25                                                           | 1        | 0.81%   |
| MSI MS-7C75                                                           | 1        | 0.81%   |
| MSI MS-7C36                                                           | 1        | 0.81%   |
| MSI MS-7B94                                                           | 1        | 0.81%   |
| MSI MS-7B89                                                           | 1        | 0.81%   |
| MSI MS-7B48                                                           | 1        | 0.81%   |
| MSI MS-7B24                                                           | 1        | 0.81%   |
| MSI MS-7A72                                                           | 1        | 0.81%   |
| MSI MS-7996                                                           | 1        | 0.81%   |
| MSI MS-7917                                                           | 1        | 0.81%   |
| MSI MS-7788                                                           | 1        | 0.81%   |
| Medion MS-7728                                                        | 1        | 0.81%   |
| LG R590-P.BE54P1                                                      | 1        | 0.81%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 0.81%   |
| Lenovo ThinkCentre M93p 10AB004DUS                                    | 1        | 0.81%   |
| Lenovo ThinkCentre M715q 10M2S08Y00                                   | 1        | 0.81%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 0.81%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL                           | 1        | 0.81%   |
| Lenovo H515s 10126                                                    | 1        | 0.81%   |
| Lenovo 10AB000KUS                                                     | 1        | 0.81%   |
| HUAWEI PUM-WDX9                                                       | 1        | 0.81%   |
| Huanan X99-QD4 V1.0                                                   | 1        | 0.81%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 0.81%   |
| HP Z400 Workstation                                                   | 1        | 0.81%   |
| HP ProLiant MicroServer Gen8                                          | 1        | 0.81%   |
| HP ProDesk 600 G1 SFF                                                 | 1        | 0.81%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 0.81%   |
| HP Compaq Elite 8300 SFF                                              | 1        | 0.81%   |
| Gigabyte Z97-D3H                                                      | 1        | 0.81%   |
| Gigabyte Z77M-D3H                                                     | 1        | 0.81%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 0.81%   |
| Gigabyte Z170X-UD5 TH                                                 | 1        | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Dell OptiPlex                                | 8        | 6.45%   |
| ASUS PRIME                                   | 8        | 6.45%   |
| ASUS ROG                                     | 5        | 4.03%   |
| MSI MS-7B86                                  | 3        | 2.42%   |
| Lenovo ThinkCentre                           | 3        | 2.42%   |
| Dell Precision                               | 3        | 2.42%   |
| ASUS TUF                                     | 3        | 2.42%   |
| ASRock X570                                  | 3        | 2.42%   |
| ASRock B450                                  | 3        | 2.42%   |
| MSI MS-7817                                  | 2        | 1.61%   |
| HP Compaq                                    | 2        | 1.61%   |
| Gigabyte GA-78LMT-USB3                       | 2        | 1.61%   |
| Fujitsu ESPRIMO                              | 2        | 1.61%   |
| ASUS SABERTOOTH                              | 2        | 1.61%   |
| ASUS All                                     | 2        | 1.61%   |
| Acer Aspire                                  | 2        | 1.61%   |
| Soyo SY-YL                                   | 1        | 0.81%   |
| Shenzhen Meigao Electronic Equipment UM480XT | 1        | 0.81%   |
| Quanta 120-1333w                             | 1        | 0.81%   |
| MSI MS-7D25                                  | 1        | 0.81%   |
| MSI MS-7C75                                  | 1        | 0.81%   |
| MSI MS-7C36                                  | 1        | 0.81%   |
| MSI MS-7B94                                  | 1        | 0.81%   |
| MSI MS-7B89                                  | 1        | 0.81%   |
| MSI MS-7B48                                  | 1        | 0.81%   |
| MSI MS-7B24                                  | 1        | 0.81%   |
| MSI MS-7A72                                  | 1        | 0.81%   |
| MSI MS-7996                                  | 1        | 0.81%   |
| MSI MS-7917                                  | 1        | 0.81%   |
| MSI MS-7788                                  | 1        | 0.81%   |
| Medion MS-7728                               | 1        | 0.81%   |
| LG R590-P.BE54P1                             | 1        | 0.81%   |
| Lenovo ThinkStation                          | 1        | 0.81%   |
| Lenovo IdeaCentre                            | 1        | 0.81%   |
| Lenovo H515s                                 | 1        | 0.81%   |
| Lenovo 10AB000KUS                            | 1        | 0.81%   |
| HUAWEI PUM-WDX9                              | 1        | 0.81%   |
| Huanan X99-QD4                               | 1        | 0.81%   |
| Huanan X79                                   | 1        | 0.81%   |
| HP Z400                                      | 1        | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 14       | 11.29%  |
| 2018 | 14       | 11.29%  |
| 2020 | 13       | 10.48%  |
| 2012 | 12       | 9.68%   |
| 2013 | 11       | 8.87%   |
| 2021 | 9        | 7.26%   |
| 2016 | 8        | 6.45%   |
| 2014 | 8        | 6.45%   |
| 2022 | 7        | 5.65%   |
| 2011 | 7        | 5.65%   |
| 2017 | 5        | 4.03%   |
| 2015 | 4        | 3.23%   |
| 2008 | 4        | 3.23%   |
| 2023 | 3        | 2.42%   |
| 2010 | 3        | 2.42%   |
| 2024 | 1        | 0.81%   |
| 2009 | 1        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 124      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 124      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 40       | 32%     |
| 8.01-16.0   | 33       | 26.4%   |
| 32.01-64.0  | 30       | 24%     |
| 4.01-8.0    | 14       | 11.2%   |
| 64.01-256.0 | 5        | 4%      |
| 24.01-32.0  | 3        | 2.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 52       | 41.6%   |
| 0.01-0.5 | 35       | 28%     |
| 1.01-2.0 | 32       | 25.6%   |
| 3.01-4.0 | 4        | 3.2%    |
| 2.01-3.0 | 2        | 1.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 36.72%  |
| 2      | 42       | 32.81%  |
| 4      | 10       | 7.81%   |
| 3      | 10       | 7.81%   |
| 0      | 7        | 5.47%   |
| 5      | 6        | 4.69%   |
| 6      | 4        | 3.13%   |
| 22     | 1        | 0.78%   |
| 7      | 1        | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 64.8%   |
| Yes       | 44       | 35.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 123      | 99.19%  |
| No        | 1        | 0.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 60.48%  |
| Yes       | 49       | 39.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 71.77%  |
| Yes       | 35       | 28.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 29       | 23.39%  |
| Germany      | 19       | 15.32%  |
| Russia       | 6        | 4.84%   |
| France       | 6        | 4.84%   |
| UK           | 4        | 3.23%   |
| Poland       | 4        | 3.23%   |
| Malaysia     | 3        | 2.42%   |
| Denmark      | 3        | 2.42%   |
| Canada       | 3        | 2.42%   |
| Brazil       | 3        | 2.42%   |
| Australia    | 3        | 2.42%   |
| Taiwan       | 2        | 1.61%   |
| Philippines  | 2        | 1.61%   |
| Paraguay     | 2        | 1.61%   |
| Norway       | 2        | 1.61%   |
| Netherlands  | 2        | 1.61%   |
| Czechia      | 2        | 1.61%   |
| Bulgaria     | 2        | 1.61%   |
| Austria      | 2        | 1.61%   |
| Argentina    | 2        | 1.61%   |
| Venezuela    | 1        | 0.81%   |
| Ukraine      | 1        | 0.81%   |
| Turkey       | 1        | 0.81%   |
| Switzerland  | 1        | 0.81%   |
| Sweden       | 1        | 0.81%   |
| Spain        | 1        | 0.81%   |
| South Africa | 1        | 0.81%   |
| Romania      | 1        | 0.81%   |
| Portugal     | 1        | 0.81%   |
| Peru         | 1        | 0.81%   |
| Morocco      | 1        | 0.81%   |
| Mexico       | 1        | 0.81%   |
| Luxembourg   | 1        | 0.81%   |
| Japan        | 1        | 0.81%   |
| Indonesia    | 1        | 0.81%   |
| Hungary      | 1        | 0.81%   |
| Hong Kong    | 1        | 0.81%   |
| Finland      | 1        | 0.81%   |
| El Salvador  | 1        | 0.81%   |
| China        | 1        | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Paris                       | 3        | 2.36%   |
| Frederiksberg               | 3        | 2.36%   |
| Denver                      | 3        | 2.36%   |
| Berlin                      | 3        | 2.36%   |
| Zdunska Wola                | 2        | 1.57%   |
| Vienna                      | 2        | 1.57%   |
| Tucson                      | 2        | 1.57%   |
| Taichung                    | 2        | 1.57%   |
| Sofia                       | 2        | 1.57%   |
| Obninsk                     | 2        | 1.57%   |
| Manila                      | 2        | 1.57%   |
| Hamburg                     | 2        | 1.57%   |
| Chelyabinsk                 | 2        | 1.57%   |
| Asunción                   | 2        | 1.57%   |
| ЕЊta-ku                   | 1        | 0.79%   |
| Zapopan                     | 1        | 0.79%   |
| Washington                  | 1        | 0.79%   |
| Warsaw                      | 1        | 0.79%   |
| Vigia                       | 1        | 0.79%   |
| Vidnoye                     | 1        | 0.79%   |
| Veenendaal                  | 1        | 0.79%   |
| Uelsen                      | 1        | 0.79%   |
| Truro                       | 1        | 0.79%   |
| Traunstein                  | 1        | 0.79%   |
| Tiznit                      | 1        | 0.79%   |
| Sydney                      | 1        | 0.79%   |
| Sun Prairie                 | 1        | 0.79%   |
| St. Albert                  | 1        | 0.79%   |
| St Petersburg               | 1        | 0.79%   |
| Springfield                 | 1        | 0.79%   |
| Southampton                 | 1        | 0.79%   |
| Solden                      | 1        | 0.79%   |
| Shatin                      | 1        | 0.79%   |
| Sarajevo                    | 1        | 0.79%   |
| San Salvador                | 1        | 0.79%   |
| San Nicolás de los Arroyos | 1        | 0.79%   |
| San Jose                    | 1        | 0.79%   |
| Salem                       | 1        | 0.79%   |
| Roesrath                    | 1        | 0.79%   |
| Robbins                     | 1        | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 63     | 19.64%  |
| Samsung Electronics | 38       | 49     | 16.96%  |
| Seagate             | 32       | 48     | 14.29%  |
| Crucial             | 19       | 27     | 8.48%   |
| Toshiba             | 12       | 15     | 5.36%   |
| SanDisk             | 9        | 14     | 4.02%   |
| Hitachi             | 9        | 9      | 4.02%   |
| Kingston            | 7        | 8      | 3.13%   |
| A-DATA Technology   | 7        | 8      | 3.13%   |
| Intel               | 4        | 4      | 1.79%   |
| HGST                | 4        | 4      | 1.79%   |
| PNY                 | 3        | 5      | 1.34%   |
| Phison              | 3        | 4      | 1.34%   |
| Micron Technology   | 3        | 3      | 1.34%   |
| Hikvision           | 3        | 4      | 1.34%   |
| OCZ                 | 2        | 2      | 0.89%   |
| Maxtor              | 2        | 2      | 0.89%   |
| Gigabyte Technology | 2        | 2      | 0.89%   |
| China               | 2        | 2      | 0.89%   |
| XrayDisk            | 1        | 1      | 0.45%   |
| XPG                 | 1        | 1      | 0.45%   |
| WD MediaMax         | 1        | 1      | 0.45%   |
| Vaseky              | 1        | 1      | 0.45%   |
| Transcend           | 1        | 1      | 0.45%   |
| SPCC                | 1        | 1      | 0.45%   |
| Plextor             | 1        | 1      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| Neo Forza           | 1        | 2      | 0.45%   |
| LITEONIT            | 1        | 1      | 0.45%   |
| LITEON              | 1        | 1      | 0.45%   |
| Lexar               | 1        | 1      | 0.45%   |
| LDLC                | 1        | 1      | 0.45%   |
| Intenso             | 1        | 1      | 0.45%   |
| HPT                 | 1        | 4      | 0.45%   |
| GOODRAM             | 1        | 1      | 0.45%   |
| Corsair             | 1        | 1      | 0.45%   |
| Apacer              | 1        | 1      | 0.45%   |
| AMD                 | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Crucial CT1000MX500SSD1 1TB     | 5        | 1.94%   |
| WDC WDS500G2B0A-00SM50 500GB    | 4        | 1.55%   |
| Toshiba DT01ACA050 500GB        | 4        | 1.55%   |
| Seagate ST500DM002-1BD142 500GB | 4        | 1.55%   |
| Samsung SSD 850 EVO 500GB       | 4        | 1.55%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.55%   |
| Seagate ST1000VM002-1SD102 1TB  | 3        | 1.16%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.16%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 2        | 0.78%   |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 0.78%   |
| WDC WD2002FAEX-007BA0 2TB       | 2        | 0.78%   |
| WDC WD2000JS-55MHB0 192GB       | 2        | 0.78%   |
| WDC WD10EZEX-21M2NA0 1TB        | 2        | 0.78%   |
| Toshiba Q300 480GB              | 2        | 0.78%   |
| Toshiba MQ01ABD100 1TB          | 2        | 0.78%   |
| Toshiba HDWD120 2TB             | 2        | 0.78%   |
| Seagate ST4000DM004-2CV104 4TB  | 2        | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.78%   |
| Samsung SSD 970 EVO 500GB       | 2        | 0.78%   |
| Samsung SSD 860 QVO 1TB         | 2        | 0.78%   |
| Samsung SSD 860 EVO 500GB       | 2        | 0.78%   |
| Samsung SSD 860 EVO 1TB         | 2        | 0.78%   |
| Samsung HM320JI 320GB           | 2        | 0.78%   |
| Phison Sabrent 512GB            | 2        | 0.78%   |
| Maxtor STM3320613AS 320GB       | 2        | 0.78%   |
| Kingston SA400M8240G 240GB      | 2        | 0.78%   |
| Hitachi HTS541612J9SA00 120GB   | 2        | 0.78%   |
| Hikvision HS-SSD-E100 512G      | 2        | 0.78%   |
| Crucial CT250MX500SSD1 250GB    | 2        | 0.78%   |
| A-DATA SU650 120GB              | 2        | 0.78%   |
| XrayDisk 1TB SSD                | 1        | 0.39%   |
| XPG GAMMIX S11 Pro 2TB          | 1        | 0.39%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.39%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 0.39%   |
| WDC WDS240G2G0C-00AJM0 240GB    | 1        | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB    | 1        | 0.39%   |
| WDC WDS200T2B0B-00YS70 2TB      | 1        | 0.39%   |
| WDC WDS200T2B0A-00SM50 2TB      | 1        | 0.39%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 33       | 45     | 33.67%  |
| Seagate             | 31       | 46     | 31.63%  |
| Toshiba             | 9        | 12     | 9.18%   |
| Hitachi             | 9        | 9      | 9.18%   |
| Samsung Electronics | 8        | 9      | 8.16%   |
| HGST                | 4        | 4      | 4.08%   |
| Maxtor              | 2        | 2      | 2.04%   |
| WD MediaMax         | 1        | 1      | 1.02%   |
| HPT                 | 1        | 4      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 25       | 29     | 25%     |
| Crucial             | 16       | 20     | 16%     |
| SanDisk             | 9        | 14     | 9%      |
| WDC                 | 8        | 11     | 8%      |
| Kingston            | 5        | 6      | 5%      |
| A-DATA Technology   | 4        | 4      | 4%      |
| Toshiba             | 3        | 3      | 3%      |
| PNY                 | 3        | 5      | 3%      |
| Hikvision           | 3        | 4      | 3%      |
| OCZ                 | 2        | 2      | 2%      |
| Micron Technology   | 2        | 2      | 2%      |
| Intel               | 2        | 2      | 2%      |
| China               | 2        | 2      | 2%      |
| XrayDisk            | 1        | 1      | 1%      |
| Vaseky              | 1        | 1      | 1%      |
| Transcend           | 1        | 1      | 1%      |
| SPCC                | 1        | 1      | 1%      |
| Seagate             | 1        | 1      | 1%      |
| Plextor             | 1        | 1      | 1%      |
| Patriot             | 1        | 1      | 1%      |
| Neo Forza           | 1        | 2      | 1%      |
| LITEONIT            | 1        | 1      | 1%      |
| LITEON              | 1        | 1      | 1%      |
| Lexar               | 1        | 1      | 1%      |
| Intenso             | 1        | 1      | 1%      |
| GOODRAM             | 1        | 1      | 1%      |
| Gigabyte Technology | 1        | 1      | 1%      |
| Apacer              | 1        | 1      | 1%      |
| AMD                 | 1        | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 74       | 132    | 42.77%  |
| SSD  | 71       | 121    | 41.04%  |
| NVMe | 28       | 43     | 16.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 253    | 80.14%  |
| NVMe | 28       | 43     | 19.86%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 87       | 133    | 52.1%   |
| 0.51-1.0   | 40       | 65     | 23.95%  |
| 1.01-2.0   | 24       | 31     | 14.37%  |
| 3.01-4.0   | 11       | 13     | 6.59%   |
| 4.01-10.0  | 4        | 9      | 2.4%    |
| 10.01-20.0 | 1        | 2      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 23.02%  |
| 251-500        | 28       | 22.22%  |
| 1-20           | 24       | 19.05%  |
| 501-1000       | 12       | 9.52%   |
| 51-100         | 10       | 7.94%   |
| Unknown        | 9        | 7.14%   |
| 21-50          | 8        | 6.35%   |
| 1001-2000      | 5        | 3.97%   |
| More than 3000 | 1        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 102      | 79.69%  |
| 21-50   | 14       | 10.94%  |
| Unknown | 9        | 7.03%   |
| 51-100  | 2        | 1.56%   |
| 251-500 | 1        | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 3      | 6.25%   |
| Samsung Electronics HM320JI 320GB | 2        | 2      | 6.25%   |
| Maxtor STM3320613AS 320GB         | 2        | 2      | 6.25%   |
| Hitachi HTS541612J9SA00 120GB     | 2        | 2      | 6.25%   |
| WDC WDS480G2G0A-00JH30 480GB      | 1        | 2      | 3.13%   |
| WDC WD800AAJS-00TDA0 80GB         | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-60WWPA0 500GB      | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 3.13%   |
| WDC WD20EZRX-19D8PB0 2TB          | 1        | 1      | 3.13%   |
| WDC WD10EZEX-21M2NA0 1TB          | 1        | 1      | 3.13%   |
| Toshiba MK3263GSX 320GB           | 1        | 1      | 3.13%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 3.13%   |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 3.13%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 3.13%   |
| Seagate ST3250310AS 250GB         | 1        | 1      | 3.13%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.13%   |
| Seagate ST31500541AS 1.5TB        | 1        | 1      | 3.13%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 3.13%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 2      | 3.13%   |
| OCZ AGILITY3 240GB                | 1        | 1      | 3.13%   |
| Hitachi HTS725032A9A364 320GB     | 1        | 1      | 3.13%   |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 3.13%   |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 3.13%   |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 3.13%   |
| Crucial CT480M500SSD1 480GB       | 1        | 1      | 3.13%   |
| Crucial CT1050MX300SSD1 1TB       | 1        | 1      | 3.13%   |
| Crucial CT1000MX500SSD1 1TB       | 1        | 1      | 3.13%   |
| A-DATA Technology SU650 120GB     | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 20%     |
| Seagate             | 6        | 9      | 20%     |
| Hitachi             | 6        | 6      | 20%     |
| Samsung Electronics | 3        | 4      | 10%     |
| Crucial             | 3        | 3      | 10%     |
| Toshiba             | 2        | 2      | 6.67%   |
| Maxtor              | 2        | 2      | 6.67%   |
| OCZ                 | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 9      | 25%     |
| Hitachi             | 6        | 6      | 25%     |
| WDC                 | 5        | 5      | 20.83%  |
| Samsung Electronics | 3        | 4      | 12.5%   |
| Toshiba             | 2        | 2      | 8.33%   |
| Maxtor              | 2        | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 28     | 78.57%  |
| SSD  | 6        | 7      | 21.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba MQ01ABD100 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 109      | 250    | 76.76%  |
| Malfunc  | 28       | 35     | 19.72%  |
| Detected | 4        | 10     | 2.82%   |
| Failed   | 1        | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 73       | 39.46%  |
| AMD                           | 51       | 27.57%  |
| Samsung Electronics           | 11       | 5.95%   |
| SanDisk                       | 7        | 3.78%   |
| ASMedia Technology            | 7        | 3.78%   |
| Phison Electronics            | 5        | 2.7%    |
| Micron/Crucial Technology     | 5        | 2.7%    |
| ADATA Technology              | 5        | 2.7%    |
| Kingston Technology Company   | 4        | 2.16%   |
| JMicron Technology            | 4        | 2.16%   |
| Marvell Technology Group      | 3        | 1.62%   |
| Micron Technology             | 2        | 1.08%   |
| Silicon Motion                | 1        | 0.54%   |
| Shenzhen Longsys Electronics  | 1        | 0.54%   |
| Seagate Technology            | 1        | 0.54%   |
| Realtek Semiconductor         | 1        | 0.54%   |
| Nvidia                        | 1        | 0.54%   |
| Integrated Technology Express | 1        | 0.54%   |
| HighPoint Technologies        | 1        | 0.54%   |
| Adaptec                       | 1        | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34       | 15.32%  |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 5.86%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 3.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.15%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 3.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.25%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.25%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 1.8%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 4        | 1.8%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 1.35%   |
| JMicron JMB362 SATA Controller                                                          | 3        | 1.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.35%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 1.35%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.35%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.9%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.9%    |
| Phison E12 NVMe Controller                                                              | 2        | 0.9%    |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 2        | 0.9%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.9%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.9%    |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.9%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 2        | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.45%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                       | 1        | 0.45%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                                   | 1        | 0.45%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.45%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 104      | 59.09%  |
| NVMe | 38       | 21.59%  |
| IDE  | 21       | 11.93%  |
| RAID | 10       | 5.68%   |
| SCSI | 2        | 1.14%   |
| SAS  | 1        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 73       | 58.87%  |
| AMD    | 51       | 41.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.42%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 2.42%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.42%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.42%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 2.42%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.42%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.61%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.61%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.61%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 1.61%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.61%   |
| AMD Ryzen 5 4600G with Radeon Graphics      | 2        | 1.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.61%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 1.61%   |
| Intel Xeon E-2236 CPU @ 3.40GHz             | 1        | 0.81%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.81%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.81%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.81%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.81%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH           | 1        | 0.81%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.81%   |
| Intel Xeon                                  | 1        | 0.81%   |
| Intel Unknown                               | 1        | 0.81%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 0.81%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.81%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.81%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 1        | 0.81%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.81%   |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1        | 0.81%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.81%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 0.81%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 1        | 0.81%   |
| Intel Core i9-10900KF CPU @ 3.70GHz         | 1        | 0.81%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.81%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.81%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.81%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.81%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 24       | 19.35%  |
| Intel Core i7           | 16       | 12.9%   |
| AMD Ryzen 5             | 16       | 12.9%   |
| AMD Ryzen 7             | 12       | 9.68%   |
| Intel Xeon              | 8        | 6.45%   |
| Other                   | 6        | 4.84%   |
| Intel Pentium           | 5        | 4.03%   |
| Intel Core i3           | 5        | 4.03%   |
| AMD Ryzen 9             | 5        | 4.03%   |
| AMD FX                  | 4        | 3.23%   |
| Intel Core i9           | 3        | 2.42%   |
| Intel Core 2 Quad       | 2        | 1.61%   |
| Intel Celeron           | 2        | 1.61%   |
| AMD Ryzen 3             | 2        | 1.61%   |
| AMD E1                  | 2        | 1.61%   |
| AMD A6                  | 2        | 1.61%   |
| Intel Pentium Silver    | 1        | 0.81%   |
| Intel Pentium Dual-Core | 1        | 0.81%   |
| Intel Core 2 Duo        | 1        | 0.81%   |
| AMD Ryzen Threadripper  | 1        | 0.81%   |
| AMD Ryzen 3 PRO         | 1        | 0.81%   |
| AMD Phenom II X4        | 1        | 0.81%   |
| AMD E2                  | 1        | 0.81%   |
| AMD Athlon X4           | 1        | 0.81%   |
| AMD Athlon              | 1        | 0.81%   |
| AMD A10                 | 1        | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 44       | 35.48%  |
| 6       | 18       | 14.52%  |
| 2       | 18       | 14.52%  |
| 12      | 14       | 11.29%  |
| 16      | 13       | 10.48%  |
| 8       | 6        | 4.84%   |
| 24      | 4        | 3.23%   |
| 10      | 3        | 2.42%   |
| 32      | 2        | 1.61%   |
| Unknown | 2        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 123      | 99.19%  |
| 2      | 1        | 0.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 83       | 66.94%  |
| 2       | 39       | 31.45%  |
| Unknown | 2        | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 15       | 12.1%   |
| Haswell       | 13       | 10.48%  |
| Zen 2         | 12       | 9.68%   |
| Zen+          | 11       | 8.87%   |
| Zen 3         | 11       | 8.87%   |
| IvyBridge     | 10       | 8.06%   |
| SandyBridge   | 9        | 7.26%   |
| Penryn        | 6        | 4.84%   |
| Skylake       | 5        | 4.03%   |
| Piledriver    | 5        | 4.03%   |
| Unknown       | 5        | 4.03%   |
| Nehalem       | 4        | 3.23%   |
| Zen           | 3        | 2.42%   |
| CometLake     | 3        | 2.42%   |
| Westmere      | 2        | 1.61%   |
| Jaguar        | 2        | 1.61%   |
| Excavator     | 2        | 1.61%   |
| Puma          | 1        | 0.81%   |
| K10           | 1        | 0.81%   |
| Goldmont plus | 1        | 0.81%   |
| Goldmont      | 1        | 0.81%   |
| Bulldozer     | 1        | 0.81%   |
| Bobcat        | 1        | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 61       | 46.92%  |
| AMD                        | 39       | 30%     |
| Intel                      | 29       | 22.31%  |
| Matrox Electronics Systems | 1        | 0.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 5.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 5.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.55%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 3.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 3.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.27%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 2.27%   |
| Intel HD Graphics 630                                                       | 3        | 2.27%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 3        | 2.27%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 2.27%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.52%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.52%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.52%   |
| Intel HD Graphics 530                                                       | 2        | 1.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 1.52%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.52%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.76%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.76%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.76%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.76%   |
| Nvidia GT215M [GeForce GT 335M]                                             | 1        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.76%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.76%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 54       | 43.55%  |
| 1 x AMD        | 37       | 29.84%  |
| 1 x Intel      | 24       | 19.35%  |
| Intel + Nvidia | 4        | 3.23%   |
| 2 x Nvidia     | 1        | 0.81%   |
| 2 x Intel      | 1        | 0.81%   |
| 2 x AMD        | 1        | 0.81%   |
| 1 x Matrox     | 1        | 0.81%   |
| AMD + Nvidia   | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 58.87%  |
| Proprietary | 51       | 41.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 40.8%   |
| 1.01-2.0   | 19       | 15.2%   |
| 0.51-1.0   | 14       | 11.2%   |
| 3.01-4.0   | 12       | 9.6%    |
| 7.01-8.0   | 11       | 8.8%    |
| 0.01-0.5   | 11       | 8.8%    |
| 5.01-6.0   | 3        | 2.4%    |
| 8.01-16.0  | 3        | 2.4%    |
| 2.01-3.0   | 1        | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 15.87%  |
| Dell                 | 14       | 11.11%  |
| Goldstar             | 12       | 9.52%   |
| BenQ                 | 9        | 7.14%   |
| Acer                 | 8        | 6.35%   |
| Hewlett-Packard      | 6        | 4.76%   |
| Philips              | 5        | 3.97%   |
| Ancor Communications | 5        | 3.97%   |
| ASUSTek Computer     | 4        | 3.17%   |
| ViewSonic            | 3        | 2.38%   |
| LG Electronics       | 3        | 2.38%   |
| Iiyama               | 3        | 2.38%   |
| AOC                  | 3        | 2.38%   |
| Vizio                | 2        | 1.59%   |
| Sony                 | 2        | 1.59%   |
| Mi                   | 2        | 1.59%   |
| Lenovo               | 2        | 1.59%   |
| Idek Iiyama          | 2        | 1.59%   |
| Fujitsu Siemens      | 2        | 1.59%   |
| WYT                  | 1        | 0.79%   |
| Toshiba              | 1        | 0.79%   |
| SANYO                | 1        | 0.79%   |
| SAC                  | 1        | 0.79%   |
| Pixio                | 1        | 0.79%   |
| Pioneer Electronic   | 1        | 0.79%   |
| Panasonic            | 1        | 0.79%   |
| OEM                  | 1        | 0.79%   |
| LG Display           | 1        | 0.79%   |
| Lenovo Group Limited | 1        | 0.79%   |
| ITE                  | 1        | 0.79%   |
| HannStar             | 1        | 0.79%   |
| Eizo                 | 1        | 0.79%   |
| DENON                | 1        | 0.79%   |
| CHD                  | 1        | 0.79%   |
| Belinea              | 1        | 0.79%   |
| ASRock               | 1        | 0.79%   |
| Apple                | 1        | 0.79%   |
| AMT International    | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch      | 3        | 2.29%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 3        | 2.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 1.53%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch   | 2        | 1.53%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1.53%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                      | 2        | 1.53%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 0.76%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 0.76%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 0.76%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 0.76%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch               | 1        | 0.76%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 0.76%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 0.76%   |
| Sony TV SNY4D04 1920x1080                                              | 1        | 0.76%   |
| Sony TV  *30 SNYC105 3840x2160 950x540mm 43.0-inch                     | 1        | 0.76%   |
| SANYO Casper SAN309A 1920x1080 470x280mm 21.5-inch                     | 1        | 0.76%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch   | 1        | 0.76%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1        | 0.76%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 0.76%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 0.76%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 630x360mm 28.6-inch      | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 700x390mm 31.5-inch   | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                       | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 0.76%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 600x340mm 27.2-inch      | 1        | 0.76%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch      | 1        | 0.76%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch      | 1        | 0.76%   |
| SAC LED MONITOR SAC952D 1920x1080 600x340mm 27.2-inch                  | 1        | 0.76%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 0.76%   |
| Pioneer Electronic LCD Monitor SC-1223 1920x1080                       | 1        | 0.76%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1        | 0.76%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 0.76%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 0.76%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 0.76%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                    | 1        | 0.76%   |
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                    | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 46.46%  |
| 3840x2160 (4K)     | 12       | 9.45%   |
| 2560x1440 (QHD)    | 12       | 9.45%   |
| 1600x900 (HD+)     | 7        | 5.51%   |
| 1280x1024 (SXGA)   | 7        | 5.51%   |
| 1680x1050 (WSXGA+) | 5        | 3.94%   |
| 2560x1080          | 4        | 3.15%   |
| Unknown            | 4        | 3.15%   |
| 1440x900 (WXGA+)   | 3        | 2.36%   |
| 1360x768           | 3        | 2.36%   |
| 1920x1200 (WUXGA)  | 2        | 1.57%   |
| 5120x1440          | 1        | 0.79%   |
| 4640x1080          | 1        | 0.79%   |
| 3840x1600          | 1        | 0.79%   |
| 3440x1440          | 1        | 0.79%   |
| 3200x1080          | 1        | 0.79%   |
| 2806x900           | 1        | 0.79%   |
| 2560x1600          | 1        | 0.79%   |
| 1920x540           | 1        | 0.79%   |
| 1366x768 (WXGA)    | 1        | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 21       | 17.07%  |
| 21      | 17       | 13.82%  |
| 24      | 16       | 13.01%  |
| Unknown | 15       | 12.2%   |
| 23      | 13       | 10.57%  |
| 19      | 13       | 10.57%  |
| 31      | 7        | 5.69%   |
| 22      | 4        | 3.25%   |
| 34      | 3        | 2.44%   |
| 54      | 2        | 1.63%   |
| 29      | 2        | 1.63%   |
| 65      | 1        | 0.81%   |
| 60      | 1        | 0.81%   |
| 57      | 1        | 0.81%   |
| 43      | 1        | 0.81%   |
| 40      | 1        | 0.81%   |
| 32      | 1        | 0.81%   |
| 28      | 1        | 0.81%   |
| 17      | 1        | 0.81%   |
| 16      | 1        | 0.81%   |
| 15      | 1        | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 45       | 37.82%  |
| 401-500     | 28       | 23.53%  |
| Unknown     | 15       | 12.61%  |
| 601-700     | 12       | 10.08%  |
| 351-400     | 5        | 4.2%    |
| 1001-1500   | 5        | 4.2%    |
| 701-800     | 4        | 3.36%   |
| 301-350     | 3        | 2.52%   |
| 801-900     | 1        | 0.84%   |
| 901-1000    | 1        | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 84       | 71.79%  |
| Unknown | 11       | 9.4%    |
| 16/10   | 9        | 7.69%   |
| 5/4     | 6        | 5.13%   |
| 21/9    | 4        | 3.42%   |
| 6/5     | 1        | 0.85%   |
| 32/9    | 1        | 0.85%   |
| 3/2     | 1        | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 45       | 36.89%  |
| 301-350        | 22       | 18.03%  |
| Unknown        | 15       | 12.3%   |
| 351-500        | 13       | 10.66%  |
| 151-200        | 13       | 10.66%  |
| More than 1000 | 5        | 4.1%    |
| 251-300        | 4        | 3.28%   |
| 501-1000       | 2        | 1.64%   |
| 141-150        | 1        | 0.82%   |
| 131-140        | 1        | 0.82%   |
| 101-110        | 1        | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 65       | 52.85%  |
| 101-120 | 27       | 21.95%  |
| Unknown | 15       | 12.2%   |
| 121-160 | 7        | 5.69%   |
| 1-50    | 5        | 4.07%   |
| 161-240 | 4        | 3.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 97       | 76.98%  |
| 2     | 16       | 12.7%   |
| 0     | 12       | 9.52%   |
| 3     | 1        | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 69       | 40.59%  |
| Intel                                 | 60       | 35.29%  |
| Qualcomm Atheros                      | 11       | 6.47%   |
| Broadcom                              | 9        | 5.29%   |
| TP-Link                               | 4        | 2.35%   |
| Ralink Technology                     | 4        | 2.35%   |
| Samsung Electronics                   | 2        | 1.18%   |
| Aquantia                              | 2        | 1.18%   |
| Ralink                                | 1        | 0.59%   |
| Qualcomm Atheros Communications       | 1        | 0.59%   |
| Qualcomm                              | 1        | 0.59%   |
| Nvidia                                | 1        | 0.59%   |
| Microchip Technology                  | 1        | 0.59%   |
| MediaTek                              | 1        | 0.59%   |
| Generic                               | 1        | 0.59%   |
| Edimax Technology                     | 1        | 0.59%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 55       | 28.21%  |
| Intel I211 Gigabit Network Connection                                          | 13       | 6.67%   |
| Intel Wi-Fi 6 AX200                                                            | 10       | 5.13%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7        | 3.59%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 3.08%   |
| Intel Ethernet Controller I225-V                                               | 4        | 2.05%   |
| Intel Ethernet Connection I217-LM                                              | 4        | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4        | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 1.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 3        | 1.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3        | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2        | 1.03%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2        | 1.03%   |
| Ralink RT5370 Wireless Adapter                                                 | 2        | 1.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.03%   |
| Intel Wireless 7265                                                            | 2        | 1.03%   |
| Intel Wireless 7260                                                            | 2        | 1.03%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2        | 1.03%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 1.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 2        | 1.03%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 1.03%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.03%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2        | 1.03%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2        | 1.03%   |
| Broadcom BCM43143 802.11bgn (1x1) Wireless Adapter                             | 2        | 1.03%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.03%   |
| TP-Link Wireless USB Adapter                                                   | 1        | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 0.51%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1        | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.51%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 1        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 0.51%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 25       | 47.17%  |
| Realtek Semiconductor                 | 8        | 15.09%  |
| Qualcomm Atheros                      | 5        | 9.43%   |
| TP-Link                               | 4        | 7.55%   |
| Ralink Technology                     | 4        | 7.55%   |
| Broadcom                              | 2        | 3.77%   |
| Ralink                                | 1        | 1.89%   |
| Qualcomm Atheros Communications       | 1        | 1.89%   |
| MediaTek                              | 1        | 1.89%   |
| Edimax Technology                     | 1        | 1.89%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                | 10       | 18.87%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 3        | 5.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 3        | 5.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                           | 2        | 3.77%   |
| Realtek RTL8188EE Wireless Network Adapter                                         | 2        | 3.77%   |
| Ralink RT5370 Wireless Adapter                                                     | 2        | 3.77%   |
| Intel Wireless 7265                                                                | 2        | 3.77%   |
| Intel Wireless 7260                                                                | 2        | 3.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                            | 2        | 3.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                   | 2        | 3.77%   |
| Broadcom BCM43143 802.11bgn (1x1) Wireless Adapter                                 | 2        | 3.77%   |
| TP-Link Wireless USB Adapter                                                       | 1        | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                       | 1        | 1.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                             | 1        | 1.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                         | 1        | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                 | 1        | 1.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                           | 1        | 1.89%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                             | 1        | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 1        | 1.89%   |
| Ralink RT5372 Wireless Adapter                                                     | 1        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                                    | 1        | 1.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                             | 1        | 1.89%   |
| Qualcomm Atheros AR9271 802.11n                                                    | 1        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 1        | 1.89%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]             | 1        | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                            | 1        | 1.89%   |
| Intel Wireless 8265 / 8275                                                         | 1        | 1.89%   |
| Intel Wireless 3165                                                                | 1        | 1.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                          | 1        | 1.89%   |
| Intel Centrino Wireless-N 105                                                      | 1        | 1.89%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                     | 1        | 1.89%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 66       | 48.18%  |
| Intel                 | 52       | 37.96%  |
| Broadcom              | 7        | 5.11%   |
| Qualcomm Atheros      | 6        | 4.38%   |
| Samsung Electronics   | 2        | 1.46%   |
| Aquantia              | 2        | 1.46%   |
| Qualcomm              | 1        | 0.73%   |
| Nvidia                | 1        | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 55       | 39.86%  |
| Intel I211 Gigabit Network Connection                                          | 13       | 9.42%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5        | 3.62%   |
| Intel Ethernet Controller I225-V                                               | 4        | 2.9%    |
| Intel Ethernet Connection I217-LM                                              | 4        | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 2.17%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 1.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2        | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.45%   |
| Intel Ethernet Connection I217-V                                               | 2        | 1.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.45%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 1.45%   |
| Intel 82579V Gigabit Network Connection                                        | 2        | 1.45%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.45%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2        | 1.45%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2        | 1.45%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.45%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1        | 0.72%   |
| Qualcomm FP3                                                                   | 1        | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.72%   |
| Nvidia MCP73 Ethernet                                                          | 1        | 0.72%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.72%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.72%   |
| Intel Ethernet Controller I226-V                                               | 1        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.72%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.72%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.72%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.72%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 1        | 0.72%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 1        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.72%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 0.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1        | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 124      | 69.66%  |
| WiFi     | 50       | 28.09%  |
| Modem    | 2        | 1.12%   |
| Unknown  | 2        | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 86.05%  |
| WiFi     | 18       | 13.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 64.52%  |
| 2     | 35       | 28.23%  |
| 3     | 8        | 6.45%   |
| 5     | 1        | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 98.39%  |
| Yes  | 2        | 1.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 21       | 60%     |
| Cambridge Silicon Radio  | 4        | 11.43%  |
| Realtek Semiconductor    | 2        | 5.71%   |
| Broadcom                 | 2        | 5.71%   |
| Skylight Digital         | 1        | 2.86%   |
| Qcom                     | 1        | 2.86%   |
| MediaTek                 | 1        | 2.86%   |
| HTC (High Tech Computer) | 1        | 2.86%   |
| ASUSTek Computer         | 1        | 2.86%   |
| Apple                    | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 8        | 22.86%  |
| Intel Bluetooth wireless interface                                   | 5        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4        | 11.43%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 8.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 5.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 5.71%   |
| Skylight Digital Realtek Bluetooth Adapter                           | 1        | 2.86%   |
| Realtek Bluetooth Adapter                                            | 1        | 2.86%   |
| Realtek Bluetooth 5.1 Adapter                                        | 1        | 2.86%   |
| Qcom Broadcom Bluetooth USB                                          | 1        | 2.86%   |
| MediaTek RZ608 Bluetooth Adapter                                     | 1        | 2.86%   |
| Intel AX211 Bluetooth                                                | 1        | 2.86%   |
| Intel AX210 Bluetooth                                                | 1        | 2.86%   |
| Intel AX201 Bluetooth                                                | 1        | 2.86%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.86%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1        | 2.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 67       | 31.46%  |
| AMD                  | 61       | 28.64%  |
| Nvidia               | 60       | 28.17%  |
| C-Media Electronics  | 5        | 2.35%   |
| Logitech             | 4        | 1.88%   |
| VIA Technologies     | 2        | 0.94%   |
| SteelSeries ApS      | 2        | 0.94%   |
| Focusrite-Novation   | 2        | 0.94%   |
| Creative Labs        | 2        | 0.94%   |
| Tenx Technology      | 1        | 0.47%   |
| RODE Microphones     | 1        | 0.47%   |
| Razer USA            | 1        | 0.47%   |
| Nam Tai E&E Products | 1        | 0.47%   |
| JMTek                | 1        | 0.47%   |
| GN Netcom            | 1        | 0.47%   |
| Creative Technology  | 1        | 0.47%   |
| Corsair              | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                            | 14       | 5.49%   |
| AMD Starship/Matisse HD Audio Controller                                              | 12       | 4.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 12       | 4.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                    | 10       | 3.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 9        | 3.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 8        | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 8        | 3.14%   |
| Nvidia GP108 High Definition Audio Controller                                         | 7        | 2.75%   |
| Nvidia GP104 High Definition Audio Controller                                         | 7        | 2.75%   |
| Nvidia GK107 HDMI Audio Controller                                                    | 7        | 2.75%   |
| Intel 200 Series PCH HD Audio                                                         | 7        | 2.75%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 6        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                            | 6        | 2.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 6        | 2.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 6        | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 6        | 2.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                          | 6        | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 6        | 2.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 5        | 1.96%   |
| AMD FCH Azalia Controller                                                             | 5        | 1.96%   |
| Nvidia TU106 High Definition Audio Controller                                         | 4        | 1.57%   |
| Nvidia GM206 High Definition Audio Controller                                         | 4        | 1.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 4        | 1.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                               | 4        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                              | 4        | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                                         | 3        | 1.18%   |
| Intel Alder Lake-S HD Audio Controller                                                | 3        | 1.18%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 3        | 1.18%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                         | 3        | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 3        | 1.18%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                         | 2        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                        | 2        | 0.78%   |
| Nvidia High Definition Audio Controller                                               | 2        | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                                    | 2        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                         | 2        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 2        | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                              | 2        | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 2        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                      | 2        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 27       | 18.24%  |
| G.Skill                      | 18       | 12.16%  |
| Samsung Electronics          | 14       | 9.46%   |
| SK hynix                     | 13       | 8.78%   |
| Corsair                      | 13       | 8.78%   |
| Crucial                      | 11       | 7.43%   |
| Unknown                      | 10       | 6.76%   |
| A-DATA Technology            | 5        | 3.38%   |
| Unknown                      | 5        | 3.38%   |
| Team                         | 4        | 2.7%    |
| Ramaxel Technology           | 4        | 2.7%    |
| Nanya Technology             | 3        | 2.03%   |
| Micron Technology            | 3        | 2.03%   |
| GOODRAM                      | 3        | 2.03%   |
| Wodposit                     | 1        | 0.68%   |
| Undefined-00BA               | 1        | 0.68%   |
| Timetec                      | 1        | 0.68%   |
| Tammuz                       | 1        | 0.68%   |
| SpecTek Incorporated         | 1        | 0.68%   |
| S                            | 1        | 0.68%   |
| Patriot Memory (PDP Systems) | 1        | 0.68%   |
| Patriot                      | 1        | 0.68%   |
| Kingmax                      | 1        | 0.68%   |
| Hewlett-Packard              | 1        | 0.68%   |
| GeIL                         | 1        | 0.68%   |
| Elpida                       | 1        | 0.68%   |
| CSX                          | 1        | 0.68%   |
| Avant                        | 1        | 0.68%   |
| Atermiter                    | 1        | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s    | 5        | 3.23%   |
| Unknown                                                  | 5        | 3.23%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 3        | 1.94%   |
| Team RAM Elite-1333 8GB DIMM DDR3 1333MT/s               | 2        | 1.29%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 1.29%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 2        | 1.29%   |
| GOODRAM RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s   | 2        | 1.29%   |
| Wodposit RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1        | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 0.65%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.65%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                | 1        | 0.65%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.65%   |
| Undefined-00BA RAM Module 4GB DIMM DDR3 1333MT/s         | 1        | 0.65%   |
| Timetec RAM SD4-2666 32GB SODIMM DDR4 2666MT/s           | 1        | 0.65%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2667MT/s       | 1        | 0.65%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s      | 1        | 0.65%   |
| Tammuz RAM TZD2G816U32-SK001 16GB DIMM DDR4 3200MT/s     | 1        | 0.65%   |
| SpecTek Incorporated RAM Module 16GB DIMM DDR4 3200MT/s  | 1        | 0.65%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.65%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 0.65%   |
| SK hynix RAM HMT41GU6DFR8A-PB 8GB DIMM DDR3 1600MT/s     | 1        | 0.65%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s     | 1        | 0.65%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s         | 1        | 0.65%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 0.65%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 0.65%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 0.65%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 0.65%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s   | 1        | 0.65%   |
| Samsung RAM VTP08G3U1600 8GB DIMM DDR3 1600MT/s          | 1        | 0.65%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.65%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s    | 1        | 0.65%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 68       | 53.97%  |
| DDR3    | 45       | 35.71%  |
| Unknown | 8        | 6.35%   |
| DDR2    | 3        | 2.38%   |
| SDRAM   | 1        | 0.79%   |
| DDR5    | 1        | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 111      | 88.8%   |
| SODIMM | 14       | 11.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 58       | 43.28%  |
| 4096  | 37       | 27.61%  |
| 16384 | 22       | 16.42%  |
| 2048  | 12       | 8.96%   |
| 32768 | 5        | 3.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 29       | 21.01%  |
| 3200  | 25       | 18.12%  |
| 1333  | 21       | 15.22%  |
| 2400  | 14       | 10.14%  |
| 2667  | 10       | 7.25%   |
| 2133  | 9        | 6.52%   |
| 2666  | 5        | 3.62%   |
| 3600  | 4        | 2.9%    |
| 1867  | 3        | 2.17%   |
| 1067  | 3        | 2.17%   |
| 1066  | 3        | 2.17%   |
| 800   | 3        | 2.17%   |
| 3000  | 2        | 1.45%   |
| 667   | 2        | 1.45%   |
| 4800  | 1        | 0.72%   |
| 3333  | 1        | 0.72%   |
| 3066  | 1        | 0.72%   |
| 2933  | 1        | 0.72%   |
| 1866  | 1        | 0.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP Laser 107a Printer | 1        | 50%     |
| Brother MFC-J485DW    | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 7        | 63.64%  |
| Xiongmai            | 1        | 9.09%   |
| Trust               | 1        | 9.09%   |
| Quanta              | 1        | 9.09%   |
| Chicony Electronics | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 3        | 27.27%  |
| Logitech HD Webcam C525               | 2        | 18.18%  |
| Xiongmai web camera                   | 1        | 9.09%   |
| Trust Trust USB Camera                | 1        | 9.09%   |
| Quanta LG Webcam                      | 1        | 9.09%   |
| Logitech Webcam C310                  | 1        | 9.09%   |
| Logitech C920 HD Pro Webcam           | 1        | 9.09%   |
| Chicony HP High Definition 1MP Webcam | 1        | 9.09%   |

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
| 1     | 61       | 49.19%  |
| 0     | 32       | 25.81%  |
| 2     | 26       | 20.97%  |
| 3     | 5        | 4.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 59       | 46.83%  |
| Bluetooth                | 21       | 16.67%  |
| Net/wireless             | 17       | 13.49%  |
| Firewire controller      | 9        | 7.14%   |
| Sound                    | 8        | 6.35%   |
| Network                  | 6        | 4.76%   |
| Card reader              | 3        | 2.38%   |
| Net/ethernet             | 2        | 1.59%   |
| Modem                    | 1        | 0.79%   |

