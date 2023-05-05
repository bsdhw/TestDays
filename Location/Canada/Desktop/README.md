BSD in Canada - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

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

Total: 396

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [73f9fac4f8](https://bsd-hardware.info/?probe=73f9fac4f8) | May 01, 2023 |
| iBASE         | Mi956                       | [e2c1e52a68](https://bsd-hardware.info/?probe=e2c1e52a68) | Apr 29, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8acf41eb6b](https://bsd-hardware.info/?probe=8acf41eb6b) | Apr 28, 2023 |
| iBASE         | Mi956                       | [cb08976732](https://bsd-hardware.info/?probe=cb08976732) | Apr 27, 2023 |
| Intel         | CRESCENTBAY                 | [b32c8cbec8](https://bsd-hardware.info/?probe=b32c8cbec8) | Apr 27, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [8476daf227](https://bsd-hardware.info/?probe=8476daf227) | Apr 27, 2023 |
| Techvision    | TVI7309X B0                 | [dcacaf8c50](https://bsd-hardware.info/?probe=dcacaf8c50) | Apr 26, 2023 |
| HP            | 1998                        | [41b5bbe52c](https://bsd-hardware.info/?probe=41b5bbe52c) | Apr 26, 2023 |
| Protectli     | FW4B                        | [111e2f7b3b](https://bsd-hardware.info/?probe=111e2f7b3b) | Apr 25, 2023 |
| Unknown       | Unknown                     | [389267d68d](https://bsd-hardware.info/?probe=389267d68d) | Apr 24, 2023 |
| Lenovo        | ThinkCentre M57p 6073ATU    | [b1e7583e6b](https://bsd-hardware.info/?probe=b1e7583e6b) | Apr 24, 2023 |
| Dell          | 04Y8V0 A02                  | [24379ebf10](https://bsd-hardware.info/?probe=24379ebf10) | Apr 20, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| iBASE         | Mi956                       | [0d4d63b29b](https://bsd-hardware.info/?probe=0d4d63b29b) | Apr 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| Protectli     | FW4B Ver                    | [d2f19cb660](https://bsd-hardware.info/?probe=d2f19cb660) | Apr 13, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| AMI           | Cherry Trail CR             | [ce3072c27a](https://bsd-hardware.info/?probe=ce3072c27a) | Apr 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | [9418e51f7e](https://bsd-hardware.info/?probe=9418e51f7e) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [3bb60897ff](https://bsd-hardware.info/?probe=3bb60897ff) | Apr 01, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b86ffef220](https://bsd-hardware.info/?probe=b86ffef220) | Mar 28, 2023 |
| Acer          | WG43M                       | [c8f2a03a08](https://bsd-hardware.info/?probe=c8f2a03a08) | Mar 27, 2023 |
| Acer          | WG43M                       | [5e154dc7cf](https://bsd-hardware.info/?probe=5e154dc7cf) | Mar 26, 2023 |
| MSI           | PRO B660-A DDR4             | [735a5cc6a2](https://bsd-hardware.info/?probe=735a5cc6a2) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Unknown       | Unknown                     | [55c708e91a](https://bsd-hardware.info/?probe=55c708e91a) | Mar 24, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Unknown       | Unknown                     | [898095b140](https://bsd-hardware.info/?probe=898095b140) | Mar 09, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | [6a15f7d4a1](https://bsd-hardware.info/?probe=6a15f7d4a1) | Mar 09, 2023 |
| Arctic Wol... | AWN101                      | [e0f187e449](https://bsd-hardware.info/?probe=e0f187e449) | Mar 01, 2023 |
| Dell          | 0D24M8 A01                  | [22a1b812f8](https://bsd-hardware.info/?probe=22a1b812f8) | Mar 01, 2023 |
| Lenovo        | 3098 0B98401 PRO            | [40d63fc1f7](https://bsd-hardware.info/?probe=40d63fc1f7) | Feb 27, 2023 |
| Dell          | 01TKCC A01                  | [42da900d88](https://bsd-hardware.info/?probe=42da900d88) | Feb 26, 2023 |
| Lenovo        | 30D9 No DPK                 | [c3864d9d51](https://bsd-hardware.info/?probe=c3864d9d51) | Feb 26, 2023 |
| AZW           | U59                         | [a4e906c608](https://bsd-hardware.info/?probe=a4e906c608) | Feb 26, 2023 |
| Unknown       | Unknown                     | [d690aee80e](https://bsd-hardware.info/?probe=d690aee80e) | Feb 26, 2023 |
| AZW           | U59                         | [4dad05a05a](https://bsd-hardware.info/?probe=4dad05a05a) | Feb 24, 2023 |
| AZW           | U59                         | [638aa3ff8e](https://bsd-hardware.info/?probe=638aa3ff8e) | Feb 24, 2023 |
| Dell          | 0HHV7N A00                  | [50f39ca7e0](https://bsd-hardware.info/?probe=50f39ca7e0) | Feb 20, 2023 |
| Apple         | PowerMac3,6                 | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Dell          | 0HHV7N A00                  | [fd90fc5154](https://bsd-hardware.info/?probe=fd90fc5154) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f3c3e6ecb5](https://bsd-hardware.info/?probe=f3c3e6ecb5) | Feb 16, 2023 |
| MiTAC         | UltraPoint                  | [00e52df710](https://bsd-hardware.info/?probe=00e52df710) | Feb 15, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [f69bff2d41](https://bsd-hardware.info/?probe=f69bff2d41) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | [c9c53f2141](https://bsd-hardware.info/?probe=c9c53f2141) | Feb 12, 2023 |
| iBASE         | Mi956                       | [86d20c1bc0](https://bsd-hardware.info/?probe=86d20c1bc0) | Feb 10, 2023 |
| Unknown       | Unknown                     | [3f0d4c3ced](https://bsd-hardware.info/?probe=3f0d4c3ced) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0587338e57](https://bsd-hardware.info/?probe=0587338e57) | Feb 08, 2023 |
| Dell          | 0F3KHR A02                  | [98c9324352](https://bsd-hardware.info/?probe=98c9324352) | Feb 05, 2023 |
| Supermicro    | X9SCL/X9SCM                 | [1022faa668](https://bsd-hardware.info/?probe=1022faa668) | Feb 01, 2023 |
| Dell          | 0J3C2F A01                  | [93a87b6106](https://bsd-hardware.info/?probe=93a87b6106) | Jan 30, 2023 |
| Unknown       | Unknown                     | [b8efd7453b](https://bsd-hardware.info/?probe=b8efd7453b) | Jan 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | [e00d33f978](https://bsd-hardware.info/?probe=e00d33f978) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | [cde064f460](https://bsd-hardware.info/?probe=cde064f460) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| Unknown       | Unknown                     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| HP            | 83F2                        | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| HP            | 83F2                        | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | Unknown                     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Unknown       | Unknown                     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| Unknown       | Unknown                     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| Unknown       | Unknown                     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Dell          | 0WR7PY A03                  | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| Gigabyte      | MBHM87P-00                  | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| HP            | 1998                        | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| ASRock        | N3710-NUC IPC               | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Protectli     | FW4B Ver                    | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| Unknown       | Unknown                     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| PC Engines    | APU                         | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| HP            | 1495                        | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| HP            | 1495                        | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| HP            | 1495                        | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| HP            | 3397                        | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Protectli     | FW4B Ver                    | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Protectli     | FW4B Ver                    | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Unknown       | Unknown                     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| Lenovo        | 30D9 No DPK                 | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| ASUSTek       | P8H77-I                     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| Datto         | SSD                         | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Protectli     | FW4B Ver                    | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| Dell          | 04YP6J A01                  | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| Techvision    | TVI7309X B0                 | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| CncTion       | N5105-4L B0                 | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| Gigabyte      | MBHM87P-00                  | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| Dell          | 04Y8V0 A02                  | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| Dell          | 0XHGV1 A00                  | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Lenovo        | SHARKBAY NOK                | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AZW           | Green G1                    | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| Datto         | SSD                         | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| Protectli     | FW6                         | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| HP            | 82A2                        | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| ASUSTek       | M5A97 PLUS                  | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| Protectli     | FW4B Ver                    | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Gigabyte      | F2A68HM-H                   | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | H81M-E                      | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| HP            | 1998                        | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Unknown       | Unknown                     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Unknown       | Unknown                     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Alienware     | 049PDM A00                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| PC Engines    | APU                         | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| Unknown       | Unknown                     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| Intel         | SHARKBAY                    | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| MSI           | MS-7388                     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| Dell          | 0XHGV1 A00                  | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| ASRock        | J4105M                      | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| ASRock        | J3455B-ITX                  | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| PC Engines    | APU2                        | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Unknown       | Unknown                     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | Z170-P                      | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Quanta        | 2AC7 011                    | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| AMI           | Cherry Trail CR             | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| Dell          | 051FJ8 A01                  | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| ASUSTek       | M5A97 PLUS                  | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| ASUSTek       | M5A97 PLUS                  | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| HP            | 843B                        | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Intel         | CRESCENTBAY                 | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Acer          | Aspire TC-780               | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| AMI           | Cherry Trail CR             | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| ASRock        | J3455B-ITX                  | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| PC Engines    | apu4                        | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| Gigabyte      | H97-D3H-CF                  | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Shuttle       | FS110                       | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| Intel         | Q3XXG4-P V1.0               | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| HP            | 805D                        | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 1998                        | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| Protectli     | FW4B Ver                    | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Unknown       | Unknown                     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 18E7                        | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| HP            | 2AF7                        | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| Dell          | 0TTDMJ A00                  | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Gigabyte      | D525TUD                     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Dell          | 0M9KCM A00                  | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ASRock        | B450M Pro4                  | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Supermicro    | A2SDi-TP8F                  | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Protectli     | FW6                         | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| Gigabyte      | MRZNVMS-00                  | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| ASRock        | Z270M-ITX/ac                | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| HP            | 0AECh D                     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| PC Engines    | apu4                        | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| HP            | 82B4                        | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| PC Engines    | APU2                        | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8STi                       | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Supermicro    | X7SLA                       | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| MSI           | X58 Pro-E                   | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | 212B                        | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| ADI Engine... | RCC-VE                      | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| IBM           | Board                       | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| MSI           | MS-7250                     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | 3031h                       | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| ASUSTek       | Z170-P                      | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 22.7.10  | 14       | 4.29%   |
| OPNsense 23.1.6   | 9        | 2.76%   |
| OPNsense 23.1.1   | 9        | 2.76%   |
| OPNsense 22.1.10  | 9        | 2.76%   |
| helloSystem 0.7.0 | 9        | 2.76%   |
| OPNsense 22.7.8   | 8        | 2.45%   |
| OPNsense 22.1.8   | 8        | 2.45%   |
| OPNsense 21.1.4   | 8        | 2.45%   |
| helloSystem 0.5.0 | 8        | 2.45%   |
| OPNsense 23.1     | 7        | 2.15%   |
| OPNsense 22.1.7   | 7        | 2.15%   |
| OPNsense 22.1     | 7        | 2.15%   |
| OPNsense 21.7     | 7        | 2.15%   |
| OPNsense 21.1.3   | 7        | 2.15%   |
| OPNsense 21.1     | 7        | 2.15%   |
| OPNsense 22.7.4   | 6        | 1.84%   |
| OPNsense 22.1.6   | 6        | 1.84%   |
| OPNsense 21.1.5   | 6        | 1.84%   |
| OPNsense 20.7.8   | 6        | 1.84%   |
| FreeBSD 13.1-p5   | 6        | 1.84%   |
| OPNsense 22.7.9   | 5        | 1.53%   |
| OPNsense 22.7.11  | 5        | 1.53%   |
| OPNsense 22.7     | 5        | 1.53%   |
| OPNsense 21.7.7   | 5        | 1.53%   |
| OPNsense 21.7.3   | 5        | 1.53%   |
| OPNsense 21.7.1   | 5        | 1.53%   |
| OPNsense 21.1.6   | 5        | 1.53%   |
| OPNsense 21.1.1   | 5        | 1.53%   |
| helloSystem 0.8.1 | 5        | 1.53%   |
| FreeBSD 13.1      | 5        | 1.53%   |
| FreeBSD 12.2      | 5        | 1.53%   |
| OPNsense 23.1.5   | 4        | 1.23%   |
| OPNsense 23.1.4   | 4        | 1.23%   |
| OPNsense 22.7.7   | 4        | 1.23%   |
| OPNsense 22.1.3   | 4        | 1.23%   |
| OPNsense 21.7.8   | 4        | 1.23%   |
| OPNsense 21.7.4   | 4        | 1.23%   |
| OPNsense 22.7.6   | 3        | 0.92%   |
| OPNsense 22.7.3   | 3        | 0.92%   |
| OPNsense 22.7.2   | 3        | 0.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 163      | 65.73%  |
| FreeBSD     | 46       | 18.55%  |
| helloSystem | 25       | 10.08%  |
| OpenBSD     | 6        | 2.42%   |
| GhostBSD    | 3        | 1.21%   |
| FreeNAS     | 3        | 1.21%   |
| TrueNAS     | 1        | 0.4%    |
| pfSense     | 1        | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 243      | 99.18%  |
| macppc | 1        | 0.41%   |
| i386   | 1        | 0.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 187      | 75.1%   |
| helloDesktop | 29       | 11.65%  |
| KDE5         | 9        | 3.61%   |
| XFCE         | 8        | 3.21%   |
| MATE         | 6        | 2.41%   |
| GNOME        | 3        | 1.2%    |
| Cinnamon     | 2        | 0.8%    |
| X-Cinnamon   | 1        | 0.4%    |
| Window Maker | 1        | 0.4%    |
| Openbox      | 1        | 0.4%    |
| LXDE         | 1        | 0.4%    |
| DWM          | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 188      | 76.73%  |
| X11     | 56       | 22.86%  |
| Wayland | 1        | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 198      | 79.52%  |
| SLiM    | 29       | 11.65%  |
| SDDM    | 12       | 4.82%   |
| LightDM | 4        | 1.61%   |
| XDM     | 3        | 1.2%    |
| GDM     | 2        | 0.8%    |
| Ly      | 1        | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 179      | 72.47%  |
| en_US   | 38       | 15.38%  |
| C       | 21       | 8.5%    |
| en_CA   | 5        | 2.02%   |
| fr_FR   | 2        | 0.81%   |
| fr      | 1        | 0.4%    |
| en      | 1        | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 208      | 83.53%  |
| BIOS | 41       | 16.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 131      | 51.57%  |
| Zfs    | 106      | 41.73%  |
| Cd9660 | 11       | 4.33%   |
| Ffs    | 6        | 2.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 226      | 92.24%  |
| MBR     | 17       | 6.94%   |
| Unknown | 2        | 0.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Hewlett-Packard            | 32       | 13.06%  |
| ASUSTek Computer           | 30       | 12.24%  |
| Dell                       | 28       | 11.43%  |
| Lenovo                     | 20       | 8.16%   |
| Unknown                    | 20       | 8.16%   |
| Protectli                  | 16       | 6.53%   |
| Intel                      | 14       | 5.71%   |
| Gigabyte Technology        | 13       | 5.31%   |
| ASRock                     | 12       | 4.9%    |
| Supermicro                 | 11       | 4.49%   |
| MSI                        | 10       | 4.08%   |
| Techvision                 | 5        | 2.04%   |
| PC Engines                 | 5        | 2.04%   |
| Acer                       | 5        | 2.04%   |
| AZW                        | 3        | 1.22%   |
| Apple                      | 2        | 0.82%   |
| Yanling                    | 1        | 0.41%   |
| Shuttle                    | 1        | 0.41%   |
| ShenZhen MinWin Technology | 1        | 0.41%   |
| SeeedStudio                | 1        | 0.41%   |
| Quanta                     | 1        | 0.41%   |
| Pegatron                   | 1        | 0.41%   |
| MiTAC                      | 1        | 0.41%   |
| IBM                        | 1        | 0.41%   |
| iBASE                      | 1        | 0.41%   |
| HARDKERNEL                 | 1        | 0.41%   |
| Datto                      | 1        | 0.41%   |
| CncTion                    | 1        | 0.41%   |
| Cisco                      | 1        | 0.41%   |
| Biostar                    | 1        | 0.41%   |
| ASRockRack                 | 1        | 0.41%   |
| Arctic Wolf Networks       | 1        | 0.41%   |
| AMI                        | 1        | 0.41%   |
| Alienware                  | 1        | 0.41%   |
| ADI Engineering            | 1        | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 20       | 8.16%   |
| Protectli FW4B                     | 9        | 3.67%   |
| Techvision TVI7309X                | 5        | 2.04%   |
| Protectli FW6                      | 5        | 2.04%   |
| Intel Q3XXG4-P V1.0                | 5        | 2.04%   |
| Intel NDISB533                     | 4        | 1.63%   |
| HP EliteDesk 800 G1 SFF            | 4        | 1.63%   |
| Dell OptiPlex 9010                 | 4        | 1.63%   |
| HP Z440 Workstation                | 3        | 1.22%   |
| HP Compaq 6200 Pro MT PC           | 3        | 1.22%   |
| Dell OptiPlex 7010                 | 3        | 1.22%   |
| ASUS All Series                    | 3        | 1.22%   |
| Supermicro X8STi                   | 2        | 0.82%   |
| PC Engines apu4                    | 2        | 0.82%   |
| PC Engines APU2                    | 2        | 0.82%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 0.82%   |
| Intel CRESCENTBAY                  | 2        | 0.82%   |
| HP Compaq Elite 8300 SFF           | 2        | 0.82%   |
| HP Compaq 8200 Elite SFF PC        | 2        | 0.82%   |
| Dell Precision WorkStation T3500   | 2        | 0.82%   |
| Dell Precision Tower 5810          | 2        | 0.82%   |
| Dell OptiPlex 7050                 | 2        | 0.82%   |
| Dell OptiPlex 7020                 | 2        | 0.82%   |
| Dell OptiPlex 3020                 | 2        | 0.82%   |
| Dell G5 5090                       | 2        | 0.82%   |
| AZW U59                            | 2        | 0.82%   |
| ASUS P8H77-I                       | 2        | 0.82%   |
| ASUS M5A97 PLUS                    | 2        | 0.82%   |
| ASRock H110M-DGS R3.0              | 2        | 0.82%   |
| ASRock B450M Pro4                  | 2        | 0.82%   |
| Yanling YL-KBR6L                   | 1        | 0.41%   |
| Supermicro X9SCL/X9SCM             | 1        | 0.41%   |
| Supermicro X9DR3-F                 | 1        | 0.41%   |
| Supermicro X7SPA-HF                | 1        | 0.41%   |
| Supermicro X7SLA                   | 1        | 0.41%   |
| Supermicro SYS-E300-9A             | 1        | 0.41%   |
| Supermicro SYS-5019S-ML            | 1        | 0.41%   |
| Supermicro SYS-5019D-FN8TP         | 1        | 0.41%   |
| Supermicro SYS-5019A-FTN4          | 1        | 0.41%   |
| Supermicro AS -5019D-FTN4          | 1        | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell OptiPlex              | 21       | 8.57%   |
| Unknown                    | 20       | 8.16%   |
| Lenovo ThinkCentre         | 18       | 7.35%   |
| Protectli FW4B             | 9        | 3.67%   |
| HP Compaq                  | 8        | 3.27%   |
| ASUS PRIME                 | 8        | 3.27%   |
| HP ProDesk                 | 7        | 2.86%   |
| HP EliteDesk               | 6        | 2.45%   |
| Techvision TVI7309X        | 5        | 2.04%   |
| Protectli FW6              | 5        | 2.04%   |
| Intel Q3XXG4-P             | 5        | 2.04%   |
| Dell Precision             | 5        | 2.04%   |
| Acer Aspire                | 5        | 2.04%   |
| Intel NDISB533             | 4        | 1.63%   |
| ASUS ROG                   | 4        | 1.63%   |
| HP Z440                    | 3        | 1.22%   |
| ASUS All                   | 3        | 1.22%   |
| ASRock B450M               | 3        | 1.22%   |
| Supermicro X8STi           | 2        | 0.82%   |
| PC Engines apu4            | 2        | 0.82%   |
| PC Engines APU2            | 2        | 0.82%   |
| Intel CRESCENTBAY          | 2        | 0.82%   |
| HP t620                    | 2        | 0.82%   |
| Dell G5                    | 2        | 0.82%   |
| AZW U59                    | 2        | 0.82%   |
| ASUS TUF                   | 2        | 0.82%   |
| ASUS P8H77-I               | 2        | 0.82%   |
| ASUS M5A97                 | 2        | 0.82%   |
| ASRock H110M-DGS           | 2        | 0.82%   |
| Yanling YL-KBR6L           | 1        | 0.41%   |
| Supermicro X9SCL           | 1        | 0.41%   |
| Supermicro X9DR3-F         | 1        | 0.41%   |
| Supermicro X7SPA-HF        | 1        | 0.41%   |
| Supermicro X7SLA           | 1        | 0.41%   |
| Supermicro SYS-E300-9A     | 1        | 0.41%   |
| Supermicro SYS-5019S-ML    | 1        | 0.41%   |
| Supermicro SYS-5019D-FN8TP | 1        | 0.41%   |
| Supermicro SYS-5019A-FTN4  | 1        | 0.41%   |
| Supermicro AS              | 1        | 0.41%   |
| Shuttle DH110              | 1        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 37       | 15.1%   |
| 2022    | 26       | 10.61%  |
| 2020    | 25       | 10.2%   |
| 2014    | 25       | 10.2%   |
| 2019    | 17       | 6.94%   |
| 2016    | 17       | 6.94%   |
| 2013    | 17       | 6.94%   |
| 2011    | 14       | 5.71%   |
| 2021    | 12       | 4.9%    |
| 2012    | 11       | 4.49%   |
| 2010    | 11       | 4.49%   |
| 2017    | 8        | 3.27%   |
| 2015    | 8        | 3.27%   |
| 2009    | 6        | 2.45%   |
| 2008    | 5        | 2.04%   |
| 2023    | 2        | 0.82%   |
| Unknown | 2        | 0.82%   |
| 2007    | 1        | 0.41%   |
| 2006    | 1        | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 245      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 237      | 96.73%  |
| Yes  | 8        | 3.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 98       | 38.74%  |
| 16.01-24.0  | 57       | 22.53%  |
| 4.01-8.0    | 42       | 16.6%   |
| 32.01-64.0  | 28       | 11.07%  |
| 64.01-256.0 | 11       | 4.35%   |
| 2.01-3.0    | 6        | 2.37%   |
| 24.01-32.0  | 5        | 1.98%   |
| 3.01-4.0    | 3        | 1.19%   |
| 1.01-2.0    | 2        | 0.79%   |
| 0.51-1.0    | 1        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 124      | 49.21%  |
| 0.51-1.0    | 76       | 30.16%  |
| 1.01-2.0    | 36       | 14.29%  |
| 4.01-8.0    | 4        | 1.59%   |
| 3.01-4.0    | 4        | 1.59%   |
| 2.01-3.0    | 4        | 1.59%   |
| 32.01-64.0  | 1        | 0.4%    |
| 64.01-256.0 | 1        | 0.4%    |
| 8.01-16.0   | 1        | 0.4%    |
| 0           | 1        | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 170      | 68.27%  |
| 2      | 36       | 14.46%  |
| 3      | 17       | 6.83%   |
| 0      | 15       | 6.02%   |
| 4      | 7        | 2.81%   |
| 13     | 1        | 0.4%    |
| 10     | 1        | 0.4%    |
| 7      | 1        | 0.4%    |
| 5      | 1        | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 76.31%  |
| Yes       | 59       | 23.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 243      | 98.78%  |
| No        | 3        | 1.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 201      | 81.05%  |
| Yes       | 47       | 18.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 214      | 87.35%  |
| Yes       | 31       | 12.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 245      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 23       | 8.81%   |
| Montreal                   | 20       | 7.66%   |
| Ottawa                     | 14       | 5.36%   |
| Calgary                    | 14       | 5.36%   |
| Edmonton                   | 12       | 4.6%    |
| Victoria                   | 9        | 3.45%   |
| Winnipeg                   | 8        | 3.07%   |
| Kitchener                  | 8        | 3.07%   |
| Vancouver                  | 6        | 2.3%    |
| Surrey                     | 6        | 2.3%    |
| Brampton                   | 6        | 2.3%    |
| Regina                     | 5        | 1.92%   |
| London                     | 4        | 1.53%   |
| Windsor                    | 3        | 1.15%   |
| St. Jean Baptiste          | 3        | 1.15%   |
| St. Albert                 | 3        | 1.15%   |
| Saskatoon                  | 3        | 1.15%   |
| Sarnia                     | 3        | 1.15%   |
| Québec                    | 3        | 1.15%   |
| Nanaimo                    | 3        | 1.15%   |
| Moncton                    | 3        | 1.15%   |
| Laval                      | 3        | 1.15%   |
| Cambridge                  | 3        | 1.15%   |
| Burlington                 | 3        | 1.15%   |
| West Kelowna               | 2        | 0.77%   |
| Terrebonne                 | 2        | 0.77%   |
| Sainte-Julie               | 2        | 0.77%   |
| Saint-Bruno-de-Montarville | 2        | 0.77%   |
| Richmond                   | 2        | 0.77%   |
| Peterborough               | 2        | 0.77%   |
| Oakville                   | 2        | 0.77%   |
| Mississauga                | 2        | 0.77%   |
| Lamont                     | 2        | 0.77%   |
| Kingston                   | 2        | 0.77%   |
| Kanata                     | 2        | 0.77%   |
| Hamilton                   | 2        | 0.77%   |
| Guelph                     | 2        | 0.77%   |
| Greater Sudbury            | 2        | 0.77%   |
| Cobourg                    | 2        | 0.77%   |
| Burnaby                    | 2        | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 43       | 76     | 14.38%  |
| WDC                 | 42       | 86     | 14.05%  |
| Samsung Electronics | 42       | 61     | 14.05%  |
| Kingston            | 37       | 48     | 12.37%  |
| Crucial             | 14       | 21     | 4.68%   |
| A-DATA Technology   | 12       | 21     | 4.01%   |
| Intel               | 11       | 15     | 3.68%   |
| SanDisk             | 9        | 11     | 3.01%   |
| Toshiba             | 7        | 11     | 2.34%   |
| SPCC                | 6        | 6      | 2.01%   |
| Patriot             | 5        | 6      | 1.67%   |
| Hitachi             | 5        | 5      | 1.67%   |
| OCZ                 | 4        | 5      | 1.34%   |
| Mushkin             | 4        | 4      | 1.34%   |
| Micron Technology   | 4        | 7      | 1.34%   |
| Dogfish             | 4        | 7      | 1.34%   |
| BIWIN               | 4        | 5      | 1.34%   |
| SK hynix            | 3        | 5      | 1%      |
| PNY                 | 3        | 4      | 1%      |
| Hoodisk             | 3        | 4      | 1%      |
| HGST                | 3        | 5      | 1%      |
| Hewlett-Packard     | 3        | 3      | 1%      |
| VisionTek           | 2        | 6      | 0.67%   |
| Transcend           | 2        | 3      | 0.67%   |
| Timetec             | 2        | 2      | 0.67%   |
| Protectli           | 2        | 3      | 0.67%   |
| Phison              | 2        | 3      | 0.67%   |
| NVMe                | 2        | 2      | 0.67%   |
| FORESEE             | 2        | 3      | 0.67%   |
| Corsair             | 2        | 4      | 0.67%   |
| China               | 2        | 3      | 0.67%   |
| walram              | 1        | 1      | 0.33%   |
| Team                | 1        | 2      | 0.33%   |
| Silicon Motion      | 1        | 1      | 0.33%   |
| SATADOM             | 1        | 2      | 0.33%   |
| OPENBSD             | 1        | 1      | 0.33%   |
| Netac               | 1        | 1      | 0.33%   |
| Lexar               | 1        | 1      | 0.33%   |
| Innodisk            | 1        | 1      | 0.33%   |
| HPT                 | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 11       | 3.46%   |
| Kingston SA400S37120G 120GB     | 8        | 2.52%   |
| Seagate ST1000DM010-2EP102 1TB  | 6        | 1.89%   |
| Seagate ST500DM002-1BD142 500GB | 5        | 1.57%   |
| Samsung SSD 850 EVO 250GB       | 5        | 1.57%   |
| Seagate ST2000DM008-2FR102 2TB  | 4        | 1.26%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.26%   |
| BIWIN SSD 128GB                 | 4        | 1.26%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 0.94%   |
| Toshiba DT01ACA100 1TB          | 3        | 0.94%   |
| Seagate ST3500413AS 500GB       | 3        | 0.94%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3        | 0.94%   |
| Samsung SSD 970 EVO Plus 1TB    | 3        | 0.94%   |
| Samsung SSD 840 EVO 120GB       | 3        | 0.94%   |
| Kingston SUV500MS120G 120GB     | 3        | 0.94%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.94%   |
| WDC WD6400AAKS-22A7B2 640GB     | 2        | 0.63%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 0.63%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2        | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2        | 0.63%   |
| WDC PC SN520 NVMe 256GB         | 2        | 0.63%   |
| VisionTek mSATA 120GB           | 2        | 0.63%   |
| Transcend TS256GMSA230S 256GB   | 2        | 0.63%   |
| Toshiba MQ01ABD075 752GB        | 2        | 0.63%   |
| SPCC Solid State Disk 256GB     | 2        | 0.63%   |
| SPCC Solid State Disk 128GB     | 2        | 0.63%   |
| Seagate ST4000VN008-2DR166 4TB  | 2        | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.63%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 2        | 0.63%   |
| Samsung SSD 980 PRO 1TB         | 2        | 0.63%   |
| Samsung SSD 980 1TB             | 2        | 0.63%   |
| Samsung SSD 870 EVO 500GB       | 2        | 0.63%   |
| Samsung SSD 850 PRO 256GB       | 2        | 0.63%   |
| Samsung SSD 850 EVO mSATA 250GB | 2        | 0.63%   |
| Samsung SSD 840 EVO 250GB       | 2        | 0.63%   |
| Protectli 64GB mSATA            | 2        | 0.63%   |
| PNY CS1311 120GB SSD            | 2        | 0.63%   |
| Mushkin MKNSSDEC60GB 64GB       | 2        | 0.63%   |
| Intel SSDSC2BB080G4 80GB        | 2        | 0.63%   |
| Crucial CT1000MX500SSD1 1TB     | 2        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 41       | 74     | 46.07%  |
| WDC     | 31       | 70     | 34.83%  |
| Toshiba | 6        | 8      | 6.74%   |
| Hitachi | 5        | 5      | 5.62%   |
| HGST    | 3        | 5      | 3.37%   |
| OPENBSD | 1        | 1      | 1.12%   |
| HPT     | 1        | 1      | 1.12%   |
| Fujitsu | 1        | 1      | 1.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 49     | 18.99%  |
| Kingston            | 34       | 41     | 18.99%  |
| Crucial             | 13       | 18     | 7.26%   |
| A-DATA Technology   | 12       | 21     | 6.7%    |
| Intel               | 10       | 14     | 5.59%   |
| SanDisk             | 9        | 11     | 5.03%   |
| WDC                 | 7        | 9      | 3.91%   |
| SPCC                | 5        | 5      | 2.79%   |
| Patriot             | 4        | 5      | 2.23%   |
| OCZ                 | 4        | 5      | 2.23%   |
| Mushkin             | 4        | 4      | 2.23%   |
| Dogfish             | 4        | 7      | 2.23%   |
| BIWIN               | 4        | 5      | 2.23%   |
| PNY                 | 3        | 4      | 1.68%   |
| Micron Technology   | 3        | 6      | 1.68%   |
| Hoodisk             | 3        | 4      | 1.68%   |
| VisionTek           | 2        | 6      | 1.12%   |
| Transcend           | 2        | 3      | 1.12%   |
| Seagate             | 2        | 2      | 1.12%   |
| Protectli           | 2        | 3      | 1.12%   |
| FORESEE             | 2        | 3      | 1.12%   |
| Corsair             | 2        | 4      | 1.12%   |
| China               | 2        | 3      | 1.12%   |
| walram              | 1        | 1      | 0.56%   |
| Timetec             | 1        | 1      | 0.56%   |
| SATADOM             | 1        | 2      | 0.56%   |
| Phison              | 1        | 1      | 0.56%   |
| NVMe                | 1        | 1      | 0.56%   |
| Netac               | 1        | 1      | 0.56%   |
| Lexar               | 1        | 1      | 0.56%   |
| Innodisk            | 1        | 1      | 0.56%   |
| HPE                 | 1        | 4      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.56%   |
| EAGET               | 1        | 1      | 0.56%   |
| AVEXIR              | 1        | 2      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 164      | 249    | 61.19%  |
| HDD  | 73       | 165    | 27.24%  |
| NVMe | 31       | 50     | 11.57%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 213      | 414    | 87.3%   |
| NVMe | 31       | 50     | 12.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 179      | 268    | 71.6%   |
| 0.51-1.0   | 36       | 63     | 14.4%   |
| 1.01-2.0   | 16       | 27     | 6.4%    |
| 3.01-4.0   | 8        | 20     | 3.2%    |
| 4.01-10.0  | 5        | 23     | 2%      |
| 2.01-3.0   | 4        | 10     | 1.6%    |
| 10.01-20.0 | 2        | 3      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 109      | 42.08%  |
| 251-500        | 41       | 15.83%  |
| 51-100         | 32       | 12.36%  |
| 1-20           | 26       | 10.04%  |
| 21-50          | 22       | 8.49%   |
| 501-1000       | 17       | 6.56%   |
| 1001-2000      | 6        | 2.32%   |
| More than 3000 | 3        | 1.16%   |
| Unknown        | 3        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 227      | 88.33%  |
| 21-50     | 17       | 6.61%   |
| 51-100    | 5        | 1.95%   |
| Unknown   | 3        | 1.17%   |
| 101-250   | 2        | 0.78%   |
| 1001-2000 | 2        | 0.78%   |
| 501-1000  | 1        | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                | 2        | 6      | 5.13%   |
| VisionTek mSATA 120GB                      | 2        | 6      | 5.13%   |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 5.13%   |
| Seagate ST500DM002-1BD142 500GB            | 2        | 4      | 5.13%   |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 5.13%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 2.56%   |
| WDC WD5003AZEX-00K1GA0 500GB               | 1        | 1      | 2.56%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 2.56%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 2.56%   |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 2.56%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 2      | 2.56%   |
| walram SSD 120G                            | 1        | 1      | 2.56%   |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 2.56%   |
| SPCC Solid State Disk 128GB                | 1        | 1      | 2.56%   |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 2.56%   |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 2.56%   |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 2.56%   |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 2.56%   |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 2.56%   |
| Seagate ST3120026A 120GB                   | 1        | 1      | 2.56%   |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 2.56%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 2.56%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 3      | 2.56%   |
| Mushkin MKNSSDEC512GB                      | 1        | 1      | 2.56%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 2.56%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 2.56%   |
| Intel SSDSC2BB480G4 480GB                  | 1        | 1      | 2.56%   |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 2.56%   |
| Hitachi HTS542520K9A300 200GB              | 1        | 1      | 2.56%   |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB                 | 1        | 2      | 2.56%   |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 2.56%   |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 2.56%   |
| A-DATA Technology SU800 1TB                | 1        | 2      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 28.95%  |
| WDC                 | 8        | 14     | 21.05%  |
| Toshiba             | 3        | 5      | 7.89%   |
| VisionTek           | 2        | 6      | 5.26%   |
| Intel               | 2        | 2      | 5.26%   |
| Hitachi             | 2        | 2      | 5.26%   |
| HGST                | 2        | 3      | 5.26%   |
| walram              | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| Samsung Electronics | 1        | 3      | 2.63%   |
| Mushkin             | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 4      | 2.63%   |
| Kingston            | 1        | 1      | 2.63%   |
| Crucial             | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 2      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 18     | 42.31%  |
| WDC     | 8        | 14     | 30.77%  |
| Toshiba | 3        | 5      | 11.54%  |
| Hitachi | 2        | 2      | 7.69%   |
| HGST    | 2        | 3      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 42     | 65.71%  |
| SSD  | 12       | 22     | 34.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB  | 1        | 1      | 50%     |
| Seagate ST3250310AS 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 208      | 390    | 82.87%  |
| Malfunc  | 34       | 64     | 13.55%  |
| Detected | 7        | 8      | 2.79%   |
| Failed   | 2        | 2      | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 201      | 67.22%  |
| AMD                         | 39       | 13.04%  |
| Samsung Electronics         | 10       | 3.34%   |
| SanDisk                     | 8        | 2.68%   |
| Silicon Motion              | 5        | 1.67%   |
| Nvidia                      | 5        | 1.67%   |
| ASMedia Technology          | 5        | 1.67%   |
| Kingston Technology Company | 4        | 1.34%   |
| SK hynix                    | 3        | 1%      |
| Broadcom / LSI              | 3        | 1%      |
| Silicon Image               | 2        | 0.67%   |
| Micron/Crucial Technology   | 2        | 0.67%   |
| MAXIO Technology (Hangzhou) | 2        | 0.67%   |
| Marvell Technology Group    | 2        | 0.67%   |
| JMicron Technology          | 2        | 0.67%   |
| Chelsio Communications      | 2        | 0.67%   |
| Toshiba                     | 1        | 0.33%   |
| Phison Electronics          | 1        | 0.33%   |
| Micron Technology           | 1        | 0.33%   |
| HighPoint Technologies      | 1        | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29       | 8.31%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 18       | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 17       | 4.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14       | 4.01%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 14       | 4.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13       | 3.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10       | 2.87%   |
| AMD 400 Series Chipset SATA Controller                                           | 10       | 2.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9        | 2.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9        | 2.58%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8        | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 2.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 2.01%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 7        | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5        | 1.43%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 5        | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 5        | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4        | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4        | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4        | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.15%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 1.15%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 0.86%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3        | 0.86%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 0.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3        | 0.86%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 0.86%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 0.57%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2        | 0.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2        | 0.57%   |
| Samsung NVMe SSD Controller 980                                                  | 2        | 0.57%   |
| Nvidia MCP61 SATA Controller                                                     | 2        | 0.57%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 215      | 71.91%  |
| NVMe | 34       | 11.37%  |
| IDE  | 34       | 11.37%  |
| RAID | 8        | 2.68%   |
| SAS  | 4        | 1.34%   |
| SCSI | 4        | 1.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 204      | 82.26%  |
| AMD     | 43       | 17.34%  |
| Unknown | 1        | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz        | 12       | 4.76%   |
| Intel Celeron CPU J3160 @ 1.60GHz    | 9        | 3.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz     | 8        | 3.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz     | 7        | 2.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz     | 6        | 2.38%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 6        | 2.38%   |
| Intel Celeron J4125 CPU @ 2.00GHz    | 6        | 2.38%   |
| Intel Core i5-4570TE CPU @ 2.70GHz   | 4        | 1.59%   |
| Intel Core i3-2100 CPU @ 3.10GHz     | 4        | 1.59%   |
| AMD GX-412TC SOC                     | 4        | 1.59%   |
| Intel Xeon                           | 3        | 1.19%   |
| Intel Pentium CPU G4560 @ 3.50GHz    | 3        | 1.19%   |
| Intel Core i7-9700K CPU @ 3.60GHz    | 3        | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 3        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 3        | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz | 3        | 1.19%   |
| AMD Ryzen 5 2600 Six-Core Processor  | 3        | 1.19%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 2        | 0.79%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz  | 2        | 0.79%   |
| Intel Pentium Silver N6005 @ 2.00GHz | 2        | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2        | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz     | 2        | 0.79%   |
| Intel Core i7-4790K CPU @ 4.00GHz    | 2        | 0.79%   |
| Intel Core i5-8400 CPU @ 2.80GHz     | 2        | 0.79%   |
| Intel Core i5-4670 CPU @ 3.40GHz     | 2        | 0.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz     | 2        | 0.79%   |
| Intel Core i5-3470T CPU @ 2.90GHz    | 2        | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 2        | 0.79%   |
| Intel Core i5-2500 CPU @ 3.30GHz     | 2        | 0.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz     | 2        | 0.79%   |
| Intel Core i3-6100T CPU @ 3.20GHz    | 2        | 0.79%   |
| Intel Core i3-4030U CPU @ 1.90GHz    | 2        | 0.79%   |
| Intel Celeron J6413 @ 1.80GHz        | 2        | 0.79%   |
| Intel Celeron J4105 CPU @ 1.50GHz    | 2        | 0.79%   |
| Intel Celeron CPU J3455 @ 1.50GHz    | 2        | 0.79%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 2        | 0.79%   |
| AMD FX-8350 Eight-Core Processor     | 2        | 0.79%   |
| AMD FX-8320E Eight-Core Processor    | 2        | 0.79%   |
| AMD FX-4350 Quad-Core Processor      | 2        | 0.79%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz    | 1        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 67       | 26.69%  |
| Intel Celeron           | 41       | 16.33%  |
| Intel Xeon              | 22       | 8.76%   |
| Intel Core i7           | 21       | 8.37%   |
| Intel Core i3           | 21       | 8.37%   |
| Other                   | 8        | 3.19%   |
| Intel Atom              | 8        | 3.19%   |
| Intel Pentium           | 6        | 2.39%   |
| AMD Ryzen 5             | 6        | 2.39%   |
| AMD GX                  | 6        | 2.39%   |
| AMD FX                  | 6        | 2.39%   |
| Intel Core 2 Duo        | 5        | 1.99%   |
| AMD Ryzen 9             | 4        | 1.59%   |
| Intel Pentium Dual-Core | 3        | 1.2%    |
| Intel Core 2 Quad       | 3        | 1.2%    |
| AMD Ryzen 7             | 3        | 1.2%    |
| AMD Athlon 64 X2        | 3        | 1.2%    |
| Intel Pentium Silver    | 2        | 0.8%    |
| AMD Ryzen 3             | 2        | 0.8%    |
| Intel Pentium 4         | 1        | 0.4%    |
| AMD Ryzen Embedded      | 1        | 0.4%    |
| AMD Ryzen 5 PRO         | 1        | 0.4%    |
| AMD Phenom II X6        | 1        | 0.4%    |
| AMD Phenom              | 1        | 0.4%    |
| AMD G                   | 1        | 0.4%    |
| AMD EPYC                | 1        | 0.4%    |
| AMD E                   | 1        | 0.4%    |
| AMD Athlon II X2        | 1        | 0.4%    |
| AMD Athlon Dual Core    | 1        | 0.4%    |
| AMD Athlon              | 1        | 0.4%    |
| AMD A6                  | 1        | 0.4%    |
| AMD A4                  | 1        | 0.4%    |
| AMD A10                 | 1        | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 136      | 54.62%  |
| 2       | 57       | 22.89%  |
| 6       | 16       | 6.43%   |
| 8       | 14       | 5.62%   |
| 12      | 8        | 3.21%   |
| 32      | 4        | 1.61%   |
| 16      | 4        | 1.61%   |
| 10      | 3        | 1.2%    |
| Unknown | 3        | 1.2%    |
| 24      | 2        | 0.8%    |
| 11      | 1        | 0.4%    |
| 3       | 1        | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 241      | 98.37%  |
| 2       | 2        | 0.82%   |
| Unknown | 2        | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 163      | 66.26%  |
| 2       | 80       | 32.52%  |
| Unknown | 3        | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 42       | 16.67%  |
| KabyLake      | 25       | 9.92%   |
| Unknown       | 24       | 9.52%   |
| IvyBridge     | 23       | 9.13%   |
| Skylake       | 14       | 5.56%   |
| Silvermont    | 14       | 5.56%   |
| SandyBridge   | 14       | 5.56%   |
| Penryn        | 11       | 4.37%   |
| Goldmont plus | 9        | 3.57%   |
| Piledriver    | 8        | 3.17%   |
| Goldmont      | 8        | 3.17%   |
| Zen+          | 7        | 2.78%   |
| Westmere      | 6        | 2.38%   |
| Broadwell     | 6        | 2.38%   |
| Zen 3         | 4        | 1.59%   |
| Zen           | 4        | 1.59%   |
| Puma          | 4        | 1.59%   |
| K8 Hammer     | 4        | 1.59%   |
| K10           | 4        | 1.59%   |
| Jaguar        | 4        | 1.59%   |
| CometLake     | 4        | 1.59%   |
| Nehalem       | 3        | 1.19%   |
| Bonnell       | 3        | 1.19%   |
| Zen 2         | 2        | 0.79%   |
| Bobcat        | 2        | 0.79%   |
| TigerLake     | 1        | 0.4%    |
| NetBurst      | 1        | 0.4%    |
| Core          | 1        | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 161      | 65.71%  |
| Nvidia                     | 38       | 15.51%  |
| AMD                        | 34       | 13.88%  |
| ASPEED Technology          | 7        | 2.86%   |
| Matrox Electronics Systems | 5        | 2.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28       | 11.24%  |
| Intel JasperLake [UHD Graphics]                                                          | 15       | 6.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12       | 4.82%   |
| Intel HD Graphics 530                                                                    | 11       | 4.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11       | 4.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 4.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9        | 3.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8        | 3.21%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7        | 2.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 2.01%   |
| Intel HD Graphics 630                                                                    | 5        | 2.01%   |
| Intel HD Graphics 500                                                                    | 5        | 2.01%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 2.01%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 1.61%   |
| Intel HD Graphics 610                                                                    | 4        | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4        | 1.61%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3        | 1.2%    |
| Intel UHD Graphics 620                                                                   | 3        | 1.2%    |
| Intel HD Graphics 620                                                                    | 3        | 1.2%    |
| Intel HD Graphics 5500                                                                   | 3        | 1.2%    |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.8%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.8%    |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.8%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.8%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.8%    |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 2        | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.8%    |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.8%    |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.8%    |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 0.8%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.4%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 150      | 59.76%  |
| 1 x Nvidia     | 36       | 14.34%  |
| 1 x AMD        | 31       | 12.35%  |
| Other          | 10       | 3.98%   |
| 2 x Intel      | 7        | 2.79%   |
| 1 x ASPEED     | 7        | 2.79%   |
| 1 x Matrox     | 5        | 1.99%   |
| 2 x AMD        | 2        | 0.8%    |
| Intel + Nvidia | 2        | 0.8%    |
| Intel + AMD    | 1        | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 217      | 86.8%   |
| Proprietary | 22       | 8.8%    |
| Unknown     | 11       | 4.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 216      | 87.45%  |
| 1.01-2.0   | 8        | 3.24%   |
| 0.51-1.0   | 8        | 3.24%   |
| 7.01-8.0   | 4        | 1.62%   |
| 3.01-4.0   | 4        | 1.62%   |
| 5.01-6.0   | 3        | 1.21%   |
| 8.01-16.0  | 2        | 0.81%   |
| 2.01-3.0   | 1        | 0.4%    |
| 0.01-0.5   | 1        | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 18.37%  |
| Dell                 | 6        | 12.24%  |
| BenQ                 | 6        | 12.24%  |
| Sony                 | 3        | 6.12%   |
| Samsung Electronics  | 3        | 6.12%   |
| LG Electronics       | 3        | 6.12%   |
| Lenovo               | 3        | 6.12%   |
| ASUSTek Computer     | 3        | 6.12%   |
| Acer                 | 3        | 6.12%   |
| Hewlett-Packard      | 2        | 4.08%   |
| AOC                  | 2        | 4.08%   |
| ViewSonic            | 1        | 2.04%   |
| Videoseven           | 1        | 2.04%   |
| Toshiba              | 1        | 2.04%   |
| LTV                  | 1        | 2.04%   |
| Insignia             | 1        | 2.04%   |
| Ancor Communications | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2        | 3.77%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2        | 3.77%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2        | 3.77%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1        | 1.89%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1        | 1.89%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 1.89%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1        | 1.89%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1        | 1.89%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1        | 1.89%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1        | 1.89%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1        | 1.89%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1        | 1.89%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.89%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1        | 1.89%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1        | 1.89%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.89%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch             | 1        | 1.89%   |
| Goldstar W2442 GSM56D9 1920x1080 530x300mm 24.0-inch                   | 1        | 1.89%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1        | 1.89%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 1.89%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.89%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch            | 1        | 1.89%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 1.89%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch               | 1        | 1.89%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.89%   |
| Goldstar LG FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch              | 1        | 1.89%   |
| Goldstar LCD Monitor GSM76F5 1920x1080 700x390mm 31.5-inch             | 1        | 1.89%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1        | 1.89%   |
| Dell SE2722H DELD116 1920x1080 600x340mm 27.2-inch                     | 1        | 1.89%   |
| Dell P3222QE DEL4246 3840x2160 700x390mm 31.5-inch                     | 1        | 1.89%   |
| Dell P2311H DEL4067 1920x1080 510x290mm 23.1-inch                      | 1        | 1.89%   |
| Dell P2219H DELA114 1920x1080 480x270mm 21.7-inch                      | 1        | 1.89%   |
| Dell LCD Monitor DELF003 1440x900 410x260mm 19.1-inch                  | 1        | 1.89%   |
| Dell 2001FP DELA008 1600x1200 410x310mm 20.2-inch                      | 1        | 1.89%   |
| BenQ XL2430T BNQ7F3D 1920x1080 530x300mm 24.0-inch                     | 1        | 1.89%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 1.89%   |
| BenQ LCD Monitor GW2765                                                | 1        | 1.89%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 1        | 1.89%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                      | 1        | 1.89%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 26       | 54.17%  |
| 3840x2160 (4K)     | 6        | 12.5%   |
| 2560x1440 (QHD)    | 2        | 4.17%   |
| 1680x1050 (WSXGA+) | 2        | 4.17%   |
| 1440x900 (WXGA+)   | 2        | 4.17%   |
| Unknown            | 2        | 4.17%   |
| 7680x2160          | 1        | 2.08%   |
| 3440x1440          | 1        | 2.08%   |
| 2560x1080          | 1        | 2.08%   |
| 1600x900 (HD+)     | 1        | 2.08%   |
| 1600x1200          | 1        | 2.08%   |
| 1366x768 (WXGA)    | 1        | 2.08%   |
| 1280x1024 (SXGA)   | 1        | 2.08%   |
| 1024x768 (XGA)     | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 12       | 24%     |
| 27      | 6        | 12%     |
| 21      | 6        | 12%     |
| Unknown | 6        | 12%     |
| 19      | 4        | 8%      |
| 54      | 3        | 6%      |
| 23      | 3        | 6%      |
| 34      | 2        | 4%      |
| 31      | 2        | 4%      |
| 22      | 2        | 4%      |
| 74      | 1        | 2%      |
| 36      | 1        | 2%      |
| 20      | 1        | 2%      |
| 18      | 1        | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 40.82%  |
| 401-500     | 13       | 26.53%  |
| Unknown     | 6        | 12.24%  |
| 701-800     | 3        | 6.12%   |
| 1001-1500   | 3        | 6.12%   |
| 601-700     | 2        | 4.08%   |
| 351-400     | 1        | 2.04%   |
| 1501-2000   | 1        | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 33       | 70.21%  |
| Unknown | 6        | 12.77%  |
| 16/10   | 4        | 8.51%   |
| 21/9    | 2        | 4.26%   |
| 5/4     | 1        | 2.13%   |
| 4/3     | 1        | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 40.82%  |
| 301-350        | 6        | 12.24%  |
| Unknown        | 6        | 12.24%  |
| 151-200        | 5        | 10.2%   |
| More than 1000 | 4        | 8.16%   |
| 351-500        | 4        | 8.16%   |
| 251-300        | 2        | 4.08%   |
| 141-150        | 1        | 2.04%   |
| 501-1000       | 1        | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 66%     |
| 101-120 | 8        | 16%     |
| Unknown | 6        | 12%     |
| 1-50    | 1        | 2%      |
| 161-240 | 1        | 2%      |
| 121-160 | 1        | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 194      | 77.91%  |
| 1     | 47       | 18.88%  |
| 2     | 8        | 3.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 192      | 56.8%   |
| Realtek Semiconductor           | 98       | 28.99%  |
| Broadcom                        | 16       | 4.73%   |
| Qualcomm Atheros                | 8        | 2.37%   |
| Solarflare Communications       | 3        | 0.89%   |
| MediaTek                        | 3        | 0.89%   |
| Ralink                          | 2        | 0.59%   |
| Mellanox Technologies           | 2        | 0.59%   |
| Marvell Technology Group        | 2        | 0.59%   |
| Chelsio Communications          | 2        | 0.59%   |
| 3Com                            | 2        | 0.59%   |
| Qualcomm Atheros Communications | 1        | 0.3%    |
| NetGear                         | 1        | 0.3%    |
| IMC Networks                    | 1        | 0.3%    |
| Hewlett-Packard                 | 1        | 0.3%    |
| Google                          | 1        | 0.3%    |
| D-Link System                   | 1        | 0.3%    |
| Aquantia                        | 1        | 0.3%    |
| Apple                           | 1        | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 82       | 19.66%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 6.95%   |
| Intel 82574L Gigabit Network Connection                                       | 23       | 5.52%   |
| Intel Ethernet Connection I217-LM                                             | 22       | 5.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22       | 5.28%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 3.12%   |
| Intel Ethernet Controller I226-V                                              | 11       | 2.64%   |
| Intel Ethernet Controller I225-V                                              | 11       | 2.64%   |
| Intel 82583V Gigabit Network Connection                                       | 10       | 2.4%    |
| Intel 82576 Gigabit Network Connection                                        | 10       | 2.4%    |
| Intel I210 Gigabit Network Connection                                         | 9        | 2.16%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 1.92%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.68%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.2%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 0.96%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.96%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.72%   |
| Intel Wireless 7260                                                           | 3        | 0.72%   |
| Intel Wireless 3165                                                           | 3        | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.72%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 0.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 3        | 0.72%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.72%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.72%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.48%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.48%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.48%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.48%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.48%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 50%     |
| Realtek Semiconductor           | 8        | 16.67%  |
| Qualcomm Atheros                | 6        | 12.5%   |
| MediaTek                        | 3        | 6.25%   |
| Ralink                          | 2        | 4.17%   |
| Broadcom                        | 2        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 2.08%   |
| NetGear                         | 1        | 2.08%   |
| IMC Networks                    | 1        | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 14%     |
| Intel Wireless 7260                                                     | 3        | 6%      |
| Intel Wireless 3165                                                     | 3        | 6%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3        | 6%      |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3        | 6%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2        | 4%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1        | 2%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 2%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 2%      |
| Realtek Bluetooth Adapter                                               | 1        | 2%      |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 2%      |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 2%      |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 2%      |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 2%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 2%      |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1        | 2%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 2%      |
| Intel Wireless 8260                                                     | 1        | 2%      |
| Intel Wireless 7265                                                     | 1        | 2%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 2%      |
| Intel Centrino Wireless-N 105                                           | 1        | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 2%      |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 2%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1        | 2%      |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 181      | 59.54%  |
| Realtek Semiconductor     | 94       | 30.92%  |
| Broadcom                  | 14       | 4.61%   |
| Solarflare Communications | 3        | 0.99%   |
| Qualcomm Atheros          | 2        | 0.66%   |
| Marvell Technology Group  | 2        | 0.66%   |
| Chelsio Communications    | 2        | 0.66%   |
| 3Com                      | 2        | 0.66%   |
| Google                    | 1        | 0.33%   |
| D-Link System             | 1        | 0.33%   |
| Aquantia                  | 1        | 0.33%   |
| Apple                     | 1        | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 82       | 22.65%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 8.01%   |
| Intel 82574L Gigabit Network Connection                                       | 23       | 6.35%   |
| Intel Ethernet Connection I217-LM                                             | 22       | 6.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22       | 6.08%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 3.59%   |
| Intel Ethernet Controller I226-V                                              | 11       | 3.04%   |
| Intel Ethernet Controller I225-V                                              | 11       | 3.04%   |
| Intel 82583V Gigabit Network Connection                                       | 10       | 2.76%   |
| Intel 82576 Gigabit Network Connection                                        | 10       | 2.76%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.21%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.21%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.38%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 1.1%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.1%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.83%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.83%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.83%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.83%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.83%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.55%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.55%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.55%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.55%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.55%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.55%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.55%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 243      | 82.37%  |
| WiFi     | 47       | 15.93%  |
| Unknown  | 4        | 1.36%   |
| Modem    | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 236      | 96.33%  |
| WiFi     | 9        | 3.67%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 59       | 23.69%  |
| 4     | 50       | 20.08%  |
| 3     | 46       | 18.47%  |
| 1     | 45       | 18.07%  |
| 5     | 22       | 8.84%   |
| 6     | 16       | 6.43%   |
| 7     | 4        | 1.61%   |
| 8     | 3        | 1.2%    |
| 0     | 2        | 0.8%    |
| 10    | 1        | 0.4%    |
| 9     | 1        | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 215      | 86%     |
| Yes  | 35       | 14%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 19       | 59.38%  |
| Cambridge Silicon Radio         | 5        | 15.63%  |
| Realtek Semiconductor           | 2        | 6.25%   |
| IMC Networks                    | 2        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 3.13%   |
| MediaTek                        | 1        | 3.13%   |
| Foxconn / Hon Hai               | 1        | 3.13%   |
| Apple                           | 1        | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                   | 6        | 18.18%  |
| Intel AX200 Bluetooth                                | 6        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 5        | 15.15%  |
| Intel Wireless-AC 3168 Bluetooth                     | 3        | 9.09%   |
| Intel AX201 Bluetooth                                | 2        | 6.06%   |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 3.03%   |
| Realtek Bluetooth Adapter                            | 1        | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 3.03%   |
| MediaTek RZ608 Bluetooth Adapter                     | 1        | 3.03%   |
| Intel Wireless Bluetooth                             | 1        | 3.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 3.03%   |
| Intel AX210 Bluetooth                                | 1        | 3.03%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 3.03%   |
| IMC Networks MediaTek Bluetooth Adapter              | 1        | 3.03%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 3.03%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 154      | 62.6%   |
| AMD                      | 41       | 16.67%  |
| Nvidia                   | 37       | 15.04%  |
| Logitech                 | 3        | 1.22%   |
| KTMicro                  | 2        | 0.81%   |
| C-Media Electronics      | 2        | 0.81%   |
| Yamaha                   | 1        | 0.41%   |
| Texas Instruments        | 1        | 0.41%   |
| SteelSeries ApS          | 1        | 0.41%   |
| Micro Star International | 1        | 0.41%   |
| Elgato Systems           | 1        | 0.41%   |
| Creative Labs            | 1        | 0.41%   |
| ASUSTek Computer         | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27       | 9.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26       | 8.78%   |
| Intel Jasper Lake HD Audio                                                                        | 15       | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15       | 5.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12       | 4.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10       | 3.38%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 3.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 3.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 2.03%   |
| AMD FCH Azalia Controller                                                                         | 6        | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6        | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.69%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.35%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.35%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.35%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4        | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 4        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 1.35%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3        | 1.01%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 1.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2        | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.68%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 47       | 16.91%  |
| Samsung Electronics | 41       | 14.75%  |
| SK hynix            | 38       | 13.67%  |
| Unknown             | 25       | 8.99%   |
| Crucial             | 22       | 7.91%   |
| Corsair             | 22       | 7.91%   |
| G.Skill             | 19       | 6.83%   |
| Micron Technology   | 14       | 5.04%   |
| Unknown             | 9        | 3.24%   |
| Apacer              | 5        | 1.8%    |
| Team                | 4        | 1.44%   |
| Ramaxel Technology  | 4        | 1.44%   |
| A-DATA Technology   | 4        | 1.44%   |
| Unknown (0x0C26)    | 3        | 1.08%   |
| Patriot             | 3        | 1.08%   |
| OCZ                 | 3        | 1.08%   |
| Nanya Technology    | 3        | 1.08%   |
| TIMETEC             | 2        | 0.72%   |
| V-Color             | 1        | 0.36%   |
| Unknown (ABCD)      | 1        | 0.36%   |
| Unknown (0x0DD5)    | 1        | 0.36%   |
| Transcend           | 1        | 0.36%   |
| Toshiba             | 1        | 0.36%   |
| Silicon Power       | 1        | 0.36%   |
| PNY                 | 1        | 0.36%   |
| Lexar Co Limited    | 1        | 0.36%   |
| Cors                | 1        | 0.36%   |
| Avant               | 1        | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown                                                 | 9        | 2.98%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 5        | 1.66%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 4        | 1.32%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s     | 4        | 1.32%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 4        | 1.32%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s | 4        | 1.32%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 3        | 0.99%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 3        | 0.99%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s    | 3        | 0.99%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s     | 3        | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 2        | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 2        | 0.66%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 2        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 0.66%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s    | 2        | 0.66%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.66%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s    | 2        | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 2        | 0.66%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s      | 2        | 0.66%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s     | 2        | 0.66%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s     | 2        | 0.66%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 0.66%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s  | 2        | 0.66%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s  | 2        | 0.66%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s        | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s               | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.33%   |
| Unknown RAM Module 8GB 1600MT/s                         | 1        | 0.33%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                  | 1        | 0.33%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 113      | 47.68%  |
| DDR4    | 94       | 39.66%  |
| DDR2    | 10       | 4.22%   |
| Unknown | 10       | 4.22%   |
| SDRAM   | 4        | 1.69%   |
| LPDDR4  | 2        | 0.84%   |
| DDR5    | 2        | 0.84%   |
| DDR     | 2        | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 163      | 70.26%  |
| SODIMM  | 65       | 28.02%  |
| RIMM    | 3        | 1.29%   |
| Unknown | 1        | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 88       | 33.85%  |
| 4096  | 87       | 33.46%  |
| 2048  | 37       | 14.23%  |
| 16384 | 33       | 12.69%  |
| 1024  | 10       | 3.85%   |
| 32768 | 4        | 1.54%   |
| 512   | 1        | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 83       | 32.17%  |
| 1333    | 38       | 14.73%  |
| 2400    | 24       | 9.3%    |
| 3200    | 22       | 8.53%   |
| 2667    | 22       | 8.53%   |
| 2133    | 20       | 7.75%   |
| 800     | 11       | 4.26%   |
| 2666    | 7        | 2.71%   |
| 1067    | 4        | 1.55%   |
| 667     | 4        | 1.55%   |
| Unknown | 4        | 1.55%   |
| 3600    | 3        | 1.16%   |
| 3000    | 3        | 1.16%   |
| 1066    | 3        | 1.16%   |
| 1866    | 2        | 0.78%   |
| 400     | 2        | 0.78%   |
| 6400    | 1        | 0.39%   |
| 5200    | 1        | 0.39%   |
| 4800    | 1        | 0.39%   |
| 3400    | 1        | 0.39%   |
| 1334    | 1        | 0.39%   |
| 333     | 1        | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 50%     |
| Brother Industries | 2        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| HP LaserJet 2200          | 1        | 25%     |
| HP Color LaserJet CP1215  | 1        | 25%     |
| Brother HL-L5200DW series | 1        | 25%     |
| Brother HL-L2300D series  | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 60%     |
| Microdia            | 1        | 20%     |
| Chicony Electronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia JOYACCESS JA-Webcam  | 1        | 20%     |
| Logitech Webcam C310          | 1        | 20%     |
| Logitech HD Pro Webcam C920   | 1        | 20%     |
| Logitech BRIO Ultra HD Webcam | 1        | 20%     |
| Chicony HP 0.3MP Webcam       | 1        | 20%     |

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
| 1     | 147      | 58.33%  |
| 0     | 69       | 27.38%  |
| 2     | 27       | 10.71%  |
| 3     | 6        | 2.38%   |
| 4     | 3        | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 162      | 75.7%   |
| Net/wireless             | 17       | 7.94%   |
| Bluetooth                | 11       | 5.14%   |
| Firewire controller      | 6        | 2.8%    |
| Sound                    | 5        | 2.34%   |
| Net/ethernet             | 5        | 2.34%   |
| Network                  | 3        | 1.4%    |
| Card reader              | 3        | 1.4%    |
| Storage/raid             | 1        | 0.47%   |
| Graphics card            | 1        | 0.47%   |

