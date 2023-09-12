BSD in Italy - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 376

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [f509d12cea](https://bsd-hardware.info/?probe=f509d12cea) | Aug 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [3d3b16c0cf](https://bsd-hardware.info/?probe=3d3b16c0cf) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Protectli     | FW4B                        | Desktop     | [4b358b0106](https://bsd-hardware.info/?probe=4b358b0106) | Aug 24, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| BESSTAR Te... | IB9                         | Desktop     | [c9f5ede507](https://bsd-hardware.info/?probe=c9f5ede507) | Aug 18, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f0398bfb85](https://bsd-hardware.info/?probe=f0398bfb85) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [28f0d503fd](https://bsd-hardware.info/?probe=28f0d503fd) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6238337b24](https://bsd-hardware.info/?probe=6238337b24) | Aug 07, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [155f885c95](https://bsd-hardware.info/?probe=155f885c95) | Aug 01, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a441b76fb8](https://bsd-hardware.info/?probe=a441b76fb8) | Jul 20, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [48fcb6e4ab](https://bsd-hardware.info/?probe=48fcb6e4ab) | Jul 05, 2023 |
| Protectli     | FW4B                        | Desktop     | [a3cf476fe8](https://bsd-hardware.info/?probe=a3cf476fe8) | Jul 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c30f91d5cc](https://bsd-hardware.info/?probe=c30f91d5cc) | Jul 01, 2023 |
| ASUSTek       | N3700T                      | Desktop     | [16b73b05ef](https://bsd-hardware.info/?probe=16b73b05ef) | Jun 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| ASUSTek       | 1015P                       | Notebook    | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [229e573059](https://bsd-hardware.info/?probe=229e573059) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d271bc94c](https://bsd-hardware.info/?probe=9d271bc94c) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fe412825f2](https://bsd-hardware.info/?probe=fe412825f2) | Jun 10, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d08f309c4c](https://bsd-hardware.info/?probe=d08f309c4c) | May 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9160d45441](https://bsd-hardware.info/?probe=9160d45441) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b5ec8c5f4](https://bsd-hardware.info/?probe=8b5ec8c5f4) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b26eac2277](https://bsd-hardware.info/?probe=b26eac2277) | May 13, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1dac5a7bb2](https://bsd-hardware.info/?probe=1dac5a7bb2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [bf8246ecb5](https://bsd-hardware.info/?probe=bf8246ecb5) | May 11, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c6c169e73](https://bsd-hardware.info/?probe=5c6c169e73) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d572f5ff91](https://bsd-hardware.info/?probe=d572f5ff91) | May 01, 2023 |
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1774da050f](https://bsd-hardware.info/?probe=1774da050f) | Apr 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [0471af8c22](https://bsd-hardware.info/?probe=0471af8c22) | Apr 24, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [30062ec670](https://bsd-hardware.info/?probe=30062ec670) | Apr 23, 2023 |
| HP            | 82B4                        | Desktop     | [9ec1e6d6f4](https://bsd-hardware.info/?probe=9ec1e6d6f4) | Apr 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [03dd920110](https://bsd-hardware.info/?probe=03dd920110) | Apr 22, 2023 |
| Sophos        | UTM                         | Firewall    | [85bf260703](https://bsd-hardware.info/?probe=85bf260703) | Apr 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d343800c53](https://bsd-hardware.info/?probe=d343800c53) | Apr 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [9217e1982f](https://bsd-hardware.info/?probe=9217e1982f) | Apr 14, 2023 |
| ASRock        | G31M-S                      | Desktop     | [fed4a42c32](https://bsd-hardware.info/?probe=fed4a42c32) | Apr 08, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4596f78aee](https://bsd-hardware.info/?probe=4596f78aee) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [5168183b15](https://bsd-hardware.info/?probe=5168183b15) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [45f590d129](https://bsd-hardware.info/?probe=45f590d129) | Apr 04, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [ab0643727f](https://bsd-hardware.info/?probe=ab0643727f) | Apr 02, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb6477d43e](https://bsd-hardware.info/?probe=fb6477d43e) | Mar 31, 2023 |
| Dell          | 0M877N A01                  | Server      | [dabe853e69](https://bsd-hardware.info/?probe=dabe853e69) | Mar 30, 2023 |
| LG Electro... | COLUMBIA                    | Notebook    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| YANYU         | H17SL                       | Desktop     | [0f9829ebe4](https://bsd-hardware.info/?probe=0f9829ebe4) | Mar 26, 2023 |
| ASUSTek       | F1A55                       | Desktop     | [91ad5bab75](https://bsd-hardware.info/?probe=91ad5bab75) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7e98f9a10](https://bsd-hardware.info/?probe=a7e98f9a10) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Intel         | S1200RP_SE                  | Notebook    | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| SiComputer    | Embedded                    | Soc         | [9d6aa61a5c](https://bsd-hardware.info/?probe=9d6aa61a5c) | Mar 17, 2023 |
| YANYU         | H17SL                       | Desktop     | [37a549331f](https://bsd-hardware.info/?probe=37a549331f) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a3f921de9a](https://bsd-hardware.info/?probe=a3f921de9a) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2050921c3d](https://bsd-hardware.info/?probe=2050921c3d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Gigabyte      | B450M K                     | Desktop     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| NF692         | 1.0                         | Desktop     | [16fa0b0102](https://bsd-hardware.info/?probe=16fa0b0102) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6729453203](https://bsd-hardware.info/?probe=6729453203) | Mar 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6dee276a48](https://bsd-hardware.info/?probe=6dee276a48) | Mar 07, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [77a58527da](https://bsd-hardware.info/?probe=77a58527da) | Mar 01, 2023 |
| Stonesoft     | FW-315-C1                   | Desktop     | [e8a2206ad2](https://bsd-hardware.info/?probe=e8a2206ad2) | Feb 28, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | Notebook    | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Intel         | JSL MRD                     | Desktop     | [1587ea95da](https://bsd-hardware.info/?probe=1587ea95da) | Feb 18, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [df7f4524d7](https://bsd-hardware.info/?probe=df7f4524d7) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7f9208dc11](https://bsd-hardware.info/?probe=7f9208dc11) | Feb 06, 2023 |
| HP            | Mini 210-1000               | Notebook    | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | 213D A01                    | Desktop     | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Dell          | 0VD5HY A00                  | Desktop     | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | Desktop     | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | Desktop     | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | Desktop     | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| Dell          | 0TY179 A05                  | Server      | [482bca3952](https://bsd-hardware.info/?probe=482bca3952) | Sep 01, 2022 |
| HP            | 1496                        | Desktop     | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [02e11159f5](https://bsd-hardware.info/?probe=02e11159f5) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| BESSTAR Te... | VB9                         | All in one  | [ec5b4884a7](https://bsd-hardware.info/?probe=ec5b4884a7) | Aug 13, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | Desktop     | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| HP            | 0A98h                       | Desktop     | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Acer          | AOD260                      | Notebook    | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | Desktop     | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | F50SL                       | Notebook    | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | Notebook    | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Dell          | 0TY179 A05                  | Server      | [124e42e2c1](https://bsd-hardware.info/?probe=124e42e2c1) | Apr 21, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9a50fe43a7](https://bsd-hardware.info/?probe=9a50fe43a7) | Apr 21, 2022 |
| Pegatron      | Benicia                     | Desktop     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Dell          | 07978V A08                  | Server      | [f315c33e95](https://bsd-hardware.info/?probe=f315c33e95) | Apr 06, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | Desktop     | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9f760529c1](https://bsd-hardware.info/?probe=9f760529c1) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [bb895c5df3](https://bsd-hardware.info/?probe=bb895c5df3) | Mar 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| HP            | 3397                        | Desktop     | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [6696106165](https://bsd-hardware.info/?probe=6696106165) | Feb 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [946c9acc2e](https://bsd-hardware.info/?probe=946c9acc2e) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| Dell          | 0TK7TF A00                  | Desktop     | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | Notebook    | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Acer          | Veriton X2610G              | Desktop     | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [e0ad80acf9](https://bsd-hardware.info/?probe=e0ad80acf9) | Sep 20, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [f1a2baeecb](https://bsd-hardware.info/?probe=f1a2baeecb) | Sep 14, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [3607c373aa](https://bsd-hardware.info/?probe=3607c373aa) | Sep 11, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [73912d5852](https://bsd-hardware.info/?probe=73912d5852) | Sep 09, 2021 |
| Protectli     | FW4B                        | Desktop     | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | Desktop     | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | Desktop     | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [acfe0caa83](https://bsd-hardware.info/?probe=acfe0caa83) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [7fe4b5ff70](https://bsd-hardware.info/?probe=7fe4b5ff70) | Jul 12, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [dbacaa5c65](https://bsd-hardware.info/?probe=dbacaa5c65) | Jul 08, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | Desktop     | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [7cf77c6f1f](https://bsd-hardware.info/?probe=7cf77c6f1f) | Jun 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | Desktop     | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [139e702b9a](https://bsd-hardware.info/?probe=139e702b9a) | Mar 27, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | Desktop     | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 00NH4P A07                  | Server      | [7cff5a5c58](https://bsd-hardware.info/?probe=7cff5a5c58) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [55045aa9e5](https://bsd-hardware.info/?probe=55045aa9e5) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| ASUSTek       | G1S                         | Notebook    | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Dell          | 00NH4P A07                  | Server      | [fff0533829](https://bsd-hardware.info/?probe=fff0533829) | Feb 20, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [01a2dd5a52](https://bsd-hardware.info/?probe=01a2dd5a52) | Feb 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [2aa7735e59](https://bsd-hardware.info/?probe=2aa7735e59) | Jan 24, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | Desktop     | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | Notebook    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | Desktop     | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [6b854263e7](https://bsd-hardware.info/?probe=6b854263e7) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.7.0 | 19        | 6.53%   |
| helloSystem 0.8.1 | 13        | 4.47%   |
| helloSystem 0.4.0 | 12        | 4.12%   |
| OpenBSD 7.1       | 9         | 3.09%   |
| helloSystem 0.5.0 | 9         | 3.09%   |
| OPNsense 22.7     | 7         | 2.41%   |
| helloSystem 0.8.0 | 7         | 2.41%   |
| OPNsense 23.1.6   | 6         | 2.06%   |
| OPNsense 23.1.5   | 6         | 2.06%   |
| helloSystem 0.6.0 | 6         | 2.06%   |
| FreeBSD 13.1      | 6         | 2.06%   |
| OPNsense 22.1.6   | 5         | 1.72%   |
| OPNsense 21.1     | 5         | 1.72%   |
| OpenBSD 7.2       | 5         | 1.72%   |
| helloSystem 0.3.0 | 5         | 1.72%   |
| OPNsense 23.1.11  | 4         | 1.37%   |
| OPNsense 22.7.9   | 4         | 1.37%   |
| OPNsense 22.7.6   | 4         | 1.37%   |
| OPNsense 22.7.3   | 4         | 1.37%   |
| OPNsense 22.7.10  | 4         | 1.37%   |
| OPNsense 22.1.9   | 4         | 1.37%   |
| OPNsense 22.1     | 4         | 1.37%   |
| OPNsense 23.7.2   | 3         | 1.03%   |
| OPNsense 23.1.9   | 3         | 1.03%   |
| OPNsense 23.1.7   | 3         | 1.03%   |
| OPNsense 23.1.4   | 3         | 1.03%   |
| OPNsense 23.1.1   | 3         | 1.03%   |
| OPNsense 23.1     | 3         | 1.03%   |
| OPNsense 22.7.2   | 3         | 1.03%   |
| OPNsense 22.7.1   | 3         | 1.03%   |
| OPNsense 22.1.10  | 3         | 1.03%   |
| OPNsense 21.7.7   | 3         | 1.03%   |
| OPNsense 21.7.3   | 3         | 1.03%   |
| OPNsense 21.1.8   | 3         | 1.03%   |
| OPNsense 21.1.3   | 3         | 1.03%   |
| OPNsense 21.1.2   | 3         | 1.03%   |
| OPNsense 20.7.8   | 3         | 1.03%   |
| OpenBSD 6.8       | 3         | 1.03%   |
| NomadBSD 1.4      | 3         | 1.03%   |
| FreeBSD 13.0-p7   | 3         | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 93        | 41.15%  |
| helloSystem | 60        | 26.55%  |
| FreeBSD     | 33        | 14.6%   |
| OpenBSD     | 20        | 8.85%   |
| NomadBSD    | 7         | 3.1%    |
| NetBSD      | 7         | 3.1%    |
| GhostBSD    | 5         | 2.21%   |
| XigmaNAS    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 219       | 97.33%  |
| i386   | 3         | 1.33%   |
| evbarm | 3         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 103       | 45.18%  |
| helloDesktop  | 66        | 28.95%  |
| XFCE          | 16        | 7.02%   |
| Openbox       | 7         | 3.07%   |
| KDE5          | 7         | 3.07%   |
| MATE          | 5         | 2.19%   |
| TWM           | 4         | 1.75%   |
| fvwm          | 4         | 1.75%   |
| CTWM          | 4         | 1.75%   |
| i3            | 3         | 1.32%   |
| Cinnamon      | 3         | 1.32%   |
| xfwm          | 2         | 0.88%   |
| LXQt          | 1         | 0.44%   |
| LXDE          | 1         | 0.44%   |
| Fluxbox       | 1         | 0.44%   |
| Enlightenment | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 53.54%  |
| Console | 104       | 46.02%  |
| Wayland | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 140       | 61.95%  |
| SLiM    | 73        | 32.3%   |
| LightDM | 8         | 3.54%   |
| SDDM    | 3         | 1.33%   |
| XDM     | 2         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 116       | 50%     |
| en_US            | 60        | 25.86%  |
| it_IT            | 24        | 10.34%  |
| C                | 17        | 7.33%   |
| fr_FR            | 5         | 2.16%   |
| it               | 3         | 1.29%   |
| it_IT.ISO8859-15 | 2         | 0.86%   |
| en               | 2         | 0.86%   |
| ru_RU            | 1         | 0.43%   |
| it_IT.ISO8859-1  | 1         | 0.43%   |
| en_GB            | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 190       | 83.7%   |
| BIOS | 37        | 16.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 101       | 43.72%  |
| Zfs    | 86        | 37.23%  |
| Cd9660 | 24        | 10.39%  |
| Ffs    | 20        | 8.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 202       | 88.6%   |
| MBR     | 20        | 8.77%   |
| Unknown | 6         | 2.63%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 38        | 16.89%  |
| Lenovo                     | 21        | 9.33%   |
| Unknown                    | 21        | 9.33%   |
| Dell                       | 19        | 8.44%   |
| Hewlett-Packard            | 16        | 7.11%   |
| Intel                      | 14        | 6.22%   |
| Gigabyte Technology        | 9         | 4%      |
| MSI                        | 8         | 3.56%   |
| Acer                       | 8         | 3.56%   |
| PC Engines                 | 7         | 3.11%   |
| Fujitsu                    | 7         | 3.11%   |
| ASRock                     | 7         | 3.11%   |
| BESSTAR Tech               | 5         | 2.22%   |
| Apple                      | 4         | 1.78%   |
| AMI                        | 4         | 1.78%   |
| AZW                        | 3         | 1.33%   |
| ZOTAC                      | 2         | 0.89%   |
| Toshiba                    | 2         | 0.89%   |
| Supermicro                 | 2         | 0.89%   |
| Sophos                     | 2         | 0.89%   |
| Protectli                  | 2         | 0.89%   |
| Pegatron                   | 2         | 0.89%   |
| MW                         | 2         | 0.89%   |
| eMachines                  | 2         | 0.89%   |
| YANYU                      | 1         | 0.44%   |
| TUXEDO                     | 1         | 0.44%   |
| T-bao                      | 1         | 0.44%   |
| Sun Microsystems           | 1         | 0.44%   |
| Stonesoft                  | 1         | 0.44%   |
| SiComputer                 | 1         | 0.44%   |
| ShenZhen MinWin Technology | 1         | 0.44%   |
| Samsung Electronics        | 1         | 0.44%   |
| Raspberry Pi Foundation    | 1         | 0.44%   |
| Packard Bell               | 1         | 0.44%   |
| NF692                      | 1         | 0.44%   |
| LG Electronics             | 1         | 0.44%   |
| Lex                        | 1         | 0.44%   |
| IBM                        | 1         | 0.44%   |
| HARDKERNEL                 | 1         | 0.44%   |
| Foxconn                    | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 21        | 9.33%   |
| PC Engines APU2                          | 4         | 1.78%   |
| Fujitsu FUTRO S920                       | 3         | 1.33%   |
| BESSTAR Tech N40                         | 3         | 1.33%   |
| ASUS PRIME H410M-A                       | 3         | 1.33%   |
| Sophos UTM                               | 2         | 0.89%   |
| Protectli FW4B                           | 2         | 0.89%   |
| PC Engines apu4                          | 2         | 0.89%   |
| MW GMLK-2_5G4L                           | 2         | 0.89%   |
| MSI MS-7B86                              | 2         | 0.89%   |
| Lenovo ThinkCentre M83 10AHS35Q00        | 2         | 0.89%   |
| Intel Q3XXG4-P V1.0                      | 2         | 0.89%   |
| Intel NCB-4210WG                         | 2         | 0.89%   |
| HP Laptop 15-da0xxx                      | 2         | 0.89%   |
| Gigabyte A520M S2H                       | 2         | 0.89%   |
| Dell OptiPlex 3020                       | 2         | 0.89%   |
| AZW U59                                  | 2         | 0.89%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 0.89%   |
| ASUS PRIME B650-PLUS                     | 2         | 0.89%   |
| ASUS M4A88TD-V EVO/USB3                  | 2         | 0.89%   |
| ASUS IP4BL-ME                            | 2         | 0.89%   |
| Apple MacBook4,1                         | 2         | 0.89%   |
| AMI Aptio CRB                            | 2         | 0.89%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO         | 1         | 0.44%   |
| ZOTAC ZBOX-CI323NANO                     | 1         | 0.44%   |
| YANYU H17SL                              | 1         | 0.44%   |
| TUXEDO N14xWU                            | 1         | 0.44%   |
| Toshiba Satellite C855-1U4               | 1         | 0.44%   |
| Toshiba PORTEGE M780                     | 1         | 0.44%   |
| T-bao MINI PC                            | 1         | 0.44%   |
| Supermicro X9SCI/X9SCA                   | 1         | 0.44%   |
| Supermicro X8STi                         | 1         | 0.44%   |
| Sun Microsystems Ultra 24                | 1         | 0.44%   |
| Stonesoft FW-315-C1                      | 1         | 0.44%   |
| SiComputer Embedded                      | 1         | 0.44%   |
| ShenZhen MinWin MW-NANO-APL-4L           | 1         | 0.44%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.44%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.44%   |
| Pegatron Pro 3405 Series                 | 1         | 0.44%   |
| Pegatron KX629AA-ABZ a6561.it            | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 21        | 9.33%   |
| Lenovo ThinkPad      | 15        | 6.67%   |
| ASUS PRIME           | 10        | 4.44%   |
| Dell PowerEdge       | 5         | 2.22%   |
| PC Engines APU2      | 4         | 1.78%   |
| Dell OptiPlex        | 4         | 1.78%   |
| Acer Aspire          | 4         | 1.78%   |
| HP Compaq            | 3         | 1.33%   |
| Fujitsu FUTRO        | 3         | 1.33%   |
| Dell Precision       | 3         | 1.33%   |
| BESSTAR Tech N40     | 3         | 1.33%   |
| ASUS VivoBook        | 3         | 1.33%   |
| Sophos UTM           | 2         | 0.89%   |
| Protectli FW4B       | 2         | 0.89%   |
| PC Engines apu4      | 2         | 0.89%   |
| MW GMLK-2            | 2         | 0.89%   |
| MSI MS-7B86          | 2         | 0.89%   |
| Lenovo ThinkCentre   | 2         | 0.89%   |
| Intel Q3XXG4-P       | 2         | 0.89%   |
| Intel NCB-4210WG     | 2         | 0.89%   |
| HP Laptop            | 2         | 0.89%   |
| Gigabyte X570        | 2         | 0.89%   |
| Gigabyte A520M       | 2         | 0.89%   |
| Fujitsu PRIMERGY     | 2         | 0.89%   |
| Fujitsu ESPRIMO      | 2         | 0.89%   |
| Dell Latitude        | 2         | 0.89%   |
| Dell Inspiron        | 2         | 0.89%   |
| AZW U59              | 2         | 0.89%   |
| ASUS M4A88TD-V       | 2         | 0.89%   |
| ASUS IP4BL-ME        | 2         | 0.89%   |
| Apple MacBook4       | 2         | 0.89%   |
| AMI Aptio            | 2         | 0.89%   |
| ZOTAC ZBOX-MI640     | 1         | 0.44%   |
| ZOTAC ZBOX-CI323NANO | 1         | 0.44%   |
| YANYU H17SL          | 1         | 0.44%   |
| TUXEDO N14xWU        | 1         | 0.44%   |
| Toshiba Satellite    | 1         | 0.44%   |
| Toshiba PORTEGE      | 1         | 0.44%   |
| T-bao MINI           | 1         | 0.44%   |
| Supermicro X9SCI     | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 21        | 9.33%   |
| 2019    | 20        | 8.89%   |
| 2021    | 19        | 8.44%   |
| 2016    | 19        | 8.44%   |
| 2011    | 17        | 7.56%   |
| 2010    | 17        | 7.56%   |
| 2018    | 16        | 7.11%   |
| 2022    | 14        | 6.22%   |
| 2020    | 14        | 6.22%   |
| 2012    | 14        | 6.22%   |
| 2013    | 12        | 5.33%   |
| 2017    | 10        | 4.44%   |
| 2008    | 8         | 3.56%   |
| 2009    | 7         | 3.11%   |
| 2023    | 5         | 2.22%   |
| 2015    | 5         | 2.22%   |
| Unknown | 3         | 1.33%   |
| 2007    | 2         | 0.89%   |
| 2006    | 2         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 133       | 59.11%  |
| Notebook       | 67        | 29.78%  |
| Mini pc        | 13        | 5.78%   |
| Server         | 6         | 2.67%   |
| System on chip | 2         | 0.89%   |
| Firewall       | 2         | 0.89%   |
| All in one     | 2         | 0.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 217       | 96.02%  |
| Yes  | 9         | 3.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 86        | 37.39%  |
| 4.01-8.0    | 60        | 26.09%  |
| 16.01-24.0  | 38        | 16.52%  |
| 2.01-3.0    | 19        | 8.26%   |
| 32.01-64.0  | 14        | 6.09%   |
| 64.01-256.0 | 4         | 1.74%   |
| 3.01-4.0    | 3         | 1.3%    |
| 24.01-32.0  | 3         | 1.3%    |
| 0.51-1.0    | 2         | 0.87%   |
| 0.01-0.5    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 141       | 61.3%   |
| 0.51-1.0   | 53        | 23.04%  |
| 1.01-2.0   | 15        | 6.52%   |
| 2.01-3.0   | 7         | 3.04%   |
| Unknown    | 7         | 3.04%   |
| 4.01-8.0   | 5         | 2.17%   |
| 24.01-32.0 | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 65.95%  |
| 2      | 37        | 15.95%  |
| 0      | 17        | 7.33%   |
| 4      | 9         | 3.88%   |
| 3      | 9         | 3.88%   |
| 7      | 2         | 0.86%   |
| 6      | 2         | 0.86%   |
| 10     | 1         | 0.43%   |
| 9      | 1         | 0.43%   |
| 5      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 70.8%   |
| Yes       | 66        | 29.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 95.11%  |
| No        | 11        | 4.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 55.31%  |
| Yes       | 101       | 44.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 70.04%  |
| Yes       | 68        | 29.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 225       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Milan              | 34        | 12.69%  |
| Rome               | 26        | 9.7%    |
| Trieste            | 7         | 2.61%   |
| Bologna            | 7         | 2.61%   |
| Turin              | 6         | 2.24%   |
| Naples             | 4         | 1.49%   |
| Brescia            | 4         | 1.49%   |
| Venice             | 3         | 1.12%   |
| Sesto San Giovanni | 3         | 1.12%   |
| Reggio Emilia      | 3         | 1.12%   |
| Padova             | 3         | 1.12%   |
| Monza              | 3         | 1.12%   |
| Verona             | 2         | 0.75%   |
| Turrivalignani     | 2         | 0.75%   |
| Treviso            | 2         | 0.75%   |
| Taviano            | 2         | 0.75%   |
| Silea              | 2         | 0.75%   |
| Rho                | 2         | 0.75%   |
| Monterotondo       | 2         | 0.75%   |
| Modena             | 2         | 0.75%   |
| Milano             | 2         | 0.75%   |
| Lucca              | 2         | 0.75%   |
| Genoa              | 2         | 0.75%   |
| Gallarate          | 2         | 0.75%   |
| Ferrara            | 2         | 0.75%   |
| Desio              | 2         | 0.75%   |
| Catania            | 2         | 0.75%   |
| Cagliari           | 2         | 0.75%   |
| Arezzo             | 2         | 0.75%   |
| Ancona             | 2         | 0.75%   |
| Adelfia            | 2         | 0.75%   |
| Vogogna            | 1         | 0.37%   |
| Viterbo            | 1         | 0.37%   |
| Villa Bartolomea   | 1         | 0.37%   |
| Vigonza            | 1         | 0.37%   |
| Vigonovo           | 1         | 0.37%   |
| Vanzago            | 1         | 0.37%   |
| Udine              | 1         | 0.37%   |
| Trento             | 1         | 0.37%   |
| Terni              | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 71     | 13.03%  |
| Seagate             | 33        | 62     | 11.62%  |
| Samsung Electronics | 32        | 52     | 11.27%  |
| Crucial             | 24        | 40     | 8.45%   |
| Kingston            | 23        | 26     | 8.1%    |
| Toshiba             | 21        | 46     | 7.39%   |
| Transcend           | 17        | 26     | 5.99%   |
| SanDisk             | 11        | 12     | 3.87%   |
| Hitachi             | 8         | 10     | 2.82%   |
| NVMe                | 6         | 6      | 2.11%   |
| China               | 6         | 11     | 2.11%   |
| Intel               | 5         | 6      | 1.76%   |
| PNY                 | 4         | 8      | 1.41%   |
| Innodisk            | 4         | 6      | 1.41%   |
| Hoodisk             | 4         | 6      | 1.41%   |
| Emtec               | 4         | 6      | 1.41%   |
| OCZ                 | 3         | 3      | 1.06%   |
| Micron Technology   | 3         | 3      | 1.06%   |
| Maxtor              | 3         | 3      | 1.06%   |
| KingSpec            | 3         | 4      | 1.06%   |
| SPCC                | 2         | 2      | 0.7%    |
| Phison              | 2         | 2      | 0.7%    |
| Leven               | 2         | 2      | 0.7%    |
| HGST                | 2         | 2      | 0.7%    |
| FORESEE             | 2         | 3      | 0.7%    |
| Dogfish             | 2         | 2      | 0.7%    |
| Corsair             | 2         | 3      | 0.7%    |
| BAITITON            | 2         | 2      | 0.7%    |
| A-DATA Technology   | 2         | 3      | 0.7%    |
| Verbatim            | 1         | 1      | 0.35%   |
| Union Memory        | 1         | 1      | 0.35%   |
| SK hynix            | 1         | 1      | 0.35%   |
| Silicon Motion      | 1         | 2      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Pccooler            | 1         | 3      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| KingDian            | 1         | 1      | 0.35%   |
| Intenso             | 1         | 1      | 0.35%   |
| Indilinx            | 1         | 1      | 0.35%   |
| Fujitsu             | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB    | 7         | 2.27%   |
| Samsung SSD 860 EVO 500GB       | 4         | 1.3%    |
| Samsung SSD 860 EVO 250GB       | 4         | 1.3%    |
| Samsung SSD 850 EVO 250GB       | 4         | 1.3%    |
| NVMe Samsung SSD 980 500GB      | 4         | 1.3%    |
| Kingston SA400S37120G 120GB     | 4         | 1.3%    |
| Crucial CT500MX500SSD1 500GB    | 4         | 1.3%    |
| Transcend TS128GMSA230S 128GB   | 3         | 0.97%   |
| Seagate ST1000DM003-1ER162 1TB  | 3         | 0.97%   |
| Samsung SSD 850 EVO 500GB       | 3         | 0.97%   |
| Kingston SV300S37A120G 120GB    | 3         | 0.97%   |
| Kingston SEDC500M480G 480GB     | 3         | 0.97%   |
| Kingston SA400S37240G 240GB     | 3         | 0.97%   |
| Emtec X150 120GB                | 3         | 0.97%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2         | 0.65%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2         | 0.65%   |
| Transcend TS64GSSD370 64GB      | 2         | 0.65%   |
| Transcend TS256GMTS430S 256GB   | 2         | 0.65%   |
| Transcend TS16GMSA370 16GB      | 2         | 0.65%   |
| Toshiba Q300 240GB              | 2         | 0.65%   |
| Toshiba MQ04ABF100 1TB          | 2         | 0.65%   |
| Toshiba MQ01ABD100 1TB          | 2         | 0.65%   |
| Toshiba HDWG440 4TB             | 2         | 0.65%   |
| Toshiba HDWD110 1TB             | 2         | 0.65%   |
| Toshiba DT01ACA050 500GB        | 2         | 0.65%   |
| Seagate ST320LT007-9ZV142 320GB | 2         | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB  | 2         | 0.65%   |
| SanDisk SDSSDP128G 128GB        | 2         | 0.65%   |
| Samsung SSD 970 EVO 250GB       | 2         | 0.65%   |
| Samsung SSD 870 EVO 250GB       | 2         | 0.65%   |
| Samsung HM321HI 320GB           | 2         | 0.65%   |
| PNY CS900 120GB SSD             | 2         | 0.65%   |
| Phison SATA SSD 16GB            | 2         | 0.65%   |
| OCZ VERTEX3 120GB               | 2         | 0.65%   |
| Maxtor 6V080E0 80GB             | 2         | 0.65%   |
| KingSpec Q-720 720GB            | 2         | 0.65%   |
| Intel SSDSC2BF180A4L 180GB      | 2         | 0.65%   |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2         | 0.65%   |
| Hoodisk SSD 256GB               | 2         | 0.65%   |
| FORESEE 128GB SSD               | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 62     | 33.67%  |
| WDC                 | 29        | 62     | 29.59%  |
| Toshiba             | 18        | 39     | 18.37%  |
| Hitachi             | 8         | 10     | 8.16%   |
| Samsung Electronics | 3         | 3      | 3.06%   |
| Maxtor              | 3         | 3      | 3.06%   |
| HGST                | 2         | 2      | 2.04%   |
| NVMe                | 1         | 1      | 1.02%   |
| Fujitsu             | 1         | 1      | 1.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 40     | 14.37%  |
| Crucial             | 22        | 37     | 13.17%  |
| Kingston            | 17        | 18     | 10.18%  |
| Transcend           | 16        | 25     | 9.58%   |
| SanDisk             | 11        | 12     | 6.59%   |
| WDC                 | 8         | 8      | 4.79%   |
| China               | 6         | 11     | 3.59%   |
| NVMe                | 5         | 5      | 2.99%   |
| Intel               | 5         | 6      | 2.99%   |
| PNY                 | 4         | 8      | 2.4%    |
| Innodisk            | 4         | 6      | 2.4%    |
| Hoodisk             | 4         | 6      | 2.4%    |
| Emtec               | 4         | 6      | 2.4%    |
| Toshiba             | 3         | 7      | 1.8%    |
| OCZ                 | 3         | 3      | 1.8%    |
| KingSpec            | 3         | 4      | 1.8%    |
| SPCC                | 2         | 2      | 1.2%    |
| Phison              | 2         | 2      | 1.2%    |
| Micron Technology   | 2         | 2      | 1.2%    |
| Leven               | 2         | 2      | 1.2%    |
| FORESEE             | 2         | 3      | 1.2%    |
| Dogfish             | 2         | 2      | 1.2%    |
| Corsair             | 2         | 3      | 1.2%    |
| BAITITON            | 2         | 2      | 1.2%    |
| A-DATA Technology   | 2         | 3      | 1.2%    |
| Verbatim            | 1         | 1      | 0.6%    |
| SK hynix            | 1         | 1      | 0.6%    |
| Plextor             | 1         | 1      | 0.6%    |
| Pccooler            | 1         | 3      | 0.6%    |
| Lexar               | 1         | 1      | 0.6%    |
| KingDian            | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| Indilinx            | 1         | 1      | 0.6%    |
| ASUSTek Computer    | 1         | 2      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 142       | 236    | 59.41%  |
| HDD  | 75        | 183    | 31.38%  |
| NVMe | 22        | 28     | 9.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 196       | 419    | 89.91%  |
| NVMe | 22        | 28     | 10.09%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 169       | 294    | 75.11%  |
| 0.51-1.0   | 32        | 72     | 14.22%  |
| 1.01-2.0   | 11        | 15     | 4.89%   |
| 3.01-4.0   | 7         | 15     | 3.11%   |
| 4.01-10.0  | 3         | 10     | 1.33%   |
| 2.01-3.0   | 2         | 5      | 0.89%   |
| 10.01-20.0 | 1         | 8      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 30.34%  |
| 1-20           | 67        | 28.63%  |
| 251-500        | 36        | 15.38%  |
| 21-50          | 19        | 8.12%   |
| 51-100         | 18        | 7.69%   |
| 501-1000       | 16        | 6.84%   |
| More than 3000 | 4         | 1.71%   |
| 1001-2000      | 2         | 0.85%   |
| Unknown        | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 207       | 89.22%  |
| 21-50          | 14        | 6.03%   |
| 51-100         | 4         | 1.72%   |
| 101-250        | 2         | 0.86%   |
| 501-1000       | 2         | 0.86%   |
| More than 3000 | 1         | 0.43%   |
| 1001-2000      | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB           | 2         | 2      | 5%      |
| Seagate ST320LT007-9ZV142 320GB       | 2         | 2      | 5%      |
| OCZ VERTEX3 120GB                     | 2         | 2      | 5%      |
| Intel SSDSC2BF180A4L 180GB            | 2         | 2      | 5%      |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 2      | 2.5%    |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 2.5%    |
| WDC WD20EVDS-63T3B0 2TB               | 1         | 1      | 2.5%    |
| WDC WD2002FYPS-01U1B1 2TB             | 1         | 1      | 2.5%    |
| WDC WD10EZEX-60M2NA0 1TB              | 1         | 1      | 2.5%    |
| WDC WD1000DHTZ-04N21V1 1TB            | 1         | 2      | 2.5%    |
| Transcend TS128GMSA230S 128GB         | 1         | 2      | 2.5%    |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 2.5%    |
| Seagate ST9750420AS 752GB             | 1         | 1      | 2.5%    |
| Seagate ST9160821AS 160GB             | 1         | 1      | 2.5%    |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BD142 500GB       | 1         | 5      | 2.5%    |
| Seagate ST4000LM024-2AN17V 4TB        | 1         | 1      | 2.5%    |
| Seagate ST31500341AS 1.5TB            | 1         | 1      | 2.5%    |
| SanDisk SDSSDP064G 64GB               | 1         | 1      | 2.5%    |
| SanDisk SD9SN8W-128G-1006 128GB       | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.5%    |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.5%    |
| Maxtor 6V080E0 80GB                   | 1         | 1      | 2.5%    |
| Kingston SV300S37A120G 120GB          | 1         | 1      | 2.5%    |
| Hitachi HTS548040M9AT00 37GB          | 1         | 2      | 2.5%    |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.5%    |
| Hitachi HDS723030ALA640 3TB           | 1         | 2      | 2.5%    |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 2.5%    |
| Crucial CT525MX300SSD1 528GB          | 1         | 3      | 2.5%    |
| China SH00R120GB                      | 1         | 1      | 2.5%    |
| China SATA3 240GB SSD                 | 1         | 1      | 2.5%    |
| BAITITON BT58SSD08M 128GB             | 1         | 1      | 2.5%    |
| A-DATA Technology SX300 128GB         | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 14     | 25%     |
| WDC                 | 9         | 11     | 22.5%   |
| Hitachi             | 3         | 5      | 7.5%    |
| SanDisk             | 2         | 2      | 5%      |
| Samsung Electronics | 2         | 2      | 5%      |
| OCZ                 | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| China               | 2         | 2      | 5%      |
| Transcend           | 1         | 2      | 2.5%    |
| Toshiba             | 1         | 1      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Crucial             | 1         | 3      | 2.5%    |
| BAITITON            | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 14     | 38.46%  |
| WDC                 | 9         | 11     | 34.62%  |
| Hitachi             | 3         | 5      | 11.54%  |
| Toshiba             | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 34     | 64.86%  |
| SSD  | 13        | 17     | 35.14%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 175       | 370    | 77.09%  |
| Malfunc  | 37        | 51     | 16.3%   |
| Detected | 15        | 26     | 6.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 63.5%   |
| AMD                              | 45        | 17.11%  |
| Samsung Electronics              | 12        | 4.56%   |
| Kingston Technology Company      | 6         | 2.28%   |
| Marvell Technology Group         | 5         | 1.9%    |
| Broadcom / LSI                   | 4         | 1.52%   |
| ASMedia Technology               | 4         | 1.52%   |
| Micron/Crucial Technology        | 3         | 1.14%   |
| VIA Technologies                 | 2         | 0.76%   |
| Silicon Integrated Systems [SiS] | 2         | 0.76%   |
| JMicron Technology               | 2         | 0.76%   |
| Union Memory (Shenzhen)          | 1         | 0.38%   |
| Transcend                        | 1         | 0.38%   |
| Silicon Motion                   | 1         | 0.38%   |
| Silicon Image                    | 1         | 0.38%   |
| SanDisk                          | 1         | 0.38%   |
| Nvidia                           | 1         | 0.38%   |
| Micron Technology                | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.38%   |
| KIOXIA                           | 1         | 0.38%   |
| Integrated Technology Express    | 1         | 0.38%   |
| Adaptec                          | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 9.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 3.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 2.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 2.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 2.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 8         | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 2.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.97%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.31%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.31%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.98%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 0.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 3         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.98%   |
| AMD FCH SATA Controller [IDE mode]                                               | 3         | 0.98%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2         | 0.66%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.66%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 181       | 68.56%  |
| IDE  | 41        | 15.53%  |
| NVMe | 27        | 10.23%  |
| RAID | 11        | 4.17%   |
| SCSI | 3         | 1.14%   |
| SAS  | 1         | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 177       | 78.32%  |
| AMD      | 46        | 20.35%  |
| Broadcom | 1         | 0.44%   |
| Arm      | 1         | 0.44%   |
| Unknown  | 1         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                              | 7         | 3.08%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 6         | 2.64%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 5         | 2.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.76%   |
| Intel Celeron N5105 @ 2.00GHz                 | 4         | 1.76%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 4         | 1.76%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.32%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 1.32%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.32%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 1.32%   |
| AMD Phenom II X4 965 Processor                | 3         | 1.32%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 3         | 1.32%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 0.88%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 2         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.88%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2         | 0.88%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.88%   |
| Intel Celeron J4105 CPU @ 1.50GHz             | 2         | 0.88%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 0.88%   |
| Intel Celeron CPU J3355 @ 2.00GHz             | 2         | 0.88%   |
| Intel Atom CPU E3826 @ 1.46GHz                | 2         | 0.88%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 2         | 0.88%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.88%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz         | 1         | 0.44%   |
| Intel Xeon E-2236 CPU @ 3.40GHz               | 1         | 0.44%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.44%   |
| Intel Xeon CPU X3470 @ 2.93GHz                | 1         | 0.44%   |
| Intel Xeon CPU X3430 @ 2.40GHz                | 1         | 0.44%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1         | 0.44%   |
| Intel Xeon CPU E5440 @ 2.83GHz                | 1         | 0.44%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.44%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH             | 1         | 0.44%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 39        | 17.18%  |
| Intel Core i5           | 35        | 15.42%  |
| Intel Core i7           | 22        | 9.69%   |
| Intel Core i3           | 16        | 7.05%   |
| Intel Atom              | 15        | 6.61%   |
| Intel Xeon              | 14        | 6.17%   |
| AMD GX                  | 12        | 5.29%   |
| Intel Pentium           | 10        | 4.41%   |
| AMD Ryzen 5             | 9         | 3.96%   |
| Intel Core 2 Duo        | 8         | 3.52%   |
| Other                   | 5         | 2.2%    |
| Intel Pentium Dual-Core | 5         | 2.2%    |
| AMD Ryzen 9             | 4         | 1.76%   |
| AMD Ryzen 7             | 4         | 1.76%   |
| Intel Pentium Dual      | 3         | 1.32%   |
| AMD Phenom II X4        | 3         | 1.32%   |
| Intel Core 2 Quad       | 2         | 0.88%   |
| AMD A4                  | 2         | 0.88%   |
| Intel Xeon Silver       | 1         | 0.44%   |
| Intel Pentium Silver    | 1         | 0.44%   |
| Intel Pentium M         | 1         | 0.44%   |
| Intel Pentium Gold      | 1         | 0.44%   |
| Intel Pentium 4         | 1         | 0.44%   |
| Intel Core 2 Extreme    | 1         | 0.44%   |
| Intel Core 2            | 1         | 0.44%   |
| Intel 686-class         | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Ryzen Embedded      | 1         | 0.44%   |
| AMD Ryzen 7 PRO         | 1         | 0.44%   |
| AMD Ryzen 3             | 1         | 0.44%   |
| AMD Opteron             | 1         | 0.44%   |
| AMD FX                  | 1         | 0.44%   |
| AMD E2                  | 1         | 0.44%   |
| AMD E1                  | 1         | 0.44%   |
| AMD E                   | 1         | 0.44%   |
| AMD Athlon II X4        | 1         | 0.44%   |
| AMD A6                  | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 85        | 37.61%  |
| 4       | 83        | 36.73%  |
| Unknown | 19        | 8.41%   |
| 12      | 9         | 3.98%   |
| 8       | 9         | 3.98%   |
| 1       | 8         | 3.54%   |
| 16      | 5         | 2.21%   |
| 6       | 5         | 2.21%   |
| 32      | 2         | 0.88%   |
| 24      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 216       | 95.58%  |
| 2       | 6         | 2.65%   |
| Unknown | 4         | 1.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 120       | 52.86%  |
| 2       | 88        | 38.77%  |
| Unknown | 19        | 8.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 18        | 7.93%   |
| SandyBridge   | 17        | 7.49%   |
| Penryn        | 17        | 7.49%   |
| KabyLake      | 17        | 7.49%   |
| Silvermont    | 16        | 7.05%   |
| Unknown       | 15        | 6.61%   |
| Bonnell       | 13        | 5.73%   |
| Goldmont plus | 12        | 5.29%   |
| IvyBridge     | 11        | 4.85%   |
| Broadwell     | 10        | 4.41%   |
| Skylake       | 9         | 3.96%   |
| Puma          | 9         | 3.96%   |
| Zen 3         | 7         | 3.08%   |
| CometLake     | 7         | 3.08%   |
| Zen+          | 6         | 2.64%   |
| Westmere      | 6         | 2.64%   |
| Jaguar        | 6         | 2.64%   |
| Core          | 5         | 2.2%    |
| Nehalem       | 4         | 1.76%   |
| K10           | 4         | 1.76%   |
| Goldmont      | 4         | 1.76%   |
| Zen           | 3         | 1.32%   |
| Zen 2         | 2         | 0.88%   |
| K10 Llano     | 2         | 0.88%   |
| Piledriver    | 1         | 0.44%   |
| P6            | 1         | 0.44%   |
| NetBurst      | 1         | 0.44%   |
| K8 Hammer     | 1         | 0.44%   |
| IceLake       | 1         | 0.44%   |
| Bulldozer     | 1         | 0.44%   |
| Bobcat        | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 137       | 60.09%  |
| AMD                              | 52        | 22.81%  |
| Nvidia                           | 30        | 13.16%  |
| Matrox Electronics Systems       | 7         | 3.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| ASPEED Technology                | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 3.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 9         | 3.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.02%   |
| Intel HD Graphics 620                                                                    | 6         | 2.59%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.59%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 2.59%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 2.16%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5         | 2.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.72%   |
| Intel HD Graphics 500                                                                    | 4         | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 3         | 1.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.29%   |
| Intel HD Graphics 630                                                                    | 3         | 1.29%   |
| Intel HD Graphics 6000                                                                   | 3         | 1.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.29%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 3         | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.29%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.86%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 2         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.86%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.86%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.86%   |
| Intel HD Graphics 530                                                                    | 2         | 0.86%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 2         | 0.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.86%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 112       | 49.34%  |
| 1 x AMD        | 46        | 20.26%  |
| 1 x Nvidia     | 19        | 8.37%   |
| 2 x Intel      | 14        | 6.17%   |
| Other          | 13        | 5.73%   |
| Intel + Nvidia | 9         | 3.96%   |
| 1 x Matrox     | 6         | 2.64%   |
| Intel + AMD    | 2         | 0.88%   |
| AMD + Nvidia   | 2         | 0.88%   |
| 2 x AMD        | 1         | 0.44%   |
| 1 x SiS        | 1         | 0.44%   |
| 1 x ASPEED     | 1         | 0.44%   |
| AMD + Matrox   | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 191       | 83.41%  |
| Proprietary | 20        | 8.73%   |
| Unknown     | 18        | 7.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 81.5%   |
| 0.01-0.5   | 15        | 6.61%   |
| 1.01-2.0   | 12        | 5.29%   |
| 3.01-4.0   | 6         | 2.64%   |
| 0.51-1.0   | 6         | 2.64%   |
| 5.01-6.0   | 2         | 0.88%   |
| 7.01-8.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 15        | 14.71%  |
| Philips              | 12        | 11.76%  |
| Samsung Electronics  | 11        | 10.78%  |
| LG Display           | 10        | 9.8%    |
| Hewlett-Packard      | 8         | 7.84%   |
| Acer                 | 6         | 5.88%   |
| Chimei Innolux       | 5         | 4.9%    |
| BOE                  | 5         | 4.9%    |
| Dell                 | 4         | 3.92%   |
| Apple                | 4         | 3.92%   |
| HannStar             | 3         | 2.94%   |
| Goldstar             | 3         | 2.94%   |
| Lenovo               | 2         | 1.96%   |
| Ancor Communications | 2         | 1.96%   |
| ___                  | 1         | 0.98%   |
| Sony                 | 1         | 0.98%   |
| Packard Bell         | 1         | 0.98%   |
| Orion                | 1         | 0.98%   |
| Mi                   | 1         | 0.98%   |
| LPL                  | 1         | 0.98%   |
| LG Philips           | 1         | 0.98%   |
| LG Electronics       | 1         | 0.98%   |
| Iiyama               | 1         | 0.98%   |
| Fujitsu Siemens      | 1         | 0.98%   |
| Eizo                 | 1         | 0.98%   |
| ASUSTek Computer     | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 10        | 9.8%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 2         | 1.96%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch     | 2         | 1.96%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch            | 2         | 1.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 2         | 1.96%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                      | 2         | 1.96%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 0.98%   |
| Sony TV SNY5D01 1360x768                                             | 1         | 0.98%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 0.98%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                     | 1         | 0.98%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 0.98%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor B2430L 1920x1080                     | 1         | 0.98%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch             | 1         | 0.98%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch             | 1         | 0.98%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch       | 1         | 0.98%   |
| Orion LCD Monitor ORN1207 1920x1080                                  | 1         | 0.98%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                     | 1         | 0.98%   |
| LPL LCD Monitor 1680x1050                                            | 1         | 0.98%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 0.98%   |
| LG Electronics LCD Monitor E2360 1920x1080                           | 1         | 0.98%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch         | 1         | 0.98%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 0.98%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 0.98%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 0.98%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 0.98%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 51.02%  |
| 1366x768 (WXGA)    | 22        | 22.45%  |
| 1440x900 (WXGA+)   | 4         | 4.08%   |
| 1600x900 (HD+)     | 3         | 3.06%   |
| 1280x1024 (SXGA)   | 3         | 3.06%   |
| 1024x600           | 3         | 3.06%   |
| 2560x1080          | 2         | 2.04%   |
| 1920x1200 (WUXGA)  | 2         | 2.04%   |
| 1280x800 (WXGA)    | 2         | 2.04%   |
| 3840x2400          | 1         | 1.02%   |
| 3840x2160 (4K)     | 1         | 1.02%   |
| 2560x1440 (QHD)    | 1         | 1.02%   |
| 1680x1050 (WSXGA+) | 1         | 1.02%   |
| 1600x1200          | 1         | 1.02%   |
| 1360x768           | 1         | 1.02%   |
| 1024x768 (XGA)     | 1         | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 25        | 24.51%  |
| 21      | 13        | 12.75%  |
| 13      | 11        | 10.78%  |
| Unknown | 10        | 9.8%    |
| 27      | 8         | 7.84%   |
| 24      | 7         | 6.86%   |
| 23      | 5         | 4.9%    |
| 19      | 4         | 3.92%   |
| 31      | 3         | 2.94%   |
| 10      | 3         | 2.94%   |
| 18      | 2         | 1.96%   |
| 17      | 2         | 1.96%   |
| 12      | 2         | 1.96%   |
| 39      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 28      | 1         | 0.98%   |
| 22      | 1         | 0.98%   |
| 20      | 1         | 0.98%   |
| 14      | 1         | 0.98%   |
| 11      | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 34%     |
| 501-600     | 18        | 18%     |
| 401-500     | 16        | 16%     |
| Unknown     | 10        | 10%     |
| 201-300     | 9         | 9%      |
| 351-400     | 6         | 6%      |
| 601-700     | 5         | 5%      |
| 701-800     | 1         | 1%      |
| 901-1000    | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 76        | 80%     |
| 16/10   | 9         | 9.47%   |
| Unknown | 4         | 4.21%   |
| 5/4     | 2         | 2.11%   |
| 4/3     | 2         | 2.11%   |
| 21/9    | 2         | 2.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 22        | 22.22%  |
| 91-100         | 17        | 17.17%  |
| 81-90          | 11        | 11.11%  |
| Unknown        | 10        | 10.1%   |
| 301-350        | 8         | 8.08%   |
| 101-110        | 8         | 8.08%   |
| 151-200        | 6         | 6.06%   |
| 351-500        | 5         | 5.05%   |
| 41-50          | 3         | 3.03%   |
| 61-70          | 2         | 2.02%   |
| 251-300        | 2         | 2.02%   |
| 121-130        | 2         | 2.02%   |
| 51-60          | 1         | 1.01%   |
| 111-120        | 1         | 1.01%   |
| 501-1000       | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 35        | 35.71%  |
| 51-100        | 35        | 35.71%  |
| 121-160       | 16        | 16.33%  |
| Unknown       | 10        | 10.2%   |
| More than 240 | 1         | 1.02%   |
| 161-240       | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 120       | 52.4%   |
| 1     | 104       | 45.41%  |
| 2     | 5         | 2.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 130       | 41.27%  |
| Realtek Semiconductor            | 98        | 31.11%  |
| Qualcomm Atheros                 | 33        | 10.48%  |
| Broadcom                         | 21        | 6.67%   |
| Ralink Technology                | 4         | 1.27%   |
| MediaTek                         | 3         | 0.95%   |
| Samsung Electronics              | 2         | 0.63%   |
| Ralink                           | 2         | 0.63%   |
| Marvell Technology Group         | 2         | 0.63%   |
| Huawei Technologies              | 2         | 0.63%   |
| Xiaomi                           | 1         | 0.32%   |
| Sitecom Europe                   | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| OPPO Electronics                 | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| NetGear                          | 1         | 0.32%   |
| Mellanox Technologies            | 1         | 0.32%   |
| JMicron Technology               | 1         | 0.32%   |
| IMC Networks                     | 1         | 0.32%   |
| Hewlett-Packard                  | 1         | 0.32%   |
| Google                           | 1         | 0.32%   |
| Edimax Technology                | 1         | 0.32%   |
| Digital Equipment                | 1         | 0.32%   |
| Davicom Semiconductor            | 1         | 0.32%   |
| BUFFALO                          | 1         | 0.32%   |
| Aquantia                         | 1         | 0.32%   |
| Apple                            | 1         | 0.32%   |
| AMD                              | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 84        | 21.99%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 6.81%   |
| Intel I210 Gigabit Network Connection                                         | 11        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.36%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 1.83%   |
| Intel Wireless 7265                                                           | 7         | 1.83%   |
| Intel Wireless 3165                                                           | 7         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 6         | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 1.31%   |
| Intel Wireless 8260                                                           | 5         | 1.31%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 1.05%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.05%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.05%   |
| Intel Ethernet Controller I225-V                                              | 4         | 1.05%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 0.79%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 0.79%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.52%   |
| Intel Wireless 7260                                                           | 2         | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 2         | 0.52%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 36.94%  |
| Qualcomm Atheros      | 32        | 28.83%  |
| Realtek Semiconductor | 15        | 13.51%  |
| Broadcom              | 10        | 9.01%   |
| Ralink Technology     | 4         | 3.6%    |
| Ralink                | 2         | 1.8%    |
| MediaTek              | 2         | 1.8%    |
| Sitecom Europe        | 1         | 0.9%    |
| NetGear               | 1         | 0.9%    |
| IMC Networks          | 1         | 0.9%    |
| Edimax Technology     | 1         | 0.9%    |
| BUFFALO               | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 7         | 6.14%   |
| Intel Wireless 7265                                                                   | 7         | 6.14%   |
| Intel Wireless 3165                                                                   | 7         | 6.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 6         | 5.26%   |
| Intel Wireless 8260                                                                   | 5         | 4.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 4         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 3.51%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 3         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 1.75%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.75%   |
| Intel Wireless 7260                                                                   | 2         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 2         | 1.75%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 1.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 1.75%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1         | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.88%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.88%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.88%   |
| Realtek Bluetooth Adapter                                                             | 1         | 0.88%   |
| Ralink RT5572 Wireless Adapter                                                        | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.88%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.88%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.88%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.88%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.88%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 110       | 45.83%  |
| Realtek Semiconductor            | 93        | 38.75%  |
| Broadcom                         | 12        | 5%      |
| Qualcomm Atheros                 | 10        | 4.17%   |
| Samsung Electronics              | 2         | 0.83%   |
| Marvell Technology Group         | 2         | 0.83%   |
| Xiaomi                           | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| OPPO Electronics                 | 1         | 0.42%   |
| Nvidia                           | 1         | 0.42%   |
| MediaTek                         | 1         | 0.42%   |
| JMicron Technology               | 1         | 0.42%   |
| Digital Equipment                | 1         | 0.42%   |
| Davicom Semiconductor            | 1         | 0.42%   |
| Aquantia                         | 1         | 0.42%   |
| Apple                            | 1         | 0.42%   |
| AMD                              | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 84        | 32.43%  |
| Intel I211 Gigabit Network Connection                                         | 26        | 10.04%  |
| Intel I210 Gigabit Network Connection                                         | 11        | 4.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 3.47%   |
| Intel 82574L Gigabit Network Connection                                       | 9         | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5         | 1.93%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.93%   |
| Intel Ethernet Controller I226-V                                              | 4         | 1.54%   |
| Intel Ethernet Controller I225-V                                              | 4         | 1.54%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 1.16%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.16%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 1.16%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.77%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.77%   |
| Intel 82575EB Gigabit Network Connection                                      | 2         | 0.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.77%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2         | 0.77%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.39%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                                | 1         | 0.39%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.39%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.39%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.39%   |
| Intel Ethernet Controller I225-LM                                             | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 66.05%  |
| WiFi     | 101       | 31.17%  |
| Unknown  | 6         | 1.85%   |
| Modem    | 3         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 191       | 77.96%  |
| WiFi     | 54        | 22.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 92        | 40.71%  |
| 1     | 54        | 23.89%  |
| 3     | 26        | 11.5%   |
| 4     | 23        | 10.18%  |
| 5     | 10        | 4.42%   |
| 6     | 9         | 3.98%   |
| 7     | 4         | 1.77%   |
| 0     | 3         | 1.33%   |
| 9     | 2         | 0.88%   |
| 8     | 2         | 0.88%   |
| 12    | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 98.67%  |
| Yes  | 3         | 1.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 40.85%  |
| Realtek Semiconductor           | 6         | 8.45%   |
| Qualcomm Atheros Communications | 6         | 8.45%   |
| Cambridge Silicon Radio         | 6         | 8.45%   |
| IMC Networks                    | 5         | 7.04%   |
| Broadcom                        | 5         | 7.04%   |
| Lite-On Technology              | 4         | 5.63%   |
| Apple                           | 3         | 4.23%   |
| Integrated System Solution      | 2         | 2.82%   |
| Toshiba                         | 1         | 1.41%   |
| MediaTek                        | 1         | 1.41%   |
| Hewlett-Packard                 | 1         | 1.41%   |
| Foxconn / Hon Hai               | 1         | 1.41%   |
| ASUSTek Computer                | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 29.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 8.45%   |
| Intel AX201 Bluetooth                                       | 3         | 4.23%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.82%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.82%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.82%   |
| Integrated System Solution Bluetooth Device                 | 2         | 2.82%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.82%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 2.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.82%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.41%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.41%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.41%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.41%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 1.41%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.41%   |
| Intel AX210 Bluetooth                                       | 1         | 1.41%   |
| Intel AX200 Bluetooth                                       | 1         | 1.41%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.41%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.41%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.41%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.41%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.41%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.41%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 61.37%  |
| AMD                              | 54        | 23.18%  |
| Nvidia                           | 21        | 9.01%   |
| C-Media Electronics              | 6         | 2.58%   |
| Silicon Integrated Systems [SiS] | 2         | 0.86%   |
| Logitech                         | 2         | 0.86%   |
| KTMicro                          | 2         | 0.86%   |
| Samson Technologies              | 1         | 0.43%   |
| Plantronics                      | 1         | 0.43%   |
| Bose                             | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 4.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 4.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 4.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 4.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 3.16%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.16%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 2.11%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 2.11%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.75%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.4%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.4%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 1.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.05%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.05%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 20.09%  |
| Unknown                      | 33        | 14.1%   |
| Kingston                     | 29        | 12.39%  |
| SK hynix                     | 28        | 11.97%  |
| Crucial                      | 16        | 6.84%   |
| Micron Technology            | 15        | 6.41%   |
| Unknown                      | 13        | 5.56%   |
| Unknown (ABCD)               | 7         | 2.99%   |
| Transcend                    | 7         | 2.99%   |
| Nanya Technology             | 7         | 2.99%   |
| Ramaxel Technology           | 5         | 2.14%   |
| Elpida                       | 4         | 1.71%   |
| Corsair                      | 4         | 1.71%   |
| A-DATA Technology            | 3         | 1.28%   |
| G.Skill                      | 2         | 0.85%   |
| Unknown (F301)               | 1         | 0.43%   |
| Unknown (AB)                 | 1         | 0.43%   |
| Unknown (0x0DD5)             | 1         | 0.43%   |
| SK_Hynix                     | 1         | 0.43%   |
| Patriot Memory (PDP Systems) | 1         | 0.43%   |
| KomputerBay                  | 1         | 0.43%   |
| Intersil                     | 1         | 0.43%   |
| Heoriady                     | 1         | 0.43%   |
| ASint Technology             | 1         | 0.43%   |
| Apacer                       | 1         | 0.43%   |
| 2C0C0843D7349CA2             | 1         | 0.43%   |
| 2C0C0843D7349C9D             | 1         | 0.43%   |
| 2C080815D82F5C7B             | 1         | 0.43%   |
| 2C0108214C359D20             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 13        | 5.1%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7         | 2.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 4         | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 3         | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 1.18%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 3         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 2         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 2         | 0.78%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2         | 0.78%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2         | 0.78%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 2         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.78%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1333MT/s           | 2         | 0.78%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                    | 2         | 0.78%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s         | 2         | 0.78%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s        | 2         | 0.78%   |
| Crucial RAM CT8G4DFRA32A.M4FF 8GB DIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                              | 1         | 0.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                    | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1         | 0.39%   |
| Unknown RAM Module 4GB 1600MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 99        | 49.25%  |
| DDR4    | 53        | 26.37%  |
| DDR2    | 24        | 11.94%  |
| LPDDR4  | 10        | 4.98%   |
| Unknown | 8         | 3.98%   |
| SDRAM   | 5         | 2.49%   |
| LPDDR3  | 1         | 0.5%    |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 52%     |
| DIMM         | 86        | 43%     |
| Row Of Chips | 4         | 2%      |
| Chip         | 4         | 2%      |
| FB-DIMM      | 1         | 0.5%    |
| Unknown      | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 80        | 36.53%  |
| 8192  | 56        | 25.57%  |
| 2048  | 48        | 21.92%  |
| 16384 | 23        | 10.5%   |
| 1024  | 8         | 3.65%   |
| 32768 | 3         | 1.37%   |
| 256   | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 25.35%  |
| 1333    | 33        | 15.49%  |
| 2400    | 23        | 10.8%   |
| 2667    | 16        | 7.51%   |
| 3200    | 15        | 7.04%   |
| 2133    | 14        | 6.57%   |
| 667     | 14        | 6.57%   |
| 800     | 12        | 5.63%   |
| 1067    | 8         | 3.76%   |
| Unknown | 7         | 3.29%   |
| 1066    | 6         | 2.82%   |
| 1334    | 4         | 1.88%   |
| 2933    | 1         | 0.47%   |
| 2666    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1867    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1200    | 1         | 0.47%   |
| 333     | 1         | 0.47%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 16        | 27.12%  |
| IMC Networks                           | 8         | 13.56%  |
| Realtek Semiconductor                  | 7         | 11.86%  |
| Sunplus Innovation Technology          | 5         | 8.47%   |
| Bison Electronics                      | 5         | 8.47%   |
| ALi                                    | 3         | 5.08%   |
| Silicon Motion                         | 2         | 3.39%   |
| Microdia                               | 2         | 3.39%   |
| Logitech                               | 2         | 3.39%   |
| Genesys Logic                          | 2         | 3.39%   |
| Trust                                  | 1         | 1.69%   |
| Syntek                                 | 1         | 1.69%   |
| Suyin                                  | 1         | 1.69%   |
| Lite-On Technology                     | 1         | 1.69%   |
| Lenovo                                 | 1         | 1.69%   |
| KYE Systems (Mouse Systems)            | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 6.78%   |
| Realtek Integrated_Webcam_HD                     | 3         | 5.08%   |
| Realtek USB Camera                               | 2         | 3.39%   |
| Realtek Lenovo EasyCamera                        | 2         | 3.39%   |
| IMC Networks Realtek PC Camera                   | 2         | 3.39%   |
| IMC Networks Integrated Camera                   | 2         | 3.39%   |
| Genesys Logic Digital Microscope                 | 2         | 3.39%   |
| Chicony HD WebCam (Acer)                         | 2         | 3.39%   |
| Bison Integrated Camera                          | 2         | 3.39%   |
| ALi Gateway Webcam                               | 2         | 3.39%   |
| Trust Trust QHD Webcam                           | 1         | 1.69%   |
| Syntek EasyCamera                                | 1         | 1.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 1.69%   |
| Sunplus Integrated Camera                        | 1         | 1.69%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 1.69%   |
| Sunplus Aukey-PC-LM1E Camera                     | 1         | 1.69%   |
| Sunplus 1.3M HD WebCam                           | 1         | 1.69%   |
| Silicon Motion Realtek USB 2.0 PC Camera         | 1         | 1.69%   |
| Silicon Motion HP Webcam-50                      | 1         | 1.69%   |
| Microdia Integrated_Webcam_HD                    | 1         | 1.69%   |
| Microdia ASUS USB 2.0 Webcam                     | 1         | 1.69%   |
| Logitech Webcam C310                             | 1         | 1.69%   |
| Logitech C505 HD Webcam                          | 1         | 1.69%   |
| Lite-On HP TrueVision HD Camera                  | 1         | 1.69%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 1.69%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1         | 1.69%   |
| IMC Networks UVC VGA Webcam                      | 1         | 1.69%   |
| IMC Networks USB 2.0 UVC HD Webcam               | 1         | 1.69%   |
| IMC Networks Realtek DMFT RGB                    | 1         | 1.69%   |
| IMC Networks Integrated Webcam                   | 1         | 1.69%   |
| Chicony WebCam                                   | 1         | 1.69%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 1.69%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 1.69%   |
| Chicony Thinkpad T430 camera                     | 1         | 1.69%   |
| Chicony Integrated Camera [ThinkPad]             | 1         | 1.69%   |
| Chicony HP TrueVision HD Camera                  | 1         | 1.69%   |
| Chicony HD WebCam (Asus N-series)                | 1         | 1.69%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 1         | 1.69%   |
| Chicony 1.3M Webcam                              | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 30%     |
| AuthenTec             | 3         | 30%     |
| Synaptics             | 2         | 20%     |
| Upek                  | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                      | 2         | 20%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics UWP WBDI Device                              | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 10%     |
| Elan Fingerprint Sensor                                | 1         | 10%     |
| AuthenTec AES2810                                      | 1         | 10%     |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 38.26%  |
| 0     | 79        | 34.35%  |
| 2     | 35        | 15.22%  |
| 3     | 24        | 10.43%  |
| 4     | 4         | 1.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 116       | 51.33%  |
| Net/wireless             | 27        | 11.95%  |
| Card reader              | 24        | 10.62%  |
| Bluetooth                | 24        | 10.62%  |
| Firewire controller      | 12        | 5.31%   |
| Fingerprint reader       | 10        | 4.42%   |
| Graphics card            | 5         | 2.21%   |
| Network                  | 4         | 1.77%   |
| Storage                  | 1         | 0.44%   |
| Sound                    | 1         | 0.44%   |
| Modem                    | 1         | 0.44%   |
| Dvb card                 | 1         | 0.44%   |

