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

Total: 398

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 83EE                        | [c2a0b11bfa](https://bsd-hardware.info/?probe=c2a0b11bfa) | May 08, 2024 |
| AZW           | EQ                          | [edb4b64548](https://bsd-hardware.info/?probe=edb4b64548) | May 06, 2024 |
| Intel         | MAHOBAY                     | [dfe3417cfb](https://bsd-hardware.info/?probe=dfe3417cfb) | May 05, 2024 |
| Unknown       | Unknown                     | [c77ff29728](https://bsd-hardware.info/?probe=c77ff29728) | May 04, 2024 |
| Intel         | PB-X6000                    | [23a7529eaa](https://bsd-hardware.info/?probe=23a7529eaa) | May 04, 2024 |
| Unknown       | Unknown                     | [da95fe1264](https://bsd-hardware.info/?probe=da95fe1264) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | [25be1b099a](https://bsd-hardware.info/?probe=25be1b099a) | May 02, 2024 |
| Dell          | 0PC5F7 A00                  | [217f8e63db](https://bsd-hardware.info/?probe=217f8e63db) | May 01, 2024 |
| Unknown       | Unknown                     | [1c2459184f](https://bsd-hardware.info/?probe=1c2459184f) | Apr 28, 2024 |
| Protectli     | VP4630                      | [a128743268](https://bsd-hardware.info/?probe=a128743268) | Apr 25, 2024 |
| Dell          | 0DNMV1 A01                  | [97161dac8a](https://bsd-hardware.info/?probe=97161dac8a) | Apr 24, 2024 |
| Gigabyte      | H110M-H-CF                  | [2000d6447a](https://bsd-hardware.info/?probe=2000d6447a) | Apr 23, 2024 |
| Gigabyte      | H110M-H-CF                  | [3e1def845f](https://bsd-hardware.info/?probe=3e1def845f) | Apr 23, 2024 |
| Gigabyte      | X570 AORUS MASTER           | [58a64ecc64](https://bsd-hardware.info/?probe=58a64ecc64) | Apr 23, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d9b4db06cf](https://bsd-hardware.info/?probe=d9b4db06cf) | Apr 21, 2024 |
| Dell          | 0XCR8D A01                  | [716181ac45](https://bsd-hardware.info/?probe=716181ac45) | Apr 21, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [fe0730cde5](https://bsd-hardware.info/?probe=fe0730cde5) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [572876d341](https://bsd-hardware.info/?probe=572876d341) | Apr 20, 2024 |
| AZW           | EQ                          | [f822d4127d](https://bsd-hardware.info/?probe=f822d4127d) | Apr 20, 2024 |
| Intel         | Q3XXG4-P V1.0               | [dd5c8c3088](https://bsd-hardware.info/?probe=dd5c8c3088) | Apr 17, 2024 |
| Techvision    | TVI7309X B0                 | [7e1d43786b](https://bsd-hardware.info/?probe=7e1d43786b) | Apr 15, 2024 |
| Intel         | MAHOBAY                     | [9202be9d8d](https://bsd-hardware.info/?probe=9202be9d8d) | Apr 12, 2024 |
| Protectli     | VP4650                      | [95ce732272](https://bsd-hardware.info/?probe=95ce732272) | Apr 12, 2024 |
| Unknown       | Unknown                     | [bafb4c3fd6](https://bsd-hardware.info/?probe=bafb4c3fd6) | Apr 06, 2024 |
| Intel         | SKYBAY                      | [7d6e63d688](https://bsd-hardware.info/?probe=7d6e63d688) | Apr 02, 2024 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [893075f24f](https://bsd-hardware.info/?probe=893075f24f) | Apr 02, 2024 |
| HP            | 83E2                        | [c1765c598f](https://bsd-hardware.info/?probe=c1765c598f) | Apr 02, 2024 |
| Dell          | 0XCR8D A01                  | [39679bc463](https://bsd-hardware.info/?probe=39679bc463) | Apr 01, 2024 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [f89dd6d1c9](https://bsd-hardware.info/?probe=f89dd6d1c9) | Mar 31, 2024 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [28f484158e](https://bsd-hardware.info/?probe=28f484158e) | Mar 31, 2024 |
| Unknown       | Unknown                     | [673473a1a0](https://bsd-hardware.info/?probe=673473a1a0) | Mar 27, 2024 |
| MSI           | MS-B0A81                    | [17e87ae023](https://bsd-hardware.info/?probe=17e87ae023) | Mar 26, 2024 |
| Intel         | SKYBAY                      | [8aaca978dc](https://bsd-hardware.info/?probe=8aaca978dc) | Mar 26, 2024 |
| HP            | 82A2                        | [736b0fa24b](https://bsd-hardware.info/?probe=736b0fa24b) | Mar 26, 2024 |
| Unknown       | Unknown                     | [5b7761ce38](https://bsd-hardware.info/?probe=5b7761ce38) | Mar 23, 2024 |
| OEM           | PB-1900-A                   | [7172e173cb](https://bsd-hardware.info/?probe=7172e173cb) | Mar 19, 2024 |
| Unknown       | Unknown                     | [5e613125ca](https://bsd-hardware.info/?probe=5e613125ca) | Mar 10, 2024 |
| Unknown       | Unknown                     | [3dadeb1ccc](https://bsd-hardware.info/?probe=3dadeb1ccc) | Mar 08, 2024 |
| Intel         | QHSW02                      | [54d2883b0f](https://bsd-hardware.info/?probe=54d2883b0f) | Mar 08, 2024 |
| Unknown       | Unknown                     | [cf72715739](https://bsd-hardware.info/?probe=cf72715739) | Mar 07, 2024 |
| Techvision    | TVI7309X B0                 | [e8ed936537](https://bsd-hardware.info/?probe=e8ed936537) | Mar 06, 2024 |
| Unknown       | Unknown                     | [ed75f5f715](https://bsd-hardware.info/?probe=ed75f5f715) | Mar 05, 2024 |
| Dell          | 0XCR8D A02                  | [8919d9eb09](https://bsd-hardware.info/?probe=8919d9eb09) | Mar 05, 2024 |
| Dell          | 07F37C A00                  | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| MSI           | MS-B0A81                    | [2f6a08c240](https://bsd-hardware.info/?probe=2f6a08c240) | Mar 03, 2024 |
| Unknown       | Unknown                     | [83a5d4bd8b](https://bsd-hardware.info/?probe=83a5d4bd8b) | Mar 01, 2024 |
| HP            | 83EE                        | [0c83be53f1](https://bsd-hardware.info/?probe=0c83be53f1) | Feb 27, 2024 |
| Unknown       | Unknown                     | [dc82774d4b](https://bsd-hardware.info/?probe=dc82774d4b) | Feb 21, 2024 |
| Unknown       | Unknown                     | [c64774303d](https://bsd-hardware.info/?probe=c64774303d) | Feb 20, 2024 |
| Unknown       | Unknown                     | [e5e747ec86](https://bsd-hardware.info/?probe=e5e747ec86) | Feb 16, 2024 |
| Unknown       | Unknown                     | [7dc7c39f38](https://bsd-hardware.info/?probe=7dc7c39f38) | Feb 15, 2024 |
| Unknown       | Unknown                     | [7b626b5a2c](https://bsd-hardware.info/?probe=7b626b5a2c) | Feb 07, 2024 |
| HP            | 83EE                        | [3fdb0e4625](https://bsd-hardware.info/?probe=3fdb0e4625) | Feb 05, 2024 |
| HP            | 83EE                        | [92258e181d](https://bsd-hardware.info/?probe=92258e181d) | Feb 05, 2024 |
| Unknown       | Unknown                     | [5eb0f3d517](https://bsd-hardware.info/?probe=5eb0f3d517) | Jan 20, 2024 |
| Gigabyte      | J1900N-D3V                  | [4d9e3faf1d](https://bsd-hardware.info/?probe=4d9e3faf1d) | Jan 06, 2024 |
| Unknown       | Unknown                     | [3ae4489483](https://bsd-hardware.info/?probe=3ae4489483) | Jan 05, 2024 |
| HP            | 83EE                        | [cbfaae0ca7](https://bsd-hardware.info/?probe=cbfaae0ca7) | Jan 05, 2024 |
| Unknown       | Unknown                     | [0d4b103495](https://bsd-hardware.info/?probe=0d4b103495) | Jan 04, 2024 |
| Intel         | Q3XXG4-P V1.0               | [52345f2706](https://bsd-hardware.info/?probe=52345f2706) | Jan 02, 2024 |
| Hardkernel    | ODROID-H2                   | [959e70a37e](https://bsd-hardware.info/?probe=959e70a37e) | Jan 02, 2024 |
| Unknown       | Unknown                     | [5354734c83](https://bsd-hardware.info/?probe=5354734c83) | Dec 29, 2023 |
| Intel         | Q3XXG4-P V1.0               | [bc5f165c4a](https://bsd-hardware.info/?probe=bc5f165c4a) | Dec 29, 2023 |
| Unknown       | Unknown                     | [03f7101d55](https://bsd-hardware.info/?probe=03f7101d55) | Dec 25, 2023 |
| Dell          | 00V62H A00                  | [b99ed60ab6](https://bsd-hardware.info/?probe=b99ed60ab6) | Dec 18, 2023 |
| Dell          | 00V62H A00                  | [8f6f4d38d3](https://bsd-hardware.info/?probe=8f6f4d38d3) | Dec 17, 2023 |
| Techvision    | TVI7309X B0                 | [878769cc62](https://bsd-hardware.info/?probe=878769cc62) | Dec 17, 2023 |
| Lenovo        | SDK0E50510 WIN              | [57a4adcc91](https://bsd-hardware.info/?probe=57a4adcc91) | Dec 17, 2023 |
| Unknown       | Unknown                     | [784c8ae515](https://bsd-hardware.info/?probe=784c8ae515) | Dec 16, 2023 |
| HP            | 82A2                        | [906fd206fe](https://bsd-hardware.info/?probe=906fd206fe) | Dec 15, 2023 |
| HP            | 82A2                        | [0a816d2760](https://bsd-hardware.info/?probe=0a816d2760) | Dec 15, 2023 |
| Dell          | 0PC5F7 A00                  | [e47e643ced](https://bsd-hardware.info/?probe=e47e643ced) | Dec 14, 2023 |
| Intel         | DENLOW_WS                   | [d8b2ccabda](https://bsd-hardware.info/?probe=d8b2ccabda) | Nov 30, 2023 |
| Unknown       | Unknown                     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Unknown       | Unknown                     | [c8960ff614](https://bsd-hardware.info/?probe=c8960ff614) | Nov 22, 2023 |
| Unknown       | Unknown                     | [066991fce5](https://bsd-hardware.info/?probe=066991fce5) | Nov 16, 2023 |
| HP            | 213D A01                    | [eff9e5704a](https://bsd-hardware.info/?probe=eff9e5704a) | Nov 16, 2023 |
| Unknown       | Unknown                     | [696dae397c](https://bsd-hardware.info/?probe=696dae397c) | Nov 12, 2023 |
| Shenzhen M... | RPBNB                       | [ab2de15a7a](https://bsd-hardware.info/?probe=ab2de15a7a) | Nov 11, 2023 |
| Shenzhen M... | RPBNB                       | [b04823f9e5](https://bsd-hardware.info/?probe=b04823f9e5) | Nov 07, 2023 |
| Dell          | 0D24M8 A01                  | [4c874fa8af](https://bsd-hardware.info/?probe=4c874fa8af) | Nov 06, 2023 |
| Dell          | 0D24M8 A01                  | [3ca7f9b6d1](https://bsd-hardware.info/?probe=3ca7f9b6d1) | Nov 06, 2023 |
| Shuttle       | FS61                        | [1ed38ceb8c](https://bsd-hardware.info/?probe=1ed38ceb8c) | Nov 05, 2023 |
| Unknown       | Unknown                     | [97f4527aab](https://bsd-hardware.info/?probe=97f4527aab) | Nov 05, 2023 |
| HP            | 83EE                        | [1ab86be61a](https://bsd-hardware.info/?probe=1ab86be61a) | Nov 05, 2023 |
| HP            | 213D A01                    | [da7d91889e](https://bsd-hardware.info/?probe=da7d91889e) | Nov 03, 2023 |
| Unknown       | Unknown                     | [743d5aec59](https://bsd-hardware.info/?probe=743d5aec59) | Nov 02, 2023 |
| Intel         | Q3XXG4-P V1.0               | [cac29f9a35](https://bsd-hardware.info/?probe=cac29f9a35) | Oct 30, 2023 |
| Unknown       | Unknown                     | [850878776a](https://bsd-hardware.info/?probe=850878776a) | Oct 27, 2023 |
| HP            | 3397                        | [3dad1378f7](https://bsd-hardware.info/?probe=3dad1378f7) | Oct 27, 2023 |
| Winston Ma... | PICO PC V1.2                | [244102bda8](https://bsd-hardware.info/?probe=244102bda8) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [9b797e809a](https://bsd-hardware.info/?probe=9b797e809a) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [4dd20af1a3](https://bsd-hardware.info/?probe=4dd20af1a3) | Oct 26, 2023 |
| Intel         | MAHOBAY                     | [c66be142de](https://bsd-hardware.info/?probe=c66be142de) | Oct 26, 2023 |
| Unknown       | Unknown                     | [530528316f](https://bsd-hardware.info/?probe=530528316f) | Oct 21, 2023 |
| CWWK          | MINIPC-G12                  | [c51a6f8459](https://bsd-hardware.info/?probe=c51a6f8459) | Oct 20, 2023 |
| Unknown       | Unknown                     | [af12786272](https://bsd-hardware.info/?probe=af12786272) | Oct 18, 2023 |
| Unknown       | J3160-4L                    | [95e017977c](https://bsd-hardware.info/?probe=95e017977c) | Oct 14, 2023 |
| HP            | 83EE                        | [88d80d215a](https://bsd-hardware.info/?probe=88d80d215a) | Sep 30, 2023 |
| HP            | 83EE                        | [d08ae678b5](https://bsd-hardware.info/?probe=d08ae678b5) | Sep 28, 2023 |
| Unknown       | Unknown                     | [a5643cabc4](https://bsd-hardware.info/?probe=a5643cabc4) | Sep 24, 2023 |
| GoWin Solu... | R86S                        | [0cfd79f7fe](https://bsd-hardware.info/?probe=0cfd79f7fe) | Sep 18, 2023 |
| HP            | 82A2                        | [4f125fbc75](https://bsd-hardware.info/?probe=4f125fbc75) | Sep 17, 2023 |
| Unknown       | Unknown                     | [21e851e9e9](https://bsd-hardware.info/?probe=21e851e9e9) | Sep 07, 2023 |
| TYAN Compu... | S5510HE                     | [99d23c35ca](https://bsd-hardware.info/?probe=99d23c35ca) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| Unknown       | Unknown                     | [b5a786e411](https://bsd-hardware.info/?probe=b5a786e411) | Aug 18, 2023 |
| ASUSTek       | PRIME B450M-K               | [74bfa3e0cd](https://bsd-hardware.info/?probe=74bfa3e0cd) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | [064ee65b5c](https://bsd-hardware.info/?probe=064ee65b5c) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | [fd4046c4d9](https://bsd-hardware.info/?probe=fd4046c4d9) | Aug 07, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [f65647a6be](https://bsd-hardware.info/?probe=f65647a6be) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [eee3c082b5](https://bsd-hardware.info/?probe=eee3c082b5) | Aug 05, 2023 |
| Unknown       | Unknown                     | [e9977bfffe](https://bsd-hardware.info/?probe=e9977bfffe) | Aug 02, 2023 |
| HP            | 18E9                        | [04c971a0de](https://bsd-hardware.info/?probe=04c971a0de) | Jul 31, 2023 |
| HP            | 83E1                        | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Unknown       | Unknown                     | [64c9b0f743](https://bsd-hardware.info/?probe=64c9b0f743) | Jul 25, 2023 |
| ASRock        | H570M-ITX/ac                | [8ac2939575](https://bsd-hardware.info/?probe=8ac2939575) | Jul 23, 2023 |
| Lenovo        | SDK0E50510 WIN              | [63ab45fcb1](https://bsd-hardware.info/?probe=63ab45fcb1) | Jul 21, 2023 |
| Unknown       | Unknown                     | [5bea9c433e](https://bsd-hardware.info/?probe=5bea9c433e) | Jul 17, 2023 |
| YANYU         | H67SL                       | [699da6c722](https://bsd-hardware.info/?probe=699da6c722) | Jul 13, 2023 |
| Gigabyte      | M85M-US2H                   | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| PC Engines    | APU2                        | [c1272678e6](https://bsd-hardware.info/?probe=c1272678e6) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| HP            | 82A2                        | [4b8d139419](https://bsd-hardware.info/?probe=4b8d139419) | Jun 29, 2023 |
| Unknown       | Unknown                     | [23cdf1d4af](https://bsd-hardware.info/?probe=23cdf1d4af) | Jun 27, 2023 |
| Unknown       | Unknown                     | [a548b021da](https://bsd-hardware.info/?probe=a548b021da) | Jun 27, 2023 |
| YANYU         | H67SL                       | [5d5fd8a8cd](https://bsd-hardware.info/?probe=5d5fd8a8cd) | Jun 27, 2023 |
| HP            | 18E9                        | [aba608120b](https://bsd-hardware.info/?probe=aba608120b) | Jun 26, 2023 |
| Shuttle       | DH370                       | [95eb3bd4a8](https://bsd-hardware.info/?probe=95eb3bd4a8) | Jun 24, 2023 |
| Protectli     | FW4B                        | [6c993e8f34](https://bsd-hardware.info/?probe=6c993e8f34) | Jun 23, 2023 |
| Intel         | SKYBAY                      | [940adce39f](https://bsd-hardware.info/?probe=940adce39f) | Jun 23, 2023 |
| ASRock        | 4X4-4000 Series             | [c9420276e7](https://bsd-hardware.info/?probe=c9420276e7) | Jun 23, 2023 |
| Intel         | J1900                       | [4a3a52030b](https://bsd-hardware.info/?probe=4a3a52030b) | Jun 15, 2023 |
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
| Hardkernel    | ODROID-H2                   | [adcfe67709](https://bsd-hardware.info/?probe=adcfe67709) | Feb 16, 2022 |
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
| Hardkernel    | ODROID-H2                   | [63850e668d](https://bsd-hardware.info/?probe=63850e668d) | Oct 16, 2021 |
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
| Hardkernel    | ODROID-H2                   | [bcaa207f9b](https://bsd-hardware.info/?probe=bcaa207f9b) | Apr 05, 2021 |
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
| Hardkernel    | ODROID-H2                   | [1f25ddeb54](https://bsd-hardware.info/?probe=1f25ddeb54) | Feb 20, 2021 |
| Unknown       | Unknown                     | [6b724a36cd](https://bsd-hardware.info/?probe=6b724a36cd) | Feb 19, 2021 |
| Unknown       | Unknown                     | [baf854930a](https://bsd-hardware.info/?probe=baf854930a) | Feb 19, 2021 |
| ASRock        | B365M Pro4                  | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| Intel         | DN2820FYK H24582-201        | [be56203e79](https://bsd-hardware.info/?probe=be56203e79) | Feb 15, 2021 |
| ASUSTek       | P5E3                        | [1d1edd3551](https://bsd-hardware.info/?probe=1d1edd3551) | Feb 08, 2021 |
| Yanling       | YL-KBR6L Ver:1.00           | [98e358b324](https://bsd-hardware.info/?probe=98e358b324) | Feb 05, 2021 |
| Radxa         | ROCK Pi X v1.4              | [688c95bda6](https://bsd-hardware.info/?probe=688c95bda6) | Feb 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a7b2c5457c](https://bsd-hardware.info/?probe=a7b2c5457c) | Jan 29, 2021 |
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
| OPNsense 24.1.6   | 12       | 3.77%   |
| OPNsense 23.7.10  | 11       | 3.46%   |
| OPNsense 23.1.11  | 11       | 3.46%   |
| OPNsense 24.1.4   | 8        | 2.52%   |
| OPNsense 23.7.7   | 8        | 2.52%   |
| OPNsense 22.7.10  | 8        | 2.52%   |
| OPNsense 22.1     | 8        | 2.52%   |
| OPNsense 22.7.6   | 7        | 2.2%    |
| OPNsense 24.1.2   | 6        | 1.89%   |
| OPNsense 23.1.8   | 6        | 1.89%   |
| OPNsense 23.1.5   | 6        | 1.89%   |
| OPNsense 23.1.10  | 6        | 1.89%   |
| OPNsense 24.1.5   | 5        | 1.57%   |
| OPNsense 22.7.9   | 5        | 1.57%   |
| OPNsense 22.7.4   | 5        | 1.57%   |
| OPNsense 21.7.7   | 5        | 1.57%   |
| OPNsense 21.7.2   | 5        | 1.57%   |
| OPNsense 21.1.4   | 5        | 1.57%   |
| OPNsense 20.7.8   | 5        | 1.57%   |
| helloSystem 0.8.1 | 5        | 1.57%   |
| OPNsense 23.7     | 4        | 1.26%   |
| OPNsense 23.1.7   | 4        | 1.26%   |
| OPNsense 23.1.1   | 4        | 1.26%   |
| OPNsense 22.1.6   | 4        | 1.26%   |
| OPNsense 22.1.4   | 4        | 1.26%   |
| OPNsense 22.1.10  | 4        | 1.26%   |
| OPNsense 21.7.3   | 4        | 1.26%   |
| OPNsense 21.1.5   | 4        | 1.26%   |
| OPNsense 21.1.2   | 4        | 1.26%   |
| OPNsense 21.1     | 4        | 1.26%   |
| helloSystem 0.7.0 | 4        | 1.26%   |
| helloSystem 0.5.0 | 4        | 1.26%   |
| OPNsense 24.1.3   | 3        | 0.94%   |
| OPNsense 23.7.3   | 3        | 0.94%   |
| OPNsense 23.7.11  | 3        | 0.94%   |
| OPNsense 23.1.9   | 3        | 0.94%   |
| OPNsense 23.1.4   | 3        | 0.94%   |
| OPNsense 23.1     | 3        | 0.94%   |
| OPNsense 22.7.5   | 3        | 0.94%   |
| OPNsense 22.7.3   | 3        | 0.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 176      | 73.95%  |
| FreeBSD     | 26       | 10.92%  |
| helloSystem | 18       | 7.56%   |
| TrueNAS     | 5        | 2.1%    |
| OpenBSD     | 5        | 2.1%    |
| GhostBSD    | 3        | 1.26%   |
| FreeNAS     | 2        | 0.84%   |
| XigmaNAS    | 1        | 0.42%   |
| NomadBSD    | 1        | 0.42%   |
| NetBSD      | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 235      | 99.16%  |
| i386  | 1        | 0.42%   |
| arm64 | 1        | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 192      | 80.33%  |
| helloDesktop | 22       | 9.21%   |
| KDE5         | 9        | 3.77%   |
| XFCE         | 7        | 2.93%   |
| TWM          | 2        | 0.84%   |
| GNOME        | 2        | 0.84%   |
| xinitrc      | 1        | 0.42%   |
| Openbox      | 1        | 0.42%   |
| MATE         | 1        | 0.42%   |
| Lumina       | 1        | 0.42%   |
| i3           | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 199      | 83.61%  |
| X11     | 38       | 15.97%  |
| Wayland | 1        | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 200      | 84.39%  |
| SLiM    | 20       | 8.44%   |
| SDDM    | 8        | 3.38%   |
| LightDM | 6        | 2.53%   |
| XDM     | 3        | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 186      | 76.86%  |
| en_US   | 23       | 9.5%    |
| C       | 21       | 8.68%   |
| en_AU   | 9        | 3.72%   |
| fr_FR   | 1        | 0.41%   |
| fr      | 1        | 0.41%   |
| en      | 1        | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 202      | 85.23%  |
| BIOS | 35       | 14.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 140      | 57.61%  |
| Zfs    | 90       | 37.04%  |
| Cd9660 | 8        | 3.29%   |
| Ffs    | 5        | 2.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 223      | 94.09%  |
| MBR     | 12       | 5.06%   |
| BSD     | 1        | 0.42%   |
| Unknown | 1        | 0.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 37       | 15.61%  |
| Dell                                 | 29       | 12.24%  |
| Hewlett-Packard                      | 24       | 10.13%  |
| Gigabyte Technology                  | 19       | 8.02%   |
| Protectli                            | 18       | 7.59%   |
| ASUSTek Computer                     | 18       | 7.59%   |
| Lenovo                               | 14       | 5.91%   |
| Intel                                | 14       | 5.91%   |
| ASRock                               | 11       | 4.64%   |
| Techvision                           | 6        | 2.53%   |
| Acer                                 | 6        | 2.53%   |
| MSI                                  | 5        | 2.11%   |
| PC Engines                           | 4        | 1.69%   |
| Shuttle                              | 3        | 1.27%   |
| AZW                                  | 3        | 1.27%   |
| MW                                   | 2        | 0.84%   |
| Inventec                             | 2        | 0.84%   |
| CWWK                                 | 2        | 0.84%   |
| YANYU                                | 1        | 0.42%   |
| Yanling                              | 1        | 0.42%   |
| Winston Marriot                      | 1        | 0.42%   |
| Unknown                              | 1        | 0.42%   |
| TYAN Computer                        | 1        | 0.42%   |
| ShenZhen MinWin Technology           | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.42%   |
| SeeedStudio                          | 1        | 0.42%   |
| Radxa                                | 1        | 0.42%   |
| OEM                                  | 1        | 0.42%   |
| IBM                                  | 1        | 0.42%   |
| Hardkernel                           | 1        | 0.42%   |
| GoWin Solution                       | 1        | 0.42%   |
| Gateway                              | 1        | 0.42%   |
| Foxconn                              | 1        | 0.42%   |
| Cisco                                | 1        | 0.42%   |
| AOpen                                | 1        | 0.42%   |
| AMD                                  | 1        | 0.42%   |
| ADI Engineering                      | 1        | 0.42%   |
| AAEON                                | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 38       | 16.03%  |
| Protectli FW4B                                    | 10       | 4.22%   |
| Dell OptiPlex 9020                                | 8        | 3.38%   |
| Techvision TVI7309X                               | 6        | 2.53%   |
| Intel MAHOBAY                                     | 4        | 1.69%   |
| HP ProLiant MicroServer                           | 4        | 1.69%   |
| Dell OptiPlex 7040                                | 4        | 1.69%   |
| Protectli VP2410                                  | 3        | 1.27%   |
| HP ProDesk 400 G4 SFF                             | 3        | 1.27%   |
| Protectli FW2B                                    | 2        | 0.84%   |
| PC Engines APU2                                   | 2        | 0.84%   |
| MW GMLK-2_5G4L                                    | 2        | 0.84%   |
| Intel QHSW02                                      | 2        | 0.84%   |
| Intel Q3XXG4-P V1.0                               | 2        | 0.84%   |
| HP ProLiant MicroServer Gen8                      | 2        | 0.84%   |
| Gigabyte J1900N-D3V                               | 2        | 0.84%   |
| Dell OptiPlex 7050                                | 2        | 0.84%   |
| Dell OptiPlex 3040                                | 2        | 0.84%   |
| Dell OptiPlex 3010                                | 2        | 0.84%   |
| ASUS STRIX Z270I GAMING                           | 2        | 0.84%   |
| ASUS All Series                                   | 2        | 0.84%   |
| YANYU H67SL                                       | 1        | 0.42%   |
| Yanling YL-KBR6L                                  | 1        | 0.42%   |
| Winston Marriot PICO PC V1.2                      | 1        | 0.42%   |
| TYAN S5510HE                                      | 1        | 0.42%   |
| Shuttle DS81D                                     | 1        | 0.42%   |
| Shuttle DS61                                      | 1        | 0.42%   |
| Shuttle DH370                                     | 1        | 0.42%   |
| ShenZhen MinWin MW-NANO-APL-4L                    | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment Venus Series | 1        | 0.42%   |
| SeeedStudio ODYSSEY-X86J4125                      | 1        | 0.42%   |
| Radxa ROCK Pi X                                   | 1        | 0.42%   |
| Protectli VP4650                                  | 1        | 0.42%   |
| Protectli VP4630                                  | 1        | 0.42%   |
| Protectli FW6                                     | 1        | 0.42%   |
| PC Engines apu4                                   | 1        | 0.42%   |
| PC Engines apu1                                   | 1        | 0.42%   |
| OEM PB-1900-A                                     | 1        | 0.42%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)                    | 1        | 0.42%   |
| MSI Pro 3130 Small Form Factor PC                 | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 38       | 16.03%  |
| Dell OptiPlex                              | 25       | 10.55%  |
| Lenovo ThinkCentre                         | 11       | 4.64%   |
| Protectli FW4B                             | 10       | 4.22%   |
| HP ProLiant                                | 8        | 3.38%   |
| HP prodesk                                 | 7        | 2.95%   |
| Techvision TVI7309X                        | 6        | 2.53%   |
| HP EliteDesk                               | 6        | 2.53%   |
| Acer Veriton                               | 5        | 2.11%   |
| Intel MAHOBAY                              | 4        | 1.69%   |
| ASUS ROG                                   | 4        | 1.69%   |
| ASUS PRIME                                 | 4        | 1.69%   |
| Protectli VP2410                           | 3        | 1.27%   |
| Protectli FW2B                             | 2        | 0.84%   |
| PC Engines APU2                            | 2        | 0.84%   |
| MW GMLK-2                                  | 2        | 0.84%   |
| MSI Pro                                    | 2        | 0.84%   |
| Intel QHSW02                               | 2        | 0.84%   |
| Intel Q3XXG4-P                             | 2        | 0.84%   |
| Gigabyte J1900N-D3V                        | 2        | 0.84%   |
| Dell Inspiron                              | 2        | 0.84%   |
| ASUS STRIX                                 | 2        | 0.84%   |
| ASUS All                                   | 2        | 0.84%   |
| ASRock X370                                | 2        | 0.84%   |
| YANYU H67SL                                | 1        | 0.42%   |
| Yanling YL-KBR6L                           | 1        | 0.42%   |
| Winston Marriot PICO                       | 1        | 0.42%   |
| TYAN S5510HE                               | 1        | 0.42%   |
| Shuttle DS81D                              | 1        | 0.42%   |
| Shuttle DS61                               | 1        | 0.42%   |
| Shuttle DH370                              | 1        | 0.42%   |
| ShenZhen MinWin MW-NANO-APL-4L             | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 0.42%   |
| SeeedStudio ODYSSEY-X86J4125               | 1        | 0.42%   |
| Radxa ROCK                                 | 1        | 0.42%   |
| Protectli VP4650                           | 1        | 0.42%   |
| Protectli VP4630                           | 1        | 0.42%   |
| Protectli FW6                              | 1        | 0.42%   |
| PC Engines apu4                            | 1        | 0.42%   |
| PC Engines apu1                            | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 26       | 10.97%  |
| 2018    | 26       | 10.97%  |
| 2016    | 21       | 8.86%   |
| 2023    | 20       | 8.44%   |
| 2014    | 19       | 8.02%   |
| 2021    | 18       | 7.59%   |
| 2019    | 18       | 7.59%   |
| 2013    | 18       | 7.59%   |
| 2020    | 14       | 5.91%   |
| 2017    | 13       | 5.49%   |
| 2012    | 10       | 4.22%   |
| 2011    | 9        | 3.8%    |
| 2015    | 8        | 3.38%   |
| 2009    | 5        | 2.11%   |
| Unknown | 4        | 1.69%   |
| 2010    | 3        | 1.27%   |
| 2008    | 3        | 1.27%   |
| 2024    | 1        | 0.42%   |
| 2006    | 1        | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 237      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 227      | 95.78%  |
| Yes  | 10       | 4.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 98       | 40.33%  |
| 16.01-24.0  | 80       | 32.92%  |
| 4.01-8.0    | 31       | 12.76%  |
| 32.01-64.0  | 18       | 7.41%   |
| 64.01-256.0 | 7        | 2.88%   |
| 2.01-3.0    | 4        | 1.65%   |
| 24.01-32.0  | 3        | 1.23%   |
| 0.51-1.0    | 2        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 112      | 45.34%  |
| 0.51-1.0   | 90       | 36.44%  |
| 1.01-2.0   | 24       | 9.72%   |
| 2.01-3.0   | 8        | 3.24%   |
| 4.01-8.0   | 5        | 2.02%   |
| 3.01-4.0   | 2        | 0.81%   |
| 16.01-24.0 | 2        | 0.81%   |
| 8.01-16.0  | 2        | 0.81%   |
| 32.01-64.0 | 1        | 0.4%    |
| Unknown    | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 171      | 70.66%  |
| 2      | 22       | 9.09%   |
| 0      | 22       | 9.09%   |
| 3      | 14       | 5.79%   |
| 4      | 5        | 2.07%   |
| 5      | 4        | 1.65%   |
| 7      | 2        | 0.83%   |
| 10     | 1        | 0.41%   |
| 6      | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 83.61%  |
| Yes       | 39       | 16.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 234      | 98.73%  |
| No        | 3        | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 187      | 78.57%  |
| Yes       | 51       | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 202      | 84.87%  |
| Yes       | 36       | 15.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 237      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sydney         | 72       | 28.02%  |
| Melbourne      | 48       | 18.68%  |
| Brisbane       | 32       | 12.45%  |
| Perth          | 27       | 10.51%  |
| Adelaide       | 10       | 3.89%   |
| Canberra       | 7        | 2.72%   |
| Nyngan         | 5        | 1.95%   |
| Kooyong        | 4        | 1.56%   |
| Hobart         | 3        | 1.17%   |
| Morwell        | 2        | 0.78%   |
| Marrickville   | 2        | 0.78%   |
| Ipswich        | 2        | 0.78%   |
| Bundaberg      | 2        | 0.78%   |
| Unknown        | 2        | 0.78%   |
| Wollongong     | 1        | 0.39%   |
| Wheelers Hill  | 1        | 0.39%   |
| Warrnambool    | 1        | 0.39%   |
| Wallan         | 1        | 0.39%   |
| Townsville     | 1        | 0.39%   |
| Southport      | 1        | 0.39%   |
| Shell Cove     | 1        | 0.39%   |
| Ryde           | 1        | 0.39%   |
| Roxby Downs    | 1        | 0.39%   |
| Rosanna        | 1        | 0.39%   |
| Ringwood       | 1        | 0.39%   |
| Port Fairy     | 1        | 0.39%   |
| North Shore    | 1        | 0.39%   |
| Noble Park     | 1        | 0.39%   |
| Nickol         | 1        | 0.39%   |
| Mount Waverley | 1        | 0.39%   |
| Mooroolbark    | 1        | 0.39%   |
| Malvern        | 1        | 0.39%   |
| Macquarie Park | 1        | 0.39%   |
| Kurunjang      | 1        | 0.39%   |
| Kellyville     | 1        | 0.39%   |
| Hall           | 1        | 0.39%   |
| Gold Coast     | 1        | 0.39%   |
| Glen Iris      | 1        | 0.39%   |
| Geelong        | 1        | 0.39%   |
| Engadine       | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 51       | 93     | 18.48%  |
| Seagate             | 31       | 42     | 11.23%  |
| WDC                 | 28       | 73     | 10.14%  |
| Crucial             | 23       | 29     | 8.33%   |
| Kingston            | 21       | 29     | 7.61%   |
| SanDisk             | 12       | 15     | 4.35%   |
| Intel               | 12       | 19     | 4.35%   |
| Toshiba             | 10       | 14     | 3.62%   |
| Hoodisk             | 10       | 20     | 3.62%   |
| China               | 7        | 8      | 2.54%   |
| Micron Technology   | 6        | 7      | 2.17%   |
| SPCC                | 4        | 8      | 1.45%   |
| Protectli           | 4        | 4      | 1.45%   |
| OCZ                 | 4        | 5      | 1.45%   |
| Silicon Motion      | 3        | 3      | 1.09%   |
| ShiJi               | 3        | 3      | 1.09%   |
| Patriot             | 3        | 4      | 1.09%   |
| Hewlett-Packard     | 3        | 6      | 1.09%   |
| FORESEE             | 3        | 4      | 1.09%   |
| A-DATA Technology   | 3        | 8      | 1.09%   |
| Transcend           | 2        | 5      | 0.72%   |
| Phison              | 2        | 2      | 0.72%   |
| NVMe                | 2        | 2      | 0.72%   |
| KIOXIA              | 2        | 2      | 0.72%   |
| KingDian            | 2        | 2      | 0.72%   |
| Gigabyte Technology | 2        | 3      | 0.72%   |
| Fanxiang            | 2        | 2      | 0.72%   |
| Dogfish             | 2        | 3      | 0.72%   |
| Corsair             | 2        | 3      | 0.72%   |
| BIWIN               | 2        | 2      | 0.72%   |
| YMTC                | 1        | 2      | 0.36%   |
| XUNZHE              | 1        | 2      | 0.36%   |
| Vaseky              | 1        | 4      | 0.36%   |
| SK hynix            | 1        | 1      | 0.36%   |
| Qunion              | 1        | 3      | 0.36%   |
| PNY                 | 1        | 1      | 0.36%   |
| Plextor             | 1        | 2      | 0.36%   |
| Netac               | 1        | 1      | 0.36%   |
| Maxtor              | 1        | 1      | 0.36%   |
| LITEONIT            | 1        | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Hoodisk SSD 128GB                | 7        | 2.27%   |
| Crucial CT250MX500SSD1 250GB     | 5        | 1.62%   |
| Samsung SSD 970 EVO Plus 500GB   | 4        | 1.3%    |
| Samsung SSD 850 EVO 500GB        | 4        | 1.3%    |
| Kingston SA400S37240G 240GB      | 4        | 1.3%    |
| Crucial CT250P2SSD8 250GB        | 4        | 1.3%    |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 0.97%   |
| Seagate ST500LM021-1KJ152 500GB  | 3        | 0.97%   |
| Samsung SSD 980 500GB            | 3        | 0.97%   |
| Samsung SSD 970 EVO Plus 250GB   | 3        | 0.97%   |
| Samsung SSD 840 EVO 120GB        | 3        | 0.97%   |
| Samsung MZ7PD256HCGM-000H7 256GB | 3        | 0.97%   |
| Kingston SA400S37480G 480GB      | 3        | 0.97%   |
| Kingston SA400S37120G 120GB      | 3        | 0.97%   |
| Crucial CT500P3SSD8 500GB        | 3        | 0.97%   |
| China SATA SSD 16GB              | 3        | 0.97%   |
| WDC WDS250G2B0A-00SM50 250GB     | 2        | 0.65%   |
| WDC WD40EFRX-68WT0N0 4TB         | 2        | 0.65%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB         | 2        | 0.65%   |
| WDC WD20EZAZ-00GGJB0 2TB         | 2        | 0.65%   |
| Toshiba MK6475GSX 640GB          | 2        | 0.65%   |
| SPCC M.2 PCIe SSD 256GB          | 2        | 0.65%   |
| Seagate ST2000DM006-2DM164 2TB   | 2        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 0.65%   |
| SanDisk SD9SB8W-256G-1006 256GB  | 2        | 0.65%   |
| SanDisk SD8SN8U-256G-1006 256GB  | 2        | 0.65%   |
| Samsung SSD 870 EVO 1TB          | 2        | 0.65%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.65%   |
| Samsung MZVLW256HEHP-000L7 256GB | 2        | 0.65%   |
| Samsung MZVLW256HEHP-000H1 256GB | 2        | 0.65%   |
| Samsung MZ7LN128HCHP-000H1 128GB | 2        | 0.65%   |
| Protectli 120GB mSATA            | 2        | 0.65%   |
| KIOXIA KXG60ZNV256G 256GB        | 2        | 0.65%   |
| Kingston SHFS37A240G 240GB       | 2        | 0.65%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 0.65%   |
| Crucial CT480BX500SSD1 480GB     | 2        | 0.65%   |
| Crucial CT1000P3SSD8 1TB         | 2        | 0.65%   |
| YMTC YMSS1ED04B21MC 256GB        | 1        | 0.32%   |
| XUNZHE MSATA 128GB               | 1        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 30       | 40     | 42.86%  |
| WDC                 | 23       | 65     | 32.86%  |
| Toshiba             | 6        | 8      | 8.57%   |
| Samsung Electronics | 3        | 5      | 4.29%   |
| Hewlett-Packard     | 3        | 6      | 4.29%   |
| NVMe                | 1        | 1      | 1.43%   |
| Maxtor              | 1        | 1      | 1.43%   |
| Hitachi             | 1        | 1      | 1.43%   |
| HGST                | 1        | 1      | 1.43%   |
| China               | 1        | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 59     | 21.62%  |
| Kingston            | 18       | 25     | 12.16%  |
| Crucial             | 13       | 17     | 8.78%   |
| SanDisk             | 12       | 15     | 8.11%   |
| Intel               | 10       | 17     | 6.76%   |
| Hoodisk             | 10       | 20     | 6.76%   |
| China               | 6        | 7      | 4.05%   |
| WDC                 | 4        | 6      | 2.7%    |
| Protectli           | 4        | 4      | 2.7%    |
| OCZ                 | 4        | 5      | 2.7%    |
| Micron Technology   | 4        | 5      | 2.7%    |
| Transcend           | 2        | 5      | 1.35%   |
| Toshiba             | 2        | 4      | 1.35%   |
| ShiJi               | 2        | 2      | 1.35%   |
| Patriot             | 2        | 2      | 1.35%   |
| KingDian            | 2        | 2      | 1.35%   |
| FORESEE             | 2        | 3      | 1.35%   |
| Dogfish             | 2        | 3      | 1.35%   |
| Corsair             | 2        | 3      | 1.35%   |
| XUNZHE              | 1        | 2      | 0.68%   |
| Vaseky              | 1        | 4      | 0.68%   |
| SPCC                | 1        | 1      | 0.68%   |
| SK hynix            | 1        | 1      | 0.68%   |
| Seagate             | 1        | 1      | 0.68%   |
| Qunion              | 1        | 3      | 0.68%   |
| Plextor             | 1        | 2      | 0.68%   |
| Phison              | 1        | 1      | 0.68%   |
| NVMe                | 1        | 1      | 0.68%   |
| Netac               | 1        | 1      | 0.68%   |
| LITEONIT            | 1        | 1      | 0.68%   |
| KingSpec            | 1        | 1      | 0.68%   |
| Fordisk             | 1        | 1      | 0.68%   |
| BIWIN               | 1        | 1      | 0.68%   |
| A-DATA Technology   | 1        | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 133      | 226    | 53.85%  |
| NVMe | 61       | 88     | 24.7%   |
| HDD  | 53       | 129    | 21.46%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 172      | 355    | 73.82%  |
| NVMe | 61       | 88     | 26.18%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 148      | 256    | 75.13%  |
| 0.51-1.0   | 22       | 32     | 11.17%  |
| 1.01-2.0   | 13       | 33     | 6.6%    |
| 3.01-4.0   | 8        | 15     | 4.06%   |
| 2.01-3.0   | 3        | 12     | 1.52%   |
| 4.01-10.0  | 2        | 5      | 1.02%   |
| 10.01-20.0 | 1        | 2      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 112      | 45.9%   |
| 251-500    | 49       | 20.08%  |
| 1-20       | 25       | 10.25%  |
| 501-1000   | 18       | 7.38%   |
| 51-100     | 18       | 7.38%   |
| 21-50      | 14       | 5.74%   |
| 1001-2000  | 6        | 2.46%   |
| 2001-3000  | 2        | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 219      | 89.02%  |
| 21-50     | 20       | 8.13%   |
| 101-250   | 3        | 1.22%   |
| 51-100    | 3        | 1.22%   |
| 1001-2000 | 1        | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB           | 2        | 2      | 8.7%    |
| WDC WDS240G2G0A-00JH30 240GB              | 1        | 1      | 4.35%   |
| WDC WD40EZRZ-00WN9B0 4TB                  | 1        | 1      | 4.35%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1        | 1      | 4.35%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1        | 2      | 4.35%   |
| WDC WD20EARX-008FB0 2TB                   | 1        | 4      | 4.35%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1        | 1      | 4.35%   |
| Toshiba KSG60ZSE256G SATA 256GB           | 1        | 1      | 4.35%   |
| Seagate ST9160314AS 160GB                 | 1        | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB           | 1        | 1      | 4.35%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 4.35%   |
| Seagate ST2000LM015-2E8174 2TB            | 1        | 1      | 4.35%   |
| Seagate ST2000DL003-9VT166 2TB            | 1        | 1      | 4.35%   |
| Seagate ST1000DM003-1CH162 1TB            | 1        | 1      | 4.35%   |
| SanDisk SDSSDA240G 240GB                  | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB       | 1        | 1      | 4.35%   |
| Samsung Electronics HM500LI 500GB         | 1        | 2      | 4.35%   |
| Micron Technology C400-MTFDDAT064MAM 64GB | 1        | 1      | 4.35%   |
| Intel SSDSA2BW120G3H 120GB                | 1        | 1      | 4.35%   |
| Hitachi HDS721010KLA330 1TB               | 1        | 1      | 4.35%   |
| Hewlett-Packard VB0250EAVER 250GB         | 1        | 1      | 4.35%   |
| BIWIN SSD 8GB                             | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 36.36%  |
| WDC                 | 5        | 10     | 22.73%  |
| Samsung Electronics | 2        | 3      | 9.09%   |
| Toshiba             | 1        | 1      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| Micron Technology   | 1        | 1      | 4.55%   |
| Intel               | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| Hewlett-Packard     | 1        | 1      | 4.55%   |
| BIWIN               | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 53.33%  |
| WDC                 | 4        | 9      | 26.67%  |
| Samsung Electronics | 1        | 2      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |
| Hewlett-Packard     | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 21     | 68.18%  |
| SSD  | 7        | 7      | 31.82%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Patriot M.2 P310 240GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Patriot | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 201      | 412    | 88.94%  |
| Malfunc  | 22       | 28     | 9.73%   |
| Detected | 2        | 2      | 0.88%   |
| Failed   | 1        | 1      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 197      | 62.34%  |
| AMD                          | 32       | 10.13%  |
| Samsung Electronics          | 22       | 6.96%   |
| Micron/Crucial Technology    | 11       | 3.48%   |
| Phison Electronics           | 9        | 2.85%   |
| Silicon Motion               | 7        | 2.22%   |
| Kingston Technology Company  | 6        | 1.9%    |
| Toshiba                      | 4        | 1.27%   |
| Micron Technology            | 3        | 0.95%   |
| Hosin Global Electronics     | 3        | 0.95%   |
| Broadcom / LSI               | 3        | 0.95%   |
| Shenzhen Longsys Electronics | 2        | 0.63%   |
| SanDisk                      | 2        | 0.63%   |
| Hewlett-Packard              | 2        | 0.63%   |
| ASMedia Technology           | 2        | 0.63%   |
| Yangtze Memory Technologies  | 1        | 0.32%   |
| Silicon Image                | 1        | 0.32%   |
| Seagate Technology           | 1        | 0.32%   |
| Realtek Semiconductor        | 1        | 0.32%   |
| QLogic                       | 1        | 0.32%   |
| Nvidia                       | 1        | 0.32%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.32%   |
| Marvell Technology Group     | 1        | 0.32%   |
| JMicron Technology           | 1        | 0.32%   |
| ADATA Technology             | 1        | 0.32%   |
| Adaptec                      | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 7.1%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 5.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 4.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14       | 3.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13       | 3.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 12       | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.41%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 11       | 3.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 2.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 2.84%   |
| Intel unknown                                                                           | 10       | 2.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 2.56%   |
| Intel SATA Controller [RAID mode]                                                       | 8        | 2.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8        | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.27%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 1.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6        | 1.7%    |
| Intel Alder Lake-P SATA AHCI Controller                                                 | 6        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 1.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.42%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.14%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.85%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 0.85%   |
| Unknown                                                                                 | 3        | 0.85%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 2        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.57%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                          | 2        | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2        | 0.57%   |
| Intel Elkhart Lake SATA AHCI                                                            | 2        | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 210      | 65.42%  |
| NVMe | 69       | 21.5%   |
| IDE  | 24       | 7.48%   |
| RAID | 13       | 4.05%   |
| SAS  | 3        | 0.93%   |
| SCSI | 2        | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 201      | 84.81%  |
| AMD    | 35       | 14.77%  |
| ARM    | 1        | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz          | 12       | 4.98%   |
| Intel Celeron J4125 CPU @ 2.00GHz          | 10       | 4.15%   |
| Intel N100                                 | 9        | 3.73%   |
| Intel Celeron N5105 @ 2.00GHz              | 8        | 3.32%   |
| Intel Core i5-6500T CPU @ 2.50GHz          | 6        | 2.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 5        | 2.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 5        | 2.07%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 5        | 2.07%   |
| Intel Core i5-4570T CPU @ 2.90GHz          | 4        | 1.66%   |
| Intel Pentium Silver N6005 @ 2.00GHz       | 3        | 1.24%   |
| Intel Pentium CPU G4560 @ 3.50GHz          | 3        | 1.24%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 3        | 1.24%   |
| Intel Core i3-6100 CPU @ 3.70GHz           | 3        | 1.24%   |
| Intel Core i3-3220 CPU @ 3.30GHz           | 3        | 1.24%   |
| AMD GX-412TC SOC                           | 3        | 1.24%   |
| Intel Xeon CPU E5504 @ 2.00GHz             | 2        | 0.83%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 2        | 0.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 2        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 2        | 0.83%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 2        | 0.83%   |
| Intel Core i5-7400 CPU @ 3.00GHz           | 2        | 0.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 2        | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 2        | 0.83%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 2        | 0.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 2        | 0.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz           | 2        | 0.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 2        | 0.83%   |
| Intel Core i3-4150 CPU @ 3.50GHz           | 2        | 0.83%   |
| Intel Core i3-10110U CPU @ 2.10GHz         | 2        | 0.83%   |
| Intel Celeron CPU J3060 @ 1.60GHz          | 2        | 0.83%   |
| Intel Celeron CPU G3900 @ 2.80GHz          | 2        | 0.83%   |
| Intel 12th Gen Core i3-1215U               | 2        | 0.83%   |
| AMD Turion II Neo N54L Dual-Core Processor | 2        | 0.83%   |
| AMD Turion II Neo N40L Dual-Core Processor | 2        | 0.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 2        | 0.83%   |
| AMD FX-8350 Eight-Core Processor           | 2        | 0.83%   |
| Intel Xeon E-2224G CPU @ 3.50GHz           | 1        | 0.41%   |
| Intel Xeon CPU W3680 @ 3.33GHz             | 1        | 0.41%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz        | 1        | 0.41%   |
| Intel Xeon CPU E31230 @ 3.20GHz            | 1        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 59       | 24.58%  |
| Intel Celeron           | 53       | 22.08%  |
| Other                   | 21       | 8.75%   |
| Intel Core i7           | 21       | 8.75%   |
| Intel Core i3           | 20       | 8.33%   |
| Intel Xeon              | 13       | 5.42%   |
| Intel Pentium           | 7        | 2.92%   |
| AMD Ryzen 5             | 7        | 2.92%   |
| AMD Ryzen 3             | 5        | 2.08%   |
| AMD GX                  | 5        | 2.08%   |
| AMD Turion II Neo       | 4        | 1.67%   |
| Intel Pentium Silver    | 3        | 1.25%   |
| Intel Core 2 Quad       | 3        | 1.25%   |
| AMD FX                  | 3        | 1.25%   |
| Intel Atom              | 2        | 0.83%   |
| AMD Ryzen 9             | 2        | 0.83%   |
| AMD G                   | 2        | 0.83%   |
| AMD Athlon              | 2        | 0.83%   |
| Intel Pentium Gold      | 1        | 0.42%   |
| Intel Pentium Dual-Core | 1        | 0.42%   |
| Intel Pentium 4         | 1        | 0.42%   |
| ARM Cortex              | 1        | 0.42%   |
| AMD Ryzen 7             | 1        | 0.42%   |
| AMD E2                  | 1        | 0.42%   |
| AMD Athlon X2           | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 139      | 58.16%  |
| 2       | 57       | 23.85%  |
| 8       | 15       | 6.28%   |
| 6       | 14       | 5.86%   |
| 12      | 5        | 2.09%   |
| Unknown | 4        | 1.67%   |
| 32      | 1        | 0.42%   |
| 24      | 1        | 0.42%   |
| 16      | 1        | 0.42%   |
| 10      | 1        | 0.42%   |
| 1       | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 234      | 98.73%  |
| 2       | 2        | 0.84%   |
| Unknown | 1        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 168      | 70.29%  |
| 2       | 67       | 28.03%  |
| Unknown | 4        | 1.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 34       | 14.23%  |
| Haswell       | 30       | 12.55%  |
| KabyLake      | 28       | 11.72%  |
| Silvermont    | 24       | 10.04%  |
| Skylake       | 21       | 8.79%   |
| IvyBridge     | 20       | 8.37%   |
| Goldmont plus | 12       | 5.02%   |
| SandyBridge   | 9        | 3.77%   |
| Broadwell     | 6        | 2.51%   |
| Zen 3         | 5        | 2.09%   |
| K10           | 5        | 2.09%   |
| CometLake     | 5        | 2.09%   |
| Zen+          | 4        | 1.67%   |
| Zen 2         | 4        | 1.67%   |
| Puma          | 4        | 1.67%   |
| Nehalem       | 4        | 1.67%   |
| Zen           | 3        | 1.26%   |
| Westmere      | 3        | 1.26%   |
| Piledriver    | 3        | 1.26%   |
| Penryn        | 3        | 1.26%   |
| Jaguar        | 3        | 1.26%   |
| Bobcat        | 3        | 1.26%   |
| TigerLake     | 2        | 0.84%   |
| NetBurst      | 1        | 0.42%   |
| K8 Hammer     | 1        | 0.42%   |
| Goldmont      | 1        | 0.42%   |
| Core          | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 174      | 74.04%  |
| AMD                        | 32       | 13.62%  |
| Nvidia                     | 20       | 8.51%   |
| Matrox Electronics Systems | 6        | 2.55%   |
| ASPEED Technology          | 2        | 0.85%   |
| Tseng Labs                 | 1        | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27       | 11.25%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15       | 6.25%   |
| Intel HD Graphics 530                                                                    | 13       | 5.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12       | 5%      |
| Intel Alder Lake-N [UHD Graphics]                                                        | 12       | 5%      |
| Intel JasperLake [UHD Graphics]                                                          | 11       | 4.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 4.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9        | 3.75%   |
| Intel HD Graphics 630                                                                    | 8        | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8        | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 2.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4        | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 1.25%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 3        | 1.25%   |
| Intel HD Graphics 610                                                                    | 3        | 1.25%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.25%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 3        | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.25%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 0.83%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 0.83%   |
| Intel UHD Graphics 620                                                                   | 2        | 0.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 0.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2        | 0.83%   |
| Intel HD Graphics 510                                                                    | 2        | 0.83%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 2        | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2        | 0.83%   |
| Intel Comet Lake UHD Graphics                                                            | 2        | 0.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 0.83%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.83%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2        | 0.83%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 0.83%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 0.83%   |
| Tseng Labs ET4000/W32p rev C                                                             | 1        | 0.42%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 165      | 69.04%  |
| 1 x AMD        | 28       | 11.72%  |
| 1 x Nvidia     | 18       | 7.53%   |
| Other          | 9        | 3.77%   |
| 1 x Matrox     | 6        | 2.51%   |
| Intel + AMD    | 4        | 1.67%   |
| 2 x Intel      | 3        | 1.26%   |
| Intel + Nvidia | 2        | 0.84%   |
| 1 x ASPEED     | 2        | 0.84%   |
| 2 x AMD        | 1        | 0.42%   |
| 1 x Tseng Labs | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 218      | 91.98%  |
| Proprietary | 10       | 4.22%   |
| Unknown     | 9        | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 217      | 90.79%  |
| 1.01-2.0   | 8        | 3.35%   |
| 0.51-1.0   | 5        | 2.09%   |
| 7.01-8.0   | 4        | 1.67%   |
| 3.01-4.0   | 2        | 0.84%   |
| 0.01-0.5   | 2        | 0.84%   |
| 8.01-16.0  | 1        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 10.81%  |
| ASUSTek Computer    | 4        | 10.81%  |
| Acer                | 4        | 10.81%  |
| Philips             | 3        | 8.11%   |
| Hewlett-Packard     | 3        | 8.11%   |
| Dell                | 3        | 8.11%   |
| AOC                 | 3        | 8.11%   |
| ViewSonic           | 2        | 5.41%   |
| Goldstar            | 2        | 5.41%   |
| BenQ                | 2        | 5.41%   |
| ___                 | 1        | 2.7%    |
| Toshiba             | 1        | 2.7%    |
| Sony                | 1        | 2.7%    |
| Lenovo              | 1        | 2.7%    |
| Konka               | 1        | 2.7%    |
| Compal              | 1        | 2.7%    |
| AU Optronics        | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer ROG XG279Q AUS278D 2560x1440 600x340mm 27.2-inch    | 2        | 5.13%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 2.56%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch            | 1        | 2.56%   |
| ViewSonic VA1912w-3 VSC711C 1440x900 410x260mm 19.1-inch             | 1        | 2.56%   |
| Toshiba TV TSB010E 1920x1080 1040x590mm 47.1-inch                    | 1        | 2.56%   |
| Sony AVAMP SNY1F02 1280x720 800x450mm 36.1-inch                      | 1        | 2.56%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1        | 2.56%   |
| Samsung Electronics SyncMaster SAM056A 1680x1050 470x300mm 22.0-inch | 1        | 2.56%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch | 1        | 2.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1        | 2.56%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 2.56%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 1        | 2.56%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 2.56%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                  | 1        | 2.56%   |
| Konka TV_MONITOR KOA0030 2288x1430 1150x650mm 52.0-inch              | 1        | 2.56%   |
| Hewlett-Packard LCD Monitor HWP2915 1920x1080 510x290mm 23.1-inch    | 1        | 2.56%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch         | 1        | 2.56%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch           | 1        | 2.56%   |
| Goldstar LG HDR WQHD GSM7716 3840x1600 880x370mm 37.6-inch           | 1        | 2.56%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 1        | 2.56%   |
| Dell SP2309W DELD01C 2048x1152 510x290mm 23.1-inch                   | 1        | 2.56%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                    | 1        | 2.56%   |
| Dell E248WFP DELA02D 1920x1200 520x320mm 24.0-inch                   | 1        | 2.56%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch             | 1        | 2.56%   |
| BenQ XL2430T BNQ7F3F 1920x1080 530x300mm 24.0-inch                   | 1        | 2.56%   |
| BenQ GW2255 BNQ78CD 1920x1080 480x270mm 21.7-inch                    | 1        | 2.56%   |
| BenQ EX2710Q BNQ7F87 2560x1440 600x340mm 27.2-inch                   | 1        | 2.56%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch       | 1        | 2.56%   |
| ASUSTek Computer XG49V AUS49A1 3840x1080 1200x340mm 49.1-inch        | 1        | 2.56%   |
| ASUSTek Computer VA32U AUS32A4 3840x2160 700x390mm 31.5-inch         | 1        | 2.56%   |
| AOC Q27T1G5 AOC2701 2560x1440 600x340mm 27.2-inch                    | 1        | 2.56%   |
| AOC 2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 1        | 2.56%   |
| AOC 2236 AOC2236 1920x1080 480x270mm 21.7-inch                       | 1        | 2.56%   |
| Acer V233H ACR0090 1920x1080 510x290mm 23.1-inch                     | 1        | 2.56%   |
| Acer LCD Monitor V243HL 1920x1080                                    | 1        | 2.56%   |
| Acer K272HL ACR0523 1920x1080 600x340mm 27.2-inch                    | 1        | 2.56%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                    | 1        | 2.56%   |
| Acer B276HL ACR0332 1920x1080 600x340mm 27.2-inch                    | 1        | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 51.35%  |
| 2560x1440 (QHD)    | 6        | 16.22%  |
| 3840x2160 (4K)     | 2        | 5.41%   |
| 1680x1050 (WSXGA+) | 2        | 5.41%   |
| 3840x1600          | 1        | 2.7%    |
| 3840x1080          | 1        | 2.7%    |
| 2560x1080          | 1        | 2.7%    |
| 2288x1430          | 1        | 2.7%    |
| 2048x1152          | 1        | 2.7%    |
| 1920x1200 (WUXGA)  | 1        | 2.7%    |
| 1440x900 (WXGA+)   | 1        | 2.7%    |
| 1280x720 (HD)      | 1        | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 11       | 28.95%  |
| 24      | 6        | 15.79%  |
| 23      | 4        | 10.53%  |
| 21      | 3        | 7.89%   |
| 31      | 2        | 5.26%   |
| 22      | 2        | 5.26%   |
| Unknown | 2        | 5.26%   |
| 52      | 1        | 2.63%   |
| 49      | 1        | 2.63%   |
| 47      | 1        | 2.63%   |
| 37      | 1        | 2.63%   |
| 36      | 1        | 2.63%   |
| 28      | 1        | 2.63%   |
| 19      | 1        | 2.63%   |
| 15      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 52.78%  |
| 401-500     | 5        | 13.89%  |
| 601-700     | 4        | 11.11%  |
| 1001-1500   | 3        | 8.33%   |
| Unknown     | 2        | 5.56%   |
| 801-900     | 1        | 2.78%   |
| 701-800     | 1        | 2.78%   |
| 301-350     | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 26       | 78.79%  |
| 16/10   | 3        | 9.09%   |
| 21/9    | 2        | 6.06%   |
| 32/9    | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 35.14%  |
| 301-350        | 11       | 29.73%  |
| 501-1000       | 4        | 10.81%  |
| 351-500        | 2        | 5.41%   |
| 251-300        | 2        | 5.41%   |
| Unknown        | 2        | 5.41%   |
| More than 1000 | 1        | 2.7%    |
| 151-200        | 1        | 2.7%    |
| 91-100         | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 56.76%  |
| 101-120 | 9        | 24.32%  |
| 121-160 | 3        | 8.11%   |
| 1-50    | 2        | 5.41%   |
| Unknown | 2        | 5.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 200      | 84.39%  |
| 1     | 33       | 13.92%  |
| 2     | 3        | 1.27%   |
| 3     | 1        | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 183      | 58.84%  |
| Realtek Semiconductor    | 81       | 26.05%  |
| Qualcomm Atheros         | 14       | 4.5%    |
| Broadcom                 | 14       | 4.5%    |
| U-Blox                   | 3        | 0.96%   |
| TP-Link                  | 2        | 0.64%   |
| IMC Networks             | 2        | 0.64%   |
| D-Link System            | 2        | 0.64%   |
| VIA Technologies         | 1        | 0.32%   |
| TRENDnet                 | 1        | 0.32%   |
| Seeed Technology         | 1        | 0.32%   |
| Ralink Technology        | 1        | 0.32%   |
| Ralink                   | 1        | 0.32%   |
| Nvidia                   | 1        | 0.32%   |
| Mellanox Technologies    | 1        | 0.32%   |
| MediaTek                 | 1        | 0.32%   |
| Marvell Technology Group | 1        | 0.32%   |
| Aquantia                 | 1        | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 68       | 18.04%  |
| Intel I211 Gigabit Network Connection                                         | 34       | 9.02%   |
| Intel Ethernet Controller I226-V                                              | 25       | 6.63%   |
| Intel I210 Gigabit Network Connection                                         | 16       | 4.24%   |
| Intel Ethernet Connection I217-LM                                             | 15       | 3.98%   |
| Intel Ethernet Controller I225-V                                              | 14       | 3.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 2.65%   |
| Intel 82576 Gigabit Network Connection                                        | 10       | 2.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 9        | 2.39%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 2.39%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 1.86%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 1.59%   |
| Intel Wireless 7260                                                           | 6        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.59%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 1.59%   |
| Intel I350 Gigabit Network Connection                                         | 5        | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                                         | 5        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                           | 4        | 1.06%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4        | 1.06%   |
| Intel 82583V Gigabit Network Connection                                       | 4        | 1.06%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 1.06%   |
| U-Blox [u-blox 7]                                                             | 3        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.8%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.53%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.53%   |
| Intel Wireless 8265 / 8275                                                    | 2        | 0.53%   |
| Intel Wireless 8260                                                           | 2        | 0.53%   |
| Intel Wireless 3165                                                           | 2        | 0.53%   |
| Intel DH8900CC Null Device                                                    | 2        | 0.53%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 0.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2        | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 27       | 50.94%  |
| Qualcomm Atheros      | 11       | 20.75%  |
| Realtek Semiconductor | 8        | 15.09%  |
| TP-Link               | 2        | 3.77%   |
| IMC Networks          | 2        | 3.77%   |
| Ralink Technology     | 1        | 1.89%   |
| Ralink                | 1        | 1.89%   |
| MediaTek              | 1        | 1.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                             | 6        | 11.11%  |
| Intel Wi-Fi 6 AX200                                             | 4        | 7.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 3        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 2        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 2        | 3.7%    |
| Intel Wireless 8265 / 8275                                      | 2        | 3.7%    |
| Intel Wireless 8260                                             | 2        | 3.7%    |
| Intel Wireless 3165                                             | 2        | 3.7%    |
| Intel Centrino Wireless-N 2230                                  | 2        | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 2        | 3.7%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 2        | 3.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                             | 1        | 1.85%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                             | 1        | 1.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]      | 1        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                              | 1        | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                 | 1        | 1.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 1.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                 | 1        | 1.85%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1        | 1.85%   |
| Ralink RT5572 Wireless Adapter                                  | 1        | 1.85%   |
| Ralink RT5392 PCIe Wireless Network Adapter                     | 1        | 1.85%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 1        | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1        | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1        | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1        | 1.85%   |
| Intel Wi-Fi 6 AX201                                             | 1        | 1.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 1        | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                  | 1        | 1.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 1        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 1.85%   |
| Intel CNVi: Wi-Fi                                               | 1        | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 1        | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 171      | 62.64%  |
| Realtek Semiconductor    | 77       | 28.21%  |
| Broadcom                 | 14       | 5.13%   |
| Qualcomm Atheros         | 4        | 1.47%   |
| D-Link System            | 2        | 0.73%   |
| VIA Technologies         | 1        | 0.37%   |
| TRENDnet                 | 1        | 0.37%   |
| Nvidia                   | 1        | 0.37%   |
| Marvell Technology Group | 1        | 0.37%   |
| Aquantia                 | 1        | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 68       | 21.52%  |
| Intel I211 Gigabit Network Connection                                         | 34       | 10.76%  |
| Intel Ethernet Controller I226-V                                              | 25       | 7.91%   |
| Intel I210 Gigabit Network Connection                                         | 16       | 5.06%   |
| Intel Ethernet Connection I217-LM                                             | 15       | 4.75%   |
| Intel Ethernet Controller I225-V                                              | 14       | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 3.16%   |
| Intel 82576 Gigabit Network Connection                                        | 10       | 3.16%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 9        | 2.85%   |
| Intel 82574L Gigabit Network Connection                                       | 9        | 2.85%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 7        | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 1.9%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 6        | 1.9%    |
| Intel I350 Gigabit Network Connection                                         | 5        | 1.58%   |
| Intel Ethernet Connection (7) I219-LM                                         | 5        | 1.58%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4        | 1.27%   |
| Intel 82583V Gigabit Network Connection                                       | 4        | 1.27%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                                          | 3        | 0.95%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 0.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 2        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 0.63%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2        | 0.63%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 2        | 0.63%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.32%   |
| TRENDnet TRENDnet USB 5G Adapter ethernet                                     | 1        | 0.32%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.32%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.32%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.32%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 1        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 234      | 80.14%  |
| WiFi     | 51       | 17.47%  |
| Modem    | 4        | 1.37%   |
| Unknown  | 3        | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 231      | 95.85%  |
| WiFi     | 10       | 4.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 59       | 24.58%  |
| 4     | 55       | 22.92%  |
| 1     | 42       | 17.5%   |
| 3     | 34       | 14.17%  |
| 6     | 20       | 8.33%   |
| 5     | 19       | 7.92%   |
| 7     | 4        | 1.67%   |
| 8     | 3        | 1.25%   |
| 9     | 2        | 0.83%   |
| 10    | 1        | 0.42%   |
| 0     | 1        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 192      | 78.37%  |
| Yes  | 53       | 21.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 60.53%  |
| Realtek Semiconductor           | 3        | 7.89%   |
| Qualcomm Atheros Communications | 3        | 7.89%   |
| Cambridge Silicon Radio         | 3        | 7.89%   |
| ASUSTek Computer                | 3        | 7.89%   |
| Broadcom                        | 2        | 5.26%   |
| MediaTek                        | 1        | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 10       | 26.32%  |
| Intel AX200 Bluetooth                                       | 4        | 10.53%  |
| Realtek Bluetooth Adapter                                   | 3        | 7.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3        | 7.89%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2        | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 5.26%   |
| Intel AX201 Bluetooth                                       | 2        | 5.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 5.26%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 2        | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 2.63%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1        | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 2.63%   |
| Intel AX211 Bluetooth                                       | 1        | 2.63%   |
| ASUS Bluetooth Controller                                   | 1        | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 169      | 75.11%  |
| AMD                                          | 30       | 13.33%  |
| Nvidia                                       | 17       | 7.56%   |
| Texas Instruments                            | 2        | 0.89%   |
| Focusrite-Novation                           | 2        | 0.89%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.44%   |
| Sony                                         | 1        | 0.44%   |
| Logitech                                     | 1        | 0.44%   |
| Creative Labs                                | 1        | 0.44%   |
| C-Media Electronics                          | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25       | 9.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24       | 8.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15       | 5.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12       | 4.4%    |
| Intel Jasper Lake HD Audio                                                                        | 11       | 4.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11       | 4.03%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 11       | 4.03%   |
| Intel 200 Series PCH HD Audio                                                                     | 11       | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9        | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 8        | 2.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8        | 2.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8        | 2.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6        | 2.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5        | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 5        | 1.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5        | 1.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5        | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4        | 1.47%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 1.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4        | 1.47%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.1%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3        | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 1.1%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 0.73%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 2        | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 0.73%   |
| AMD Wrestler HDMI Audio                                                                           | 2        | 0.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 0.73%   |
| AMD Navi 10 HDMI Audio                                                                            | 2        | 0.73%   |
| AMD FCH Azalia Controller                                                                         | 2        | 0.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 0.73%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.37%   |
| Texas Instruments SMSL Q5 AMP                                                                     | 1        | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 38       | 14.96%  |
| Kingston                     | 38       | 14.96%  |
| Crucial                      | 28       | 11.02%  |
| SK hynix                     | 26       | 10.24%  |
| Micron Technology            | 23       | 9.06%   |
| Corsair                      | 22       | 8.66%   |
| Unknown                      | 21       | 8.27%   |
| G.Skill                      | 11       | 4.33%   |
| Team                         | 6        | 2.36%   |
| Ramaxel Technology           | 5        | 1.97%   |
| Unknown                      | 5        | 1.97%   |
| Transcend                    | 3        | 1.18%   |
| Kimtigo                      | 3        | 1.18%   |
| GeIL                         | 3        | 1.18%   |
| Apacer                       | 3        | 1.18%   |
| Unknown (ABCD)               | 2        | 0.79%   |
| Silicon Power                | 2        | 0.79%   |
| Patriot                      | 2        | 0.79%   |
| Vasekey                      | 1        | 0.39%   |
| Uroad                        | 1        | 0.39%   |
| Timetec                      | 1        | 0.39%   |
| Smart Modular                | 1        | 0.39%   |
| PNY                          | 1        | 0.39%   |
| Patriot Memory (PDP Systems) | 1        | 0.39%   |
| Nanya Technology             | 1        | 0.39%   |
| Kingmax                      | 1        | 0.39%   |
| Innodisk                     | 1        | 0.39%   |
| Hewlett-Packard              | 1        | 0.39%   |
| Heoriady                     | 1        | 0.39%   |
| Golden Empire                | 1        | 0.39%   |
| Elpida                       | 1        | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 6        | 2.25%   |
| Unknown                                                      | 5        | 1.87%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 4        | 1.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 4        | 1.5%    |
| Corsair RAM Module 8GB DIMM DDR4 2133MT/s                    | 4        | 1.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 3        | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3        | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 3        | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 3        | 1.12%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 3        | 1.12%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s        | 3        | 1.12%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 3        | 1.12%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 3        | 1.12%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 2        | 0.75%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 2        | 0.75%   |
| Unknown RAM Module 8GB 1600MT/s                              | 2        | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 2        | 0.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2        | 0.75%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 2        | 0.75%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2667MT/s          | 2        | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2        | 0.75%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s       | 2        | 0.75%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 2        | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2        | 0.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 2        | 0.75%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.75%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s        | 2        | 0.75%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s        | 2        | 0.75%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2        | 0.75%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 2        | 0.75%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s           | 2        | 0.75%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s        | 2        | 0.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 2        | 0.75%   |
| GeIL RAM CL19-19-19 D4-2666 8GB DIMM DDR4 2667MT/s           | 2        | 0.75%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1600MT/s         | 2        | 0.75%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s         | 2        | 0.75%   |
| Crucial RAM CT8G48C40S5.M4A1 8GB SODIMM DDR5 4800MT/s        | 2        | 0.75%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s      | 2        | 0.75%   |
| Crucial RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 2667MT/s     | 2        | 0.75%   |
| Corsair RAM CMZ16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s         | 2        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 102      | 45.74%  |
| DDR4    | 92       | 41.26%  |
| DDR5    | 12       | 5.38%   |
| Unknown | 10       | 4.48%   |
| LPDDR4  | 2        | 0.9%    |
| DDR2    | 2        | 0.9%    |
| DDR     | 2        | 0.9%    |
| LPDDR5  | 1        | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 132      | 59.73%  |
| SODIMM       | 82       | 37.1%   |
| Unknown      | 5        | 2.26%   |
| Row Of Chips | 1        | 0.45%   |
| RIMM         | 1        | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 102      | 43.78%  |
| 4096  | 66       | 28.33%  |
| 16384 | 35       | 15.02%  |
| 2048  | 19       | 8.15%   |
| 32768 | 8        | 3.43%   |
| 1024  | 3        | 1.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 81       | 34.76%  |
| 2133    | 28       | 12.02%  |
| 1333    | 27       | 11.59%  |
| 2400    | 25       | 10.73%  |
| 2667    | 20       | 8.58%   |
| 3200    | 19       | 8.15%   |
| 4800    | 9        | 3.86%   |
| 800     | 6        | 2.58%   |
| 3600    | 4        | 1.72%   |
| 5600    | 3        | 1.29%   |
| 1066    | 3        | 1.29%   |
| 3000    | 2        | 0.86%   |
| 59392   | 1        | 0.43%   |
| 6400    | 1        | 0.43%   |
| 2666    | 1        | 0.43%   |
| 1867    | 1        | 0.43%   |
| 400     | 1        | 0.43%   |
| Unknown | 1        | 0.43%   |

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


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microdia USB 2.0 Camera         | 1        | 50%     |
| Logitech C922 Pro Stream Webcam | 1        | 50%     |

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
| 1     | 132      | 55.23%  |
| 0     | 69       | 28.87%  |
| 2     | 26       | 10.88%  |
| 3     | 7        | 2.93%   |
| 4     | 4        | 1.67%   |
| 5     | 1        | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 157      | 76.21%  |
| Bluetooth                | 15       | 7.28%   |
| Net/wireless             | 13       | 6.31%   |
| Sound                    | 5        | 2.43%   |
| Network                  | 5        | 2.43%   |
| Card reader              | 5        | 2.43%   |
| Firewire controller      | 3        | 1.46%   |
| Storage/raid             | 1        | 0.49%   |
| Net/ethernet             | 1        | 0.49%   |
| Dvb card                 | 1        | 0.49%   |

