BSD in Sweden - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

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

Total: 120

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 82A1                        | [2d7d9105f7](https://bsd-hardware.info/?probe=2d7d9105f7) | Jan 13, 2023 |
| Gigabyte      | G31M-ES2C                   | [8353660219](https://bsd-hardware.info/?probe=8353660219) | Jan 08, 2023 |
| ASRock        | E3C226D2I                   | [5dfcf8051d](https://bsd-hardware.info/?probe=5dfcf8051d) | Jan 06, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Unknown       | Unknown                     | [b4d44b0018](https://bsd-hardware.info/?probe=b4d44b0018) | Dec 26, 2022 |
| ACMA          | X8SIE                       | [01898b2ffb](https://bsd-hardware.info/?probe=01898b2ffb) | Dec 21, 2022 |
| PC Engines    | APU3                        | [5597cca988](https://bsd-hardware.info/?probe=5597cca988) | Dec 17, 2022 |
| ACMA          | X8SIE                       | [361e4ccc04](https://bsd-hardware.info/?probe=361e4ccc04) | Dec 05, 2022 |
| ACMA          | X8SIE                       | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ACMA          | X8SIE                       | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Intel         | CRESCENTBAY                 | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2C                   | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Lenovo        | ThinkServer RS140           | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| Cisco         | ASA5515 A0                  | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | P5L-VM 1394                 | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |
| Unknown       | Unknown                     | [e5efeb3781](https://bsd-hardware.info/?probe=e5efeb3781) | Aug 24, 2022 |
| Unknown       | Unknown                     | [9d1eb045e5](https://bsd-hardware.info/?probe=9d1eb045e5) | Aug 20, 2022 |
| ASRock        | X399 Taichi                 | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| ASUSTek       | CM6731_CM6431_CM6331        | [6e40b41bc3](https://bsd-hardware.info/?probe=6e40b41bc3) | Aug 04, 2022 |
| Gigabyte      | Z87M-D3H                    | [59ae6fc283](https://bsd-hardware.info/?probe=59ae6fc283) | Jul 26, 2022 |
| Supermicro    | X11SSV-M4                   | [444d9ed75e](https://bsd-hardware.info/?probe=444d9ed75e) | Jul 04, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [ea22a644f6](https://bsd-hardware.info/?probe=ea22a644f6) | Jul 04, 2022 |
| PC Engines    | APU                         | [f41e59d78b](https://bsd-hardware.info/?probe=f41e59d78b) | Jun 11, 2022 |
| MSI           | MS-7369                     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Intel         | CRESCENTBAY                 | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| Shuttle       | SH570                       | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| HPE           | ProLiant MicroServer Gen... | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Gigabyte      | G31M-ES2C                   | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| ASUSTek       | P8H77-I                     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| Lenovo        | ThinkServer RS140           | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
| Intel         | DH61AG AAG81491-600         | [fd9659a9fe](https://bsd-hardware.info/?probe=fd9659a9fe) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | [34633c2ca8](https://bsd-hardware.info/?probe=34633c2ca8) | Dec 02, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [a6b7ceeada](https://bsd-hardware.info/?probe=a6b7ceeada) | Oct 20, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | [4fdd90135a](https://bsd-hardware.info/?probe=4fdd90135a) | Oct 20, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| Gigabyte      | Z87M-D3H                    | [8cb8c4dbf4](https://bsd-hardware.info/?probe=8cb8c4dbf4) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [4737978dbf](https://bsd-hardware.info/?probe=4737978dbf) | Aug 18, 2021 |
| HPE           | ProLiant MicroServer Gen... | [04d9692802](https://bsd-hardware.info/?probe=04d9692802) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | [24df2da075](https://bsd-hardware.info/?probe=24df2da075) | Aug 08, 2021 |
| PC Engines    | apu4                        | [815567b75c](https://bsd-hardware.info/?probe=815567b75c) | Aug 02, 2021 |
| PC Engines    | apu4                        | [77fa195d5e](https://bsd-hardware.info/?probe=77fa195d5e) | Aug 02, 2021 |
| ASUSTek       | P8H77-I                     | [52e8a39fb1](https://bsd-hardware.info/?probe=52e8a39fb1) | Jul 19, 2021 |
| Protectli     | FW4B Ver                    | [452a8558c0](https://bsd-hardware.info/?probe=452a8558c0) | Jul 09, 2021 |
| Dell          | 05XGC8 A01                  | [b9841b1272](https://bsd-hardware.info/?probe=b9841b1272) | Jul 08, 2021 |
| Unknown       | Unknown                     | [935263c5a0](https://bsd-hardware.info/?probe=935263c5a0) | Jul 03, 2021 |
| HP            | 82A1                        | [dba57fb77f](https://bsd-hardware.info/?probe=dba57fb77f) | Jun 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | [18e34c37cd](https://bsd-hardware.info/?probe=18e34c37cd) | Jun 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | [3d717eec8f](https://bsd-hardware.info/?probe=3d717eec8f) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| ASUSTek       | P5Q DELUXE                  | [5091db2ace](https://bsd-hardware.info/?probe=5091db2ace) | Jun 16, 2021 |
| MSI           | Z97 GAMING 3                | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | X99 WS                      | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| PC Engines    | APU2                        | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
| ASUSTek       | Z87-DELUXE/DUAL             | [69a811cae5](https://bsd-hardware.info/?probe=69a811cae5) | May 25, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [586a4db247](https://bsd-hardware.info/?probe=586a4db247) | May 20, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [eb0c02a451](https://bsd-hardware.info/?probe=eb0c02a451) | May 19, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| ASRock        | X99 WS                      | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| ASUSTek       | All Series                  | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Unknown       | YL-J3160L4                  | [ad564817c9](https://bsd-hardware.info/?probe=ad564817c9) | Apr 11, 2021 |
| Unknown       | YL-J3160L4                  | [0712c3048c](https://bsd-hardware.info/?probe=0712c3048c) | Apr 11, 2021 |
| Shuttle       | FH170                       | [d36fccf7b7](https://bsd-hardware.info/?probe=d36fccf7b7) | Apr 01, 2021 |
| MSI           | IONA                        | [5f857882ff](https://bsd-hardware.info/?probe=5f857882ff) | Mar 25, 2021 |
| Unknown       | Unknown                     | [93ef7a4b6e](https://bsd-hardware.info/?probe=93ef7a4b6e) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | 8054                        | [1db522699a](https://bsd-hardware.info/?probe=1db522699a) | Mar 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [ddc66bc2fb](https://bsd-hardware.info/?probe=ddc66bc2fb) | Mar 20, 2021 |
| Gigabyte      | 970A-DS3P                   | [a5833ca2c9](https://bsd-hardware.info/?probe=a5833ca2c9) | Mar 18, 2021 |
| HP            | 8053                        | [b7ebdfe456](https://bsd-hardware.info/?probe=b7ebdfe456) | Mar 17, 2021 |
| ASUSTek       | P8H67-M                     | [e95d6c6972](https://bsd-hardware.info/?probe=e95d6c6972) | Mar 17, 2021 |
| ADI           | MinnowBoard Turbot          | [ebd85cee04](https://bsd-hardware.info/?probe=ebd85cee04) | Mar 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | [93c9f14bf0](https://bsd-hardware.info/?probe=93c9f14bf0) | Mar 12, 2021 |
| Dell          | 0XCR8D A02                  | [af5d6a85ef](https://bsd-hardware.info/?probe=af5d6a85ef) | Mar 09, 2021 |
| Dell          | 00V62H A00                  | [a9f921e29b](https://bsd-hardware.info/?probe=a9f921e29b) | Mar 03, 2021 |
| Intel         | DQ67SW AAG12527-306         | [a4fb7ae326](https://bsd-hardware.info/?probe=a4fb7ae326) | Mar 02, 2021 |
| Unknown       | Unknown                     | [b00dc0301a](https://bsd-hardware.info/?probe=b00dc0301a) | Feb 27, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [da62664934](https://bsd-hardware.info/?probe=da62664934) | Feb 23, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [5ca10a4860](https://bsd-hardware.info/?probe=5ca10a4860) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [263a74d1ce](https://bsd-hardware.info/?probe=263a74d1ce) | Feb 12, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [508b3afc1c](https://bsd-hardware.info/?probe=508b3afc1c) | Feb 09, 2021 |
| Lenovo        | 3098 0B98401 PRO            | [8b9f162f70](https://bsd-hardware.info/?probe=8b9f162f70) | Feb 09, 2021 |
| Deciso        | Netboard A10 V2.1           | [dfb0240726](https://bsd-hardware.info/?probe=dfb0240726) | Feb 05, 2021 |
| PC Engines    | APU2                        | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| ADI           | MinnowBoard Turbot          | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| ASUSTek       | All Series                  | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| PC Engines    | APU2                        | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| PC Engines    | APU2                        | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | APU2                        | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
| PC Engines    | APU2                        | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| HP            | ProLiant ML30 Gen9          | [ecaec68cdb](https://bsd-hardware.info/?probe=ecaec68cdb) | Oct 27, 2020 |
| Wistron       | ProLiant ML110 G6           | [0d2e0f44c1](https://bsd-hardware.info/?probe=0d2e0f44c1) | Aug 06, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [6245f1e175](https://bsd-hardware.info/?probe=6245f1e175) | Aug 06, 2020 |
| Unknown       | Unknown                     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OPNsense 21.1     | 8        | 8.33%   |
| OPNsense 21.1.3   | 5        | 5.21%   |
| OPNsense 21.1.2   | 5        | 5.21%   |
| OPNsense 22.7.8   | 4        | 4.17%   |
| OPNsense 22.7.10  | 4        | 4.17%   |
| OPNsense 21.7.7   | 4        | 4.17%   |
| OPNsense 22.7.2   | 3        | 3.13%   |
| OPNsense 21.7.3   | 3        | 3.13%   |
| OPNsense 21.1.8   | 3        | 3.13%   |
| OPNsense 21.1.5   | 3        | 3.13%   |
| OpenBSD 6.8       | 3        | 3.13%   |
| OPNsense 22.7.9   | 2        | 2.08%   |
| OPNsense 22.7.6   | 2        | 2.08%   |
| OPNsense 22.1.9   | 2        | 2.08%   |
| OPNsense 22.1.3   | 2        | 2.08%   |
| OPNsense 21.7.6   | 2        | 2.08%   |
| OPNsense 21.7.1   | 2        | 2.08%   |
| OPNsense 21.7     | 2        | 2.08%   |
| OPNsense 21.1.7   | 2        | 2.08%   |
| OPNsense 20.7.8   | 2        | 2.08%   |
| FreeBSD 13.0-p7   | 2        | 2.08%   |
| FreeBSD 12.2-p4   | 2        | 2.08%   |
| pfSense 2.5.0     | 1        | 1.04%   |
| OPNsense 22.7.7   | 1        | 1.04%   |
| OPNsense 22.7     | 1        | 1.04%   |
| OPNsense 22.1.8   | 1        | 1.04%   |
| OPNsense 22.1.6   | 1        | 1.04%   |
| OPNsense 22.1.5   | 1        | 1.04%   |
| OPNsense 22.1.2   | 1        | 1.04%   |
| OPNsense 22.1.10  | 1        | 1.04%   |
| OPNsense 22.1.1   | 1        | 1.04%   |
| OPNsense 22.1     | 1        | 1.04%   |
| OPNsense 21.1.6   | 1        | 1.04%   |
| OPNsense 21.1.1   | 1        | 1.04%   |
| OpenBSD 7.0       | 1        | 1.04%   |
| OpenBSD 6.7       | 1        | 1.04%   |
| helloSystem 0.7.0 | 1        | 1.04%   |
| helloSystem 0.5.0 | 1        | 1.04%   |
| GhostBSD 19.12    | 1        | 1.04%   |
| FuryBSD 12.2-p3   | 1        | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 54       | 69.23%  |
| FreeBSD     | 14       | 17.95%  |
| OpenBSD     | 5        | 6.41%   |
| helloSystem | 2        | 2.56%   |
| pfSense     | 1        | 1.28%   |
| GhostBSD    | 1        | 1.28%   |
| FuryBSD     | 1        | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 77       | 98.72%  |
| octeon | 1        | 1.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 60       | 75.95%  |
| KDE5         | 8        | 10.13%  |
| fvwm         | 3        | 3.8%    |
| MATE         | 2        | 2.53%   |
| helloDesktop | 2        | 2.53%   |
| xfwm         | 1        | 1.27%   |
| XFCE         | 1        | 1.27%   |
| TWM          | 1        | 1.27%   |
| AwesomeWM    | 1        | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 60       | 76.92%  |
| X11     | 18       | 23.08%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 64       | 79.01%  |
| SDDM    | 9        | 11.11%  |
| LightDM | 3        | 3.7%    |
| SLiM    | 2        | 2.47%   |
| GDM     | 2        | 2.47%   |
| XDM     | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 62       | 77.5%   |
| C              | 7        | 8.75%   |
| en_US          | 6        | 7.5%    |
| sv_SE          | 3        | 3.75%   |
| sv_SE.US-ASCII | 1        | 1.25%   |
| en_CA          | 1        | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 64       | 81.01%  |
| BIOS | 15       | 18.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 50       | 63.29%  |
| Zfs    | 23       | 29.11%  |
| Ffs    | 5        | 6.33%   |
| Cd9660 | 1        | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 70       | 88.61%  |
| MBR  | 9        | 11.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 11       | 14.1%   |
| PC Engines                 | 8        | 10.26%  |
| Unknown                    | 8        | 10.26%  |
| Gigabyte Technology        | 7        | 8.97%   |
| Intel                      | 6        | 7.69%   |
| MSI                        | 5        | 6.41%   |
| Lenovo                     | 5        | 6.41%   |
| Hewlett-Packard            | 5        | 6.41%   |
| Dell                       | 4        | 5.13%   |
| ASRock                     | 3        | 3.85%   |
| Shuttle                    | 2        | 2.56%   |
| Fujitsu                    | 2        | 2.56%   |
| Wistron                    | 1        | 1.28%   |
| Supermicro                 | 1        | 1.28%   |
| ShenZhen MinWin Technology | 1        | 1.28%   |
| Protectli                  | 1        | 1.28%   |
| HPE                        | 1        | 1.28%   |
| Fujitsu Siemens            | 1        | 1.28%   |
| Deciso                     | 1        | 1.28%   |
| Cisco                      | 1        | 1.28%   |
| AOpen                      | 1        | 1.28%   |
| AMI                        | 1        | 1.28%   |
| ADI                        | 1        | 1.28%   |
| ACMA                       | 1        | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 8        | 10.26%  |
| PC Engines APU2                     | 4        | 5.13%   |
| ASUS All Series                     | 3        | 3.85%   |
| PC Engines apu4                     | 2        | 2.56%   |
| Intel CRESCENTBAY                   | 2        | 2.56%   |
| Dell OptiPlex 9020                  | 2        | 2.56%   |
| Wistron ProLiant ML110 G6           | 1        | 1.28%   |
| Supermicro SYS-1019S-MP             | 1        | 1.28%   |
| Shuttle SH570                       | 1        | 1.28%   |
| Shuttle DH170                       | 1        | 1.28%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1        | 1.28%   |
| Protectli FW4B                      | 1        | 1.28%   |
| PC Engines APU3                     | 1        | 1.28%   |
| PC Engines APU                      | 1        | 1.28%   |
| MSI WC776AA-UUW HPE-110sc           | 1        | 1.28%   |
| MSI MS-7C56                         | 1        | 1.28%   |
| MSI MS-7B43                         | 1        | 1.28%   |
| MSI MS-7918                         | 1        | 1.28%   |
| MSI MS-7369                         | 1        | 1.28%   |
| Lenovo ThinkCentre M92p 2988B1G     | 1        | 1.28%   |
| Lenovo ThinkCentre M700 10GRCTO1WW  | 1        | 1.28%   |
| Lenovo ThinkCentre Edge72 3493AZG   | 1        | 1.28%   |
| Lenovo ThinkCentre E73 10AS002QMX   | 1        | 1.28%   |
| Lenovo 70F3S00K00 ThinkServer RS140 | 1        | 1.28%   |
| Intel Q3XXG4-P V1.0                 | 1        | 1.28%   |
| Intel DQ67SW AAG12527-306           | 1        | 1.28%   |
| Intel DH61AG AAG81491-600           | 1        | 1.28%   |
| Intel D54250WYK H13922-303          | 1        | 1.28%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 1.28%   |
| HP Z230 Tower Workstation           | 1        | 1.28%   |
| HP ProLiant ML30 Gen9               | 1        | 1.28%   |
| HP ProDesk 400 G4 MT                | 1        | 1.28%   |
| HP EliteDesk 800 G2 TWR             | 1        | 1.28%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.28%   |
| Gigabyte Z87M-D3H                   | 1        | 1.28%   |
| Gigabyte Z68X-UD7-B3                | 1        | 1.28%   |
| Gigabyte Z170X-UD5 TH               | 1        | 1.28%   |
| Gigabyte G31M-ES2C                  | 1        | 1.28%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 1.28%   |
| Gigabyte AB350M-Gaming 3            | 1        | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 8        | 10.26%  |
| PC Engines APU2                | 4        | 5.13%   |
| Lenovo ThinkCentre             | 4        | 5.13%   |
| Dell OptiPlex                  | 4        | 5.13%   |
| ASUS All                       | 3        | 3.85%   |
| PC Engines apu4                | 2        | 2.56%   |
| Intel CRESCENTBAY              | 2        | 2.56%   |
| HP EliteDesk                   | 2        | 2.56%   |
| Wistron ProLiant               | 1        | 1.28%   |
| Supermicro SYS-1019S-MP        | 1        | 1.28%   |
| Shuttle SH570                  | 1        | 1.28%   |
| Shuttle DH170                  | 1        | 1.28%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.28%   |
| Protectli FW4B                 | 1        | 1.28%   |
| PC Engines APU3                | 1        | 1.28%   |
| PC Engines APU                 | 1        | 1.28%   |
| MSI WC776AA-UUW                | 1        | 1.28%   |
| MSI MS-7C56                    | 1        | 1.28%   |
| MSI MS-7B43                    | 1        | 1.28%   |
| MSI MS-7918                    | 1        | 1.28%   |
| MSI MS-7369                    | 1        | 1.28%   |
| Lenovo 70F3S00K00              | 1        | 1.28%   |
| Intel Q3XXG4-P                 | 1        | 1.28%   |
| Intel DQ67SW                   | 1        | 1.28%   |
| Intel DH61AG                   | 1        | 1.28%   |
| Intel D54250WYK                | 1        | 1.28%   |
| HPE ProLiant                   | 1        | 1.28%   |
| HP Z230                        | 1        | 1.28%   |
| HP ProLiant                    | 1        | 1.28%   |
| HP ProDesk                     | 1        | 1.28%   |
| Gigabyte Z87M-D3H              | 1        | 1.28%   |
| Gigabyte Z68X-UD7-B3           | 1        | 1.28%   |
| Gigabyte Z170X-UD5             | 1        | 1.28%   |
| Gigabyte G31M-ES2C             | 1        | 1.28%   |
| Gigabyte B550I                 | 1        | 1.28%   |
| Gigabyte AB350M-Gaming         | 1        | 1.28%   |
| Gigabyte 970A-DS3P             | 1        | 1.28%   |
| Fujitsu Siemens ESPRIMO        | 1        | 1.28%   |
| Fujitsu FUTRO                  | 1        | 1.28%   |
| Fujitsu ESPRIMO                | 1        | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 10       | 12.82%  |
| 2017    | 10       | 12.82%  |
| 2016    | 9        | 11.54%  |
| 2014    | 9        | 11.54%  |
| 2021    | 7        | 8.97%   |
| 2010    | 6        | 7.69%   |
| 2020    | 5        | 6.41%   |
| 2019    | 5        | 6.41%   |
| 2013    | 5        | 6.41%   |
| 2012    | 4        | 5.13%   |
| 2009    | 3        | 3.85%   |
| 2022    | 2        | 2.56%   |
| 2015    | 1        | 1.28%   |
| 2006    | 1        | 1.28%   |
| Unknown | 1        | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 78       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 69       | 88.46%  |
| Yes  | 9        | 11.54%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 23       | 28.4%   |
| 4.01-8.0    | 21       | 25.93%  |
| 16.01-24.0  | 16       | 19.75%  |
| 32.01-64.0  | 11       | 13.58%  |
| 24.01-32.0  | 3        | 3.7%    |
| 2.01-3.0    | 3        | 3.7%    |
| 64.01-256.0 | 3        | 3.7%    |
| 1.01-2.0    | 1        | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 38       | 46.34%  |
| 0.51-1.0   | 28       | 34.15%  |
| 1.01-2.0   | 9        | 10.98%  |
| 4.01-8.0   | 4        | 4.88%   |
| 3.01-4.0   | 2        | 2.44%   |
| 24.01-32.0 | 1        | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 64.63%  |
| 2      | 8        | 9.76%   |
| 3      | 7        | 8.54%   |
| 0      | 5        | 6.1%    |
| 6      | 3        | 3.66%   |
| 4      | 3        | 3.66%   |
| 12     | 1        | 1.22%   |
| 10     | 1        | 1.22%   |
| 9      | 1        | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 82.28%  |
| Yes       | 14       | 17.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 98.72%  |
| No        | 1        | 1.28%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 84.81%  |
| Yes       | 12       | 15.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 87.18%  |
| Yes       | 10       | 12.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Sweden  | 78       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Stockholm             | 16       | 17.58%  |
| Malmo                 | 8        | 8.79%   |
| Bromma                | 5        | 5.49%   |
| Taby                  | 3        | 3.3%    |
| VÃ¤sterÃ¥s        | 2        | 2.2%    |
| Västerås            | 2        | 2.2%    |
| UmeГҐ               | 2        | 2.2%    |
| Tumba                 | 2        | 2.2%    |
| Sollentuna            | 2        | 2.2%    |
| Solleftea             | 2        | 2.2%    |
| Piteå                | 2        | 2.2%    |
| Lund                  | 2        | 2.2%    |
| LinkГ¶ping          | 2        | 2.2%    |
| JГ¶nkГ¶ping       | 2        | 2.2%    |
| Helsingborg           | 2        | 2.2%    |
| Enskede-Arsta-Vantoer | 2        | 2.2%    |
| Bandhagen             | 2        | 2.2%    |
| Г…hus              | 1        | 1.1%    |
| Г„lvГ¤ngen       | 1        | 1.1%    |
| Vaxjo                 | 1        | 1.1%    |
| Upplands Vasby        | 1        | 1.1%    |
| UmeÃ¥               | 1        | 1.1%    |
| Umeå                 | 1        | 1.1%    |
| Tyreso Strand         | 1        | 1.1%    |
| Trelleborg            | 1        | 1.1%    |
| Trangsund             | 1        | 1.1%    |
| Torsby                | 1        | 1.1%    |
| SГ¶dertГ¤lje      | 1        | 1.1%    |
| Sundsvall             | 1        | 1.1%    |
| Sundbyberg            | 1        | 1.1%    |
| Stroemstad            | 1        | 1.1%    |
| Skövde               | 1        | 1.1%    |
| SkÃ¶vde             | 1        | 1.1%    |
| Skaellinge            | 1        | 1.1%    |
| Saltsjoe-Boo          | 1        | 1.1%    |
| NorrkГ¶ping         | 1        | 1.1%    |
| Moelndal              | 1        | 1.1%    |
| Landskrona            | 1        | 1.1%    |
| Kungsbacka            | 1        | 1.1%    |
| Kristianstad          | 1        | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 29     | 17.43%  |
| Seagate             | 14       | 29     | 12.84%  |
| WDC                 | 13       | 22     | 11.93%  |
| Hoodisk             | 11       | 14     | 10.09%  |
| Kingston            | 10       | 12     | 9.17%   |
| Intel               | 8        | 13     | 7.34%   |
| Crucial             | 6        | 14     | 5.5%    |
| Toshiba             | 5        | 13     | 4.59%   |
| SanDisk             | 2        | 3      | 1.83%   |
| Phison              | 2        | 2      | 1.83%   |
| NVMe                | 2        | 3      | 1.83%   |
| Innodisk            | 2        | 3      | 1.83%   |
| Hitachi             | 2        | 2      | 1.83%   |
| Apacer              | 2        | 2      | 1.83%   |
| XrayDisk            | 1        | 1      | 0.92%   |
| Transcend           | 1        | 1      | 0.92%   |
| Supermicro          | 1        | 1      | 0.92%   |
| SK hynix            | 1        | 1      | 0.92%   |
| PNY                 | 1        | 1      | 0.92%   |
| OCZ                 | 1        | 2      | 0.92%   |
| LITEONIT            | 1        | 1      | 0.92%   |
| LITEON              | 1        | 1      | 0.92%   |
| KingSpec            | 1        | 1      | 0.92%   |
| Fordisk             | 1        | 1      | 0.92%   |
| Corsair             | 1        | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 860 QVO 1TB           | 3        | 2.48%   |
| Hoodisk SSD 64GB                  | 3        | 2.48%   |
| Hoodisk SSD 16GB                  | 3        | 2.48%   |
| Hoodisk SSD 128GB                 | 3        | 2.48%   |
| WDC WD5000AZLX-60K2TA0 500GB      | 2        | 1.65%   |
| Toshiba HDWQ140 4TB               | 2        | 1.65%   |
| Samsung SSD 970 EVO 500GB         | 2        | 1.65%   |
| Samsung HD501LJ 500GB             | 2        | 1.65%   |
| Phison SATA SSD 16GB              | 2        | 1.65%   |
| Kingston SV300S37A240G 240GB      | 2        | 1.65%   |
| Kingston SA400S37240G 240GB       | 2        | 1.65%   |
| Intel SSDSC2BW240A4 240GB         | 2        | 1.65%   |
| Crucial CT256MX100SSD1 256GB      | 2        | 1.65%   |
| Apacer 64GB SATA Flash Drive      | 2        | 1.65%   |
| XrayDisk SSD 64GB                 | 1        | 0.83%   |
| WDC WDS250G2B0C-00PXH0 250GB      | 1        | 0.83%   |
| WDC WDS250G2B0A-00SM50 250GB      | 1        | 0.83%   |
| WDC WDS120G1G0A-00SS50 120GB      | 1        | 0.83%   |
| WDC WD82PURZ-85TEUY0 8TB          | 1        | 0.83%   |
| WDC WD6400AARS-00Y5B1 640GB       | 1        | 0.83%   |
| WDC WD5000AAKS-07V0A0 500GB       | 1        | 0.83%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 0.83%   |
| WDC WD40EZRZ-22GXCB0 4TB          | 1        | 0.83%   |
| WDC WD40EFRX-68N32N0 4TB          | 1        | 0.83%   |
| WDC WD2500AAJS-60B4A0 250GB       | 1        | 0.83%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1        | 0.83%   |
| WDC WD20EARX-00ZUDB0 2TB          | 1        | 0.83%   |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 0.83%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1        | 0.83%   |
| Transcend TS256GMSA452T 256GB     | 1        | 0.83%   |
| Toshiba HDWR11A 10TB              | 1        | 0.83%   |
| Toshiba HDWN180 8TB               | 1        | 0.83%   |
| Toshiba HDWG480 8TB               | 1        | 0.83%   |
| Toshiba HDWG180 8TB               | 1        | 0.83%   |
| Toshiba DT01ACA100 1TB            | 1        | 0.83%   |
| Supermicro SSD 64GB               | 1        | 0.83%   |
| SK hynix HFS128G32MND-2200A 128GB | 1        | 0.83%   |
| Seagate ST9500325AS 500GB         | 1        | 0.83%   |
| Seagate ST9200420ASG 200GB        | 1        | 0.83%   |
| Seagate ST8000VX0022-2EJ112 8TB   | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 13       | 27     | 37.14%  |
| WDC                 | 10       | 17     | 28.57%  |
| Toshiba             | 5        | 13     | 14.29%  |
| Samsung Electronics | 4        | 6      | 11.43%  |
| Hitachi             | 2        | 2      | 5.71%   |
| NVMe                | 1        | 2      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 18     | 18.31%  |
| Hoodisk             | 11       | 14     | 15.49%  |
| Kingston            | 10       | 12     | 14.08%  |
| Intel               | 8        | 13     | 11.27%  |
| Crucial             | 6        | 14     | 8.45%   |
| WDC                 | 2        | 4      | 2.82%   |
| SanDisk             | 2        | 3      | 2.82%   |
| Phison              | 2        | 2      | 2.82%   |
| Innodisk            | 2        | 3      | 2.82%   |
| Apacer              | 2        | 2      | 2.82%   |
| XrayDisk            | 1        | 1      | 1.41%   |
| Transcend           | 1        | 1      | 1.41%   |
| Supermicro          | 1        | 1      | 1.41%   |
| SK hynix            | 1        | 1      | 1.41%   |
| Seagate             | 1        | 1      | 1.41%   |
| PNY                 | 1        | 1      | 1.41%   |
| OCZ                 | 1        | 2      | 1.41%   |
| NVMe                | 1        | 1      | 1.41%   |
| LITEONIT            | 1        | 1      | 1.41%   |
| LITEON              | 1        | 1      | 1.41%   |
| KingSpec            | 1        | 1      | 1.41%   |
| Fordisk             | 1        | 1      | 1.41%   |
| Corsair             | 1        | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 59       | 99     | 67.05%  |
| HDD  | 23       | 67     | 26.14%  |
| NVMe | 6        | 7      | 6.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 166    | 92.21%  |
| NVMe | 6        | 7      | 7.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 64       | 105    | 66.67%  |
| 0.51-1.0   | 15       | 22     | 15.63%  |
| 3.01-4.0   | 8        | 18     | 8.33%   |
| 1.01-2.0   | 6        | 11     | 6.25%   |
| 4.01-10.0  | 3        | 10     | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 35       | 43.21%  |
| 1-20           | 11       | 13.58%  |
| 21-50          | 10       | 12.35%  |
| 51-100         | 9        | 11.11%  |
| 251-500        | 8        | 9.88%   |
| 1001-2000      | 4        | 4.94%   |
| 501-1000       | 3        | 3.7%    |
| More than 3000 | 1        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 65       | 81.25%  |
| 21-50     | 11       | 13.75%  |
| 251-500   | 2        | 2.5%    |
| 101-250   | 1        | 1.25%   |
| 1001-2000 | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB           | 1        | 1      | 7.14%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 2      | 7.14%   |
| WDC WD2500AAJS-60B4A0 250GB           | 1        | 2      | 7.14%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 7.14%   |
| WDC WD20EARX-00ZUDB0 2TB              | 1        | 1      | 7.14%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1        | 1      | 7.14%   |
| SK hynix HFS128G32MND-2200A 128GB     | 1        | 1      | 7.14%   |
| Seagate ST100FN0021 100GB             | 1        | 1      | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 7.14%   |
| Samsung Electronics HD321KJ 320GB     | 1        | 1      | 7.14%   |
| Kingston SV300S37A120G 120GB          | 1        | 1      | 7.14%   |
| Intel SSDSC2CT120A3 120GB             | 1        | 1      | 7.14%   |
| Intel SSDSC2CT060A3 64GB              | 1        | 2      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 9      | 33.33%  |
| Seagate             | 2        | 2      | 16.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Intel               | 2        | 3      | 16.67%  |
| SK hynix            | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 9      | 66.67%  |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 5        | 6      | 45.45%  |
| HDD  | 5        | 11     | 45.45%  |
| NVMe | 1        | 1      | 9.09%   |

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
| Works    | 69       | 146    | 80.23%  |
| Malfunc  | 11       | 18     | 12.79%  |
| Detected | 6        | 9      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 58       | 61.7%   |
| AMD                      | 18       | 19.15%  |
| Samsung Electronics      | 6        | 6.38%   |
| Broadcom / LSI           | 3        | 3.19%   |
| Marvell Technology Group | 2        | 2.13%   |
| ASMedia Technology       | 2        | 2.13%   |
| VIA Technologies         | 1        | 1.06%   |
| Seagate Technology       | 1        | 1.06%   |
| SanDisk                  | 1        | 1.06%   |
| Nvidia                   | 1        | 1.06%   |
| 3ware                    | 1        | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 11.82%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 8.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 7.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 2.73%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2.73%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 2.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.82%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.82%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.91%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.91%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.91%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.91%   |
| Nvidia MCP65 SATA Controller                                                            | 1        | 0.91%   |
| Nvidia MCP65 IDE                                                                        | 1        | 0.91%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.91%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.91%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 1        | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.91%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.91%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 70.21%  |
| IDE  | 13       | 13.83%  |
| NVMe | 8        | 8.51%   |
| RAID | 4        | 4.26%   |
| SAS  | 3        | 3.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 59       | 74.68%  |
| AMD     | 19       | 24.05%  |
| Unknown | 1        | 1.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD GX-412TC SOC                      | 7        | 8.75%   |
| Intel Core i7-4770K CPU @ 3.50GHz     | 3        | 3.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 3        | 3.75%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz   | 2        | 2.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2        | 2.5%    |
| Intel Core i3-6100 CPU @ 3.70GHz      | 2        | 2.5%    |
| Intel Celeron CPU J3160 @ 1.60GHz     | 2        | 2.5%    |
| Intel Atom CPU E3845 @ 1.91GHz        | 2        | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor   | 2        | 2.5%    |
| AMD Ryzen 7 1700 Eight-Core Processor | 2        | 2.5%    |
| Intel Xeon E-2224 CPU @ 3.40GHz       | 1        | 1.25%   |
| Intel Xeon CPU X3470 @ 2.93GHz        | 1        | 1.25%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1        | 1.25%   |
| Intel Xeon CPU E5450 @ 3.00GHz        | 1        | 1.25%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz  | 1        | 1.25%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz  | 1        | 1.25%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz   | 1        | 1.25%   |
| Intel Pentium Dual-Core CPU E5700     | 1        | 1.25%   |
| Intel Pentium CPU G6950 @ 2.80GHz     | 1        | 1.25%   |
| Intel Pentium CPU G4400 @ 3.30GHz     | 1        | 1.25%   |
| Intel Core i7-8700K CPU @ 3.70GHz     | 1        | 1.25%   |
| Intel Core i7-6850K CPU @ 3.60GHz     | 1        | 1.25%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1        | 1.25%   |
| Intel Core i7-6500U CPU @ 2.50GHz     | 1        | 1.25%   |
| Intel Core i7-5550U CPU @ 2.00GHz     | 1        | 1.25%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 1        | 1.25%   |
| Intel Core i7-4600U CPU @ 2.10GHz     | 1        | 1.25%   |
| Intel Core i7-3770S CPU @ 3.10GHz     | 1        | 1.25%   |
| Intel Core i7-2600 CPU @ 3.40GHz      | 1        | 1.25%   |
| Intel Core i5-6400 CPU @ 2.70GHz      | 1        | 1.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz     | 1        | 1.25%   |
| Intel Core i5-4690K CPU @ 3.50GHz     | 1        | 1.25%   |
| Intel Core i5-4670K CPU @ 3.40GHz     | 1        | 1.25%   |
| Intel Core i5-4590 CPU @ 3.30GHz      | 1        | 1.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz      | 1        | 1.25%   |
| Intel Core i5-4250U CPU @ 1.30GHz     | 1        | 1.25%   |
| Intel Core i5-3570K CPU @ 3.40GHz     | 1        | 1.25%   |
| Intel Core i5-3470S CPU @ 2.90GHz     | 1        | 1.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz      | 1        | 1.25%   |
| Intel Core i5-3450 CPU @ 3.10GHz      | 1        | 1.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 17       | 21.25%  |
| Intel Core i7           | 14       | 17.5%   |
| Intel Xeon              | 9        | 11.25%  |
| AMD GX                  | 9        | 11.25%  |
| Intel Celeron           | 6        | 7.5%    |
| Intel Core i3           | 4        | 5%      |
| AMD Ryzen 7             | 3        | 3.75%   |
| Other                   | 2        | 2.5%    |
| Intel Pentium           | 2        | 2.5%    |
| Intel Core 2 Quad       | 2        | 2.5%    |
| Intel Atom              | 2        | 2.5%    |
| AMD Ryzen 9             | 2        | 2.5%    |
| Intel Pentium Dual-Core | 1        | 1.25%   |
| Intel Core 2 Duo        | 1        | 1.25%   |
| Intel Core 2            | 1        | 1.25%   |
| AMD Ryzen Threadripper  | 1        | 1.25%   |
| AMD G                   | 1        | 1.25%   |
| AMD FX                  | 1        | 1.25%   |
| AMD Athlon 64 X2        | 1        | 1.25%   |
| AMD Athlon              | 1        | 1.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 49       | 61.25%  |
| 2       | 17       | 21.25%  |
| Unknown | 5        | 6.25%   |
| 24      | 3        | 3.75%   |
| 6       | 3        | 3.75%   |
| 16      | 2        | 2.5%    |
| 8       | 1        | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 76       | 97.44%  |
| Unknown | 2        | 2.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 50       | 62.5%   |
| 2       | 25       | 31.25%  |
| Unknown | 5        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 14       | 17.5%   |
| Skylake       | 11       | 13.75%  |
| Puma          | 8        | 10%     |
| IvyBridge     | 6        | 7.5%    |
| Silvermont    | 5        | 6.25%   |
| Penryn        | 4        | 5%      |
| KabyLake      | 4        | 5%      |
| Unknown       | 4        | 5%      |
| Zen           | 3        | 3.75%   |
| SandyBridge   | 3        | 3.75%   |
| Nehalem       | 3        | 3.75%   |
| Broadwell     | 3        | 3.75%   |
| Zen 2         | 2        | 2.5%    |
| Jaguar        | 2        | 2.5%    |
| Core          | 2        | 2.5%    |
| Westmere      | 1        | 1.25%   |
| Piledriver    | 1        | 1.25%   |
| K8 Hammer     | 1        | 1.25%   |
| Goldmont plus | 1        | 1.25%   |
| Goldmont      | 1        | 1.25%   |
| Bobcat        | 1        | 1.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 41       | 59.42%  |
| Nvidia                     | 15       | 21.74%  |
| AMD                        | 7        | 10.14%  |
| Matrox Electronics Systems | 4        | 5.8%    |
| ASPEED Technology          | 2        | 2.9%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 8.57%   |
| Intel HD Graphics 530                                                                    | 5        | 7.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 5.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 5.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 4.29%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2        | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 2.86%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 2.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 2.86%   |
| Intel HD Graphics 620                                                                    | 2        | 2.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.86%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.43%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.43%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.43%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.43%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.43%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1        | 1.43%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.43%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.43%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.43%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 1.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 1        | 1.43%   |
| Intel Iris Pro Graphics P580                                                             | 1        | 1.43%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.43%   |
| Intel HD Graphics 5500                                                                   | 1        | 1.43%   |
| Intel HD Graphics 510                                                                    | 1        | 1.43%   |
| Intel HD Graphics 500                                                                    | 1        | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 1.43%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.43%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.43%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.43%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1        | 1.43%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 1        | 1.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 40       | 50%     |
| 1 x Nvidia  | 15       | 18.75%  |
| Other       | 11       | 13.75%  |
| 1 x AMD     | 7        | 8.75%   |
| 1 x Matrox  | 4        | 5%      |
| 1 x ASPEED  | 2        | 2.5%    |
| Intel + AMD | 1        | 1.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 56       | 70.89%  |
| Unknown     | 13       | 16.46%  |
| Proprietary | 10       | 12.66%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 66       | 84.62%  |
| 1.01-2.0   | 3        | 3.85%   |
| 0.51-1.0   | 3        | 3.85%   |
| 5.01-6.0   | 2        | 2.56%   |
| 3.01-4.0   | 2        | 2.56%   |
| 7.01-8.0   | 1        | 1.28%   |
| 8.01-16.0  | 1        | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 27.27%  |
| Hewlett-Packard     | 5        | 22.73%  |
| Philips             | 3        | 13.64%  |
| Iiyama              | 2        | 9.09%   |
| Dell                | 2        | 9.09%   |
| AOC                 | 2        | 9.09%   |
| LG Electronics      | 1        | 4.55%   |
| Goldstar            | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch | 2        | 7.69%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch             | 2        | 7.69%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                  | 2        | 7.69%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                    | 2        | 7.69%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch | 1        | 3.85%   |
| Samsung Electronics LCD Monitor SyncMaster                        | 1        | 3.85%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                  | 1        | 3.85%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                 | 1        | 3.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch | 1        | 3.85%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch         | 1        | 3.85%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch          | 1        | 3.85%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch          | 1        | 3.85%   |
| LG Electronics LCD Monitor LX20D 1600x1200                        | 1        | 3.85%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch             | 1        | 3.85%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch     | 1        | 3.85%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch       | 1        | 3.85%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                        | 1        | 3.85%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                       | 1        | 3.85%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch       | 1        | 3.85%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch       | 1        | 3.85%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch             | 1        | 3.85%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1200 (WUXGA)  | 5        | 22.73%  |
| 1920x1080 (FHD)    | 5        | 22.73%  |
| 2560x1440 (QHD)    | 4        | 18.18%  |
| 3840x2160 (4K)     | 3        | 13.64%  |
| 3840x1080          | 1        | 4.55%   |
| 3440x1440          | 1        | 4.55%   |
| 1680x1050 (WSXGA+) | 1        | 4.55%   |
| 1600x1200          | 1        | 4.55%   |
| Unknown            | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 5        | 26.32%  |
| 27      | 4        | 21.05%  |
| 23      | 4        | 21.05%  |
| 21      | 3        | 15.79%  |
| 24      | 2        | 10.53%  |
| 32      | 1        | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 47.37%  |
| Unknown     | 5        | 26.32%  |
| 401-500     | 3        | 15.79%  |
| 701-800     | 1        | 5.26%   |
| 601-700     | 1        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 55.56%  |
| Unknown | 5        | 27.78%  |
| 16/10   | 3        | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 33.33%  |
| Unknown        | 5        | 27.78%  |
| 301-350        | 4        | 22.22%  |
| 251-300        | 2        | 11.11%  |
| 351-500        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 33.33%  |
| Unknown | 5        | 23.81%  |
| 161-240 | 3        | 14.29%  |
| 101-120 | 3        | 14.29%  |
| 1-50    | 2        | 9.52%   |
| 121-160 | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 61       | 76.25%  |
| 1     | 13       | 16.25%  |
| 2     | 6        | 7.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 60       | 58.82%  |
| Realtek Semiconductor    | 26       | 25.49%  |
| Broadcom                 | 6        | 5.88%   |
| Qualcomm Atheros         | 3        | 2.94%   |
| TP-Link                  | 2        | 1.96%   |
| Ralink Technology        | 1        | 0.98%   |
| Mellanox Technologies    | 1        | 0.98%   |
| MediaTek                 | 1        | 0.98%   |
| Marvell Technology Group | 1        | 0.98%   |
| Apple                    | 1        | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23       | 17.69%  |
| Intel I210 Gigabit Network Connection                                         | 15       | 11.54%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 10.77%  |
| Intel 82574L Gigabit Network Connection                                       | 7        | 5.38%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 4.62%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 3.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.08%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 3.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 3.08%   |
| Intel Ethernet Connection I217-V                                              | 3        | 2.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.54%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.54%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 1.54%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.77%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.77%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.77%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.77%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.77%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.77%   |
| Intel Wireless 7260                                                           | 1        | 0.77%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 0.77%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.77%   |
| Intel Ethernet Controller I226-V                                              | 1        | 0.77%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.77%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.77%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1        | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 41.67%  |
| TP-Link               | 2        | 16.67%  |
| Realtek Semiconductor | 2        | 16.67%  |
| Ralink Technology     | 1        | 8.33%   |
| Qualcomm Atheros      | 1        | 8.33%   |
| Broadcom              | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1        | 8.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 8.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1        | 8.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 8.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1        | 8.33%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 8.33%   |
| Intel Wireless 8265 / 8275                                      | 1        | 8.33%   |
| Intel Wireless 7260                                             | 1        | 8.33%   |
| Intel Wi-Fi 6 AX200                                             | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1        | 8.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 58       | 62.37%  |
| Realtek Semiconductor    | 26       | 27.96%  |
| Broadcom                 | 5        | 5.38%   |
| Qualcomm Atheros         | 2        | 2.15%   |
| Marvell Technology Group | 1        | 1.08%   |
| Apple                    | 1        | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 23       | 19.83%  |
| Intel I210 Gigabit Network Connection                                         | 15       | 12.93%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 12.07%  |
| Intel 82574L Gigabit Network Connection                                       | 7        | 6.03%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 5.17%   |
| Intel Ethernet Connection I217-LM                                             | 5        | 4.31%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 3.45%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 3.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 3.45%   |
| Intel Ethernet Connection I217-V                                              | 3        | 2.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.72%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 1.72%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 1.72%   |
| Intel 82576 Gigabit Network Connection                                        | 2        | 1.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.86%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.86%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.86%   |
| Intel Ethernet Controller I226-V                                              | 1        | 0.86%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.86%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.86%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 0.86%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.86%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 0.86%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 0.86%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 0.86%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.86%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.86%   |
| Broadcom NetXtreme BCM5701 Gigabit Ethernet                                   | 1        | 0.86%   |
| Apple Ethernet Adapter [A1277]                                                | 1        | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 84.62%  |
| WiFi     | 12       | 13.19%  |
| Modem    | 1        | 1.1%    |
| Unknown  | 1        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 76       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 24       | 29.27%  |
| 3     | 14       | 17.07%  |
| 4     | 12       | 14.63%  |
| 1     | 11       | 13.41%  |
| 6     | 7        | 8.54%   |
| 5     | 7        | 8.54%   |
| 7     | 3        | 3.66%   |
| 13    | 1        | 1.22%   |
| 9     | 1        | 1.22%   |
| 8     | 1        | 1.22%   |
| 0     | 1        | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 90.12%  |
| Yes  | 8        | 9.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 4        | 40%     |
| Intel                   | 3        | 30%     |
| IMC Networks            | 1        | 10%     |
| Dell                    | 1        | 10%     |
| Apple                   | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4        | 40%     |
| Intel Bluetooth wireless interface                   | 2        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                     | 1        | 10%     |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 10%     |
| Dell Dell Wireless 355C Bluetooth 2.0 + EDR module   | 1        | 10%     |
| Apple Apple Broadcom Built-in Bluetooth              | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 39       | 56.52%  |
| Nvidia                  | 15       | 21.74%  |
| AMD                     | 12       | 17.39%  |
| Philips (or NXP)        | 1        | 1.45%   |
| GN Netcom               | 1        | 1.45%   |
| BEHRINGER International | 1        | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 9.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8        | 9.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 8.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4        | 4.76%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 3.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 2.38%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.38%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1        | 1.19%   |
| Nvidia MCP65 High Definition Audio                                                                | 1        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.19%   |
| Intel Jasper Lake HD Audio                                                                        | 1        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.19%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.19%   |
| GN Netcom Jabra SPEAK 410 USB                                                                     | 1        | 1.19%   |
| BEHRINGER International UMC1820                                                                   | 1        | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 1.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 1.19%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 1.19%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 1        | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 19.23%  |
| Corsair             | 15       | 19.23%  |
| Samsung Electronics | 13       | 16.67%  |
| Kingston            | 7        | 8.97%   |
| SK hynix            | 5        | 6.41%   |
| Micron Technology   | 5        | 6.41%   |
| Crucial             | 5        | 6.41%   |
| G.Skill             | 3        | 3.85%   |
| Kimtigo             | 2        | 2.56%   |
| Smart Modular       | 1        | 1.28%   |
| Ramaxel Technology  | 1        | 1.28%   |
| HPE                 | 1        | 1.28%   |
| Hewlett-Packard     | 1        | 1.28%   |
| Elpida              | 1        | 1.28%   |
| ASint Technology    | 1        | 1.28%   |
| Apacer              | 1        | 1.28%   |
| Unknown             | 1        | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 6        | 7.06%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s    | 4        | 4.71%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s   | 2        | 2.35%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s              | 2        | 2.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s | 2        | 2.35%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s         | 2        | 2.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s             | 1        | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s           | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 1.18%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 1.18%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s           | 1        | 1.18%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 1        | 1.18%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 1.18%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s               | 1        | 1.18%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s             | 1        | 1.18%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s           | 1        | 1.18%   |
| Smart Modular RAM Module 4GB DIMM DDR3 1333MT/s        | 1        | 1.18%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.18%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.18%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s   | 1        | 1.18%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.18%   |
| Samsung RAM M471B5173BH0-YK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s  | 1        | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s  | 1        | 1.18%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s    | 1        | 1.18%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.18%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.18%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.18%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s | 1        | 1.18%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.18%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB DIMM DDR3 1867MT/s    | 1        | 1.18%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s   | 1        | 1.18%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s   | 1        | 1.18%   |
| Kingston RAM 99U5458-005.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 1.18%   |
| Kingston RAM 9965745-020.A00G 32GB DIMM DDR4 3200MT/s  | 1        | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 42       | 59.15%  |
| DDR4    | 21       | 29.58%  |
| DDR2    | 4        | 5.63%   |
| SDRAM   | 2        | 2.82%   |
| Unknown | 2        | 2.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 51       | 71.83%  |
| SODIMM | 20       | 28.17%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 29       | 37.18%  |
| 8192  | 27       | 34.62%  |
| 16384 | 10       | 12.82%  |
| 2048  | 6        | 7.69%   |
| 1024  | 5        | 6.41%   |
| 32768 | 1        | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 30.67%  |
| 1333    | 19       | 25.33%  |
| 2133    | 8        | 10.67%  |
| 2667    | 5        | 6.67%   |
| 3200    | 4        | 5.33%   |
| 800     | 4        | 5.33%   |
| 2400    | 3        | 4%      |
| 2666    | 2        | 2.67%   |
| 667     | 2        | 2.67%   |
| Unknown | 2        | 2.67%   |
| 1867    | 1        | 1.33%   |
| 1332    | 1        | 1.33%   |
| 333     | 1        | 1.33%   |

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
| 1     | 42       | 53.16%  |
| 0     | 28       | 35.44%  |
| 2     | 7        | 8.86%   |
| 5     | 1        | 1.27%   |
| 3     | 1        | 1.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 46       | 80.7%   |
| Net/wireless             | 5        | 8.77%   |
| Storage/ata              | 1        | 1.75%   |
| Sound                    | 1        | 1.75%   |
| Net/ethernet             | 1        | 1.75%   |
| Graphics card            | 1        | 1.75%   |
| Firewire controller      | 1        | 1.75%   |
| Bluetooth                | 1        | 1.75%   |

