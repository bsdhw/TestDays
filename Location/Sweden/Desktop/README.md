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

Total: 93

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | CRESCENTBAY                 | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| Shuttle       | SH570                       | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| HPE           | ProLiant MicroServer Gen... | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| AOPEN         | iBTMx-DS R1.04 55DED10A0... | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| ASUSTek       | AM1I-A                      | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| ASUSTek       | P8H77-I                     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| Dell          | 0T10XW A01                  | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
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
| PC Engines    | apu2                        | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
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
| PC Engines    | apu2                        | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| ADI           | MinnowBoard Turbot          | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| ASUSTek       | All Series                  | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| PC Engines    | apu2                        | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| PC Engines    | apu2                        | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | apu2                        | [0d6c7132ff](https://bsd-hardware.info/?probe=0d6c7132ff) | Nov 23, 2020 |
| PC Engines    | apu2                        | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
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


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 21.1        | 8        | 11.27%  |
| OPNsense 21.1.3      | 5        | 7.04%   |
| OPNsense 21.1.2      | 5        | 7.04%   |
| OPNsense 21.7.7      | 4        | 5.63%   |
| OPNsense 21.7.3      | 3        | 4.23%   |
| OPNsense 21.1.8      | 3        | 4.23%   |
| OPNsense 21.1.5      | 3        | 4.23%   |
| OpenBSD 6.8          | 3        | 4.23%   |
| OPNsense 22.1.3      | 2        | 2.82%   |
| OPNsense 21.7.6      | 2        | 2.82%   |
| OPNsense 21.7.1      | 2        | 2.82%   |
| OPNsense 21.7        | 2        | 2.82%   |
| OPNsense 21.1.7      | 2        | 2.82%   |
| OPNsense 20.7.8      | 2        | 2.82%   |
| FreeBSD 13.0-p7      | 2        | 2.82%   |
| FreeBSD 12.2-p4      | 2        | 2.82%   |
| pfSense 2.5.0        | 1        | 1.41%   |
| OPNsense 22.1.6      | 1        | 1.41%   |
| OPNsense 22.1.5      | 1        | 1.41%   |
| OPNsense 22.1.2      | 1        | 1.41%   |
| OPNsense 22.1.1      | 1        | 1.41%   |
| OPNsense 22.1        | 1        | 1.41%   |
| OPNsense 21.1.6      | 1        | 1.41%   |
| OPNsense 21.1.1      | 1        | 1.41%   |
| OpenBSD 7.0          | 1        | 1.41%   |
| OpenBSD 6.7          | 1        | 1.41%   |
| helloSystem 0.5.0    | 1        | 1.41%   |
| GhostBSD 19.12       | 1        | 1.41%   |
| FuryBSD 12.2-p3      | 1        | 1.41%   |
| FreeBSD 14.0-CURRENT | 1        | 1.41%   |
| FreeBSD 13.1-RC2     | 1        | 1.41%   |
| FreeBSD 13.0-p5      | 1        | 1.41%   |
| FreeBSD 13.0-p4      | 1        | 1.41%   |
| FreeBSD 13.0-p2      | 1        | 1.41%   |
| FreeBSD 12.1-p8      | 1        | 1.41%   |
| FreeBSD 12.1-p7      | 1        | 1.41%   |
| FreeBSD 12.1-p10     | 1        | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 42       | 67.74%  |
| FreeBSD     | 11       | 17.74%  |
| OpenBSD     | 5        | 8.06%   |
| pfSense     | 1        | 1.61%   |
| helloSystem | 1        | 1.61%   |
| GhostBSD    | 1        | 1.61%   |
| FuryBSD     | 1        | 1.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 61       | 98.39%  |
| octeon | 1        | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 48       | 76.19%  |
| KDE5         | 7        | 11.11%  |
| fvwm         | 3        | 4.76%   |
| xfwm         | 1        | 1.59%   |
| XFCE         | 1        | 1.59%   |
| TWM          | 1        | 1.59%   |
| helloDesktop | 1        | 1.59%   |
| AwesomeWM    | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 48       | 77.42%  |
| X11     | 14       | 22.58%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 52       | 80%     |
| SDDM    | 7        | 10.77%  |
| LightDM | 2        | 3.08%   |
| GDM     | 2        | 3.08%   |
| XDM     | 1        | 1.54%   |
| SLiM    | 1        | 1.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 49       | 76.56%  |
| C              | 6        | 9.38%   |
| en_US          | 4        | 6.25%   |
| sv_SE          | 3        | 4.69%   |
| sv_SE.US-ASCII | 1        | 1.56%   |
| en_CA          | 1        | 1.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 51       | 80.95%  |
| BIOS | 12       | 19.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 42       | 67.74%  |
| Zfs  | 15       | 24.19%  |
| Ffs  | 5        | 8.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 56       | 88.89%  |
| MBR  | 7        | 11.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 10       | 16.13%  |
| PC Engines                 | 6        | 9.68%   |
| Gigabyte Technology        | 6        | 9.68%   |
| Unknown                    | 6        | 9.68%   |
| Hewlett-Packard            | 5        | 8.06%   |
| Dell                       | 5        | 8.06%   |
| Intel                      | 4        | 6.45%   |
| MSI                        | 3        | 4.84%   |
| Lenovo                     | 3        | 4.84%   |
| Shuttle                    | 2        | 3.23%   |
| ASRock                     | 2        | 3.23%   |
| Wistron                    | 1        | 1.61%   |
| ShenZhen MinWin Technology | 1        | 1.61%   |
| Protectli                  | 1        | 1.61%   |
| HPE                        | 1        | 1.61%   |
| Fujitsu Siemens            | 1        | 1.61%   |
| Fujitsu                    | 1        | 1.61%   |
| Deciso                     | 1        | 1.61%   |
| AOPEN                      | 1        | 1.61%   |
| AMI                        | 1        | 1.61%   |
| ADI                        | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 6        | 9.68%   |
| PC Engines apu2                     | 4        | 6.45%   |
| ASUS All Series                     | 4        | 6.45%   |
| PC Engines apu4                     | 2        | 3.23%   |
| Dell OptiPlex 9020                  | 2        | 3.23%   |
| Wistron ProLiant ML110 G6           | 1        | 1.61%   |
| Shuttle SH570                       | 1        | 1.61%   |
| Shuttle DH170                       | 1        | 1.61%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1        | 1.61%   |
| Protectli FW4B                      | 1        | 1.61%   |
| MSI WC776AA-UUW HPE-110sc           | 1        | 1.61%   |
| MSI MS-7C56                         | 1        | 1.61%   |
| MSI MS-7918                         | 1        | 1.61%   |
| Lenovo ThinkCentre M92p 2988B1G     | 1        | 1.61%   |
| Lenovo ThinkCentre Edge72 3493AZG   | 1        | 1.61%   |
| Lenovo ThinkCentre E73 10AS002QMX   | 1        | 1.61%   |
| Intel Q3XXG4-P V1.0                 | 1        | 1.61%   |
| Intel DQ67SW AAG12527-306           | 1        | 1.61%   |
| Intel DH61AG AAG81491-600           | 1        | 1.61%   |
| Intel CRESCENTBAY                   | 1        | 1.61%   |
| HPE ProLiant MicroServer Gen10 Plus | 1        | 1.61%   |
| HP Z230 Tower Workstation           | 1        | 1.61%   |
| HP ProLiant ML30 Gen9               | 1        | 1.61%   |
| HP ProDesk 400 G4 MT                | 1        | 1.61%   |
| HP EliteDesk 800 G2 TWR             | 1        | 1.61%   |
| HP EliteDesk 800 G2 SFF             | 1        | 1.61%   |
| Gigabyte Z87M-D3H                   | 1        | 1.61%   |
| Gigabyte Z68X-UD7-B3                | 1        | 1.61%   |
| Gigabyte Z170X-UD5 TH               | 1        | 1.61%   |
| Gigabyte B550I AORUS PRO AX         | 1        | 1.61%   |
| Gigabyte AB350M-Gaming 3            | 1        | 1.61%   |
| Gigabyte 970A-DS3P                  | 1        | 1.61%   |
| Fujitsu Siemens ESPRIMO P5730       | 1        | 1.61%   |
| Fujitsu ESPRIMO E720                | 1        | 1.61%   |
| Dell OptiPlex 5055 Ryzen CPU        | 1        | 1.61%   |
| Dell OptiPlex 3040                  | 1        | 1.61%   |
| Dell OptiPlex 3010                  | 1        | 1.61%   |
| Deciso Netboard A10 V2              | 1        | 1.61%   |
| ASUS ROG STRIX X570-F GAMING        | 1        | 1.61%   |
| ASUS Rampage Formula                | 1        | 1.61%   |
| ASUS P8H77-I                        | 1        | 1.61%   |
| ASUS P8H67-M                        | 1        | 1.61%   |
| ASUS P5Q DELUXE                     | 1        | 1.61%   |
| ASUS M32CD_A_F_K20CD_K31CD          | 1        | 1.61%   |
| ASRock X99 WS                       | 1        | 1.61%   |
| ASRock E3C226D2I                    | 1        | 1.61%   |
| AOPEN DE3250                        | 1        | 1.61%   |
| AMI PEISIA E3845 VER1.0             | 1        | 1.61%   |
| ADI Minnowboard Turbot D0 PLATFORM  | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 6        | 9.68%   |
| Dell OptiPlex                  | 5        | 8.06%   |
| PC Engines APU2                | 4        | 6.45%   |
| ASUS All                       | 4        | 6.45%   |
| Lenovo ThinkCentre             | 3        | 4.84%   |
| PC Engines apu4                | 2        | 3.23%   |
| HP EliteDesk                   | 2        | 3.23%   |
| Wistron ProLiant               | 1        | 1.61%   |
| Shuttle SH570                  | 1        | 1.61%   |
| Shuttle DH170                  | 1        | 1.61%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.61%   |
| Protectli FW4B                 | 1        | 1.61%   |
| MSI WC776AA-UUW                | 1        | 1.61%   |
| MSI MS-7C56                    | 1        | 1.61%   |
| MSI MS-7918                    | 1        | 1.61%   |
| Intel Q3XXG4-P                 | 1        | 1.61%   |
| Intel DQ67SW                   | 1        | 1.61%   |
| Intel DH61AG                   | 1        | 1.61%   |
| Intel CRESCENTBAY              | 1        | 1.61%   |
| HPE ProLiant                   | 1        | 1.61%   |
| HP Z230                        | 1        | 1.61%   |
| HP ProLiant                    | 1        | 1.61%   |
| HP ProDesk                     | 1        | 1.61%   |
| Gigabyte Z87M-D3H              | 1        | 1.61%   |
| Gigabyte Z68X-UD7-B3           | 1        | 1.61%   |
| Gigabyte Z170X-UD5             | 1        | 1.61%   |
| Gigabyte B550I                 | 1        | 1.61%   |
| Gigabyte AB350M-Gaming         | 1        | 1.61%   |
| Gigabyte 970A-DS3P             | 1        | 1.61%   |
| Fujitsu Siemens ESPRIMO        | 1        | 1.61%   |
| Fujitsu ESPRIMO                | 1        | 1.61%   |
| Deciso Netboard                | 1        | 1.61%   |
| ASUS ROG                       | 1        | 1.61%   |
| ASUS Rampage                   | 1        | 1.61%   |
| ASUS P8H77-I                   | 1        | 1.61%   |
| ASUS P8H67-M                   | 1        | 1.61%   |
| ASUS P5Q                       | 1        | 1.61%   |
| ASUS M32CD                     | 1        | 1.61%   |
| ASRock X99                     | 1        | 1.61%   |
| ASRock E3C226D2I               | 1        | 1.61%   |
| AOPEN DE3250                   | 1        | 1.61%   |
| AMI PEISIA                     | 1        | 1.61%   |
| ADI Minnowboard                | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 10       | 16.13%  |
| 2016    | 10       | 16.13%  |
| 2014    | 8        | 12.9%   |
| 2021    | 7        | 11.29%  |
| 2017    | 6        | 9.68%   |
| 2020    | 5        | 8.06%   |
| 2010    | 4        | 6.45%   |
| 2013    | 3        | 4.84%   |
| 2012    | 3        | 4.84%   |
| 2019    | 2        | 3.23%   |
| 2009    | 2        | 3.23%   |
| 2015    | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 88.71%  |
| Yes  | 7        | 11.29%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 19       | 29.69%  |
| 4.01-8.0    | 17       | 26.56%  |
| 16.01-24.0  | 12       | 18.75%  |
| 32.01-64.0  | 10       | 15.63%  |
| 2.01-3.0    | 2        | 3.13%   |
| 64.01-256.0 | 2        | 3.13%   |
| 24.01-32.0  | 1        | 1.56%   |
| 1.01-2.0    | 1        | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 30       | 46.88%  |
| 0.51-1.0   | 20       | 31.25%  |
| 1.01-2.0   | 8        | 12.5%   |
| 4.01-8.0   | 4        | 6.25%   |
| 3.01-4.0   | 1        | 1.56%   |
| 24.01-32.0 | 1        | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 66.67%  |
| 2      | 6        | 9.09%   |
| 3      | 4        | 6.06%   |
| 0      | 4        | 6.06%   |
| 4      | 3        | 4.55%   |
| 6      | 2        | 3.03%   |
| 12     | 1        | 1.52%   |
| 10     | 1        | 1.52%   |
| 9      | 1        | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 80.95%  |
| Yes       | 12       | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 61       | 98.39%  |
| No        | 1        | 1.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 90.48%  |
| Yes       | 6        | 9.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 90.32%  |
| Yes       | 6        | 9.68%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Sweden  | 62       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Stockholm             | 10       | 14.29%  |
| Malmo                 | 8        | 11.43%  |
| Bromma                | 4        | 5.71%   |
| Taby                  | 3        | 4.29%   |
| VÃ¤sterÃ¥s        | 2        | 2.86%   |
| UmeГҐ               | 2        | 2.86%   |
| Tumba                 | 2        | 2.86%   |
| Sollentuna            | 2        | 2.86%   |
| Solleftea             | 2        | 2.86%   |
| Lund                  | 2        | 2.86%   |
| LinkГ¶ping          | 2        | 2.86%   |
| JГ¶nkГ¶ping       | 2        | 2.86%   |
| Helsingborg           | 2        | 2.86%   |
| Г…hus              | 1        | 1.43%   |
| Г„lvГ¤ngen       | 1        | 1.43%   |
| Upplands Vasby        | 1        | 1.43%   |
| UmeÃ¥               | 1        | 1.43%   |
| Umeå                 | 1        | 1.43%   |
| Tyreso Strand         | 1        | 1.43%   |
| Trelleborg            | 1        | 1.43%   |
| Trangsund             | 1        | 1.43%   |
| Torsby                | 1        | 1.43%   |
| SГ¶dertГ¤lje      | 1        | 1.43%   |
| Sundsvall             | 1        | 1.43%   |
| Sundbyberg            | 1        | 1.43%   |
| Stroemstad            | 1        | 1.43%   |
| SkÃ¶vde             | 1        | 1.43%   |
| Skaellinge            | 1        | 1.43%   |
| Saltsjoe-Boo          | 1        | 1.43%   |
| NorrkГ¶ping         | 1        | 1.43%   |
| Landskrona            | 1        | 1.43%   |
| Kungsbacka            | 1        | 1.43%   |
| Kristianstad          | 1        | 1.43%   |
| Kista                 | 1        | 1.43%   |
| Hudiksvall            | 1        | 1.43%   |
| Halmstad              | 1        | 1.43%   |
| Grebbestad            | 1        | 1.43%   |
| Enskede-Arsta-Vantoer | 1        | 1.43%   |
| Bandhagen             | 1        | 1.43%   |
| Akarp                 | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 22     | 17.65%  |
| WDC                 | 10       | 13     | 11.76%  |
| Seagate             | 10       | 25     | 11.76%  |
| Hoodisk             | 9        | 11     | 10.59%  |
| Kingston            | 8        | 10     | 9.41%   |
| Intel               | 6        | 10     | 7.06%   |
| Toshiba             | 5        | 13     | 5.88%   |
| Crucial             | 4        | 12     | 4.71%   |
| SanDisk             | 2        | 3      | 2.35%   |
| Phison              | 2        | 2      | 2.35%   |
| NVMe                | 2        | 3      | 2.35%   |
| Hitachi             | 2        | 2      | 2.35%   |
| Apacer              | 2        | 2      | 2.35%   |
| XrayDisk            | 1        | 1      | 1.18%   |
| Transcend           | 1        | 1      | 1.18%   |
| SK Hynix            | 1        | 1      | 1.18%   |
| OCZ                 | 1        | 2      | 1.18%   |
| LITEONIT            | 1        | 1      | 1.18%   |
| LITEON              | 1        | 1      | 1.18%   |
| InnoDisk            | 1        | 1      | 1.18%   |
| Fordisk             | 1        | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Hoodisk SSD 128GB                           | 3        | 3.23%   |
| WDC WD5000AZLX-60K2TA0 500GB                | 2        | 2.15%   |
| Toshiba HDWQ140 4TB                         | 2        | 2.15%   |
| Samsung SSD 860 QVO 1TB                     | 2        | 2.15%   |
| Samsung HD501LJ 500GB                       | 2        | 2.15%   |
| Phison SATA SSD 16GB                        | 2        | 2.15%   |
| Kingston SV300S37A240G 240GB                | 2        | 2.15%   |
| Intel SSDSC2BW240A4 240GB                   | 2        | 2.15%   |
| Hoodisk SSD 64GB                            | 2        | 2.15%   |
| Hoodisk SSD 16GB                            | 2        | 2.15%   |
| Crucial CT256MX100SSD1 256GB                | 2        | 2.15%   |
| Apacer 64GB SATA Flash Drive                | 2        | 2.15%   |
| XrayDisk SSD 64GB                           | 1        | 1.08%   |
| WDC WDS250G2B0C-00PXH0 250GB                | 1        | 1.08%   |
| WDC WDS250G2B0A-00SM50 250GB                | 1        | 1.08%   |
| WDC WDS120G1G0A-00SS50 120GB                | 1        | 1.08%   |
| WDC WD82PURZ-85TEUY0 8TB                    | 1        | 1.08%   |
| WDC WD5000AAKS-07V0A0 500GB                 | 1        | 1.08%   |
| WDC WD2500AAJS-60B4A0 250GB                 | 1        | 1.08%   |
| WDC WD20EARX-00ZUDB0 2TB                    | 1        | 1.08%   |
| WDC WD2002FYPS-02W3B0 2TB                   | 1        | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1        | 1.08%   |
| Transcend TS256GMSA452T 256GB               | 1        | 1.08%   |
| Toshiba HDWR11A 10TB                        | 1        | 1.08%   |
| Toshiba HDWN180 8TB                         | 1        | 1.08%   |
| Toshiba HDWG480 8TB                         | 1        | 1.08%   |
| Toshiba HDWG180 8TB                         | 1        | 1.08%   |
| Toshiba DT01ACA100 1TB                      | 1        | 1.08%   |
| SK Hynix HFS128G32MND-2200A 128GB           | 1        | 1.08%   |
| Seagate ST9500325AS 500GB                   | 1        | 1.08%   |
| Seagate ST8000VX0022-2EJ112 8TB             | 1        | 1.08%   |
| Seagate ST4000NE0025-2EW107 4TB             | 1        | 1.08%   |
| Seagate ST4000DM005-2DP166 4TB              | 1        | 1.08%   |
| Seagate ST4000DM000-2AE166 4TB              | 1        | 1.08%   |
| Seagate ST4000DM000-1F2168 4TB              | 1        | 1.08%   |
| Seagate ST2000NC001-1DY164 2TB              | 1        | 1.08%   |
| Seagate ST2000DM008-2FR102 2TB              | 1        | 1.08%   |
| Seagate ST100FN0021 100GB                   | 1        | 1.08%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB         | 1        | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB              | 1        | 1.08%   |
| Seagate FireCuda 520 SSD ZP500GM30002 500GB | 1        | 1.08%   |
| SanDisk SDSSDHII960G 960GB                  | 1        | 1.08%   |
| SanDisk SDCFX3-4096 4GB                     | 1        | 1.08%   |
| Samsung SSD 970 EVO Plus 250GB              | 1        | 1.08%   |
| Samsung SSD 960 EVO 250GB                   | 1        | 1.08%   |
| Samsung SSD 860 EVO mSATA 250GB             | 1        | 1.08%   |
| Samsung SSD 860 EVO 250GB                   | 1        | 1.08%   |
| Samsung SSD 860 EVO 1TB                     | 1        | 1.08%   |
| Samsung SSD 850 EVO 500GB                   | 1        | 1.08%   |
| Samsung SSD 850 EVO 1TB                     | 1        | 1.08%   |
| Samsung SSD 840 Series 120GB                | 1        | 1.08%   |
| Samsung SSD 840 PRO Series 256GB            | 1        | 1.08%   |
| Samsung SSD 840 EVO 500GB                   | 1        | 1.08%   |
| Samsung MZ7TY128HDHP-000L1 128GB            | 1        | 1.08%   |
| Samsung MZ7LN256HMJP-000H1 256GB            | 1        | 1.08%   |
| Samsung HD103UJ 1TB                         | 1        | 1.08%   |
| OCZ AGILITY3 120GB                          | 1        | 1.08%   |
| NVMe Samsung SSD 980 500GB                  | 1        | 1.08%   |
| NVMe SAMSUNG MZVPV256 256GB                 | 1        | 1.08%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB           | 1        | 1.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 23     | 33.33%  |
| WDC                 | 7        | 9      | 25.93%  |
| Toshiba             | 5        | 13     | 18.52%  |
| Samsung Electronics | 3        | 4      | 11.11%  |
| Hitachi             | 2        | 2      | 7.41%   |
| NVMe                | 1        | 2      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 16     | 19.64%  |
| Hoodisk             | 9        | 11     | 16.07%  |
| Kingston            | 8        | 10     | 14.29%  |
| Intel               | 6        | 10     | 10.71%  |
| Crucial             | 4        | 12     | 7.14%   |
| WDC                 | 2        | 3      | 3.57%   |
| SanDisk             | 2        | 3      | 3.57%   |
| Phison              | 2        | 2      | 3.57%   |
| Apacer              | 2        | 2      | 3.57%   |
| XrayDisk            | 1        | 1      | 1.79%   |
| Transcend           | 1        | 1      | 1.79%   |
| SK Hynix            | 1        | 1      | 1.79%   |
| Seagate             | 1        | 1      | 1.79%   |
| OCZ                 | 1        | 2      | 1.79%   |
| NVMe                | 1        | 1      | 1.79%   |
| LITEONIT            | 1        | 1      | 1.79%   |
| LITEON              | 1        | 1      | 1.79%   |
| InnoDisk            | 1        | 1      | 1.79%   |
| Fordisk             | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 47       | 80     | 68.12%  |
| HDD  | 18       | 53     | 26.09%  |
| NVMe | 4        | 4      | 5.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 57       | 133    | 93.44%  |
| NVMe | 4        | 4      | 6.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 49       | 83     | 67.12%  |
| 0.51-1.0   | 10       | 17     | 13.7%   |
| 3.01-4.0   | 6        | 14     | 8.22%   |
| 1.01-2.0   | 5        | 9      | 6.85%   |
| 4.01-10.0  | 3        | 10     | 4.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 29       | 46.77%  |
| 51-100     | 9        | 14.52%  |
| 1-20       | 8        | 12.9%   |
| 21-50      | 7        | 11.29%  |
| 251-500    | 4        | 6.45%   |
| 1001-2000  | 3        | 4.84%   |
| 501-1000   | 2        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 52       | 81.25%  |
| 21-50   | 10       | 15.63%  |
| 251-500 | 2        | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD2500AAJS-60B4A0 250GB       | 1        | 2      | 14.29%  |
| WDC WD20EARX-00ZUDB0 2TB          | 1        | 1      | 14.29%  |
| WDC WD2002FYPS-02W3B0 2TB         | 1        | 1      | 14.29%  |
| SK Hynix HFS128G32MND-2200A 128GB | 1        | 1      | 14.29%  |
| Seagate ST100FN0021 100GB         | 1        | 1      | 14.29%  |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 14.29%  |
| Intel SSDSC2CT120A3 120GB         | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 3        | 4      | 42.86%  |
| SK Hynix | 1        | 1      | 14.29%  |
| Seagate  | 1        | 1      | 14.29%  |
| Kingston | 1        | 1      | 14.29%  |
| Intel    | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 3        | 4      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 4        | 4      | 57.14%  |
| HDD  | 3        | 4      | 42.86%  |

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
| Works    | 52       | 120    | 80%     |
| Malfunc  | 7        | 8      | 10.77%  |
| Detected | 6        | 9      | 9.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 46       | 62.16%  |
| AMD                      | 14       | 18.92%  |
| Samsung Electronics      | 4        | 5.41%   |
| Broadcom / LSI           | 3        | 4.05%   |
| Marvell Technology Group | 2        | 2.7%    |
| ASMedia Technology       | 2        | 2.7%    |
| VIA Technologies         | 1        | 1.35%   |
| Seagate Technology       | 1        | 1.35%   |
| Sandisk                  | 1        | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 11.9%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 8.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 4.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 3.57%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 3.57%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 2.38%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 2.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 2.38%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.38%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 2.38%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 1.19%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 1.19%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.19%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.19%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 1.19%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 1.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.19%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.19%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 1.19%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.19%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.19%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.19%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 54       | 72.97%  |
| IDE  | 8        | 10.81%  |
| NVMe | 6        | 8.11%   |
| RAID | 3        | 4.05%   |
| SAS  | 3        | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 47       | 75.81%  |
| AMD     | 14       | 22.58%  |
| Unknown | 1        | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD GX-412TC SOC                        | 6        | 9.68%   |
| Intel Core i7-4770K CPU @ 3.50GHz       | 3        | 4.84%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3        | 4.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2        | 3.23%   |
| Intel Celeron CPU J3160 @ 1.60GHz       | 2        | 3.23%   |
| Intel Atom CPU E3845 @ 1.91GHz          | 2        | 3.23%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2        | 3.23%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 2        | 3.23%   |
| Intel Xeon E-2224 CPU @ 3.40GHz         | 1        | 1.61%   |
| Intel Xeon CPU E5450 @ 3.00GHz          | 1        | 1.61%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz    | 1        | 1.61%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz     | 1        | 1.61%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz     | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E5700       | 1        | 1.61%   |
| Intel Pentium CPU G6950 @ 2.80GHz       | 1        | 1.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz       | 1        | 1.61%   |
| Intel Core i7-6850K CPU @ 3.60GHz       | 1        | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1        | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1        | 1.61%   |
| Intel Core i7-5550U CPU @ 2.00GHz       | 1        | 1.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1        | 1.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1        | 1.61%   |
| Intel Core i7-3770S CPU @ 3.10GHz       | 1        | 1.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 1        | 1.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz        | 1        | 1.61%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 1        | 1.61%   |
| Intel Core i5-4670K CPU @ 3.40GHz       | 1        | 1.61%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1        | 1.61%   |
| Intel Core i5-3570K CPU @ 3.40GHz       | 1        | 1.61%   |
| Intel Core i5-3470S CPU @ 2.90GHz       | 1        | 1.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1        | 1.61%   |
| Intel Core i5-2300 CPU @ 2.80GHz        | 1        | 1.61%   |
| Intel Core i5-2300 CPU                  | 1        | 1.61%   |
| Intel Core i5 CPU 750 @ 2.67GHz         | 1        | 1.61%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 1        | 1.61%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 1        | 1.61%   |
| Intel Core i3-3220 CPU @ 3.30GHz        | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz    | 1        | 1.61%   |
| Intel Celeron CPU N2930 @ 1.83GHz       | 1        | 1.61%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 1        | 1.61%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1        | 1.61%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1        | 1.61%   |
| AMD GX-416RA SOC                        | 1        | 1.61%   |
| AMD FX-6300 Six-Core Processor          | 1        | 1.61%   |
| AMD Athlon 5370 APU with Radeon R3      | 1        | 1.61%   |
|                                         | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 22.58%  |
| Intel Core i7           | 13       | 20.97%  |
| AMD GX                  | 7        | 11.29%  |
| Intel Xeon              | 5        | 8.06%   |
| Intel Celeron           | 4        | 6.45%   |
| Intel Core i3           | 3        | 4.84%   |
| AMD Ryzen 7             | 3        | 4.84%   |
| Other                   | 2        | 3.23%   |
| Intel Pentium           | 2        | 3.23%   |
| Intel Atom              | 2        | 3.23%   |
| AMD Ryzen 9             | 2        | 3.23%   |
| Intel Pentium Dual-Core | 1        | 1.61%   |
| Intel Core 2 Quad       | 1        | 1.61%   |
| Intel Core 2 Duo        | 1        | 1.61%   |
| AMD FX                  | 1        | 1.61%   |
| AMD Athlon              | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 41       | 66.13%  |
| 2       | 11       | 17.74%  |
| Unknown | 3        | 4.84%   |
| 24      | 2        | 3.23%   |
| 16      | 2        | 3.23%   |
| 6       | 2        | 3.23%   |
| 8       | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 60       | 96.77%  |
| Unknown | 2        | 3.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 41       | 66.13%  |
| 2       | 18       | 29.03%  |
| Unknown | 3        | 4.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 12       | 19.35%  |
| Skylake     | 9        | 14.52%  |
| Puma        | 6        | 9.68%   |
| Silvermont  | 5        | 8.06%   |
| IvyBridge   | 5        | 8.06%   |
| SandyBridge | 3        | 4.84%   |
| Penryn      | 3        | 4.84%   |
| KabyLake    | 3        | 4.84%   |
| Unknown     | 3        | 4.84%   |
| Zen 2       | 2        | 3.23%   |
| Zen         | 2        | 3.23%   |
| Jaguar      | 2        | 3.23%   |
| Broadwell   | 2        | 3.23%   |
| Westmere    | 1        | 1.61%   |
| Piledriver  | 1        | 1.61%   |
| Nehalem     | 1        | 1.61%   |
| Goldmont    | 1        | 1.61%   |
| Core        | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 32       | 59.26%  |
| Nvidia                     | 13       | 24.07%  |
| AMD                        | 5        | 9.26%   |
| Matrox Electronics Systems | 3        | 5.56%   |
| ASPEED Technology          | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 11.11%  |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 7.41%   |
| Intel HD Graphics 530                                                                    | 4        | 7.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 5.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 3.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 3.7%    |
| Intel HD Graphics 620                                                                    | 2        | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 3.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.85%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 1.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 1.85%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1        | 1.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.85%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 1.85%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1        | 1.85%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1        | 1.85%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.85%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1        | 1.85%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1        | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1        | 1.85%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.85%   |
| Intel HD Graphics 510                                                                    | 1        | 1.85%   |
| Intel HD Graphics 500                                                                    | 1        | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 1        | 1.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.85%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 31       | 49.21%  |
| 1 x Nvidia  | 13       | 20.63%  |
| Other       | 9        | 14.29%  |
| 1 x AMD     | 5        | 7.94%   |
| 1 x Matrox  | 3        | 4.76%   |
| Intel + AMD | 1        | 1.59%   |
| 1 x ASPEED  | 1        | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 68.25%  |
| Unknown     | 11       | 17.46%  |
| Proprietary | 9        | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 83.87%  |
| 0.51-1.0   | 3        | 4.84%   |
| 3.01-4.0   | 2        | 3.23%   |
| 1.01-2.0   | 2        | 3.23%   |
| 7.01-8.0   | 1        | 1.61%   |
| 5.01-6.0   | 1        | 1.61%   |
| 8.01-16.0  | 1        | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 33.33%  |
| Hewlett-Packard     | 4        | 22.22%  |
| Iiyama              | 2        | 11.11%  |
| Dell                | 2        | 11.11%  |
| AOC                 | 2        | 11.11%  |
| Philips             | 1        | 5.56%   |
| LG Electronics      | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch | 2        | 9.09%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch             | 2        | 9.09%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                  | 2        | 9.09%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                    | 2        | 9.09%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch | 1        | 4.55%   |
| Samsung Electronics LCD Monitor SyncMaster                        | 1        | 4.55%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                  | 1        | 4.55%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                 | 1        | 4.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch | 1        | 4.55%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch          | 1        | 4.55%   |
| LG Electronics LCD Monitor LX20D 1600x1200                        | 1        | 4.55%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch             | 1        | 4.55%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch     | 1        | 4.55%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch       | 1        | 4.55%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                        | 1        | 4.55%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                       | 1        | 4.55%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch       | 1        | 4.55%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1200 (WUXGA)  | 4        | 22.22%  |
| 3840x2160 (4K)     | 3        | 16.67%  |
| 2560x1440 (QHD)    | 3        | 16.67%  |
| 1920x1080 (FHD)    | 3        | 16.67%  |
| 3840x1080          | 1        | 5.56%   |
| 3440x1440          | 1        | 5.56%   |
| 1680x1050 (WSXGA+) | 1        | 5.56%   |
| 1600x1200          | 1        | 5.56%   |
| Unknown            | 1        | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 5        | 33.33%  |
| 27      | 4        | 26.67%  |
| 23      | 4        | 26.67%  |
| 24      | 1        | 6.67%   |
| 21      | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 53.33%  |
| Unknown     | 5        | 33.33%  |
| 601-700     | 1        | 6.67%   |
| 401-500     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 7        | 50%     |
| Unknown | 5        | 35.71%  |
| 16/10   | 2        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 5        | 35.71%  |
| 301-350        | 4        | 28.57%  |
| 201-250        | 4        | 28.57%  |
| 251-300        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 29.41%  |
| Unknown | 5        | 29.41%  |
| 161-240 | 3        | 17.65%  |
| 1-50    | 2        | 11.76%  |
| 121-160 | 1        | 5.88%   |
| 101-120 | 1        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 49       | 76.56%  |
| 1     | 9        | 14.06%  |
| 2     | 6        | 9.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 48       | 60%     |
| Realtek Semiconductor    | 20       | 25%     |
| Broadcom                 | 5        | 6.25%   |
| TP-Link                  | 2        | 2.5%    |
| Ralink Technology        | 1        | 1.25%   |
| Qualcomm Atheros         | 1        | 1.25%   |
| Mellanox Technologies    | 1        | 1.25%   |
| MediaTek                 | 1        | 1.25%   |
| Marvell Technology Group | 1        | 1.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 18.56%  |
| Intel I210 Gigabit Network Connection                                         | 13       | 13.4%   |
| Intel I211 Gigabit Network Connection                                         | 11       | 11.34%  |
| Intel I350 Gigabit Network Connection                                         | 5        | 5.15%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 5.15%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 4.12%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 4.12%   |
| Intel Ethernet Connection I217-V                                              | 3        | 3.09%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3.09%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.06%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 2.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 1.03%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.03%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 1.03%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 1.03%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.03%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 1.03%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.03%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 1.03%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.03%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.03%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 1.03%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 1.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 1.03%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 1.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1        | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 2        | 33.33%  |
| Realtek Semiconductor | 1        | 16.67%  |
| Ralink Technology     | 1        | 16.67%  |
| Intel                 | 1        | 16.67%  |
| Broadcom              | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]             | 1        | 16.67%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                   | 1        | 16.67%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter | 1        | 16.67%  |
| Ralink RT2870/RT3070 Wireless Adapter                    | 1        | 16.67%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 16.67%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter       | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 47       | 64.38%  |
| Realtek Semiconductor    | 20       | 27.4%   |
| Broadcom                 | 4        | 5.48%   |
| Qualcomm Atheros         | 1        | 1.37%   |
| Marvell Technology Group | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 20.22%  |
| Intel I210 Gigabit Network Connection                                         | 13       | 14.61%  |
| Intel I211 Gigabit Network Connection                                         | 11       | 12.36%  |
| Intel I350 Gigabit Network Connection                                         | 5        | 5.62%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 5.62%   |
| Intel Ethernet Connection I217-LM                                             | 4        | 4.49%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 4.49%   |
| Intel Ethernet Connection I217-V                                              | 3        | 3.37%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 3.37%   |
| Intel 82580 Gigabit Network Connection                                        | 3        | 3.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 2.25%   |
| Intel 82576NS Gigabit Network Connection                                      | 2        | 2.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.12%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 1.12%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.12%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 1.12%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1        | 1.12%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.12%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 1.12%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1        | 1.12%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 1.12%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 1.12%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 1.12%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 61       | 88.41%  |
| WiFi     | 6        | 8.7%    |
| Modem    | 1        | 1.45%   |
| Unknown  | 1        | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 19       | 29.69%  |
| 3     | 12       | 18.75%  |
| 4     | 9        | 14.06%  |
| 1     | 9        | 14.06%  |
| 6     | 7        | 10.94%  |
| 5     | 4        | 6.25%   |
| 7     | 2        | 3.13%   |
| 9     | 1        | 1.56%   |
| 0     | 1        | 1.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 92.06%  |
| Yes  | 5        | 7.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 3        | 50%     |
| IMC Networks            | 1        | 16.67%  |
| Dell                    | 1        | 16.67%  |
| Apple                   | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 3        | 50%     |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip | 1        | 16.67%  |
| Dell Dell Wireless 355C Bluetooth 2.0 + EDR module   | 1        | 16.67%  |
| Apple Apple Broadcom Built-in Bluetooth              | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 32       | 56.14%  |
| Nvidia           | 13       | 22.81%  |
| AMD              | 10       | 17.54%  |
| Philips (or NXP) | 1        | 1.75%   |
| GN Netcom        | 1        | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8        | 11.76%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7        | 10.29%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 8.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5        | 7.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3        | 4.41%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 2.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.94%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1        | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 1.47%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1        | 1.47%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.47%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.47%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.47%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 1.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 1.47%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.47%   |
| GN Netcom Jabra SPEAK 410 USB                                                                     | 1        | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1        | 1.47%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 1.47%   |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 1        | 1.47%   |
| Unknown                                                                                           | 1        | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 13       | 21.67%  |
| Unknown             | 11       | 18.33%  |
| Samsung Electronics | 10       | 16.67%  |
| Micron Technology   | 5        | 8.33%   |
| Kingston            | 5        | 8.33%   |
| SK Hynix            | 4        | 6.67%   |
| Crucial             | 4        | 6.67%   |
| G.Skill             | 2        | 3.33%   |
| Kimtigo             | 1        | 1.67%   |
| HPE                 | 1        | 1.67%   |
| Hewlett-Packard     | 1        | 1.67%   |
| Elpida              | 1        | 1.67%   |
| Apacer              | 1        | 1.67%   |
| Unknown             | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                            | 5        | 7.46%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s                    | 4        | 5.97%   |
| SK Hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s                   | 2        | 2.99%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                              | 2        | 2.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                 | 2        | 2.99%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                   | 1        | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                             | 1        | 1.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s                           | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                                      | 1        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                               | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s                           | 1        | 1.49%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                               | 1        | 1.49%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                             | 1        | 1.49%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s                           | 1        | 1.49%   |
| SK Hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s                   | 1        | 1.49%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                   | 1        | 1.49%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                              | 1        | 1.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s                    | 1        | 1.49%   |
| Samsung RAM M471B5173BH0-YK0 4GB DIMM DDR3 1600MT/s                    | 1        | 1.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                  | 1        | 1.49%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                    | 1        | 1.49%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s                    | 1        | 1.49%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s                    | 1        | 1.49%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 1.49%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s                   | 1        | 1.49%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB DIMM DDR3 1867MT/s                    | 1        | 1.49%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3                            | 1        | 1.49%   |
| Micron RAM 16ATF2G64AZ-2G6J1 16GB DIMM DDR4 2667MT/s                   | 1        | 1.49%   |
| Kingston RAM 99U5458-005.A00LF 4GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s                  | 1        | 1.49%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Kingston RAM 9905471-006.A01LF 4GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Kingston RAM 9905458-009.A00LF 2GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Kingston RAM 9905403-011.A02LF 2GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                         | 1        | 1.49%   |
| HPE RAM 879527-091 16GB DIMM DDR4 2666MT/s                             | 1        | 1.49%   |
| HP RAM 862690-091 16GB DIMM DDR4 2400MT/s                              | 1        | 1.49%   |
| HP RAM 797258-081 8GB DIMM DDR4 2133MT/s                               | 1        | 1.49%   |
| G.Skill RAM F4-3600C18-16GVK 16GB DIMM DDR4 2133MT/s                   | 1        | 1.49%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 2133MT/s                 | 1        | 1.49%   |
| Elpida RAM EBJ21UE8BDF0-DJ-F 2GB DIMM DDR3 1333MT/s                    | 1        | 1.49%   |
| Crucial RAM CT16G4DFD8213.C16FDD 16GB DIMM DDR4 2133MT/s               | 1        | 1.49%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s                | 1        | 1.49%   |
| Crucial RAM BLS8G4D240FSA.16FARG 8192MB DIMM DDR4 2400MT/s             | 1        | 1.49%   |
| Crucial RAM BLS8G3D1609DS 8192MB DIMM DDR3 800MT/s                     | 1        | 1.49%   |
| Crucial RAM BLS4G3D1609DS 4GB DIMM DDR3 800MT/s                        | 1        | 1.49%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s                         | 1        | 1.49%   |
| Corsair RAM CMX16GX3M2A1600C11 8GB DIMM DDR3 1333MT/s                  | 1        | 1.49%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1333MT/s                    | 1        | 1.49%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM 1333MT/s                      | 1        | 1.49%   |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s                   | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2Z2666C16 8GB DIMM DDR4 2666MT/s                  | 1        | 1.49%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                  | 1        | 1.49%   |
| Corsair RAM CMD16GX3M2A2400C10 8GB DIMM DDR3 1600MT/s                  | 1        | 1.49%   |
| Corsair RAM 434D3258313032342D363430304334202020 1GB DIMM DDR2 667MT/s | 1        | 1.49%   |
| Apacer RAM 78.B2GC9.AF1 4GB SODIMM DDR3 1333MT/s                       | 1        | 1.49%   |
| Unknown                                                                | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 35       | 63.64%  |
| DDR4    | 15       | 27.27%  |
| DDR2    | 3        | 5.45%   |
| SDRAM   | 1        | 1.82%   |
| Unknown | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 43       | 76.79%  |
| SODIMM | 13       | 23.21%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 24       | 39.34%  |
| 8192  | 20       | 32.79%  |
| 16384 | 8        | 13.11%  |
| 2048  | 6        | 9.84%   |
| 1024  | 3        | 4.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 18       | 31.03%  |
| 1333    | 16       | 27.59%  |
| 2133    | 7        | 12.07%  |
| 2667    | 4        | 6.9%    |
| 800     | 3        | 5.17%   |
| 2666    | 2        | 3.45%   |
| 2400    | 2        | 3.45%   |
| 667     | 2        | 3.45%   |
| 3200    | 1        | 1.72%   |
| 1867    | 1        | 1.72%   |
| 1332    | 1        | 1.72%   |
| Unknown | 1        | 1.72%   |

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
| 1     | 33       | 52.38%  |
| 0     | 22       | 34.92%  |
| 2     | 6        | 9.52%   |
| 5     | 1        | 1.59%   |
| 3     | 1        | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 38       | 82.61%  |
| Net/wireless             | 4        | 8.7%    |
| Storage/ata              | 1        | 2.17%   |
| Net/ethernet             | 1        | 2.17%   |
| Graphics card            | 1        | 2.17%   |
| Firewire controller      | 1        | 2.17%   |

