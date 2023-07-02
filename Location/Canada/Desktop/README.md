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

Total: 418

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| MW            | GMLK-2_5G4L                 | [1ef9818928](https://bsd-hardware.info/?probe=1ef9818928) | Jun 27, 2023 |
| HP            | 1495                        | [564ff2ef77](https://bsd-hardware.info/?probe=564ff2ef77) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M55 880894U     | [e406083f25](https://bsd-hardware.info/?probe=e406083f25) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | [0b667bc4e7](https://bsd-hardware.info/?probe=0b667bc4e7) | Jun 22, 2023 |
| ASUSTek       | M5A97 PLUS                  | [39e7195baf](https://bsd-hardware.info/?probe=39e7195baf) | Jun 15, 2023 |
| Protectli     | FW4B Ver                    | [3484cbbf9f](https://bsd-hardware.info/?probe=3484cbbf9f) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | [080be9d6f5](https://bsd-hardware.info/?probe=080be9d6f5) | Jun 13, 2023 |
| Unknown       | Unknown                     | [88a421e275](https://bsd-hardware.info/?probe=88a421e275) | Jun 10, 2023 |
| ASUSTek       | P8Z68-V LE                  | [48833ba1a3](https://bsd-hardware.info/?probe=48833ba1a3) | Jun 08, 2023 |
| Protectli     | VP2420                      | [45e550e09f](https://bsd-hardware.info/?probe=45e550e09f) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | [f0f13f5cea](https://bsd-hardware.info/?probe=f0f13f5cea) | Jun 06, 2023 |
| HP            | 1495                        | [a7a24624d7](https://bsd-hardware.info/?probe=a7a24624d7) | Jun 05, 2023 |
| Protectli     | FW4B Ver                    | [5fc38b17d3](https://bsd-hardware.info/?probe=5fc38b17d3) | Jun 04, 2023 |
| Techvision    | TVI7309X B0                 | [5be94420c2](https://bsd-hardware.info/?probe=5be94420c2) | Jun 02, 2023 |
| Techvision    | TVI7309X B0                 | [ed0c6cf73c](https://bsd-hardware.info/?probe=ed0c6cf73c) | May 31, 2023 |
| Unknown       | Unknown                     | [88e6cd10c6](https://bsd-hardware.info/?probe=88e6cd10c6) | May 27, 2023 |
| Protectli     | FW4B                        | [c5c9276f48](https://bsd-hardware.info/?probe=c5c9276f48) | May 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| MSI           | B450I GAMING PLUS AC        | [cc4c36977f](https://bsd-hardware.info/?probe=cc4c36977f) | May 18, 2023 |
| MSI           | B450I GAMING PLUS AC        | [432b2a27c3](https://bsd-hardware.info/?probe=432b2a27c3) | May 13, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | [b0c462fbd5](https://bsd-hardware.info/?probe=b0c462fbd5) | May 02, 2023 |
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
| HP            | 1495                        | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
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
| HP            | 1495                        | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
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
| OPNsense 22.7.10  | 14       | 4.06%   |
| OPNsense 23.1.6   | 10       | 2.9%    |
| OPNsense 23.1.1   | 9        | 2.61%   |
| OPNsense 22.1.10  | 9        | 2.61%   |
| helloSystem 0.7.0 | 9        | 2.61%   |
| OPNsense 23.1.9   | 8        | 2.32%   |
| OPNsense 22.7.8   | 8        | 2.32%   |
| OPNsense 22.1.8   | 8        | 2.32%   |
| OPNsense 21.1.4   | 8        | 2.32%   |
| helloSystem 0.5.0 | 8        | 2.32%   |
| OPNsense 23.1     | 7        | 2.03%   |
| OPNsense 22.1.7   | 7        | 2.03%   |
| OPNsense 22.1     | 7        | 2.03%   |
| OPNsense 21.7     | 7        | 2.03%   |
| OPNsense 21.1.3   | 7        | 2.03%   |
| OPNsense 21.1     | 7        | 2.03%   |
| OPNsense 22.7.4   | 6        | 1.74%   |
| OPNsense 22.1.6   | 6        | 1.74%   |
| OPNsense 21.1.5   | 6        | 1.74%   |
| OPNsense 20.7.8   | 6        | 1.74%   |
| FreeBSD 13.1-p5   | 6        | 1.74%   |
| OPNsense 22.7.9   | 5        | 1.45%   |
| OPNsense 22.7.11  | 5        | 1.45%   |
| OPNsense 22.7     | 5        | 1.45%   |
| OPNsense 21.7.7   | 5        | 1.45%   |
| OPNsense 21.7.3   | 5        | 1.45%   |
| OPNsense 21.7.1   | 5        | 1.45%   |
| OPNsense 21.1.6   | 5        | 1.45%   |
| OPNsense 21.1.1   | 5        | 1.45%   |
| helloSystem 0.8.1 | 5        | 1.45%   |
| FreeBSD 13.1      | 5        | 1.45%   |
| FreeBSD 12.2      | 5        | 1.45%   |
| OPNsense 23.1.5   | 4        | 1.16%   |
| OPNsense 23.1.4   | 4        | 1.16%   |
| OPNsense 22.7.7   | 4        | 1.16%   |
| OPNsense 22.1.3   | 4        | 1.16%   |
| OPNsense 21.7.8   | 4        | 1.16%   |
| OPNsense 21.7.4   | 4        | 1.16%   |
| OPNsense 23.1.8   | 3        | 0.87%   |
| OPNsense 22.7.6   | 3        | 0.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 175      | 66.79%  |
| FreeBSD     | 47       | 17.94%  |
| helloSystem | 25       | 9.54%   |
| OpenBSD     | 6        | 2.29%   |
| GhostBSD    | 3        | 1.15%   |
| FreeNAS     | 3        | 1.15%   |
| TrueNAS     | 1        | 0.38%   |
| pfSense     | 1        | 0.38%   |
| MyBee       | 1        | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 257      | 99.23%  |
| macppc | 1        | 0.39%   |
| i386   | 1        | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 200      | 76.05%  |
| helloDesktop | 29       | 11.03%  |
| KDE5         | 10       | 3.8%    |
| XFCE         | 8        | 3.04%   |
| MATE         | 6        | 2.28%   |
| GNOME        | 3        | 1.14%   |
| Cinnamon     | 2        | 0.76%   |
| X-Cinnamon   | 1        | 0.38%   |
| Window Maker | 1        | 0.38%   |
| Openbox      | 1        | 0.38%   |
| LXDE         | 1        | 0.38%   |
| DWM          | 1        | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 201      | 77.61%  |
| X11     | 57       | 22.01%  |
| Wayland | 1        | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 211      | 80.23%  |
| SLiM    | 29       | 11.03%  |
| SDDM    | 13       | 4.94%   |
| LightDM | 4        | 1.52%   |
| XDM     | 3        | 1.14%   |
| GDM     | 2        | 0.76%   |
| Ly      | 1        | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 191      | 73.18%  |
| en_US   | 39       | 14.94%  |
| C       | 22       | 8.43%   |
| en_CA   | 5        | 1.92%   |
| fr_FR   | 2        | 0.77%   |
| fr      | 1        | 0.38%   |
| en      | 1        | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 220      | 83.65%  |
| BIOS | 43       | 16.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 139      | 51.87%  |
| Zfs    | 112      | 41.79%  |
| Cd9660 | 11       | 4.1%    |
| Ffs    | 6        | 2.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 240      | 92.66%  |
| MBR     | 17       | 6.56%   |
| Unknown | 2        | 0.77%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Hewlett-Packard            | 33       | 12.74%  |
| ASUSTek Computer           | 31       | 11.97%  |
| Dell                       | 28       | 10.81%  |
| Unknown                    | 22       | 8.49%   |
| Lenovo                     | 20       | 7.72%   |
| Protectli                  | 19       | 7.34%   |
| Intel                      | 15       | 5.79%   |
| Gigabyte Technology        | 13       | 5.02%   |
| ASRock                     | 12       | 4.63%   |
| Supermicro                 | 11       | 4.25%   |
| MSI                        | 11       | 4.25%   |
| Techvision                 | 8        | 3.09%   |
| PC Engines                 | 5        | 1.93%   |
| Acer                       | 5        | 1.93%   |
| AZW                        | 3        | 1.16%   |
| ASRockRack                 | 2        | 0.77%   |
| Apple                      | 2        | 0.77%   |
| Yanling                    | 1        | 0.39%   |
| Shuttle                    | 1        | 0.39%   |
| ShenZhen MinWin Technology | 1        | 0.39%   |
| SeeedStudio                | 1        | 0.39%   |
| Quanta                     | 1        | 0.39%   |
| Pegatron                   | 1        | 0.39%   |
| MW                         | 1        | 0.39%   |
| MiTAC                      | 1        | 0.39%   |
| IBM                        | 1        | 0.39%   |
| iBASE                      | 1        | 0.39%   |
| HARDKERNEL                 | 1        | 0.39%   |
| Datto                      | 1        | 0.39%   |
| CncTion                    | 1        | 0.39%   |
| Cisco                      | 1        | 0.39%   |
| Biostar                    | 1        | 0.39%   |
| Arctic Wolf Networks       | 1        | 0.39%   |
| AMI                        | 1        | 0.39%   |
| Alienware                  | 1        | 0.39%   |
| ADI Engineering            | 1        | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 22       | 8.49%   |
| Protectli FW4B                     | 11       | 4.25%   |
| Techvision TVI7309X                | 8        | 3.09%   |
| Intel Q3XXG4-P V1.0                | 6        | 2.32%   |
| Protectli FW6                      | 5        | 1.93%   |
| Intel NDISB533                     | 4        | 1.54%   |
| HP EliteDesk 800 G1 SFF            | 4        | 1.54%   |
| Dell OptiPlex 9010                 | 4        | 1.54%   |
| HP Z440 Workstation                | 3        | 1.16%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 1.16%   |
| HP Compaq 6200 Pro MT PC           | 3        | 1.16%   |
| Dell OptiPlex 7010                 | 3        | 1.16%   |
| ASUS All Series                    | 3        | 1.16%   |
| Supermicro X8STi                   | 2        | 0.77%   |
| PC Engines apu4                    | 2        | 0.77%   |
| PC Engines APU2                    | 2        | 0.77%   |
| MSI MS-7A40                        | 2        | 0.77%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2        | 0.77%   |
| Intel CRESCENTBAY                  | 2        | 0.77%   |
| HP Compaq Elite 8300 SFF           | 2        | 0.77%   |
| Dell Precision WorkStation T3500   | 2        | 0.77%   |
| Dell Precision Tower 5810          | 2        | 0.77%   |
| Dell OptiPlex 7050                 | 2        | 0.77%   |
| Dell OptiPlex 7020                 | 2        | 0.77%   |
| Dell OptiPlex 3020                 | 2        | 0.77%   |
| Dell G5 5090                       | 2        | 0.77%   |
| AZW U59                            | 2        | 0.77%   |
| ASUS P8H77-I                       | 2        | 0.77%   |
| ASUS M5A97 PLUS                    | 2        | 0.77%   |
| ASRock H110M-DGS R3.0              | 2        | 0.77%   |
| ASRock B450M Pro4                  | 2        | 0.77%   |
| Yanling YL-KBR6L                   | 1        | 0.39%   |
| Supermicro X9SCL/X9SCM             | 1        | 0.39%   |
| Supermicro X9DR3-F                 | 1        | 0.39%   |
| Supermicro X7SPA-HF                | 1        | 0.39%   |
| Supermicro X7SLA                   | 1        | 0.39%   |
| Supermicro SYS-E300-9A             | 1        | 0.39%   |
| Supermicro SYS-5019S-ML            | 1        | 0.39%   |
| Supermicro SYS-5019D-FN8TP         | 1        | 0.39%   |
| Supermicro SYS-5019A-FTN4          | 1        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 22       | 8.49%   |
| Dell OptiPlex              | 21       | 8.11%   |
| Lenovo ThinkCentre         | 18       | 6.95%   |
| Protectli FW4B             | 11       | 4.25%   |
| HP Compaq                  | 9        | 3.47%   |
| Techvision TVI7309X        | 8        | 3.09%   |
| ASUS PRIME                 | 8        | 3.09%   |
| HP ProDesk                 | 7        | 2.7%    |
| Intel Q3XXG4-P             | 6        | 2.32%   |
| HP EliteDesk               | 6        | 2.32%   |
| Protectli FW6              | 5        | 1.93%   |
| Dell Precision             | 5        | 1.93%   |
| ASUS ROG                   | 5        | 1.93%   |
| Acer Aspire                | 5        | 1.93%   |
| Intel NDISB533             | 4        | 1.54%   |
| HP Z440                    | 3        | 1.16%   |
| ASUS All                   | 3        | 1.16%   |
| ASRock B450M               | 3        | 1.16%   |
| Supermicro X8STi           | 2        | 0.77%   |
| PC Engines apu4            | 2        | 0.77%   |
| PC Engines APU2            | 2        | 0.77%   |
| MSI MS-7A40                | 2        | 0.77%   |
| Intel CRESCENTBAY          | 2        | 0.77%   |
| HP t620                    | 2        | 0.77%   |
| Dell G5                    | 2        | 0.77%   |
| AZW U59                    | 2        | 0.77%   |
| ASUS TUF                   | 2        | 0.77%   |
| ASUS P8H77-I               | 2        | 0.77%   |
| ASUS M5A97                 | 2        | 0.77%   |
| ASRock H110M-DGS           | 2        | 0.77%   |
| Yanling YL-KBR6L           | 1        | 0.39%   |
| Supermicro X9SCL           | 1        | 0.39%   |
| Supermicro X9DR3-F         | 1        | 0.39%   |
| Supermicro X7SPA-HF        | 1        | 0.39%   |
| Supermicro X7SLA           | 1        | 0.39%   |
| Supermicro SYS-E300-9A     | 1        | 0.39%   |
| Supermicro SYS-5019S-ML    | 1        | 0.39%   |
| Supermicro SYS-5019D-FN8TP | 1        | 0.39%   |
| Supermicro SYS-5019A-FTN4  | 1        | 0.39%   |
| Supermicro AS              | 1        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 37       | 14.29%  |
| 2022    | 31       | 11.97%  |
| 2020    | 26       | 10.04%  |
| 2014    | 24       | 9.27%   |
| 2019    | 18       | 6.95%   |
| 2016    | 18       | 6.95%   |
| 2013    | 18       | 6.95%   |
| 2011    | 15       | 5.79%   |
| 2021    | 14       | 5.41%   |
| 2012    | 11       | 4.25%   |
| 2010    | 11       | 4.25%   |
| 2017    | 9        | 3.47%   |
| 2015    | 8        | 3.09%   |
| 2009    | 6        | 2.32%   |
| 2008    | 6        | 2.32%   |
| 2023    | 3        | 1.16%   |
| Unknown | 2        | 0.77%   |
| 2007    | 1        | 0.39%   |
| 2006    | 1        | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 259      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 250      | 96.53%  |
| Yes  | 9        | 3.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 104      | 38.95%  |
| 16.01-24.0  | 59       | 22.1%   |
| 4.01-8.0    | 43       | 16.1%   |
| 32.01-64.0  | 30       | 11.24%  |
| 64.01-256.0 | 13       | 4.87%   |
| 2.01-3.0    | 6        | 2.25%   |
| 24.01-32.0  | 5        | 1.87%   |
| 3.01-4.0    | 4        | 1.5%    |
| 1.01-2.0    | 2        | 0.75%   |
| 0.51-1.0    | 1        | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 132      | 49.62%  |
| 0.51-1.0    | 78       | 29.32%  |
| 1.01-2.0    | 38       | 14.29%  |
| 2.01-3.0    | 6        | 2.26%   |
| 4.01-8.0    | 4        | 1.5%    |
| 3.01-4.0    | 4        | 1.5%    |
| 32.01-64.0  | 1        | 0.38%   |
| 64.01-256.0 | 1        | 0.38%   |
| 8.01-16.0   | 1        | 0.38%   |
| 0           | 1        | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 183      | 69.58%  |
| 2      | 37       | 14.07%  |
| 3      | 17       | 6.46%   |
| 0      | 15       | 5.7%    |
| 4      | 7        | 2.66%   |
| 13     | 1        | 0.38%   |
| 10     | 1        | 0.38%   |
| 7      | 1        | 0.38%   |
| 5      | 1        | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 204      | 77.27%  |
| Yes       | 60       | 22.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 257      | 98.85%  |
| No        | 3        | 1.15%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 212      | 80.92%  |
| Yes       | 50       | 19.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 225      | 86.87%  |
| Yes       | 34       | 13.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Canada  | 259      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Desktops | Percent |
|----------------------------|----------|---------|
| Toronto                    | 25       | 9.06%   |
| Montreal                   | 24       | 8.7%    |
| Calgary                    | 15       | 5.43%   |
| Ottawa                     | 14       | 5.07%   |
| Edmonton                   | 13       | 4.71%   |
| Victoria                   | 9        | 3.26%   |
| Winnipeg                   | 8        | 2.9%    |
| Kitchener                  | 8        | 2.9%    |
| Vancouver                  | 6        | 2.17%   |
| Surrey                     | 6        | 2.17%   |
| Brampton                   | 6        | 2.17%   |
| Regina                     | 5        | 1.81%   |
| St. Albert                 | 4        | 1.45%   |
| London                     | 4        | 1.45%   |
| Windsor                    | 3        | 1.09%   |
| St. Jean Baptiste          | 3        | 1.09%   |
| Saskatoon                  | 3        | 1.09%   |
| Sarnia                     | 3        | 1.09%   |
| Québec                    | 3        | 1.09%   |
| Nanaimo                    | 3        | 1.09%   |
| Moncton                    | 3        | 1.09%   |
| Laval                      | 3        | 1.09%   |
| Greater Sudbury            | 3        | 1.09%   |
| Cambridge                  | 3        | 1.09%   |
| Burlington                 | 3        | 1.09%   |
| West Kelowna               | 2        | 0.72%   |
| Terrebonne                 | 2        | 0.72%   |
| Sainte-Julie               | 2        | 0.72%   |
| Saint-Bruno-de-Montarville | 2        | 0.72%   |
| Richmond                   | 2        | 0.72%   |
| Peterborough               | 2        | 0.72%   |
| Oakville                   | 2        | 0.72%   |
| Mississauga                | 2        | 0.72%   |
| Lamont                     | 2        | 0.72%   |
| La Prairie                 | 2        | 0.72%   |
| Kingston                   | 2        | 0.72%   |
| Kanata                     | 2        | 0.72%   |
| Hamilton                   | 2        | 0.72%   |
| Guelph                     | 2        | 0.72%   |
| Cobourg                    | 2        | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 50       | 72     | 15.92%  |
| Seagate             | 43       | 76     | 13.69%  |
| WDC                 | 42       | 87     | 13.38%  |
| Kingston            | 38       | 49     | 12.1%   |
| Crucial             | 14       | 21     | 4.46%   |
| A-DATA Technology   | 13       | 22     | 4.14%   |
| Intel               | 11       | 15     | 3.5%    |
| SanDisk             | 9        | 11     | 2.87%   |
| Toshiba             | 7        | 11     | 2.23%   |
| Patriot             | 7        | 8      | 2.23%   |
| SPCC                | 6        | 6      | 1.91%   |
| Hitachi             | 6        | 6      | 1.91%   |
| Dogfish             | 5        | 8      | 1.59%   |
| OCZ                 | 4        | 5      | 1.27%   |
| Mushkin             | 4        | 4      | 1.27%   |
| Micron Technology   | 4        | 7      | 1.27%   |
| BIWIN               | 4        | 6      | 1.27%   |
| Transcend           | 3        | 4      | 0.96%   |
| SK hynix            | 3        | 5      | 0.96%   |
| PNY                 | 3        | 4      | 0.96%   |
| Hoodisk             | 3        | 4      | 0.96%   |
| HGST                | 3        | 5      | 0.96%   |
| Hewlett-Packard     | 3        | 3      | 0.96%   |
| VisionTek           | 2        | 6      | 0.64%   |
| Timetec             | 2        | 2      | 0.64%   |
| Protectli           | 2        | 3      | 0.64%   |
| Phison              | 2        | 3      | 0.64%   |
| NVMe                | 2        | 2      | 0.64%   |
| FORESEE             | 2        | 3      | 0.64%   |
| Corsair             | 2        | 4      | 0.64%   |
| China               | 2        | 4      | 0.64%   |
| walram              | 1        | 1      | 0.32%   |
| Team                | 1        | 2      | 0.32%   |
| Silicon Motion      | 1        | 1      | 0.32%   |
| SATADOM             | 1        | 2      | 0.32%   |
| OPENBSD             | 1        | 1      | 0.32%   |
| Netac               | 1        | 1      | 0.32%   |
| Lexar               | 1        | 1      | 0.32%   |
| Innodisk            | 1        | 1      | 0.32%   |
| HPT                 | 1        | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 11       | 3.3%    |
| Kingston SA400S37120G 120GB     | 9        | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB  | 6        | 1.8%    |
| Seagate ST500DM002-1BD142 500GB | 5        | 1.5%    |
| Samsung SSD 850 EVO 250GB       | 5        | 1.5%    |
| Seagate ST2000DM008-2FR102 2TB  | 4        | 1.2%    |
| Samsung SSD 970 EVO Plus 1TB    | 4        | 1.2%    |
| Samsung SSD 860 EVO 500GB       | 4        | 1.2%    |
| BIWIN SSD 128GB                 | 4        | 1.2%    |
| WDC WD20EZRX-00DC0B0 2TB        | 3        | 0.9%    |
| Transcend TS256GMSA230S 256GB   | 3        | 0.9%    |
| Toshiba DT01ACA100 1TB          | 3        | 0.9%    |
| Seagate ST3500413AS 500GB       | 3        | 0.9%    |
| SanDisk SD6SB1M064G1022I 64GB   | 3        | 0.9%    |
| Samsung SSD 980 1TB             | 3        | 0.9%    |
| Samsung SSD 840 EVO 120GB       | 3        | 0.9%    |
| Kingston SUV500MS120G 120GB     | 3        | 0.9%    |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.9%    |
| WDC WD6400AAKS-22A7B2 640GB     | 2        | 0.6%    |
| WDC WD40EFRX-68WT0N0 4TB        | 2        | 0.6%    |
| WDC WD10EZEX-22MFCA0 1TB        | 2        | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB        | 2        | 0.6%    |
| WDC PC SN520 NVMe 256GB         | 2        | 0.6%    |
| VisionTek mSATA 120GB           | 2        | 0.6%    |
| Toshiba MQ01ABD075 752GB        | 2        | 0.6%    |
| SPCC Solid State Disk 256GB     | 2        | 0.6%    |
| SPCC Solid State Disk 128GB     | 2        | 0.6%    |
| Seagate ST4000VN008-2DR166 4TB  | 2        | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.6%    |
| SanDisk SDSA6MM-016G-1006 16GB  | 2        | 0.6%    |
| Samsung SSD 980 PRO 1TB         | 2        | 0.6%    |
| Samsung SSD 970 EVO Plus 250GB  | 2        | 0.6%    |
| Samsung SSD 870 EVO 500GB       | 2        | 0.6%    |
| Samsung SSD 850 PRO 256GB       | 2        | 0.6%    |
| Samsung SSD 850 EVO mSATA 250GB | 2        | 0.6%    |
| Samsung SSD 840 EVO 250GB       | 2        | 0.6%    |
| Protectli 64GB mSATA            | 2        | 0.6%    |
| PNY CS1311 120GB SSD            | 2        | 0.6%    |
| Patriot M.2 P310 240GB          | 2        | 0.6%    |
| Mushkin MKNSSDEC60GB 64GB       | 2        | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 41       | 74     | 45.56%  |
| WDC     | 31       | 71     | 34.44%  |
| Toshiba | 6        | 8      | 6.67%   |
| Hitachi | 6        | 6      | 6.67%   |
| HGST    | 3        | 5      | 3.33%   |
| OPENBSD | 1        | 1      | 1.11%   |
| HPT     | 1        | 1      | 1.11%   |
| Fujitsu | 1        | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 54     | 19.89%  |
| Kingston            | 35       | 42     | 18.82%  |
| Crucial             | 13       | 18     | 6.99%   |
| A-DATA Technology   | 13       | 22     | 6.99%   |
| Intel               | 10       | 14     | 5.38%   |
| SanDisk             | 9        | 11     | 4.84%   |
| WDC                 | 7        | 9      | 3.76%   |
| SPCC                | 5        | 5      | 2.69%   |
| Dogfish             | 5        | 8      | 2.69%   |
| Patriot             | 4        | 5      | 2.15%   |
| OCZ                 | 4        | 5      | 2.15%   |
| Mushkin             | 4        | 4      | 2.15%   |
| BIWIN               | 4        | 6      | 2.15%   |
| Transcend           | 3        | 4      | 1.61%   |
| PNY                 | 3        | 4      | 1.61%   |
| Micron Technology   | 3        | 6      | 1.61%   |
| Hoodisk             | 3        | 4      | 1.61%   |
| VisionTek           | 2        | 6      | 1.08%   |
| Seagate             | 2        | 2      | 1.08%   |
| Protectli           | 2        | 3      | 1.08%   |
| FORESEE             | 2        | 3      | 1.08%   |
| Corsair             | 2        | 4      | 1.08%   |
| China               | 2        | 4      | 1.08%   |
| walram              | 1        | 1      | 0.54%   |
| Timetec             | 1        | 1      | 0.54%   |
| SATADOM             | 1        | 2      | 0.54%   |
| Phison              | 1        | 1      | 0.54%   |
| NVMe                | 1        | 1      | 0.54%   |
| Netac               | 1        | 1      | 0.54%   |
| Lexar               | 1        | 1      | 0.54%   |
| Innodisk            | 1        | 1      | 0.54%   |
| HPE                 | 1        | 4      | 0.54%   |
| Hewlett-Packard     | 1        | 1      | 0.54%   |
| EAGET               | 1        | 1      | 0.54%   |
| AVEXIR              | 1        | 2      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 171      | 260    | 60.42%  |
| HDD  | 74       | 167    | 26.15%  |
| NVMe | 38       | 58     | 13.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 220      | 427    | 85.27%  |
| NVMe | 38       | 58     | 14.73%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 184      | 278    | 71.88%  |
| 0.51-1.0   | 37       | 66     | 14.45%  |
| 1.01-2.0   | 16       | 27     | 6.25%   |
| 3.01-4.0   | 8        | 20     | 3.13%   |
| 4.01-10.0  | 5        | 23     | 1.95%   |
| 2.01-3.0   | 4        | 10     | 1.56%   |
| 10.01-20.0 | 2        | 3      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 117      | 42.7%   |
| 251-500        | 42       | 15.33%  |
| 51-100         | 33       | 12.04%  |
| 1-20           | 26       | 9.49%   |
| 21-50          | 22       | 8.03%   |
| 501-1000       | 21       | 7.66%   |
| 1001-2000      | 7        | 2.55%   |
| More than 3000 | 3        | 1.09%   |
| Unknown        | 3        | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 241      | 88.6%   |
| 21-50     | 18       | 6.62%   |
| 51-100    | 5        | 1.84%   |
| Unknown   | 3        | 1.1%    |
| 101-250   | 2        | 0.74%   |
| 1001-2000 | 2        | 0.74%   |
| 501-1000  | 1        | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                | 2        | 7      | 5%      |
| VisionTek mSATA 120GB                      | 2        | 6      | 5%      |
| Toshiba MQ01ABD075 752GB                   | 2        | 2      | 5%      |
| Seagate ST500DM002-1BD142 500GB            | 2        | 4      | 5%      |
| Seagate ST3500413AS 500GB                  | 2        | 4      | 5%      |
| WDC WD50EFRX-68L0BN1 5TB                   | 1        | 1      | 2.5%    |
| WDC WD5003AZEX-00K1GA0 500GB               | 1        | 1      | 2.5%    |
| WDC WD40EFRX-68WT0N0 4TB                   | 1        | 2      | 2.5%    |
| WDC WD30EZRX-22D8PB0 3TB                   | 1        | 1      | 2.5%    |
| WDC WD2500AAKX-001CA0 250GB                | 1        | 1      | 2.5%    |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 2      | 2.5%    |
| walram SSD 120G                            | 1        | 1      | 2.5%    |
| Toshiba DT01ACA100 1TB                     | 1        | 3      | 2.5%    |
| SPCC Solid State Disk 128GB                | 1        | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB            | 1        | 1      | 2.5%    |
| Seagate ST3250318AS 250GB                  | 1        | 1      | 2.5%    |
| Seagate ST3200822AS 200GB                  | 1        | 1      | 2.5%    |
| Seagate ST3160815AS 160GB                  | 1        | 1      | 2.5%    |
| Seagate ST31500341AS 1.5TB                 | 1        | 2      | 2.5%    |
| Seagate ST3120026A 120GB                   | 1        | 1      | 2.5%    |
| Seagate ST31000520AS 1TB                   | 1        | 1      | 2.5%    |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 2      | 2.5%    |
| Samsung Electronics SSD 870 EVO 250GB      | 1        | 3      | 2.5%    |
| Mushkin MKNSSDEC512GB                      | 1        | 1      | 2.5%    |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1        | 4      | 2.5%    |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 2.5%    |
| Intel SSDSC2BB480G4 480GB                  | 1        | 1      | 2.5%    |
| Intel SSDSA2M080G2GC 80GB                  | 1        | 1      | 2.5%    |
| Hitachi HTS727550A9E364 500GB              | 1        | 1      | 2.5%    |
| Hitachi HTS542520K9A300 200GB              | 1        | 1      | 2.5%    |
| Hitachi HDT721010SLA360 1TB                | 1        | 1      | 2.5%    |
| HGST HTS725050A7E630 500GB                 | 1        | 2      | 2.5%    |
| HGST HTS541010A9E680 1TB                   | 1        | 1      | 2.5%    |
| Crucial CT240M500SSD1 240GB                | 1        | 1      | 2.5%    |
| A-DATA Technology SU800 1TB                | 1        | 2      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 18     | 28.21%  |
| WDC                 | 8        | 15     | 20.51%  |
| Toshiba             | 3        | 5      | 7.69%   |
| Hitachi             | 3        | 3      | 7.69%   |
| VisionTek           | 2        | 6      | 5.13%   |
| Intel               | 2        | 2      | 5.13%   |
| HGST                | 2        | 3      | 5.13%   |
| walram              | 1        | 1      | 2.56%   |
| SPCC                | 1        | 1      | 2.56%   |
| Samsung Electronics | 1        | 3      | 2.56%   |
| Mushkin             | 1        | 1      | 2.56%   |
| Micron Technology   | 1        | 4      | 2.56%   |
| Kingston            | 1        | 1      | 2.56%   |
| Crucial             | 1        | 1      | 2.56%   |
| A-DATA Technology   | 1        | 2      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 18     | 40.74%  |
| WDC     | 8        | 15     | 29.63%  |
| Toshiba | 3        | 5      | 11.11%  |
| Hitachi | 3        | 3      | 11.11%  |
| HGST    | 2        | 3      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 44     | 66.67%  |
| SSD  | 12       | 22     | 33.33%  |

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
| Works    | 222      | 409    | 83.46%  |
| Malfunc  | 35       | 66     | 13.16%  |
| Detected | 7        | 8      | 2.63%   |
| Failed   | 2        | 2      | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 212      | 66.46%  |
| AMD                         | 42       | 13.17%  |
| Samsung Electronics         | 14       | 4.39%   |
| SanDisk                     | 8        | 2.51%   |
| Silicon Motion              | 5        | 1.57%   |
| Nvidia                      | 5        | 1.57%   |
| ASMedia Technology          | 5        | 1.57%   |
| MAXIO Technology (Hangzhou) | 4        | 1.25%   |
| Kingston Technology Company | 4        | 1.25%   |
| SK hynix                    | 3        | 0.94%   |
| Broadcom / LSI              | 3        | 0.94%   |
| Silicon Image               | 2        | 0.63%   |
| Micron/Crucial Technology   | 2        | 0.63%   |
| Marvell Technology Group    | 2        | 0.63%   |
| JMicron Technology          | 2        | 0.63%   |
| Chelsio Communications      | 2        | 0.63%   |
| Toshiba                     | 1        | 0.31%   |
| Phison Electronics          | 1        | 0.31%   |
| Micron Technology           | 1        | 0.31%   |
| HighPoint Technologies      | 1        | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29       | 7.77%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19       | 5.09%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 18       | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 18       | 4.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 14       | 3.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13       | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12       | 3.22%   |
| AMD 400 Series Chipset SATA Controller                                           | 12       | 3.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10       | 2.68%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 9        | 2.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8        | 2.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7        | 1.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7        | 1.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 7        | 1.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5        | 1.34%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 5        | 1.34%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 5        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5        | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5        | 1.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4        | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 1.07%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 4        | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4        | 1.07%   |
| Intel Elkhart Lake SATA AHCI                                                     | 4        | 1.07%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4        | 1.07%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 1.07%   |
| SanDisk PC SN520 NVMe SSD                                                        | 3        | 0.8%    |
| Samsung NVMe SSD Controller 980                                                  | 3        | 0.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3        | 0.8%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3        | 0.8%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 3        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 3        | 0.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3        | 0.8%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 3        | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 0.8%    |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 2        | 0.54%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 2        | 0.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 227      | 71.16%  |
| NVMe | 41       | 12.85%  |
| IDE  | 34       | 10.66%  |
| RAID | 9        | 2.82%   |
| SAS  | 4        | 1.25%   |
| SCSI | 4        | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 215      | 82.06%  |
| AMD     | 46       | 17.56%  |
| Unknown | 1        | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz        | 14       | 5.24%   |
| Intel Celeron CPU J3160 @ 1.60GHz    | 11       | 4.12%   |
| Intel Core i5-3570 CPU @ 3.40GHz     | 8        | 3%      |
| Intel Core i5-4570 CPU @ 3.20GHz     | 7        | 2.62%   |
| Intel Celeron J4125 CPU @ 2.00GHz    | 7        | 2.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz     | 6        | 2.25%   |
| Intel Core i5-4590 CPU @ 3.30GHz     | 6        | 2.25%   |
| Intel Core i5-4570TE CPU @ 2.70GHz   | 4        | 1.5%    |
| Intel Core i3-2100 CPU @ 3.10GHz     | 4        | 1.5%    |
| AMD GX-412TC SOC                     | 4        | 1.5%    |
| Intel Xeon                           | 3        | 1.12%   |
| Intel Pentium Silver N6005 @ 2.00GHz | 3        | 1.12%   |
| Intel Pentium CPU G4560 @ 3.50GHz    | 3        | 1.12%   |
| Intel Core i7-9700K CPU @ 3.60GHz    | 3        | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz     | 3        | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 3        | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz     | 3        | 1.12%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz | 3        | 1.12%   |
| Intel Celeron J6413 @ 1.80GHz        | 3        | 1.12%   |
| AMD Ryzen 5 2600 Six-Core Processor  | 3        | 1.12%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 2        | 0.75%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz  | 2        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz     | 2        | 0.75%   |
| Intel Core i7-4790K CPU @ 4.00GHz    | 2        | 0.75%   |
| Intel Core i5-8400 CPU @ 2.80GHz     | 2        | 0.75%   |
| Intel Core i5-4670 CPU @ 3.40GHz     | 2        | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz     | 2        | 0.75%   |
| Intel Core i5-3470T CPU @ 2.90GHz    | 2        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 2        | 0.75%   |
| Intel Core i5-2500 CPU @ 3.30GHz     | 2        | 0.75%   |
| Intel Core i3-6100T CPU @ 3.20GHz    | 2        | 0.75%   |
| Intel Core i3-4030U CPU @ 1.90GHz    | 2        | 0.75%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 2        | 0.75%   |
| Intel Celeron N5100 @ 1.10GHz        | 2        | 0.75%   |
| Intel Celeron J4105 CPU @ 1.50GHz    | 2        | 0.75%   |
| Intel Celeron CPU J3455 @ 1.50GHz    | 2        | 0.75%   |
| Intel Celeron CPU J1900 @ 1.99GHz    | 2        | 0.75%   |
| AMD Ryzen 9 7950X 16-Core Processor  | 2        | 0.75%   |
| AMD FX-8350 Eight-Core Processor     | 2        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 68       | 25.56%  |
| Intel Celeron           | 49       | 18.42%  |
| Intel Xeon              | 22       | 8.27%   |
| Intel Core i3           | 22       | 8.27%   |
| Intel Core i7           | 21       | 7.89%   |
| Other                   | 8        | 3.01%   |
| Intel Atom              | 8        | 3.01%   |
| AMD Ryzen 5             | 7        | 2.63%   |
| Intel Pentium           | 6        | 2.26%   |
| AMD GX                  | 6        | 2.26%   |
| AMD FX                  | 6        | 2.26%   |
| Intel Core 2 Duo        | 5        | 1.88%   |
| AMD Ryzen 9             | 5        | 1.88%   |
| AMD Ryzen 7             | 4        | 1.5%    |
| Intel Pentium Silver    | 3        | 1.13%   |
| Intel Pentium Dual-Core | 3        | 1.13%   |
| Intel Core 2 Quad       | 3        | 1.13%   |
| AMD Athlon 64 X2        | 3        | 1.13%   |
| AMD Ryzen 3             | 2        | 0.75%   |
| Intel Pentium 4         | 1        | 0.38%   |
| Intel Core 2            | 1        | 0.38%   |
| AMD Ryzen Embedded      | 1        | 0.38%   |
| AMD Ryzen 5 PRO         | 1        | 0.38%   |
| AMD Phenom II X6        | 1        | 0.38%   |
| AMD Phenom              | 1        | 0.38%   |
| AMD G                   | 1        | 0.38%   |
| AMD EPYC                | 1        | 0.38%   |
| AMD E                   | 1        | 0.38%   |
| AMD Athlon II X2        | 1        | 0.38%   |
| AMD Athlon Dual Core    | 1        | 0.38%   |
| AMD Athlon              | 1        | 0.38%   |
| AMD A6                  | 1        | 0.38%   |
| AMD A4                  | 1        | 0.38%   |
| AMD A10                 | 1        | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 146      | 55.3%   |
| 2       | 58       | 21.97%  |
| 6       | 16       | 6.06%   |
| 8       | 14       | 5.3%    |
| 12      | 9        | 3.41%   |
| 32      | 5        | 1.89%   |
| 16      | 5        | 1.89%   |
| Unknown | 4        | 1.52%   |
| 10      | 3        | 1.14%   |
| 24      | 2        | 0.76%   |
| 11      | 1        | 0.38%   |
| 3       | 1        | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 255      | 98.46%  |
| 2       | 2        | 0.77%   |
| Unknown | 2        | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 175      | 67.31%  |
| 2       | 81       | 31.15%  |
| Unknown | 4        | 1.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 43       | 16.1%   |
| Unknown       | 31       | 11.61%  |
| KabyLake      | 25       | 9.36%   |
| IvyBridge     | 23       | 8.61%   |
| Silvermont    | 16       | 5.99%   |
| SandyBridge   | 15       | 5.62%   |
| Skylake       | 14       | 5.24%   |
| Penryn        | 11       | 4.12%   |
| Goldmont plus | 10       | 3.75%   |
| Piledriver    | 8        | 3%      |
| Goldmont      | 8        | 3%      |
| Zen+          | 7        | 2.62%   |
| Westmere      | 6        | 2.25%   |
| Broadwell     | 6        | 2.25%   |
| Zen 3         | 5        | 1.87%   |
| Zen           | 5        | 1.87%   |
| Puma          | 4        | 1.5%    |
| K8 Hammer     | 4        | 1.5%    |
| K10           | 4        | 1.5%    |
| Jaguar        | 4        | 1.5%    |
| CometLake     | 4        | 1.5%    |
| Nehalem       | 3        | 1.12%   |
| Bonnell       | 3        | 1.12%   |
| Zen 2         | 2        | 0.75%   |
| Core          | 2        | 0.75%   |
| Bobcat        | 2        | 0.75%   |
| TigerLake     | 1        | 0.37%   |
| NetBurst      | 1        | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 172      | 66.67%  |
| Nvidia                     | 38       | 14.73%  |
| AMD                        | 35       | 13.57%  |
| ASPEED Technology          | 8        | 3.1%    |
| Matrox Electronics Systems | 5        | 1.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28       | 10.61%  |
| Intel JasperLake [UHD Graphics]                                                          | 19       | 7.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13       | 4.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12       | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12       | 4.55%   |
| Intel HD Graphics 530                                                                    | 11       | 4.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10       | 3.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8        | 3.03%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 8        | 3.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 1.89%   |
| Intel HD Graphics 630                                                                    | 5        | 1.89%   |
| Intel HD Graphics 500                                                                    | 5        | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5        | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 1.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.52%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4        | 1.52%   |
| Intel HD Graphics 610                                                                    | 4        | 1.52%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 4        | 1.52%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3        | 1.14%   |
| Intel UHD Graphics 620                                                                   | 3        | 1.14%   |
| Intel HD Graphics 620                                                                    | 3        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.14%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.76%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.76%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.76%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.76%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.76%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.76%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 0.76%   |
| AMD Raphael                                                                              | 2        | 0.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 0.76%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 0.76%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1        | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 161      | 60.75%  |
| 1 x Nvidia     | 36       | 13.58%  |
| 1 x AMD        | 31       | 11.7%   |
| Other          | 11       | 4.15%   |
| 1 x ASPEED     | 8        | 3.02%   |
| 2 x Intel      | 7        | 2.64%   |
| 1 x Matrox     | 5        | 1.89%   |
| 2 x AMD        | 3        | 1.13%   |
| Intel + Nvidia | 2        | 0.75%   |
| Intel + AMD    | 1        | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 230      | 87.12%  |
| Proprietary | 22       | 8.33%   |
| Unknown     | 12       | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 230      | 88.12%  |
| 1.01-2.0   | 8        | 3.07%   |
| 0.51-1.0   | 8        | 3.07%   |
| 7.01-8.0   | 4        | 1.53%   |
| 3.01-4.0   | 4        | 1.53%   |
| 5.01-6.0   | 3        | 1.15%   |
| 8.01-16.0  | 2        | 0.77%   |
| 2.01-3.0   | 1        | 0.38%   |
| 0.01-0.5   | 1        | 0.38%   |

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
| 0     | 208      | 79.09%  |
| 1     | 47       | 17.87%  |
| 2     | 8        | 3.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 205      | 57.58%  |
| Realtek Semiconductor           | 99       | 27.81%  |
| Broadcom                        | 17       | 4.78%   |
| Qualcomm Atheros                | 8        | 2.25%   |
| MediaTek                        | 4        | 1.12%   |
| Solarflare Communications       | 3        | 0.84%   |
| Ralink                          | 2        | 0.56%   |
| Mellanox Technologies           | 2        | 0.56%   |
| Marvell Technology Group        | 2        | 0.56%   |
| Chelsio Communications          | 2        | 0.56%   |
| 3Com                            | 2        | 0.56%   |
| Qualcomm Atheros Communications | 1        | 0.28%   |
| NetGear                         | 1        | 0.28%   |
| Linksys                         | 1        | 0.28%   |
| IMC Networks                    | 1        | 0.28%   |
| Hewlett-Packard                 | 1        | 0.28%   |
| Google                          | 1        | 0.28%   |
| D-Link System                   | 1        | 0.28%   |
| Aquantia                        | 1        | 0.28%   |
| Apple                           | 1        | 0.28%   |
| American Megatrends             | 1        | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 83       | 18.99%  |
| Intel I211 Gigabit Network Connection                                         | 32       | 7.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 23       | 5.26%   |
| Intel 82574L Gigabit Network Connection                                       | 23       | 5.26%   |
| Intel Ethernet Connection I217-LM                                             | 22       | 5.03%   |
| Intel Ethernet Controller I226-V                                              | 15       | 3.43%   |
| Intel Ethernet Controller I225-V                                              | 15       | 3.43%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 2.97%   |
| Intel 82583V Gigabit Network Connection                                       | 10       | 2.29%   |
| Intel 82576 Gigabit Network Connection                                        | 10       | 2.29%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 1.83%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 1.83%   |
| Intel Wi-Fi 6 AX200                                                           | 7        | 1.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.6%    |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.14%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4        | 0.92%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 0.92%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.69%   |
| Intel Wireless 7260                                                           | 3        | 0.69%   |
| Intel Wireless 3165                                                           | 3        | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 3        | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.69%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.69%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.46%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2        | 0.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 2        | 0.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 0.46%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.46%   |
| Intel Ethernet Controller X550                                                | 2        | 0.46%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.46%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.46%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 49.02%  |
| Realtek Semiconductor           | 8        | 15.69%  |
| Qualcomm Atheros                | 6        | 11.76%  |
| MediaTek                        | 4        | 7.84%   |
| Ralink                          | 2        | 3.92%   |
| Broadcom                        | 2        | 3.92%   |
| Qualcomm Atheros Communications | 1        | 1.96%   |
| NetGear                         | 1        | 1.96%   |
| Linksys                         | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 7        | 13.21%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4        | 7.55%   |
| Intel Wireless 7260                                                     | 3        | 5.66%   |
| Intel Wireless 3165                                                     | 3        | 5.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 3        | 5.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2        | 3.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2        | 3.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2        | 3.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1        | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.89%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1        | 1.89%   |
| Realtek Bluetooth Adapter                                               | 1        | 1.89%   |
| Ralink RT5592 PCIe Wireless Network Adapter                             | 1        | 1.89%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                    | 1        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1        | 1.89%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1        | 1.89%   |
| Qualcomm Atheros AR958x 802.11abgn Wireless Network Adapter             | 1        | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1        | 1.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1        | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 1.89%   |
| NetGear A6200 802.11a/b/g/n/ac Wireless Adapter [Broadcom BCM43526]     | 1        | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1        | 1.89%   |
| Linksys WUSB54G v4 802.11g Adapter [Ralink RT2500USB]                   | 1        | 1.89%   |
| Intel Wireless 8260                                                     | 1        | 1.89%   |
| Intel Wireless 7265                                                     | 1        | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1        | 1.89%   |
| Intel Centrino Wireless-N 105                                           | 1        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1        | 1.89%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 1        | 1.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1        | 1.89%   |
| Broadcom BCM4321 802.11b/g/n                                            | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 194      | 60.63%  |
| Realtek Semiconductor     | 95       | 29.69%  |
| Broadcom                  | 15       | 4.69%   |
| Solarflare Communications | 3        | 0.94%   |
| Qualcomm Atheros          | 2        | 0.63%   |
| Marvell Technology Group  | 2        | 0.63%   |
| Chelsio Communications    | 2        | 0.63%   |
| 3Com                      | 2        | 0.63%   |
| Google                    | 1        | 0.31%   |
| D-Link System             | 1        | 0.31%   |
| Aquantia                  | 1        | 0.31%   |
| Apple                     | 1        | 0.31%   |
| American Megatrends       | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 83       | 21.9%   |
| Intel I211 Gigabit Network Connection                                         | 32       | 8.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 23       | 6.07%   |
| Intel 82574L Gigabit Network Connection                                       | 23       | 6.07%   |
| Intel Ethernet Connection I217-LM                                             | 22       | 5.8%    |
| Intel Ethernet Controller I226-V                                              | 15       | 3.96%   |
| Intel Ethernet Controller I225-V                                              | 15       | 3.96%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 3.43%   |
| Intel 82583V Gigabit Network Connection                                       | 10       | 2.64%   |
| Intel 82576 Gigabit Network Connection                                        | 10       | 2.64%   |
| Intel I210 Gigabit Network Connection                                         | 9        | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8        | 2.11%   |
| Intel 82580 Gigabit Network Connection                                        | 8        | 2.11%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7        | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 1.32%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 5        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                          | 4        | 1.06%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4        | 1.06%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3        | 0.79%   |
| Intel Ethernet Connection (5) I219-LM                                         | 3        | 0.79%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3        | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.79%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3        | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 3        | 0.79%   |
| Solarflare SFC9020 10G Ethernet Controller                                    | 2        | 0.53%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 2        | 0.53%   |
| Intel Ethernet Controller X550                                                | 2        | 0.53%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2        | 0.53%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 0.53%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 0.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 0.53%   |
| Intel 82599 10 Gigabit Network Connection                                     | 2        | 0.53%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.53%   |
| Intel 82575GB Gigabit Network Connection                                      | 2        | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.53%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                 | 2        | 0.53%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 257      | 82.37%  |
| WiFi     | 50       | 16.03%  |
| Unknown  | 4        | 1.28%   |
| Modem    | 1        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 249      | 96.51%  |
| WiFi     | 9        | 3.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 60       | 22.81%  |
| 2     | 60       | 22.81%  |
| 3     | 46       | 17.49%  |
| 1     | 46       | 17.49%  |
| 5     | 22       | 8.37%   |
| 6     | 17       | 6.46%   |
| 7     | 4        | 1.52%   |
| 8     | 3        | 1.14%   |
| 0     | 3        | 1.14%   |
| 10    | 1        | 0.38%   |
| 9     | 1        | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 225      | 85.23%  |
| Yes  | 39       | 14.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 57.14%  |
| Cambridge Silicon Radio         | 5        | 14.29%  |
| Foxconn / Hon Hai               | 3        | 8.57%   |
| Realtek Semiconductor           | 2        | 5.71%   |
| IMC Networks                    | 2        | 5.71%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| MediaTek                        | 1        | 2.86%   |
| Apple                           | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                   | 6        | 16.67%  |
| Intel AX200 Bluetooth                                | 6        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 5        | 13.89%  |
| Intel Wireless-AC 3168 Bluetooth                     | 4        | 11.11%  |
| Intel AX201 Bluetooth                                | 2        | 5.56%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter            | 2        | 5.56%   |
| Realtek  Bluetooth 4.2 Adapter                       | 1        | 2.78%   |
| Realtek Bluetooth Adapter                            | 1        | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 1        | 2.78%   |
| MediaTek RZ608 Bluetooth Adapter                     | 1        | 2.78%   |
| Intel Wireless Bluetooth                             | 1        | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 1        | 2.78%   |
| Intel AX210 Bluetooth                                | 1        | 2.78%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 2.78%   |
| IMC Networks MediaTek Bluetooth Adapter              | 1        | 2.78%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 1        | 2.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 165      | 62.98%  |
| AMD                      | 44       | 16.79%  |
| Nvidia                   | 37       | 14.12%  |
| Logitech                 | 3        | 1.15%   |
| C-Media Electronics      | 3        | 1.15%   |
| KTMicro                  | 2        | 0.76%   |
| ASUSTek Computer         | 2        | 0.76%   |
| Yamaha                   | 1        | 0.38%   |
| Texas Instruments        | 1        | 0.38%   |
| SteelSeries ApS          | 1        | 0.38%   |
| Micro Star International | 1        | 0.38%   |
| Elgato Systems           | 1        | 0.38%   |
| Creative Labs            | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27       | 8.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26       | 8.28%   |
| Intel Jasper Lake HD Audio                                                                        | 19       | 6.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16       | 5.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12       | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12       | 3.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 9        | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8        | 2.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7        | 2.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7        | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 1.91%   |
| AMD FCH Azalia Controller                                                                         | 6        | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 1.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5        | 1.59%   |
| Intel 8 Series HD Audio Controller                                                                | 5        | 1.59%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5        | 1.59%   |
| Nvidia High Definition Audio Controller                                                           | 4        | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4        | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4        | 1.27%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 4        | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 4        | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4        | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4        | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 1.27%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3        | 0.96%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 0.96%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 0.96%   |
| Nvidia MCP61 High Definition Audio                                                                | 2        | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2        | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.64%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2        | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 49       | 16.67%  |
| Samsung Electronics          | 42       | 14.29%  |
| SK hynix                     | 39       | 13.27%  |
| Unknown                      | 26       | 8.84%   |
| Corsair                      | 26       | 8.84%   |
| Crucial                      | 25       | 8.5%    |
| G.Skill                      | 19       | 6.46%   |
| Micron Technology            | 16       | 5.44%   |
| Unknown                      | 9        | 3.06%   |
| Apacer                       | 5        | 1.7%    |
| A-DATA Technology            | 5        | 1.7%    |
| Team                         | 4        | 1.36%   |
| Ramaxel Technology           | 4        | 1.36%   |
| Unknown (0x0C26)             | 3        | 1.02%   |
| Patriot                      | 3        | 1.02%   |
| OCZ                          | 3        | 1.02%   |
| Nanya Technology             | 3        | 1.02%   |
| TIMETEC                      | 2        | 0.68%   |
| V-Color                      | 1        | 0.34%   |
| Unknown (ABCD)               | 1        | 0.34%   |
| Unknown (0x0DD5)             | 1        | 0.34%   |
| Transcend                    | 1        | 0.34%   |
| Toshiba                      | 1        | 0.34%   |
| Silicon Power                | 1        | 0.34%   |
| PNY                          | 1        | 0.34%   |
| Patriot Memory (PDP Systems) | 1        | 0.34%   |
| Lexar Co Limited             | 1        | 0.34%   |
| Cors                         | 1        | 0.34%   |
| Avant                        | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown                                                   | 9        | 2.82%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 5        | 1.57%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s   | 5        | 1.57%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 4        | 1.25%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s       | 4        | 1.25%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s       | 4        | 1.25%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 3        | 0.94%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 3        | 0.94%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 3        | 0.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 3        | 0.94%   |
| Unknown RAM Module 8GB 1600MT/s                           | 2        | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 2        | 0.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 0.63%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 2        | 0.63%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                | 2        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s      | 2        | 0.63%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s      | 2        | 0.63%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s      | 2        | 0.63%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s      | 2        | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2        | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s       | 2        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s       | 2        | 0.63%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 0.63%   |
| Micron RAM 9ASF51272PZ-2G1A2 4GB RIMM DDR4 2133MT/s       | 2        | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 2        | 0.63%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 2        | 0.63%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s        | 2        | 0.63%   |
| Crucial RAM CT8G4SFRA32A.M4FF 8GB SODIMM DDR4 3200MT/s    | 2        | 0.63%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s       | 2        | 0.63%   |
| Corsair RAM CMV8GX3M1A1333C9 8GB DIMM DDR3 1333MT/s       | 2        | 0.63%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s       | 2        | 0.63%   |
| Corsair RAM CMSX32GX4M2A3200C22 16GB SODIMM DDR4 3200MT/s | 2        | 0.63%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 0.63%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s    | 2        | 0.63%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s    | 2        | 0.63%   |
| V-Color RAM VCOLOR-TD2G16C9-H8 2GB DIMM 1333MT/s          | 1        | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR4 2666MT/s                 | 1        | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                 | 1        | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 115      | 45.82%  |
| DDR4    | 103      | 41.04%  |
| DDR2    | 11       | 4.38%   |
| Unknown | 11       | 4.38%   |
| SDRAM   | 4        | 1.59%   |
| DDR5    | 3        | 1.2%    |
| LPDDR4  | 2        | 0.8%    |
| DDR     | 2        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 168      | 68.29%  |
| SODIMM  | 73       | 29.67%  |
| RIMM    | 3        | 1.22%   |
| Unknown | 2        | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 93       | 33.7%   |
| 4096  | 90       | 32.61%  |
| 2048  | 38       | 13.77%  |
| 16384 | 36       | 13.04%  |
| 1024  | 11       | 3.99%   |
| 32768 | 7        | 2.54%   |
| 512   | 1        | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 86       | 31.62%  |
| 1333    | 38       | 13.97%  |
| 3200    | 28       | 10.29%  |
| 2400    | 25       | 9.19%   |
| 2667    | 23       | 8.46%   |
| 2133    | 21       | 7.72%   |
| 800     | 11       | 4.04%   |
| 2666    | 7        | 2.57%   |
| 667     | 5        | 1.84%   |
| 1067    | 4        | 1.47%   |
| Unknown | 4        | 1.47%   |
| 3600    | 3        | 1.1%    |
| 3000    | 3        | 1.1%    |
| 1066    | 3        | 1.1%    |
| 4800    | 2        | 0.74%   |
| 1866    | 2        | 0.74%   |
| 400     | 2        | 0.74%   |
| 6400    | 1        | 0.37%   |
| 5200    | 1        | 0.37%   |
| 3400    | 1        | 0.37%   |
| 1334    | 1        | 0.37%   |
| 333     | 1        | 0.37%   |

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
| 1     | 156      | 58.65%  |
| 0     | 73       | 27.44%  |
| 2     | 27       | 10.15%  |
| 3     | 7        | 2.63%   |
| 4     | 3        | 1.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 170      | 75.56%  |
| Net/wireless             | 18       | 8%      |
| Bluetooth                | 12       | 5.33%   |
| Firewire controller      | 6        | 2.67%   |
| Sound                    | 5        | 2.22%   |
| Net/ethernet             | 5        | 2.22%   |
| Network                  | 3        | 1.33%   |
| Card reader              | 3        | 1.33%   |
| Storage/raid             | 2        | 0.89%   |
| Graphics card            | 1        | 0.44%   |

