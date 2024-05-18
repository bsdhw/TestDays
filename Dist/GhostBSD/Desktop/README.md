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

Total: 143

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| GhostBSD 20.04.02 | 45       | 40.54%  |
| GhostBSD 24.01.1  | 13       | 11.71%  |
| GhostBSD 21.08.27 | 8        | 7.21%   |
| GhostBSD 23.10.1  | 6        | 5.41%   |
| GhostBSD 23.02.02 | 4        | 3.6%    |
| GhostBSD 22.01.12 | 4        | 3.6%    |
| GhostBSD 23.06.01 | 3        | 2.7%    |
| GhostBSD 22.11.22 | 3        | 2.7%    |
| GhostBSD 22.06.18 | 3        | 2.7%    |
| GhostBSD 22.09.16 | 2        | 1.8%    |
| GhostBSD 22.07.16 | 2        | 1.8%    |
| GhostBSD 22.04.06 | 2        | 1.8%    |
| GhostBSD 23.09.29 | 1        | 0.9%    |
| GhostBSD 23.09.06 | 1        | 0.9%    |
| GhostBSD 23.06.22 | 1        | 0.9%    |
| GhostBSD 23.05.18 | 1        | 0.9%    |
| GhostBSD 23.04.23 | 1        | 0.9%    |
| GhostBSD 23.03.17 | 1        | 0.9%    |
| GhostBSD 22.12.20 | 1        | 0.9%    |
| GhostBSD 22.11.02 | 1        | 0.9%    |
| GhostBSD 22.10.12 | 1        | 0.9%    |
| GhostBSD 22.08.23 | 1        | 0.9%    |
| GhostBSD 22.07.13 | 1        | 0.9%    |
| GhostBSD 22.06.26 | 1        | 0.9%    |
| GhostBSD 22.05.14 | 1        | 0.9%    |
| GhostBSD 22.04.22 | 1        | 0.9%    |
| GhostBSD 22.01.28 | 1        | 0.9%    |
| GhostBSD 19.12    | 1        | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GhostBSD | 105      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 105      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 81       | 75.7%   |
| XFCE             | 13       | 12.15%  |
| KDE5             | 7        | 6.54%   |
| openbox          | 1        | 0.93%   |
| Metacity (Marco) | 1        | 0.93%   |
| LXQt             | 1        | 0.93%   |
| i3               | 1        | 0.93%   |
| GNOME            | 1        | 0.93%   |
| Cinnamon         | 1        | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 105      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 102      | 97.14%  |
| SDDM    | 2        | 1.9%    |
| Console | 1        | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 48       | 45.28%  |
| C       | 21       | 19.81%  |
| Unknown | 12       | 11.32%  |
| de_DE   | 10       | 9.43%   |
| ru_RU   | 4        | 3.77%   |
| pt_BR   | 2        | 1.89%   |
| fr_FR   | 2        | 1.89%   |
| es_ES   | 2        | 1.89%   |
| en_AU   | 2        | 1.89%   |
| UTF-8   | 1        | 0.94%   |
| sk_SK   | 1        | 0.94%   |
| en_GB   | 1        | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 79       | 75.24%  |
| BIOS | 26       | 24.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 98       | 93.33%  |
| Ufs  | 7        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 98       | 93.33%  |
| MBR     | 6        | 5.71%   |
| Unknown | 1        | 0.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 25       | 23.81%  |
| Gigabyte Technology                  | 19       | 18.1%   |
| MSI                                  | 12       | 11.43%  |
| ASRock                               | 12       | 11.43%  |
| Dell                                 | 11       | 10.48%  |
| Lenovo                               | 6        | 5.71%   |
| Hewlett-Packard                      | 4        | 3.81%   |
| Huanan                               | 2        | 1.9%    |
| Fujitsu                              | 2        | 1.9%    |
| Acer                                 | 2        | 1.9%    |
| Soyo                                 | 1        | 0.95%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.95%   |
| Quanta                               | 1        | 0.95%   |
| Medion                               | 1        | 0.95%   |
| LG Electronics                       | 1        | 0.95%   |
| HUAWEI                               | 1        | 0.95%   |
| Casper                               | 1        | 0.95%   |
| Apple                                | 1        | 0.95%   |
| Alienware                            | 1        | 0.95%   |
| Unknown                              | 1        | 0.95%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 2        | 1.9%    |
| MSI MS-7817                                                           | 2        | 1.9%    |
| ASUS SABERTOOTH X58                                                   | 2        | 1.9%    |
| ASUS All Series                                                       | 2        | 1.9%    |
| Soyo SY-YL B550M                                                      | 1        | 0.95%   |
| Shenzhen Meigao Electronic Equipment UM480XT                          | 1        | 0.95%   |
| Quanta 120-1333w                                                      | 1        | 0.95%   |
| MSI MS-7C36                                                           | 1        | 0.95%   |
| MSI MS-7B94                                                           | 1        | 0.95%   |
| MSI MS-7B89                                                           | 1        | 0.95%   |
| MSI MS-7B48                                                           | 1        | 0.95%   |
| MSI MS-7B24                                                           | 1        | 0.95%   |
| MSI MS-7A72                                                           | 1        | 0.95%   |
| MSI MS-7917                                                           | 1        | 0.95%   |
| MSI MS-7788                                                           | 1        | 0.95%   |
| Medion MS-7728                                                        | 1        | 0.95%   |
| LG R590-P.BE54P1                                                      | 1        | 0.95%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 0.95%   |
| Lenovo ThinkCentre M93p 10AB004DUS                                    | 1        | 0.95%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 0.95%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL                           | 1        | 0.95%   |
| Lenovo H515s 10126                                                    | 1        | 0.95%   |
| Lenovo 10AB000KUS                                                     | 1        | 0.95%   |
| HUAWEI PUM-WDX9                                                       | 1        | 0.95%   |
| Huanan X99-QD4 V1.0                                                   | 1        | 0.95%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 0.95%   |
| HP Z400 Workstation                                                   | 1        | 0.95%   |
| HP ProLiant MicroServer Gen8                                          | 1        | 0.95%   |
| HP ProDesk 600 G1 SFF                                                 | 1        | 0.95%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 0.95%   |
| Gigabyte Z97-D3H                                                      | 1        | 0.95%   |
| Gigabyte Z77M-D3H                                                     | 1        | 0.95%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 0.95%   |
| Gigabyte Z170X-UD5 TH                                                 | 1        | 0.95%   |
| Gigabyte X670E AORUS MASTER                                           | 1        | 0.95%   |
| Gigabyte X570 AORUS MASTER                                            | 1        | 0.95%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1        | 0.95%   |
| Gigabyte Pentino Mini                                                 | 1        | 0.95%   |
| Gigabyte P55-USB3                                                     | 1        | 0.95%   |
| Gigabyte H67A-UD3H-B3                                                 | 1        | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Dell OptiPlex                                | 7        | 6.67%   |
| ASUS PRIME                                   | 7        | 6.67%   |
| ASUS ROG                                     | 5        | 4.76%   |
| Dell Precision                               | 3        | 2.86%   |
| ASUS TUF                                     | 3        | 2.86%   |
| ASRock X570                                  | 3        | 2.86%   |
| MSI MS-7B86                                  | 2        | 1.9%    |
| MSI MS-7817                                  | 2        | 1.9%    |
| Lenovo ThinkCentre                           | 2        | 1.9%    |
| Gigabyte GA-78LMT-USB3                       | 2        | 1.9%    |
| ASUS SABERTOOTH                              | 2        | 1.9%    |
| ASUS All                                     | 2        | 1.9%    |
| ASRock B450                                  | 2        | 1.9%    |
| Acer Aspire                                  | 2        | 1.9%    |
| Soyo SY-YL                                   | 1        | 0.95%   |
| Shenzhen Meigao Electronic Equipment UM480XT | 1        | 0.95%   |
| Quanta 120-1333w                             | 1        | 0.95%   |
| MSI MS-7C36                                  | 1        | 0.95%   |
| MSI MS-7B94                                  | 1        | 0.95%   |
| MSI MS-7B89                                  | 1        | 0.95%   |
| MSI MS-7B48                                  | 1        | 0.95%   |
| MSI MS-7B24                                  | 1        | 0.95%   |
| MSI MS-7A72                                  | 1        | 0.95%   |
| MSI MS-7917                                  | 1        | 0.95%   |
| MSI MS-7788                                  | 1        | 0.95%   |
| Medion MS-7728                               | 1        | 0.95%   |
| LG R590-P.BE54P1                             | 1        | 0.95%   |
| Lenovo ThinkStation                          | 1        | 0.95%   |
| Lenovo IdeaCentre                            | 1        | 0.95%   |
| Lenovo H515s                                 | 1        | 0.95%   |
| Lenovo 10AB000KUS                            | 1        | 0.95%   |
| HUAWEI PUM-WDX9                              | 1        | 0.95%   |
| Huanan X99-QD4                               | 1        | 0.95%   |
| Huanan X79                                   | 1        | 0.95%   |
| HP Z400                                      | 1        | 0.95%   |
| HP ProLiant                                  | 1        | 0.95%   |
| HP ProDesk                                   | 1        | 0.95%   |
| HP Compaq                                    | 1        | 0.95%   |
| Gigabyte Z97-D3H                             | 1        | 0.95%   |
| Gigabyte Z77M-D3H                            | 1        | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 14       | 13.33%  |
| 2019 | 12       | 11.43%  |
| 2013 | 11       | 10.48%  |
| 2020 | 10       | 9.52%   |
| 2012 | 9        | 8.57%   |
| 2014 | 8        | 7.62%   |
| 2022 | 7        | 6.67%   |
| 2011 | 7        | 6.67%   |
| 2021 | 6        | 5.71%   |
| 2016 | 6        | 5.71%   |
| 2008 | 4        | 3.81%   |
| 2017 | 3        | 2.86%   |
| 2015 | 3        | 2.86%   |
| 2023 | 2        | 1.9%    |
| 2010 | 2        | 1.9%    |
| 2009 | 1        | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 105      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 32       | 30.19%  |
| 8.01-16.0   | 29       | 27.36%  |
| 32.01-64.0  | 25       | 23.58%  |
| 4.01-8.0    | 13       | 12.26%  |
| 64.01-256.0 | 5        | 4.72%   |
| 24.01-32.0  | 2        | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 44       | 41.51%  |
| 0.01-0.5 | 33       | 31.13%  |
| 1.01-2.0 | 24       | 22.64%  |
| 3.01-4.0 | 4        | 3.77%   |
| 2.01-3.0 | 1        | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 37       | 33.94%  |
| 1      | 37       | 33.94%  |
| 4      | 10       | 9.17%   |
| 3      | 7        | 6.42%   |
| 5      | 6        | 5.5%    |
| 0      | 6        | 5.5%    |
| 6      | 4        | 3.67%   |
| 22     | 1        | 0.92%   |
| 7      | 1        | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 63.21%  |
| Yes       | 39       | 36.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 105      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 60.95%  |
| Yes       | 41       | 39.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 71.43%  |
| Yes       | 30       | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 26       | 24.76%  |
| Germany                | 16       | 15.24%  |
| Russia                 | 6        | 5.71%   |
| France                 | 6        | 5.71%   |
| UK                     | 4        | 3.81%   |
| Malaysia               | 3        | 2.86%   |
| Denmark                | 3        | 2.86%   |
| Canada                 | 3        | 2.86%   |
| Brazil                 | 3        | 2.86%   |
| Australia              | 3        | 2.86%   |
| Taiwan                 | 2        | 1.9%    |
| Norway                 | 2        | 1.9%    |
| Netherlands            | 2        | 1.9%    |
| Czechia                | 2        | 1.9%    |
| Bulgaria               | 2        | 1.9%    |
| Argentina              | 2        | 1.9%    |
| Ukraine                | 1        | 0.95%   |
| Turkey                 | 1        | 0.95%   |
| Switzerland            | 1        | 0.95%   |
| Sweden                 | 1        | 0.95%   |
| Spain                  | 1        | 0.95%   |
| South Africa           | 1        | 0.95%   |
| Romania                | 1        | 0.95%   |
| Peru                   | 1        | 0.95%   |
| Paraguay               | 1        | 0.95%   |
| Morocco                | 1        | 0.95%   |
| Mexico                 | 1        | 0.95%   |
| Luxembourg             | 1        | 0.95%   |
| Japan                  | 1        | 0.95%   |
| Hungary                | 1        | 0.95%   |
| Finland                | 1        | 0.95%   |
| El Salvador            | 1        | 0.95%   |
| China                  | 1        | 0.95%   |
| Bosnia and Herzegovina | 1        | 0.95%   |
| Belgium                | 1        | 0.95%   |
| Austria                | 1        | 0.95%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Paris                       | 3        | 2.8%    |
| Frederiksberg               | 3        | 2.8%    |
| Berlin                      | 3        | 2.8%    |
| Tucson                      | 2        | 1.87%   |
| Taichung                    | 2        | 1.87%   |
| Sofia                       | 2        | 1.87%   |
| Obninsk                     | 2        | 1.87%   |
| Denver                      | 2        | 1.87%   |
| Chelyabinsk                 | 2        | 1.87%   |
| ЕЊta-ku                   | 1        | 0.93%   |
| Zapopan                     | 1        | 0.93%   |
| Washington                  | 1        | 0.93%   |
| Vienna                      | 1        | 0.93%   |
| Vidnoye                     | 1        | 0.93%   |
| Veenendaal                  | 1        | 0.93%   |
| Uelsen                      | 1        | 0.93%   |
| Truro                       | 1        | 0.93%   |
| Traunstein                  | 1        | 0.93%   |
| Sydney                      | 1        | 0.93%   |
| Sun Prairie                 | 1        | 0.93%   |
| St. Albert                  | 1        | 0.93%   |
| St Petersburg               | 1        | 0.93%   |
| Springfield                 | 1        | 0.93%   |
| Southampton                 | 1        | 0.93%   |
| Solden                      | 1        | 0.93%   |
| Sarajevo                    | 1        | 0.93%   |
| San Salvador                | 1        | 0.93%   |
| San Nicolás de los Arroyos | 1        | 0.93%   |
| San Jose                    | 1        | 0.93%   |
| Salem                       | 1        | 0.93%   |
| Roesrath                    | 1        | 0.93%   |
| Robbins                     | 1        | 0.93%   |
| Riedstadt                   | 1        | 0.93%   |
| Richmond                    | 1        | 0.93%   |
| Remseck am Neckar           | 1        | 0.93%   |
| Prague                      | 1        | 0.93%   |
| Port Elizabeth              | 1        | 0.93%   |
| Phoenix                     | 1        | 0.93%   |
| Petaling Jaya               | 1        | 0.93%   |
| Perth                       | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 42       | 61     | 21.54%  |
| Samsung Electronics | 33       | 44     | 16.92%  |
| Seagate             | 28       | 40     | 14.36%  |
| Crucial             | 18       | 26     | 9.23%   |
| Toshiba             | 10       | 12     | 5.13%   |
| Hitachi             | 9        | 9      | 4.62%   |
| SanDisk             | 6        | 11     | 3.08%   |
| Kingston            | 6        | 7      | 3.08%   |
| A-DATA Technology   | 6        | 7      | 3.08%   |
| Intel               | 4        | 4      | 2.05%   |
| HGST                | 4        | 4      | 2.05%   |
| Phison              | 3        | 4      | 1.54%   |
| Micron Technology   | 3        | 3      | 1.54%   |
| PNY                 | 2        | 4      | 1.03%   |
| OCZ                 | 2        | 2      | 1.03%   |
| Maxtor              | 2        | 2      | 1.03%   |
| XrayDisk            | 1        | 1      | 0.51%   |
| XPG                 | 1        | 1      | 0.51%   |
| Vaseky              | 1        | 1      | 0.51%   |
| Transcend           | 1        | 1      | 0.51%   |
| SPCC                | 1        | 1      | 0.51%   |
| Plextor             | 1        | 1      | 0.51%   |
| Patriot             | 1        | 1      | 0.51%   |
| Neo Forza           | 1        | 2      | 0.51%   |
| Lexar               | 1        | 1      | 0.51%   |
| LDLC                | 1        | 1      | 0.51%   |
| HPT                 | 1        | 4      | 0.51%   |
| Hikvision           | 1        | 2      | 0.51%   |
| Gigabyte Technology | 1        | 1      | 0.51%   |
| Corsair             | 1        | 1      | 0.51%   |
| China               | 1        | 1      | 0.51%   |
| Apacer              | 1        | 1      | 0.51%   |
| AMD                 | 1        | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Crucial CT1000MX500SSD1 1TB     | 5        | 2.2%    |
| WDC WDS500G2B0A-00SM50 500GB    | 4        | 1.76%   |
| Samsung SSD 850 EVO 500GB       | 4        | 1.76%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.76%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.32%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.32%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 2        | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 0.88%   |
| WDC WD2000JS-55MHB0 192GB       | 2        | 0.88%   |
| WDC WD10EZEX-21M2NA0 1TB        | 2        | 0.88%   |
| Toshiba Q300 480GB              | 2        | 0.88%   |
| Toshiba MQ01ABD100 1TB          | 2        | 0.88%   |
| Toshiba HDWD120 2TB             | 2        | 0.88%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.88%   |
| Seagate ST4000DM004-2CV104 4TB  | 2        | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 0.88%   |
| Seagate ST1000VM002-1SD102 1TB  | 2        | 0.88%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.88%   |
| Samsung SSD 970 EVO 500GB       | 2        | 0.88%   |
| Samsung SSD 860 QVO 1TB         | 2        | 0.88%   |
| Samsung SSD 860 EVO 1TB         | 2        | 0.88%   |
| Phison Sabrent 1TB              | 2        | 0.88%   |
| Maxtor STM3320613AS 320GB       | 2        | 0.88%   |
| Kingston SA400M8240G 240GB      | 2        | 0.88%   |
| Hitachi HTS541612J9SA00 120GB   | 2        | 0.88%   |
| Crucial CT250MX500SSD1 250GB    | 2        | 0.88%   |
| XrayDisk 1TB SSD                | 1        | 0.44%   |
| XPG GAMMIX S11 Pro 256GB        | 1        | 0.44%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.44%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 0.44%   |
| WDC WDS240G2G0C-00AJM0 240GB    | 1        | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB    | 1        | 0.44%   |
| WDC WDS200T2B0B-00YS70 2TB      | 1        | 0.44%   |
| WDC WDS200T2B0A-00SM50 2TB      | 1        | 0.44%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.44%   |
| WDC WDS100T1X0E-00AFY0 1TB      | 1        | 0.44%   |
| WDC WD800BEVT-75ZCT2 80GB       | 1        | 0.44%   |
| WDC WD800AAJS-00TDA0 80GB       | 1        | 0.44%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 0.44%   |
| WDC WD60EZRZ-00GZ5B1 6TB        | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 43     | 36.05%  |
| Seagate             | 27       | 38     | 31.4%   |
| Hitachi             | 9        | 9      | 10.47%  |
| Toshiba             | 7        | 9      | 8.14%   |
| Samsung Electronics | 5        | 6      | 5.81%   |
| HGST                | 4        | 4      | 4.65%   |
| Maxtor              | 2        | 2      | 2.33%   |
| HPT                 | 1        | 4      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 27     | 27.71%  |
| Crucial             | 15       | 19     | 18.07%  |
| WDC                 | 8        | 11     | 9.64%   |
| SanDisk             | 6        | 11     | 7.23%   |
| Kingston            | 4        | 5      | 4.82%   |
| Toshiba             | 3        | 3      | 3.61%   |
| A-DATA Technology   | 3        | 3      | 3.61%   |
| PNY                 | 2        | 4      | 2.41%   |
| OCZ                 | 2        | 2      | 2.41%   |
| Micron Technology   | 2        | 2      | 2.41%   |
| Intel               | 2        | 2      | 2.41%   |
| XrayDisk            | 1        | 1      | 1.2%    |
| Vaseky              | 1        | 1      | 1.2%    |
| Transcend           | 1        | 1      | 1.2%    |
| SPCC                | 1        | 1      | 1.2%    |
| Seagate             | 1        | 1      | 1.2%    |
| Plextor             | 1        | 1      | 1.2%    |
| Patriot             | 1        | 1      | 1.2%    |
| Neo Forza           | 1        | 2      | 1.2%    |
| Lexar               | 1        | 1      | 1.2%    |
| Hikvision           | 1        | 2      | 1.2%    |
| China               | 1        | 1      | 1.2%    |
| Apacer              | 1        | 1      | 1.2%    |
| AMD                 | 1        | 1      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 64       | 115    | 42.11%  |
| SSD  | 60       | 104    | 39.47%  |
| NVMe | 28       | 43     | 18.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 95       | 219    | 77.24%  |
| NVMe | 28       | 43     | 22.76%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 71       | 110    | 50%     |
| 0.51-1.0   | 34       | 57     | 23.94%  |
| 1.01-2.0   | 21       | 28     | 14.79%  |
| 3.01-4.0   | 11       | 13     | 7.75%   |
| 4.01-10.0  | 4        | 9      | 2.82%   |
| 10.01-20.0 | 1        | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 24       | 22.64%  |
| 1-20           | 24       | 22.64%  |
| 101-250        | 22       | 20.75%  |
| 501-1000       | 12       | 11.32%  |
| Unknown        | 8        | 7.55%   |
| 51-100         | 7        | 6.6%    |
| 21-50          | 5        | 4.72%   |
| 1001-2000      | 3        | 2.83%   |
| More than 3000 | 1        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 84       | 77.78%  |
| 21-50   | 13       | 12.04%  |
| Unknown | 8        | 7.41%   |
| 51-100  | 2        | 1.85%   |
| 251-500 | 1        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 7.41%   |
| Maxtor STM3320613AS 320GB         | 2        | 2      | 7.41%   |
| Hitachi HTS541612J9SA00 120GB     | 2        | 2      | 7.41%   |
| WDC WDS480G2G0A-00JH30 480GB      | 1        | 2      | 3.7%    |
| WDC WD800AAJS-00TDA0 80GB         | 1        | 1      | 3.7%    |
| WDC WD5000AAKS-60WWPA0 500GB      | 1        | 1      | 3.7%    |
| WDC WD20EZRX-19D8PB0 2TB          | 1        | 1      | 3.7%    |
| WDC WD10EZEX-21M2NA0 1TB          | 1        | 1      | 3.7%    |
| Toshiba MK3263GSX 320GB           | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 3.7%    |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 1      | 3.7%    |
| Seagate ST3250310AS 250GB         | 1        | 1      | 3.7%    |
| Seagate ST31500541AS 1.5TB        | 1        | 1      | 3.7%    |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 1      | 3.7%    |
| Samsung Electronics HM320JI 320GB | 1        | 1      | 3.7%    |
| Samsung Electronics HD103SJ 1TB   | 1        | 2      | 3.7%    |
| OCZ AGILITY3 240GB                | 1        | 1      | 3.7%    |
| Hitachi HTS725032A9A364 320GB     | 1        | 1      | 3.7%    |
| Hitachi HTS547575A9E384 752GB     | 1        | 1      | 3.7%    |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 3.7%    |
| Hitachi HDS721616PLA380 160GB     | 1        | 1      | 3.7%    |
| Crucial CT480M500SSD1 480GB       | 1        | 1      | 3.7%    |
| Crucial CT1050MX300SSD1 1TB       | 1        | 1      | 3.7%    |
| Crucial CT1000MX500SSD1 1TB       | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 23.08%  |
| Hitachi             | 6        | 6      | 23.08%  |
| WDC                 | 5        | 6      | 19.23%  |
| Crucial             | 3        | 3      | 11.54%  |
| Samsung Electronics | 2        | 3      | 7.69%   |
| Maxtor              | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| OCZ                 | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 7      | 28.57%  |
| Hitachi             | 6        | 6      | 28.57%  |
| WDC                 | 4        | 4      | 19.05%  |
| Samsung Electronics | 2        | 3      | 9.52%   |
| Maxtor              | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 23     | 79.17%  |
| SSD  | 5        | 6      | 20.83%  |

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
| Works    | 93       | 222    | 76.23%  |
| Malfunc  | 24       | 29     | 19.67%  |
| Detected | 4        | 10     | 3.28%   |
| Failed   | 1        | 1      | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 62       | 38.75%  |
| AMD                           | 44       | 27.5%   |
| Samsung Electronics           | 11       | 6.88%   |
| SanDisk                       | 7        | 4.38%   |
| Phison Electronics            | 5        | 3.13%   |
| Micron/Crucial Technology     | 5        | 3.13%   |
| ASMedia Technology            | 5        | 3.13%   |
| ADATA Technology              | 4        | 2.5%    |
| Marvell Technology Group      | 3        | 1.88%   |
| Kingston Technology Company   | 3        | 1.88%   |
| JMicron Technology            | 3        | 1.88%   |
| Micron Technology             | 2        | 1.25%   |
| Silicon Motion                | 1        | 0.63%   |
| Seagate Technology            | 1        | 0.63%   |
| Nvidia                        | 1        | 0.63%   |
| Integrated Technology Express | 1        | 0.63%   |
| HighPoint Technologies        | 1        | 0.63%   |
| Adaptec                       | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29       | 15.26%  |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 4.74%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 3.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 3.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.16%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.63%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 2.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.11%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.58%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2        | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.05%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.05%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.05%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 1.05%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.05%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.05%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.05%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.05%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.53%   |
| Seagate FireCuda 520/IronWolf 525 SSD                                                   | 1        | 0.53%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.53%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 0.53%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 1        | 0.53%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                                   | 1        | 0.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 88       | 57.89%  |
| NVMe | 34       | 22.37%  |
| IDE  | 18       | 11.84%  |
| RAID | 9        | 5.92%   |
| SCSI | 2        | 1.32%   |
| SAS  | 1        | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 62       | 59.05%  |
| AMD    | 43       | 40.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.86%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.9%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.9%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 1.9%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2        | 1.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.9%    |
| AMD FX-8320 Eight-Core Processor            | 2        | 1.9%    |
| Intel Xeon E-2236 CPU @ 3.40GHz             | 1        | 0.95%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1        | 0.95%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 0.95%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 0.95%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 0.95%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH           | 1        | 0.95%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.95%   |
| Intel Xeon                                  | 1        | 0.95%   |
| Intel Unknown                               | 1        | 0.95%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 0.95%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.95%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.95%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 0.95%   |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1        | 0.95%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.95%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 0.95%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 1        | 0.95%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.95%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.95%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.95%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.95%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 0.95%   |
| Intel Core i7-2600K CPU                     | 1        | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.95%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1        | 0.95%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 0.95%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 0.95%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 20%     |
| Intel Core i7           | 15       | 14.29%  |
| AMD Ryzen 5             | 12       | 11.43%  |
| AMD Ryzen 7             | 11       | 10.48%  |
| Intel Xeon              | 8        | 7.62%   |
| AMD Ryzen 9             | 5        | 4.76%   |
| Intel Pentium           | 4        | 3.81%   |
| AMD FX                  | 4        | 3.81%   |
| Other                   | 3        | 2.86%   |
| Intel Core i3           | 3        | 2.86%   |
| Intel Core i9           | 2        | 1.9%    |
| Intel Core 2 Quad       | 2        | 1.9%    |
| AMD Ryzen 3             | 2        | 1.9%    |
| AMD E1                  | 2        | 1.9%    |
| Intel Pentium Silver    | 1        | 0.95%   |
| Intel Pentium Dual-Core | 1        | 0.95%   |
| Intel Core 2 Duo        | 1        | 0.95%   |
| Intel Celeron           | 1        | 0.95%   |
| AMD Ryzen Threadripper  | 1        | 0.95%   |
| AMD Ryzen 3 PRO         | 1        | 0.95%   |
| AMD E2                  | 1        | 0.95%   |
| AMD Athlon X4           | 1        | 0.95%   |
| AMD Athlon              | 1        | 0.95%   |
| AMD A6                  | 1        | 0.95%   |
| AMD A10                 | 1        | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 37       | 35.24%  |
| 6       | 14       | 13.33%  |
| 2       | 14       | 13.33%  |
| 12      | 13       | 12.38%  |
| 16      | 11       | 10.48%  |
| 8       | 6        | 5.71%   |
| 24      | 4        | 3.81%   |
| 32      | 2        | 1.9%    |
| 10      | 2        | 1.9%    |
| Unknown | 2        | 1.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 104      | 99.05%  |
| 2      | 1        | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 73       | 69.52%  |
| 2       | 30       | 28.57%  |
| Unknown | 2        | 1.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 13       | 12.38%  |
| Haswell       | 12       | 11.43%  |
| Zen 2         | 11       | 10.48%  |
| Zen+          | 10       | 9.52%   |
| Zen 3         | 8        | 7.62%   |
| SandyBridge   | 8        | 7.62%   |
| IvyBridge     | 8        | 7.62%   |
| Penryn        | 6        | 5.71%   |
| Piledriver    | 5        | 4.76%   |
| Skylake       | 4        | 3.81%   |
| Nehalem       | 4        | 3.81%   |
| Zen           | 3        | 2.86%   |
| Unknown       | 3        | 2.86%   |
| Westmere      | 2        | 1.9%    |
| CometLake     | 2        | 1.9%    |
| Puma          | 1        | 0.95%   |
| Jaguar        | 1        | 0.95%   |
| Goldmont plus | 1        | 0.95%   |
| Excavator     | 1        | 0.95%   |
| Bulldozer     | 1        | 0.95%   |
| Bobcat        | 1        | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 55       | 50%     |
| AMD                        | 30       | 27.27%  |
| Intel                      | 24       | 21.82%  |
| Matrox Electronics Systems | 1        | 0.91%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 6.25%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 4.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 4.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 3.57%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 3.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 2.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 2.68%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 2.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.79%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.79%   |
| Intel HD Graphics 630                                                       | 2        | 1.79%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 2        | 1.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 1.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.89%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.89%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.89%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.89%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.89%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.89%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.89%   |
| Nvidia GT218 [GeForce 405]                                                  | 1        | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.89%   |
| Nvidia GT215M [GeForce GT 335M]                                             | 1        | 0.89%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.89%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.89%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 0.89%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.89%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.89%   |
| Nvidia GK104 [GeForce GTX 760 OEM]                                          | 1        | 0.89%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.89%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 49       | 46.67%  |
| 1 x AMD        | 28       | 26.67%  |
| 1 x Intel      | 20       | 19.05%  |
| Intel + Nvidia | 3        | 2.86%   |
| 2 x Nvidia     | 1        | 0.95%   |
| 2 x Intel      | 1        | 0.95%   |
| 2 x AMD        | 1        | 0.95%   |
| 1 x Matrox     | 1        | 0.95%   |
| AMD + Nvidia   | 1        | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 60       | 57.14%  |
| Proprietary | 45       | 42.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 43.4%   |
| 1.01-2.0   | 14       | 13.21%  |
| 7.01-8.0   | 11       | 10.38%  |
| 0.51-1.0   | 11       | 10.38%  |
| 3.01-4.0   | 9        | 8.49%   |
| 0.01-0.5   | 9        | 8.49%   |
| 5.01-6.0   | 3        | 2.83%   |
| 8.01-16.0  | 2        | 1.89%   |
| 2.01-3.0   | 1        | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 14.81%  |
| Goldstar             | 11       | 10.19%  |
| Dell                 | 11       | 10.19%  |
| BenQ                 | 8        | 7.41%   |
| Acer                 | 7        | 6.48%   |
| Ancor Communications | 5        | 4.63%   |
| Philips              | 4        | 3.7%    |
| Hewlett-Packard      | 4        | 3.7%    |
| ViewSonic            | 3        | 2.78%   |
| LG Electronics       | 3        | 2.78%   |
| Iiyama               | 3        | 2.78%   |
| ASUSTek Computer     | 3        | 2.78%   |
| AOC                  | 3        | 2.78%   |
| Vizio                | 2        | 1.85%   |
| Mi                   | 2        | 1.85%   |
| Lenovo               | 2        | 1.85%   |
| Idek Iiyama          | 2        | 1.85%   |
| Fujitsu Siemens      | 2        | 1.85%   |
| WYT                  | 1        | 0.93%   |
| Toshiba              | 1        | 0.93%   |
| Sony                 | 1        | 0.93%   |
| SANYO                | 1        | 0.93%   |
| SAC                  | 1        | 0.93%   |
| Pixio                | 1        | 0.93%   |
| Pioneer Electronic   | 1        | 0.93%   |
| OEM                  | 1        | 0.93%   |
| LG Display           | 1        | 0.93%   |
| Lenovo Group Limited | 1        | 0.93%   |
| HannStar             | 1        | 0.93%   |
| DENON                | 1        | 0.93%   |
| CHD                  | 1        | 0.93%   |
| Belinea              | 1        | 0.93%   |
| ASRock               | 1        | 0.93%   |
| Apple                | 1        | 0.93%   |
| AMT International    | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch      | 3        | 2.65%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 3        | 2.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 1.77%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 0.88%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 0.88%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 0.88%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 0.88%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch               | 1        | 0.88%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 0.88%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 0.88%   |
| Sony TV SNY4D04 1920x1080                                              | 1        | 0.88%   |
| SANYO Casper SAN309A 1920x1080 470x280mm 21.5-inch                     | 1        | 0.88%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch   | 1        | 0.88%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1        | 0.88%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 0.88%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 0.88%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 700x390mm 31.5-inch   | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0678 1360x768                       | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 0.88%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 600x340mm 27.2-inch      | 1        | 0.88%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch      | 1        | 0.88%   |
| SAC LED MONITOR SAC952D 1920x1080 470x280mm 21.5-inch                  | 1        | 0.88%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 0.88%   |
| Pioneer Electronic LCD Monitor SC-1223 1920x1080                       | 1        | 0.88%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 0.88%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 0.88%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 0.88%   |
| Philips 221EL PHLC056 1920x1080 480x270mm 21.7-inch                    | 1        | 0.88%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1        | 0.88%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                   | 1        | 0.88%   |
| Mi 30 HFCW XMIA010 2560x1080 690x290mm 29.5-inch                       | 1        | 0.88%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1        | 0.88%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 0.88%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 0.88%   |
| LG Display LCD Monitor LGD020C 1600x900 350x190mm 15.7-inch            | 1        | 0.88%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 52       | 47.27%  |
| 2560x1440 (QHD)    | 12       | 10.91%  |
| 3840x2160 (4K)     | 8        | 7.27%   |
| 1600x900 (HD+)     | 5        | 4.55%   |
| 1280x1024 (SXGA)   | 5        | 4.55%   |
| 2560x1080          | 4        | 3.64%   |
| 1680x1050 (WSXGA+) | 4        | 3.64%   |
| Unknown            | 4        | 3.64%   |
| 1440x900 (WXGA+)   | 3        | 2.73%   |
| 1360x768           | 3        | 2.73%   |
| 5120x1440          | 1        | 0.91%   |
| 4640x1080          | 1        | 0.91%   |
| 3840x1600          | 1        | 0.91%   |
| 3440x1440          | 1        | 0.91%   |
| 3200x1080          | 1        | 0.91%   |
| 2806x900           | 1        | 0.91%   |
| 2560x1600          | 1        | 0.91%   |
| 1920x540           | 1        | 0.91%   |
| 1920x1200 (WUXGA)  | 1        | 0.91%   |
| 1366x768 (WXGA)    | 1        | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 18       | 17.14%  |
| 27      | 17       | 16.19%  |
| Unknown | 14       | 13.33%  |
| 24      | 12       | 11.43%  |
| 23      | 11       | 10.48%  |
| 19      | 10       | 9.52%   |
| 31      | 6        | 5.71%   |
| 34      | 3        | 2.86%   |
| 22      | 3        | 2.86%   |
| 54      | 2        | 1.9%    |
| 29      | 2        | 1.9%    |
| 65      | 1        | 0.95%   |
| 60      | 1        | 0.95%   |
| 40      | 1        | 0.95%   |
| 32      | 1        | 0.95%   |
| 17      | 1        | 0.95%   |
| 16      | 1        | 0.95%   |
| 15      | 1        | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 35       | 34.65%  |
| 401-500     | 27       | 26.73%  |
| Unknown     | 14       | 13.86%  |
| 601-700     | 10       | 9.9%    |
| 701-800     | 4        | 3.96%   |
| 1001-1500   | 4        | 3.96%   |
| 351-400     | 3        | 2.97%   |
| 301-350     | 3        | 2.97%   |
| 801-900     | 1        | 0.99%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 72       | 72%     |
| Unknown | 10       | 10%     |
| 16/10   | 7        | 7%      |
| 5/4     | 4        | 4%      |
| 21/9    | 4        | 4%      |
| 6/5     | 1        | 1%      |
| 32/9    | 1        | 1%      |
| 3/2     | 1        | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 40       | 38.46%  |
| 301-350        | 18       | 17.31%  |
| Unknown        | 14       | 13.46%  |
| 351-500        | 11       | 10.58%  |
| 151-200        | 10       | 9.62%   |
| More than 1000 | 4        | 3.85%   |
| 251-300        | 3        | 2.88%   |
| 141-150        | 1        | 0.96%   |
| 131-140        | 1        | 0.96%   |
| 101-110        | 1        | 0.96%   |
| 501-1000       | 1        | 0.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 52       | 49.52%  |
| 101-120 | 27       | 25.71%  |
| Unknown | 14       | 13.33%  |
| 121-160 | 6        | 5.71%   |
| 1-50    | 4        | 3.81%   |
| 161-240 | 2        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 74.77%  |
| 2     | 15       | 14.02%  |
| 0     | 11       | 10.28%  |
| 3     | 1        | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 55       | 38.46%  |
| Intel                                 | 52       | 36.36%  |
| Qualcomm Atheros                      | 11       | 7.69%   |
| Broadcom                              | 7        | 4.9%    |
| TP-Link                               | 3        | 2.1%    |
| Ralink Technology                     | 3        | 2.1%    |
| Samsung Electronics                   | 2        | 1.4%    |
| Aquantia                              | 2        | 1.4%    |
| Ralink                                | 1        | 0.7%    |
| Qualcomm Atheros Communications       | 1        | 0.7%    |
| Qualcomm                              | 1        | 0.7%    |
| Nvidia                                | 1        | 0.7%    |
| Microchip Technology                  | 1        | 0.7%    |
| MediaTek                              | 1        | 0.7%    |
| Generic                               | 1        | 0.7%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 42       | 25.3%   |
| Intel I211 Gigabit Network Connection                                          | 13       | 7.83%   |
| Intel Wi-Fi 6 AX200                                                            | 8        | 4.82%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 3.61%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 3.61%   |
| Intel Ethernet Connection I217-LM                                              | 4        | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 1.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 3        | 1.81%   |
| Intel Ethernet Controller I225-V                                               | 3        | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3        | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2        | 1.2%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2        | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                 | 2        | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.2%    |
| Intel Wireless 7265                                                            | 2        | 1.2%    |
| Intel Wireless 7260                                                            | 2        | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.2%    |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2        | 1.2%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2        | 1.2%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.2%    |
| TP-Link Wireless USB Adapter                                                   | 1        | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1        | 0.6%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 1        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 0.6%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                                | 1        | 0.6%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                         | 1        | 0.6%    |
| Qualcomm FP3                                                                   | 1        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                                | 1        | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 22       | 50%     |
| Realtek Semiconductor                 | 7        | 15.91%  |
| Qualcomm Atheros                      | 5        | 11.36%  |
| TP-Link                               | 3        | 6.82%   |
| Ralink Technology                     | 3        | 6.82%   |
| Ralink                                | 1        | 2.27%   |
| Qualcomm Atheros Communications       | 1        | 2.27%   |
| MediaTek                              | 1        | 2.27%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                | 8        | 18.18%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 3        | 6.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 3        | 6.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                           | 2        | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                         | 2        | 4.55%   |
| Ralink RT5370 Wireless Adapter                                                     | 2        | 4.55%   |
| Intel Wireless 7265                                                                | 2        | 4.55%   |
| Intel Wireless 7260                                                                | 2        | 4.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                            | 2        | 4.55%   |
| TP-Link Wireless USB Adapter                                                       | 1        | 2.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                       | 1        | 2.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                         | 1        | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                           | 1        | 2.27%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                             | 1        | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 1        | 2.27%   |
| Ralink MT7601U Wireless Adapter                                                    | 1        | 2.27%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                             | 1        | 2.27%   |
| Qualcomm Atheros AR9271 802.11n                                                    | 1        | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 1        | 2.27%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]             | 1        | 2.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                            | 1        | 2.27%   |
| Intel Wireless 8265 / 8275                                                         | 1        | 2.27%   |
| Intel Wireless 3165                                                                | 1        | 2.27%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                          | 1        | 2.27%   |
| Intel Centrino Wireless-N 105                                                      | 1        | 2.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                   | 1        | 2.27%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 53       | 44.92%  |
| Intel                 | 46       | 38.98%  |
| Broadcom              | 7        | 5.93%   |
| Qualcomm Atheros      | 6        | 5.08%   |
| Samsung Electronics   | 2        | 1.69%   |
| Aquantia              | 2        | 1.69%   |
| Qualcomm              | 1        | 0.85%   |
| Nvidia                | 1        | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 42       | 35.29%  |
| Intel I211 Gigabit Network Connection                                          | 13       | 10.92%  |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 5.04%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5        | 4.2%    |
| Intel Ethernet Connection I217-LM                                              | 4        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 2.52%   |
| Intel Ethernet Controller I225-V                                               | 3        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3        | 2.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 1.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 2        | 1.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 1.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2        | 1.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1.68%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 1.68%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2        | 1.68%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2        | 1.68%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 1.68%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1        | 0.84%   |
| Qualcomm FP3                                                                   | 1        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1        | 0.84%   |
| Nvidia MCP73 Ethernet                                                          | 1        | 0.84%   |
| Intel I350 Gigabit Network Connection                                          | 1        | 0.84%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 1        | 0.84%   |
| Intel Ethernet Controller I226-V                                               | 1        | 0.84%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                                           | 1        | 0.84%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 0.84%   |
| Intel Ethernet Connection (14) I219-V                                          | 1        | 0.84%   |
| Intel 82579V Gigabit Network Connection                                        | 1        | 0.84%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.84%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 1        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 0.84%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1        | 0.84%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                        | 1        | 0.84%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 1        | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 106      | 70.2%   |
| WiFi     | 42       | 27.81%  |
| Modem    | 2        | 1.32%   |
| Unknown  | 1        | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 95       | 84.82%  |
| WiFi     | 17       | 15.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 65       | 61.9%   |
| 2     | 31       | 29.52%  |
| 3     | 8        | 7.62%   |
| 5     | 1        | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 103      | 98.1%   |
| Yes  | 2        | 1.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 19       | 63.33%  |
| Cambridge Silicon Radio  | 2        | 6.67%   |
| Broadcom                 | 2        | 6.67%   |
| Skylight Digital         | 1        | 3.33%   |
| Realtek Semiconductor    | 1        | 3.33%   |
| Qcom                     | 1        | 3.33%   |
| MediaTek                 | 1        | 3.33%   |
| HTC (High Tech Computer) | 1        | 3.33%   |
| ASUSTek Computer         | 1        | 3.33%   |
| Apple                    | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 7        | 23.33%  |
| Intel Bluetooth wireless interface                                   | 5        | 16.67%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2        | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 6.67%   |
| Skylight Digital Realtek Bluetooth Adapter                           | 1        | 3.33%   |
| Realtek Bluetooth Adapter                                            | 1        | 3.33%   |
| Qcom Broadcom Bluetooth USB                                          | 1        | 3.33%   |
| MediaTek RZ608 Bluetooth Adapter                                     | 1        | 3.33%   |
| Intel AX211 Bluetooth                                                | 1        | 3.33%   |
| Intel AX210 Bluetooth                                                | 1        | 3.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.33%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1        | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 57       | 30.98%  |
| Nvidia               | 54       | 29.35%  |
| AMD                  | 51       | 27.72%  |
| Logitech             | 4        | 2.17%   |
| C-Media Electronics  | 4        | 2.17%   |
| VIA Technologies     | 2        | 1.09%   |
| SteelSeries ApS      | 2        | 1.09%   |
| Creative Labs        | 2        | 1.09%   |
| Tenx Technology      | 1        | 0.54%   |
| RODE Microphones     | 1        | 0.54%   |
| Razer USA            | 1        | 0.54%   |
| Nam Tai E&E Products | 1        | 0.54%   |
| JMTek                | 1        | 0.54%   |
| Focusrite-Novation   | 1        | 0.54%   |
| Creative Technology  | 1        | 0.54%   |
| Corsair              | 1        | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                              | 12       | 5.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 11       | 5.05%   |
| AMD Family 17h/19h HD Audio Controller                                                | 10       | 4.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 8        | 3.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 8        | 3.67%   |
| Nvidia GP104 High Definition Audio Controller                                         | 7        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 7        | 3.21%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 6        | 2.75%   |
| Nvidia GK107 HDMI Audio Controller                                                    | 6        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                            | 6        | 2.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 6        | 2.75%   |
| Intel 200 Series PCH HD Audio                                                         | 6        | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                    | 6        | 2.75%   |
| Nvidia GP108 High Definition Audio Controller                                         | 5        | 2.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 5        | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                          | 5        | 2.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 5        | 2.29%   |
| Nvidia TU106 High Definition Audio Controller                                         | 4        | 1.83%   |
| Nvidia GM206 High Definition Audio Controller                                         | 4        | 1.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 4        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 4        | 1.83%   |
| AMD FCH Azalia Controller                                                             | 4        | 1.83%   |
| Nvidia GP106 High Definition Audio Controller                                         | 3        | 1.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 3        | 1.38%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                         | 3        | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 3        | 1.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                               | 3        | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                              | 3        | 1.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 3        | 1.38%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2        | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                         | 2        | 0.92%   |
| Nvidia High Definition Audio Controller                                               | 2        | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                                         | 2        | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 2        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                              | 2        | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 2        | 0.92%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1        | 0.46%   |
| VIA Technologies USB Audio Device                                                     | 1        | 0.46%   |
| Tenx Technology USB  AUDIO                                                            | 1        | 0.46%   |
| RODE Microphones RDE NT-USB Mini                                                      | 1        | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 23       | 18.7%   |
| G.Skill                      | 16       | 13.01%  |
| Samsung Electronics          | 13       | 10.57%  |
| Corsair                      | 13       | 10.57%  |
| SK hynix                     | 10       | 8.13%   |
| Crucial                      | 9        | 7.32%   |
| Unknown                      | 8        | 6.5%    |
| A-DATA Technology            | 4        | 3.25%   |
| Unknown                      | 4        | 3.25%   |
| Team                         | 3        | 2.44%   |
| Nanya Technology             | 3        | 2.44%   |
| Ramaxel Technology           | 2        | 1.63%   |
| Micron Technology            | 2        | 1.63%   |
| Wodposit                     | 1        | 0.81%   |
| Undefined-00BA               | 1        | 0.81%   |
| Timetec                      | 1        | 0.81%   |
| S                            | 1        | 0.81%   |
| Patriot Memory (PDP Systems) | 1        | 0.81%   |
| Patriot                      | 1        | 0.81%   |
| Kingmax                      | 1        | 0.81%   |
| Hewlett-Packard              | 1        | 0.81%   |
| GeIL                         | 1        | 0.81%   |
| Elpida                       | 1        | 0.81%   |
| CSX                          | 1        | 0.81%   |
| Avant                        | 1        | 0.81%   |
| Atermiter                    | 1        | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s    | 5        | 3.88%   |
| Unknown                                                  | 4        | 3.1%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s      | 3        | 2.33%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s               | 2        | 1.55%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 2        | 1.55%   |
| Wodposit RAM WPBH32D408SWM-16G 16GB SODIMM DDR4 3200MT/s | 1        | 0.78%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.78%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.78%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                | 1        | 0.78%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 1        | 0.78%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.78%   |
| Undefined-00BA RAM Module 4GB DIMM DDR3 1333MT/s         | 1        | 0.78%   |
| Timetec RAM SD4-2666 32GB SODIMM DDR4 2666MT/s           | 1        | 0.78%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2667MT/s       | 1        | 0.78%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.78%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 0.78%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s     | 1        | 0.78%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.78%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s         | 1        | 0.78%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 0.78%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 0.78%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 1        | 0.78%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 0.78%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 0.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1        | 0.78%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.78%   |
| Samsung RAM M471B1G73QHO-YKO 4GB SODIMM DDR3 1600MT/s    | 1        | 0.78%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB DIMM DDR4 3200MT/s      | 1        | 0.78%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s          | 1        | 0.78%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s      | 1        | 0.78%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s      | 1        | 0.78%   |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s     | 1        | 0.78%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.78%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.78%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.78%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 1        | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 56       | 52.34%  |
| DDR3    | 39       | 36.45%  |
| Unknown | 7        | 6.54%   |
| DDR2    | 3        | 2.8%    |
| SDRAM   | 1        | 0.93%   |
| DDR5    | 1        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 96       | 90.57%  |
| SODIMM | 10       | 9.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 41.96%  |
| 4096  | 31       | 27.68%  |
| 16384 | 17       | 15.18%  |
| 2048  | 12       | 10.71%  |
| 32768 | 5        | 4.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 24       | 20.69%  |
| 3200  | 21       | 18.1%   |
| 1333  | 19       | 16.38%  |
| 2400  | 11       | 9.48%   |
| 2133  | 8        | 6.9%    |
| 2667  | 7        | 6.03%   |
| 2666  | 5        | 4.31%   |
| 1867  | 3        | 2.59%   |
| 1066  | 3        | 2.59%   |
| 800   | 3        | 2.59%   |
| 3600  | 2        | 1.72%   |
| 3000  | 2        | 1.72%   |
| 1067  | 2        | 1.72%   |
| 667   | 2        | 1.72%   |
| 4800  | 1        | 0.86%   |
| 3333  | 1        | 0.86%   |
| 3066  | 1        | 0.86%   |
| 2933  | 1        | 0.86%   |

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
| Logitech            | 6        | 60%     |
| Xiongmai            | 1        | 10%     |
| Trust               | 1        | 10%     |
| Quanta              | 1        | 10%     |
| Chicony Electronics | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Webcam C525               | 2        | 20%     |
| Logitech HD Pro Webcam C920           | 2        | 20%     |
| Xiongmai web camera                   | 1        | 10%     |
| Trust Trust USB Camera                | 1        | 10%     |
| Quanta LG Webcam                      | 1        | 10%     |
| Logitech Webcam C310                  | 1        | 10%     |
| Logitech C920 HD Pro Webcam           | 1        | 10%     |
| Chicony HP High Definition 1MP Webcam | 1        | 10%     |

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
| 1     | 56       | 53.33%  |
| 0     | 26       | 24.76%  |
| 2     | 19       | 18.1%   |
| 3     | 4        | 3.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 47       | 44.34%  |
| Bluetooth                | 20       | 18.87%  |
| Net/wireless             | 13       | 12.26%  |
| Firewire controller      | 9        | 8.49%   |
| Sound                    | 6        | 5.66%   |
| Network                  | 5        | 4.72%   |
| Card reader              | 3        | 2.83%   |
| Net/ethernet             | 2        | 1.89%   |
| Modem                    | 1        | 0.94%   |

