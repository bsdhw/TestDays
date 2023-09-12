BSD in Italy - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 241

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | [3d3b16c0cf](https://bsd-hardware.info/?probe=3d3b16c0cf) | Aug 25, 2023 |
| AZW           | U59                         | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Protectli     | FW4B                        | [4b358b0106](https://bsd-hardware.info/?probe=4b358b0106) | Aug 24, 2023 |
| BESSTAR Te... | IB9                         | [c9f5ede507](https://bsd-hardware.info/?probe=c9f5ede507) | Aug 18, 2023 |
| Intel         | Q3XXG4-P V1.0               | [f0398bfb85](https://bsd-hardware.info/?probe=f0398bfb85) | Aug 10, 2023 |
| Unknown       | Unknown                     | [28f0d503fd](https://bsd-hardware.info/?probe=28f0d503fd) | Aug 07, 2023 |
| Unknown       | Unknown                     | [6238337b24](https://bsd-hardware.info/?probe=6238337b24) | Aug 07, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| MW            | GMLK-2_5G4L                 | [155f885c95](https://bsd-hardware.info/?probe=155f885c95) | Aug 01, 2023 |
| ASUSTek       | P8P67                       | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Dell          | 0PTTT9 A01                  | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| Dell          | 0PTTT9 A01                  | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | H510I PRO WIFI              | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Dell          | 0WMJ54 A01                  | [48fcb6e4ab](https://bsd-hardware.info/?probe=48fcb6e4ab) | Jul 05, 2023 |
| Protectli     | FW4B                        | [a3cf476fe8](https://bsd-hardware.info/?probe=a3cf476fe8) | Jul 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c30f91d5cc](https://bsd-hardware.info/?probe=c30f91d5cc) | Jul 01, 2023 |
| ASUSTek       | N3700T                      | [16b73b05ef](https://bsd-hardware.info/?probe=16b73b05ef) | Jun 26, 2023 |
| Unknown       | Unknown                     | [229e573059](https://bsd-hardware.info/?probe=229e573059) | Jun 13, 2023 |
| Unknown       | Unknown                     | [9d271bc94c](https://bsd-hardware.info/?probe=9d271bc94c) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fe412825f2](https://bsd-hardware.info/?probe=fe412825f2) | Jun 10, 2023 |
| Dell          | 0WR7PY A03                  | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d08f309c4c](https://bsd-hardware.info/?probe=d08f309c4c) | May 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | [9160d45441](https://bsd-hardware.info/?probe=9160d45441) | May 25, 2023 |
| Unknown       | Unknown                     | [8b5ec8c5f4](https://bsd-hardware.info/?probe=8b5ec8c5f4) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| Unknown       | Unknown                     | [b26eac2277](https://bsd-hardware.info/?probe=b26eac2277) | May 13, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1dac5a7bb2](https://bsd-hardware.info/?probe=1dac5a7bb2) | May 13, 2023 |
| Unknown       | Unknown                     | [bf8246ecb5](https://bsd-hardware.info/?probe=bf8246ecb5) | May 11, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Unknown       | Unknown                     | [5c6c169e73](https://bsd-hardware.info/?probe=5c6c169e73) | May 01, 2023 |
| Unknown       | Unknown                     | [d572f5ff91](https://bsd-hardware.info/?probe=d572f5ff91) | May 01, 2023 |
| Unknown       | HX90                        | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| Unknown       | Unknown                     | [1774da050f](https://bsd-hardware.info/?probe=1774da050f) | Apr 29, 2023 |
| HP            | 82B4                        | [9ec1e6d6f4](https://bsd-hardware.info/?probe=9ec1e6d6f4) | Apr 23, 2023 |
| Intel         | SKYBAY                      | [03dd920110](https://bsd-hardware.info/?probe=03dd920110) | Apr 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [d343800c53](https://bsd-hardware.info/?probe=d343800c53) | Apr 16, 2023 |
| PC Engines    | apu4                        | [9217e1982f](https://bsd-hardware.info/?probe=9217e1982f) | Apr 14, 2023 |
| ASRock        | G31M-S                      | [fed4a42c32](https://bsd-hardware.info/?probe=fed4a42c32) | Apr 08, 2023 |
| ASRock        | G31M-S                      | [4596f78aee](https://bsd-hardware.info/?probe=4596f78aee) | Apr 08, 2023 |
| Unknown       | Unknown                     | [5168183b15](https://bsd-hardware.info/?probe=5168183b15) | Apr 06, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [45f590d129](https://bsd-hardware.info/?probe=45f590d129) | Apr 04, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [ab0643727f](https://bsd-hardware.info/?probe=ab0643727f) | Apr 02, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [fb6477d43e](https://bsd-hardware.info/?probe=fb6477d43e) | Mar 31, 2023 |
| YANYU         | H17SL                       | [0f9829ebe4](https://bsd-hardware.info/?probe=0f9829ebe4) | Mar 26, 2023 |
| ASUSTek       | F1A55                       | [91ad5bab75](https://bsd-hardware.info/?probe=91ad5bab75) | Mar 25, 2023 |
| Unknown       | Unknown                     | [a7e98f9a10](https://bsd-hardware.info/?probe=a7e98f9a10) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| ASUSTek       | PRIME H410M-A               | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| HP            | 8054                        | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| YANYU         | H17SL                       | [37a549331f](https://bsd-hardware.info/?probe=37a549331f) | Mar 14, 2023 |
| MSI           | 0A48                        | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| AZW           | U59                         | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Dell          | 0WMJ54 A01                  | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [a3f921de9a](https://bsd-hardware.info/?probe=a3f921de9a) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2050921c3d](https://bsd-hardware.info/?probe=2050921c3d) | Mar 12, 2023 |
| Gigabyte      | B450M K                     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| NF692         | 1.0                         | [16fa0b0102](https://bsd-hardware.info/?probe=16fa0b0102) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6729453203](https://bsd-hardware.info/?probe=6729453203) | Mar 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [6dee276a48](https://bsd-hardware.info/?probe=6dee276a48) | Mar 07, 2023 |
| Gigabyte      | H97M-HD3                    | [77a58527da](https://bsd-hardware.info/?probe=77a58527da) | Mar 01, 2023 |
| Stonesoft     | FW-315-C1                   | [e8a2206ad2](https://bsd-hardware.info/?probe=e8a2206ad2) | Feb 28, 2023 |
| Intel         | JSL MRD                     | [1587ea95da](https://bsd-hardware.info/?probe=1587ea95da) | Feb 18, 2023 |
| Unknown       | SKYBAY                      | [df7f4524d7](https://bsd-hardware.info/?probe=df7f4524d7) | Feb 12, 2023 |
| Unknown       | Unknown                     | [7f9208dc11](https://bsd-hardware.info/?probe=7f9208dc11) | Feb 06, 2023 |
| HP            | 213D A01                    | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| MSI           | MS-7922                     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Gigabyte      | N3160ND3V                   | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Dell          | 0WMJ54 A01                  | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | 0VD5HY A00                  | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| Acer          | Veriton X2610G              | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| ASRock        | J3355B-ITX                  | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | 0WMJ54 A01                  | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| HP            | 1496                        | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| ASUSTek       | M4A87TD EVO                 | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| Dell          | 0WMJ54 A01                  | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Unknown       | Unknown                     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| Unknown       | Unknown                     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| HP            | 0A98h                       | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| T-bao         | MINI PC V1.0                | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Pegatron      | Benicia                     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| Unknown       | Unknown                     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| Unknown       | Unknown                     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| HP            | 3397                        | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| Pegatron      | 2ACF                        | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| Dell          | 0TK7TF A00                  | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| T-bao         | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| Pegatron      | 2ACF                        | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Veriton X2610G              | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASRock        | B75M R2.0                   | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| Protectli     | FW4B                        | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Gigabyte      | P55A-UD3                    | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| Unknown       | Unknown                     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 0R849J A00                  | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Intel         | MAHOBAY                     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| HARDKERNEL    | ODROID-H2                   | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| Dell          | 06NWYK A00                  | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | CRESCENTBAY                 | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| Sun Micros... | Ultra 24 50                 | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| PC Engines    | APU2                        | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| MSI           | Boston                      | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| Unknown       | Unknown                     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Intel         | D945GCLF2                   | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| ASRock        | 990FX Extreme9              | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OpenBSD 7.1       | 8        | 4.37%   |
| helloSystem 0.8.1 | 7        | 3.83%   |
| helloSystem 0.4.0 | 7        | 3.83%   |
| OPNsense 22.7     | 6        | 3.28%   |
| helloSystem 0.7.0 | 6        | 3.28%   |
| OPNsense 23.1.5   | 5        | 2.73%   |
| OPNsense 23.1.6   | 4        | 2.19%   |
| OPNsense 22.7.9   | 4        | 2.19%   |
| OPNsense 22.7.6   | 4        | 2.19%   |
| OPNsense 22.1     | 4        | 2.19%   |
| OPNsense 21.1     | 4        | 2.19%   |
| OpenBSD 7.2       | 4        | 2.19%   |
| helloSystem 0.5.0 | 4        | 2.19%   |
| OPNsense 23.1.9   | 3        | 1.64%   |
| OPNsense 23.1.7   | 3        | 1.64%   |
| OPNsense 23.1.4   | 3        | 1.64%   |
| OPNsense 23.1.11  | 3        | 1.64%   |
| OPNsense 23.1.1   | 3        | 1.64%   |
| OPNsense 23.1     | 3        | 1.64%   |
| OPNsense 22.7.3   | 3        | 1.64%   |
| OPNsense 22.7.10  | 3        | 1.64%   |
| OPNsense 22.1.9   | 3        | 1.64%   |
| OPNsense 22.1.10  | 3        | 1.64%   |
| OPNsense 21.7.3   | 3        | 1.64%   |
| helloSystem 0.8.0 | 3        | 1.64%   |
| helloSystem 0.6.0 | 3        | 1.64%   |
| helloSystem 0.3.0 | 3        | 1.64%   |
| OPNsense 23.7.2   | 2        | 1.09%   |
| OPNsense 23.7.1   | 2        | 1.09%   |
| OPNsense 23.7     | 2        | 1.09%   |
| OPNsense 23.1.8   | 2        | 1.09%   |
| OPNsense 22.7.5   | 2        | 1.09%   |
| OPNsense 22.7.4   | 2        | 1.09%   |
| OPNsense 22.7.2   | 2        | 1.09%   |
| OPNsense 22.7.11  | 2        | 1.09%   |
| OPNsense 22.7.1   | 2        | 1.09%   |
| OPNsense 22.1.8   | 2        | 1.09%   |
| OPNsense 22.1.6   | 2        | 1.09%   |
| OPNsense 22.1.4   | 2        | 1.09%   |
| OPNsense 21.7.7   | 2        | 1.09%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 71       | 53.38%  |
| helloSystem | 25       | 18.8%   |
| OpenBSD     | 16       | 12.03%  |
| FreeBSD     | 16       | 12.03%  |
| NomadBSD    | 2        | 1.5%    |
| NetBSD      | 2        | 1.5%    |
| XigmaNAS    | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 130      | 97.74%  |
| evbarm | 2        | 1.5%    |
| i386   | 1        | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 76       | 56.72%  |
| helloDesktop  | 31       | 23.13%  |
| XFCE          | 10       | 7.46%   |
| MATE          | 4        | 2.99%   |
| TWM           | 3        | 2.24%   |
| Openbox       | 2        | 1.49%   |
| KDE5          | 2        | 1.49%   |
| fvwm          | 2        | 1.49%   |
| xfwm          | 1        | 0.75%   |
| LXDE          | 1        | 0.75%   |
| Enlightenment | 1        | 0.75%   |
| CTWM          | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 79       | 58.96%  |
| X11     | 55       | 41.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 100      | 74.63%  |
| SLiM    | 31       | 23.13%  |
| LightDM | 3        | 2.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 90       | 65.69%  |
| en_US            | 20       | 14.6%   |
| it_IT            | 12       | 8.76%   |
| C                | 8        | 5.84%   |
| fr_FR            | 4        | 2.92%   |
| it_IT.ISO8859-15 | 1        | 0.73%   |
| it               | 1        | 0.73%   |
| en               | 1        | 0.73%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 111      | 82.22%  |
| BIOS | 24       | 17.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 65       | 47.1%   |
| Zfs    | 45       | 32.61%  |
| Ffs    | 16       | 11.59%  |
| Cd9660 | 12       | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 119      | 87.5%   |
| MBR     | 13       | 9.56%   |
| Unknown | 4        | 2.94%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 25       | 18.8%   |
| Unknown                    | 19       | 14.29%  |
| Intel                      | 10       | 7.52%   |
| Hewlett-Packard            | 10       | 7.52%   |
| Gigabyte Technology        | 9        | 6.77%   |
| Dell                       | 9        | 6.77%   |
| PC Engines                 | 7        | 5.26%   |
| MSI                        | 7        | 5.26%   |
| ASRock                     | 7        | 5.26%   |
| Fujitsu                    | 5        | 3.76%   |
| AZW                        | 3        | 2.26%   |
| Supermicro                 | 2        | 1.5%    |
| Protectli                  | 2        | 1.5%    |
| Pegatron                   | 2        | 1.5%    |
| MW                         | 2        | 1.5%    |
| Lenovo                     | 2        | 1.5%    |
| Acer                       | 2        | 1.5%    |
| YANYU                      | 1        | 0.75%   |
| T-bao                      | 1        | 0.75%   |
| Sun Microsystems           | 1        | 0.75%   |
| Stonesoft                  | 1        | 0.75%   |
| ShenZhen MinWin Technology | 1        | 0.75%   |
| NF692                      | 1        | 0.75%   |
| Lex                        | 1        | 0.75%   |
| HARDKERNEL                 | 1        | 0.75%   |
| Foxconn                    | 1        | 0.75%   |
| BESSTAR Tech               | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 19       | 14.29%  |
| PC Engines APU2                         | 4        | 3.01%   |
| Fujitsu FUTRO S920                      | 3        | 2.26%   |
| ASUS PRIME H410M-A                      | 3        | 2.26%   |
| Protectli FW4B                          | 2        | 1.5%    |
| PC Engines apu4                         | 2        | 1.5%    |
| MW GMLK-2_5G4L                          | 2        | 1.5%    |
| MSI MS-7B86                             | 2        | 1.5%    |
| Lenovo ThinkCentre M83 10AHS35Q00       | 2        | 1.5%    |
| Intel Q3XXG4-P V1.0                     | 2        | 1.5%    |
| Intel NCB-4210WG                        | 2        | 1.5%    |
| Gigabyte A520M S2H                      | 2        | 1.5%    |
| Dell OptiPlex 3020                      | 2        | 1.5%    |
| AZW U59                                 | 2        | 1.5%    |
| ASUS PRIME B650-PLUS                    | 2        | 1.5%    |
| ASUS M4A88TD-V EVO/USB3                 | 2        | 1.5%    |
| ASUS IP4BL-ME                           | 2        | 1.5%    |
| YANYU H17SL                             | 1        | 0.75%   |
| T-bao MINI PC                           | 1        | 0.75%   |
| Supermicro X9SCI/X9SCA                  | 1        | 0.75%   |
| Supermicro X8STi                        | 1        | 0.75%   |
| Sun Microsystems Ultra 24               | 1        | 0.75%   |
| Stonesoft FW-315-C1                     | 1        | 0.75%   |
| ShenZhen MinWin MW-NANO-APL-4L          | 1        | 0.75%   |
| Pegatron Pro 3405 Series                | 1        | 0.75%   |
| Pegatron KX629AA-ABZ a6561.it           | 1        | 0.75%   |
| PC Engines APU3                         | 1        | 0.75%   |
| NF692 1.0                               | 1        | 0.75%   |
| MSI NR074AA-ABZ CQ5125IT                | 1        | 0.75%   |
| MSI MS-7D16                             | 1        | 0.75%   |
| MSI MS-7922                             | 1        | 0.75%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159) | 1        | 0.75%   |
| MSI Compaq dx2200 MT                    | 1        | 0.75%   |
| Lex Pineview-D                          | 1        | 0.75%   |
| Intel MAHOBAY                           | 1        | 0.75%   |
| Intel Jasper Lake Client Platform       | 1        | 0.75%   |
| Intel J1900                             | 1        | 0.75%   |
| Intel D945GCLF2                         | 1        | 0.75%   |
| Intel D2500CC AAG81477-401              | 1        | 0.75%   |
| Intel CRESCENTBAY                       | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 19       | 14.29%  |
| ASUS PRIME                     | 10       | 7.52%   |
| PC Engines APU2                | 4        | 3.01%   |
| Dell OptiPlex                  | 4        | 3.01%   |
| HP Compaq                      | 3        | 2.26%   |
| Fujitsu FUTRO                  | 3        | 2.26%   |
| Protectli FW4B                 | 2        | 1.5%    |
| PC Engines apu4                | 2        | 1.5%    |
| MW GMLK-2                      | 2        | 1.5%    |
| MSI MS-7B86                    | 2        | 1.5%    |
| Lenovo ThinkCentre             | 2        | 1.5%    |
| Intel Q3XXG4-P                 | 2        | 1.5%    |
| Intel NCB-4210WG               | 2        | 1.5%    |
| Gigabyte X570                  | 2        | 1.5%    |
| Gigabyte A520M                 | 2        | 1.5%    |
| Fujitsu ESPRIMO                | 2        | 1.5%    |
| Dell Precision                 | 2        | 1.5%    |
| AZW U59                        | 2        | 1.5%    |
| ASUS M4A88TD-V                 | 2        | 1.5%    |
| ASUS IP4BL-ME                  | 2        | 1.5%    |
| YANYU H17SL                    | 1        | 0.75%   |
| T-bao MINI                     | 1        | 0.75%   |
| Supermicro X9SCI               | 1        | 0.75%   |
| Supermicro X8STi               | 1        | 0.75%   |
| Sun Microsystems Ultra         | 1        | 0.75%   |
| Stonesoft FW-315-C1            | 1        | 0.75%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.75%   |
| Pegatron Pro                   | 1        | 0.75%   |
| Pegatron KX629AA-ABZ           | 1        | 0.75%   |
| PC Engines APU3                | 1        | 0.75%   |
| NF692 1.0                      | 1        | 0.75%   |
| MSI NR074AA-ABZ                | 1        | 0.75%   |
| MSI MS-7D16                    | 1        | 0.75%   |
| MSI MS-7922                    | 1        | 0.75%   |
| MSI KBL-U                      | 1        | 0.75%   |
| MSI Compaq                     | 1        | 0.75%   |
| Lex Pineview-D                 | 1        | 0.75%   |
| Intel MAHOBAY                  | 1        | 0.75%   |
| Intel Jasper                   | 1        | 0.75%   |
| Intel J1900                    | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 15       | 11.28%  |
| 2022    | 12       | 9.02%   |
| 2016    | 11       | 8.27%   |
| 2012    | 11       | 8.27%   |
| 2021    | 10       | 7.52%   |
| 2019    | 10       | 7.52%   |
| 2018    | 9        | 6.77%   |
| 2017    | 9        | 6.77%   |
| 2011    | 9        | 6.77%   |
| 2010    | 9        | 6.77%   |
| 2020    | 8        | 6.02%   |
| 2008    | 5        | 3.76%   |
| 2023    | 4        | 3.01%   |
| 2009    | 4        | 3.01%   |
| Unknown | 3        | 2.26%   |
| 2013    | 2        | 1.5%    |
| 2015    | 1        | 0.75%   |
| 2006    | 1        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 133      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 94.03%  |
| Yes  | 8        | 5.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 52       | 38.24%  |
| 4.01-8.0    | 30       | 22.06%  |
| 16.01-24.0  | 27       | 19.85%  |
| 2.01-3.0    | 10       | 7.35%   |
| 32.01-64.0  | 8        | 5.88%   |
| 64.01-256.0 | 3        | 2.21%   |
| 3.01-4.0    | 2        | 1.47%   |
| 24.01-32.0  | 2        | 1.47%   |
| 0.51-1.0    | 2        | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 81       | 60.45%  |
| 0.51-1.0 | 39       | 29.1%   |
| 1.01-2.0 | 8        | 5.97%   |
| 4.01-8.0 | 2        | 1.49%   |
| 2.01-3.0 | 2        | 1.49%   |
| Unknown  | 2        | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 63.04%  |
| 2      | 19       | 13.77%  |
| 0      | 10       | 7.25%   |
| 4      | 9        | 6.52%   |
| 3      | 9        | 6.52%   |
| 10     | 1        | 0.72%   |
| 7      | 1        | 0.72%   |
| 6      | 1        | 0.72%   |
| 5      | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 72.93%  |
| Yes       | 36       | 27.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 130      | 97.74%  |
| No        | 3        | 2.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 80.6%   |
| Yes       | 26       | 19.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 88.06%  |
| Yes       | 16       | 11.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 133      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 24       | 14.72%  |
| Rome                  | 11       | 6.75%   |
| Trieste               | 4        | 2.45%   |
| Naples                | 4        | 2.45%   |
| Monza                 | 3        | 1.84%   |
| Venice                | 2        | 1.23%   |
| Turrivalignani        | 2        | 1.23%   |
| Turin                 | 2        | 1.23%   |
| Taviano               | 2        | 1.23%   |
| Silea                 | 2        | 1.23%   |
| Reggio Emilia         | 2        | 1.23%   |
| Modena                | 2        | 1.23%   |
| Milano                | 2        | 1.23%   |
| Lucca                 | 2        | 1.23%   |
| Genoa                 | 2        | 1.23%   |
| Ferrara               | 2        | 1.23%   |
| Desio                 | 2        | 1.23%   |
| Bologna               | 2        | 1.23%   |
| Ancona                | 2        | 1.23%   |
| Vogogna               | 1        | 0.61%   |
| Viterbo               | 1        | 0.61%   |
| Villa Bartolomea      | 1        | 0.61%   |
| Verona                | 1        | 0.61%   |
| Vanzago               | 1        | 0.61%   |
| Treviso               | 1        | 0.61%   |
| Trento                | 1        | 0.61%   |
| Terni                 | 1        | 0.61%   |
| Soresina              | 1        | 0.61%   |
| Somma Vesuviana       | 1        | 0.61%   |
| Sesto San Giovanni    | 1        | 0.61%   |
| Selvazzano Dentro     | 1        | 0.61%   |
| Sasso Marconi         | 1        | 0.61%   |
| Sarno                 | 1        | 0.61%   |
| Sannicandro di Bari   | 1        | 0.61%   |
| San Vincenzo La Costa | 1        | 0.61%   |
| San Prospero          | 1        | 0.61%   |
| San Giuliano Terme    | 1        | 0.61%   |
| San Donato Milanese   | 1        | 0.61%   |
| Rosignano Marittimo   | 1        | 0.61%   |
| Reggio Calabria       | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 51     | 14.53%  |
| Seagate             | 19       | 30     | 10.61%  |
| Samsung Electronics | 18       | 26     | 10.06%  |
| Crucial             | 16       | 29     | 8.94%   |
| Toshiba             | 15       | 32     | 8.38%   |
| Kingston            | 14       | 16     | 7.82%   |
| Transcend           | 11       | 18     | 6.15%   |
| SanDisk             | 6        | 7      | 3.35%   |
| NVMe                | 6        | 6      | 3.35%   |
| China               | 5        | 10     | 2.79%   |
| Innodisk            | 4        | 6      | 2.23%   |
| Hoodisk             | 4        | 6      | 2.23%   |
| Emtec               | 4        | 6      | 2.23%   |
| OCZ                 | 3        | 3      | 1.68%   |
| Maxtor              | 3        | 3      | 1.68%   |
| Hitachi             | 3        | 3      | 1.68%   |
| PNY                 | 2        | 6      | 1.12%   |
| Phison              | 2        | 2      | 1.12%   |
| Micron Technology   | 2        | 2      | 1.12%   |
| Dogfish             | 2        | 2      | 1.12%   |
| BAITITON            | 2        | 2      | 1.12%   |
| A-DATA Technology   | 2        | 3      | 1.12%   |
| Verbatim            | 1        | 1      | 0.56%   |
| SPCC                | 1        | 1      | 0.56%   |
| Silicon Motion      | 1        | 2      | 0.56%   |
| Pccooler            | 1        | 3      | 0.56%   |
| KingSpec            | 1        | 2      | 0.56%   |
| Intel               | 1        | 2      | 0.56%   |
| HGST                | 1        | 1      | 0.56%   |
| Fanxiang            | 1        | 1      | 0.56%   |
| Corsair             | 1        | 1      | 0.56%   |
| ASint Technology    | 1        | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Crucial CT240BX500SSD1 240GB    | 5        | 2.55%   |
| NVMe Samsung SSD 980 500GB      | 4        | 2.04%   |
| Transcend TS128GMSA230S 128GB   | 3        | 1.53%   |
| Samsung SSD 850 EVO 250GB       | 3        | 1.53%   |
| Kingston SEDC500M480G 480GB     | 3        | 1.53%   |
| Kingston SA400S37120G 120GB     | 3        | 1.53%   |
| Emtec X150 120GB                | 3        | 1.53%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 1.53%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2        | 1.02%   |
| Transcend TS16GMSA370 16GB      | 2        | 1.02%   |
| Toshiba Q300 240GB              | 2        | 1.02%   |
| Toshiba HDWG440 4TB             | 2        | 1.02%   |
| Toshiba HDWD110 1TB             | 2        | 1.02%   |
| Toshiba DT01ACA050 500GB        | 2        | 1.02%   |
| Seagate ST320LT007-9ZV142 320GB | 2        | 1.02%   |
| Seagate ST1000DM003-1ER162 1TB  | 2        | 1.02%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 1.02%   |
| SanDisk SDSSDP128G 128GB        | 2        | 1.02%   |
| Samsung SSD 870 EVO 250GB       | 2        | 1.02%   |
| Samsung SSD 860 EVO 250GB       | 2        | 1.02%   |
| Samsung HM321HI 320GB           | 2        | 1.02%   |
| Phison SATA SSD 16GB            | 2        | 1.02%   |
| OCZ VERTEX3 120GB               | 2        | 1.02%   |
| Maxtor 6V080E0 80GB             | 2        | 1.02%   |
| Kingston SV300S37A120G 120GB    | 2        | 1.02%   |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2        | 1.02%   |
| Hoodisk SSD 256GB               | 2        | 1.02%   |
| Crucial CT500P2SSD8 500GB       | 2        | 1.02%   |
| Crucial CT250MX500SSD1 250GB    | 2        | 1.02%   |
| Crucial CT120BX500SSD1 120GB    | 2        | 1.02%   |
| BAITITON BT58SSD08M 128GB       | 2        | 1.02%   |
| WDC WDS250G2B0A-00SM50 250GB    | 1        | 0.51%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.51%   |
| WDC WDS100T2B0B-00YS70 1TB      | 1        | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.51%   |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.51%   |
| WDC WD6400AAKS-65A7B0 640GB     | 1        | 0.51%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1        | 0.51%   |
| WDC WD5000LPVT-80G33T2 500GB    | 1        | 0.51%   |
| WDC WD5000BPKX-00HPJT0 500GB    | 1        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 46     | 33.85%  |
| Seagate             | 19       | 30     | 29.23%  |
| Toshiba             | 13       | 26     | 20%     |
| Samsung Electronics | 3        | 3      | 4.62%   |
| Maxtor              | 3        | 3      | 4.62%   |
| Hitachi             | 3        | 3      | 4.62%   |
| NVMe                | 1        | 1      | 1.54%   |
| HGST                | 1        | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 14       | 26     | 13.33%  |
| Samsung Electronics | 13       | 18     | 12.38%  |
| Kingston            | 12       | 13     | 11.43%  |
| Transcend           | 11       | 18     | 10.48%  |
| SanDisk             | 6        | 7      | 5.71%   |
| NVMe                | 5        | 5      | 4.76%   |
| China               | 5        | 10     | 4.76%   |
| WDC                 | 4        | 4      | 3.81%   |
| Innodisk            | 4        | 6      | 3.81%   |
| Hoodisk             | 4        | 6      | 3.81%   |
| Emtec               | 4        | 6      | 3.81%   |
| OCZ                 | 3        | 3      | 2.86%   |
| Toshiba             | 2        | 6      | 1.9%    |
| PNY                 | 2        | 6      | 1.9%    |
| Phison              | 2        | 2      | 1.9%    |
| Micron Technology   | 2        | 2      | 1.9%    |
| Dogfish             | 2        | 2      | 1.9%    |
| BAITITON            | 2        | 2      | 1.9%    |
| A-DATA Technology   | 2        | 3      | 1.9%    |
| Verbatim            | 1        | 1      | 0.95%   |
| SPCC                | 1        | 1      | 0.95%   |
| Pccooler            | 1        | 3      | 0.95%   |
| KingSpec            | 1        | 2      | 0.95%   |
| Intel               | 1        | 2      | 0.95%   |
| Corsair             | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 86       | 155    | 59.72%  |
| HDD  | 47       | 113    | 32.64%  |
| NVMe | 11       | 16     | 7.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 119      | 268    | 91.54%  |
| NVMe | 11       | 16     | 8.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 104      | 200    | 72.73%  |
| 0.51-1.0   | 18       | 26     | 12.59%  |
| 1.01-2.0   | 10       | 14     | 6.99%   |
| 3.01-4.0   | 7        | 15     | 4.9%    |
| 4.01-10.0  | 3        | 10     | 2.1%    |
| 2.01-3.0   | 1        | 3      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 47       | 33.57%  |
| 1-20           | 35       | 25%     |
| 251-500        | 21       | 15%     |
| 501-1000       | 11       | 7.86%   |
| 51-100         | 10       | 7.14%   |
| 21-50          | 9        | 6.43%   |
| More than 3000 | 4        | 2.86%   |
| 1001-2000      | 2        | 1.43%   |
| Unknown        | 1        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 122      | 89.71%  |
| 21-50          | 6        | 4.41%   |
| 501-1000       | 2        | 1.47%   |
| 51-100         | 2        | 1.47%   |
| More than 3000 | 1        | 0.74%   |
| 101-250        | 1        | 0.74%   |
| 1001-2000      | 1        | 0.74%   |
| Unknown        | 1        | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2        | 2      | 8.33%   |
| Seagate ST320LT007-9ZV142 320GB   | 2        | 2      | 8.33%   |
| OCZ VERTEX3 120GB                 | 2        | 2      | 8.33%   |
| WDC WD800JD-75MSA3 80GB           | 1        | 1      | 4.17%   |
| WDC WD5000AAKS-00E4A0 500GB       | 1        | 1      | 4.17%   |
| WDC WD20EVDS-63T3B0 2TB           | 1        | 1      | 4.17%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1        | 1      | 4.17%   |
| WDC WD10EZEX-60M2NA0 1TB          | 1        | 1      | 4.17%   |
| WDC WD1000DHTZ-04N21V1 1TB        | 1        | 2      | 4.17%   |
| Transcend TS128GMSA230S 128GB     | 1        | 2      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 5      | 4.17%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1        | 1      | 4.17%   |
| Seagate ST31500341AS 1.5TB        | 1        | 1      | 4.17%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 4.17%   |
| Maxtor 6V080E0 80GB               | 1        | 1      | 4.17%   |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 4.17%   |
| HGST HTS541075A9E680 752GB        | 1        | 1      | 4.17%   |
| China SH00R120GB                  | 1        | 1      | 4.17%   |
| BAITITON BT58SSD08M 128GB         | 1        | 1      | 4.17%   |
| A-DATA Technology SX300 128GB     | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 33.33%  |
| Seagate             | 6        | 10     | 25%     |
| OCZ                 | 2        | 2      | 8.33%   |
| Transcend           | 1        | 2      | 4.17%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| Maxtor              | 1        | 1      | 4.17%   |
| Kingston            | 1        | 1      | 4.17%   |
| HGST                | 1        | 1      | 4.17%   |
| China               | 1        | 1      | 4.17%   |
| BAITITON            | 1        | 1      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 9      | 47.06%  |
| Seagate             | 6        | 10     | 35.29%  |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 22     | 71.43%  |
| SSD  | 6        | 8      | 28.57%  |

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
| Works    | 104      | 232    | 75.36%  |
| Malfunc  | 21       | 30     | 15.22%  |
| Detected | 13       | 22     | 9.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 95       | 57.58%  |
| AMD                              | 35       | 21.21%  |
| Samsung Electronics              | 8        | 4.85%   |
| Marvell Technology Group         | 5        | 3.03%   |
| ASMedia Technology               | 4        | 2.42%   |
| Micron/Crucial Technology        | 3        | 1.82%   |
| VIA Technologies                 | 2        | 1.21%   |
| Kingston Technology Company      | 2        | 1.21%   |
| Broadcom / LSI                   | 2        | 1.21%   |
| Silicon Motion                   | 1        | 0.61%   |
| Silicon Integrated Systems [SiS] | 1        | 0.61%   |
| Silicon Image                    | 1        | 0.61%   |
| SanDisk                          | 1        | 0.61%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.61%   |
| KIOXIA                           | 1        | 0.61%   |
| JMicron Technology               | 1        | 0.61%   |
| Integrated Technology Express    | 1        | 0.61%   |
| Adaptec                          | 1        | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21       | 10.94%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8        | 4.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7        | 3.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6        | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6        | 3.13%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5        | 2.6%    |
| AMD 400 Series Chipset SATA Controller                                           | 5        | 2.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4        | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4        | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4        | 2.08%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 2.08%   |
| AMD 500 Series Chipset SATA Controller                                           | 4        | 2.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3        | 1.56%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 1.56%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3        | 1.56%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2        | 1.04%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2        | 1.04%   |
| Intel SATA Controller [RAID mode]                                                | 2        | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2        | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1        | 0.52%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 1        | 0.52%   |
| Silicon Image SiI 0649 Ultra ATA/100 PCI to ATA Host Controller                  | 1        | 0.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.52%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                      | 1        | 0.52%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 1        | 0.52%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 107      | 67.3%   |
| IDE  | 25       | 15.72%  |
| NVMe | 17       | 10.69%  |
| RAID | 6        | 3.77%   |
| SCSI | 3        | 1.89%   |
| SAS  | 1        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 98       | 73.13%  |
| AMD     | 34       | 25.37%  |
| Arm     | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 7        | 5.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 5        | 3.73%   |
| Intel Celeron N5105 @ 2.00GHz               | 4        | 2.99%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 2.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3        | 2.24%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 3        | 2.24%   |
| AMD Phenom II X4 965 Processor              | 3        | 2.24%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 3        | 2.24%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 1.49%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 1.49%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 1.49%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.49%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2        | 1.49%   |
| Intel Celeron CPU J3355 @ 2.00GHz           | 2        | 1.49%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 2        | 1.49%   |
| Intel Atom CPU D525 @ 1.80GHz               | 2        | 1.49%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.49%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.49%   |
| Intel Xeon E-2236 CPU @ 3.40GHz             | 1        | 0.75%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.75%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 0.75%   |
| Intel Xeon CPU E5440 @ 2.83GHz              | 1        | 0.75%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.75%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH           | 1        | 0.75%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 0.75%   |
| Intel Xeon CPU E31245 @ 3.30GH              | 1        | 0.75%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 0.75%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 0.75%   |
| Intel Pentium Gold 8505                     | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E6600           | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.75%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.75%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1        | 0.75%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 0.75%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.75%   |
| Intel Pentium CPU G3440 @ 3.30GHz           | 1        | 0.75%   |
| Intel Pentium 4 CPU                         | 1        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 27       | 20.15%  |
| Intel Core i5           | 13       | 9.7%    |
| Intel Core i3           | 12       | 8.96%   |
| AMD GX                  | 12       | 8.96%   |
| Intel Core i7           | 10       | 7.46%   |
| Intel Xeon              | 9        | 6.72%   |
| Intel Atom              | 7        | 5.22%   |
| Intel Pentium           | 6        | 4.48%   |
| AMD Ryzen 5             | 6        | 4.48%   |
| AMD Ryzen 9             | 4        | 2.99%   |
| AMD Ryzen 7             | 4        | 2.99%   |
| Intel Pentium Dual-Core | 3        | 2.24%   |
| Intel Pentium Dual      | 3        | 2.24%   |
| AMD Phenom II X4        | 3        | 2.24%   |
| Other                   | 2        | 1.49%   |
| Intel Core 2 Quad       | 2        | 1.49%   |
| Intel Core 2 Duo        | 2        | 1.49%   |
| Intel Pentium Silver    | 1        | 0.75%   |
| Intel Pentium Gold      | 1        | 0.75%   |
| Intel Pentium 4         | 1        | 0.75%   |
| Intel Core 2 Extreme    | 1        | 0.75%   |
| AMD Ryzen 3             | 1        | 0.75%   |
| AMD FX                  | 1        | 0.75%   |
| AMD E2                  | 1        | 0.75%   |
| AMD Athlon II X4        | 1        | 0.75%   |
| AMD A4                  | 1        | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 64       | 48.12%  |
| 2       | 36       | 27.07%  |
| Unknown | 9        | 6.77%   |
| 12      | 6        | 4.51%   |
| 16      | 5        | 3.76%   |
| 6       | 4        | 3.01%   |
| 8       | 3        | 2.26%   |
| 1       | 3        | 2.26%   |
| 32      | 2        | 1.5%    |
| 24      | 1        | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 128      | 96.24%  |
| Unknown | 3        | 2.26%   |
| 2       | 2        | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 84       | 62.69%  |
| 2       | 41       | 30.6%   |
| Unknown | 9        | 6.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 12       | 8.96%   |
| Unknown       | 11       | 8.21%   |
| SandyBridge   | 10       | 7.46%   |
| KabyLake      | 10       | 7.46%   |
| Silvermont    | 8        | 5.97%   |
| Puma          | 8        | 5.97%   |
| Penryn        | 8        | 5.97%   |
| Goldmont plus | 8        | 5.97%   |
| Zen 3         | 7        | 5.22%   |
| Bonnell       | 7        | 5.22%   |
| IvyBridge     | 5        | 3.73%   |
| CometLake     | 5        | 3.73%   |
| K10           | 4        | 2.99%   |
| Jaguar        | 4        | 2.99%   |
| Goldmont      | 4        | 2.99%   |
| Core          | 4        | 2.99%   |
| Zen+          | 3        | 2.24%   |
| Skylake       | 3        | 2.24%   |
| Nehalem       | 3        | 2.24%   |
| Zen 2         | 2        | 1.49%   |
| K10 Llano     | 2        | 1.49%   |
| Zen           | 1        | 0.75%   |
| Westmere      | 1        | 0.75%   |
| Piledriver    | 1        | 0.75%   |
| NetBurst      | 1        | 0.75%   |
| IceLake       | 1        | 0.75%   |
| Broadwell     | 1        | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 72       | 56.69%  |
| AMD                              | 32       | 25.2%   |
| Nvidia                           | 19       | 14.96%  |
| Matrox Electronics Systems       | 2        | 1.57%   |
| Silicon Integrated Systems [SiS] | 1        | 0.79%   |
| ASPEED Technology                | 1        | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 7        | 5.51%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 4.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 3.94%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5        | 3.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 3.15%   |
| Intel HD Graphics 620                                                                    | 4        | 3.15%   |
| Intel HD Graphics 500                                                                    | 4        | 3.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 3.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4        | 3.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 3.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4        | 3.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 3.15%   |
| Intel HD Graphics 630                                                                    | 3        | 2.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.36%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 3        | 2.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 2.36%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.57%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 1.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 2        | 1.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.57%   |
| AMD Raphael                                                                              | 2        | 1.57%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 2        | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.57%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 1.57%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.79%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 0.79%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.79%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1        | 0.79%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1        | 0.79%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 1        | 0.79%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 67       | 49.63%  |
| 1 x AMD        | 30       | 22.22%  |
| 1 x Nvidia     | 16       | 11.85%  |
| Other          | 11       | 8.15%   |
| 2 x Intel      | 4        | 2.96%   |
| 1 x Matrox     | 2        | 1.48%   |
| AMD + Nvidia   | 2        | 1.48%   |
| 1 x SiS        | 1        | 0.74%   |
| Intel + Nvidia | 1        | 0.74%   |
| 1 x ASPEED     | 1        | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 108      | 80%     |
| Proprietary | 15       | 11.11%  |
| Unknown     | 12       | 8.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 110      | 81.48%  |
| 1.01-2.0   | 7        | 5.19%   |
| 3.01-4.0   | 5        | 3.7%    |
| 0.51-1.0   | 5        | 3.7%    |
| 0.01-0.5   | 5        | 3.7%    |
| 5.01-6.0   | 2        | 1.48%   |
| 7.01-8.0   | 1        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 12       | 24.49%  |
| Samsung Electronics  | 9        | 18.37%  |
| Hewlett-Packard      | 7        | 14.29%  |
| Acer                 | 4        | 8.16%   |
| Goldstar             | 3        | 6.12%   |
| Dell                 | 3        | 6.12%   |
| Ancor Communications | 2        | 4.08%   |
| Sony                 | 1        | 2.04%   |
| Packard Bell         | 1        | 2.04%   |
| Orion                | 1        | 2.04%   |
| Mi                   | 1        | 2.04%   |
| LG Electronics       | 1        | 2.04%   |
| Iiyama               | 1        | 2.04%   |
| Eizo                 | 1        | 2.04%   |
| ASUSTek Computer     | 1        | 2.04%   |
| Apple                | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 10       | 20.41%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 4.08%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch      | 2        | 4.08%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 2        | 4.08%   |
| Sony TV SNY5D01 1360x768                                              | 1        | 2.04%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 2.04%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 2.04%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1        | 2.04%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 1        | 2.04%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1        | 2.04%   |
| Samsung Electronics LCD Monitor B2430L 1920x1080                      | 1        | 2.04%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 2.04%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1        | 2.04%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1        | 2.04%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1        | 2.04%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1        | 2.04%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1        | 2.04%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                | 1        | 2.04%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch             | 1        | 2.04%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch             | 1        | 2.04%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 2.04%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1        | 2.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 2.04%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch           | 1        | 2.04%   |
| Eizo LCD Monitor S1901 1280x1024                                      | 1        | 2.04%   |
| Dell U4021QW DEL4206 2560x1080 930x390mm 39.7-inch                    | 1        | 2.04%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                     | 1        | 2.04%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                     | 1        | 2.04%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1        | 2.04%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1        | 2.04%   |
| Ancor Communications VH226 ACI22F2 1920x1080 480x270mm 21.7-inch      | 1        | 2.04%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 2.04%   |
| Acer X203H ACR0097 1600x900 440x250mm 19.9-inch                       | 1        | 2.04%   |
| Acer RT240Y ACR0539 1920x1080 530x300mm 24.0-inch                     | 1        | 2.04%   |
| Acer R271 ACR0496 1920x1080 600x340mm 27.2-inch                       | 1        | 2.04%   |
| Acer AL1917 ACRAD63 1280x1024 380x300mm 19.1-inch                     | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 34       | 73.91%  |
| 1280x1024 (SXGA)  | 3        | 6.52%   |
| 2560x1080         | 2        | 4.35%   |
| 1920x1200 (WUXGA) | 2        | 4.35%   |
| 3840x2160 (4K)    | 1        | 2.17%   |
| 1600x900 (HD+)    | 1        | 2.17%   |
| 1440x900 (WXGA+)  | 1        | 2.17%   |
| 1360x768          | 1        | 2.17%   |
| 1024x768 (XGA)    | 1        | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 13       | 26.53%  |
| Unknown | 8        | 16.33%  |
| 27      | 7        | 14.29%  |
| 24      | 6        | 12.24%  |
| 19      | 4        | 8.16%   |
| 31      | 3        | 6.12%   |
| 23      | 3        | 6.12%   |
| 39      | 1        | 2.04%   |
| 34      | 1        | 2.04%   |
| 28      | 1        | 2.04%   |
| 22      | 1        | 2.04%   |
| 14      | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 15       | 31.91%  |
| 501-600     | 14       | 29.79%  |
| Unknown     | 8        | 17.02%  |
| 601-700     | 5        | 10.64%  |
| 351-400     | 2        | 4.26%   |
| 701-800     | 1        | 2.13%   |
| 201-300     | 1        | 2.13%   |
| 901-1000    | 1        | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 34       | 75.56%  |
| 16/10   | 3        | 6.67%   |
| Unknown | 3        | 6.67%   |
| 5/4     | 2        | 4.44%   |
| 21/9    | 2        | 4.44%   |
| 4/3     | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 40.43%  |
| Unknown        | 8        | 17.02%  |
| 301-350        | 7        | 14.89%  |
| 351-500        | 5        | 10.64%  |
| 151-200        | 4        | 8.51%   |
| 251-300        | 2        | 4.26%   |
| 101-110        | 1        | 2.13%   |
| 501-1000       | 1        | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 53.19%  |
| 101-120 | 13       | 27.66%  |
| Unknown | 8        | 17.02%  |
| 121-160 | 1        | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 85       | 62.96%  |
| 1     | 48       | 35.56%  |
| 2     | 2        | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 80       | 46.51%  |
| Realtek Semiconductor | 68       | 39.53%  |
| Broadcom              | 7        | 4.07%   |
| Qualcomm Atheros      | 5        | 2.91%   |
| Ralink                | 2        | 1.16%   |
| MediaTek              | 2        | 1.16%   |
| Sitecom Europe        | 1        | 0.58%   |
| Ralink Technology     | 1        | 0.58%   |
| Mellanox Technologies | 1        | 0.58%   |
| IMC Networks          | 1        | 0.58%   |
| Google                | 1        | 0.58%   |
| Digital Equipment     | 1        | 0.58%   |
| Davicom Semiconductor | 1        | 0.58%   |
| Aquantia              | 1        | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 59       | 29.5%   |
| Intel I211 Gigabit Network Connection                                                 | 22       | 11%     |
| Intel I210 Gigabit Network Connection                                                 | 8        | 4%      |
| Intel 82574L Gigabit Network Connection                                               | 8        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6        | 3%      |
| Realtek RTL8125 2.5GbE Controller                                                     | 4        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 4        | 2%      |
| Intel Ethernet Controller I226-V                                                      | 4        | 2%      |
| Intel Ethernet Controller I225-V                                                      | 4        | 2%      |
| Intel Wireless 3165                                                                   | 3        | 1.5%    |
| Intel Ethernet Connection I217-LM                                                     | 3        | 1.5%    |
| Intel 82583V Gigabit Network Connection                                               | 3        | 1.5%    |
| Intel 82579V Gigabit Network Connection                                               | 3        | 1.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)         | 3        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2        | 1%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 2        | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 1%      |
| Intel I350 Gigabit Network Connection                                                 | 2        | 1%      |
| Intel DH8900CC Null Device                                                            | 2        | 1%      |
| Intel 82575EB Gigabit Network Connection                                              | 2        | 1%      |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.5%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.5%    |
| Realtek Bluetooth Adapter                                                             | 1        | 0.5%    |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 0.5%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 0.5%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 0.5%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 0.5%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.5%    |
| Mellanox MT27520 Family [ConnectX-3 Pro]                                              | 1        | 0.5%    |
| MediaTek USB Ethernet-RNDIS                                                           | 1        | 0.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 0.5%    |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 29.63%  |
| Realtek Semiconductor | 7        | 25.93%  |
| Qualcomm Atheros      | 5        | 18.52%  |
| Ralink                | 2        | 7.41%   |
| Sitecom Europe        | 1        | 3.7%    |
| Ralink Technology     | 1        | 3.7%    |
| MediaTek              | 1        | 3.7%    |
| IMC Networks          | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                                                   | 3        | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 2        | 6.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 6.67%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 3.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 3.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 3.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 3.33%   |
| Realtek Bluetooth Adapter                                                             | 1        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 3.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 3.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 3.33%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 3.33%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 3.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 1        | 3.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 3.33%   |
| Intel Centrino Advanced-N 6235                                                        | 1        | 3.33%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 3.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1        | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 75       | 50.34%  |
| Realtek Semiconductor | 64       | 42.95%  |
| Broadcom              | 6        | 4.03%   |
| MediaTek              | 1        | 0.67%   |
| Digital Equipment     | 1        | 0.67%   |
| Davicom Semiconductor | 1        | 0.67%   |
| Aquantia              | 1        | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 59       | 35.76%  |
| Intel I211 Gigabit Network Connection                                         | 22       | 13.33%  |
| Intel I210 Gigabit Network Connection                                         | 8        | 4.85%   |
| Intel 82574L Gigabit Network Connection                                       | 8        | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 3.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4        | 2.42%   |
| Intel Ethernet Controller I226-V                                              | 4        | 2.42%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.82%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 1.82%   |
| Intel 82583V Gigabit Network Connection                                       | 3        | 1.82%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 1.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.21%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.21%   |
| Intel 82575EB Gigabit Network Connection                                      | 2        | 1.21%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.61%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.61%   |
| Intel Ethernet Controller I225-LM                                             | 1        | 0.61%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.61%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.61%   |
| Intel 82580 Gigabit Fiber Network Connection                                  | 1        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.61%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 0.61%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.61%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.61%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.61%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.61%   |
| Digital Equipment DECchip 21142/43                                            | 1        | 0.61%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1        | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.61%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 80.75%  |
| WiFi     | 26       | 16.15%  |
| Unknown  | 5        | 3.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 94.89%  |
| WiFi     | 7        | 5.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 45       | 33.58%  |
| 2     | 28       | 20.9%   |
| 3     | 20       | 14.93%  |
| 4     | 18       | 13.43%  |
| 5     | 7        | 5.22%   |
| 6     | 6        | 4.48%   |
| 7     | 4        | 2.99%   |
| 9     | 2        | 1.49%   |
| 0     | 2        | 1.49%   |
| 12    | 1        | 0.75%   |
| 8     | 1        | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 98.5%   |
| Yes  | 2        | 1.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 6        | 37.5%   |
| Cambridge Silicon Radio    | 4        | 25%     |
| Realtek Semiconductor      | 3        | 18.75%  |
| Integrated System Solution | 2        | 12.5%   |
| MediaTek                   | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 25%     |
| Realtek Bluetooth Adapter                           | 2        | 12.5%   |
| Intel Bluetooth wireless interface                  | 2        | 12.5%   |
| Integrated System Solution Bluetooth Device         | 2        | 12.5%   |
| Realtek Bluetooth 4.2 Adapter                       | 1        | 6.25%   |
| MediaTek RZ608 Bluetooth Adapter                    | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 6.25%   |
| Intel AX201 Bluetooth                               | 1        | 6.25%   |
| Intel AX200 Bluetooth                               | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 79       | 54.11%  |
| AMD                              | 37       | 25.34%  |
| Nvidia                           | 17       | 11.64%  |
| C-Media Electronics              | 5        | 3.42%   |
| Logitech                         | 2        | 1.37%   |
| KTMicro                          | 2        | 1.37%   |
| Silicon Integrated Systems [SiS] | 1        | 0.68%   |
| Samson Technologies              | 1        | 0.68%   |
| Plantronics                      | 1        | 0.68%   |
| Bose                             | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8        | 4.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7        | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7        | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6        | 3.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 6        | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6        | 3.43%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6        | 3.43%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 2.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 2.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5        | 2.86%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4        | 2.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 2.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 2.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 1.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 1.71%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3        | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3        | 1.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3        | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 1.71%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 1.14%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2        | 1.14%   |
| KTMicro KT USB Audio                                                                              | 2        | 1.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2        | 1.14%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2        | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2        | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 1.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.14%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 23       | 17.83%  |
| Kingston                     | 20       | 15.5%   |
| Samsung Electronics          | 19       | 14.73%  |
| Crucial                      | 11       | 8.53%   |
| SK hynix                     | 10       | 7.75%   |
| Transcend                    | 5        | 3.88%   |
| Ramaxel Technology           | 4        | 3.1%    |
| Nanya Technology             | 4        | 3.1%    |
| Micron Technology            | 4        | 3.1%    |
| Elpida                       | 4        | 3.1%    |
| Corsair                      | 4        | 3.1%    |
| Unknown                      | 4        | 3.1%    |
| Unknown (ABCD)               | 3        | 2.33%   |
| G.Skill                      | 2        | 1.55%   |
| Unknown (AB)                 | 1        | 0.78%   |
| Unknown (0x0DD5)             | 1        | 0.78%   |
| SK_Hynix                     | 1        | 0.78%   |
| Patriot Memory (PDP Systems) | 1        | 0.78%   |
| KomputerBay                  | 1        | 0.78%   |
| Intersil                     | 1        | 0.78%   |
| Heoriady                     | 1        | 0.78%   |
| A-DATA Technology            | 1        | 0.78%   |
| 2C0C0843D7349CA2             | 1        | 0.78%   |
| 2C0C0843D7349C9D             | 1        | 0.78%   |
| 2C080815D82F5C7B             | 1        | 0.78%   |
| 2C0108214C359D20             | 1        | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 4        | 2.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 3        | 2.07%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3        | 2.07%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 3        | 2.07%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 2        | 1.38%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2        | 1.38%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 1.38%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 2        | 1.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2        | 1.38%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 2        | 1.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 2        | 1.38%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 2        | 1.38%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 2        | 1.38%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s         | 2        | 1.38%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s        | 2        | 1.38%   |
| Crucial RAM CT8G4DFRA32A.M4FF 8GB DIMM DDR4 3200MT/s           | 2        | 1.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1        | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                     | 1        | 0.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.69%   |
| Unknown RAM Module 4GB 1600MT/s                                | 1        | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                   | 1        | 0.69%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1        | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 0.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 0.69%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.69%   |
| Unknown RAM Module 1GB DIMM DDR2                               | 1        | 0.69%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s            | 1        | 0.69%   |
| Unknown (0x0DD5) RAM AZ8G4SW266-8G 8GB SODIMM DDR4 2667MT/s    | 1        | 0.69%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s           | 1        | 0.69%   |
| Transcend RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1        | 0.69%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s          | 1        | 0.69%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1        | 0.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1        | 0.69%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 0.69%   |
| SK hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s            | 1        | 0.69%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 1        | 0.69%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 54       | 48.21%  |
| DDR4    | 33       | 29.46%  |
| DDR2    | 13       | 11.61%  |
| LPDDR4  | 5        | 4.46%   |
| Unknown | 5        | 4.46%   |
| SDRAM   | 2        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 70       | 62.5%   |
| SODIMM       | 38       | 33.93%  |
| Row Of Chips | 2        | 1.79%   |
| FB-DIMM      | 1        | 0.89%   |
| Unknown      | 1        | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 45       | 37.5%   |
| 8192  | 32       | 26.67%  |
| 2048  | 25       | 20.83%  |
| 16384 | 11       | 9.17%   |
| 1024  | 6        | 5%      |
| 32768 | 1        | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 24.58%  |
| 1333    | 23       | 19.49%  |
| 2400    | 13       | 11.02%  |
| 3200    | 10       | 8.47%   |
| 800     | 10       | 8.47%   |
| 2667    | 8        | 6.78%   |
| 2133    | 8        | 6.78%   |
| 1067    | 4        | 3.39%   |
| 667     | 3        | 2.54%   |
| Unknown | 3        | 2.54%   |
| 1066    | 2        | 1.69%   |
| 2933    | 1        | 0.85%   |
| 2666    | 1        | 0.85%   |
| 1866    | 1        | 0.85%   |
| 1334    | 1        | 0.85%   |
| 1200    | 1        | 0.85%   |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 2        | 25%     |
| Genesys Logic                 | 2        | 25%     |
| Trust                         | 1        | 12.5%   |
| Sunplus Innovation Technology | 1        | 12.5%   |
| Microdia                      | 1        | 12.5%   |
| KYE Systems (Mouse Systems)   | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Genesys Logic Digital Microscope                 | 2        | 25%     |
| Trust Trust QHD Webcam                           | 1        | 12.5%   |
| Sunplus Aukey-PC-LM1E Camera                     | 1        | 12.5%   |
| Microdia ASUS USB 2.0 Webcam                     | 1        | 12.5%   |
| Logitech Webcam C310                             | 1        | 12.5%   |
| Logitech C505 HD Webcam                          | 1        | 12.5%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1        | 12.5%   |

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
| 1     | 68       | 50.37%  |
| 0     | 53       | 39.26%  |
| 2     | 7        | 5.19%   |
| 3     | 6        | 4.44%   |
| 4     | 1        | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 65       | 69.15%  |
| Firewire controller      | 9        | 9.57%   |
| Net/wireless             | 8        | 8.51%   |
| Network                  | 3        | 3.19%   |
| Card reader              | 3        | 3.19%   |
| Bluetooth                | 3        | 3.19%   |
| Graphics card            | 2        | 2.13%   |
| Dvb card                 | 1        | 1.06%   |

