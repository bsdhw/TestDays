BSD in Sweden - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 158

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | Z87M-D3H                    | Desktop     | [59ae6fc283](https://bsd-hardware.info/?probe=59ae6fc283) | Jul 26, 2022 |
| HP            | ProBook 4730s               | Notebook    | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Supermicro    | X11SSV-M4                   | Desktop     | [444d9ed75e](https://bsd-hardware.info/?probe=444d9ed75e) | Jul 04, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ea22a644f6](https://bsd-hardware.info/?probe=ea22a644f6) | Jul 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [dfd321896a](https://bsd-hardware.info/?probe=dfd321896a) | Jun 14, 2022 |
| PC Engines    | APU                         | Desktop     | [f41e59d78b](https://bsd-hardware.info/?probe=f41e59d78b) | Jun 11, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [d3ba57cf29](https://bsd-hardware.info/?probe=d3ba57cf29) | Jun 01, 2022 |
| MSI           | MS-7369                     | Desktop     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Dell          | 05Y15N A06                  | Server      | [047ecc3a64](https://bsd-hardware.info/?probe=047ecc3a64) | May 13, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0d11258d3a](https://bsd-hardware.info/?probe=0d11258d3a) | Apr 22, 2022 |
| HP            | 8103 A01                    | Mini pc     | [b3d4d3c2db](https://bsd-hardware.info/?probe=b3d4d3c2db) | Apr 16, 2022 |
| Shuttle       | SH570                       | Desktop     | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [2e4a7843ab](https://bsd-hardware.info/?probe=2e4a7843ab) | Apr 14, 2022 |
| ASUSTek       | UX305UA                     | Notebook    | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Dell          | 0GFKVD A00                  | Server      | [2b14dd2a23](https://bsd-hardware.info/?probe=2b14dd2a23) | Mar 29, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04e77555a2](https://bsd-hardware.info/?probe=04e77555a2) | Mar 24, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [23055a27d9](https://bsd-hardware.info/?probe=23055a27d9) | Mar 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [8faec8e7ed](https://bsd-hardware.info/?probe=8faec8e7ed) | Mar 10, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [a2c59d02ee](https://bsd-hardware.info/?probe=a2c59d02ee) | Mar 08, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [099edf57ae](https://bsd-hardware.info/?probe=099edf57ae) | Mar 08, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [8016115ff1](https://bsd-hardware.info/?probe=8016115ff1) | Feb 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5d39002367](https://bsd-hardware.info/?probe=5d39002367) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| MSI           | MS-7C56                     | Desktop     | [962ac1c7b0](https://bsd-hardware.info/?probe=962ac1c7b0) | Jan 20, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [26ccd8e3c5](https://bsd-hardware.info/?probe=26ccd8e3c5) | Jan 16, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [e15d67e8db](https://bsd-hardware.info/?probe=e15d67e8db) | Jan 08, 2022 |
| ASRock        | E3C226D2I                   | Desktop     | [a31265ae13](https://bsd-hardware.info/?probe=a31265ae13) | Jan 07, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [27960088a3](https://bsd-hardware.info/?probe=27960088a3) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [1684618e22](https://bsd-hardware.info/?probe=1684618e22) | Jan 01, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [8eaea61913](https://bsd-hardware.info/?probe=8eaea61913) | Dec 29, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [fda420b944](https://bsd-hardware.info/?probe=fda420b944) | Dec 20, 2021 |
| HPE           | ProLiant DL380 Gen10        | Server      | [d1e6144816](https://bsd-hardware.info/?probe=d1e6144816) | Dec 20, 2021 |
| Intel         | DH61AG AAG81491-600         | Desktop     | [fd9659a9fe](https://bsd-hardware.info/?probe=fd9659a9fe) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | Desktop     | [34633c2ca8](https://bsd-hardware.info/?probe=34633c2ca8) | Dec 02, 2021 |
| MSI           | MS-7C56                     | Desktop     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| Dell          | 0N28XX A02                  | Server      | [b640c5a644](https://bsd-hardware.info/?probe=b640c5a644) | Nov 10, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google        | Grunt                       | Notebook    | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google        | Grunt                       | Notebook    | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Google        | Grunt                       | Notebook    | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [a6b7ceeada](https://bsd-hardware.info/?probe=a6b7ceeada) | Oct 20, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [4fdd90135a](https://bsd-hardware.info/?probe=4fdd90135a) | Oct 20, 2021 |
| Google        | Grunt                       | Notebook    | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google        | Grunt                       | Notebook    | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| Google        | Grunt                       | Notebook    | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer          | Aspire A315-56              | Notebook    | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [8cb8c4dbf4](https://bsd-hardware.info/?probe=8cb8c4dbf4) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1ef37663db](https://bsd-hardware.info/?probe=1ef37663db) | Sep 01, 2021 |
| Dell          | 0M877N A01                  | Server      | [1585126252](https://bsd-hardware.info/?probe=1585126252) | Aug 18, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [4737978dbf](https://bsd-hardware.info/?probe=4737978dbf) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [04d9692802](https://bsd-hardware.info/?probe=04d9692802) | Aug 09, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24df2da075](https://bsd-hardware.info/?probe=24df2da075) | Aug 08, 2021 |
| PC Engines    | apu4                        | Desktop     | [815567b75c](https://bsd-hardware.info/?probe=815567b75c) | Aug 02, 2021 |
| PC Engines    | apu4                        | Desktop     | [77fa195d5e](https://bsd-hardware.info/?probe=77fa195d5e) | Aug 02, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | Notebook    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c577b93feb](https://bsd-hardware.info/?probe=c577b93feb) | Jul 24, 2021 |
| Lenovo        | ThinkPad T400 2767WSB       | Notebook    | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [52e8a39fb1](https://bsd-hardware.info/?probe=52e8a39fb1) | Jul 19, 2021 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [452a8558c0](https://bsd-hardware.info/?probe=452a8558c0) | Jul 09, 2021 |
| Dell          | 05XGC8 A01                  | Desktop     | [b9841b1272](https://bsd-hardware.info/?probe=b9841b1272) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [935263c5a0](https://bsd-hardware.info/?probe=935263c5a0) | Jul 03, 2021 |
| HP            | 82A1                        | Desktop     | [dba57fb77f](https://bsd-hardware.info/?probe=dba57fb77f) | Jun 30, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [18e34c37cd](https://bsd-hardware.info/?probe=18e34c37cd) | Jun 28, 2021 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3d717eec8f](https://bsd-hardware.info/?probe=3d717eec8f) | Jun 25, 2021 |
| Dell          | 0P03DX A03                  | Desktop     | [b2f0c90d79](https://bsd-hardware.info/?probe=b2f0c90d79) | Jun 24, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [1b8d66e5f0](https://bsd-hardware.info/?probe=1b8d66e5f0) | Jun 22, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [5091db2ace](https://bsd-hardware.info/?probe=5091db2ace) | Jun 16, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [c6d7626b29](https://bsd-hardware.info/?probe=c6d7626b29) | Jun 12, 2021 |
| ASRock        | X99 WS                      | Desktop     | [201a7417a5](https://bsd-hardware.info/?probe=201a7417a5) | Jun 11, 2021 |
| Dell          | 0NR282 A00                  | Server      | [f3854ba6e8](https://bsd-hardware.info/?probe=f3854ba6e8) | Jun 07, 2021 |
| Sony          | SVP1322M1EBI                | Notebook    | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| PC Engines    | APU2                        | Desktop     | [2070f50252](https://bsd-hardware.info/?probe=2070f50252) | May 26, 2021 |
| ASUSTek       | Z87-DELUXE/DUAL             | Desktop     | [69a811cae5](https://bsd-hardware.info/?probe=69a811cae5) | May 25, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [586a4db247](https://bsd-hardware.info/?probe=586a4db247) | May 20, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [eb0c02a451](https://bsd-hardware.info/?probe=eb0c02a451) | May 19, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [62b9ea2794](https://bsd-hardware.info/?probe=62b9ea2794) | May 14, 2021 |
| Dell          | Latitude 5500               | Notebook    | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| ASRock        | X99 WS                      | Desktop     | [eb20367455](https://bsd-hardware.info/?probe=eb20367455) | May 05, 2021 |
| Dell          | 0NR282 A00                  | Server      | [09082703f8](https://bsd-hardware.info/?probe=09082703f8) | Apr 29, 2021 |
| Dell          | 03X6X0 A01                  | Server      | [9f13074b78](https://bsd-hardware.info/?probe=9f13074b78) | Apr 24, 2021 |
| ASUSTek       | All Series                  | Desktop     | [ef6afe88d7](https://bsd-hardware.info/?probe=ef6afe88d7) | Apr 17, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [ad564817c9](https://bsd-hardware.info/?probe=ad564817c9) | Apr 11, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [0712c3048c](https://bsd-hardware.info/?probe=0712c3048c) | Apr 11, 2021 |
| Dell          | 09T7VV A05                  | Server      | [668c05619b](https://bsd-hardware.info/?probe=668c05619b) | Apr 09, 2021 |
| Dell          | 09T7VV A05                  | Server      | [917ab2c4e6](https://bsd-hardware.info/?probe=917ab2c4e6) | Apr 06, 2021 |
| Shuttle       | FH170                       | Desktop     | [d36fccf7b7](https://bsd-hardware.info/?probe=d36fccf7b7) | Apr 01, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [052c1899c8](https://bsd-hardware.info/?probe=052c1899c8) | Mar 29, 2021 |
| Dell          | 0F0XJ6 A02                  | Server      | [806c6f796e](https://bsd-hardware.info/?probe=806c6f796e) | Mar 29, 2021 |
| MSI           | IONA                        | Desktop     | [5f857882ff](https://bsd-hardware.info/?probe=5f857882ff) | Mar 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [93ef7a4b6e](https://bsd-hardware.info/?probe=93ef7a4b6e) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [c5bc64e4e9](https://bsd-hardware.info/?probe=c5bc64e4e9) | Mar 22, 2021 |
| ASUSTek       | All Series                  | Desktop     | [700ff7d378](https://bsd-hardware.info/?probe=700ff7d378) | Mar 22, 2021 |
| HP            | 8054                        | Desktop     | [1db522699a](https://bsd-hardware.info/?probe=1db522699a) | Mar 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [ddc66bc2fb](https://bsd-hardware.info/?probe=ddc66bc2fb) | Mar 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a5833ca2c9](https://bsd-hardware.info/?probe=a5833ca2c9) | Mar 18, 2021 |
| HP            | 8053                        | Desktop     | [b7ebdfe456](https://bsd-hardware.info/?probe=b7ebdfe456) | Mar 17, 2021 |
| ASUSTek       | P8H67-M                     | Desktop     | [e95d6c6972](https://bsd-hardware.info/?probe=e95d6c6972) | Mar 17, 2021 |
| Lenovo        | ThinkPad X395 20NL001SMX    | Notebook    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [ebd85cee04](https://bsd-hardware.info/?probe=ebd85cee04) | Mar 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [93c9f14bf0](https://bsd-hardware.info/?probe=93c9f14bf0) | Mar 12, 2021 |
| Dell          | 0XCR8D A02                  | Desktop     | [af5d6a85ef](https://bsd-hardware.info/?probe=af5d6a85ef) | Mar 09, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [a9f921e29b](https://bsd-hardware.info/?probe=a9f921e29b) | Mar 03, 2021 |
| Intel         | DQ67SW AAG12527-306         | Desktop     | [a4fb7ae326](https://bsd-hardware.info/?probe=a4fb7ae326) | Mar 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00dc0301a](https://bsd-hardware.info/?probe=b00dc0301a) | Feb 27, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [da62664934](https://bsd-hardware.info/?probe=da62664934) | Feb 23, 2021 |
| Dell          | Latitude E7240              | Notebook    | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [5ca10a4860](https://bsd-hardware.info/?probe=5ca10a4860) | Feb 14, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [263a74d1ce](https://bsd-hardware.info/?probe=263a74d1ce) | Feb 12, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba       | Satellite L450              | Notebook    | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [508b3afc1c](https://bsd-hardware.info/?probe=508b3afc1c) | Feb 09, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [8b9f162f70](https://bsd-hardware.info/?probe=8b9f162f70) | Feb 09, 2021 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [dfb0240726](https://bsd-hardware.info/?probe=dfb0240726) | Feb 05, 2021 |
| PC Engines    | APU2                        | Desktop     | [8983ab6689](https://bsd-hardware.info/?probe=8983ab6689) | Feb 03, 2021 |
| HP            | 1905                        | Desktop     | [72ab5653d3](https://bsd-hardware.info/?probe=72ab5653d3) | Feb 03, 2021 |
| Microsoft     | Surface Go 2                | Tablet      | [69c8123ec6](https://bsd-hardware.info/?probe=69c8123ec6) | Feb 01, 2021 |
| HP            | 8103 A01                    | Mini pc     | [da8a373d43](https://bsd-hardware.info/?probe=da8a373d43) | Jan 30, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [137ff14192](https://bsd-hardware.info/?probe=137ff14192) | Jan 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [920259bf95](https://bsd-hardware.info/?probe=920259bf95) | Jan 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [55c7d22c4d](https://bsd-hardware.info/?probe=55c7d22c4d) | Jan 28, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [c2bb148e8a](https://bsd-hardware.info/?probe=c2bb148e8a) | Jan 28, 2021 |
| Dell          | 06G98X A02                  | Server      | [b062e0f4e4](https://bsd-hardware.info/?probe=b062e0f4e4) | Jan 28, 2021 |
| Dell          | 0WCJNT A06                  | Server      | [4710d6000d](https://bsd-hardware.info/?probe=4710d6000d) | Jan 28, 2021 |
| ASUSTek       | All Series                  | Desktop     | [7ebe6eee38](https://bsd-hardware.info/?probe=7ebe6eee38) | Jan 25, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [e2fbc5f326](https://bsd-hardware.info/?probe=e2fbc5f326) | Jan 21, 2021 |
| ADI           | MinnowBoard Turbot          | Desktop     | [0b8e4d0630](https://bsd-hardware.info/?probe=0b8e4d0630) | Jan 21, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [bd3877826c](https://bsd-hardware.info/?probe=bd3877826c) | Jan 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3a9d5d1a1d](https://bsd-hardware.info/?probe=3a9d5d1a1d) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [ecf35d22c4](https://bsd-hardware.info/?probe=ecf35d22c4) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3680FAG       | Notebook    | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| PC Engines    | APU2                        | Desktop     | [2e6256a0ab](https://bsd-hardware.info/?probe=2e6256a0ab) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [0d6c7132ff](https://bsd-hardware.info/?probe=0d6c7132ff) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [65de6946d3](https://bsd-hardware.info/?probe=65de6946d3) | Nov 23, 2020 |
| PC Engines    | APU2                        | Desktop     | [b4f5d7d344](https://bsd-hardware.info/?probe=b4f5d7d344) | Nov 16, 2020 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [ecaec68cdb](https://bsd-hardware.info/?probe=ecaec68cdb) | Oct 27, 2020 |
| Intel         | NUC5CPYB                    | Mini pc     | [1ec5c12f0b](https://bsd-hardware.info/?probe=1ec5c12f0b) | Oct 27, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [0d2e0f44c1](https://bsd-hardware.info/?probe=0d2e0f44c1) | Aug 06, 2020 |
| Lenovo        | ThinkPad L560 20F10032MS    | Notebook    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6245f1e175](https://bsd-hardware.info/?probe=6245f1e175) | Aug 06, 2020 |
| Unknown       | Unknown                     | Desktop     | [4e3b87cc6c](https://bsd-hardware.info/?probe=4e3b87cc6c) | Jun 01, 2020 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 21.1        | 11        | 8.66%   |
| OPNsense 21.7.7      | 6         | 4.72%   |
| OPNsense 21.1.3      | 6         | 4.72%   |
| OpenBSD 6.8          | 6         | 4.72%   |
| OPNsense 21.1.5      | 5         | 3.94%   |
| OPNsense 21.1.2      | 5         | 3.94%   |
| OpenBSD 7.0          | 5         | 3.94%   |
| helloSystem 0.5.0    | 5         | 3.94%   |
| OPNsense 21.1.8      | 4         | 3.15%   |
| OPNsense 22.1.8      | 3         | 2.36%   |
| OPNsense 21.7.3      | 3         | 2.36%   |
| OPNsense 21.7.1      | 3         | 2.36%   |
| OPNsense 20.7.8      | 3         | 2.36%   |
| OpenBSD 6.9          | 3         | 2.36%   |
| FreeBSD 13.0-p7      | 3         | 2.36%   |
| FreeBSD 12.1-p8      | 3         | 2.36%   |
| OPNsense 22.1.9      | 2         | 1.57%   |
| OPNsense 22.1.6      | 2         | 1.57%   |
| OPNsense 22.1.3      | 2         | 1.57%   |
| OPNsense 22.1.1      | 2         | 1.57%   |
| OPNsense 21.7.6      | 2         | 1.57%   |
| OPNsense 21.7        | 2         | 1.57%   |
| OPNsense 21.1.7      | 2         | 1.57%   |
| OPNsense 21.1.6      | 2         | 1.57%   |
| OpenBSD 6.7          | 2         | 1.57%   |
| helloSystem 0.7.0    | 2         | 1.57%   |
| helloSystem 0.4.0    | 2         | 1.57%   |
| FreeBSD 14.0-CURRENT | 2         | 1.57%   |
| FreeBSD 12.2-p4      | 2         | 1.57%   |
| FreeBSD 12.2-p2      | 2         | 1.57%   |
| pfSense 2.5.0        | 1         | 0.79%   |
| OPNsense 22.1.7      | 1         | 0.79%   |
| OPNsense 22.1.5      | 1         | 0.79%   |
| OPNsense 22.1.4      | 1         | 0.79%   |
| OPNsense 22.1.2      | 1         | 0.79%   |
| OPNsense 22.1.10     | 1         | 0.79%   |
| OPNsense 22.1        | 1         | 0.79%   |
| OPNsense 21.7.4      | 1         | 0.79%   |
| OPNsense 21.1.4      | 1         | 0.79%   |
| OPNsense 21.1.1      | 1         | 0.79%   |
| GhostBSD 21.08.27    | 1         | 0.79%   |
| GhostBSD 20.04.02    | 1         | 0.79%   |
| GhostBSD 19.12       | 1         | 0.79%   |
| FuryBSD 12.2-p3      | 1         | 0.79%   |
| FreeBSD 13.1-RC2     | 1         | 0.79%   |
| FreeBSD 13.0-STABLE  | 1         | 0.79%   |
| FreeBSD 13.0-p5      | 1         | 0.79%   |
| FreeBSD 13.0-p4      | 1         | 0.79%   |
| FreeBSD 13.0-p2      | 1         | 0.79%   |
| FreeBSD 13.0-p10     | 1         | 0.79%   |
| FreeBSD 13.0         | 1         | 0.79%   |
| FreeBSD 12.3-p5      | 1         | 0.79%   |
| FreeBSD 12.1-p7      | 1         | 0.79%   |
| FreeBSD 12.1-p10     | 1         | 0.79%   |
| FreeBSD 11.4-p6      | 1         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 63        | 55.26%  |
| FreeBSD     | 22        | 19.3%   |
| OpenBSD     | 15        | 13.16%  |
| helloSystem | 9         | 7.89%   |
| GhostBSD    | 3         | 2.63%   |
| pfSense     | 1         | 0.88%   |
| FuryBSD     | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 113       | 99.12%  |
| octeon | 1         | 0.88%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 76        | 65.52%  |
| fvwm         | 12        | 10.34%  |
| KDE5         | 9         | 7.76%   |
| helloDesktop | 9         | 7.76%   |
| MATE         | 3         | 2.59%   |
| i3           | 2         | 1.72%   |
| xfwm         | 1         | 0.86%   |
| XFCE         | 1         | 0.86%   |
| TWM          | 1         | 0.86%   |
| Mutter       | 1         | 0.86%   |
| AwesomeWM    | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 77        | 67.54%  |
| X11     | 37        | 32.46%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 88        | 75.21%  |
| SLiM    | 10        | 8.55%   |
| SDDM    | 8         | 6.84%   |
| LightDM | 5         | 4.27%   |
| GDM     | 4         | 3.42%   |
| XDM     | 2         | 1.71%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 78        | 67.24%  |
| en_US          | 20        | 17.24%  |
| C              | 13        | 11.21%  |
| sv_SE          | 3         | 2.59%   |
| sv_SE.US-ASCII | 1         | 0.86%   |
| en_CA          | 1         | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 94        | 81.03%  |
| BIOS | 22        | 18.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 62        | 54.39%  |
| Zfs  | 37        | 32.46%  |
| Ffs  | 15        | 13.16%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 101       | 86.32%  |
| MBR  | 16        | 13.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 18        | 15.79%  |
| Hewlett-Packard            | 14        | 12.28%  |
| Lenovo                     | 13        | 11.4%   |
| ASUSTek Computer           | 13        | 11.4%   |
| PC Engines                 | 7         | 6.14%   |
| Gigabyte Technology        | 6         | 5.26%   |
| Unknown                    | 6         | 5.26%   |
| Intel                      | 5         | 4.39%   |
| MSI                        | 4         | 3.51%   |
| AMI                        | 4         | 3.51%   |
| Microsoft                  | 3         | 2.63%   |
| Supermicro                 | 2         | 1.75%   |
| Shuttle                    | 2         | 1.75%   |
| HPE                        | 2         | 1.75%   |
| Fujitsu                    | 2         | 1.75%   |
| ASRock                     | 2         | 1.75%   |
| Wistron                    | 1         | 0.88%   |
| Toshiba                    | 1         | 0.88%   |
| Sony                       | 1         | 0.88%   |
| ShenZhen MinWin Technology | 1         | 0.88%   |
| Protectli                  | 1         | 0.88%   |
| Google                     | 1         | 0.88%   |
| Fujitsu Siemens            | 1         | 0.88%   |
| Deciso                     | 1         | 0.88%   |
| AOpen                      | 1         | 0.88%   |
| ADI                        | 1         | 0.88%   |
| Acer                       | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 5.26%   |
| PC Engines APU2                     | 4         | 3.51%   |
| ASUS All Series                     | 4         | 3.51%   |
| HP t730 Thin Client                 | 3         | 2.63%   |
| AMI Aptio CRB                       | 3         | 2.63%   |
| PC Engines apu4                     | 2         | 1.75%   |
| Microsoft Surface Pro 7             | 2         | 1.75%   |
| Dell PowerEdge R210 II              | 2         | 1.75%   |
| Dell OptiPlex 9020                  | 2         | 1.75%   |
| Wistron ProLiant ML110 G6           | 1         | 0.88%   |
| Toshiba Satellite L450              | 1         | 0.88%   |
| Supermicro SYS-1019S-MP             | 1         | 0.88%   |
| Supermicro Super Server             | 1         | 0.88%   |
| Sony SVP1322M1EBI                   | 1         | 0.88%   |
| Shuttle SH570                       | 1         | 0.88%   |
| Shuttle DH170                       | 1         | 0.88%   |
| ShenZhen MinWin MW-NANO-APL-4L      | 1         | 0.88%   |
| Protectli FW4B                      | 1         | 0.88%   |
| PC Engines APU                      | 1         | 0.88%   |
| MSI WC776AA-UUW HPE-110sc           | 1         | 0.88%   |
| MSI MS-7C56                         | 1         | 0.88%   |
| MSI MS-7918                         | 1         | 0.88%   |
| MSI MS-7369                         | 1         | 0.88%   |
| Microsoft Surface Go 2              | 1         | 0.88%   |
| Lenovo V130-15IGM 81HL              | 1         | 0.88%   |
| Lenovo ThinkPad X395 20NL001SMX     | 1         | 0.88%   |
| Lenovo ThinkPad X250 20CLS4JH00     | 1         | 0.88%   |
| Lenovo ThinkPad X201 3680FAG        | 1         | 0.88%   |
| Lenovo ThinkPad W520 4284GN2        | 1         | 0.88%   |
| Lenovo ThinkPad T460s 20FAS4KH02    | 1         | 0.88%   |
| Lenovo ThinkPad T420 4236MBG        | 1         | 0.88%   |
| Lenovo ThinkPad T400 2767WSB        | 1         | 0.88%   |
| Lenovo ThinkPad L560 20F10032MS     | 1         | 0.88%   |
| Lenovo ThinkCentre M92p 2988B1G     | 1         | 0.88%   |
| Lenovo ThinkCentre Edge72 3493AZG   | 1         | 0.88%   |
| Lenovo ThinkCentre E73 10AS002QMX   | 1         | 0.88%   |
| Lenovo Legion Y530-15ICH 81FV       | 1         | 0.88%   |
| Intel Q3XXG4-P V1.0                 | 1         | 0.88%   |
| Intel NUC5CPYB                      | 1         | 0.88%   |
| Intel DQ67SW AAG12527-306           | 1         | 0.88%   |
| Intel DH61AG AAG81491-600           | 1         | 0.88%   |
| Intel CRESCENTBAY                   | 1         | 0.88%   |
| HPE ProLiant MicroServer Gen10 Plus | 1         | 0.88%   |
| HPE ProLiant DL380 Gen10            | 1         | 0.88%   |
| HP Z230 Tower Workstation           | 1         | 0.88%   |
| HP ProLiant ML30 Gen9               | 1         | 0.88%   |
| HP ProLiant DL380 Gen9              | 1         | 0.88%   |
| HP ProLiant DL360p Gen8             | 1         | 0.88%   |
| HP ProLiant DL360 G5                | 1         | 0.88%   |
| HP ProDesk 400 G4 MT                | 1         | 0.88%   |
| HP ProBook 4730s                    | 1         | 0.88%   |
| HP Laptop 15-dw0xxx                 | 1         | 0.88%   |
| HP EliteDesk 800 G2 TWR             | 1         | 0.88%   |
| HP EliteDesk 800 G2 SFF             | 1         | 0.88%   |
| HP EliteBook 8440p                  | 1         | 0.88%   |
| Google Grunt                        | 1         | 0.88%   |
| Gigabyte Z87M-D3H                   | 1         | 0.88%   |
| Gigabyte Z68X-UD7-B3                | 1         | 0.88%   |
| Gigabyte Z170X-UD5 TH               | 1         | 0.88%   |
| Gigabyte B550I AORUS PRO AX         | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell PowerEdge                 | 10        | 8.77%   |
| Lenovo ThinkPad                | 8         | 7.02%   |
| Unknown                        | 6         | 5.26%   |
| Dell OptiPlex                  | 5         | 4.39%   |
| PC Engines APU2                | 4         | 3.51%   |
| HP ProLiant                    | 4         | 3.51%   |
| ASUS All                       | 4         | 3.51%   |
| Microsoft Surface              | 3         | 2.63%   |
| Lenovo ThinkCentre             | 3         | 2.63%   |
| HP t730                        | 3         | 2.63%   |
| Dell Latitude                  | 3         | 2.63%   |
| AMI Aptio                      | 3         | 2.63%   |
| PC Engines apu4                | 2         | 1.75%   |
| HPE ProLiant                   | 2         | 1.75%   |
| HP EliteDesk                   | 2         | 1.75%   |
| Wistron ProLiant               | 1         | 0.88%   |
| Toshiba Satellite              | 1         | 0.88%   |
| Supermicro SYS-1019S-MP        | 1         | 0.88%   |
| Supermicro Super               | 1         | 0.88%   |
| Sony SVP1322M1EBI              | 1         | 0.88%   |
| Shuttle SH570                  | 1         | 0.88%   |
| Shuttle DH170                  | 1         | 0.88%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.88%   |
| Protectli FW4B                 | 1         | 0.88%   |
| PC Engines APU                 | 1         | 0.88%   |
| MSI WC776AA-UUW                | 1         | 0.88%   |
| MSI MS-7C56                    | 1         | 0.88%   |
| MSI MS-7918                    | 1         | 0.88%   |
| MSI MS-7369                    | 1         | 0.88%   |
| Lenovo V130-15IGM              | 1         | 0.88%   |
| Lenovo Legion                  | 1         | 0.88%   |
| Intel Q3XXG4-P                 | 1         | 0.88%   |
| Intel NUC5CPYB                 | 1         | 0.88%   |
| Intel DQ67SW                   | 1         | 0.88%   |
| Intel DH61AG                   | 1         | 0.88%   |
| Intel CRESCENTBAY              | 1         | 0.88%   |
| HP Z230                        | 1         | 0.88%   |
| HP ProDesk                     | 1         | 0.88%   |
| HP ProBook                     | 1         | 0.88%   |
| HP Laptop                      | 1         | 0.88%   |
| HP EliteBook                   | 1         | 0.88%   |
| Google Grunt                   | 1         | 0.88%   |
| Gigabyte Z87M-D3H              | 1         | 0.88%   |
| Gigabyte Z68X-UD7-B3           | 1         | 0.88%   |
| Gigabyte Z170X-UD5             | 1         | 0.88%   |
| Gigabyte B550I                 | 1         | 0.88%   |
| Gigabyte AB350M-Gaming         | 1         | 0.88%   |
| Gigabyte 970A-DS3P             | 1         | 0.88%   |
| Fujitsu Siemens ESPRIMO        | 1         | 0.88%   |
| Fujitsu FUTRO                  | 1         | 0.88%   |
| Fujitsu ESPRIMO                | 1         | 0.88%   |
| Deciso Netboard                | 1         | 0.88%   |
| ASUS UX305UA                   | 1         | 0.88%   |
| ASUS S551LN                    | 1         | 0.88%   |
| ASUS ROG                       | 1         | 0.88%   |
| ASUS Rampage                   | 1         | 0.88%   |
| ASUS P8H77-I                   | 1         | 0.88%   |
| ASUS P8H67-M                   | 1         | 0.88%   |
| ASUS P5Q                       | 1         | 0.88%   |
| ASUS M32CD                     | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 15        | 13.16%  |
| 2018    | 13        | 11.4%   |
| 2016    | 13        | 11.4%   |
| 2014    | 11        | 9.65%   |
| 2017    | 10        | 8.77%   |
| 2015    | 9         | 7.89%   |
| 2010    | 9         | 7.89%   |
| 2021    | 8         | 7.02%   |
| 2019    | 8         | 7.02%   |
| 2012    | 5         | 4.39%   |
| 2009    | 5         | 4.39%   |
| 2013    | 4         | 3.51%   |
| 2011    | 2         | 1.75%   |
| 2007    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 66        | 57.89%  |
| Notebook | 23        | 20.18%  |
| Server   | 15        | 13.16%  |
| Mini pc  | 7         | 6.14%   |
| Tablet   | 3         | 2.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 91.23%  |
| Yes  | 10        | 8.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 36        | 31.03%  |
| 4.01-8.0        | 32        | 27.59%  |
| 16.01-24.0      | 19        | 16.38%  |
| 32.01-64.0      | 13        | 11.21%  |
| 64.01-256.0     | 5         | 4.31%   |
| More than 256.0 | 3         | 2.59%   |
| 24.01-32.0      | 3         | 2.59%   |
| 3.01-4.0        | 2         | 1.72%   |
| 2.01-3.0        | 2         | 1.72%   |
| 1.01-2.0        | 1         | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 59        | 50.86%  |
| 0.51-1.0    | 31        | 26.72%  |
| 1.01-2.0    | 14        | 12.07%  |
| 4.01-8.0    | 4         | 3.45%   |
| 2.01-3.0    | 3         | 2.59%   |
| 24.01-32.0  | 2         | 1.72%   |
| 64.01-256.0 | 2         | 1.72%   |
| 3.01-4.0    | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 66.95%  |
| 2      | 12        | 10.17%  |
| 0      | 8         | 6.78%   |
| 3      | 6         | 5.08%   |
| 4      | 3         | 2.54%   |
| 11     | 2         | 1.69%   |
| 6      | 2         | 1.69%   |
| 18     | 1         | 0.85%   |
| 12     | 1         | 0.85%   |
| 10     | 1         | 0.85%   |
| 9      | 1         | 0.85%   |
| 8      | 1         | 0.85%   |
| 5      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 77.39%  |
| Yes       | 26        | 22.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 93.86%  |
| No        | 7         | 6.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 67.83%  |
| Yes       | 37        | 32.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 76.52%  |
| Yes       | 27        | 23.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 114       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Stockholm        | 15        | 11.9%   |
| Malmo            | 11        | 8.73%   |
| LinkГ¶ping     | 5         | 3.97%   |
| VÃ¤sterÃ¥s   | 4         | 3.17%   |
| UmeГҐ          | 4         | 3.17%   |
| Bromma           | 4         | 3.17%   |
| Taby             | 3         | 2.38%   |
| Sollentuna       | 3         | 2.38%   |
| JГ¶nkГ¶ping  | 3         | 2.38%   |
| Gothenburg       | 3         | 2.38%   |
| Umeå            | 2         | 1.59%   |
| Tyreso Strand    | 2         | 1.59%   |
| Tumba            | 2         | 1.59%   |
| Solleftea        | 2         | 1.59%   |
| Lund             | 2         | 1.59%   |
| Kungsbacka       | 2         | 1.59%   |
| Henan            | 2         | 1.59%   |
| Helsingborg      | 2         | 1.59%   |
| Bandhagen        | 2         | 1.59%   |
| Г…hus         | 1         | 0.79%   |
| Г„lvГ¤ngen  | 1         | 0.79%   |
| Västerås       | 1         | 0.79%   |
| Uppsala          | 1         | 0.79%   |
| Upplands Vasby   | 1         | 0.79%   |
| UmeÃ¥          | 1         | 0.79%   |
| Trosa            | 1         | 0.79%   |
| Trelleborg       | 1         | 0.79%   |
| Trangsund        | 1         | 0.79%   |
| Torsby           | 1         | 0.79%   |
| SГ¶dertГ¤lje | 1         | 0.79%   |
| Sundsvall        | 1         | 0.79%   |
| Sundbyberg       | 1         | 0.79%   |
| Stroemstad       | 1         | 0.79%   |
| Staffanstorp     | 1         | 0.79%   |
| Solna            | 1         | 0.79%   |
| Soeraker         | 1         | 0.79%   |
| SkГ¶vde        | 1         | 0.79%   |
| SkellefteÃ¥    | 1         | 0.79%   |
| SkÃ¶vde        | 1         | 0.79%   |
| Skaellinge       | 1         | 0.79%   |
| Saltsjoe-Boo     | 1         | 0.79%   |
| Piteå           | 1         | 0.79%   |
| Östersund       | 1         | 0.79%   |
| OEvertornea      | 1         | 0.79%   |
| OEverlida        | 1         | 0.79%   |
| NykГ¶ping      | 1         | 0.79%   |
| NorrkГ¶ping    | 1         | 0.79%   |
| Norrköping      | 1         | 0.79%   |
| Norberg          | 1         | 0.79%   |
| Morgongava       | 1         | 0.79%   |
| Matfors          | 1         | 0.79%   |
| LuleÃ¥         | 1         | 0.79%   |
| Lidkoeping       | 1         | 0.79%   |
| Landskrona       | 1         | 0.79%   |
| Kristianstad     | 1         | 0.79%   |
| Klagshamn        | 1         | 0.79%   |
| Kista            | 1         | 0.79%   |
| Karlskrona       | 1         | 0.79%   |
| Karlshamn        | 1         | 0.79%   |
| Joenaker         | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 35     | 17.61%  |
| Seagate             | 18        | 42     | 12.68%  |
| WDC                 | 14        | 18     | 9.86%   |
| Kingston            | 11        | 13     | 7.75%   |
| Intel               | 11        | 25     | 7.75%   |
| Hoodisk             | 10        | 12     | 7.04%   |
| SanDisk             | 7         | 8      | 4.93%   |
| Toshiba             | 6         | 15     | 4.23%   |
| NVMe                | 5         | 6      | 3.52%   |
| Crucial             | 4         | 12     | 2.82%   |
| Micron Technology   | 3         | 6      | 2.11%   |
| Hitachi             | 3         | 3      | 2.11%   |
| Hewlett-Packard     | 3         | 7      | 2.11%   |
| Transcend           | 2         | 2      | 1.41%   |
| SK hynix            | 2         | 2      | 1.41%   |
| Phison              | 2         | 2      | 1.41%   |
| Innodisk            | 2         | 2      | 1.41%   |
| HPE                 | 2         | 14     | 1.41%   |
| Apacer              | 2         | 2      | 1.41%   |
| XrayDisk            | 1         | 1      | 0.7%    |
| Supermicro          | 1         | 1      | 0.7%    |
| OCZ                 | 1         | 2      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| LITEON              | 1         | 1      | 0.7%    |
| KingSpec            | 1         | 1      | 0.7%    |
| HGST                | 1         | 4      | 0.7%    |
| Fordisk             | 1         | 1      | 0.7%    |
| Dell                | 1         | 2      | 0.7%    |
| A-DATA Technology   | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SanDisk SDSA6MM-032G-1006 32GB       | 3         | 1.92%   |
| Kingston SA400S37120G 120GB          | 3         | 1.92%   |
| Hoodisk SSD 128GB                    | 3         | 1.92%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 2         | 1.28%   |
| Toshiba HDWQ140 4TB                  | 2         | 1.28%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.28%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.28%   |
| Samsung HD501LJ 500GB                | 2         | 1.28%   |
| Phison SATA SSD 16GB                 | 2         | 1.28%   |
| NVMe KBG40ZPZ256G TOS 256GB          | 2         | 1.28%   |
| Kingston SV300S37A240G 240GB         | 2         | 1.28%   |
| Intel SSDSC2BW240A4 240GB            | 2         | 1.28%   |
| Hoodisk SSD 64GB                     | 2         | 1.28%   |
| Hoodisk SSD 32GB                     | 2         | 1.28%   |
| Hoodisk SSD 16GB                     | 2         | 1.28%   |
| HP RAID 1(1+0) 146GB                 | 2         | 1.28%   |
| Crucial CT256MX100SSD1 256GB         | 2         | 1.28%   |
| Apacer 64GB SATA Flash Drive         | 2         | 1.28%   |
| XrayDisk SSD 64GB                    | 1         | 0.64%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.64%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.64%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.64%   |
| WDC WD82PURZ-85TEUY0 8TB             | 1         | 0.64%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.64%   |
| WDC WD5000AAKS-07V0A0 500GB          | 1         | 0.64%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 0.64%   |
| WDC WD2500AAJS-60B4A0 250GB          | 1         | 0.64%   |
| WDC WD20EARX-00ZUDB0 2TB             | 1         | 0.64%   |
| WDC WD2002FYPS-02W3B0 2TB            | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.64%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.64%   |
| Transcend TS256GMSA452T 256GB        | 1         | 0.64%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.64%   |
| Toshiba KPM5XVUG960G 960GB           | 1         | 0.64%   |
| Toshiba KPM5XMUG400G 400GB           | 1         | 0.64%   |
| Toshiba HDWR11A 10TB                 | 1         | 0.64%   |
| Toshiba HDWN180 8TB                  | 1         | 0.64%   |
| Toshiba HDWG480 8TB                  | 1         | 0.64%   |
| Toshiba HDWG180 8TB                  | 1         | 0.64%   |
| Toshiba DT01ACA100 1TB               | 1         | 0.64%   |
| Supermicro SSD 64GB                  | 1         | 0.64%   |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 0.64%   |
| SK hynix HFS128G32MND-2200A 128GB    | 1         | 0.64%   |
| Seagate ST9640320AS 640GB            | 1         | 0.64%   |
| Seagate ST9500420AS 500GB            | 1         | 0.64%   |
| Seagate ST9500325AS 500GB            | 1         | 0.64%   |
| Seagate ST9320423AS 320GB            | 1         | 0.64%   |
| Seagate ST8000VX0022-2EJ112 8TB      | 1         | 0.64%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 0.64%   |
| Seagate ST4000NE0025-2EW107 4TB      | 1         | 0.64%   |
| Seagate ST4000DM005-2DP166 4TB       | 1         | 0.64%   |
| Seagate ST4000DM000-2AE166 4TB       | 1         | 0.64%   |
| Seagate ST4000DM000-1F2168 4TB       | 1         | 0.64%   |
| Seagate ST2000NC001-1DY164 2TB       | 1         | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 0.64%   |
| Seagate ST1800MM0159 1.8TB           | 1         | 0.64%   |
| Seagate ST100FN0021 100GB            | 1         | 0.64%   |
| Seagate ST1000NX0313 1TB             | 1         | 0.64%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 40     | 36.17%  |
| WDC                 | 9         | 11     | 19.15%  |
| Toshiba             | 5         | 13     | 10.64%  |
| Samsung Electronics | 5         | 8      | 10.64%  |
| NVMe                | 3         | 4      | 6.38%   |
| Hitachi             | 3         | 3      | 6.38%   |
| Hewlett-Packard     | 3         | 7      | 6.38%   |
| HPE                 | 1         | 8      | 2.13%   |
| HGST                | 1         | 4      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 25     | 21.59%  |
| Kingston            | 11        | 13     | 12.5%   |
| Intel               | 10        | 23     | 11.36%  |
| Hoodisk             | 10        | 12     | 11.36%  |
| SanDisk             | 7         | 8      | 7.95%   |
| Crucial             | 4         | 12     | 4.55%   |
| Micron Technology   | 3         | 6      | 3.41%   |
| WDC                 | 2         | 4      | 2.27%   |
| SK hynix            | 2         | 2      | 2.27%   |
| Phison              | 2         | 2      | 2.27%   |
| NVMe                | 2         | 2      | 2.27%   |
| Innodisk            | 2         | 2      | 2.27%   |
| Apacer              | 2         | 2      | 2.27%   |
| XrayDisk            | 1         | 1      | 1.14%   |
| Transcend           | 1         | 1      | 1.14%   |
| Toshiba             | 1         | 2      | 1.14%   |
| Supermicro          | 1         | 1      | 1.14%   |
| Seagate             | 1         | 1      | 1.14%   |
| OCZ                 | 1         | 2      | 1.14%   |
| LITEONIT            | 1         | 1      | 1.14%   |
| LITEON              | 1         | 1      | 1.14%   |
| KingSpec            | 1         | 1      | 1.14%   |
| HPE                 | 1         | 6      | 1.14%   |
| Fordisk             | 1         | 1      | 1.14%   |
| Dell                | 1         | 2      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 77        | 133    | 62.1%   |
| HDD  | 37        | 98     | 29.84%  |
| NVMe | 10        | 10     | 8.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 231    | 90.99%  |
| NVMe | 10        | 10     | 9.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 137    | 69.05%  |
| 0.51-1.0   | 21        | 34     | 16.67%  |
| 3.01-4.0   | 7         | 22     | 5.56%   |
| 1.01-2.0   | 6         | 19     | 4.76%   |
| 4.01-10.0  | 5         | 19     | 3.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 44.35%  |
| 51-100         | 17        | 14.78%  |
| 21-50          | 14        | 12.17%  |
| 1-20           | 13        | 11.3%   |
| 251-500        | 10        | 8.7%    |
| 501-1000       | 6         | 5.22%   |
| 1001-2000      | 3         | 2.61%   |
| More than 3000 | 1         | 0.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 99        | 84.62%  |
| 21-50   | 15        | 12.82%  |
| 251-500 | 2         | 1.71%   |
| 101-250 | 1         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 5.88%   |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 5.88%   |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 5.88%   |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 5.88%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 5.88%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 5.88%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 5.88%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 5.88%   |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 5.88%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 5.88%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 5.88%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 5.88%   |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 5.88%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 5.88%   |
| Intel SSDSC2CT120A3 120GB                    | 1         | 1      | 5.88%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 5.88%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 41.18%  |
| WDC                 | 3         | 4      | 17.65%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Intel               | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Kingston            | 1         | 1      | 5.88%   |
| Hitachi             | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 54.55%  |
| WDC                 | 3         | 4      | 27.27%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 62.5%   |
| SSD  | 6         | 6      | 37.5%   |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 88        | 204    | 75.86%  |
| Malfunc  | 16        | 18     | 13.79%  |
| Detected | 12        | 19     | 10.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 83        | 61.94%  |
| AMD                      | 19        | 14.18%  |
| Broadcom / LSI           | 7         | 5.22%   |
| Samsung Electronics      | 4         | 2.99%   |
| Marvell Technology Group | 4         | 2.99%   |
| SanDisk                  | 3         | 2.24%   |
| Hewlett-Packard          | 3         | 2.24%   |
| KIOXIA                   | 2         | 1.49%   |
| ASMedia Technology       | 2         | 1.49%   |
| VIA Technologies         | 1         | 0.75%   |
| Silicon Motion           | 1         | 0.75%   |
| Seagate Technology       | 1         | 0.75%   |
| Realtek Semiconductor    | 1         | 0.75%   |
| Nvidia                   | 1         | 0.75%   |
| Dell                     | 1         | 0.75%   |
| Adaptec                  | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 8.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 5.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 5         | 3.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.53%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 1.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.9%    |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 1.9%    |
| AMD FCH IDE Controller                                                           | 3         | 1.9%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.27%   |
| Intel SSD 660P Series                                                            | 2         | 1.27%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 1.27%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.27%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 2         | 1.27%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 2         | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                           | 2         | 1.27%   |
| AMD 300 Series Chipset SATA Controller                                           | 2         | 1.27%   |
| VIA VT6415 PATA IDE Host Controller                                              | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.63%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.63%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.63%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.63%   |
| Nvidia MCP65 SATA Controller                                                     | 1         | 0.63%   |
| Nvidia MCP65 IDE                                                                 | 1         | 0.63%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller            | 1         | 0.63%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.63%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 1         | 0.63%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 0.63%   |
| Intel PCIe Data Center SSD                                                       | 1         | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.63%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 1         | 0.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 1         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 1         | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1         | 0.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 90        | 64.29%  |
| IDE  | 17        | 12.14%  |
| NVMe | 15        | 10.71%  |
| RAID | 11        | 7.86%   |
| SAS  | 7         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 91        | 79.82%  |
| AMD     | 22        | 19.3%   |
| Unknown | 1         | 0.88%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 6         | 5.26%   |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 2.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 3         | 2.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 3         | 2.63%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 2.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 1.75%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 1.75%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 1.75%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 1.75%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 2         | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.75%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 1.75%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.88%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.88%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.88%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.88%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.88%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.88%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.88%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.88%   |
| Intel Xeon CPU E5-2623 v4 @ 2.60GHz      | 1         | 0.88%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 1         | 0.88%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.88%   |
| Intel Xeon CPU E31240 @ 3.30GHz          | 1         | 0.88%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1         | 0.88%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz     | 1         | 0.88%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz     | 1         | 0.88%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz      | 1         | 0.88%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1         | 0.88%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz      | 1         | 0.88%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 1         | 0.88%   |
| Intel Xeon CPU 5140 @ 2.33GHz            | 1         | 0.88%   |
| Intel Xeon                               | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU E5700        | 1         | 0.88%   |
| Intel Pentium CPU G6950 @ 2.80GHz        | 1         | 0.88%   |
| Intel Pentium CPU G4400 @ 3.30GHz        | 1         | 0.88%   |
| Intel CPU Version                        | 1         | 0.88%   |
| Intel Core m3-8100Y CPU @ 1.10GHz        | 1         | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.88%   |
| Intel Core i7-6850K CPU @ 3.60GHz        | 1         | 0.88%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 1         | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 0.88%   |
| Intel Core i7-5550U CPU @ 2.00GHz        | 1         | 0.88%   |
| Intel Core i7-4790K CPU @ 4.00GHz        | 1         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.88%   |
| Intel Core i7-3770S CPU @ 3.10GHz        | 1         | 0.88%   |
| Intel Core i7-2760QM CPU @ 2.40GHz       | 1         | 0.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz         | 1         | 0.88%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 0.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 1         | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 1         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 0.88%   |
| Intel Core i5-4690K CPU @ 3.50GHz        | 1         | 0.88%   |
| Intel Core i5-4670K CPU @ 3.40GHz        | 1         | 0.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1         | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 30        | 26.32%  |
| Intel Xeon              | 18        | 15.79%  |
| Intel Core i7           | 16        | 14.04%  |
| Intel Celeron           | 9         | 7.89%   |
| AMD GX                  | 8         | 7.02%   |
| Other                   | 6         | 5.26%   |
| Intel Core i3           | 4         | 3.51%   |
| Intel Xeon Silver       | 3         | 2.63%   |
| AMD Ryzen 7             | 3         | 2.63%   |
| Intel Pentium           | 2         | 1.75%   |
| Intel Core 2 Duo        | 2         | 1.75%   |
| Intel Atom              | 2         | 1.75%   |
| AMD Ryzen 9             | 2         | 1.75%   |
| Intel Pentium Dual-Core | 1         | 0.88%   |
| Intel Core m3           | 1         | 0.88%   |
| Intel Core 2 Quad       | 1         | 0.88%   |
| AMD Ryzen 5 PRO         | 1         | 0.88%   |
| AMD G                   | 1         | 0.88%   |
| AMD FX                  | 1         | 0.88%   |
| AMD Athlon 64 X2        | 1         | 0.88%   |
| AMD Athlon              | 1         | 0.88%   |
| AMD A4                  | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 60        | 52.63%  |
| 2       | 32        | 28.07%  |
| 8       | 5         | 4.39%   |
| 6       | 5         | 4.39%   |
| Unknown | 4         | 3.51%   |
| 24      | 3         | 2.63%   |
| 16      | 3         | 2.63%   |
| 12      | 1         | 0.88%   |
| 10      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 105       | 92.11%  |
| 2       | 6         | 5.26%   |
| Unknown | 3         | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 60        | 52.63%  |
| 2       | 50        | 43.86%  |
| Unknown | 4         | 3.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 17        | 14.91%  |
| Haswell       | 16        | 14.04%  |
| SandyBridge   | 10        | 8.77%   |
| Silvermont    | 9         | 7.89%   |
| Puma          | 7         | 6.14%   |
| KabyLake      | 7         | 6.14%   |
| Penryn        | 6         | 5.26%   |
| IvyBridge     | 6         | 5.26%   |
| Westmere      | 5         | 4.39%   |
| Broadwell     | 5         | 4.39%   |
| Steamroller   | 3         | 2.63%   |
| IceLake       | 3         | 2.63%   |
| Unknown       | 3         | 2.63%   |
| Zen 2         | 2         | 1.75%   |
| Zen           | 2         | 1.75%   |
| Nehalem       | 2         | 1.75%   |
| Jaguar        | 2         | 1.75%   |
| Core          | 2         | 1.75%   |
| Zen+          | 1         | 0.88%   |
| Piledriver    | 1         | 0.88%   |
| K8 Hammer     | 1         | 0.88%   |
| Goldmont plus | 1         | 0.88%   |
| Goldmont      | 1         | 0.88%   |
| Excavator     | 1         | 0.88%   |
| Bobcat        | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 60        | 55.56%  |
| Nvidia                     | 17        | 15.74%  |
| Matrox Electronics Systems | 15        | 13.89%  |
| AMD                        | 14        | 12.96%  |
| ASPEED Technology          | 2         | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 5.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 5.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 3.7%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 3.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.7%    |
| Intel HD Graphics 530                                                                    | 4         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.7%    |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 2.78%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 2.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.78%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 2.78%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.85%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1.85%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.85%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1.85%   |
| Intel HD Graphics 620                                                                    | 2         | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 1.85%   |
| AMD ES1000                                                                               | 2         | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.93%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.93%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.93%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.93%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1         | 0.93%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.93%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.93%   |
| Intel UHD Graphics 615                                                                   | 1         | 0.93%   |
| Intel Iris Pro Graphics P580                                                             | 1         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.93%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.93%   |
| Intel HD Graphics 510                                                                    | 1         | 0.93%   |
| Intel HD Graphics 500                                                                    | 1         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.93%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.93%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.93%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 1         | 0.93%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 0.93%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 0.93%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 46.96%  |
| 1 x Nvidia     | 15        | 13.04%  |
| 1 x Matrox     | 15        | 13.04%  |
| 1 x AMD        | 13        | 11.3%   |
| Other          | 10        | 8.7%    |
| 2 x Intel      | 2         | 1.74%   |
| Intel + Nvidia | 2         | 1.74%   |
| Intel + AMD    | 2         | 1.74%   |
| 1 x ASPEED     | 2         | 1.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 91        | 79.13%  |
| Unknown     | 14        | 12.17%  |
| Proprietary | 10        | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 89.47%  |
| 1.01-2.0   | 4         | 3.51%   |
| 0.51-1.0   | 3         | 2.63%   |
| 3.01-4.0   | 2         | 1.75%   |
| 7.01-8.0   | 1         | 0.88%   |
| 5.01-6.0   | 1         | 0.88%   |
| 8.01-16.0  | 1         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 7         | 15.91%  |
| Samsung Electronics     | 6         | 13.64%  |
| Hewlett-Packard         | 6         | 13.64%  |
| Chimei Innolux          | 6         | 13.64%  |
| Dell                    | 4         | 9.09%   |
| Iiyama                  | 2         | 4.55%   |
| AOC                     | 2         | 4.55%   |
| Philips                 | 1         | 2.27%   |
| Panasonic               | 1         | 2.27%   |
| LG Electronics          | 1         | 2.27%   |
| Lenovo Group Limited    | 1         | 2.27%   |
| Lenovo                  | 1         | 2.27%   |
| InfoVision              | 1         | 2.27%   |
| Gigabyte Technology     | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| BOE                     | 1         | 2.27%   |
| AU Optronics            | 1         | 2.27%   |
| Ancor Communications    | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch        | 2         | 4.17%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 2         | 4.17%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                    | 2         | 4.17%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                         | 2         | 4.17%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                           | 2         | 4.17%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch        | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SyncMaster                               | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                         | 1         | 2.08%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                        | 1         | 2.08%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 2.08%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                 | 1         | 2.08%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 2.08%   |
| LG Electronics LCD Monitor LX20D 1600x1200                               | 1         | 2.08%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 2.08%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 2.08%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 2.08%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                    | 1         | 2.08%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch            | 1         | 2.08%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch              | 1         | 2.08%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                               | 1         | 2.08%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                              | 1         | 2.08%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch              | 1         | 2.08%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch              | 1         | 2.08%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 2.08%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 2.08%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                       | 1         | 2.08%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                        | 1         | 2.08%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE088B 1920x1280 220x150mm 10.5-inch                    | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 2.08%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 25%     |
| 1920x1200 (WUXGA)  | 6         | 13.64%  |
| 3840x2160 (4K)     | 5         | 11.36%  |
| 1366x768 (WXGA)    | 5         | 11.36%  |
| 2560x1440 (QHD)    | 3         | 6.82%   |
| 1600x900 (HD+)     | 3         | 6.82%   |
| 3440x1440          | 2         | 4.55%   |
| 2736x1824          | 2         | 4.55%   |
| 3840x1080          | 1         | 2.27%   |
| 2880x1620          | 1         | 2.27%   |
| 1920x1280          | 1         | 2.27%   |
| 1680x1050 (WSXGA+) | 1         | 2.27%   |
| 1600x1200          | 1         | 2.27%   |
| 1440x900 (WXGA+)   | 1         | 2.27%   |
| Unknown            | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 21.95%  |
| Unknown | 6         | 14.63%  |
| 27      | 5         | 12.2%   |
| 24      | 4         | 9.76%   |
| 23      | 4         | 9.76%   |
| 13      | 3         | 7.32%   |
| 12      | 3         | 7.32%   |
| 34      | 1         | 2.44%   |
| 28      | 1         | 2.44%   |
| 21      | 1         | 2.44%   |
| 17      | 1         | 2.44%   |
| 14      | 1         | 2.44%   |
| 11      | 1         | 2.44%   |
| 10      | 1         | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 11        | 26.83%  |
| 301-350     | 11        | 26.83%  |
| 201-300     | 7         | 17.07%  |
| Unknown     | 6         | 14.63%  |
| 601-700     | 3         | 7.32%   |
| 701-800     | 1         | 2.44%   |
| 401-500     | 1         | 2.44%   |
| 351-400     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 59.46%  |
| Unknown | 6         | 16.22%  |
| 16/10   | 5         | 13.51%  |
| 3/2     | 3         | 8.11%   |
| 21/9    | 1         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 22.5%   |
| Unknown        | 6         | 15%     |
| 301-350        | 5         | 12.5%   |
| 201-250        | 5         | 12.5%   |
| 81-90          | 3         | 7.5%    |
| 61-70          | 3         | 7.5%    |
| 251-300        | 3         | 7.5%    |
| 51-60          | 2         | 5%      |
| 351-500        | 2         | 5%      |
| 71-80          | 1         | 2.5%    |
| 121-130        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 28.57%  |
| 51-100        | 8         | 19.05%  |
| 161-240       | 6         | 14.29%  |
| 101-120       | 6         | 14.29%  |
| Unknown       | 6         | 14.29%  |
| More than 240 | 2         | 4.76%   |
| 1-50          | 2         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 77        | 66.38%  |
| 1     | 30        | 25.86%  |
| 2     | 8         | 6.9%    |
| 3     | 1         | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 86        | 53.75%  |
| Realtek Semiconductor    | 35        | 21.88%  |
| Broadcom                 | 20        | 12.5%   |
| Qualcomm Atheros         | 5         | 3.13%   |
| TP-Link                  | 2         | 1.25%   |
| Sierra Wireless          | 1         | 0.63%   |
| Ralink Technology        | 1         | 0.63%   |
| NetXen Incorporated      | 1         | 0.63%   |
| Microsoft                | 1         | 0.63%   |
| Mellanox Technologies    | 1         | 0.63%   |
| MediaTek                 | 1         | 0.63%   |
| Marvell Technology Group | 1         | 0.63%   |
| JMicron Technology       | 1         | 0.63%   |
| IMC Networks             | 1         | 0.63%   |
| Hewlett-Packard          | 1         | 0.63%   |
| Edimax Technology        | 1         | 0.63%   |
| Chelsio Communications   | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32        | 16.24%  |
| Intel I210 Gigabit Network Connection                                         | 16        | 8.12%   |
| Intel I211 Gigabit Network Connection                                         | 12        | 6.09%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 4.06%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 3.55%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 3.05%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.54%   |
| Intel Wireless 7260                                                           | 4         | 2.03%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 2.03%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 2.03%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.03%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.52%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 1.52%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.02%   |
| Intel Wireless 8260                                                           | 2         | 1.02%   |
| Intel Wireless 7265                                                           | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.02%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 1.02%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.02%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 1.02%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.51%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.51%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                 | 1         | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.51%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1         | 0.51%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.51%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1         | 0.51%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.51%   |
| Intel Wireless 3165                                                           | 1         | 0.51%   |
| Intel WiFi Link 5100                                                          | 1         | 0.51%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.51%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 55%     |
| Realtek Semiconductor | 4         | 10%     |
| Qualcomm Atheros      | 4         | 10%     |
| Broadcom              | 4         | 10%     |
| TP-Link               | 2         | 5%      |
| Sierra Wireless       | 1         | 2.5%    |
| Ralink Technology     | 1         | 2.5%    |
| IMC Networks          | 1         | 2.5%    |
| Edimax Technology     | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 4         | 9.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 7.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 4.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.88%   |
| Intel Wireless 8260                                            | 2         | 4.88%   |
| Intel Wireless 7265                                            | 2         | 4.88%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 4.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.88%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.44%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.44%   |
| Intel Wireless-AC 9260                                         | 1         | 2.44%   |
| Intel Wireless 3165                                            | 1         | 2.44%   |
| Intel WiFi Link 5100                                           | 1         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.44%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 2.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 74        | 57.36%  |
| Realtek Semiconductor    | 35        | 27.13%  |
| Broadcom                 | 16        | 12.4%   |
| Qualcomm Atheros         | 1         | 0.78%   |
| Microsoft                | 1         | 0.78%   |
| Marvell Technology Group | 1         | 0.78%   |
| JMicron Technology       | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 32        | 21.19%  |
| Intel I210 Gigabit Network Connection                                         | 16        | 10.6%   |
| Intel I211 Gigabit Network Connection                                         | 12        | 7.95%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 5.3%    |
| Intel 82580 Gigabit Network Connection                                        | 7         | 4.64%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 3.97%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.31%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 3.31%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 2.65%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 2.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.65%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.99%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 3         | 1.99%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.99%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.32%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.32%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.32%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 1.32%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 1.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.66%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.66%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.66%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.66%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.66%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.66%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.66%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.66%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.66%   |
| Intel 82567LF-3 Gigabit Network Connection                                    | 1         | 0.66%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.66%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1         | 0.66%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.66%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 107       | 71.81%  |
| WiFi     | 37        | 24.83%  |
| Unknown  | 4         | 2.68%   |
| Modem    | 1         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 81.3%   |
| WiFi     | 23        | 18.7%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 34.48%  |
| 1     | 19        | 16.38%  |
| 4     | 16        | 13.79%  |
| 3     | 15        | 12.93%  |
| 6     | 12        | 10.34%  |
| 5     | 6         | 5.17%   |
| 8     | 3         | 2.59%   |
| 7     | 3         | 2.59%   |
| 9     | 1         | 0.86%   |
| 0     | 1         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 94.78%  |
| Yes  | 6         | 5.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 12        | 44.44%  |
| Cambridge Silicon Radio | 4         | 14.81%  |
| Broadcom                | 3         | 11.11%  |
| IMC Networks            | 2         | 7.41%   |
| Hewlett-Packard         | 2         | 7.41%   |
| Dell                    | 2         | 7.41%   |
| Lite-On Technology      | 1         | 3.7%    |
| Apple                   | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 7         | 25.93%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 14.81%  |
| Intel AX201 Bluetooth                                   | 2         | 7.41%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 7.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 3.7%    |
| Intel AX200 Bluetooth                                   | 1         | 3.7%    |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 3.7%    |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 3.7%    |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 3.7%    |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 3.7%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 3.7%    |
| Dell Dell Wireless 355C Bluetooth 2.0 + EDR module      | 1         | 3.7%    |
| Broadcom Broadcom Bluetooth 4.0 Adapter                 | 1         | 3.7%    |
| Apple Apple Broadcom Built-in Bluetooth                 | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 60        | 63.83%  |
| AMD              | 16        | 17.02%  |
| Nvidia           | 15        | 15.96%  |
| Philips (or NXP) | 1         | 1.06%   |
| Lenovo           | 1         | 1.06%   |
| GN Netcom        | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 7.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 6.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 6.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 6.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 4.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 4.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.51%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.51%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.51%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 2.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 2.63%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.75%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.75%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.88%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.88%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.88%   |
| GN Netcom Jabra SPEAK 410 USB                                                                     | 1         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.88%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 18.92%  |
| SK hynix            | 17        | 15.32%  |
| Corsair             | 16        | 14.41%  |
| Unknown             | 13        | 11.71%  |
| Kingston            | 12        | 10.81%  |
| Micron Technology   | 11        | 9.91%   |
| Crucial             | 4         | 3.6%    |
| Hewlett-Packard     | 3         | 2.7%    |
| Elpida              | 3         | 2.7%    |
| Unknown             | 3         | 2.7%    |
| HPE                 | 2         | 1.8%    |
| G.Skill             | 2         | 1.8%    |
| Toshiba             | 1         | 0.9%    |
| Tigo                | 1         | 0.9%    |
| Kimtigo             | 1         | 0.9%    |
| Apacer              | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 5         | 4.13%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s         | 4         | 3.31%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 3         | 2.48%   |
| Unknown                                                     | 3         | 2.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.65%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 2         | 1.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.65%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 2         | 1.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.65%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                  | 1         | 0.83%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s                | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s                | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 1         | 0.83%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                  | 1         | 0.83%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s                | 1         | 0.83%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s        | 1         | 0.83%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s         | 1         | 0.83%   |
| Tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                  | 1         | 0.83%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 0.83%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT351U7EFR8C-RD 4GB DIMM DDR3                 | 1         | 0.83%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.83%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.83%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2666MT/s       | 1         | 0.83%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 0.83%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s        | 1         | 0.83%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                   | 1         | 0.83%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471B5173BH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 1         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s       | 1         | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 0.83%   |
| Samsung RAM M395T2953CZ4-CE65 1GB FB-DIMM DDR2 667MT/s      | 1         | 0.83%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM DDR3 1600MT/s        | 1         | 0.83%   |
| Samsung RAM M391B5773CH0-YH9 2GB DIMM DDR3 1333MT/s         | 1         | 0.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s         | 1         | 0.83%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 0.83%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                    | 1         | 0.83%   |
| Micron RAM M378B5273BH1-CK0 8GB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 1         | 0.83%   |
| Micron RAM 36JSZF51272PZ1G4F1 4GB DIMM DDR3 1333MT/s        | 1         | 0.83%   |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s        | 1         | 0.83%   |
| Micron RAM 18ASF2G72PDZ-2G6E1 16GB DIMM DDR4 2667MT/s       | 1         | 0.83%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s      | 1         | 0.83%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB DIMM DDR3 1867MT/s         | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 59        | 60.2%   |
| DDR4    | 28        | 28.57%  |
| DDR2    | 6         | 6.12%   |
| Unknown | 2         | 2.04%   |
| SDRAM   | 1         | 1.02%   |
| LPDDR3  | 1         | 1.02%   |
| DRAM    | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 60        | 60.61%  |
| SODIMM  | 36        | 36.36%  |
| FB-DIMM | 2         | 2.02%   |
| Chip    | 1         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 43        | 40.57%  |
| 8192  | 27        | 25.47%  |
| 16384 | 16        | 15.09%  |
| 2048  | 12        | 11.32%  |
| 1024  | 6         | 5.66%   |
| 32768 | 2         | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 31.68%  |
| 1333    | 25        | 24.75%  |
| 2133    | 10        | 9.9%    |
| 2667    | 9         | 8.91%   |
| 2666    | 4         | 3.96%   |
| 2400    | 4         | 3.96%   |
| 800     | 4         | 3.96%   |
| 667     | 4         | 3.96%   |
| Unknown | 3         | 2.97%   |
| 3200    | 2         | 1.98%   |
| 1867    | 1         | 0.99%   |
| 1334    | 1         | 0.99%   |
| 1332    | 1         | 0.99%   |
| 333     | 1         | 0.99%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 7         | 36.84%  |
| Acer                  | 3         | 15.79%  |
| Realtek Semiconductor | 2         | 10.53%  |
| IMC Networks          | 2         | 10.53%  |
| Suyin                 | 1         | 5.26%   |
| Quanta                | 1         | 5.26%   |
| Microdia              | 1         | 5.26%   |
| Logitech              | 1         | 5.26%   |
| Lenovo                | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Suyin Asus Integrated Webcam             | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD             | 1         | 5.26%   |
| Realtek Front Camera                     | 1         | 5.26%   |
| Quanta VGA WebCam                        | 1         | 5.26%   |
| Microdia Integrated Webcam               | 1         | 5.26%   |
| Logitech Webcam C270                     | 1         | 5.26%   |
| Lenovo Integrated Webcam                 | 1         | 5.26%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 5.26%   |
| IMC Networks EasyCamera                  | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 5.26%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 5.26%   |
| Chicony ThinkPad T490 Webcam             | 1         | 5.26%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5.26%   |
| Chicony Integrated HP HD Webcam          | 1         | 5.26%   |
| Chicony Integrated Camera                | 1         | 5.26%   |
| Chicony Camera                           | 1         | 5.26%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 5.26%   |
| Acer Integrated Camera                   | 1         | 5.26%   |
| Acer EasyCamera                          | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 28.57%  |
| Upek             | 2         | 28.57%  |
| Synaptics        | 1         | 14.29%  |
| Broadcom         | 1         | 14.29%  |
| AuthenTec        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 28.57%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| AuthenTec AES2810                                                            | 1         | 14.29%  |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 45        | 38.79%  |
| 0     | 39        | 33.62%  |
| 2     | 21        | 18.1%   |
| 3     | 6         | 5.17%   |
| 4     | 3         | 2.59%   |
| 5     | 2         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 68        | 67.33%  |
| Net/wireless             | 9         | 8.91%   |
| Card reader              | 6         | 5.94%   |
| Fingerprint reader       | 5         | 4.95%   |
| Graphics card            | 3         | 2.97%   |
| Firewire controller      | 3         | 2.97%   |
| Storage/ata              | 2         | 1.98%   |
| Network                  | 2         | 1.98%   |
| Sound                    | 1         | 0.99%   |
| Net/ethernet             | 1         | 0.99%   |
| Bluetooth                | 1         | 0.99%   |

