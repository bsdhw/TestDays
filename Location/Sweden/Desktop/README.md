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

Total: 162

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Techvision    | TVI7309X B0                 | [906fd7e198](https://bsd-hardware.info/?probe=906fd7e198) | Sep 30, 2023 |
| Intel         | DN2820FYK H24582-201        | [ea832a672d](https://bsd-hardware.info/?probe=ea832a672d) | Sep 30, 2023 |
| HP            | 8299                        | [fee80cc3e3](https://bsd-hardware.info/?probe=fee80cc3e3) | Sep 23, 2023 |
| PC Engines    | apu6                        | [1a45dd59a4](https://bsd-hardware.info/?probe=1a45dd59a4) | Sep 21, 2023 |
| HP            | 8299                        | [2f1bdffe66](https://bsd-hardware.info/?probe=2f1bdffe66) | Sep 20, 2023 |
| CWWK          | CW-AD4L-N V1                | [cdeddbf4be](https://bsd-hardware.info/?probe=cdeddbf4be) | Sep 17, 2023 |
| Unknown       | Unknown                     | [b95f409ccf](https://bsd-hardware.info/?probe=b95f409ccf) | Sep 05, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| Intel         | Q3XXG4-P V1.0               | [0836b029bc](https://bsd-hardware.info/?probe=0836b029bc) | Aug 17, 2023 |
| PC Engines    | APU2                        | [d8f32b19ff](https://bsd-hardware.info/?probe=d8f32b19ff) | Aug 14, 2023 |
| HP            | 8299                        | [74c24bcb16](https://bsd-hardware.info/?probe=74c24bcb16) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| MSI           | B350I PRO AC                | [3c4d3b94d0](https://bsd-hardware.info/?probe=3c4d3b94d0) | Jul 14, 2023 |
| MSI           | B350I PRO AC                | [ab56e76e70](https://bsd-hardware.info/?probe=ab56e76e70) | Jul 14, 2023 |
| PC Engines    | APU2                        | [80d79341a8](https://bsd-hardware.info/?probe=80d79341a8) | Jul 05, 2023 |
| ASUSTek       | P5Q DELUXE                  | [0cf9bf6a63](https://bsd-hardware.info/?probe=0cf9bf6a63) | Jul 04, 2023 |
| Unknown       | Unknown                     | [5080e84698](https://bsd-hardware.info/?probe=5080e84698) | Jun 28, 2023 |
| Unknown       | Unknown                     | [c660f668dc](https://bsd-hardware.info/?probe=c660f668dc) | Jun 25, 2023 |
| Unknown       | Unknown                     | [b67ce69ea4](https://bsd-hardware.info/?probe=b67ce69ea4) | Jun 23, 2023 |
| Unknown       | Unknown                     | [6e8085380f](https://bsd-hardware.info/?probe=6e8085380f) | Jun 23, 2023 |
| Unknown       | Unknown                     | [eb49ebcc0c](https://bsd-hardware.info/?probe=eb49ebcc0c) | Jun 22, 2023 |
| Unknown       | Unknown                     | [193c7d152b](https://bsd-hardware.info/?probe=193c7d152b) | Jun 11, 2023 |
| PC Engines    | APU2                        | [f644f33061](https://bsd-hardware.info/?probe=f644f33061) | Jun 07, 2023 |
| Unknown       | Unknown                     | [e80a97aec3](https://bsd-hardware.info/?probe=e80a97aec3) | May 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| Lenovo        | ThinkCentre M81 1730A1G     | [8f59660eca](https://bsd-hardware.info/?probe=8f59660eca) | May 17, 2023 |
| Techvision    | TVI7309X B0                 | [a75ff519b0](https://bsd-hardware.info/?probe=a75ff519b0) | May 15, 2023 |
| CWWK          | MINIPC-G12                  | [4806dc7d9a](https://bsd-hardware.info/?probe=4806dc7d9a) | Apr 29, 2023 |
| AZW           | GK55                        | [31a99b9d2a](https://bsd-hardware.info/?probe=31a99b9d2a) | Apr 25, 2023 |
| Techvision    | TVI7309X B0                 | [a4bc168937](https://bsd-hardware.info/?probe=a4bc168937) | Apr 22, 2023 |
| AZW           | GK55                        | [cc5a32800f](https://bsd-hardware.info/?probe=cc5a32800f) | Apr 14, 2023 |
| HP            | 1998                        | [bc67c37f5f](https://bsd-hardware.info/?probe=bc67c37f5f) | Apr 04, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| DFI           | CM100-C                     | [c34832095b](https://bsd-hardware.info/?probe=c34832095b) | Mar 15, 2023 |
| Techvision    | TVI7309X B0                 | [23f9004191](https://bsd-hardware.info/?probe=23f9004191) | Mar 13, 2023 |
| AMI           | MNHO-048                    | [ebd90b78c1](https://bsd-hardware.info/?probe=ebd90b78c1) | Mar 12, 2023 |
| AMI           | MNHO-048                    | [52cdeb023e](https://bsd-hardware.info/?probe=52cdeb023e) | Mar 12, 2023 |
| PC Engines    | APU3                        | [c8008161b0](https://bsd-hardware.info/?probe=c8008161b0) | Mar 09, 2023 |
| Unknown       | Unknown                     | [e4b77410c6](https://bsd-hardware.info/?probe=e4b77410c6) | Mar 08, 2023 |
| Dell          | 0WMJ54 A01                  | [31ed952f9c](https://bsd-hardware.info/?probe=31ed952f9c) | Mar 06, 2023 |
| Dell          | 0WMJ54 A01                  | [732a635016](https://bsd-hardware.info/?probe=732a635016) | Mar 06, 2023 |
| Unknown       | Unknown                     | [44ac3b2832](https://bsd-hardware.info/?probe=44ac3b2832) | Feb 13, 2023 |
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
| OPNsense 21.1     | 8        | 6.15%   |
| OPNsense 21.1.3   | 5        | 3.85%   |
| OPNsense 21.1.2   | 5        | 3.85%   |
| OPNsense 23.1.11  | 4        | 3.08%   |
| OPNsense 22.7.8   | 4        | 3.08%   |
| OPNsense 22.7.10  | 4        | 3.08%   |
| OPNsense 21.7.7   | 4        | 3.08%   |
| OPNsense 23.7.4   | 3        | 2.31%   |
| OPNsense 23.1.6   | 3        | 2.31%   |
| OPNsense 23.1.3   | 3        | 2.31%   |
| OPNsense 23.1.10  | 3        | 2.31%   |
| OPNsense 22.7.2   | 3        | 2.31%   |
| OPNsense 21.7.3   | 3        | 2.31%   |
| OPNsense 21.1.8   | 3        | 2.31%   |
| OPNsense 21.1.5   | 3        | 2.31%   |
| OpenBSD 6.8       | 3        | 2.31%   |
| OPNsense 23.7.5   | 2        | 1.54%   |
| OPNsense 23.1.7   | 2        | 1.54%   |
| OPNsense 23.1.2   | 2        | 1.54%   |
| OPNsense 22.7.9   | 2        | 1.54%   |
| OPNsense 22.7.6   | 2        | 1.54%   |
| OPNsense 22.1.9   | 2        | 1.54%   |
| OPNsense 22.1.3   | 2        | 1.54%   |
| OPNsense 21.7.6   | 2        | 1.54%   |
| OPNsense 21.7.1   | 2        | 1.54%   |
| OPNsense 21.7     | 2        | 1.54%   |
| OPNsense 21.1.7   | 2        | 1.54%   |
| OPNsense 20.7.8   | 2        | 1.54%   |
| helloSystem 0.8.1 | 2        | 1.54%   |
| FreeBSD 13.2      | 2        | 1.54%   |
| FreeBSD 13.0-p7   | 2        | 1.54%   |
| FreeBSD 12.2-p4   | 2        | 1.54%   |
| pfSense 2.5.0     | 1        | 0.77%   |
| OPNsense 23.7.3   | 1        | 0.77%   |
| OPNsense 23.7.1   | 1        | 0.77%   |
| OPNsense 23.7     | 1        | 0.77%   |
| OPNsense 23.1.9   | 1        | 0.77%   |
| OPNsense 23.1.8   | 1        | 0.77%   |
| OPNsense 23.1.5   | 1        | 0.77%   |
| OPNsense 23.1.1   | 1        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 75       | 72.82%  |
| FreeBSD     | 16       | 15.53%  |
| OpenBSD     | 5        | 4.85%   |
| helloSystem | 4        | 3.88%   |
| pfSense     | 1        | 0.97%   |
| GhostBSD    | 1        | 0.97%   |
| FuryBSD     | 1        | 0.97%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 102      | 99.03%  |
| octeon | 1        | 0.97%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 82       | 78.85%  |
| KDE5         | 9        | 8.65%   |
| helloDesktop | 4        | 3.85%   |
| fvwm         | 3        | 2.88%   |
| MATE         | 2        | 1.92%   |
| xfwm         | 1        | 0.96%   |
| XFCE         | 1        | 0.96%   |
| TWM          | 1        | 0.96%   |
| AwesomeWM    | 1        | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 82       | 79.61%  |
| X11     | 21       | 20.39%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 86       | 81.13%  |
| SDDM    | 10       | 9.43%   |
| SLiM    | 4        | 3.77%   |
| LightDM | 3        | 2.83%   |
| GDM     | 2        | 1.89%   |
| XDM     | 1        | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 83       | 79.05%  |
| en_US          | 9        | 8.57%   |
| C              | 8        | 7.62%   |
| sv_SE          | 3        | 2.86%   |
| sv_SE.US-ASCII | 1        | 0.95%   |
| en_CA          | 1        | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 89       | 85.58%  |
| BIOS | 15       | 14.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 60       | 57.14%  |
| Zfs    | 38       | 36.19%  |
| Ffs    | 5        | 4.76%   |
| Cd9660 | 2        | 1.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 95       | 91.35%  |
| MBR  | 9        | 8.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 13       | 12.62%  |
| Unknown                    | 13       | 12.62%  |
| PC Engines                 | 10       | 9.71%   |
| Intel                      | 8        | 7.77%   |
| MSI                        | 7        | 6.8%    |
| Lenovo                     | 7        | 6.8%    |
| Hewlett-Packard            | 7        | 6.8%    |
| Gigabyte Technology        | 7        | 6.8%    |
| Dell                       | 5        | 4.85%   |
| ASRock                     | 3        | 2.91%   |
| Techvision                 | 2        | 1.94%   |
| Shuttle                    | 2        | 1.94%   |
| Fujitsu                    | 2        | 1.94%   |
| CWWK                       | 2        | 1.94%   |
| AMI                        | 2        | 1.94%   |
| Wistron                    | 1        | 0.97%   |
| Supermicro                 | 1        | 0.97%   |
| ShenZhen MinWin Technology | 1        | 0.97%   |
| Protectli                  | 1        | 0.97%   |
| HPE                        | 1        | 0.97%   |
| Fujitsu Siemens            | 1        | 0.97%   |
| DFI                        | 1        | 0.97%   |
| Deciso                     | 1        | 0.97%   |
| Cisco                      | 1        | 0.97%   |
| AZW                        | 1        | 0.97%   |
| AOpen                      | 1        | 0.97%   |
| ADI                        | 1        | 0.97%   |
| ACMA                       | 1        | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 13       | 12.62%  |
| PC Engines APU2                        | 5        | 4.85%   |
| ASUS All Series                        | 3        | 2.91%   |
| Techvision TVI7309X                    | 2        | 1.94%   |
| PC Engines apu4                        | 2        | 1.94%   |
| Intel Q3XXG4-P V1.0                    | 2        | 1.94%   |
| Intel CRESCENTBAY                      | 2        | 1.94%   |
| Dell OptiPlex 9020                     | 2        | 1.94%   |
| Wistron ProLiant ML110 G6              | 1        | 0.97%   |
| Supermicro SYS-1019S-MP                | 1        | 0.97%   |
| Shuttle SH570                          | 1        | 0.97%   |
| Shuttle DH170                          | 1        | 0.97%   |
| ShenZhen MinWin MW-NANO-APL-4L         | 1        | 0.97%   |
| Protectli FW4B                         | 1        | 0.97%   |
| PC Engines apu6                        | 1        | 0.97%   |
| PC Engines APU3                        | 1        | 0.97%   |
| PC Engines APU                         | 1        | 0.97%   |
| MSI WC776AA-UUW HPE-110sc              | 1        | 0.97%   |
| MSI MS-7C56                            | 1        | 0.97%   |
| MSI MS-7B85                            | 1        | 0.97%   |
| MSI MS-7B43                            | 1        | 0.97%   |
| MSI MS-7A40                            | 1        | 0.97%   |
| MSI MS-7918                            | 1        | 0.97%   |
| MSI MS-7369                            | 1        | 0.97%   |
| Lenovo ThinkCentre M92p 2988B1G        | 1        | 0.97%   |
| Lenovo ThinkCentre M81 1730A1G         | 1        | 0.97%   |
| Lenovo ThinkCentre M700 10GRCTO1WW     | 1        | 0.97%   |
| Lenovo ThinkCentre Edge72 3493AZG      | 1        | 0.97%   |
| Lenovo ThinkCentre E73 10AS002QMX      | 1        | 0.97%   |
| Lenovo IdeaCentre 300-20ISH 90DA00HEMT | 1        | 0.97%   |
| Lenovo 70F3S00K00 ThinkServer RS140    | 1        | 0.97%   |
| Intel DQ67SW AAG12527-306              | 1        | 0.97%   |
| Intel DN2820FYK H24582-201             | 1        | 0.97%   |
| Intel DH61AG AAG81491-600              | 1        | 0.97%   |
| Intel D54250WYK H13922-303             | 1        | 0.97%   |
| HPE ProLiant MicroServer Gen10 Plus    | 1        | 0.97%   |
| HP Z230 Tower Workstation              | 1        | 0.97%   |
| HP ProLiant ML30 Gen9                  | 1        | 0.97%   |
| HP ProDesk 400 G4 MT                   | 1        | 0.97%   |
| HP EliteDesk 800 G3 SFF                | 1        | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 13       | 12.62%  |
| PC Engines APU2                | 5        | 4.85%   |
| Lenovo ThinkCentre             | 5        | 4.85%   |
| Dell OptiPlex                  | 5        | 4.85%   |
| HP EliteDesk                   | 4        | 3.88%   |
| ASUS All                       | 3        | 2.91%   |
| Techvision TVI7309X            | 2        | 1.94%   |
| PC Engines apu4                | 2        | 1.94%   |
| Intel Q3XXG4-P                 | 2        | 1.94%   |
| Intel CRESCENTBAY              | 2        | 1.94%   |
| ASUS ROG                       | 2        | 1.94%   |
| Wistron ProLiant               | 1        | 0.97%   |
| Supermicro SYS-1019S-MP        | 1        | 0.97%   |
| Shuttle SH570                  | 1        | 0.97%   |
| Shuttle DH170                  | 1        | 0.97%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 0.97%   |
| Protectli FW4B                 | 1        | 0.97%   |
| PC Engines apu6                | 1        | 0.97%   |
| PC Engines APU3                | 1        | 0.97%   |
| PC Engines APU                 | 1        | 0.97%   |
| MSI WC776AA-UUW                | 1        | 0.97%   |
| MSI MS-7C56                    | 1        | 0.97%   |
| MSI MS-7B85                    | 1        | 0.97%   |
| MSI MS-7B43                    | 1        | 0.97%   |
| MSI MS-7A40                    | 1        | 0.97%   |
| MSI MS-7918                    | 1        | 0.97%   |
| MSI MS-7369                    | 1        | 0.97%   |
| Lenovo IdeaCentre              | 1        | 0.97%   |
| Lenovo 70F3S00K00              | 1        | 0.97%   |
| Intel DQ67SW                   | 1        | 0.97%   |
| Intel DN2820FYK                | 1        | 0.97%   |
| Intel DH61AG                   | 1        | 0.97%   |
| Intel D54250WYK                | 1        | 0.97%   |
| HPE ProLiant                   | 1        | 0.97%   |
| HP Z230                        | 1        | 0.97%   |
| HP ProLiant                    | 1        | 0.97%   |
| HP ProDesk                     | 1        | 0.97%   |
| Gigabyte Z87M-D3H              | 1        | 0.97%   |
| Gigabyte Z68X-UD7-B3           | 1        | 0.97%   |
| Gigabyte Z170X-UD5             | 1        | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2017    | 13       | 12.62%  |
| 2016    | 13       | 12.62%  |
| 2014    | 11       | 10.68%  |
| 2022    | 10       | 9.71%   |
| 2018    | 9        | 8.74%   |
| 2020    | 8        | 7.77%   |
| 2021    | 7        | 6.8%    |
| 2019    | 6        | 5.83%   |
| 2010    | 6        | 5.83%   |
| 2013    | 5        | 4.85%   |
| 2012    | 5        | 4.85%   |
| 2009    | 3        | 2.91%   |
| 2023    | 2        | 1.94%   |
| 2015    | 2        | 1.94%   |
| 2011    | 1        | 0.97%   |
| 2006    | 1        | 0.97%   |
| Unknown | 1        | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 103      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 92       | 89.32%  |
| Yes  | 11       | 10.68%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 33       | 31.13%  |
| 4.01-8.0    | 25       | 23.58%  |
| 16.01-24.0  | 24       | 22.64%  |
| 32.01-64.0  | 13       | 12.26%  |
| 2.01-3.0    | 4        | 3.77%   |
| 24.01-32.0  | 3        | 2.83%   |
| 64.01-256.0 | 3        | 2.83%   |
| 1.01-2.0    | 1        | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 50       | 46.73%  |
| 0.51-1.0   | 38       | 35.51%  |
| 1.01-2.0   | 10       | 9.35%   |
| 4.01-8.0   | 4        | 3.74%   |
| 3.01-4.0   | 2        | 1.87%   |
| 32.01-64.0 | 1        | 0.93%   |
| 24.01-32.0 | 1        | 0.93%   |
| 2.01-3.0   | 1        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 65.42%  |
| 2      | 12       | 11.21%  |
| 3      | 9        | 8.41%   |
| 0      | 6        | 5.61%   |
| 6      | 3        | 2.8%    |
| 4      | 3        | 2.8%    |
| 12     | 1        | 0.93%   |
| 10     | 1        | 0.93%   |
| 9      | 1        | 0.93%   |
| 8      | 1        | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 84.62%  |
| Yes       | 16       | 15.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 102      | 99.03%  |
| No        | 1        | 0.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 88       | 84.62%  |
| Yes       | 16       | 15.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 87.38%  |
| Yes       | 13       | 12.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Sweden  | 103      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Stockholm             | 20       | 16.67%  |
| Malmo                 | 8        | 6.67%   |
| Bromma                | 6        | 5%      |
| Taby                  | 3        | 2.5%    |
| Piteå                | 3        | 2.5%    |
| Lund                  | 3        | 2.5%    |
| Gothenburg            | 3        | 2.5%    |
| VÃ¤sterÃ¥s        | 2        | 1.67%   |
| Västerås            | 2        | 1.67%   |
| UmeГҐ               | 2        | 1.67%   |
| Tumba                 | 2        | 1.67%   |
| Sollentuna            | 2        | 1.67%   |
| Solleftea             | 2        | 1.67%   |
| Skövde               | 2        | 1.67%   |
| LinkГ¶ping          | 2        | 1.67%   |
| Linköping            | 2        | 1.67%   |
| Landskrona            | 2        | 1.67%   |
| Karlskrona            | 2        | 1.67%   |
| JГ¶nkГ¶ping       | 2        | 1.67%   |
| Helsingborg           | 2        | 1.67%   |
| Enskede-Arsta-Vantoer | 2        | 1.67%   |
| Bandhagen             | 2        | 1.67%   |
| Г…hus              | 1        | 0.83%   |
| Г„lvГ¤ngen       | 1        | 0.83%   |
| Vaxjo                 | 1        | 0.83%   |
| Upplands Vasby        | 1        | 0.83%   |
| UmeÃ¥               | 1        | 0.83%   |
| Umeå                 | 1        | 0.83%   |
| Ulricehamn            | 1        | 0.83%   |
| Tyreso Strand         | 1        | 0.83%   |
| Trelleborg            | 1        | 0.83%   |
| Trangsund             | 1        | 0.83%   |
| Torsby                | 1        | 0.83%   |
| SГ¶dertГ¤lje      | 1        | 0.83%   |
| Svanesund             | 1        | 0.83%   |
| Sundsvall             | 1        | 0.83%   |
| Sundbyberg            | 1        | 0.83%   |
| Stroemstad            | 1        | 0.83%   |
| Solna                 | 1        | 0.83%   |
| Skogas                | 1        | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 39     | 19.57%  |
| WDC                 | 16       | 27     | 11.59%  |
| Seagate             | 16       | 36     | 11.59%  |
| Kingston            | 13       | 19     | 9.42%   |
| Intel               | 12       | 17     | 8.7%    |
| Hoodisk             | 12       | 19     | 8.7%    |
| Crucial             | 6        | 14     | 4.35%   |
| Toshiba             | 5        | 13     | 3.62%   |
| Phison              | 3        | 3      | 2.17%   |
| SanDisk             | 2        | 3      | 1.45%   |
| OCZ                 | 2        | 3      | 1.45%   |
| NVMe                | 2        | 3      | 1.45%   |
| LITEON              | 2        | 5      | 1.45%   |
| Innodisk            | 2        | 3      | 1.45%   |
| Hitachi             | 2        | 2      | 1.45%   |
| Apacer              | 2        | 2      | 1.45%   |
| XrayDisk            | 1        | 1      | 0.72%   |
| Transcend           | 1        | 1      | 0.72%   |
| Supermicro          | 1        | 1      | 0.72%   |
| SK hynix            | 1        | 1      | 0.72%   |
| PNY                 | 1        | 1      | 0.72%   |
| LITEONIT            | 1        | 1      | 0.72%   |
| KingSpec            | 1        | 1      | 0.72%   |
| Kimtigo             | 1        | 1      | 0.72%   |
| Fordisk             | 1        | 1      | 0.72%   |
| Fanxiang            | 1        | 1      | 0.72%   |
| Corsair             | 1        | 1      | 0.72%   |
| China               | 1        | 1      | 0.72%   |
| Apple               | 1        | 1      | 0.72%   |
| A-DATA Technology   | 1        | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Hoodisk SSD 64GB               | 4        | 2.53%   |
| Samsung SSD 860 QVO 1TB        | 3        | 1.9%    |
| Kingston SA400S37240G 240GB    | 3        | 1.9%    |
| Intel SSDSC2BW240A4 240GB      | 3        | 1.9%    |
| Hoodisk SSD 16GB               | 3        | 1.9%    |
| Hoodisk SSD 128GB              | 3        | 1.9%    |
| WDC WD5000AZLX-60K2TA0 500GB   | 2        | 1.27%   |
| Toshiba HDWQ140 4TB            | 2        | 1.27%   |
| Seagate ST4000DM004-2CV104 4TB | 2        | 1.27%   |
| Seagate ST2000DM008-2FR102 2TB | 2        | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB | 2        | 1.27%   |
| Samsung SSD 970 EVO Plus 500GB | 2        | 1.27%   |
| Samsung SSD 970 EVO 500GB      | 2        | 1.27%   |
| Samsung HD501LJ 500GB          | 2        | 1.27%   |
| Phison SATA SSD 16GB           | 2        | 1.27%   |
| OCZ AGILITY3 120GB             | 2        | 1.27%   |
| Kingston SV300S37A240G 240GB   | 2        | 1.27%   |
| Kingston SKC600MS256G 256GB    | 2        | 1.27%   |
| Crucial CT256MX100SSD1 256GB   | 2        | 1.27%   |
| Apacer 64GB SATA Flash Drive   | 2        | 1.27%   |
| XrayDisk SSD 64GB              | 1        | 0.63%   |
| WDC WDS500G3X0C-00SJG0 500GB   | 1        | 0.63%   |
| WDC WDS250G2B0C-00PXH0 250GB   | 1        | 0.63%   |
| WDC WDS250G2B0A-00SM50 250GB   | 1        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB   | 1        | 0.63%   |
| WDC WDS120G1G0A-00SS50 120GB   | 1        | 0.63%   |
| WDC WD82PURZ-85TEUY0 8TB       | 1        | 0.63%   |
| WDC WD80EZAZ-11TDBA0 8TB       | 1        | 0.63%   |
| WDC WD6400AARS-00Y5B1 640GB    | 1        | 0.63%   |
| WDC WD5000AAKS-07V0A0 500GB    | 1        | 0.63%   |
| WDC WD5000AACS-00ZUB0 500GB    | 1        | 0.63%   |
| WDC WD40EZRZ-22GXCB0 4TB       | 1        | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB       | 1        | 0.63%   |
| WDC WD2500AAJS-60B4A0 250GB    | 1        | 0.63%   |
| WDC WD20EFRX-68EUZN0 2TB       | 1        | 0.63%   |
| WDC WD20EARX-00ZUDB0 2TB       | 1        | 0.63%   |
| WDC WD2002FYPS-02W3B0 2TB      | 1        | 0.63%   |
| WDC WD15EARS-00Z5B1 1.5TB      | 1        | 0.63%   |
| WDC WD15EARS-00MVWB0 1.5TB     | 1        | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB       | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 34     | 37.5%   |
| WDC                 | 11       | 20     | 27.5%   |
| Toshiba             | 5        | 13     | 12.5%   |
| Samsung Electronics | 5        | 7      | 12.5%   |
| Hitachi             | 2        | 2      | 5%      |
| NVMe                | 1        | 2      | 2.5%    |
| Apple               | 1        | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 23     | 20%     |
| Kingston            | 13       | 19     | 15.29%  |
| Hoodisk             | 12       | 19     | 14.12%  |
| Intel               | 10       | 15     | 11.76%  |
| Crucial             | 6        | 14     | 7.06%   |
| WDC                 | 3        | 5      | 3.53%   |
| SanDisk             | 2        | 3      | 2.35%   |
| Phison              | 2        | 2      | 2.35%   |
| OCZ                 | 2        | 3      | 2.35%   |
| LITEON              | 2        | 5      | 2.35%   |
| Innodisk            | 2        | 3      | 2.35%   |
| Apacer              | 2        | 2      | 2.35%   |
| XrayDisk            | 1        | 1      | 1.18%   |
| Transcend           | 1        | 1      | 1.18%   |
| Supermicro          | 1        | 1      | 1.18%   |
| SK hynix            | 1        | 1      | 1.18%   |
| Seagate             | 1        | 1      | 1.18%   |
| PNY                 | 1        | 1      | 1.18%   |
| NVMe                | 1        | 1      | 1.18%   |
| LITEONIT            | 1        | 1      | 1.18%   |
| KingSpec            | 1        | 1      | 1.18%   |
| Fordisk             | 1        | 1      | 1.18%   |
| Corsair             | 1        | 1      | 1.18%   |
| China               | 1        | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 72       | 125    | 62.61%  |
| HDD  | 27       | 79     | 23.48%  |
| NVMe | 16       | 18     | 13.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 88       | 204    | 84.62%  |
| NVMe | 16       | 18     | 15.38%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 78       | 133    | 67.24%  |
| 0.51-1.0   | 17       | 24     | 14.66%  |
| 3.01-4.0   | 9        | 20     | 7.76%   |
| 1.01-2.0   | 8        | 14     | 6.9%    |
| 4.01-10.0  | 4        | 13     | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 48       | 45.28%  |
| 251-500        | 15       | 14.15%  |
| 1-20           | 13       | 12.26%  |
| 21-50          | 11       | 10.38%  |
| 51-100         | 9        | 8.49%   |
| 1001-2000      | 4        | 3.77%   |
| 501-1000       | 4        | 3.77%   |
| More than 3000 | 2        | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 88       | 83.81%  |
| 21-50          | 12       | 11.43%  |
| 251-500        | 2        | 1.9%    |
| More than 3000 | 1        | 0.95%   |
| 101-250        | 1        | 0.95%   |
| 1001-2000      | 1        | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB           | 1        | 1      | 4.55%   |
| WDC WD40EFRX-68N32N0 4TB              | 1        | 2      | 4.55%   |
| WDC WD2500AAJS-60B4A0 250GB           | 1        | 2      | 4.55%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 4.55%   |
| WDC WD20EARX-00ZUDB0 2TB              | 1        | 1      | 4.55%   |
| WDC WD2002FYPS-02W3B0 2TB             | 1        | 1      | 4.55%   |
| WDC WD15EARS-00Z5B1 1.5TB             | 1        | 1      | 4.55%   |
| WDC WD15EARS-00MVWB0 1.5TB            | 1        | 1      | 4.55%   |
| SK hynix HFS128G32MND-2200A 128GB     | 1        | 1      | 4.55%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1        | 1      | 4.55%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 4.55%   |
| Seagate ST100FN0021 100GB             | 1        | 1      | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1      | 4.55%   |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 4.55%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 4.55%   |
| Samsung Electronics HM250JI 250GB     | 1        | 1      | 4.55%   |
| Samsung Electronics HD321KJ 320GB     | 1        | 1      | 4.55%   |
| OCZ AGILITY3 120GB                    | 1        | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB          | 1        | 1      | 4.55%   |
| Intel SSDSC2CT120A3 120GB             | 1        | 1      | 4.55%   |
| Intel SSDSC2CT060A3 64GB              | 1        | 2      | 4.55%   |
| Intel SSDSC2BA400G4 400GB             | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 11     | 27.78%  |
| Seagate             | 4        | 5      | 22.22%  |
| Samsung Electronics | 3        | 3      | 16.67%  |
| Intel               | 3        | 4      | 16.67%  |
| SK hynix            | 1        | 1      | 5.56%   |
| OCZ                 | 1        | 1      | 5.56%   |
| Kingston            | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 11     | 50%     |
| Seagate             | 3        | 4      | 30%     |
| Samsung Electronics | 2        | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 17     | 50%     |
| SSD  | 7        | 8      | 43.75%  |
| NVMe | 1        | 1      | 6.25%   |

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
| Works    | 90       | 187    | 80.36%  |
| Malfunc  | 16       | 26     | 14.29%  |
| Detected | 6        | 9      | 5.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 76       | 58.46%  |
| AMD                      | 24       | 18.46%  |
| Samsung Electronics      | 10       | 7.69%   |
| ASMedia Technology       | 4        | 3.08%   |
| Broadcom / LSI           | 3        | 2.31%   |
| Silicon Motion           | 2        | 1.54%   |
| SanDisk                  | 2        | 1.54%   |
| Marvell Technology Group | 2        | 1.54%   |
| VIA Technologies         | 1        | 0.77%   |
| Seagate Technology       | 1        | 0.77%   |
| Phison Electronics       | 1        | 0.77%   |
| Nvidia                   | 1        | 0.77%   |
| ADATA Technology         | 1        | 0.77%   |
| Adaptec                  | 1        | 0.77%   |
| 3ware                    | 1        | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 11.33%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 6%      |
| Intel Jasper Lake SATA AHCI Controller                                                  | 7        | 4.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.33%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4        | 2.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 2%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 2%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3        | 2%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2%      |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 2%      |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2%      |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2%      |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 1.33%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2        | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.33%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.67%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.67%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.67%   |
| Nvidia MCP65 SATA Controller                                                            | 1        | 0.67%   |
| Nvidia MCP65 IDE                                                                        | 1        | 0.67%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.67%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.67%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 1        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 89       | 68.46%  |
| NVMe | 18       | 13.85%  |
| IDE  | 14       | 10.77%  |
| RAID | 6        | 4.62%   |
| SAS  | 3        | 2.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 78       | 75%     |
| AMD     | 25       | 24.04%  |
| Unknown | 1        | 0.96%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD GX-412TC SOC                      | 9        | 8.57%   |
| Intel Celeron N5105 @ 2.00GHz         | 5        | 4.76%   |
| Intel Core i7-4770K CPU @ 3.50GHz     | 3        | 2.86%   |
| Intel Core i5-6500 CPU @ 3.20GHz      | 3        | 2.86%   |
| Intel Core i5-4590 CPU @ 3.30GHz      | 3        | 2.86%   |
| Intel Atom CPU E3845 @ 1.91GHz        | 3        | 2.86%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz   | 2        | 1.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz     | 2        | 1.9%    |
| Intel Core i5-6400 CPU @ 2.70GHz      | 2        | 1.9%    |
| Intel Core i3-6100 CPU @ 3.70GHz      | 2        | 1.9%    |
| Intel Celeron J4125 CPU @ 2.00GHz     | 2        | 1.9%    |
| Intel Celeron CPU J3160 @ 1.60GHz     | 2        | 1.9%    |
| AMD Ryzen 9 3900X 12-Core Processor   | 2        | 1.9%    |
| AMD Ryzen 7 1700 Eight-Core Processor | 2        | 1.9%    |
| Intel Xeon E-2224 CPU @ 3.40GHz       | 1        | 0.95%   |
| Intel Xeon CPU X3470 @ 2.93GHz        | 1        | 0.95%   |
| Intel Xeon CPU X3440 @ 2.53GHz        | 1        | 0.95%   |
| Intel Xeon CPU E5450 @ 3.00GHz        | 1        | 0.95%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz  | 1        | 0.95%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz  | 1        | 0.95%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz   | 1        | 0.95%   |
| Intel Pentium Silver N6005 @ 2.00GHz  | 1        | 0.95%   |
| Intel Pentium Dual-Core CPU E5700     | 1        | 0.95%   |
| Intel Pentium CPU G6950 @ 2.80GHz     | 1        | 0.95%   |
| Intel Pentium CPU G4400 @ 3.30GHz     | 1        | 0.95%   |
| Intel N100                            | 1        | 0.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz     | 1        | 0.95%   |
| Intel Core i7-6850K CPU @ 3.60GHz     | 1        | 0.95%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1        | 0.95%   |
| Intel Core i7-6500U CPU @ 2.50GHz     | 1        | 0.95%   |
| Intel Core i7-5550U CPU @ 2.00GHz     | 1        | 0.95%   |
| Intel Core i7-4790K CPU @ 4.00GHz     | 1        | 0.95%   |
| Intel Core i7-4600U CPU @ 2.10GHz     | 1        | 0.95%   |
| Intel Core i7-4510U CPU @ 2.00GHz     | 1        | 0.95%   |
| Intel Core i7-3770S CPU @ 3.10GHz     | 1        | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz      | 1        | 0.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz     | 1        | 0.95%   |
| Intel Core i5-7500 CPU @ 3.40GHz      | 1        | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz     | 1        | 0.95%   |
| Intel Core i5-4690K CPU @ 3.50GHz     | 1        | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 21.9%   |
| Intel Core i7           | 15       | 14.29%  |
| Intel Celeron           | 13       | 12.38%  |
| AMD GX                  | 11       | 10.48%  |
| Intel Xeon              | 9        | 8.57%   |
| Other                   | 6        | 5.71%   |
| Intel Core i3           | 4        | 3.81%   |
| AMD Ryzen 7             | 4        | 3.81%   |
| Intel Atom              | 3        | 2.86%   |
| Intel Pentium           | 2        | 1.9%    |
| Intel Core 2 Quad       | 2        | 1.9%    |
| AMD Ryzen 9             | 2        | 1.9%    |
| Intel Pentium Silver    | 1        | 0.95%   |
| Intel Pentium Dual-Core | 1        | 0.95%   |
| Intel Core 2 Duo        | 1        | 0.95%   |
| Intel Core 2            | 1        | 0.95%   |
| AMD Ryzen Threadripper  | 1        | 0.95%   |
| AMD Ryzen 7 PRO         | 1        | 0.95%   |
| AMD Ryzen 5             | 1        | 0.95%   |
| AMD G                   | 1        | 0.95%   |
| AMD FX                  | 1        | 0.95%   |
| AMD Athlon 64 X2        | 1        | 0.95%   |
| AMD Athlon              | 1        | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 68       | 64.76%  |
| 2       | 20       | 19.05%  |
| Unknown | 5        | 4.76%   |
| 16      | 4        | 3.81%   |
| 6       | 4        | 3.81%   |
| 24      | 3        | 2.86%   |
| 8       | 1        | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 101      | 98.06%  |
| Unknown | 2        | 1.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 72       | 68.57%  |
| 2       | 28       | 26.67%  |
| Unknown | 5        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 17       | 16.19%  |
| Skylake       | 12       | 11.43%  |
| Unknown       | 12       | 11.43%  |
| Puma          | 10       | 9.52%   |
| Silvermont    | 7        | 6.67%   |
| KabyLake      | 6        | 5.71%   |
| IvyBridge     | 6        | 5.71%   |
| Zen           | 4        | 3.81%   |
| SandyBridge   | 4        | 3.81%   |
| Penryn        | 4        | 3.81%   |
| Zen 2         | 3        | 2.86%   |
| Nehalem       | 3        | 2.86%   |
| Broadwell     | 3        | 2.86%   |
| Piledriver    | 2        | 1.9%    |
| Jaguar        | 2        | 1.9%    |
| Goldmont plus | 2        | 1.9%    |
| Core          | 2        | 1.9%    |
| Zen 3         | 1        | 0.95%   |
| Westmere      | 1        | 0.95%   |
| TigerLake     | 1        | 0.95%   |
| K8 Hammer     | 1        | 0.95%   |
| Goldmont      | 1        | 0.95%   |
| Bobcat        | 1        | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 59       | 64.13%  |
| Nvidia                     | 16       | 17.39%  |
| AMD                        | 11       | 11.96%  |
| Matrox Electronics Systems | 4        | 4.35%   |
| ASPEED Technology          | 2        | 2.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 8.6%    |
| Intel JasperLake [UHD Graphics]                                                          | 7        | 7.53%   |
| Intel HD Graphics 530                                                                    | 6        | 6.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5        | 5.38%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 4.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 4.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3        | 3.23%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2        | 2.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 2.15%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2        | 2.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 2.15%   |
| Intel HD Graphics 620                                                                    | 2        | 2.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.15%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 2.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.15%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.08%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.08%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1        | 1.08%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.08%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.08%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.08%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 1.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 1.08%   |
| Intel Iris Pro Graphics P580                                                             | 1        | 1.08%   |
| Intel HD Graphics 630                                                                    | 1        | 1.08%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.08%   |
| Intel HD Graphics 5500                                                                   | 1        | 1.08%   |
| Intel HD Graphics 510                                                                    | 1        | 1.08%   |
| Intel HD Graphics 500                                                                    | 1        | 1.08%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 1        | 1.08%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1        | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 58       | 55.24%  |
| 1 x Nvidia  | 16       | 15.24%  |
| Other       | 13       | 12.38%  |
| 1 x AMD     | 11       | 10.48%  |
| 1 x Matrox  | 4        | 3.81%   |
| 1 x ASPEED  | 2        | 1.9%    |
| Intel + AMD | 1        | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 78       | 75%     |
| Unknown     | 15       | 14.42%  |
| Proprietary | 11       | 10.58%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 89       | 86.41%  |
| 1.01-2.0   | 4        | 3.88%   |
| 5.01-6.0   | 3        | 2.91%   |
| 0.51-1.0   | 3        | 2.91%   |
| 3.01-4.0   | 2        | 1.94%   |
| 7.01-8.0   | 1        | 0.97%   |
| 8.01-16.0  | 1        | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 26.92%  |
| Hewlett-Packard      | 5        | 19.23%  |
| Philips              | 4        | 15.38%  |
| Iiyama               | 2        | 7.69%   |
| Dell                 | 2        | 7.69%   |
| AOC                  | 2        | 7.69%   |
| LG Electronics       | 1        | 3.85%   |
| Goldstar             | 1        | 3.85%   |
| Ancor Communications | 1        | 3.85%   |
| Acer                 | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2        | 6.67%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 2        | 6.67%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2        | 6.67%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2        | 6.67%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2        | 6.67%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch | 1        | 3.33%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1        | 3.33%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1        | 3.33%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1        | 3.33%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1        | 3.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1        | 3.33%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1        | 3.33%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1        | 3.33%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1        | 3.33%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1        | 3.33%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1        | 3.33%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1        | 3.33%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1        | 3.33%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1        | 3.33%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1        | 3.33%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1        | 3.33%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                | 1        | 3.33%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1        | 3.33%   |
| Ancor Communications LCD Monitor VX238                               | 1        | 3.33%   |
| Acer LCD Monitor KG251Q 3840x1080                                    | 1        | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 23.08%  |
| 1920x1200 (WUXGA)  | 5        | 19.23%  |
| 3840x2160 (4K)     | 4        | 15.38%  |
| 2560x1440 (QHD)    | 4        | 15.38%  |
| 3840x1080          | 2        | 7.69%   |
| Unknown            | 2        | 7.69%   |
| 3440x1440          | 1        | 3.85%   |
| 1680x1050 (WSXGA+) | 1        | 3.85%   |
| 1600x1200          | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 27.27%  |
| 27      | 5        | 22.73%  |
| 23      | 4        | 18.18%  |
| 21      | 4        | 18.18%  |
| 24      | 2        | 9.09%   |
| 32      | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 45.45%  |
| Unknown     | 6        | 27.27%  |
| 401-500     | 4        | 18.18%  |
| 701-800     | 1        | 4.55%   |
| 601-700     | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 12       | 57.14%  |
| Unknown | 6        | 28.57%  |
| 16/10   | 3        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 33.33%  |
| Unknown        | 6        | 28.57%  |
| 301-350        | 5        | 23.81%  |
| 251-300        | 2        | 9.52%   |
| 351-500        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 29.17%  |
| Unknown | 6        | 25%     |
| 161-240 | 4        | 16.67%  |
| 101-120 | 4        | 16.67%  |
| 1-50    | 2        | 8.33%   |
| 121-160 | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 83       | 79.05%  |
| 1     | 15       | 14.29%  |
| 2     | 7        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 83       | 62.41%  |
| Realtek Semiconductor    | 32       | 24.06%  |
| Broadcom                 | 6        | 4.51%   |
| Qualcomm Atheros         | 4        | 3.01%   |
| TP-Link                  | 2        | 1.5%    |
| Ralink Technology        | 1        | 0.75%   |
| Mellanox Technologies    | 1        | 0.75%   |
| MediaTek                 | 1        | 0.75%   |
| Marvell Technology Group | 1        | 0.75%   |
| D-Link System            | 1        | 0.75%   |
| Apple                    | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 28       | 17.07%  |
| Intel I211 Gigabit Network Connection                                         | 17       | 10.37%  |
| Intel I210 Gigabit Network Connection                                         | 16       | 9.76%   |
| Intel 82574L Gigabit Network Connection                                       | 10       | 6.1%    |
| Intel Ethernet Controller I226-V                                              | 9        | 5.49%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 3.66%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 3.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 3.05%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 2.44%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 2.44%   |
| Intel Ethernet Controller I225-V                                              | 3        | 1.83%   |
| Intel Ethernet Connection I217-V                                              | 3        | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.83%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.22%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.22%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 0.61%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter               | 1        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 0.61%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.61%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.61%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.61%   |
| Intel Wireless 8265 / 8275                                                    | 1        | 0.61%   |
| Intel Wireless 7260                                                           | 1        | 0.61%   |
| Intel Wireless 3165                                                           | 1        | 0.61%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 0.61%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.61%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 43.75%  |
| Realtek Semiconductor | 3        | 18.75%  |
| TP-Link               | 2        | 12.5%   |
| Qualcomm Atheros      | 2        | 12.5%   |
| Ralink Technology     | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                    | 1        | 6.25%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 1        | 6.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter        | 1        | 6.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1        | 6.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                           | 1        | 6.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1        | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 1        | 6.25%   |
| Intel Wireless-AC 9260                                          | 1        | 6.25%   |
| Intel Wireless 8265 / 8275                                      | 1        | 6.25%   |
| Intel Wireless 7260                                             | 1        | 6.25%   |
| Intel Wireless 3165                                             | 1        | 6.25%   |
| Intel Wi-Fi 6 AX200                                             | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 1        | 6.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter              | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 80       | 65.57%  |
| Realtek Semiconductor    | 31       | 25.41%  |
| Broadcom                 | 5        | 4.1%    |
| Qualcomm Atheros         | 2        | 1.64%   |
| MediaTek                 | 1        | 0.82%   |
| Marvell Technology Group | 1        | 0.82%   |
| D-Link System            | 1        | 0.82%   |
| Apple                    | 1        | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 28       | 19.05%  |
| Intel I211 Gigabit Network Connection                                         | 17       | 11.56%  |
| Intel I210 Gigabit Network Connection                                         | 16       | 10.88%  |
| Intel 82574L Gigabit Network Connection                                       | 10       | 6.8%    |
| Intel Ethernet Controller I226-V                                              | 9        | 6.12%   |
| Intel I350 Gigabit Network Connection                                         | 6        | 4.08%   |
| Intel Ethernet Connection I217-LM                                             | 6        | 4.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 3.4%    |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 2.72%   |
| Intel 82580 Gigabit Network Connection                                        | 4        | 2.72%   |
| Intel Ethernet Controller I225-V                                              | 3        | 2.04%   |
| Intel Ethernet Connection I217-V                                              | 3        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 2.04%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.36%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2        | 1.36%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 1.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1        | 0.68%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.68%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 0.68%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.68%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.68%   |
| Intel Ethernet Connection I218-V                                              | 1        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.68%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 0.68%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.68%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 0.68%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 1        | 0.68%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 0.68%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 0.68%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.68%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.68%   |
| Broadcom NetXtreme BCM5701 Gigabit Ethernet                                   | 1        | 0.68%   |
| Apple Ethernet Adapter [A1277]                                                | 1        | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 102      | 85.71%  |
| WiFi     | 16       | 13.45%  |
| Unknown  | 1        | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 30       | 28.04%  |
| 4     | 22       | 20.56%  |
| 3     | 19       | 17.76%  |
| 1     | 13       | 12.15%  |
| 6     | 9        | 8.41%   |
| 5     | 7        | 6.54%   |
| 7     | 3        | 2.8%    |
| 13    | 1        | 0.93%   |
| 9     | 1        | 0.93%   |
| 8     | 1        | 0.93%   |
| 0     | 1        | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 97       | 90.65%  |
| Yes  | 10       | 9.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 46.15%  |
| Cambridge Silicon Radio | 4        | 30.77%  |
| IMC Networks            | 1        | 7.69%   |
| Dell                    | 1        | 7.69%   |
| Apple                   | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4        | 30.77%  |
| Intel Bluetooth wireless interface                   | 3        | 23.08%  |
| Intel Wireless-AC 3168 Bluetooth                     | 2        | 15.38%  |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 1        | 7.69%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 7.69%   |
| Dell Wireless 355C Bluetooth 2.0 + EDR module        | 1        | 7.69%   |
| Apple Bluetooth Host Controller                      | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 55       | 59.14%  |
| Nvidia                   | 16       | 17.2%   |
| AMD                      | 16       | 17.2%   |
| Realtek Semiconductor    | 1        | 1.08%   |
| Philips (or NXP)         | 1        | 1.08%   |
| Nordic Semiconductor ASA | 1        | 1.08%   |
| Hewlett-Packard          | 1        | 1.08%   |
| GN Netcom                | 1        | 1.08%   |
| BEHRINGER International  | 1        | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 8.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9        | 7.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9        | 7.96%   |
| Intel Jasper Lake HD Audio                                                                        | 7        | 6.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 4.42%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 2.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 2.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3        | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 2.65%   |
| Intel 8 Series HD Audio Controller                                                                | 3        | 2.65%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 2.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3        | 2.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 1.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.77%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2        | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 1.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.77%   |
| Realtek Semiconductor Microphone(Attila) Microphone(Attila) Microphone(Attila)                    | 1        | 0.88%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.88%   |
| Nvidia MCP65 High Definition Audio                                                                | 1        | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1        | 0.88%   |
| Nordic Semiconductor ASA USB Composite Device Mic Device                                          | 1        | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 0.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 19       | 18.27%  |
| Unknown             | 17       | 16.35%  |
| Samsung Electronics | 15       | 14.42%  |
| Kingston            | 10       | 9.62%   |
| Micron Technology   | 9        | 8.65%   |
| SK hynix            | 7        | 6.73%   |
| Crucial             | 7        | 6.73%   |
| G.Skill             | 5        | 4.81%   |
| Ramaxel Technology  | 3        | 2.88%   |
| Kimtigo             | 3        | 2.88%   |
| Unknown             | 2        | 1.92%   |
| Smart Modular       | 1        | 0.96%   |
| Mushkin             | 1        | 0.96%   |
| HPE                 | 1        | 0.96%   |
| Hewlett-Packard     | 1        | 0.96%   |
| Elpida              | 1        | 0.96%   |
| ASint Technology    | 1        | 0.96%   |
| Apacer              | 1        | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 8        | 7.14%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 4        | 3.57%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s          | 3        | 2.68%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 2        | 1.79%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s               | 2        | 1.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 2        | 1.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 2        | 1.79%   |
| Unknown                                                 | 2        | 1.79%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.89%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s              | 1        | 0.89%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s            | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s            | 1        | 0.89%   |
| Unknown RAM Module 1GB DIMM SDRAM                       | 1        | 0.89%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 1        | 0.89%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.89%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s              | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s            | 1        | 0.89%   |
| Smart Modular RAM Module 4GB DIMM DDR3 1333MT/s         | 1        | 0.89%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.89%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 0.89%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 0.89%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s    | 1        | 0.89%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 1        | 0.89%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s               | 1        | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 0.89%   |
| Samsung RAM M471B5173BH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 1        | 0.89%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1        | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s | 1        | 0.89%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s     | 1        | 0.89%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Samsung RAM M378B1G73BH0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 0.89%   |
| Ramaxel RAM RMUA5120MB86H9F2400 4GB DIMM DDR4 2400MT/s  | 1        | 0.89%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s  | 1        | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 51       | 53.13%  |
| DDR4    | 36       | 37.5%   |
| DDR2    | 4        | 4.17%   |
| SDRAM   | 2        | 2.08%   |
| Unknown | 2        | 2.08%   |
| DDR5    | 1        | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 63       | 65.63%  |
| SODIMM | 33       | 34.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 42       | 40.38%  |
| 4096  | 36       | 34.62%  |
| 16384 | 12       | 11.54%  |
| 2048  | 7        | 6.73%   |
| 1024  | 6        | 5.77%   |
| 32768 | 1        | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 28       | 28%     |
| 1333    | 22       | 22%     |
| 2133    | 12       | 12%     |
| 3200    | 11       | 11%     |
| 2667    | 7        | 7%      |
| 2400    | 4        | 4%      |
| 800     | 4        | 4%      |
| 667     | 3        | 3%      |
| 2666    | 2        | 2%      |
| Unknown | 2        | 2%      |
| 4800    | 1        | 1%      |
| 4400    | 1        | 1%      |
| 1867    | 1        | 1%      |
| 1332    | 1        | 1%      |
| 333     | 1        | 1%      |

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
| 1     | 58       | 55.77%  |
| 0     | 34       | 32.69%  |
| 2     | 10       | 9.62%   |
| 5     | 1        | 0.96%   |
| 3     | 1        | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 62       | 79.49%  |
| Net/wireless             | 6        | 7.69%   |
| Bluetooth                | 4        | 5.13%   |
| Sound                    | 2        | 2.56%   |
| Storage/ata              | 1        | 1.28%   |
| Net/ethernet             | 1        | 1.28%   |
| Graphics card            | 1        | 1.28%   |
| Firewire controller      | 1        | 1.28%   |

