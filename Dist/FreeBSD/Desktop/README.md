FreeBSD - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 1657

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [65092dde79](https://bsd-hardware.info/?probe=65092dde79) | Aug 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| MSI           | H81M-P33                    | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| ASRock        | B550 PG Velocita            | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| HP            | 8298                        | [961bfad69a](https://bsd-hardware.info/?probe=961bfad69a) | Aug 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [be9b9caa66](https://bsd-hardware.info/?probe=be9b9caa66) | Jul 31, 2023 |
| ASUSTek       | PRIME A320I-K               | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| MSI           | H81M-P33                    | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| ASUSTek       | P8P67                       | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| Dell          | 0PTTT9 A01                  | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| MSI           | H81M-P33                    | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| Unknown       | Unknown                     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| Intel         | HM570                       | [a9abbf1e12](https://bsd-hardware.info/?probe=a9abbf1e12) | Jul 15, 2023 |
| Unknown       | Unknown                     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [d0f09cc8c4](https://bsd-hardware.info/?probe=d0f09cc8c4) | Jul 11, 2023 |
| ASRock        | Z690 PG Riptide             | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| MSI           | H81M-P33                    | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| HP            | 3397                        | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Dell          | 0PTTT9 A01                  | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | [e0d3f841c7](https://bsd-hardware.info/?probe=e0d3f841c7) | Jul 07, 2023 |
| MSI           | H510I PRO WIFI              | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| ASRock        | Z690 PG Riptide             | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| HP            | 82F2 A01                    | [a77d73b637](https://bsd-hardware.info/?probe=a77d73b637) | Jul 04, 2023 |
| ASUSTek       | PRIME H510M-A               | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Gigabyte      | M85M-US2H                   | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| MSI           | H81M-P33                    | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| Gigabyte      | B360M D2V                   | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [6479d60da2](https://bsd-hardware.info/?probe=6479d60da2) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Unknown       | Unknown                     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| MSI           | H81M-P33                    | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASUSTek       | P5K PRO                     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Unknown       | Unknown                     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Unknown       | Unknown                     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| MSI           | H81M-P33                    | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | [7e0151a93f](https://bsd-hardware.info/?probe=7e0151a93f) | Jun 10, 2023 |
| ASRock        | Z590 Pro4                   | [d04a63aa31](https://bsd-hardware.info/?probe=d04a63aa31) | Jun 06, 2023 |
| HP            | 212B                        | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| MSI           | H81M-P33                    | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| ASRock        | Z590 Pro4                   | [314d462dcd](https://bsd-hardware.info/?probe=314d462dcd) | Jun 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [2445651c96](https://bsd-hardware.info/?probe=2445651c96) | May 31, 2023 |
| ASRock        | Z590 Pro4                   | [a9b9a2e045](https://bsd-hardware.info/?probe=a9b9a2e045) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | [e63f1f4874](https://bsd-hardware.info/?probe=e63f1f4874) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | [382fe30ec1](https://bsd-hardware.info/?probe=382fe30ec1) | May 28, 2023 |
| Gigabyte      | H170-D3HP-CF                | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| ASUSTek       | PRIME A520M-A II            | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| MSI           | H81M-P33                    | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| HP            | 158B                        | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| ASUSTek       | PRO B460M-C                 | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Gigabyte      | H170-D3HP-CF                | [830100249f](https://bsd-hardware.info/?probe=830100249f) | May 17, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| ASRock        | Z790M-ITX WiFi              | [3bf2cd6d1e](https://bsd-hardware.info/?probe=3bf2cd6d1e) | May 14, 2023 |
| MSI           | B450M MORTAR                | [7d0fe109f0](https://bsd-hardware.info/?probe=7d0fe109f0) | May 14, 2023 |
| MSI           | B85M-G43                    | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| MSI           | H81M-P33                    | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| HP            | 802F                        | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Unknown       | Unknown                     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| MSI           | H81M-P33                    | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| HP            | 805D                        | [648c680432](https://bsd-hardware.info/?probe=648c680432) | May 07, 2023 |
| ASUSTek       | P5K SE/EPU                  | [4cde43ac30](https://bsd-hardware.info/?probe=4cde43ac30) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 1589                        | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Unknown       | HX90                        | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| GVC           | DR 738                      | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| Gigabyte      | B360M D2V                   | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| MSI           | H81M-P33                    | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| ASUSTek       | P8H77-V                     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| HP            | 158B                        | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| ASUSTek       | Pro B560M-C                 | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Lenovo        | YangTianM6880N              | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| MSI           | H81M-P33                    | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-A II             | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| Unknown       | Unknown                     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| HP            | 212B                        | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| MSI           | H81M-P33                    | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Unknown       | Unknown                     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| ASUSTek       | PRIME B450M-K II            | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| ASRock        | X570S PG Riptide            | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | H81M-P33                    | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| HP            | 1497                        | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| HP            | 1497                        | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| HP            | 3397                        | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| ASRock        | B550M Pro4                  | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| GVC           | DR 738                      | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | 3397                        | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | PRIME X370-PRO              | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| HP            | 0AA8h                       | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| ASUSTek       | PRO B460M-C                 | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| ASRock        | H470M-STX                   | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Dell          | 0HHV7N A00                  | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| MSI           | H81M-P33                    | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| ASRock        | X570 Taichi                 | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| HP            | 212B                        | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| MSI           | H81M-P33                    | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| ASUSTek       | PRIME H410M-K               | [d2edba8775](https://bsd-hardware.info/?probe=d2edba8775) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| MSI           | B450M MORTAR MAX            | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| MSI           | H81M-P33                    | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [6d46662662](https://bsd-hardware.info/?probe=6d46662662) | Jan 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Dell          | 08NPPY A00                  | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Shuttle       | DS20U                       | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| IBM           | 9210MML                     | [8b7e2413ee](https://bsd-hardware.info/?probe=8b7e2413ee) | Jan 25, 2023 |
| ADI Engine... | RCC-VE                      | [e2941c00fc](https://bsd-hardware.info/?probe=e2941c00fc) | Jan 25, 2023 |
| ASUSTek       | P5Q-E                       | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| MSI           | H81M-P33                    | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| MSI           | H81M-P33                    | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| MSI           | MEG Z690 UNIFY-X            | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| MSI           | H81M-P33                    | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| HP            | ProLiant MicroServer        | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Supermicro    | X9DR3-F                     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Dell          | 09KPNV A01                  | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| ASRock        | B660M-ITX/ac                | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| BESSTAR Te... | UM350                       | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| HP            | ProLiant MicroServer        | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Biostar       | A68N-5600E                  | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| MSI           | H81M-P33                    | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| HP            | 82A2                        | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| MSI           | H81M-P33                    | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| MSI           | H81M-P33                    | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| ASRock        | B450M-HDV                   | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| MSI           | H81M-P33                    | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| TOPFEEL       | H110D4-P1                   | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| MSI           | B450M MORTAR MAX            | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| HP            | 21B4 A01                    | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| MSI           | H81M-P33                    | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Gigabyte      | Z97X-UD5H                   | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| MSI           | H81M-P33                    | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| Unknown       | Unknown                     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| HP            | 1589                        | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| ASRock        | X399 Taichi                 | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| ASRockRack    | EP2C612D16FM                | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| IBM           | 9210MML                     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| HPE           | ProLiant ML30 Gen10         | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| HP            | 212B                        | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| MSI           | A520M-A PRO                 | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Pegatron      | H81-X1                      | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| MSI           | Z490-A PRO                  | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Gigabyte      | H410M S2 V2                 | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| ASUSTek       | P5Q-E                       | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASRockRack    | X470D4U2/1N1                | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| MSI           | H81M-P33                    | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Dell          | 07T4MC A09                  | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | H81M-DS2                    | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Dell          | 07T4MC A00                  | [1060f1b6e3](https://bsd-hardware.info/?probe=1060f1b6e3) | Aug 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5684672f5a](https://bsd-hardware.info/?probe=5684672f5a) | Aug 26, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| MSI           | H81M-P33                    | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| ASRock        | B550 Extreme4               | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| Gigabyte      | H61M-DS2                    | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| ASUSTek       | M4A87TD EVO                 | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| Unknown       | Unknown                     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| MSI           | H81M-P33                    | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| ASRock        | X399 Taichi                 | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| GVC           | DR 738                      | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Gigabyte      | P85-D3                      | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| HP            | 1825                        | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Gigabyte      | H61M-DS2                    | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Gigabyte      | H310M S2 x.x                | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Acer          | Veriton X490G               | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| MouseCompu... | B360M                       | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Acer          | Veriton X490G               | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| ASRock        | B75 Pro3                    | [7f4fa7f74d](https://bsd-hardware.info/?probe=7f4fa7f74d) | Jul 10, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| ASRock        | Z490M Pro4                  | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| ASRock        | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| ASUSTek       | PRIME Z590-P                | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| HP            | 86E9 A                      | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| Dell          | 0HMF7C A01                  | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| MSI           | Z590 PRO WIFI               | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [1cc3d99da5](https://bsd-hardware.info/?probe=1cc3d99da5) | May 31, 2022 |
| NF-M2S        | ABIT                        | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| Unknown       | Unknown                     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| PC Engines    | APU3                        | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Unknown       | Unknown                     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| Unknown       | Unknown                     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| HP            | 158A                        | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| Dell          | 055H3G A01                  | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| khadas        | edge-v                      | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [443b1d3c3e](https://bsd-hardware.info/?probe=443b1d3c3e) | May 22, 2022 |
| MSI           | H81M-P33                    | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| GVC           | DR 738                      | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| Gigabyte      | H61MA-D3V                   | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Dell          | 07T4MC A11                  | [63d6080a31](https://bsd-hardware.info/?probe=63d6080a31) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| ASRock        | E350M1                      | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| MSI           | MS-7369                     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Unknown       | Unknown                     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Intel         | DH67BL AAG10189-213         | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| HP            | ProLiant MicroServer        | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| ASRock        | A320M Pro4-F                | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| ASUSTek       | H97I-PLUS                   | [1fde9daf7d](https://bsd-hardware.info/?probe=1fde9daf7d) | May 01, 2022 |
| HP            | 1495                        | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Gigabyte      | H310M S2 x.x                | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| Dell          | 0T7D40 A01                  | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| MSI           | X570-A PRO                  | [89fcee49d9](https://bsd-hardware.info/?probe=89fcee49d9) | Apr 22, 2022 |
| HP            | 2820h                       | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [28c8d07136](https://bsd-hardware.info/?probe=28c8d07136) | Apr 22, 2022 |
| Dell          | 06JWJY A01                  | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| Dell          | 0T7D40 A01                  | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| Gigabyte      | N3160ND3V                   | [eb3d850e0a](https://bsd-hardware.info/?probe=eb3d850e0a) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | [0a550ec649](https://bsd-hardware.info/?probe=0a550ec649) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | [c1e6f095a8](https://bsd-hardware.info/?probe=c1e6f095a8) | Apr 17, 2022 |
| Shuttle       | DS20U                       | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| Shuttle       | SH570                       | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| ASUSTek       | AT5NM10T-I                  | [211c3291dd](https://bsd-hardware.info/?probe=211c3291dd) | Apr 15, 2022 |
| HP            | 86E9 A                      | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [f6bc20d345](https://bsd-hardware.info/?probe=f6bc20d345) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [bb9129d4df](https://bsd-hardware.info/?probe=bb9129d4df) | Apr 13, 2022 |
| Intel         | DH67CL AAG10212-205         | [ecbb820987](https://bsd-hardware.info/?probe=ecbb820987) | Apr 12, 2022 |
| Alienware     | 049PDM A00                  | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| MSI           | H81M-P33                    | [52abbcbc5b](https://bsd-hardware.info/?probe=52abbcbc5b) | Apr 10, 2022 |
| ASUSTek       | P5Q-E                       | [0cbb5faa2e](https://bsd-hardware.info/?probe=0cbb5faa2e) | Apr 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5d759d6436](https://bsd-hardware.info/?probe=5d759d6436) | Apr 10, 2022 |
| Intel         | DH67CL AAG10212-205         | [de2cd29be6](https://bsd-hardware.info/?probe=de2cd29be6) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | [2a03c05cce](https://bsd-hardware.info/?probe=2a03c05cce) | Apr 10, 2022 |
| Intel         | DH61CR AAG14064-204         | [fa4b6b0257](https://bsd-hardware.info/?probe=fa4b6b0257) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [4436915ba0](https://bsd-hardware.info/?probe=4436915ba0) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-210         | [a01376dfc5](https://bsd-hardware.info/?probe=a01376dfc5) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [85a5d08117](https://bsd-hardware.info/?probe=85a5d08117) | Apr 09, 2022 |
| Intel         | DH67BL AAG10189-211         | [689ff6c484](https://bsd-hardware.info/?probe=689ff6c484) | Apr 09, 2022 |
| Intel         | DH55TC AAE70932-302         | [b9a45002ae](https://bsd-hardware.info/?probe=b9a45002ae) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [68f10ed8de](https://bsd-hardware.info/?probe=68f10ed8de) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | [092643d1c3](https://bsd-hardware.info/?probe=092643d1c3) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | [02b581994b](https://bsd-hardware.info/?probe=02b581994b) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [840805d1fa](https://bsd-hardware.info/?probe=840805d1fa) | Apr 08, 2022 |
| Gigabyte      | B450M S2H                   | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| MSI           | MAG B550M MORTAR            | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2d04e83ea4](https://bsd-hardware.info/?probe=2d04e83ea4) | Apr 06, 2022 |
| ASRock        | AM1H-ITX                    | [5556bf474c](https://bsd-hardware.info/?probe=5556bf474c) | Apr 06, 2022 |
| Unknown       | Unknown                     | [821456e342](https://bsd-hardware.info/?probe=821456e342) | Apr 06, 2022 |
| Unknown       | Unknown                     | [6955791aa5](https://bsd-hardware.info/?probe=6955791aa5) | Apr 06, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| HP            | 212B                        | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1043649da9](https://bsd-hardware.info/?probe=1043649da9) | Apr 03, 2022 |
| MSI           | H81M-P33                    | [b0d11aabb7](https://bsd-hardware.info/?probe=b0d11aabb7) | Apr 03, 2022 |
| ASUSTek       | P5Q-E                       | [dbaaa0dcda](https://bsd-hardware.info/?probe=dbaaa0dcda) | Apr 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| HP            | 158A                        | [5d463584db](https://bsd-hardware.info/?probe=5d463584db) | Mar 31, 2022 |
| ASUSTek       | PRO B460M-C                 | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| ASUSTek       | D700SA                      | [e0d66ad9cf](https://bsd-hardware.info/?probe=e0d66ad9cf) | Mar 28, 2022 |
| MSI           | H81M-P33                    | [823d2d7336](https://bsd-hardware.info/?probe=823d2d7336) | Mar 27, 2022 |
| ASUSTek       | P5Q-E                       | [4e44bfd765](https://bsd-hardware.info/?probe=4e44bfd765) | Mar 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [51507583f6](https://bsd-hardware.info/?probe=51507583f6) | Mar 27, 2022 |
| ASUSTek       | P5KPL-CM                    | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| MSI           | MS-A6221 100                | [ba62f48990](https://bsd-hardware.info/?probe=ba62f48990) | Mar 23, 2022 |
| ASUSTek       | M4A78T-E                    | [7c46c8e712](https://bsd-hardware.info/?probe=7c46c8e712) | Mar 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4a9a28c612](https://bsd-hardware.info/?probe=4a9a28c612) | Mar 22, 2022 |
| ASRock        | H61M-VG3                    | [543bcf2d09](https://bsd-hardware.info/?probe=543bcf2d09) | Mar 22, 2022 |
| ASUSTek       | PRO B460M-C                 | [6ceff4eca1](https://bsd-hardware.info/?probe=6ceff4eca1) | Mar 21, 2022 |
| Unknown       | Unknown                     | [c4ffde79eb](https://bsd-hardware.info/?probe=c4ffde79eb) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [2aeeaaacfc](https://bsd-hardware.info/?probe=2aeeaaacfc) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | [4b6df22ff5](https://bsd-hardware.info/?probe=4b6df22ff5) | Mar 20, 2022 |
| MSI           | H81M-P33                    | [d9421c2715](https://bsd-hardware.info/?probe=d9421c2715) | Mar 20, 2022 |
| ASUSTek       | P5Q-E                       | [5a6cb7ab07](https://bsd-hardware.info/?probe=5a6cb7ab07) | Mar 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [12814be80b](https://bsd-hardware.info/?probe=12814be80b) | Mar 20, 2022 |
| ASUSTek       | PRIME Z590-P                | [054946738a](https://bsd-hardware.info/?probe=054946738a) | Mar 19, 2022 |
| ASUSTek       | PRIME B350M-A               | [753af67ffa](https://bsd-hardware.info/?probe=753af67ffa) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6d4ac7f6f5](https://bsd-hardware.info/?probe=6d4ac7f6f5) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [3f94a005a7](https://bsd-hardware.info/?probe=3f94a005a7) | Mar 17, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| ASUSTek       | P5K PRO                     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| ASRock        | Q1900B-ITX                  | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Gigabyte      | C246-WU4-CF                 | [17b3590a3f](https://bsd-hardware.info/?probe=17b3590a3f) | Mar 08, 2022 |
| Intel         | DX79TO AAG28805-401         | [431b37f050](https://bsd-hardware.info/?probe=431b37f050) | Mar 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [0d2956a144](https://bsd-hardware.info/?probe=0d2956a144) | Mar 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| Intel         | D865PERL AAC27646-213       | [4e11b970ab](https://bsd-hardware.info/?probe=4e11b970ab) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| Supermicro    | A2SDi-LN4F                  | [b10f6655d9](https://bsd-hardware.info/?probe=b10f6655d9) | Mar 01, 2022 |
| MSI           | B365M PRO-VDH               | [d45ca02f84](https://bsd-hardware.info/?probe=d45ca02f84) | Feb 24, 2022 |
| MSI           | MAG B550M BAZOOKA           | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| Shuttle       | FZ270                       | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| MSI           | MAG B550M BAZOOKA           | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| GALAX         | B365M G10b                  | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| ASRock        | A88M-G                      | [14fcd1e849](https://bsd-hardware.info/?probe=14fcd1e849) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [0f3ee4caab](https://bsd-hardware.info/?probe=0f3ee4caab) | Feb 18, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | [e506cf84f4](https://bsd-hardware.info/?probe=e506cf84f4) | Feb 15, 2022 |
| Supermicro    | X9SCL/X9SCM                 | [2b58423bfe](https://bsd-hardware.info/?probe=2b58423bfe) | Feb 15, 2022 |
| Biostar       | X470GTA                     | [b7fc5ef684](https://bsd-hardware.info/?probe=b7fc5ef684) | Feb 12, 2022 |
| MSI           | H81M-P33                    | [5b4505d25e](https://bsd-hardware.info/?probe=5b4505d25e) | Feb 11, 2022 |
| ASUSTek       | P5Q-E                       | [42c29744d6](https://bsd-hardware.info/?probe=42c29744d6) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1b042ff2e0](https://bsd-hardware.info/?probe=1b042ff2e0) | Feb 11, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | [3c315d0c15](https://bsd-hardware.info/?probe=3c315d0c15) | Feb 09, 2022 |
| ASRock        | X370 Gaming X               | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASUSTek       | PRIME Z270-P                | [ae4f0642fd](https://bsd-hardware.info/?probe=ae4f0642fd) | Feb 09, 2022 |
| Dell          | 0654JC A01                  | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| HP            | 0B54h D                     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Unknown       | Unknown                     | [8d38089ced](https://bsd-hardware.info/?probe=8d38089ced) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| Unknown       | Unknown                     | [12e979c82a](https://bsd-hardware.info/?probe=12e979c82a) | Feb 06, 2022 |
| HP            | 0B54h D                     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e41d9cff21](https://bsd-hardware.info/?probe=e41d9cff21) | Feb 06, 2022 |
| MSI           | H81M-P33                    | [049a615166](https://bsd-hardware.info/?probe=049a615166) | Feb 06, 2022 |
| ASUSTek       | P5Q-E                       | [5afa08fe32](https://bsd-hardware.info/?probe=5afa08fe32) | Feb 06, 2022 |
| Gateway       | DX4870                      | [5035507c5c](https://bsd-hardware.info/?probe=5035507c5c) | Feb 05, 2022 |
| HP            | 802E                        | [e23b3e314a](https://bsd-hardware.info/?probe=e23b3e314a) | Feb 05, 2022 |
| Gateway       | DX4870                      | [1f31c4a99b](https://bsd-hardware.info/?probe=1f31c4a99b) | Feb 05, 2022 |
| ASUSTek       | P4P800-VM                   | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Dell          | 05DN3X A00                  | [edef5c789d](https://bsd-hardware.info/?probe=edef5c789d) | Feb 04, 2022 |
| Dell          | 0D28YY A02                  | [8eb27db8c9](https://bsd-hardware.info/?probe=8eb27db8c9) | Jan 31, 2022 |
| Dell          | 0J37VM A01                  | [47061377bd](https://bsd-hardware.info/?probe=47061377bd) | Jan 31, 2022 |
| Dell          | 0TK7TF A00                  | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e0c2a150f7](https://bsd-hardware.info/?probe=e0c2a150f7) | Jan 29, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| Kontron       | KT965/ATXP 61420000         | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| HP            | ProLiant MicroServer        | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| MSI           | G31TM-P21                   | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| ASUSTek       | P5M2                        | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a90b68e57b](https://bsd-hardware.info/?probe=a90b68e57b) | Jan 23, 2022 |
| MSI           | H81M-P33                    | [9d6207401e](https://bsd-hardware.info/?probe=9d6207401e) | Jan 23, 2022 |
| ASUSTek       | P5Q-E                       | [691f4c1a9a](https://bsd-hardware.info/?probe=691f4c1a9a) | Jan 23, 2022 |
| ASUSTek       | PRIME Z590-P                | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| MSI           | H81M-P33                    | [4cc0e9443d](https://bsd-hardware.info/?probe=4cc0e9443d) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7307e3e0be](https://bsd-hardware.info/?probe=7307e3e0be) | Jan 16, 2022 |
| ASUSTek       | P5Q-E                       | [d9f18d4d56](https://bsd-hardware.info/?probe=d9f18d4d56) | Jan 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8b55745b6f](https://bsd-hardware.info/?probe=8b55745b6f) | Jan 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [1d7c4c096e](https://bsd-hardware.info/?probe=1d7c4c096e) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Supermicro    | X7SBL                       | [c7d877a988](https://bsd-hardware.info/?probe=c7d877a988) | Jan 11, 2022 |
| Intel         | DH61CR AAG14064-210         | [15bb78bf9a](https://bsd-hardware.info/?probe=15bb78bf9a) | Jan 11, 2022 |
| Intel         | DQ35JO AAD82085-804         | [117b469a53](https://bsd-hardware.info/?probe=117b469a53) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| ASUSTek       | A68HM-PLUS                  | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [03252493ce](https://bsd-hardware.info/?probe=03252493ce) | Jan 09, 2022 |
| ASRock        | FM2A85X Extreme6            | [c87969f2d8](https://bsd-hardware.info/?probe=c87969f2d8) | Jan 09, 2022 |
| ASRock        | Z170M Extreme4              | [c518ded272](https://bsd-hardware.info/?probe=c518ded272) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2cc4698cbc](https://bsd-hardware.info/?probe=2cc4698cbc) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2481037b2a](https://bsd-hardware.info/?probe=2481037b2a) | Jan 09, 2022 |
| Gigabyte      | H470 HD3                    | [afa675e7a7](https://bsd-hardware.info/?probe=afa675e7a7) | Jan 08, 2022 |
| Intel         | DH67CL AAG10212-205         | [1b0837ff84](https://bsd-hardware.info/?probe=1b0837ff84) | Jan 08, 2022 |
| Gigabyte      | B150-HD3P-CF                | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Unknown       | Unknown                     | [7367c82ceb](https://bsd-hardware.info/?probe=7367c82ceb) | Jan 05, 2022 |
| Unknown       | Unknown                     | [54ba0d5236](https://bsd-hardware.info/?probe=54ba0d5236) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B550-PLUS        | [ea4719600a](https://bsd-hardware.info/?probe=ea4719600a) | Jan 05, 2022 |
| ASUSTek       | P8H67-M PRO                 | [d789a35c01](https://bsd-hardware.info/?probe=d789a35c01) | Jan 02, 2022 |
| MSI           | H81M-P33                    | [759c219ace](https://bsd-hardware.info/?probe=759c219ace) | Jan 02, 2022 |
| Unknown       | Unknown                     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [82256452fe](https://bsd-hardware.info/?probe=82256452fe) | Jan 01, 2022 |
| ASRock        | B450 Steel Legend           | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Unknown       | Unknown                     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| HP            | ProLiant MicroServer        | [d641a4bea9](https://bsd-hardware.info/?probe=d641a4bea9) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [d19f149583](https://bsd-hardware.info/?probe=d19f149583) | Dec 26, 2021 |
| Gigabyte      | P67A-D3-B3                  | [62f424cac5](https://bsd-hardware.info/?probe=62f424cac5) | Dec 26, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [afc3e2a972](https://bsd-hardware.info/?probe=afc3e2a972) | Dec 25, 2021 |
| Intel         | D54250WYK H13922-304        | [61acc33619](https://bsd-hardware.info/?probe=61acc33619) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| Purism        | Librem Mini v2              | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| ASUSTek       | X99-E-10G WS                | [dacf7f604c](https://bsd-hardware.info/?probe=dacf7f604c) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [69bf80f0c6](https://bsd-hardware.info/?probe=69bf80f0c6) | Dec 20, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [ef0dcfaccf](https://bsd-hardware.info/?probe=ef0dcfaccf) | Dec 20, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| Gigabyte      | X570 AORUS PRO              | [17cad87a0d](https://bsd-hardware.info/?probe=17cad87a0d) | Dec 19, 2021 |
| MSI           | MS-9852 10                  | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [848e618f87](https://bsd-hardware.info/?probe=848e618f87) | Dec 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [d46498baa7](https://bsd-hardware.info/?probe=d46498baa7) | Dec 13, 2021 |
| MSI           | H81M-P33                    | [fe193c863a](https://bsd-hardware.info/?probe=fe193c863a) | Dec 12, 2021 |
| Unknown       | Unknown                     | [b726a1b3e3](https://bsd-hardware.info/?probe=b726a1b3e3) | Dec 11, 2021 |
| ASUSTek       | PRIME X570-PRO              | [9a8d19aa04](https://bsd-hardware.info/?probe=9a8d19aa04) | Dec 11, 2021 |
| PC Engines    | apu4                        | [826a08be25](https://bsd-hardware.info/?probe=826a08be25) | Dec 11, 2021 |
| Unknown       | Unknown                     | [7633cb9296](https://bsd-hardware.info/?probe=7633cb9296) | Dec 11, 2021 |
| ASUSTek       | M5A99X EVO                  | [2e3b493ba3](https://bsd-hardware.info/?probe=2e3b493ba3) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [8a9387c5da](https://bsd-hardware.info/?probe=8a9387c5da) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | [9762ebd7c7](https://bsd-hardware.info/?probe=9762ebd7c7) | Dec 10, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [74538b669d](https://bsd-hardware.info/?probe=74538b669d) | Dec 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| MSI           | H81M-P33                    | [237b84b5fc](https://bsd-hardware.info/?probe=237b84b5fc) | Dec 09, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [3956ad0525](https://bsd-hardware.info/?probe=3956ad0525) | Dec 09, 2021 |
| Unknown       | Raspberry Pi 4 Model B R... | [5dbff17614](https://bsd-hardware.info/?probe=5dbff17614) | Dec 06, 2021 |
| Unknown       | Raspberry Pi 3 Model B P... | [646ca92a69](https://bsd-hardware.info/?probe=646ca92a69) | Dec 06, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [66ed413cab](https://bsd-hardware.info/?probe=66ed413cab) | Dec 05, 2021 |
| MSI           | X99S MPOWER                 | [ba0ac00cf6](https://bsd-hardware.info/?probe=ba0ac00cf6) | Dec 04, 2021 |
| ASUSTek       | P7P55D                      | [73373c3c65](https://bsd-hardware.info/?probe=73373c3c65) | Dec 04, 2021 |
| Unknown       | Unknown                     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| HP            | 0B54h D                     | [5186b81327](https://bsd-hardware.info/?probe=5186b81327) | Dec 02, 2021 |
| Dell          | 0Y5DDC A00                  | [888de14ef5](https://bsd-hardware.info/?probe=888de14ef5) | Dec 02, 2021 |
| ASRock        | B450 Steel Legend           | [f3a11b2c2d](https://bsd-hardware.info/?probe=f3a11b2c2d) | Dec 01, 2021 |
| ASUSTek       | P7P55D                      | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| MSI           | H81M-P33                    | [effc42884a](https://bsd-hardware.info/?probe=effc42884a) | Nov 28, 2021 |
| ASUSTek       | P5Q-E                       | [158a4879ac](https://bsd-hardware.info/?probe=158a4879ac) | Nov 28, 2021 |
| Shuttle       | FH270                       | [81643d52fd](https://bsd-hardware.info/?probe=81643d52fd) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [7f32937b2c](https://bsd-hardware.info/?probe=7f32937b2c) | Nov 26, 2021 |
| Shuttle       | FZ270                       | [309687b5be](https://bsd-hardware.info/?probe=309687b5be) | Nov 26, 2021 |
| ASRock        | Q1900B-ITX                  | [4df18caa5f](https://bsd-hardware.info/?probe=4df18caa5f) | Nov 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a915598e32](https://bsd-hardware.info/?probe=a915598e32) | Nov 26, 2021 |
| Lenovo        | MAHOBAY                     | [b77016bee5](https://bsd-hardware.info/?probe=b77016bee5) | Nov 25, 2021 |
| Gigabyte      | G41M-Combo                  | [d227ad0b48](https://bsd-hardware.info/?probe=d227ad0b48) | Nov 25, 2021 |
| Gigabyte      | G41M-Combo                  | [3a4a54eed4](https://bsd-hardware.info/?probe=3a4a54eed4) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| ASRock        | X570M Pro4                  | [b10f02e887](https://bsd-hardware.info/?probe=b10f02e887) | Nov 23, 2021 |
| Supermicro    | X7SPA-HF                    | [0ed5f516f4](https://bsd-hardware.info/?probe=0ed5f516f4) | Nov 21, 2021 |
| ASUSTek       | P5Q-E                       | [60ccf13a97](https://bsd-hardware.info/?probe=60ccf13a97) | Nov 21, 2021 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | [fe64c7bb21](https://bsd-hardware.info/?probe=fe64c7bb21) | Nov 21, 2021 |
| ASRockRack    | E3C246D4U2-2T               | [fd00b64a4c](https://bsd-hardware.info/?probe=fd00b64a4c) | Nov 21, 2021 |
| Dell          | 0M5DCD A00                  | [2f26c69137](https://bsd-hardware.info/?probe=2f26c69137) | Nov 20, 2021 |
| HP            | 87D6 SMVB                   | [ffa88d066b](https://bsd-hardware.info/?probe=ffa88d066b) | Nov 16, 2021 |
| PC Engines    | APU                         | [c1656cb13b](https://bsd-hardware.info/?probe=c1656cb13b) | Nov 15, 2021 |
| HP            | ProLiant MicroServer Gen... | [33b6a20321](https://bsd-hardware.info/?probe=33b6a20321) | Nov 14, 2021 |
| PC Engines    | APU                         | [6db53946a4](https://bsd-hardware.info/?probe=6db53946a4) | Nov 14, 2021 |
| PC Engines    | APU2                        | [424bb1e286](https://bsd-hardware.info/?probe=424bb1e286) | Nov 10, 2021 |
| MSI           | GF615M-P33 V2               | [6be2d8aec7](https://bsd-hardware.info/?probe=6be2d8aec7) | Nov 09, 2021 |
| MSI           | MS-9129                     | [4ab900bda7](https://bsd-hardware.info/?probe=4ab900bda7) | Nov 08, 2021 |
| MSI           | MS-9129                     | [7c69051998](https://bsd-hardware.info/?probe=7c69051998) | Nov 08, 2021 |
| Unknown       | Unknown                     | [27e7cd5267](https://bsd-hardware.info/?probe=27e7cd5267) | Nov 08, 2021 |
| PC Engines    | APU                         | [a39767bccb](https://bsd-hardware.info/?probe=a39767bccb) | Nov 08, 2021 |
| PC Engines    | APU2                        | [12ab05bc2e](https://bsd-hardware.info/?probe=12ab05bc2e) | Nov 08, 2021 |
| PC Engines    | APU2                        | [bcb26e0164](https://bsd-hardware.info/?probe=bcb26e0164) | Nov 08, 2021 |
| ASUSTek       | P9X79 WS                    | [050e2e2a8c](https://bsd-hardware.info/?probe=050e2e2a8c) | Nov 08, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| HP            | 3397                        | [3434fa8427](https://bsd-hardware.info/?probe=3434fa8427) | Nov 07, 2021 |
| HP            | 3048h                       | [c2e57e5b06](https://bsd-hardware.info/?probe=c2e57e5b06) | Nov 06, 2021 |
| ASUSTek       | P4PE2-X                     | [25c402cbf0](https://bsd-hardware.info/?probe=25c402cbf0) | Nov 05, 2021 |
| ASRock        | 970 Extreme4                | [cc090875b1](https://bsd-hardware.info/?probe=cc090875b1) | Nov 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a6b0693d9f](https://bsd-hardware.info/?probe=a6b0693d9f) | Nov 01, 2021 |
| Gigabyte      | H110M-H-CF                  | [202d616682](https://bsd-hardware.info/?probe=202d616682) | Oct 31, 2021 |
| Apple         | Mac-F221BEC8                | [bf9d536016](https://bsd-hardware.info/?probe=bf9d536016) | Oct 30, 2021 |
| MSI           | Z270 PC MATE                | [bc9dc27f58](https://bsd-hardware.info/?probe=bc9dc27f58) | Oct 30, 2021 |
| ADI Engine... | RCC-VE                      | [9744b5eca0](https://bsd-hardware.info/?probe=9744b5eca0) | Oct 29, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [206f086c58](https://bsd-hardware.info/?probe=206f086c58) | Oct 29, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 1589                        | [8a1cec788f](https://bsd-hardware.info/?probe=8a1cec788f) | Oct 28, 2021 |
| Dell          | 0KC9NP A01                  | [d80d739506](https://bsd-hardware.info/?probe=d80d739506) | Oct 28, 2021 |
| Radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Beckhoff A... | CX51x0 G3                   | [6db720018b](https://bsd-hardware.info/?probe=6db720018b) | Oct 25, 2021 |
| Beckhoff A... | CX20x3 G1                   | [a49fbd5ce3](https://bsd-hardware.info/?probe=a49fbd5ce3) | Oct 25, 2021 |
| ASUSTek       | P5Q-E                       | [d821d68ffa](https://bsd-hardware.info/?probe=d821d68ffa) | Oct 24, 2021 |
| MSI           | H81M-P33                    | [b4a1918b44](https://bsd-hardware.info/?probe=b4a1918b44) | Oct 24, 2021 |
| ASUSTek       | P10S WS                     | [e2d86f8c45](https://bsd-hardware.info/?probe=e2d86f8c45) | Oct 23, 2021 |
| Gigabyte      | B450M S2H                   | [f3bf8edc1e](https://bsd-hardware.info/?probe=f3bf8edc1e) | Oct 22, 2021 |
| HP            | 18E7                        | [bc3f111ee4](https://bsd-hardware.info/?probe=bc3f111ee4) | Oct 22, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [15d56aee58](https://bsd-hardware.info/?probe=15d56aee58) | Oct 21, 2021 |
| Apple         | Mac-F221BEC8                | [4e91fa71b2](https://bsd-hardware.info/?probe=4e91fa71b2) | Oct 19, 2021 |
| Radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [c4efccfa90](https://bsd-hardware.info/?probe=c4efccfa90) | Oct 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [80719c7010](https://bsd-hardware.info/?probe=80719c7010) | Oct 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [f397fb3c85](https://bsd-hardware.info/?probe=f397fb3c85) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Supermicro    | X10SRH-CLN4FA               | [8e713b55dc](https://bsd-hardware.info/?probe=8e713b55dc) | Oct 06, 2021 |
| MSI           | 970A-G43                    | [5664e84f3c](https://bsd-hardware.info/?probe=5664e84f3c) | Oct 06, 2021 |
| ASUSTek       | H81M-E                      | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [76c73f0745](https://bsd-hardware.info/?probe=76c73f0745) | Oct 01, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [1da3490d20](https://bsd-hardware.info/?probe=1da3490d20) | Sep 30, 2021 |
| Foxconn       | 2A92                        | [da467830af](https://bsd-hardware.info/?probe=da467830af) | Sep 30, 2021 |
| HP            | 0AE8h C                     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Dell          | 06X1TJ A00                  | [ab93f4d860](https://bsd-hardware.info/?probe=ab93f4d860) | Sep 29, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [74e5b610f0](https://bsd-hardware.info/?probe=74e5b610f0) | Sep 28, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [a302e181a5](https://bsd-hardware.info/?probe=a302e181a5) | Sep 27, 2021 |
| ASUSTek       | PRIME Z590-A                | [1aa5ced5a0](https://bsd-hardware.info/?probe=1aa5ced5a0) | Sep 23, 2021 |
| Dell          | 0Y2K8N A01                  | [1559654b51](https://bsd-hardware.info/?probe=1559654b51) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| ASRock        | X58 Extreme3                | [540fef417b](https://bsd-hardware.info/?probe=540fef417b) | Sep 22, 2021 |
| Unknown       | Unknown                     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Gigabyte      | EP45-UD3R                   | [21e4a40d62](https://bsd-hardware.info/?probe=21e4a40d62) | Sep 18, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| QTQD          | Board                       | [2e778ac107](https://bsd-hardware.info/?probe=2e778ac107) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASUSTek       | PRIME X370-PRO              | [433df71bee](https://bsd-hardware.info/?probe=433df71bee) | Sep 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [e15f50c6b9](https://bsd-hardware.info/?probe=e15f50c6b9) | Sep 13, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [8fff74c89c](https://bsd-hardware.info/?probe=8fff74c89c) | Sep 13, 2021 |
| MSI           | Z590 PRO WIFI               | [b77d4fef6b](https://bsd-hardware.info/?probe=b77d4fef6b) | Sep 11, 2021 |
| ASRock        | X570 Taichi                 | [d23af74c18](https://bsd-hardware.info/?probe=d23af74c18) | Sep 10, 2021 |
| HP            | 212B                        | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| HP            | 158A                        | [a9b66cb0e1](https://bsd-hardware.info/?probe=a9b66cb0e1) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| MSI           | B360-A PRO                  | [ca906cd56a](https://bsd-hardware.info/?probe=ca906cd56a) | Sep 06, 2021 |
| Dell          | 0C522T A01                  | [f735ee3c9e](https://bsd-hardware.info/?probe=f735ee3c9e) | Sep 05, 2021 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [a78cc6a11b](https://bsd-hardware.info/?probe=a78cc6a11b) | Sep 04, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [fa4da2509b](https://bsd-hardware.info/?probe=fa4da2509b) | Sep 03, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | [97035edd33](https://bsd-hardware.info/?probe=97035edd33) | Sep 03, 2021 |
| Dell          | 0Y2K8N A01                  | [7294dc1dcc](https://bsd-hardware.info/?probe=7294dc1dcc) | Sep 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| HP            | 1589                        | [288b956c1e](https://bsd-hardware.info/?probe=288b956c1e) | Aug 31, 2021 |
| ASRock        | 970 Extreme3                | [8f18868bb4](https://bsd-hardware.info/?probe=8f18868bb4) | Aug 30, 2021 |
| Intel         | DG33BU AAD79951-408         | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| ASRock        | H67M                        | [53d71eb3fc](https://bsd-hardware.info/?probe=53d71eb3fc) | Aug 29, 2021 |
| Gigabyte      | N3160ND3V                   | [66430483e3](https://bsd-hardware.info/?probe=66430483e3) | Aug 29, 2021 |
| ASRock        | H67M                        | [4b65ec99db](https://bsd-hardware.info/?probe=4b65ec99db) | Aug 29, 2021 |
| Dell          | 0G3HR7 A00                  | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Medion        | MS-7616                     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| ECS-USA       | GeForce6100PM-M2            | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| MSI           | B450 TOMAHAWK               | [b7c1cae5a8](https://bsd-hardware.info/?probe=b7c1cae5a8) | Aug 23, 2021 |
| MSI           | B450 TOMAHAWK               | [ff33f91374](https://bsd-hardware.info/?probe=ff33f91374) | Aug 22, 2021 |
| ASUSTek       | P5Q                         | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| ASRock        | B450M-HDV                   | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| ASRock        | 990FX Killer                | [9f6f8fe218](https://bsd-hardware.info/?probe=9f6f8fe218) | Aug 22, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [5bf55e14a4](https://bsd-hardware.info/?probe=5bf55e14a4) | Aug 21, 2021 |
| Lenovo        | 3728 SDK0J40709 WIN 3259... | [7ba1ccc40d](https://bsd-hardware.info/?probe=7ba1ccc40d) | Aug 19, 2021 |
| Biostar       | TH55B HD                    | [635f13a7c0](https://bsd-hardware.info/?probe=635f13a7c0) | Aug 16, 2021 |
| HP            | 158A                        | [e2c79dfa71](https://bsd-hardware.info/?probe=e2c79dfa71) | Aug 16, 2021 |
| Dell          | 0G261D A00                  | [ba9e468d6d](https://bsd-hardware.info/?probe=ba9e468d6d) | Aug 14, 2021 |
| Biostar       | TH55B HD                    | [6aef0c0281](https://bsd-hardware.info/?probe=6aef0c0281) | Aug 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [b5f1b8963a](https://bsd-hardware.info/?probe=b5f1b8963a) | Aug 13, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [8331eb7cbf](https://bsd-hardware.info/?probe=8331eb7cbf) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [1a89e4b6d7](https://bsd-hardware.info/?probe=1a89e4b6d7) | Aug 07, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [0c4fd12ee6](https://bsd-hardware.info/?probe=0c4fd12ee6) | Jul 26, 2021 |
| Unknown       | Unknown                     | [223d74d547](https://bsd-hardware.info/?probe=223d74d547) | Jul 25, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| ASUSTek       | H170 PRO GAMING             | [ef9820081f](https://bsd-hardware.info/?probe=ef9820081f) | Jul 21, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [8df129e74d](https://bsd-hardware.info/?probe=8df129e74d) | Jul 20, 2021 |
| Dell          | 0HD5W2 A00                  | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Gigabyte      | P55A-UD3                    | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [7717726619](https://bsd-hardware.info/?probe=7717726619) | Jul 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| HP            | ProLiant MicroServer Gen... | [250fc347ce](https://bsd-hardware.info/?probe=250fc347ce) | Jul 11, 2021 |
| HP            | ProLiant MicroServer Gen... | [93b487fc6a](https://bsd-hardware.info/?probe=93b487fc6a) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| HP            | 158A                        | [01d7f3bfd3](https://bsd-hardware.info/?probe=01d7f3bfd3) | Jul 10, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| FreeBSD 13.1         | 93       | 7.46%   |
| FreeBSD 13.0         | 77       | 6.17%   |
| FreeBSD 12.2         | 65       | 5.21%   |
| FreeBSD 14.0-CURRENT | 61       | 4.89%   |
| FreeBSD 13.2         | 51       | 4.09%   |
| FreeBSD 13.0-p5      | 43       | 3.45%   |
| FreeBSD 12.2-p2      | 41       | 3.29%   |
| FreeBSD 13.1-p2      | 40       | 3.21%   |
| FreeBSD 13.0-p4      | 35       | 2.81%   |
| FreeBSD 12.1-p8      | 35       | 2.81%   |
| FreeBSD 12.1-p10     | 34       | 2.73%   |
| FreeBSD 13.1-p5      | 33       | 2.65%   |
| FreeBSD 13.0-STABLE  | 33       | 2.65%   |
| FreeBSD 12.1-STABLE  | 29       | 2.33%   |
| FreeBSD 12.1-p5      | 29       | 2.33%   |
| FreeBSD 12.1-p7      | 28       | 2.25%   |
| FreeBSD 13.1-p7      | 26       | 2.09%   |
| FreeBSD 12.2-p3      | 24       | 1.92%   |
| FreeBSD 13.0-CURRENT | 22       | 1.76%   |
| FreeBSD 12.1         | 22       | 1.76%   |
| FreeBSD 13.0-p11     | 21       | 1.68%   |
| FreeBSD 13.0-p7      | 20       | 1.6%    |
| FreeBSD 12.2-p4      | 19       | 1.52%   |
| FreeBSD 13.0-p3      | 18       | 1.44%   |
| FreeBSD 12.3         | 16       | 1.28%   |
| FreeBSD 12.2-STABLE  | 16       | 1.28%   |
| FreeBSD 13.1-STABLE  | 15       | 1.2%    |
| FreeBSD 13.0-p10     | 14       | 1.12%   |
| FreeBSD 13.1-p1      | 13       | 1.04%   |
| FreeBSD 13.0-p2      | 13       | 1.04%   |
| FreeBSD 12.2-p6      | 11       | 0.88%   |
| FreeBSD 12.1-p6      | 11       | 0.88%   |
| FreeBSD 13.1-p8      | 10       | 0.8%    |
| FreeBSD 13.1-p3      | 10       | 0.8%    |
| FreeBSD 13.0-p6      | 10       | 0.8%    |
| FreeBSD 12.2-p10     | 10       | 0.8%    |
| FreeBSD 12.1-p12     | 9        | 0.72%   |
| FreeBSD 13.2-p1      | 8        | 0.64%   |
| FreeBSD 13.1-p4      | 8        | 0.64%   |
| FreeBSD 12.1-p9      | 8        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| FreeBSD | 1007     | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 930      | 92.35%  |
| arm64   | 35       | 3.48%   |
| i386    | 29       | 2.88%   |
| arm     | 7        | 0.7%    |
| powerpc | 4        | 0.4%    |
| sparc64 | 1        | 0.1%    |
| riscv   | 1        | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 437      | 41.78%  |
| KDE5          | 167      | 15.97%  |
| XFCE          | 131      | 12.52%  |
| GNOME         | 64       | 6.12%   |
| TWM           | 60       | 5.74%   |
| MATE          | 51       | 4.88%   |
| i3            | 27       | 2.58%   |
| Openbox       | 26       | 2.49%   |
| Cinnamon      | 10       | 0.96%   |
| AwesomeWM     | 10       | 0.96%   |
| Fluxbox       | 9        | 0.86%   |
| LXQt          | 8        | 0.76%   |
| LXDE          | 7        | 0.67%   |
| Lumina        | 5        | 0.48%   |
| Enlightenment | 5        | 0.48%   |
| DWM           | 5        | 0.48%   |
| CDE           | 3        | 0.29%   |
| xfwm          | 2        | 0.19%   |
| X-Cinnamon    | 2        | 0.19%   |
| Window Maker  | 2        | 0.19%   |
| Picom         | 2        | 0.19%   |
| KDE           | 2        | 0.19%   |
| GNUstep       | 2        | 0.19%   |
| xinitrc       | 1        | 0.1%    |
| spectrwm      | 1        | 0.1%    |
| plasma        | 1        | 0.1%    |
| KWin          | 1        | 0.1%    |
| Compton       | 1        | 0.1%    |
| Budgie        | 1        | 0.1%    |
| bspwm         | 1        | 0.1%    |
| Blackbox      | 1        | 0.1%    |
| akonadi_newm  | 1        | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 537      | 52.44%  |
| Console | 475      | 46.39%  |
| Wayland | 11       | 1.07%   |
| Tty     | 1        | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 639      | 61.8%   |
| SDDM    | 150      | 14.51%  |
| SLiM    | 76       | 7.35%   |
| XDM     | 66       | 6.38%   |
| LightDM | 54       | 5.22%   |
| GDM     | 43       | 4.16%   |
| Ly      | 6        | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| C                | 395      | 37.3%   |
| Unknown          | 293      | 27.67%  |
| en_US            | 162      | 15.3%   |
| ru_RU            | 77       | 7.27%   |
| de_DE            | 21       | 1.98%   |
| fr_FR            | 14       | 1.32%   |
| en_GB            | 14       | 1.32%   |
| en_CA            | 7        | 0.66%   |
| uk_UA            | 6        | 0.57%   |
| pt_BR            | 6        | 0.57%   |
| ja_JP            | 6        | 0.57%   |
| it_IT            | 6        | 0.57%   |
| zh_CN            | 5        | 0.47%   |
| es_ES            | 4        | 0.38%   |
| en_IE            | 4        | 0.38%   |
| en_AU            | 4        | 0.38%   |
| el_GR            | 4        | 0.38%   |
| ru_RU.KOI8-R     | 3        | 0.28%   |
| pl_PL            | 3        | 0.28%   |
| fi_FI            | 3        | 0.28%   |
| sv_SE            | 2        | 0.19%   |
| nb_NO            | 2        | 0.19%   |
| es_AR            | 2        | 0.19%   |
| zh_TW            | 1        | 0.09%   |
| sv_SE.US-ASCII   | 1        | 0.09%   |
| nl_NL            | 1        | 0.09%   |
| it_IT.ISO8859-15 | 1        | 0.09%   |
| fr_FR.US-ASCII   | 1        | 0.09%   |
| fi_FI.ISO8859-15 | 1        | 0.09%   |
| et_EE.US-ASCII   | 1        | 0.09%   |
| es_MX            | 1        | 0.09%   |
| es_ES.ISO8859-15 | 1        | 0.09%   |
| en_US.utf-8      | 1        | 0.09%   |
| en_US.ISO8859-1  | 1        | 0.09%   |
| en_GB.US-ASCII   | 1        | 0.09%   |
| de_DE.ISO8859-1  | 1        | 0.09%   |
| de_CH            | 1        | 0.09%   |
| da_DK            | 1        | 0.09%   |
| cv_RU.US-ASCII   | 1        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 583      | 57.05%  |
| BIOS | 439      | 42.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 626      | 61.49%  |
| Ufs    | 389      | 38.21%  |
| Cd9660 | 2        | 0.2%    |
| Nfs    | 1        | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 898      | 88.74%  |
| MBR     | 103      | 10.18%  |
| Unknown | 7        | 0.69%   |
| BSD     | 4        | 0.4%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 219      | 21.75%  |
| Gigabyte Technology        | 129      | 12.81%  |
| ASRock                     | 110      | 10.92%  |
| Hewlett-Packard            | 93       | 9.24%   |
| MSI                        | 81       | 8.04%   |
| Dell                       | 71       | 7.05%   |
| Unknown                    | 60       | 5.96%   |
| Intel                      | 40       | 3.97%   |
| Supermicro                 | 34       | 3.38%   |
| Lenovo                     | 22       | 2.18%   |
| Fujitsu                    | 17       | 1.69%   |
| PC Engines                 | 16       | 1.59%   |
| ASRockRack                 | 15       | 1.49%   |
| Acer                       | 10       | 0.99%   |
| Shuttle                    | 7        | 0.7%    |
| Biostar                    | 5        | 0.5%    |
| Beckhoff Automation        | 5        | 0.5%    |
| Wistron                    | 4        | 0.4%    |
| Huanan                     | 4        | 0.4%    |
| Foxconn                    | 4        | 0.4%    |
| Pegatron                   | 3        | 0.3%    |
| HPE                        | 3        | 0.3%    |
| Apple                      | 3        | 0.3%    |
| Radxa                      | 2        | 0.2%    |
| Google                     | 2        | 0.2%    |
| Gateway                    | 2        | 0.2%    |
| EVGA                       | 2        | 0.2%    |
| Deciso                     | 2        | 0.2%    |
| BESSTAR Tech               | 2        | 0.2%    |
| AMI                        | 2        | 0.2%    |
| ADI Engineering            | 2        | 0.2%    |
| VIA Technologies           | 1        | 0.1%    |
| TYAN Computer              | 1        | 0.1%    |
| TOPFEEL                    | 1        | 0.1%    |
| Sun Microsystems           | 1        | 0.1%    |
| SolidRun                   | 1        | 0.1%    |
| ShenZhen MinWin Technology | 1        | 0.1%    |
| Seeed Studio               | 1        | 0.1%    |
| Raspberry Pi Foundation    | 1        | 0.1%    |
| QTQD                       | 1        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 61       | 6.06%   |
| ASUS All Series                  | 27       | 2.68%   |
| HP ProLiant MicroServer Gen8     | 10       | 0.99%   |
| Intel Nobilis                    | 9        | 0.89%   |
| PC Engines APU2                  | 8        | 0.79%   |
| HP ProLiant MicroServer          | 6        | 0.6%    |
| ASUS TUF GAMING X570-PLUS        | 6        | 0.6%    |
| MSI MS-7C02                      | 5        | 0.5%    |
| HP Z440 Workstation              | 5        | 0.5%    |
| Gigabyte B360N WIFI              | 5        | 0.5%    |
| Dell OptiPlex 9020               | 5        | 0.5%    |
| ASRock X570 Phantom Gaming 4     | 5        | 0.5%    |
| Supermicro X9SCL/X9SCM           | 4        | 0.4%    |
| MSI MS-7B89                      | 4        | 0.4%    |
| HP Z620 Workstation              | 4        | 0.4%    |
| HP Z420 Workstation              | 4        | 0.4%    |
| HP t620 Quad Core TC             | 4        | 0.4%    |
| HP Compaq Elite 8300 SFF         | 4        | 0.4%    |
| Gigabyte X570 I AORUS PRO WIFI   | 4        | 0.4%    |
| Gigabyte B450M DS3H              | 4        | 0.4%    |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4        | 0.4%    |
| Dell PowerEdge T30               | 4        | 0.4%    |
| Dell OptiPlex 7040               | 4        | 0.4%    |
| Dell OptiPlex 3010               | 4        | 0.4%    |
| ASRock Z590 Pro4                 | 4        | 0.4%    |
| ASRock Q1900B-ITX                | 4        | 0.4%    |
| Wistron ProLiant ML110 G6        | 3        | 0.3%    |
| Supermicro X7SPA-HF              | 3        | 0.3%    |
| PC Engines apu4                  | 3        | 0.3%    |
| PC Engines APU                   | 3        | 0.3%    |
| MSI MS-7C37                      | 3        | 0.3%    |
| MSI MS-7817                      | 3        | 0.3%    |
| MSI MS-7693                      | 3        | 0.3%    |
| MSI MS-7522                      | 3        | 0.3%    |
| HP Z820 Workstation              | 3        | 0.3%    |
| HP Z600 Workstation              | 3        | 0.3%    |
| HP t620 PLUS Quad Core TC        | 3        | 0.3%    |
| HP Compaq 6200 Pro MT PC         | 3        | 0.3%    |
| Gigabyte B550M AORUS PRO-P       | 3        | 0.3%    |
| ASUS SABERTOOTH 990FX R2.0       | 3        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Unknown            | 61       | 6.06%   |
| ASUS PRIME         | 43       | 4.27%   |
| Dell OptiPlex      | 39       | 3.87%   |
| ASUS All           | 27       | 2.68%   |
| ASUS ROG           | 25       | 2.48%   |
| ASUS TUF           | 22       | 2.18%   |
| HP Compaq          | 21       | 2.09%   |
| HP ProLiant        | 20       | 1.99%   |
| Dell Precision     | 13       | 1.29%   |
| ASRock X570        | 13       | 1.29%   |
| Lenovo ThinkCentre | 12       | 1.19%   |
| Intel Nobilis      | 9        | 0.89%   |
| Gigabyte X570      | 9        | 0.89%   |
| PC Engines APU2    | 8        | 0.79%   |
| ASRock X370        | 8        | 0.79%   |
| HP t620            | 7        | 0.7%    |
| HP EliteDesk       | 7        | 0.7%    |
| Gigabyte B450M     | 7        | 0.7%    |
| Dell PowerEdge     | 7        | 0.7%    |
| Fujitsu ESPRIMO    | 6        | 0.6%    |
| ASUS PRO           | 6        | 0.6%    |
| MSI MS-7C02        | 5        | 0.5%    |
| HP Z440            | 5        | 0.5%    |
| HP ProDesk         | 5        | 0.5%    |
| Gigabyte B360N     | 5        | 0.5%    |
| ASRock B550        | 5        | 0.5%    |
| ASRock 970         | 5        | 0.5%    |
| Acer Aspire        | 5        | 0.5%    |
| Wistron ProLiant   | 4        | 0.4%    |
| Supermicro X9SCL   | 4        | 0.4%    |
| MSI MS-7B89        | 4        | 0.4%    |
| HP Z620            | 4        | 0.4%    |
| HP Z420            | 4        | 0.4%    |
| Gigabyte X470      | 4        | 0.4%    |
| Gigabyte B550M     | 4        | 0.4%    |
| Fujitsu D3401-H2   | 4        | 0.4%    |
| ASUS SABERTOOTH    | 4        | 0.4%    |
| ASUS P5Q           | 4        | 0.4%    |
| ASUS M5A78L-M      | 4        | 0.4%    |
| ASRock Z590        | 4        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 121      | 12.02%  |
| 2018    | 101      | 10.03%  |
| 2020    | 88       | 8.74%   |
| 2013    | 73       | 7.25%   |
| 2021    | 71       | 7.05%   |
| 2014    | 69       | 6.85%   |
| 2011    | 63       | 6.26%   |
| 2012    | 56       | 5.56%   |
| 2017    | 54       | 5.36%   |
| Unknown | 47       | 4.67%   |
| 2016    | 45       | 4.47%   |
| 2015    | 43       | 4.27%   |
| 2010    | 42       | 4.17%   |
| 2022    | 34       | 3.38%   |
| 2009    | 33       | 3.28%   |
| 2008    | 29       | 2.88%   |
| 2007    | 13       | 1.29%   |
| 2023    | 7        | 0.7%    |
| 2006    | 5        | 0.5%    |
| 2005    | 4        | 0.4%    |
| 2004    | 4        | 0.4%    |
| 2003    | 2        | 0.2%    |
| 2002    | 2        | 0.2%    |
| 2001    | 1        | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1007     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 983      | 97.62%  |
| Yes  | 24       | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 249      | 24.46%  |
| 8.01-16.0       | 224      | 22%     |
| 32.01-64.0      | 201      | 19.74%  |
| 4.01-8.0        | 116      | 11.39%  |
| 64.01-256.0     | 111      | 10.9%   |
| 2.01-3.0        | 33       | 3.24%   |
| 0.51-1.0        | 23       | 2.26%   |
| 24.01-32.0      | 21       | 2.06%   |
| 3.01-4.0        | 20       | 1.96%   |
| 0.01-0.5        | 10       | 0.98%   |
| 1.01-2.0        | 6        | 0.59%   |
| More than 256.0 | 3        | 0.29%   |
| Unknown         | 1        | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 320      | 30.13%  |
| 0.01-0.5    | 309      | 29.1%   |
| 1.01-2.0    | 216      | 20.34%  |
| 2.01-3.0    | 49       | 4.61%   |
| 3.01-4.0    | 43       | 4.05%   |
| 4.01-8.0    | 42       | 3.95%   |
| 8.01-16.0   | 24       | 2.26%   |
| 0           | 15       | 1.41%   |
| 24.01-32.0  | 14       | 1.32%   |
| 32.01-64.0  | 11       | 1.04%   |
| 16.01-24.0  | 10       | 0.94%   |
| 64.01-256.0 | 8        | 0.75%   |
| Unknown     | 1        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 293      | 27.72%  |
| 2      | 256      | 24.22%  |
| 3      | 159      | 15.04%  |
| 4      | 114      | 10.79%  |
| 5      | 72       | 6.81%   |
| 0      | 57       | 5.39%   |
| 6      | 41       | 3.88%   |
| 7      | 22       | 2.08%   |
| 8      | 11       | 1.04%   |
| 10     | 7        | 0.66%   |
| 9      | 7        | 0.66%   |
| 14     | 3        | 0.28%   |
| 12     | 3        | 0.28%   |
| 11     | 3        | 0.28%   |
| 23     | 2        | 0.19%   |
| 13     | 2        | 0.19%   |
| 21     | 1        | 0.09%   |
| 19     | 1        | 0.09%   |
| 18     | 1        | 0.09%   |
| 17     | 1        | 0.09%   |
| 15     | 1        | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 705      | 69.32%  |
| Yes       | 312      | 30.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 966      | 95.83%  |
| No        | 42       | 4.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 759      | 74.63%  |
| Yes       | 258      | 25.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 837      | 82.46%  |
| Yes       | 178      | 17.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 226      | 22.33%  |
| Russia      | 145      | 14.33%  |
| Germany     | 112      | 11.07%  |
| Canada      | 48       | 4.74%   |
| France      | 46       | 4.55%   |
| Poland      | 39       | 3.85%   |
| UK          | 34       | 3.36%   |
| Netherlands | 25       | 2.47%   |
| Ukraine     | 23       | 2.27%   |
| Australia   | 23       | 2.27%   |
| Czechia     | 20       | 1.98%   |
| Brazil      | 19       | 1.88%   |
| Japan       | 18       | 1.78%   |
| Italy       | 16       | 1.58%   |
| Finland     | 16       | 1.58%   |
| Sweden      | 15       | 1.48%   |
| Switzerland | 12       | 1.19%   |
| Spain       | 12       | 1.19%   |
| China       | 11       | 1.09%   |
| Greece      | 10       | 0.99%   |
| Romania     | 9        | 0.89%   |
| Norway      | 8        | 0.79%   |
| Ireland     | 8        | 0.79%   |
| Indonesia   | 8        | 0.79%   |
| Thailand    | 7        | 0.69%   |
| India       | 7        | 0.69%   |
| Belgium     | 7        | 0.69%   |
| Austria     | 7        | 0.69%   |
| Taiwan      | 6        | 0.59%   |
| Hungary     | 6        | 0.59%   |
| Serbia      | 5        | 0.49%   |
| Denmark     | 5        | 0.49%   |
| Bulgaria    | 5        | 0.49%   |
| Argentina   | 5        | 0.49%   |
| Slovenia    | 4        | 0.4%    |
| New Zealand | 4        | 0.4%    |
| Estonia     | 4        | 0.4%    |
| Slovakia    | 3        | 0.3%    |
| Mexico      | 3        | 0.3%    |
| Malaysia    | 3        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Moscow               | 49       | 4.54%   |
| Krasnodar            | 15       | 1.39%   |
| Grand Rapids         | 14       | 1.3%    |
| Berlin               | 14       | 1.3%    |
| St Petersburg        | 13       | 1.2%    |
| Kyiv                 | 12       | 1.11%   |
| Sydney               | 11       | 1.02%   |
| Ludwigsburg          | 11       | 1.02%   |
| Helsinki             | 10       | 0.93%   |
| Yekaterinburg        | 8        | 0.74%   |
| Tuklaty              | 8        | 0.74%   |
| Montreal             | 8        | 0.74%   |
| Hamburg              | 7        | 0.65%   |
| Warsaw               | 6        | 0.56%   |
| Rochester            | 6        | 0.56%   |
| Poway                | 6        | 0.56%   |
| Portland             | 6        | 0.56%   |
| Paris                | 6        | 0.56%   |
| Novosibirsk          | 6        | 0.56%   |
| Madrid               | 6        | 0.56%   |
| Lublin               | 6        | 0.56%   |
| London               | 6        | 0.56%   |
| Falkenstein          | 6        | 0.56%   |
| Chicago              | 6        | 0.56%   |
| Brooklyn             | 6        | 0.56%   |
| Amsterdam            | 6        | 0.56%   |
| Zurich               | 5        | 0.46%   |
| Zaporizhzhya         | 5        | 0.46%   |
| Vienna               | 5        | 0.46%   |
| Toronto              | 5        | 0.46%   |
| Teaneck              | 5        | 0.46%   |
| Ozersk               | 5        | 0.46%   |
| Kamensk-Ural'skiy    | 5        | 0.46%   |
| Dublin               | 5        | 0.46%   |
| City of Saint Peters | 5        | 0.46%   |
| Bellevue             | 5        | 0.46%   |
| Bangkok              | 5        | 0.46%   |
| Athens               | 5        | 0.46%   |
| Tamm                 | 4        | 0.37%   |
| Stockholm            | 4        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 401      | 1353   | 23.19%  |
| Seagate             | 309      | 795    | 17.87%  |
| Samsung Electronics | 255      | 613    | 14.75%  |
| Toshiba             | 106      | 243    | 6.13%   |
| Kingston            | 99       | 129    | 5.73%   |
| Crucial             | 94       | 146    | 5.44%   |
| Intel               | 65       | 132    | 3.76%   |
| Hitachi             | 47       | 114    | 2.72%   |
| HGST                | 42       | 91     | 2.43%   |
| SanDisk             | 36       | 54     | 2.08%   |
| A-DATA Technology   | 34       | 45     | 1.97%   |
| Transcend           | 15       | 21     | 0.87%   |
| SK hynix            | 13       | 17     | 0.75%   |
| OCZ                 | 13       | 16     | 0.75%   |
| Corsair             | 13       | 34     | 0.75%   |
| Phison              | 12       | 16     | 0.69%   |
| Micron Technology   | 11       | 23     | 0.64%   |
| GOODRAM             | 11       | 21     | 0.64%   |
| SPCC                | 9        | 26     | 0.52%   |
| Maxtor              | 9        | 13     | 0.52%   |
| PNY                 | 8        | 10     | 0.46%   |
| Patriot             | 8        | 11     | 0.46%   |
| Hewlett-Packard     | 8        | 22     | 0.46%   |
| Plextor             | 6        | 12     | 0.35%   |
| Intenso             | 6        | 7      | 0.35%   |
| KingSpec            | 5        | 8      | 0.29%   |
| Silicon Motion      | 4        | 5      | 0.23%   |
| MidasForce          | 4        | 4      | 0.23%   |
| KIOXIA-EXCERIA      | 4        | 10     | 0.23%   |
| FORESEE             | 4        | 4      | 0.23%   |
| China               | 4        | 4      | 0.23%   |
| Apacer              | 4        | 4      | 0.23%   |
| Verbatim            | 3        | 3      | 0.17%   |
| Vaseky              | 3        | 3      | 0.17%   |
| T-FORCE             | 3        | 4      | 0.17%   |
| Netac               | 3        | 3      | 0.17%   |
| Mushkin             | 3        | 4      | 0.17%   |
| Hoodisk             | 3        | 5      | 0.17%   |
| Gigabyte Technology | 3        | 3      | 0.17%   |
| Team                | 2        | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB  | 23       | 1.07%   |
| WDC WD10EZEX-08WN4A0 1TB        | 22       | 1.02%   |
| Samsung SSD 850 EVO 250GB       | 22       | 1.02%   |
| WDC WD30EFRX-68EUZN0 3TB        | 18       | 0.84%   |
| Kingston SA400S37240G 240GB     | 18       | 0.84%   |
| WDC WD800JD-75MSA3 80GB         | 16       | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB  | 16       | 0.74%   |
| Kingston SA400S37120G 120GB     | 16       | 0.74%   |
| WDC WD40EFRX-68N32N0 4TB        | 15       | 0.7%    |
| Toshiba DT01ACA100 1TB          | 14       | 0.65%   |
| Seagate ST4000DM000-1F2168 4TB  | 13       | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB    | 13       | 0.6%    |
| Crucial CT240BX500SSD1 240GB    | 13       | 0.6%    |
| Seagate ST500DM002-1BD142 496GB | 12       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB  | 11       | 0.51%   |
| Samsung SSD 860 EVO 250GB       | 11       | 0.51%   |
| Samsung SSD 850 EVO 500GB       | 11       | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB        | 10       | 0.46%   |
| Seagate ST3500418AS 500GB       | 10       | 0.46%   |
| Kingston SA400S37480G 480GB     | 10       | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB  | 9        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB  | 9        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB  | 9        | 0.42%   |
| Samsung SSD 870 EVO 1TB         | 9        | 0.42%   |
| Samsung SSD 860 EVO 1TB         | 9        | 0.42%   |
| Crucial CT250MX500SSD1 250GB    | 9        | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 8        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB        | 8        | 0.37%   |
| WDC WD10EFRX-68FYTN0 1TB        | 8        | 0.37%   |
| Seagate ST4000VN008-2DR166 4TB  | 8        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB  | 8        | 0.37%   |
| Samsung SSD 980 PRO 1TB         | 8        | 0.37%   |
| Samsung SSD 860 EVO 500GB       | 8        | 0.37%   |
| WDC WDS500G1R0A-68A4W0 500GB    | 7        | 0.32%   |
| WDC WD40EFRX-68WT0N0 4TB        | 7        | 0.32%   |
| Seagate ST8000DM004-2CX188 8TB  | 7        | 0.32%   |
| Seagate ST3500413AS 500GB       | 7        | 0.32%   |
| Samsung SSD 970 EVO 1TB         | 7        | 0.32%   |
| Samsung SSD 850 EVO 1TB         | 7        | 0.32%   |
| Kingston SV300S37A120G 120GB    | 7        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 359      | 1224   | 39.36%  |
| Seagate              | 304      | 785    | 33.33%  |
| Toshiba              | 97       | 231    | 10.64%  |
| Hitachi              | 47       | 114    | 5.15%   |
| HGST                 | 42       | 91     | 4.61%   |
| Samsung Electronics  | 37       | 60     | 4.06%   |
| Maxtor               | 9        | 13     | 0.99%   |
| Hewlett-Packard      | 5        | 16     | 0.55%   |
| HPT                  | 2        | 9      | 0.22%   |
| Apple                | 2        | 3      | 0.22%   |
| WD MediaMax          | 1        | 2      | 0.11%   |
| QUANTUM              | 1        | 2      | 0.11%   |
| MaxDigital           | 1        | 1      | 0.11%   |
| IBM/Hitachi          | 1        | 1      | 0.11%   |
| IBM                  | 1        | 1      | 0.11%   |
| HPE                  | 1        | 4      | 0.11%   |
| ExcelStor Technology | 1        | 4      | 0.11%   |
| Areca                | 1        | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 156      | 392    | 24.38%  |
| Kingston            | 86       | 108    | 13.44%  |
| Crucial             | 82       | 124    | 12.81%  |
| Intel               | 46       | 107    | 7.19%   |
| WDC                 | 42       | 70     | 6.56%   |
| SanDisk             | 36       | 54     | 5.63%   |
| A-DATA Technology   | 25       | 34     | 3.91%   |
| Transcend           | 13       | 18     | 2.03%   |
| OCZ                 | 13       | 16     | 2.03%   |
| Micron Technology   | 9        | 20     | 1.41%   |
| Toshiba             | 8        | 8      | 1.25%   |
| Patriot             | 8        | 11     | 1.25%   |
| GOODRAM             | 8        | 17     | 1.25%   |
| SK hynix            | 7        | 9      | 1.09%   |
| Corsair             | 7        | 9      | 1.09%   |
| SPCC                | 6        | 22     | 0.94%   |
| Intenso             | 6        | 7      | 0.94%   |
| PNY                 | 5        | 6      | 0.78%   |
| Plextor             | 5        | 8      | 0.78%   |
| KingSpec            | 5        | 8      | 0.78%   |
| Seagate             | 4        | 6      | 0.63%   |
| MidasForce          | 4        | 4      | 0.63%   |
| China               | 4        | 4      | 0.63%   |
| Apacer              | 4        | 4      | 0.63%   |
| Verbatim            | 3        | 3      | 0.47%   |
| Vaseky              | 3        | 3      | 0.47%   |
| Hoodisk             | 3        | 5      | 0.47%   |
| FORESEE             | 3        | 3      | 0.47%   |
| Team                | 2        | 2      | 0.31%   |
| Smartbuy            | 2        | 2      | 0.31%   |
| ORICO               | 2        | 2      | 0.31%   |
| Netac               | 2        | 2      | 0.31%   |
| Mushkin             | 2        | 2      | 0.31%   |
| LITEONIT            | 2        | 2      | 0.31%   |
| LITEON              | 2        | 2      | 0.31%   |
| Kston               | 2        | 2      | 0.31%   |
| Innodisk            | 2        | 2      | 0.31%   |
| Hikvision           | 2        | 2      | 0.31%   |
| Emtec               | 2        | 2      | 0.31%   |
| AMD                 | 2        | 3      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 671      | 2562   | 46.92%  |
| SSD  | 539      | 1134   | 37.69%  |
| NVMe | 220      | 412    | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 897      | 3696   | 80.3%   |
| NVMe | 220      | 412    | 19.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 641      | 1314   | 45.3%   |
| 0.51-1.0   | 310      | 656    | 21.91%  |
| 1.01-2.0   | 170      | 493    | 12.01%  |
| 3.01-4.0   | 115      | 383    | 8.13%   |
| 4.01-10.0  | 95       | 537    | 6.71%   |
| 2.01-3.0   | 61       | 205    | 4.31%   |
| 10.01-20.0 | 22       | 107    | 1.55%   |
| 20.01-50.0 | 1        | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 269      | 25.67%  |
| 251-500        | 200      | 19.08%  |
| 501-1000       | 160      | 15.27%  |
| 51-100         | 124      | 11.83%  |
| 21-50          | 77       | 7.35%   |
| 1-20           | 70       | 6.68%   |
| 1001-2000      | 62       | 5.92%   |
| More than 3000 | 51       | 4.87%   |
| 2001-3000      | 21       | 2%      |
| Unknown        | 14       | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 702      | 67.11%  |
| 21-50          | 141      | 13.48%  |
| 51-100         | 53       | 5.07%   |
| 101-250        | 36       | 3.44%   |
| 251-500        | 34       | 3.25%   |
| 501-1000       | 23       | 2.2%    |
| More than 3000 | 18       | 1.72%   |
| 1001-2000      | 14       | 1.34%   |
| Unknown        | 14       | 1.34%   |
| 2001-3000      | 9        | 0.86%   |
| 0              | 2        | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 6        | 18     | 2.11%   |
| Seagate ST3500413AS 500GB           | 6        | 9      | 2.11%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5        | 12     | 1.76%   |
| Samsung Electronics SSD 870 EVO 1TB | 5        | 7      | 1.76%   |
| WDC WD40EFRX-68WT0N0 4TB            | 3        | 7      | 1.06%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 3        | 5      | 1.06%   |
| Seagate ST3500418AS 500GB           | 3        | 6      | 1.06%   |
| Seagate ST2000DM001-9YN164 2TB      | 3        | 3      | 1.06%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 4      | 1.06%   |
| Samsung Electronics HD501LJ 500GB   | 3        | 4      | 1.06%   |
| Samsung Electronics HD154UI 1.5TB   | 3        | 4      | 1.06%   |
| Samsung Electronics HD103UJ 1TB     | 3        | 6      | 1.06%   |
| Intel SSDSA2M080G2GC 80GB           | 3        | 3      | 1.06%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2        | 2      | 0.7%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 2      | 0.7%    |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 5      | 0.7%    |
| WDC WD20EARS-00MVWB0 2TB            | 2        | 2      | 0.7%    |
| WDC WD2002FYPS-02W3B0 2TB           | 2        | 2      | 0.7%    |
| WDC WD2002FYPS-01U1B0 2TB           | 2        | 3      | 0.7%    |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2        | 4      | 0.7%    |
| WDC WD15EADS-00P8B0 1.5TB           | 2        | 2      | 0.7%    |
| Toshiba MK5076GSXN 500GB            | 2        | 2      | 0.7%    |
| Seagate ST9250827AS 250GB           | 2        | 3      | 0.7%    |
| Seagate ST500DM002-1BD142 496GB     | 2        | 2      | 0.7%    |
| Seagate ST500DM002-1BC142 500GB     | 2        | 2      | 0.7%    |
| Seagate ST380013AS 80GB             | 2        | 3      | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB      | 2        | 2      | 0.7%    |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 2      | 0.7%    |
| Seagate ST1000DM003-9YN162 1TB      | 2        | 6      | 0.7%    |
| Seagate ST1000DM003-1ER162 1TB      | 2        | 2      | 0.7%    |
| Samsung Electronics HD204UI 2TB     | 2        | 3      | 0.7%    |
| Maxtor 6Y080P0 82GB                 | 2        | 3      | 0.7%    |
| Kingston SMS200S360G 64GB           | 2        | 2      | 0.7%    |
| Kingston SA400S37120G 120GB         | 2        | 2      | 0.7%    |
| Intel SSDSC2CW120A3 120GB           | 2        | 2      | 0.7%    |
| Intel SSDSC2BW480A4 480GB           | 2        | 2      | 0.7%    |
| Hitachi HUA722020ALA330 2TB         | 2        | 4      | 0.7%    |
| Hitachi HDS721010CLA332 1TB         | 2        | 3      | 0.7%    |
| HGST HTS725050A7E630 500GB          | 2        | 6      | 0.7%    |
| Crucial CT525MX300SSD1 528GB        | 2        | 2      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 79       | 158    | 29.59%  |
| Seagate              | 68       | 96     | 25.47%  |
| Samsung Electronics  | 29       | 41     | 10.86%  |
| Hitachi              | 14       | 19     | 5.24%   |
| Toshiba              | 13       | 32     | 4.87%   |
| Intel                | 12       | 16     | 4.49%   |
| Crucial              | 8        | 13     | 3%      |
| Kingston             | 7        | 7      | 2.62%   |
| HGST                 | 7        | 12     | 2.62%   |
| Maxtor               | 6        | 10     | 2.25%   |
| SanDisk              | 4        | 5      | 1.5%    |
| A-DATA Technology    | 3        | 4      | 1.12%   |
| SK hynix             | 2        | 4      | 0.75%   |
| OCZ                  | 2        | 3      | 0.75%   |
| Micron Technology    | 2        | 6      | 0.75%   |
| Hewlett-Packard      | 2        | 4      | 0.75%   |
| Corsair              | 2        | 4      | 0.75%   |
| walram               | 1        | 1      | 0.37%   |
| SPCC                 | 1        | 1      | 0.37%   |
| Plextor              | 1        | 1      | 0.37%   |
| LITEON               | 1        | 1      | 0.37%   |
| GK                   | 1        | 1      | 0.37%   |
| ExcelStor Technology | 1        | 2      | 0.37%   |
| AMD                  | 1        | 2      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Desktops | Drives | Percent |
|----------------------|----------|--------|---------|
| WDC                  | 78       | 157    | 37.86%  |
| Seagate              | 67       | 95     | 32.52%  |
| Samsung Electronics  | 18       | 24     | 8.74%   |
| Hitachi              | 14       | 19     | 6.8%    |
| Toshiba              | 13       | 32     | 6.31%   |
| HGST                 | 7        | 12     | 3.4%    |
| Maxtor               | 6        | 10     | 2.91%   |
| Hewlett-Packard      | 2        | 4      | 0.97%   |
| ExcelStor Technology | 1        | 2      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 188      | 355    | 76.11%  |
| SSD  | 58       | 87     | 23.48%  |
| NVMe | 1        | 1      | 0.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB     | 1        | 1      | 25%     |
| Toshiba MG05ACA800E 8TB      | 1        | 1      | 25%     |
| Maxtor 6E040L0 41GB          | 1        | 1      | 25%     |
| Crucial M4-CT256M4SSD1 256GB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Toshiba | 1        | 1      | 25%     |
| Maxtor  | 1        | 1      | 25%     |
| Crucial | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 886      | 3566   | 76.45%  |
| Malfunc  | 231      | 443    | 19.93%  |
| Detected | 38       | 95     | 3.28%   |
| Failed   | 4        | 4      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 636      | 43.92%  |
| AMD                              | 302      | 20.86%  |
| Samsung Electronics              | 99       | 6.84%   |
| ASMedia Technology               | 61       | 4.21%   |
| Marvell Technology Group         | 49       | 3.38%   |
| Broadcom / LSI                   | 49       | 3.38%   |
| SanDisk                          | 40       | 2.76%   |
| Phison Electronics               | 26       | 1.8%    |
| Silicon Motion                   | 24       | 1.66%   |
| JMicron Technology               | 24       | 1.66%   |
| Nvidia                           | 18       | 1.24%   |
| Kingston Technology Company      | 17       | 1.17%   |
| Micron/Crucial Technology        | 12       | 0.83%   |
| Silicon Image                    | 9        | 0.62%   |
| ADATA Technology                 | 9        | 0.62%   |
| Adaptec                          | 9        | 0.62%   |
| VIA Technologies                 | 7        | 0.48%   |
| SK hynix                         | 7        | 0.48%   |
| Areca Technology                 | 6        | 0.41%   |
| Seagate Technology               | 4        | 0.28%   |
| Realtek Semiconductor            | 4        | 0.28%   |
| Micron Technology                | 4        | 0.28%   |
| KIOXIA                           | 4        | 0.28%   |
| Toshiba                          | 3        | 0.21%   |
| Silicon Integrated Systems [SiS] | 3        | 0.21%   |
| Integrated Technology Express    | 3        | 0.21%   |
| Hewlett-Packard                  | 3        | 0.21%   |
| Chelsio Communications           | 3        | 0.21%   |
| 3ware                            | 3        | 0.21%   |
| Promise Technology               | 2        | 0.14%   |
| Lite-On Technology               | 2        | 0.14%   |
| HighPoint Technologies           | 2        | 0.14%   |
| ULi Electronics                  | 1        | 0.07%   |
| Transcend                        | 1        | 0.07%   |
| Lenovo                           | 1        | 0.07%   |
| Broadcom                         | 1        | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 178      | 10.05%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 67       | 3.78%   |
| AMD 400 Series Chipset SATA Controller                                         | 58       | 3.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 57       | 3.22%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 56       | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 55       | 3.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 54       | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 54       | 3.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 35       | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34       | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 34       | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 34       | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                         | 32       | 1.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 23       | 1.3%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 23       | 1.3%    |
| Intel SATA Controller [RAID mode]                                              | 22       | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21       | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 21       | 1.19%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 21       | 1.19%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 20       | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 18       | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 18       | 1.02%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 18       | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 18       | 1.02%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 17       | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 17       | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16       | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 16       | 0.9%    |
| Phison E12 NVMe Controller                                                     | 15       | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14       | 0.79%   |
| AMD X370 Series Chipset SATA Controller                                        | 14       | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 13       | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                             | 13       | 0.73%   |
| AMD FCH SATA Controller [IDE mode]                                             | 13       | 0.73%   |
| Samsung NVMe SSD Controller 980                                                | 12       | 0.68%   |
| Intel SSD 660P Series                                                          | 12       | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                         | 12       | 0.68%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 11       | 0.62%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 11       | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11       | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 805      | 57.25%  |
| NVMe | 254      | 18.07%  |
| IDE  | 206      | 14.65%  |
| RAID | 69       | 4.91%   |
| SAS  | 51       | 3.63%   |
| SCSI | 21       | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 639      | 63.27%  |
| AMD      | 318      | 31.49%  |
| ARM      | 37       | 3.66%   |
| Unknown  | 8        | 0.79%   |
| IBM      | 2        | 0.2%    |
| VIA      | 1        | 0.1%    |
| Sun      | 1        | 0.1%    |
| Research | 1        | 0.1%    |
| NXP      | 1        | 0.1%    |
| Motorola | 1        | 0.1%    |
| i        | 1        | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 1.47%   |
| AMD GX-412TC SOC                            | 12       | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11       | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11       | 1.08%   |
| ARM Cortex-A55 r2p0                         | 11       | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 11       | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 11       | 1.08%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 1.08%   |
| AMD FX-8350 Eight-Core Processor            | 11       | 1.08%   |
| ARM Cortex-A53 r0p4                         | 10       | 0.98%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 10       | 0.98%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 10       | 0.98%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 9        | 0.88%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 9        | 0.88%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 9        | 0.88%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 8        | 0.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 8        | 0.79%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 8        | 0.79%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 0.79%   |
|                                             | 8        | 0.79%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 7        | 0.69%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 7        | 0.69%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 7        | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 0.69%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 7        | 0.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 7        | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 6        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 0.59%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 6        | 0.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 6        | 0.59%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 6        | 0.59%   |
| Intel Celeron CPU G1610T @ 2.30GHz          | 6        | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6        | 0.59%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 6        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.49%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 5        | 0.49%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.49%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 5        | 0.49%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 137      | 13.52%  |
| Intel Core i7           | 122      | 12.04%  |
| Intel Xeon              | 110      | 10.86%  |
| AMD Ryzen 7             | 64       | 6.32%   |
| Intel Core i3           | 55       | 5.43%   |
| Intel Celeron           | 52       | 5.13%   |
| AMD Ryzen 5             | 52       | 5.13%   |
| Other                   | 49       | 4.84%   |
| AMD Ryzen 9             | 38       | 3.75%   |
| ARM Cortex              | 34       | 3.36%   |
| Intel Atom              | 30       | 2.96%   |
| AMD FX                  | 28       | 2.76%   |
| Intel Pentium           | 26       | 2.57%   |
| Intel Core 2 Duo        | 25       | 2.47%   |
| AMD GX                  | 23       | 2.27%   |
| AMD Ryzen 3             | 18       | 1.78%   |
| Intel Core 2 Quad       | 14       | 1.38%   |
| Intel Pentium 4         | 12       | 1.18%   |
| AMD Ryzen Threadripper  | 9        | 0.89%   |
| Intel Core i9           | 8        | 0.79%   |
| AMD Turion II Neo       | 7        | 0.69%   |
| AMD Phenom II X6        | 7        | 0.69%   |
| AMD Athlon 64 X2        | 7        | 0.69%   |
| AMD Athlon              | 6        | 0.59%   |
| AMD A10                 | 6        | 0.59%   |
| Intel Core 2            | 5        | 0.49%   |
| AMD Phenom II X4        | 5        | 0.49%   |
| AMD Phenom              | 5        | 0.49%   |
| AMD G                   | 5        | 0.49%   |
| Intel Pentium Gold      | 4        | 0.39%   |
| AMD Ryzen 7 PRO         | 4        | 0.39%   |
| AMD Ryzen 5 PRO         | 4        | 0.39%   |
| AMD Sempron             | 3        | 0.3%    |
| AMD Opteron             | 3        | 0.3%    |
| AMD EPYC                | 3        | 0.3%    |
| AMD A4                  | 3        | 0.3%    |
| Intel Xeon Bronze       | 2        | 0.2%    |
| Intel Pentium Dual-Core | 2        | 0.2%    |
| Intel Pentium D         | 2        | 0.2%    |
| AMD Phenom II X2        | 2        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 362      | 35.7%   |
| 2       | 167      | 16.47%  |
| Unknown | 96       | 9.47%   |
| 8       | 86       | 8.48%   |
| 6       | 83       | 8.19%   |
| 16      | 76       | 7.5%    |
| 12      | 54       | 5.33%   |
| 32      | 23       | 2.27%   |
| 24      | 23       | 2.27%   |
| 1       | 21       | 2.07%   |
| 10      | 10       | 0.99%   |
| 64      | 4        | 0.39%   |
| 20      | 2        | 0.2%    |
| 14      | 2        | 0.2%    |
| 3       | 2        | 0.2%    |
| 48      | 1        | 0.1%    |
| 28      | 1        | 0.1%    |
| 11      | 1        | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 939      | 92.88%  |
| Unknown | 46       | 4.55%   |
| 2       | 25       | 2.47%   |
| 4       | 1        | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 579      | 57.38%  |
| 2       | 322      | 31.91%  |
| Unknown | 108      | 10.7%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 95       | 9.37%   |
| KabyLake      | 90       | 8.88%   |
| IvyBridge     | 85       | 8.38%   |
| Unknown       | 81       | 7.99%   |
| Zen 2         | 69       | 6.8%    |
| SandyBridge   | 67       | 6.61%   |
| Skylake       | 52       | 5.13%   |
| Zen 3         | 45       | 4.44%   |
| Zen+          | 42       | 4.14%   |
| Penryn        | 38       | 3.75%   |
| Zen           | 37       | 3.65%   |
| K10           | 33       | 3.25%   |
| CometLake     | 33       | 3.25%   |
| Piledriver    | 31       | 3.06%   |
| Silvermont    | 27       | 2.66%   |
| Westmere      | 22       | 2.17%   |
| Core          | 22       | 2.17%   |
| Bonnell       | 20       | 1.97%   |
| NetBurst      | 18       | 1.78%   |
| Puma          | 17       | 1.68%   |
| Nehalem       | 15       | 1.48%   |
| Broadwell     | 13       | 1.28%   |
| Jaguar        | 12       | 1.18%   |
| K8 Hammer     | 10       | 0.99%   |
| Goldmont      | 9        | 0.89%   |
| Bobcat        | 8        | 0.79%   |
| Goldmont plus | 6        | 0.59%   |
| Excavator     | 4        | 0.39%   |
| Bulldozer     | 4        | 0.39%   |
| Steamroller   | 3        | 0.3%    |
| P6            | 3        | 0.3%    |
| Geode         | 2        | 0.2%    |
| TigerLake     | 1        | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 347      | 35.19%  |
| Nvidia                                       | 318      | 32.25%  |
| AMD                                          | 251      | 25.46%  |
| Matrox Electronics Systems                   | 32       | 3.25%   |
| ASPEED Technology                            | 30       | 3.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.2%    |
| VIA Technologies                             | 2        | 0.2%    |
| S3 Graphics                                  | 2        | 0.2%    |
| Silicon Integrated Systems [SiS]             | 1        | 0.1%    |
| NVidia / SGS Thomson (Joint Venture)         | 1        | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42       | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36       | 3.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 33       | 3.27%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 30       | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26       | 2.58%   |
| Intel HD Graphics 530                                                                    | 26       | 2.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26       | 2.58%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 23       | 2.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 23       | 2.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22       | 2.18%   |
| Intel HD Graphics 630                                                                    | 18       | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16       | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15       | 1.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 14       | 1.39%   |
| Matrox Electronics Systems MGA G200EH                                                    | 13       | 1.29%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 12       | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12       | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 1.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 11       | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 10       | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10       | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 8        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.79%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 8        | 0.79%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 8        | 0.79%   |
| AMD Renoir                                                                               | 8        | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8        | 0.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7        | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 7        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7        | 0.69%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 7        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7        | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7        | 0.69%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7        | 0.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 7        | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 0.69%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7        | 0.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7        | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6        | 0.6%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 300      | 29.62%  |
| 1 x Nvidia                               | 284      | 28.04%  |
| 1 x AMD                                  | 226      | 22.31%  |
| Other                                    | 71       | 7.01%   |
| 1 x Matrox                               | 32       | 3.16%   |
| 1 x ASPEED                               | 27       | 2.67%   |
| Intel + Nvidia                           | 25       | 2.47%   |
| 2 x Intel                                | 11       | 1.09%   |
| 2 x AMD                                  | 11       | 1.09%   |
| Intel + AMD                              | 9        | 0.89%   |
| 2 x Nvidia                               | 3        | 0.3%    |
| 1 x XGI                                  | 2        | 0.2%    |
| 1 x VIA                                  | 2        | 0.2%    |
| 1 x S3 Graphics                          | 2        | 0.2%    |
| Nvidia + ASPEED                          | 2        | 0.2%    |
| AMD + Nvidia                             | 2        | 0.2%    |
| 1 x SiS                                  | 1        | 0.1%    |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 0.1%    |
| Intel + ASPEED                           | 1        | 0.1%    |
| AMD + ASPEED                             | 1        | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 690      | 68.11%  |
| Proprietary | 246      | 24.28%  |
| Unknown     | 77       | 7.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 655      | 63.72%  |
| 1.01-2.0   | 101      | 9.82%   |
| 0.51-1.0   | 64       | 6.23%   |
| 7.01-8.0   | 60       | 5.84%   |
| 3.01-4.0   | 58       | 5.64%   |
| 0.01-0.5   | 35       | 3.4%    |
| 5.01-6.0   | 29       | 2.82%   |
| 8.01-16.0  | 15       | 1.46%   |
| 2.01-3.0   | 10       | 0.97%   |
| 4.01-5.0   | 1        | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 89       | 16.51%  |
| Dell                 | 84       | 15.58%  |
| Goldstar             | 55       | 10.2%   |
| Acer                 | 36       | 6.68%   |
| Hewlett-Packard      | 33       | 6.12%   |
| AOC                  | 27       | 5.01%   |
| Philips              | 22       | 4.08%   |
| BenQ                 | 22       | 4.08%   |
| Ancor Communications | 20       | 3.71%   |
| LG Electronics       | 19       | 3.53%   |
| Iiyama               | 19       | 3.53%   |
| Sony                 | 12       | 2.23%   |
| ViewSonic            | 11       | 2.04%   |
| Lenovo               | 10       | 1.86%   |
| NEC Computers        | 8        | 1.48%   |
| Idek Iiyama          | 7        | 1.3%    |
| Unknown              | 6        | 1.11%   |
| Eizo                 | 6        | 1.11%   |
| ASUSTek Computer     | 5        | 0.93%   |
| MSI                  | 4        | 0.74%   |
| Sceptre Tech         | 3        | 0.56%   |
| Toshiba              | 2        | 0.37%   |
| RTK                  | 2        | 0.37%   |
| Panasonic            | 2        | 0.37%   |
| Microstep            | 2        | 0.37%   |
| Mi                   | 2        | 0.37%   |
| IOD                  | 2        | 0.37%   |
| Insignia             | 2        | 0.37%   |
| IBM                  | 2        | 0.37%   |
| HPN                  | 2        | 0.37%   |
| Fujitsu Siemens      | 2        | 0.37%   |
| Apple                | 2        | 0.37%   |
| VIE                  | 1        | 0.19%   |
| Vestel Elektronik    | 1        | 0.19%   |
| SGT                  | 1        | 0.19%   |
| SAC                  | 1        | 0.19%   |
| Pioneer Electronic   | 1        | 0.19%   |
| Orion                | 1        | 0.19%   |
| Medion               | 1        | 0.19%   |
| Lenovo Group Limited | 1        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                | 6        | 1.02%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5        | 0.85%   |
| MSI G241 MSI3BA4 1920x1080 530x300mm 24.0-inch                       | 4        | 0.68%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 4        | 0.68%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3        | 0.51%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3        | 0.51%   |
| LG Electronics LCD Monitor LG Ultra HD                               | 3        | 0.51%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 3        | 0.51%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 3        | 0.51%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 3        | 0.51%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 3        | 0.51%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 3        | 0.51%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch          | 2        | 0.34%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                | 2        | 0.34%   |
| Sony TV SNY4B03 1920x1080 930x520mm 41.9-inch                        | 2        | 0.34%   |
| Sony LCD Monitor TV XV 1920x1080                                     | 2        | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 2        | 0.34%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 2        | 0.34%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch  | 2        | 0.34%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch  | 2        | 0.34%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch    | 2        | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 2        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                 | 2        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                 | 2        | 0.34%   |
| Samsung Electronics LCD Monitor SAM04FB 1920x1080                    | 2        | 0.34%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2        | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 2        | 0.34%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                | 2        | 0.34%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2        | 0.34%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 2        | 0.34%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch          | 2        | 0.34%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 2        | 0.34%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch             | 2        | 0.34%   |
| Lenovo LCD Monitor LEN0990 1440x900 410x260mm 19.1-inch              | 2        | 0.34%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                           | 2        | 0.34%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch          | 2        | 0.34%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 540x350mm 25.3-inch        | 2        | 0.34%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch        | 2        | 0.34%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                 | 2        | 0.34%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 238      | 44.32%  |
| 3840x2160 (4K)     | 51       | 9.5%    |
| 2560x1440 (QHD)    | 45       | 8.38%   |
| 1920x1200 (WUXGA)  | 43       | 8.01%   |
| 1280x1024 (SXGA)   | 35       | 6.52%   |
| 1680x1050 (WSXGA+) | 18       | 3.35%   |
| Unknown            | 18       | 3.35%   |
| 1600x900 (HD+)     | 13       | 2.42%   |
| 3440x1440          | 11       | 2.05%   |
| 1366x768 (WXGA)    | 10       | 1.86%   |
| 2560x1080          | 9        | 1.68%   |
| 1440x900 (WXGA+)   | 9        | 1.68%   |
| 3840x1080          | 5        | 0.93%   |
| 1024x768 (XGA)     | 5        | 0.93%   |
| 1600x1200          | 4        | 0.74%   |
| 3840x1200          | 2        | 0.37%   |
| 2560x1600          | 2        | 0.37%   |
| 1920x540           | 2        | 0.37%   |
| 7680x2160          | 1        | 0.19%   |
| 5760x1256          | 1        | 0.19%   |
| 5760x1200          | 1        | 0.19%   |
| 5760x1080          | 1        | 0.19%   |
| 3840x1600          | 1        | 0.19%   |
| 3640x1920          | 1        | 0.19%   |
| 3600x1080          | 1        | 0.19%   |
| 3520x1200          | 1        | 0.19%   |
| 3360x1050          | 1        | 0.19%   |
| 2648x1024          | 1        | 0.19%   |
| 2560x2520          | 1        | 0.19%   |
| 2288x1430          | 1        | 0.19%   |
| 2048x1152          | 1        | 0.19%   |
| 1360x768           | 1        | 0.19%   |
| 1280x720 (HD)      | 1        | 0.19%   |
| 11520x2160         | 1        | 0.19%   |
| 1024x600           | 1        | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 107      | 19.81%  |
| 24      | 85       | 15.74%  |
| 27      | 76       | 14.07%  |
| 21      | 59       | 10.93%  |
| 23      | 47       | 8.7%    |
| 19      | 30       | 5.56%   |
| 31      | 21       | 3.89%   |
| 17      | 17       | 3.15%   |
| 22      | 16       | 2.96%   |
| 34      | 11       | 2.04%   |
| 18      | 10       | 1.85%   |
| 15      | 6        | 1.11%   |
| 25      | 5        | 0.93%   |
| 20      | 5        | 0.93%   |
| 29      | 4        | 0.74%   |
| 14      | 4        | 0.74%   |
| 52      | 3        | 0.56%   |
| 42      | 3        | 0.56%   |
| 40      | 3        | 0.56%   |
| 32      | 3        | 0.56%   |
| 26      | 3        | 0.56%   |
| 54      | 2        | 0.37%   |
| 46      | 2        | 0.37%   |
| 41      | 2        | 0.37%   |
| 16      | 2        | 0.37%   |
| 13      | 2        | 0.37%   |
| 74      | 1        | 0.19%   |
| 64      | 1        | 0.19%   |
| 57      | 1        | 0.19%   |
| 55      | 1        | 0.19%   |
| 49      | 1        | 0.19%   |
| 48      | 1        | 0.19%   |
| 47      | 1        | 0.19%   |
| 43      | 1        | 0.19%   |
| 39      | 1        | 0.19%   |
| 37      | 1        | 0.19%   |
| 28      | 1        | 0.19%   |
| 9       | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 200      | 38.1%   |
| Unknown     | 107      | 20.38%  |
| 401-500     | 103      | 19.62%  |
| 601-700     | 32       | 6.1%    |
| 301-350     | 26       | 4.95%   |
| 701-800     | 14       | 2.67%   |
| 1001-1500   | 13       | 2.48%   |
| 351-400     | 12       | 2.29%   |
| 901-1000    | 7        | 1.33%   |
| 201-300     | 5        | 0.95%   |
| 801-900     | 4        | 0.76%   |
| 1501-2000   | 1        | 0.19%   |
| 101-200     | 1        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 296      | 58.04%  |
| Unknown | 99       | 19.41%  |
| 16/10   | 51       | 10%     |
| 5/4     | 27       | 5.29%   |
| 21/9    | 16       | 3.14%   |
| 4/3     | 10       | 1.96%   |
| 3/2     | 7        | 1.37%   |
| 6/5     | 2        | 0.39%   |
| 32/9    | 2        | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 164      | 30.94%  |
| Unknown        | 107      | 20.19%  |
| 301-350        | 80       | 15.09%  |
| 251-300        | 39       | 7.36%   |
| 151-200        | 38       | 7.17%   |
| 351-500        | 37       | 6.98%   |
| 141-150        | 25       | 4.72%   |
| 501-1000       | 15       | 2.83%   |
| More than 1000 | 10       | 1.89%   |
| 101-110        | 6        | 1.13%   |
| 121-130        | 3        | 0.57%   |
| 111-120        | 3        | 0.57%   |
| 81-90          | 2        | 0.38%   |
| 1-40           | 1        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 268      | 51.74%  |
| Unknown | 107      | 20.66%  |
| 101-120 | 92       | 17.76%  |
| 121-160 | 26       | 5.02%   |
| 161-240 | 18       | 3.47%   |
| 1-50    | 7        | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 513      | 50.1%   |
| 1     | 434      | 42.38%  |
| 2     | 69       | 6.74%   |
| 3     | 8        | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 527      | 40.98%  |
| Realtek Semiconductor             | 466      | 36.24%  |
| Qualcomm Atheros                  | 76       | 5.91%   |
| Broadcom                          | 65       | 5.05%   |
| Marvell Technology Group          | 12       | 0.93%   |
| Ralink Technology                 | 11       | 0.86%   |
| Ralink                            | 11       | 0.86%   |
| Mellanox Technologies             | 11       | 0.86%   |
| TP-Link                           | 10       | 0.78%   |
| VIA Technologies                  | 9        | 0.7%    |
| D-Link System                     | 6        | 0.47%   |
| American Megatrends               | 6        | 0.47%   |
| Samsung Electronics               | 5        | 0.39%   |
| Aquantia                          | 5        | 0.39%   |
| Xiaomi                            | 4        | 0.31%   |
| MediaTek                          | 4        | 0.31%   |
| 3Com                              | 4        | 0.31%   |
| Nvidia                            | 3        | 0.23%   |
| IMC Networks                      | 3        | 0.23%   |
| Dresden Elektronik                | 3        | 0.23%   |
| Chelsio Communications            | 3        | 0.23%   |
| Arduino SA                        | 3        | 0.23%   |
| Apple                             | 3        | 0.23%   |
| Qualcomm Atheros Communications   | 2        | 0.16%   |
| Qualcomm                          | 2        | 0.16%   |
| Huawei Technologies               | 2        | 0.16%   |
| D-Link                            | 2        | 0.16%   |
| ADMtek                            | 2        | 0.16%   |
| Accton Technology                 | 2        | 0.16%   |
| U.S. Robotics                     | 1        | 0.08%   |
| Tehuti Networks                   | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus | 1        | 0.08%   |
| Solarflare Communications         | 1        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.08%   |
| Sigma Designs                     | 1        | 0.08%   |
| Pulse-Eight                       | 1        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.08%   |
| Microchip Technology              | 1        | 0.08%   |
| Linksys                           | 1        | 0.08%   |
| LG Electronics                    | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 378      | 25.03%  |
| Intel I211 Gigabit Network Connection                                         | 97       | 6.42%   |
| Intel 82574L Gigabit Network Connection                                       | 53       | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 46       | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                             | 43       | 2.85%   |
| Intel Wi-Fi 6 AX200                                                           | 40       | 2.65%   |
| Intel I210 Gigabit Network Connection                                         | 39       | 2.58%   |
| Intel 82579V Gigabit Network Connection                                       | 26       | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                         | 25       | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 24       | 1.59%   |
| Intel Ethernet Controller I225-V                                              | 23       | 1.52%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 1.32%   |
| Intel I350 Gigabit Network Connection                                         | 16       | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                          | 16       | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 16       | 1.06%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16       | 1.06%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 0.79%   |
| Intel Wireless-AC 9260                                                        | 11       | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 11       | 0.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 0.66%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 10       | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 9        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9        | 0.6%    |
| Intel Ethernet Connection I217-V                                              | 9        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 9        | 0.6%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 9        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 8        | 0.53%   |
| Intel Wireless 7265                                                           | 8        | 0.53%   |
| Intel Ethernet Controller X550                                                | 8        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                         | 8        | 0.53%   |
| Intel 82576 Gigabit Network Connection                                        | 8        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 8        | 0.53%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 8        | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 7        | 0.46%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 114      | 41.45%  |
| Realtek Semiconductor                 | 51       | 18.55%  |
| Qualcomm Atheros                      | 49       | 17.82%  |
| Broadcom                              | 12       | 4.36%   |
| Ralink Technology                     | 11       | 4%      |
| Ralink                                | 11       | 4%      |
| TP-Link                               | 10       | 3.64%   |
| MediaTek                              | 4        | 1.45%   |
| IMC Networks                          | 3        | 1.09%   |
| Qualcomm Atheros Communications       | 2        | 0.73%   |
| D-Link                                | 2        | 0.73%   |
| Linksys                               | 1        | 0.36%   |
| Edimax Technology                     | 1        | 0.36%   |
| Atheros                               | 1        | 0.36%   |
| ASUSTek Computer                      | 1        | 0.36%   |
| AboCom Systems                        | 1        | 0.36%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 40       | 14.34%  |
| Intel Wireless-AC 9260                                                                        | 11       | 3.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 11       | 3.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 9        | 3.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 9        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 9        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 8        | 2.87%   |
| Intel Wireless 7265                                                                           | 8        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 6        | 2.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 6        | 2.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 6        | 2.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 5        | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 5        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 5        | 1.79%   |
| Intel Wireless 8260                                                                           | 5        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 5        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 4        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4        | 1.43%   |
| Intel Wireless 8265 / 8275                                                                    | 4        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 4        | 1.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 4        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 3        | 1.08%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                                  | 3        | 1.08%   |
| Ralink RT5572 Wireless Adapter                                                                | 3        | 1.08%   |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 1.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 3        | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 3        | 1.08%   |
| Intel Wireless 7260                                                                           | 3        | 1.08%   |
| Intel Wireless 3160                                                                           | 3        | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 0.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 2        | 0.72%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 2        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 0.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 2        | 0.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 2        | 0.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2        | 0.72%   |
| Realtek Bluetooth Adapter                                                                     | 2        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 495      | 45.29%  |
| Realtek Semiconductor             | 442      | 40.44%  |
| Broadcom                          | 53       | 4.85%   |
| Qualcomm Atheros                  | 30       | 2.74%   |
| Marvell Technology Group          | 12       | 1.1%    |
| VIA Technologies                  | 9        | 0.82%   |
| D-Link System                     | 6        | 0.55%   |
| American Megatrends               | 6        | 0.55%   |
| Samsung Electronics               | 5        | 0.46%   |
| Aquantia                          | 5        | 0.46%   |
| Xiaomi                            | 4        | 0.37%   |
| 3Com                              | 4        | 0.37%   |
| Nvidia                            | 3        | 0.27%   |
| Chelsio Communications            | 3        | 0.27%   |
| Qualcomm                          | 2        | 0.18%   |
| Apple                             | 2        | 0.18%   |
| ADMtek                            | 2        | 0.18%   |
| U.S. Robotics                     | 1        | 0.09%   |
| Tehuti Networks                   | 1        | 0.09%   |
| Sundance Technology Inc / IC Plus | 1        | 0.09%   |
| Solarflare Communications         | 1        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.09%   |
| Huawei Technologies               | 1        | 0.09%   |
| Emulex                            | 1        | 0.09%   |
| Davicom Semiconductor             | 1        | 0.09%   |
| Accton Technology                 | 1        | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 378      | 31.68%  |
| Intel I211 Gigabit Network Connection                                         | 97       | 8.13%   |
| Intel 82574L Gigabit Network Connection                                       | 53       | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 46       | 3.86%   |
| Intel I210 Gigabit Network Connection                                         | 39       | 3.27%   |
| Realtek RTL8125 2.5GbE Controller                                             | 38       | 3.19%   |
| Intel 82579V Gigabit Network Connection                                       | 26       | 2.18%   |
| Intel Ethernet Connection (2) I219-LM                                         | 25       | 2.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 24       | 2.01%   |
| Intel Ethernet Controller I225-V                                              | 23       | 1.93%   |
| Intel Ethernet Connection I217-LM                                             | 20       | 1.68%   |
| Intel I350 Gigabit Network Connection                                         | 16       | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                          | 16       | 1.34%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 16       | 1.34%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 16       | 1.34%   |
| Intel Ethernet Connection (2) I218-V                                          | 12       | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 0.84%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 10       | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 9        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9        | 0.75%   |
| Intel Ethernet Connection I217-V                                              | 9        | 0.75%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 9        | 0.75%   |
| Intel Ethernet Controller X550                                                | 8        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                         | 8        | 0.67%   |
| Intel 82576 Gigabit Network Connection                                        | 8        | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 8        | 0.67%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 8        | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 7        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 7        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 7        | 0.59%   |
| Intel 82580 Gigabit Network Connection                                        | 7        | 0.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 0.5%    |
| American Megatrends Virtual Ethernet                                          | 6        | 0.5%    |
| VIA VT6105/VT6106S [Rhine-III]                                                | 5        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5        | 0.42%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 5        | 0.42%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5        | 0.42%   |
| Intel Ethernet Connection (2) I218-LM                                         | 5        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                         | 5        | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 5        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 966      | 76.55%  |
| WiFi     | 258      | 20.44%  |
| Unknown  | 25       | 1.98%   |
| Modem    | 13       | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 918      | 89.91%  |
| WiFi     | 98       | 9.6%    |
| Unknown  | 5        | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 499      | 48.92%  |
| 2     | 311      | 30.49%  |
| 3     | 100      | 9.8%    |
| 4     | 39       | 3.82%   |
| 0     | 36       | 3.53%   |
| 5     | 15       | 1.47%   |
| 6     | 12       | 1.18%   |
| 7     | 5        | 0.49%   |
| 8     | 2        | 0.2%    |
| 10    | 1        | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 906      | 87.54%  |
| Yes  | 129      | 12.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 102      | 56.35%  |
| Cambridge Silicon Radio         | 27       | 14.92%  |
| ASUSTek Computer                | 12       | 6.63%   |
| Realtek Semiconductor           | 11       | 6.08%   |
| Qualcomm Atheros Communications | 6        | 3.31%   |
| Broadcom                        | 5        | 2.76%   |
| Apple                           | 5        | 2.76%   |
| IMC Networks                    | 4        | 2.21%   |
| MediaTek                        | 3        | 1.66%   |
| Lite-On Technology              | 3        | 1.66%   |
| Ralink                          | 1        | 0.55%   |
| Micro Star International        | 1        | 0.55%   |
| Foxconn / Hon Hai               | 1        | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 36       | 19.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 27       | 14.67%  |
| Intel Bluetooth wireless interface                          | 19       | 10.33%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 12       | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12       | 6.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 10       | 5.43%   |
| Intel AX201 Bluetooth                                       | 9        | 4.89%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5        | 2.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 5        | 2.72%   |
| Realtek Bluetooth Adapter                                   | 4        | 2.17%   |
| Intel AX210 Bluetooth                                       | 4        | 2.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 4        | 2.17%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3        | 1.63%   |
| Apple Bluetooth Host Controller                             | 3        | 1.63%   |
| Realtek Bluetooth 4.2 Adapter                               | 2        | 1.09%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2        | 1.09%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 2        | 1.09%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 2        | 1.09%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 2        | 1.09%   |
| ASUS Bluetooth USB module                                   | 2        | 1.09%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2        | 1.09%   |
| Ralink RT3290 Bluetooth                                     | 1        | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1        | 0.54%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1        | 0.54%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1        | 0.54%   |
| Lite-On Bluetooth USB Module                                | 1        | 0.54%   |
| Lite-On Atheros AR9462 Bluetooth 4.0 + HS                   | 1        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 0.54%   |
| Intel Wireless Bluetooth                                    | 1        | 0.54%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 0.54%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1        | 0.54%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1        | 0.54%   |
| ASUS USB-BT500                                              | 1        | 0.54%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 474      | 38.41%  |
| AMD                                          | 328      | 26.58%  |
| Nvidia                                       | 287      | 23.26%  |
| C-Media Electronics                          | 20       | 1.62%   |
| Creative Labs                                | 16       | 1.3%    |
| Logitech                                     | 14       | 1.13%   |
| Texas Instruments                            | 7        | 0.57%   |
| Realtek Semiconductor                        | 6        | 0.49%   |
| Kingston Technology                          | 4        | 0.32%   |
| JMTek                                        | 4        | 0.32%   |
| Focusrite-Novation                           | 4        | 0.32%   |
| Blue Microphones                             | 4        | 0.32%   |
| BEHRINGER International                      | 4        | 0.32%   |
| ASUSTek Computer                             | 4        | 0.32%   |
| Tenx Technology                              | 3        | 0.24%   |
| SteelSeries ApS                              | 3        | 0.24%   |
| Sony                                         | 3        | 0.24%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.24%   |
| Yamaha                                       | 2        | 0.16%   |
| VIA Technologies                             | 2        | 0.16%   |
| Trust                                        | 2        | 0.16%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.16%   |
| Plantronics                                  | 2        | 0.16%   |
| Micro Star International                     | 2        | 0.16%   |
| M-Audio                                      | 2        | 0.16%   |
| GN Netcom                                    | 2        | 0.16%   |
| Generalplus Technology                       | 2        | 0.16%   |
| Creative Technology                          | 2        | 0.16%   |
| Corsair                                      | 2        | 0.16%   |
| Cambridge Silicon Radio                      | 2        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.08%   |
| XMOS                                         | 1        | 0.08%   |
| Xilinx                                       | 1        | 0.08%   |
| Samsung Electronics                          | 1        | 0.08%   |
| Samson Technologies                          | 1        | 0.08%   |
| RODE Microphones                             | 1        | 0.08%   |
| ROCCAT                                       | 1        | 0.08%   |
| Razer USA                                    | 1        | 0.08%   |
| Microsoft                                    | 1        | 0.08%   |
| Micronas                                     | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 83       | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 53       | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 50       | 3.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 48       | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 48       | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 47       | 3.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 42       | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41       | 2.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41       | 2.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 39       | 2.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 38       | 2.64%   |
| Intel 200 Series PCH HD Audio                                              | 31       | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 30       | 2.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25       | 1.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25       | 1.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25       | 1.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 23       | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22       | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 20       | 1.39%   |
| Nvidia High Definition Audio Controller                                    | 20       | 1.39%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 20       | 1.39%   |
| AMD FCH Azalia Controller                                                  | 19       | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18       | 1.25%   |
| Nvidia GF119 HDMI Audio Controller                                         | 17       | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 15       | 1.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15       | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 14       | 0.97%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 14       | 0.97%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 0.97%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 14       | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 14       | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 13       | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12       | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 12       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12       | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10       | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 180      | 17.16%  |
| Unknown                      | 166      | 15.82%  |
| Corsair                      | 130      | 12.39%  |
| Samsung Electronics          | 105      | 10.01%  |
| SK hynix                     | 96       | 9.15%   |
| Crucial                      | 80       | 7.63%   |
| G.Skill                      | 67       | 6.39%   |
| Micron Technology            | 65       | 6.2%    |
| A-DATA Technology            | 21       | 2%      |
| Unknown                      | 12       | 1.14%   |
| Patriot                      | 11       | 1.05%   |
| GOODRAM                      | 10       | 0.95%   |
| Team                         | 9        | 0.86%   |
| Ramaxel Technology           | 9        | 0.86%   |
| Nanya Technology             | 9        | 0.86%   |
| Hewlett-Packard              | 9        | 0.86%   |
| Transcend                    | 7        | 0.67%   |
| Patriot Memory (PDP Systems) | 6        | 0.57%   |
| AMD                          | 4        | 0.38%   |
| Unknown (ABCD)               | 3        | 0.29%   |
| Super Talent                 | 3        | 0.29%   |
| Qimonda                      | 3        | 0.29%   |
| Avant                        | 3        | 0.29%   |
| tigo                         | 2        | 0.19%   |
| Silicon Power                | 2        | 0.19%   |
| PNY                          | 2        | 0.19%   |
| Kingmax                      | 2        | 0.19%   |
| HPE                          | 2        | 0.19%   |
| Goldkey                      | 2        | 0.19%   |
| Golden Empire                | 2        | 0.19%   |
| Elpida                       | 2        | 0.19%   |
| Apacer                       | 2        | 0.19%   |
| V-GeN                        | 1        | 0.1%    |
| V-Color                      | 1        | 0.1%    |
| Unknown (AB)                 | 1        | 0.1%    |
| Unknown (8A5D)               | 1        | 0.1%    |
| Unknown (0x05F7)             | 1        | 0.1%    |
| TIMETEC                      | 1        | 0.1%    |
| Smart                        | 1        | 0.1%    |
| SK_Hynix                     | 1        | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 13       | 1.13%   |
| Unknown                                                | 12       | 1.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 11       | 0.96%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 10       | 0.87%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 8        | 0.7%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s      | 7        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 6        | 0.52%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 6        | 0.52%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s           | 6        | 0.52%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s   | 6        | 0.52%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s    | 6        | 0.52%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s  | 6        | 0.52%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 5        | 0.43%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 5        | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 5        | 0.43%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 5        | 0.43%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 5        | 0.43%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s   | 5        | 0.43%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s  | 5        | 0.43%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s | 5        | 0.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s  | 5        | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 4        | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 4        | 0.35%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 4        | 0.35%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 4        | 0.35%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.35%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.35%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s   | 4        | 0.35%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 2666MT/s   | 4        | 0.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 4        | 0.35%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 4        | 0.35%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s    | 4        | 0.35%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 4        | 0.35%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM 1333MT/s       | 4        | 0.35%   |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s  | 4        | 0.35%   |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s  | 4        | 0.35%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s    | 4        | 0.35%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 2933MT/s | 4        | 0.35%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s | 4        | 0.35%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 3        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 416      | 44.4%   |
| DDR3         | 357      | 38.1%   |
| Unknown      | 55       | 5.87%   |
| DDR2         | 52       | 5.55%   |
| SDRAM        | 28       | 2.99%   |
| DDR          | 16       | 1.71%   |
| DDR5         | 6        | 0.64%   |
| LPDDR4       | 3        | 0.32%   |
| DRAM         | 2        | 0.21%   |
| LPDDR3       | 1        | 0.11%   |
| DDR2 FB-DIMM | 1        | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 838      | 90.11%  |
| SODIMM       | 84       | 9.03%   |
| RIMM         | 6        | 0.65%   |
| Row Of Chips | 1        | 0.11%   |
| FB-DIMM      | 1        | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 351      | 34.48%  |
| 4096  | 238      | 23.38%  |
| 16384 | 194      | 19.06%  |
| 2048  | 123      | 12.08%  |
| 32768 | 55       | 5.4%    |
| 1024  | 38       | 3.73%   |
| 512   | 13       | 1.28%   |
| 128   | 2        | 0.2%    |
| 256   | 1        | 0.1%    |
| 64    | 1        | 0.1%    |
| 32    | 1        | 0.1%    |
| 8     | 1        | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 201      | 20.24%  |
| 1333    | 152      | 15.31%  |
| 3200    | 118      | 11.88%  |
| 2400    | 91       | 9.16%   |
| 2133    | 85       | 8.56%   |
| 800     | 58       | 5.84%   |
| 2667    | 57       | 5.74%   |
| 2666    | 31       | 3.12%   |
| 667     | 28       | 2.82%   |
| Unknown | 25       | 2.52%   |
| 3000    | 21       | 2.11%   |
| 3600    | 20       | 2.01%   |
| 1066    | 14       | 1.41%   |
| 2933    | 13       | 1.31%   |
| 1866    | 13       | 1.31%   |
| 533     | 10       | 1.01%   |
| 400     | 8        | 0.81%   |
| 1867    | 6        | 0.6%    |
| 1067    | 6        | 0.6%    |
| 4800    | 4        | 0.4%    |
| 3400    | 4        | 0.4%    |
| 4000    | 3        | 0.3%    |
| 1334    | 3        | 0.3%    |
| 5200    | 2        | 0.2%    |
| 3534    | 2        | 0.2%    |
| 2048    | 2        | 0.2%    |
| 1332    | 2        | 0.2%    |
| 333     | 2        | 0.2%    |
| 65535   | 1        | 0.1%    |
| 6400    | 1        | 0.1%    |
| 4133    | 1        | 0.1%    |
| 3500    | 1        | 0.1%    |
| 3066    | 1        | 0.1%    |
| 2800    | 1        | 0.1%    |
| 2134    | 1        | 0.1%    |
| 1800    | 1        | 0.1%    |
| 1639    | 1        | 0.1%    |
| 1400    | 1        | 0.1%    |
| 933     | 1        | 0.1%    |
| 266     | 1        | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 4        | 36.36%  |
| Hewlett-Packard     | 2        | 18.18%  |
| Seiko Epson         | 1        | 9.09%   |
| QinHeng Electronics | 1        | 9.09%   |
| Prolific Technology | 1        | 9.09%   |
| Dymo-CoStar         | 1        | 9.09%   |
| Canon               | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson Printer                                                                        | 1        | 9.09%   |
| QinHeng CH340S                                                                             | 1        | 9.09%   |
| Prolific PL2305 Parallel Port                                                              | 1        | 9.09%   |
| HP LaserJet 1012                                                                           | 1        | 9.09%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1        | 9.09%   |
| Dymo-CoStar LabelWriter 450                                                                | 1        | 9.09%   |
| Canon LBP2900                                                                              | 1        | 9.09%   |
| Brother MFC-7360N                                                                          | 1        | 9.09%   |
| Brother HL-L5200DW series                                                                  | 1        | 9.09%   |
| Brother HL-2030 Laser Printer                                                              | 1        | 9.09%   |
| Brother HL-1430 Laser Printer                                                              | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 60%     |
| Seiko Epson     | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Desktops | Percent |
|-------------------------------------------------------------------------------------|----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1        | 20%     |
| HP ScanJet 5300c/5370c                                                              | 1        | 20%     |
| Canon CanoScan LIDE 25                                                              | 1        | 20%     |
| Canon CanoScan LiDE 220                                                             | 1        | 20%     |
| Canon CanoScan LiDE 110                                                             | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Logitech                  | 33       | 54.1%   |
| Microdia                  | 9        | 14.75%  |
| WCM_USB                   | 2        | 3.28%   |
| Trust                     | 2        | 3.28%   |
| SHENZHEN EMEET TECHNOLOGY | 2        | 3.28%   |
| ARC International         | 2        | 3.28%   |
| YGTek                     | 1        | 1.64%   |
| Valve Software            | 1        | 1.64%   |
| Suyin                     | 1        | 1.64%   |
| Sonix Technology          | 1        | 1.64%   |
| Realtek Semiconductor     | 1        | 1.64%   |
| OmniVision Technologies   | 1        | 1.64%   |
| Lenovo                    | 1        | 1.64%   |
| Huawei Technologies       | 1        | 1.64%   |
| Cubeternet                | 1        | 1.64%   |
| Aveo Technology           | 1        | 1.64%   |
| Arkmicro Technologies     | 1        | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 11       | 18.03%  |
| Logitech HD Pro Webcam C920                    | 4        | 6.56%   |
| Logitech C920 PRO HD Webcam                    | 3        | 4.92%   |
| WCM_USB WEB CAM                                | 2        | 3.28%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 2        | 3.28%   |
| Microdia Webcam Vitade AF                      | 2        | 3.28%   |
| Microdia USB 2.0 Camera                        | 2        | 3.28%   |
| Microdia HP Integrated Webcam                  | 2        | 3.28%   |
| Logitech Webcam C310                           | 2        | 3.28%   |
| Logitech Labtec Webcam Pro                     | 2        | 3.28%   |
| Logitech C922 Pro Stream Webcam                | 2        | 3.28%   |
| Logitech C505 HD Webcam                        | 2        | 3.28%   |
| Logitech BRIO Ultra HD Webcam                  | 2        | 3.28%   |
| ARC International Camera                       | 2        | 3.28%   |
| YGTek Webcam                                   | 1        | 1.64%   |
| Valve Software 3D Camera                       | 1        | 1.64%   |
| Trust Trust QHD Webcam                         | 1        | 1.64%   |
| Trust Canyon CNS-CWC6 Webcam                   | 1        | 1.64%   |
| Suyin Acer CrystalEye Webcam                   | 1        | 1.64%   |
| Sonix FHD Webcam                               | 1        | 1.64%   |
| Realtek USB Video Device                       | 1        | 1.64%   |
| OmniVision Monitor Webcam                      | 1        | 1.64%   |
| Microdia REDRAGON Live Camera Audio            | 1        | 1.64%   |
| Microdia JOYACCESS JA-Webcam                   | 1        | 1.64%   |
| Microdia Camera                                | 1        | 1.64%   |
| Logitech Webcam C930e                          | 1        | 1.64%   |
| Logitech Webcam C170                           | 1        | 1.64%   |
| Logitech Logitech Webcam C925e                 | 1        | 1.64%   |
| Logitech HD Webcam C615                        | 1        | 1.64%   |
| Logitech HD Webcam C525                        | 1        | 1.64%   |
| Lenovo Integrated Camera                       | 1        | 1.64%   |
| Huawei HiCamera                                | 1        | 1.64%   |
| Cubeternet GL-UPC822 UVC WebCam                | 1        | 1.64%   |
| Aveo USB2.0 Camera                             | 1        | 1.64%   |
| Arkmicro USB 2.0 PC CAMERA                     | 1        | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| FocalTech Systems | 1        | 50%     |
| DigitalPersona    | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| FocalTech Systems Fingerprint Reader | 1        | 50%     |
| DigitalPersona Fingerprint Reader    | 1        | 50%     |

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
| 1     | 426      | 41.04%  |
| 0     | 425      | 40.94%  |
| 2     | 148      | 14.26%  |
| 3     | 31       | 2.99%   |
| 4     | 6        | 0.58%   |
| 6     | 2        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 457      | 59.9%   |
| Net/wireless             | 94       | 12.32%  |
| Bluetooth                | 67       | 8.78%   |
| Firewire controller      | 63       | 8.26%   |
| Sound                    | 23       | 3.01%   |
| Net/ethernet             | 20       | 2.62%   |
| Network                  | 17       | 2.23%   |
| Card reader              | 14       | 1.83%   |
| Dvb card                 | 4        | 0.52%   |
| Storage/raid             | 2        | 0.26%   |
| Fingerprint reader       | 2        | 0.26%   |

