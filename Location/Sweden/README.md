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

Total: 165

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 05KX61 A04                  | Server      | [f1232f79c4](https://bsd-hardware.info/?probe=f1232f79c4) | Sep 25, 2022 |
| HP            | Unknown                     | Notebook    | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| AOpen         | iBTMx-DS R1.04 55DED10A0... | Desktop     | [a480263c28](https://bsd-hardware.info/?probe=a480263c28) | Aug 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e5efeb3781](https://bsd-hardware.info/?probe=e5efeb3781) | Aug 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9d1eb045e5](https://bsd-hardware.info/?probe=9d1eb045e5) | Aug 20, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| ASUSTek       | CM6731_CM6431_CM6331        | Desktop     | [6e40b41bc3](https://bsd-hardware.info/?probe=6e40b41bc3) | Aug 04, 2022 |
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
| OPNsense 21.1        | 11        | 8.21%   |
| OPNsense 21.7.7      | 6         | 4.48%   |
| OPNsense 21.1.3      | 6         | 4.48%   |
| OpenBSD 6.8          | 6         | 4.48%   |
| OPNsense 21.1.5      | 5         | 3.73%   |
| OPNsense 21.1.2      | 5         | 3.73%   |
| OpenBSD 7.0          | 5         | 3.73%   |
| helloSystem 0.5.0    | 5         | 3.73%   |
| OPNsense 21.1.8      | 4         | 2.99%   |
| OPNsense 22.7.2      | 3         | 2.24%   |
| OPNsense 22.1.8      | 3         | 2.24%   |
| OPNsense 21.7.3      | 3         | 2.24%   |
| OPNsense 21.7.1      | 3         | 2.24%   |
| OPNsense 20.7.8      | 3         | 2.24%   |
| OpenBSD 6.9          | 3         | 2.24%   |
| FreeBSD 13.0-p7      | 3         | 2.24%   |
| FreeBSD 12.1-p8      | 3         | 2.24%   |
| OPNsense 22.1.9      | 2         | 1.49%   |
| OPNsense 22.1.6      | 2         | 1.49%   |
| OPNsense 22.1.3      | 2         | 1.49%   |
| OPNsense 22.1.1      | 2         | 1.49%   |
| OPNsense 21.7.6      | 2         | 1.49%   |
| OPNsense 21.7        | 2         | 1.49%   |
| OPNsense 21.1.7      | 2         | 1.49%   |
| OPNsense 21.1.6      | 2         | 1.49%   |
| OpenBSD 6.7          | 2         | 1.49%   |
| helloSystem 0.7.0    | 2         | 1.49%   |
| helloSystem 0.4.0    | 2         | 1.49%   |
| FreeBSD 14.0-CURRENT | 2         | 1.49%   |
| FreeBSD 12.2-p4      | 2         | 1.49%   |
| FreeBSD 12.2-p2      | 2         | 1.49%   |
| pfSense 2.5.0        | 1         | 0.75%   |
| OPNsense 22.7        | 1         | 0.75%   |
| OPNsense 22.1.7      | 1         | 0.75%   |
| OPNsense 22.1.5      | 1         | 0.75%   |
| OPNsense 22.1.4      | 1         | 0.75%   |
| OPNsense 22.1.2      | 1         | 0.75%   |
| OPNsense 22.1.10     | 1         | 0.75%   |
| OPNsense 22.1        | 1         | 0.75%   |
| OPNsense 21.7.8      | 1         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 66        | 55.46%  |
| FreeBSD     | 23        | 19.33%  |
| OpenBSD     | 15        | 12.61%  |
| helloSystem | 9         | 7.56%   |
| GhostBSD    | 4         | 3.36%   |
| pfSense     | 1         | 0.84%   |
| FuryBSD     | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 118       | 99.16%  |
| octeon | 1         | 0.84%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 79        | 65.29%  |
| fvwm         | 12        | 9.92%   |
| KDE5         | 10        | 8.26%   |
| helloDesktop | 9         | 7.44%   |
| MATE         | 4         | 3.31%   |
| i3           | 2         | 1.65%   |
| xfwm         | 1         | 0.83%   |
| XFCE         | 1         | 0.83%   |
| TWM          | 1         | 0.83%   |
| Mutter       | 1         | 0.83%   |
| AwesomeWM    | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 80        | 67.23%  |
| X11     | 39        | 32.77%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 91        | 74.59%  |
| SLiM    | 10        | 8.2%    |
| SDDM    | 9         | 7.38%   |
| LightDM | 6         | 4.92%   |
| GDM     | 4         | 3.28%   |
| XDM     | 2         | 1.64%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 81        | 66.94%  |
| en_US          | 21        | 17.36%  |
| C              | 13        | 10.74%  |
| sv_SE          | 4         | 3.31%   |
| sv_SE.US-ASCII | 1         | 0.83%   |
| en_CA          | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 97        | 80.17%  |
| BIOS | 24        | 19.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 64        | 53.78%  |
| Zfs  | 40        | 33.61%  |
| Ffs  | 15        | 12.61%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 106       | 86.89%  |
| MBR  | 16        | 13.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 19        | 15.97%  |
| Hewlett-Packard            | 15        | 12.61%  |
| ASUSTek Computer           | 14        | 11.76%  |
| Lenovo                     | 13        | 10.92%  |
| PC Engines                 | 7         | 5.88%   |
| Unknown                    | 7         | 5.88%   |
| Gigabyte Technology        | 6         | 5.04%   |
| Intel                      | 5         | 4.2%    |
| MSI                        | 4         | 3.36%   |
| AMI                        | 4         | 3.36%   |
| Microsoft                  | 3         | 2.52%   |
| ASRock                     | 3         | 2.52%   |
| Supermicro                 | 2         | 1.68%   |
| Shuttle                    | 2         | 1.68%   |
| HPE                        | 2         | 1.68%   |
| Fujitsu                    | 2         | 1.68%   |
| Wistron                    | 1         | 0.84%   |
| Toshiba                    | 1         | 0.84%   |
| Sony                       | 1         | 0.84%   |
| ShenZhen MinWin Technology | 1         | 0.84%   |
| Protectli                  | 1         | 0.84%   |
| Google                     | 1         | 0.84%   |
| Fujitsu Siemens            | 1         | 0.84%   |
| Deciso                     | 1         | 0.84%   |
| AOpen                      | 1         | 0.84%   |
| ADI                        | 1         | 0.84%   |
| Acer                       | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 8         | 6.72%   |
| PC Engines APU2                   | 4         | 3.36%   |
| ASUS All Series                   | 4         | 3.36%   |
| HP t730 Thin Client               | 3         | 2.52%   |
| AMI Aptio CRB                     | 3         | 2.52%   |
| PC Engines apu4                   | 2         | 1.68%   |
| Microsoft Surface Pro 7           | 2         | 1.68%   |
| Dell PowerEdge R210 II            | 2         | 1.68%   |
| Dell PowerEdge R210               | 2         | 1.68%   |
| Dell OptiPlex 9020                | 2         | 1.68%   |
| Wistron ProLiant ML110 G6         | 1         | 0.84%   |
| Toshiba Satellite L450            | 1         | 0.84%   |
| Supermicro SYS-1019S-MP           | 1         | 0.84%   |
| Supermicro Super Server           | 1         | 0.84%   |
| Sony SVP1322M1EBI                 | 1         | 0.84%   |
| Shuttle SH570                     | 1         | 0.84%   |
| Shuttle DH170                     | 1         | 0.84%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1         | 0.84%   |
| Protectli FW4B                    | 1         | 0.84%   |
| PC Engines APU                    | 1         | 0.84%   |
| MSI WC776AA-UUW HPE-110sc         | 1         | 0.84%   |
| MSI MS-7C56                       | 1         | 0.84%   |
| MSI MS-7918                       | 1         | 0.84%   |
| MSI MS-7369                       | 1         | 0.84%   |
| Microsoft Surface Go 2            | 1         | 0.84%   |
| Lenovo V130-15IGM 81HL            | 1         | 0.84%   |
| Lenovo ThinkPad X395 20NL001SMX   | 1         | 0.84%   |
| Lenovo ThinkPad X250 20CLS4JH00   | 1         | 0.84%   |
| Lenovo ThinkPad X201 3680FAG      | 1         | 0.84%   |
| Lenovo ThinkPad W520 4284GN2      | 1         | 0.84%   |
| Lenovo ThinkPad T460s 20FAS4KH02  | 1         | 0.84%   |
| Lenovo ThinkPad T420 4236MBG      | 1         | 0.84%   |
| Lenovo ThinkPad T400 2767WSB      | 1         | 0.84%   |
| Lenovo ThinkPad L560 20F10032MS   | 1         | 0.84%   |
| Lenovo ThinkCentre M92p 2988B1G   | 1         | 0.84%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 0.84%   |
| Lenovo ThinkCentre E73 10AS002QMX | 1         | 0.84%   |
| Lenovo Legion Y530-15ICH 81FV     | 1         | 0.84%   |
| Intel Q3XXG4-P V1.0               | 1         | 0.84%   |
| Intel NUC5CPYB                    | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell PowerEdge                 | 11        | 9.24%   |
| Lenovo ThinkPad                | 8         | 6.72%   |
| Unknown                        | 8         | 6.72%   |
| Dell OptiPlex                  | 5         | 4.2%    |
| PC Engines APU2                | 4         | 3.36%   |
| HP ProLiant                    | 4         | 3.36%   |
| ASUS All                       | 4         | 3.36%   |
| Microsoft Surface              | 3         | 2.52%   |
| Lenovo ThinkCentre             | 3         | 2.52%   |
| HP t730                        | 3         | 2.52%   |
| Dell Latitude                  | 3         | 2.52%   |
| AMI Aptio                      | 3         | 2.52%   |
| PC Engines apu4                | 2         | 1.68%   |
| HPE ProLiant                   | 2         | 1.68%   |
| HP EliteDesk                   | 2         | 1.68%   |
| Wistron ProLiant               | 1         | 0.84%   |
| Toshiba Satellite              | 1         | 0.84%   |
| Supermicro SYS-1019S-MP        | 1         | 0.84%   |
| Supermicro Super               | 1         | 0.84%   |
| Sony SVP1322M1EBI              | 1         | 0.84%   |
| Shuttle SH570                  | 1         | 0.84%   |
| Shuttle DH170                  | 1         | 0.84%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.84%   |
| Protectli FW4B                 | 1         | 0.84%   |
| PC Engines APU                 | 1         | 0.84%   |
| MSI WC776AA-UUW                | 1         | 0.84%   |
| MSI MS-7C56                    | 1         | 0.84%   |
| MSI MS-7918                    | 1         | 0.84%   |
| MSI MS-7369                    | 1         | 0.84%   |
| Lenovo V130-15IGM              | 1         | 0.84%   |
| Lenovo Legion                  | 1         | 0.84%   |
| Intel Q3XXG4-P                 | 1         | 0.84%   |
| Intel NUC5CPYB                 | 1         | 0.84%   |
| Intel DQ67SW                   | 1         | 0.84%   |
| Intel DH61AG                   | 1         | 0.84%   |
| Intel CRESCENTBAY              | 1         | 0.84%   |
| HP Z230                        | 1         | 0.84%   |
| HP ProDesk                     | 1         | 0.84%   |
| HP ProBook                     | 1         | 0.84%   |
| HP Laptop                      | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 15        | 12.61%  |
| 2018    | 14        | 11.76%  |
| 2016    | 13        | 10.92%  |
| 2014    | 11        | 9.24%   |
| 2017    | 10        | 8.4%    |
| 2019    | 9         | 7.56%   |
| 2015    | 9         | 7.56%   |
| 2010    | 9         | 7.56%   |
| 2021    | 8         | 6.72%   |
| 2012    | 6         | 5.04%   |
| 2009    | 6         | 5.04%   |
| 2013    | 4         | 3.36%   |
| 2011    | 2         | 1.68%   |
| 2022    | 1         | 0.84%   |
| 2007    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 69        | 57.98%  |
| Notebook | 24        | 20.17%  |
| Server   | 16        | 13.45%  |
| Mini pc  | 7         | 5.88%   |
| Tablet   | 3         | 2.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 91.6%   |
| Yes  | 10        | 8.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 39        | 32.23%  |
| 4.01-8.0        | 33        | 27.27%  |
| 16.01-24.0      | 19        | 15.7%   |
| 32.01-64.0      | 13        | 10.74%  |
| 64.01-256.0     | 6         | 4.96%   |
| More than 256.0 | 3         | 2.48%   |
| 24.01-32.0      | 3         | 2.48%   |
| 3.01-4.0        | 2         | 1.65%   |
| 2.01-3.0        | 2         | 1.65%   |
| 1.01-2.0        | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 62        | 51.24%  |
| 0.51-1.0    | 32        | 26.45%  |
| 1.01-2.0    | 14        | 11.57%  |
| 4.01-8.0    | 4         | 3.31%   |
| 2.01-3.0    | 3         | 2.48%   |
| 3.01-4.0    | 2         | 1.65%   |
| 24.01-32.0  | 2         | 1.65%   |
| 64.01-256.0 | 2         | 1.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 83        | 67.48%  |
| 2      | 12        | 9.76%   |
| 0      | 8         | 6.5%    |
| 3      | 6         | 4.88%   |
| 6      | 3         | 2.44%   |
| 4      | 3         | 2.44%   |
| 11     | 2         | 1.63%   |
| 18     | 1         | 0.81%   |
| 12     | 1         | 0.81%   |
| 10     | 1         | 0.81%   |
| 9      | 1         | 0.81%   |
| 8      | 1         | 0.81%   |
| 5      | 1         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 76.67%  |
| Yes       | 28        | 23.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 94.12%  |
| No        | 7         | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 66.67%  |
| Yes       | 40        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 76.67%  |
| Yes       | 28        | 23.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 119       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Stockholm        | 15        | 11.36%  |
| Malmo            | 11        | 8.33%   |
| LinkГ¶ping     | 5         | 3.79%   |
| Bromma           | 5         | 3.79%   |
| VÃ¤sterÃ¥s   | 4         | 3.03%   |
| UmeГҐ          | 4         | 3.03%   |
| Taby             | 3         | 2.27%   |
| Sollentuna       | 3         | 2.27%   |
| JГ¶nkГ¶ping  | 3         | 2.27%   |
| Gothenburg       | 3         | 2.27%   |
| Umeå            | 2         | 1.52%   |
| Tyreso Strand    | 2         | 1.52%   |
| Tumba            | 2         | 1.52%   |
| Solleftea        | 2         | 1.52%   |
| Lund             | 2         | 1.52%   |
| Kungsbacka       | 2         | 1.52%   |
| Henan            | 2         | 1.52%   |
| Helsingborg      | 2         | 1.52%   |
| Bandhagen        | 2         | 1.52%   |
| Г…hus         | 1         | 0.76%   |
| Г„lvГ¤ngen  | 1         | 0.76%   |
| Västerås       | 1         | 0.76%   |
| Uppsala          | 1         | 0.76%   |
| Upplands Vasby   | 1         | 0.76%   |
| UmeÃ¥          | 1         | 0.76%   |
| Trosa            | 1         | 0.76%   |
| Trelleborg       | 1         | 0.76%   |
| Trangsund        | 1         | 0.76%   |
| Torsby           | 1         | 0.76%   |
| SГ¶dertГ¤lje | 1         | 0.76%   |
| Sundsvall        | 1         | 0.76%   |
| Sundbyberg       | 1         | 0.76%   |
| Stroemstad       | 1         | 0.76%   |
| Staffanstorp     | 1         | 0.76%   |
| Solna            | 1         | 0.76%   |
| Soeraker         | 1         | 0.76%   |
| SkГ¶vde        | 1         | 0.76%   |
| SkellefteÃ¥    | 1         | 0.76%   |
| SkÃ¶vde        | 1         | 0.76%   |
| Skaellinge       | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 36     | 17.57%  |
| Seagate             | 19        | 43     | 12.84%  |
| WDC                 | 15        | 23     | 10.14%  |
| Kingston            | 14        | 16     | 9.46%   |
| Intel               | 11        | 25     | 7.43%   |
| Hoodisk             | 10        | 13     | 6.76%   |
| SanDisk             | 7         | 8      | 4.73%   |
| Toshiba             | 6         | 15     | 4.05%   |
| NVMe                | 5         | 6      | 3.38%   |
| Crucial             | 4         | 12     | 2.7%    |
| Micron Technology   | 3         | 6      | 2.03%   |
| Hitachi             | 3         | 3      | 2.03%   |
| Hewlett-Packard     | 3         | 7      | 2.03%   |
| Transcend           | 2         | 2      | 1.35%   |
| SK hynix            | 2         | 2      | 1.35%   |
| Phison              | 2         | 2      | 1.35%   |
| Innodisk            | 2         | 3      | 1.35%   |
| HPE                 | 2         | 14     | 1.35%   |
| Apacer              | 2         | 2      | 1.35%   |
| XrayDisk            | 1         | 1      | 0.68%   |
| Supermicro          | 1         | 1      | 0.68%   |
| OCZ                 | 1         | 2      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| KingSpec            | 1         | 1      | 0.68%   |
| HGST                | 1         | 4      | 0.68%   |
| Fordisk             | 1         | 1      | 0.68%   |
| Dell                | 1         | 2      | 0.68%   |
| A-DATA Technology   | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB          | 4         | 2.44%   |
| SanDisk SDSA6MM-032G-1006 32GB       | 3         | 1.83%   |
| Hoodisk SSD 128GB                    | 3         | 1.83%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 2         | 1.22%   |
| Toshiba HDWQ140 4TB                  | 2         | 1.22%   |
| Samsung SSD 860 QVO 1TB              | 2         | 1.22%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.22%   |
| Samsung HD501LJ 500GB                | 2         | 1.22%   |
| Phison SATA SSD 16GB                 | 2         | 1.22%   |
| NVMe KBG40ZPZ256G TOS 256GB          | 2         | 1.22%   |
| Kingston SV300S37A240G 240GB         | 2         | 1.22%   |
| Intel SSDSC2BW240A4 240GB            | 2         | 1.22%   |
| Hoodisk SSD 64GB                     | 2         | 1.22%   |
| Hoodisk SSD 32GB                     | 2         | 1.22%   |
| Hoodisk SSD 16GB                     | 2         | 1.22%   |
| HP RAID 1(1+0) 240GB                 | 2         | 1.22%   |
| Crucial CT256MX100SSD1 256GB         | 2         | 1.22%   |
| Apacer 64GB SATA Flash Drive         | 2         | 1.22%   |
| XrayDisk SSD 64GB                    | 1         | 0.61%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.61%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.61%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.61%   |
| WDC WD82PURZ-85TEUY0 8TB             | 1         | 0.61%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.61%   |
| WDC WD6400AARS-00Y5B1 640GB          | 1         | 0.61%   |
| WDC WD5000AAKS-07V0A0 500GB          | 1         | 0.61%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.61%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 0.61%   |
| WDC WD2500AAJS-60B4A0 250GB          | 1         | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 0.61%   |
| WDC WD20EARX-00ZUDB0 2TB             | 1         | 0.61%   |
| WDC WD2002FYPS-02W3B0 2TB            | 1         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.61%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.61%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.61%   |
| Transcend TS256GMSA452T 256GB        | 1         | 0.61%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.61%   |
| Toshiba KPM5XVUG960G 960GB           | 1         | 0.61%   |
| Toshiba KPM5XMUG400G 400GB           | 1         | 0.61%   |
| Toshiba HDWR11A 10TB                 | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 41     | 36.73%  |
| WDC                 | 10        | 16     | 20.41%  |
| Toshiba             | 5         | 13     | 10.2%   |
| Samsung Electronics | 5         | 8      | 10.2%   |
| NVMe                | 3         | 4      | 6.12%   |
| Hitachi             | 3         | 3      | 6.12%   |
| Hewlett-Packard     | 3         | 7      | 6.12%   |
| HPE                 | 1         | 8      | 2.04%   |
| HGST                | 1         | 4      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 26     | 21.74%  |
| Kingston            | 14        | 16     | 15.22%  |
| Intel               | 10        | 23     | 10.87%  |
| Hoodisk             | 10        | 13     | 10.87%  |
| SanDisk             | 7         | 8      | 7.61%   |
| Crucial             | 4         | 12     | 4.35%   |
| Micron Technology   | 3         | 6      | 3.26%   |
| WDC                 | 2         | 4      | 2.17%   |
| SK hynix            | 2         | 2      | 2.17%   |
| Phison              | 2         | 2      | 2.17%   |
| NVMe                | 2         | 2      | 2.17%   |
| Innodisk            | 2         | 3      | 2.17%   |
| Apacer              | 2         | 2      | 2.17%   |
| XrayDisk            | 1         | 1      | 1.09%   |
| Transcend           | 1         | 1      | 1.09%   |
| Toshiba             | 1         | 2      | 1.09%   |
| Supermicro          | 1         | 1      | 1.09%   |
| Seagate             | 1         | 1      | 1.09%   |
| OCZ                 | 1         | 2      | 1.09%   |
| LITEONIT            | 1         | 1      | 1.09%   |
| LITEON              | 1         | 1      | 1.09%   |
| KingSpec            | 1         | 1      | 1.09%   |
| HPE                 | 1         | 6      | 1.09%   |
| Fordisk             | 1         | 1      | 1.09%   |
| Dell                | 1         | 2      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 81        | 139    | 62.79%  |
| HDD  | 38        | 104    | 29.46%  |
| NVMe | 10        | 10     | 7.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 243    | 91.38%  |
| NVMe | 10        | 10     | 8.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 144    | 68.66%  |
| 0.51-1.0   | 22        | 35     | 16.42%  |
| 3.01-4.0   | 8         | 24     | 5.97%   |
| 1.01-2.0   | 7         | 21     | 5.22%   |
| 4.01-10.0  | 5         | 19     | 3.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 53        | 44.17%  |
| 51-100         | 18        | 15%     |
| 21-50          | 15        | 12.5%   |
| 1-20           | 13        | 10.83%  |
| 251-500        | 10        | 8.33%   |
| 501-1000       | 6         | 5%      |
| 1001-2000      | 4         | 3.33%   |
| More than 3000 | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 103       | 84.43%  |
| 21-50   | 16        | 13.11%  |
| 251-500 | 2         | 1.64%   |
| 101-250 | 1         | 0.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 1      | 5%      |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 5%      |
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 5%      |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 5%      |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 5%      |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 5%      |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 5%      |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 5%      |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 5%      |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 5%      |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 5%      |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 5%      |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 5%      |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 5%      |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 5%      |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 5%      |
| Intel SSDSC2CT120A3 120GB                    | 1         | 1      | 5%      |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 5%      |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 38.89%  |
| WDC                 | 4         | 9      | 22.22%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| Hitachi             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| WDC                 | 4         | 9      | 33.33%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 17     | 64.71%  |
| SSD  | 6         | 6      | 35.29%  |

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
| Works    | 93        | 211    | 76.23%  |
| Malfunc  | 17        | 23     | 13.93%  |
| Detected | 12        | 19     | 9.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 62.59%  |
| AMD                      | 20        | 14.39%  |
| Broadcom / LSI           | 7         | 5.04%   |
| Samsung Electronics      | 4         | 2.88%   |
| Marvell Technology Group | 4         | 2.88%   |
| SanDisk                  | 3         | 2.16%   |
| Hewlett-Packard          | 3         | 2.16%   |
| KIOXIA                   | 2         | 1.44%   |
| ASMedia Technology       | 2         | 1.44%   |
| VIA Technologies         | 1         | 0.72%   |
| Silicon Motion           | 1         | 0.72%   |
| Seagate Technology       | 1         | 0.72%   |
| Realtek Semiconductor    | 1         | 0.72%   |
| Nvidia                   | 1         | 0.72%   |
| Dell                     | 1         | 0.72%   |
| Adaptec                  | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 9.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 5.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 4.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 3.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 3.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 2.41%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.81%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.81%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 1.81%   |
| AMD FCH IDE Controller                                                                  | 3         | 1.81%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.2%    |
| Intel SSD 660P Series                                                                   | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.2%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.2%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.2%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.2%    |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.2%    |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 2         | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.2%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.2%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.6%    |
| Seagate FireCuda 520 SSD                                                                | 1         | 0.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.6%    |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 94        | 64.38%  |
| IDE  | 19        | 13.01%  |
| NVMe | 15        | 10.27%  |
| RAID | 11        | 7.53%   |
| SAS  | 7         | 4.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 95        | 79.83%  |
| AMD     | 23        | 19.33%  |
| Unknown | 1         | 0.84%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 6         | 5.04%   |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 2.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 3         | 2.52%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 3         | 2.52%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 2.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 1.68%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 1.68%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 1.68%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 1.68%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 2         | 1.68%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.68%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 1.68%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.84%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.84%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.84%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.84%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.84%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.84%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.84%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.84%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.84%   |
| Intel Xeon CPU E5-2623 v4 @ 2.60GHz      | 1         | 0.84%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 1         | 0.84%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.84%   |
| Intel Xeon CPU E31240 @ 3.30GHz          | 1         | 0.84%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1         | 0.84%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz     | 1         | 0.84%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz     | 1         | 0.84%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz      | 1         | 0.84%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 1         | 0.84%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz      | 1         | 0.84%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 1         | 0.84%   |
| Intel Xeon CPU 5140 @ 2.33GHz            | 1         | 0.84%   |
| Intel Xeon                               | 1         | 0.84%   |
| Intel Pentium Dual-Core CPU E5700        | 1         | 0.84%   |
| Intel Pentium CPU G6950 @ 2.80GHz        | 1         | 0.84%   |
| Intel Pentium CPU G4400 @ 3.30GHz        | 1         | 0.84%   |
| Intel CPU Version                        | 1         | 0.84%   |
| Intel Core m3-8100Y CPU @ 1.10GHz        | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 26.05%  |
| Intel Xeon              | 19        | 15.97%  |
| Intel Core i7           | 16        | 13.45%  |
| Intel Celeron           | 10        | 8.4%    |
| AMD GX                  | 8         | 6.72%   |
| Other                   | 6         | 5.04%   |
| Intel Core i3           | 4         | 3.36%   |
| Intel Xeon Silver       | 3         | 2.52%   |
| Intel Core 2 Duo        | 3         | 2.52%   |
| AMD Ryzen 7             | 3         | 2.52%   |
| Intel Pentium           | 2         | 1.68%   |
| Intel Atom              | 2         | 1.68%   |
| AMD Ryzen 9             | 2         | 1.68%   |
| Intel Pentium Dual-Core | 1         | 0.84%   |
| Intel Core m3           | 1         | 0.84%   |
| Intel Core 2 Quad       | 1         | 0.84%   |
| AMD Ryzen Threadripper  | 1         | 0.84%   |
| AMD Ryzen 5 PRO         | 1         | 0.84%   |
| AMD G                   | 1         | 0.84%   |
| AMD FX                  | 1         | 0.84%   |
| AMD Athlon 64 X2        | 1         | 0.84%   |
| AMD Athlon              | 1         | 0.84%   |
| AMD A4                  | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 63        | 52.94%  |
| 2       | 32        | 26.89%  |
| 8       | 5         | 4.2%    |
| 6       | 5         | 4.2%    |
| Unknown | 5         | 4.2%    |
| 24      | 4         | 3.36%   |
| 16      | 3         | 2.52%   |
| 12      | 1         | 0.84%   |
| 10      | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 110       | 92.44%  |
| 2       | 6         | 5.04%   |
| Unknown | 3         | 2.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 63        | 52.94%  |
| 2       | 51        | 42.86%  |
| Unknown | 5         | 4.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 17        | 14.29%  |
| Haswell       | 16        | 13.45%  |
| SandyBridge   | 10        | 8.4%    |
| Silvermont    | 9         | 7.56%   |
| Puma          | 7         | 5.88%   |
| KabyLake      | 7         | 5.88%   |
| IvyBridge     | 7         | 5.88%   |
| Penryn        | 6         | 5.04%   |
| Westmere      | 5         | 4.2%    |
| Broadwell     | 5         | 4.2%    |
| Zen           | 3         | 2.52%   |
| Steamroller   | 3         | 2.52%   |
| Nehalem       | 3         | 2.52%   |
| IceLake       | 3         | 2.52%   |
| Core          | 3         | 2.52%   |
| Unknown       | 3         | 2.52%   |
| Zen 2         | 2         | 1.68%   |
| Jaguar        | 2         | 1.68%   |
| Goldmont plus | 2         | 1.68%   |
| Zen+          | 1         | 0.84%   |
| Piledriver    | 1         | 0.84%   |
| K8 Hammer     | 1         | 0.84%   |
| Goldmont      | 1         | 0.84%   |
| Excavator     | 1         | 0.84%   |
| Bobcat        | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 63        | 55.75%  |
| Nvidia                     | 17        | 15.04%  |
| Matrox Electronics Systems | 16        | 14.16%  |
| AMD                        | 15        | 13.27%  |
| ASPEED Technology          | 2         | 1.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 5.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 5.26%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 4.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 3.51%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 3.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.51%   |
| Intel HD Graphics 530                                                                    | 4         | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.51%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 2.63%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.63%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 2.63%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.75%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1.75%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.75%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.75%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1.75%   |
| Intel HD Graphics 620                                                                    | 2         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.75%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 1.75%   |
| AMD ES1000                                                                               | 2         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.75%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.88%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.88%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.88%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1         | 0.88%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.88%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 1         | 0.88%   |
| Intel UHD Graphics 615                                                                   | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 46.67%  |
| 1 x Matrox     | 16        | 13.33%  |
| 1 x Nvidia     | 15        | 12.5%   |
| 1 x AMD        | 14        | 11.67%  |
| Other          | 10        | 8.33%   |
| 2 x Intel      | 3         | 2.5%    |
| Intel + Nvidia | 2         | 1.67%   |
| Intel + AMD    | 2         | 1.67%   |
| 1 x ASPEED     | 2         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 96        | 80%     |
| Unknown     | 14        | 11.67%  |
| Proprietary | 10        | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 106       | 89.08%  |
| 1.01-2.0   | 5         | 4.2%    |
| 0.51-1.0   | 3         | 2.52%   |
| 3.01-4.0   | 2         | 1.68%   |
| 7.01-8.0   | 1         | 0.84%   |
| 5.01-6.0   | 1         | 0.84%   |
| 8.01-16.0  | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 15.22%  |
| LG Display              | 7         | 15.22%  |
| Hewlett-Packard         | 6         | 13.04%  |
| Chimei Innolux          | 6         | 13.04%  |
| Dell                    | 4         | 8.7%    |
| Philips                 | 2         | 4.35%   |
| Iiyama                  | 2         | 4.35%   |
| AOC                     | 2         | 4.35%   |
| Panasonic               | 1         | 2.17%   |
| LG Electronics          | 1         | 2.17%   |
| Lenovo Group Limited    | 1         | 2.17%   |
| Lenovo                  | 1         | 2.17%   |
| InfoVision              | 1         | 2.17%   |
| Gigabyte Technology     | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| BOE                     | 1         | 2.17%   |
| AU Optronics            | 1         | 2.17%   |
| Ancor Communications    | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 4%      |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 4%      |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 4%      |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 4%      |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 4%      |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 2%      |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 2%      |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 2%      |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 2%      |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 2%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 2%      |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 1         | 2%      |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 2%      |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 2%      |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 2%      |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 2%      |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 2%      |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 2%      |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 2%      |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 2%      |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 2%      |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 2%      |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 2%      |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 2%      |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 2%      |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 2%      |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 2%      |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 2%      |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 2%      |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 2%      |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1         | 2%      |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                    | 1         | 2%      |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch     | 1         | 2%      |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch     | 1         | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 12        | 26.09%  |
| 1920x1200 (WUXGA)  | 6         | 13.04%  |
| 1366x768 (WXGA)    | 6         | 13.04%  |
| 3840x2160 (4K)     | 5         | 10.87%  |
| 2560x1440 (QHD)    | 3         | 6.52%   |
| 1600x900 (HD+)     | 3         | 6.52%   |
| 3440x1440          | 2         | 4.35%   |
| 2736x1824          | 2         | 4.35%   |
| 3840x1080          | 1         | 2.17%   |
| 2880x1620          | 1         | 2.17%   |
| 1920x1280          | 1         | 2.17%   |
| 1680x1050 (WSXGA+) | 1         | 2.17%   |
| 1600x1200          | 1         | 2.17%   |
| 1440x900 (WXGA+)   | 1         | 2.17%   |
| Unknown            | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 20.93%  |
| Unknown | 6         | 13.95%  |
| 27      | 5         | 11.63%  |
| 24      | 4         | 9.3%    |
| 23      | 4         | 9.3%    |
| 13      | 3         | 6.98%   |
| 12      | 3         | 6.98%   |
| 21      | 2         | 4.65%   |
| 14      | 2         | 4.65%   |
| 34      | 1         | 2.33%   |
| 28      | 1         | 2.33%   |
| 17      | 1         | 2.33%   |
| 11      | 1         | 2.33%   |
| 10      | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 11        | 25.58%  |
| 301-350     | 11        | 25.58%  |
| 201-300     | 8         | 18.6%   |
| Unknown     | 6         | 13.95%  |
| 601-700     | 3         | 6.98%   |
| 401-500     | 2         | 4.65%   |
| 701-800     | 1         | 2.33%   |
| 351-400     | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 58.97%  |
| 16/10   | 6         | 15.38%  |
| Unknown | 6         | 15.38%  |
| 3/2     | 3         | 7.69%   |
| 21/9    | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 21.43%  |
| 201-250        | 6         | 14.29%  |
| Unknown        | 6         | 14.29%  |
| 301-350        | 5         | 11.9%   |
| 81-90          | 4         | 9.52%   |
| 61-70          | 3         | 7.14%   |
| 251-300        | 3         | 7.14%   |
| 51-60          | 2         | 4.76%   |
| 351-500        | 2         | 4.76%   |
| 71-80          | 1         | 2.38%   |
| 121-130        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 27.27%  |
| 101-120       | 8         | 18.18%  |
| 51-100        | 8         | 18.18%  |
| 161-240       | 6         | 13.64%  |
| Unknown       | 6         | 13.64%  |
| More than 240 | 2         | 4.55%   |
| 1-50          | 2         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 66.12%  |
| 1     | 32        | 26.45%  |
| 2     | 8         | 6.61%   |
| 3     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 89        | 53.29%  |
| Realtek Semiconductor    | 36        | 21.56%  |
| Broadcom                 | 22        | 13.17%  |
| Qualcomm Atheros         | 5         | 2.99%   |
| TP-Link                  | 2         | 1.2%    |
| Ralink Technology        | 2         | 1.2%    |
| Sierra Wireless          | 1         | 0.6%    |
| NetXen Incorporated      | 1         | 0.6%    |
| Microsoft                | 1         | 0.6%    |
| Mellanox Technologies    | 1         | 0.6%    |
| MediaTek                 | 1         | 0.6%    |
| Marvell Technology Group | 1         | 0.6%    |
| JMicron Technology       | 1         | 0.6%    |
| IMC Networks             | 1         | 0.6%    |
| Hewlett-Packard          | 1         | 0.6%    |
| Edimax Technology        | 1         | 0.6%    |
| Chelsio Communications   | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 15.94%  |
| Intel I210 Gigabit Network Connection                                         | 16        | 7.73%   |
| Intel I211 Gigabit Network Connection                                         | 13        | 6.28%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 3.86%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 3.38%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 2.9%    |
| Intel 82574L Gigabit Network Connection                                       | 5         | 2.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.42%   |
| Intel Wireless 7260                                                           | 4         | 1.93%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 1.93%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.93%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.45%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.97%   |
| Intel Wireless 8260                                                           | 2         | 0.97%   |
| Intel Wireless 7265                                                           | 2         | 0.97%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.97%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.97%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.97%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.97%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.97%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.97%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.48%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.48%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                 | 1         | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 53.49%  |
| Realtek Semiconductor | 5         | 11.63%  |
| Qualcomm Atheros      | 4         | 9.3%    |
| Broadcom              | 4         | 9.3%    |
| TP-Link               | 2         | 4.65%   |
| Ralink Technology     | 2         | 4.65%   |
| Sierra Wireless       | 1         | 2.33%   |
| IMC Networks          | 1         | 2.33%   |
| Edimax Technology     | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 4         | 9.09%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 6.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.55%   |
| Intel Wireless 8260                                            | 2         | 4.55%   |
| Intel Wireless 7265                                            | 2         | 4.55%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 4.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.55%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.27%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 2.27%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.27%   |
| Intel Wireless-AC 9260                                         | 1         | 2.27%   |
| Intel Wireless 3165                                            | 1         | 2.27%   |
| Intel WiFi Link 5100                                           | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.27%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 2.27%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 77        | 57.04%  |
| Realtek Semiconductor    | 36        | 26.67%  |
| Broadcom                 | 18        | 13.33%  |
| Qualcomm Atheros         | 1         | 0.74%   |
| Microsoft                | 1         | 0.74%   |
| Marvell Technology Group | 1         | 0.74%   |
| JMicron Technology       | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 20.89%  |
| Intel I210 Gigabit Network Connection                                         | 16        | 10.13%  |
| Intel I211 Gigabit Network Connection                                         | 13        | 8.23%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 5.06%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 4.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 3.8%    |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.16%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 3.16%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 2.53%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 2.53%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.53%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 2.53%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.9%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.9%    |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.27%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 1.27%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 1.27%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 1.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.63%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.63%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.63%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.63%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.63%   |
| Intel Ethernet Connection (14) I219-LM                                        | 1         | 0.63%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.63%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 112       | 71.34%  |
| WiFi     | 40        | 25.48%  |
| Unknown  | 4         | 2.55%   |
| Modem    | 1         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 81.89%  |
| WiFi     | 23        | 18.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 33.88%  |
| 1     | 20        | 16.53%  |
| 4     | 17        | 14.05%  |
| 3     | 16        | 13.22%  |
| 6     | 12        | 9.92%   |
| 5     | 7         | 5.79%   |
| 8     | 3         | 2.48%   |
| 7     | 3         | 2.48%   |
| 9     | 1         | 0.83%   |
| 0     | 1         | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 94.21%  |
| Yes  | 7         | 5.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 13        | 46.43%  |
| Cambridge Silicon Radio | 4         | 14.29%  |
| Broadcom                | 3         | 10.71%  |
| IMC Networks            | 2         | 7.14%   |
| Hewlett-Packard         | 2         | 7.14%   |
| Dell                    | 2         | 7.14%   |
| Lite-On Technology      | 1         | 3.57%   |
| Apple                   | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 7         | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 14.29%  |
| Intel AX201 Bluetooth                                   | 2         | 7.14%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 7.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 3.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.57%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 3.57%   |
| Intel AX200 Bluetooth                                   | 1         | 3.57%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 3.57%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 3.57%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 3.57%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 3.57%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 3.57%   |
| Dell Dell Wireless 355C Bluetooth 2.0 + EDR module      | 1         | 3.57%   |
| Broadcom Broadcom Bluetooth 4.0 Adapter                 | 1         | 3.57%   |
| Apple Apple Broadcom Built-in Bluetooth                 | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 62        | 63.92%  |
| AMD              | 17        | 17.53%  |
| Nvidia           | 15        | 15.46%  |
| Philips (or NXP) | 1         | 1.03%   |
| Lenovo           | 1         | 1.03%   |
| GN Netcom        | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 6.78%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 5.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 5.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 4.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 4.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.39%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.39%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.39%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 2.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.54%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 2.54%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 2.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 2.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.69%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.85%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.85%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.85%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 18.1%   |
| SK hynix            | 18        | 15.52%  |
| Corsair             | 17        | 14.66%  |
| Unknown             | 13        | 11.21%  |
| Kingston            | 13        | 11.21%  |
| Micron Technology   | 12        | 10.34%  |
| Crucial             | 4         | 3.45%   |
| Hewlett-Packard     | 3         | 2.59%   |
| Elpida              | 3         | 2.59%   |
| Unknown             | 3         | 2.59%   |
| HPE                 | 2         | 1.72%   |
| G.Skill             | 2         | 1.72%   |
| Toshiba             | 1         | 0.86%   |
| Tigo                | 1         | 0.86%   |
| Kimtigo             | 1         | 0.86%   |
| ASint Technology    | 1         | 0.86%   |
| Apacer              | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 5         | 3.97%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s         | 4         | 3.17%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 3         | 2.38%   |
| Unknown                                                     | 3         | 2.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.59%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 2         | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.59%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 2         | 1.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.59%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1         | 0.79%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                  | 1         | 0.79%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s                | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.79%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s                | 1         | 0.79%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                    | 1         | 0.79%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 1         | 0.79%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                  | 1         | 0.79%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s                | 1         | 0.79%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s        | 1         | 0.79%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s         | 1         | 0.79%   |
| Tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                  | 1         | 0.79%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 0.79%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.79%   |
| SK hynix RAM HMT351U7EFR8C-RD 4GB DIMM DDR3                 | 1         | 0.79%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.79%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.79%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2666MT/s       | 1         | 0.79%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 0.79%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s        | 1         | 0.79%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                   | 1         | 0.79%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 0.79%   |
| Samsung RAM M471B5173BH0-YK0 4GB DIMM DDR3 1600MT/s         | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 61        | 59.22%  |
| DDR4    | 30        | 29.13%  |
| DDR2    | 7         | 6.8%    |
| Unknown | 2         | 1.94%   |
| SDRAM   | 1         | 0.97%   |
| LPDDR3  | 1         | 0.97%   |
| DRAM    | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 63        | 60.58%  |
| SODIMM  | 38        | 36.54%  |
| FB-DIMM | 2         | 1.92%   |
| Chip    | 1         | 0.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 45        | 40.54%  |
| 8192  | 28        | 25.23%  |
| 16384 | 16        | 14.41%  |
| 2048  | 13        | 11.71%  |
| 1024  | 6         | 5.41%   |
| 32768 | 3         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 31.13%  |
| 1333    | 26        | 24.53%  |
| 2133    | 10        | 9.43%   |
| 2667    | 9         | 8.49%   |
| 2400    | 5         | 4.72%   |
| 800     | 5         | 4.72%   |
| 2666    | 4         | 3.77%   |
| 667     | 4         | 3.77%   |
| 3200    | 3         | 2.83%   |
| Unknown | 3         | 2.83%   |
| 1867    | 1         | 0.94%   |
| 1334    | 1         | 0.94%   |
| 1332    | 1         | 0.94%   |
| 333     | 1         | 0.94%   |

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
| Validity Sensors | 2         | 25%     |
| Upek             | 2         | 25%     |
| AuthenTec        | 2         | 25%     |
| Synaptics        | 1         | 12.5%   |
| Broadcom         | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 25%     |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 12.5%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| AuthenTec AES2810                                                            | 1         | 12.5%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 12.5%   |

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
| 1     | 48        | 39.67%  |
| 0     | 40        | 33.06%  |
| 2     | 22        | 18.18%  |
| 3     | 6         | 4.96%   |
| 4     | 3         | 2.48%   |
| 5     | 2         | 1.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 70        | 66.04%  |
| Net/wireless             | 9         | 8.49%   |
| Fingerprint reader       | 6         | 5.66%   |
| Card reader              | 6         | 5.66%   |
| Firewire controller      | 4         | 3.77%   |
| Graphics card            | 3         | 2.83%   |
| Storage/ata              | 2         | 1.89%   |
| Sound                    | 2         | 1.89%   |
| Network                  | 2         | 1.89%   |
| Net/ethernet             | 1         | 0.94%   |
| Bluetooth                | 1         | 0.94%   |

