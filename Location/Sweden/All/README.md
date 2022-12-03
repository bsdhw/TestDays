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

Total: 176

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ACMA          | X8SIE                       | Desktop     | [532b81e55f](https://bsd-hardware.info/?probe=532b81e55f) | Nov 29, 2022 |
| ACMA          | X8SIE                       | Desktop     | [d0112d027b](https://bsd-hardware.info/?probe=d0112d027b) | Nov 28, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [e850e0ae9c](https://bsd-hardware.info/?probe=e850e0ae9c) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [bd1f1fa769](https://bsd-hardware.info/?probe=bd1f1fa769) | Nov 26, 2022 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [2959091a59](https://bsd-hardware.info/?probe=2959091a59) | Nov 25, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [0dd05e08aa](https://bsd-hardware.info/?probe=0dd05e08aa) | Nov 12, 2022 |
| Lenovo        | ThinkServer RS140           | Desktop     | [b2b1509adf](https://bsd-hardware.info/?probe=b2b1509adf) | Nov 11, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | Desktop     | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [970443066b](https://bsd-hardware.info/?probe=970443066b) | Nov 07, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [7f848d7c57](https://bsd-hardware.info/?probe=7f848d7c57) | Oct 22, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [d7c3749eba](https://bsd-hardware.info/?probe=d7c3749eba) | Oct 13, 2022 |
| HP            | 8103 A01                    | Mini pc     | [f187229469](https://bsd-hardware.info/?probe=f187229469) | Oct 09, 2022 |
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
| Gigabyte      | G31M-ES2C                   | Desktop     | [5f27a360e4](https://bsd-hardware.info/?probe=5f27a360e4) | Feb 10, 2022 |
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
| Lenovo        | ThinkServer RS140           | Desktop     | [e28b542e9e](https://bsd-hardware.info/?probe=e28b542e9e) | Dec 23, 2021 |
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 21.1        | 11        | 7.59%   |
| OPNsense 21.7.7      | 6         | 4.14%   |
| OPNsense 21.1.3      | 6         | 4.14%   |
| OpenBSD 6.8          | 6         | 4.14%   |
| OPNsense 21.1.5      | 5         | 3.45%   |
| OPNsense 21.1.2      | 5         | 3.45%   |
| OpenBSD 7.0          | 5         | 3.45%   |
| helloSystem 0.5.0    | 5         | 3.45%   |
| OPNsense 22.7.8      | 4         | 2.76%   |
| OPNsense 21.1.8      | 4         | 2.76%   |
| OPNsense 22.7.2      | 3         | 2.07%   |
| OPNsense 22.1.8      | 3         | 2.07%   |
| OPNsense 21.7.3      | 3         | 2.07%   |
| OPNsense 21.7.1      | 3         | 2.07%   |
| OPNsense 20.7.8      | 3         | 2.07%   |
| OpenBSD 6.9          | 3         | 2.07%   |
| helloSystem 0.7.0    | 3         | 2.07%   |
| FreeBSD 13.0-p7      | 3         | 2.07%   |
| FreeBSD 12.1-p8      | 3         | 2.07%   |
| OPNsense 22.7.7      | 2         | 1.38%   |
| OPNsense 22.7.6      | 2         | 1.38%   |
| OPNsense 22.1.9      | 2         | 1.38%   |
| OPNsense 22.1.6      | 2         | 1.38%   |
| OPNsense 22.1.3      | 2         | 1.38%   |
| OPNsense 22.1.1      | 2         | 1.38%   |
| OPNsense 21.7.6      | 2         | 1.38%   |
| OPNsense 21.7        | 2         | 1.38%   |
| OPNsense 21.1.7      | 2         | 1.38%   |
| OPNsense 21.1.6      | 2         | 1.38%   |
| OpenBSD 6.7          | 2         | 1.38%   |
| helloSystem 0.4.0    | 2         | 1.38%   |
| FreeBSD 14.0-CURRENT | 2         | 1.38%   |
| FreeBSD 12.2-p4      | 2         | 1.38%   |
| FreeBSD 12.2-p2      | 2         | 1.38%   |
| pfSense 2.5.0        | 1         | 0.69%   |
| OPNsense 22.7.5      | 1         | 0.69%   |
| OPNsense 22.7        | 1         | 0.69%   |
| OPNsense 22.1.7      | 1         | 0.69%   |
| OPNsense 22.1.5      | 1         | 0.69%   |
| OPNsense 22.1.4      | 1         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 72        | 56.69%  |
| FreeBSD     | 23        | 18.11%  |
| OpenBSD     | 15        | 11.81%  |
| helloSystem | 11        | 8.66%   |
| GhostBSD    | 4         | 3.15%   |
| pfSense     | 1         | 0.79%   |
| FuryBSD     | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 126       | 99.21%  |
| octeon | 1         | 0.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 85        | 65.89%  |
| fvwm         | 12        | 9.3%    |
| helloDesktop | 11        | 8.53%   |
| KDE5         | 10        | 7.75%   |
| MATE         | 4         | 3.1%    |
| i3           | 2         | 1.55%   |
| xfwm         | 1         | 0.78%   |
| XFCE         | 1         | 0.78%   |
| TWM          | 1         | 0.78%   |
| Mutter       | 1         | 0.78%   |
| AwesomeWM    | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 86        | 67.72%  |
| X11     | 41        | 32.28%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 97        | 74.62%  |
| SLiM    | 12        | 9.23%   |
| SDDM    | 9         | 6.92%   |
| LightDM | 6         | 4.62%   |
| GDM     | 4         | 3.08%   |
| XDM     | 2         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 87        | 67.44%  |
| en_US          | 23        | 17.83%  |
| C              | 13        | 10.08%  |
| sv_SE          | 4         | 3.1%    |
| sv_SE.US-ASCII | 1         | 0.78%   |
| en_CA          | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 105       | 81.4%   |
| BIOS | 24        | 18.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 67        | 52.34%  |
| Zfs    | 44        | 34.38%  |
| Ffs    | 15        | 11.72%  |
| Cd9660 | 2         | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 114       | 87.69%  |
| MBR  | 16        | 12.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 18        | 14.17%  |
| Hewlett-Packard            | 15        | 11.81%  |
| Lenovo                     | 14        | 11.02%  |
| ASUSTek Computer           | 14        | 11.02%  |
| PC Engines                 | 7         | 5.51%   |
| Intel                      | 7         | 5.51%   |
| Gigabyte Technology        | 7         | 5.51%   |
| Unknown                    | 7         | 5.51%   |
| MSI                        | 5         | 3.94%   |
| AMI                        | 5         | 3.94%   |
| Microsoft                  | 3         | 2.36%   |
| ASRock                     | 3         | 2.36%   |
| Toshiba                    | 2         | 1.57%   |
| Supermicro                 | 2         | 1.57%   |
| Shuttle                    | 2         | 1.57%   |
| HPE                        | 2         | 1.57%   |
| Fujitsu                    | 2         | 1.57%   |
| Wistron                    | 1         | 0.79%   |
| Sony                       | 1         | 0.79%   |
| ShenZhen MinWin Technology | 1         | 0.79%   |
| Protectli                  | 1         | 0.79%   |
| Google                     | 1         | 0.79%   |
| Fujitsu Siemens            | 1         | 0.79%   |
| Deciso                     | 1         | 0.79%   |
| Cisco                      | 1         | 0.79%   |
| AOpen                      | 1         | 0.79%   |
| ADI                        | 1         | 0.79%   |
| ACMA                       | 1         | 0.79%   |
| Acer                       | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 8         | 6.3%    |
| PC Engines APU2                   | 4         | 3.15%   |
| AMI Aptio CRB                     | 4         | 3.15%   |
| HP t730 Thin Client               | 3         | 2.36%   |
| ASUS All Series                   | 3         | 2.36%   |
| PC Engines apu4                   | 2         | 1.57%   |
| Microsoft Surface Pro 7           | 2         | 1.57%   |
| Intel CRESCENTBAY                 | 2         | 1.57%   |
| Dell PowerEdge R210 II            | 2         | 1.57%   |
| Dell PowerEdge R210               | 2         | 1.57%   |
| Dell OptiPlex 9020                | 2         | 1.57%   |
| Wistron ProLiant ML110 G6         | 1         | 0.79%   |
| Toshiba TECRA Z40-C-12Z           | 1         | 0.79%   |
| Toshiba Satellite L450            | 1         | 0.79%   |
| Supermicro SYS-1019S-MP           | 1         | 0.79%   |
| Supermicro Super Server           | 1         | 0.79%   |
| Sony SVP1322M1EBI                 | 1         | 0.79%   |
| Shuttle SH570                     | 1         | 0.79%   |
| Shuttle DH170                     | 1         | 0.79%   |
| ShenZhen MinWin MW-NANO-APL-4L    | 1         | 0.79%   |
| Protectli FW4B                    | 1         | 0.79%   |
| PC Engines APU                    | 1         | 0.79%   |
| MSI WC776AA-UUW HPE-110sc         | 1         | 0.79%   |
| MSI MS-7C56                       | 1         | 0.79%   |
| MSI MS-7B43                       | 1         | 0.79%   |
| MSI MS-7918                       | 1         | 0.79%   |
| MSI MS-7369                       | 1         | 0.79%   |
| Microsoft Surface Go 2            | 1         | 0.79%   |
| Lenovo V130-15IGM 81HL            | 1         | 0.79%   |
| Lenovo ThinkPad X395 20NL001SMX   | 1         | 0.79%   |
| Lenovo ThinkPad X250 20CLS4JH00   | 1         | 0.79%   |
| Lenovo ThinkPad X201 3680FAG      | 1         | 0.79%   |
| Lenovo ThinkPad W520 4284GN2      | 1         | 0.79%   |
| Lenovo ThinkPad T460s 20FAS4KH02  | 1         | 0.79%   |
| Lenovo ThinkPad T420 4236MBG      | 1         | 0.79%   |
| Lenovo ThinkPad T400 2767WSB      | 1         | 0.79%   |
| Lenovo ThinkPad L560 20F10032MS   | 1         | 0.79%   |
| Lenovo ThinkCentre M92p 2988B1G   | 1         | 0.79%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1         | 0.79%   |
| Lenovo ThinkCentre E73 10AS002QMX | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell PowerEdge                 | 11        | 8.66%   |
| Lenovo ThinkPad                | 8         | 6.3%    |
| Unknown                        | 8         | 6.3%    |
| PC Engines APU2                | 4         | 3.15%   |
| HP ProLiant                    | 4         | 3.15%   |
| Dell OptiPlex                  | 4         | 3.15%   |
| AMI Aptio                      | 4         | 3.15%   |
| Microsoft Surface              | 3         | 2.36%   |
| Lenovo ThinkCentre             | 3         | 2.36%   |
| HP t730                        | 3         | 2.36%   |
| Dell Latitude                  | 3         | 2.36%   |
| ASUS All                       | 3         | 2.36%   |
| PC Engines apu4                | 2         | 1.57%   |
| Intel CRESCENTBAY              | 2         | 1.57%   |
| HPE ProLiant                   | 2         | 1.57%   |
| HP EliteDesk                   | 2         | 1.57%   |
| Wistron ProLiant               | 1         | 0.79%   |
| Toshiba TECRA                  | 1         | 0.79%   |
| Toshiba Satellite              | 1         | 0.79%   |
| Supermicro SYS-1019S-MP        | 1         | 0.79%   |
| Supermicro Super               | 1         | 0.79%   |
| Sony SVP1322M1EBI              | 1         | 0.79%   |
| Shuttle SH570                  | 1         | 0.79%   |
| Shuttle DH170                  | 1         | 0.79%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.79%   |
| Protectli FW4B                 | 1         | 0.79%   |
| PC Engines APU                 | 1         | 0.79%   |
| MSI WC776AA-UUW                | 1         | 0.79%   |
| MSI MS-7C56                    | 1         | 0.79%   |
| MSI MS-7B43                    | 1         | 0.79%   |
| MSI MS-7918                    | 1         | 0.79%   |
| MSI MS-7369                    | 1         | 0.79%   |
| Lenovo V130-15IGM              | 1         | 0.79%   |
| Lenovo Legion                  | 1         | 0.79%   |
| Lenovo 70F3S00K00              | 1         | 0.79%   |
| Intel Q3XXG4-P                 | 1         | 0.79%   |
| Intel NUC5CPYB                 | 1         | 0.79%   |
| Intel DQ67SW                   | 1         | 0.79%   |
| Intel DH61AG                   | 1         | 0.79%   |
| Intel D54250WYK                | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 15        | 11.81%  |
| 2018    | 14        | 11.02%  |
| 2016    | 13        | 10.24%  |
| 2017    | 11        | 8.66%   |
| 2014    | 11        | 8.66%   |
| 2010    | 11        | 8.66%   |
| 2019    | 10        | 7.87%   |
| 2021    | 9         | 7.09%   |
| 2015    | 9         | 7.09%   |
| 2013    | 6         | 4.72%   |
| 2012    | 6         | 4.72%   |
| 2009    | 6         | 4.72%   |
| 2011    | 2         | 1.57%   |
| 2022    | 1         | 0.79%   |
| 2007    | 1         | 0.79%   |
| 2006    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 75        | 59.06%  |
| Notebook | 25        | 19.69%  |
| Server   | 16        | 12.6%   |
| Mini pc  | 8         | 6.3%    |
| Tablet   | 3         | 2.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 117       | 92.13%  |
| Yes  | 10        | 7.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 42        | 32.31%  |
| 4.01-8.0        | 33        | 25.38%  |
| 16.01-24.0      | 22        | 16.92%  |
| 32.01-64.0      | 13        | 10%     |
| 64.01-256.0     | 6         | 4.62%   |
| 24.01-32.0      | 4         | 3.08%   |
| 2.01-3.0        | 4         | 3.08%   |
| More than 256.0 | 3         | 2.31%   |
| 3.01-4.0        | 2         | 1.54%   |
| 1.01-2.0        | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 68        | 51.91%  |
| 0.51-1.0    | 36        | 27.48%  |
| 1.01-2.0    | 14        | 10.69%  |
| 4.01-8.0    | 4         | 3.05%   |
| 2.01-3.0    | 3         | 2.29%   |
| 3.01-4.0    | 2         | 1.53%   |
| 24.01-32.0  | 2         | 1.53%   |
| 64.01-256.0 | 2         | 1.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 67.94%  |
| 2      | 12        | 9.16%   |
| 0      | 9         | 6.87%   |
| 3      | 7         | 5.34%   |
| 6      | 3         | 2.29%   |
| 4      | 3         | 2.29%   |
| 11     | 2         | 1.53%   |
| 18     | 1         | 0.76%   |
| 12     | 1         | 0.76%   |
| 10     | 1         | 0.76%   |
| 9      | 1         | 0.76%   |
| 8      | 1         | 0.76%   |
| 5      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 77.34%  |
| Yes       | 29        | 22.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 94.49%  |
| No        | 7         | 5.51%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 67.19%  |
| Yes       | 42        | 32.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 77.34%  |
| Yes       | 29        | 22.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 127       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Stockholm             | 15        | 10.71%  |
| Malmo                 | 11        | 7.86%   |
| LinkГ¶ping          | 5         | 3.57%   |
| Bromma                | 5         | 3.57%   |
| VÃ¤sterÃ¥s        | 4         | 2.86%   |
| UmeГҐ               | 4         | 2.86%   |
| Taby                  | 3         | 2.14%   |
| Sollentuna            | 3         | 2.14%   |
| JГ¶nkГ¶ping       | 3         | 2.14%   |
| Gothenburg            | 3         | 2.14%   |
| Bandhagen             | 3         | 2.14%   |
| Umeå                 | 2         | 1.43%   |
| Tyreso Strand         | 2         | 1.43%   |
| Tumba                 | 2         | 1.43%   |
| Solleftea             | 2         | 1.43%   |
| Piteå                | 2         | 1.43%   |
| Lund                  | 2         | 1.43%   |
| Kungsbacka            | 2         | 1.43%   |
| Henan                 | 2         | 1.43%   |
| Helsingborg           | 2         | 1.43%   |
| Enskede-Arsta-Vantoer | 2         | 1.43%   |
| Г…hus              | 1         | 0.71%   |
| Г„lvГ¤ngen       | 1         | 0.71%   |
| Vaxjo                 | 1         | 0.71%   |
| Västerås            | 1         | 0.71%   |
| Uppsala               | 1         | 0.71%   |
| Upplands Vasby        | 1         | 0.71%   |
| UmeÃ¥               | 1         | 0.71%   |
| Trosa                 | 1         | 0.71%   |
| Trelleborg            | 1         | 0.71%   |
| Trangsund             | 1         | 0.71%   |
| Torsby                | 1         | 0.71%   |
| SГ¶dertГ¤lje      | 1         | 0.71%   |
| Sundsvall             | 1         | 0.71%   |
| Sundbyberg            | 1         | 0.71%   |
| Stroemstad            | 1         | 0.71%   |
| Staffanstorp          | 1         | 0.71%   |
| Solna                 | 1         | 0.71%   |
| Soeraker              | 1         | 0.71%   |
| SkГ¶vde             | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 38     | 17.09%  |
| Seagate             | 19        | 43     | 12.03%  |
| WDC                 | 16        | 24     | 10.13%  |
| Kingston            | 15        | 17     | 9.49%   |
| Intel               | 13        | 27     | 8.23%   |
| Hoodisk             | 11        | 14     | 6.96%   |
| Toshiba             | 7         | 16     | 4.43%   |
| SanDisk             | 7         | 9      | 4.43%   |
| NVMe                | 5         | 6      | 3.16%   |
| Crucial             | 5         | 13     | 3.16%   |
| Micron Technology   | 3         | 6      | 1.9%    |
| Hitachi             | 3         | 3      | 1.9%    |
| Hewlett-Packard     | 3         | 7      | 1.9%    |
| Transcend           | 2         | 2      | 1.27%   |
| SK hynix            | 2         | 2      | 1.27%   |
| Phison              | 2         | 2      | 1.27%   |
| Innodisk            | 2         | 3      | 1.27%   |
| HPE                 | 2         | 14     | 1.27%   |
| Apacer              | 2         | 2      | 1.27%   |
| XrayDisk            | 1         | 1      | 0.63%   |
| Supermicro          | 1         | 1      | 0.63%   |
| OCZ                 | 1         | 2      | 0.63%   |
| MARVELL             | 1         | 1      | 0.63%   |
| LITEONIT            | 1         | 1      | 0.63%   |
| LITEON              | 1         | 1      | 0.63%   |
| KingSpec            | 1         | 1      | 0.63%   |
| HGST                | 1         | 4      | 0.63%   |
| Fordisk             | 1         | 1      | 0.63%   |
| Dell                | 1         | 2      | 0.63%   |
| Corsair             | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB          | 4         | 2.29%   |
| SanDisk SDSA6MM-032G-1006 32GB       | 3         | 1.71%   |
| Samsung SSD 860 QVO 1TB              | 3         | 1.71%   |
| Hoodisk SSD 64GB                     | 3         | 1.71%   |
| Hoodisk SSD 128GB                    | 3         | 1.71%   |
| WDC WD5000AZLX-60K2TA0 500GB         | 2         | 1.14%   |
| Toshiba HDWQ140 4TB                  | 2         | 1.14%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.14%   |
| Samsung HD501LJ 500GB                | 2         | 1.14%   |
| Phison SATA SSD 16GB                 | 2         | 1.14%   |
| NVMe KBG40ZPZ256G TOS 256GB          | 2         | 1.14%   |
| Kingston SV300S37A240G 240GB         | 2         | 1.14%   |
| Kingston SA400S37240G 240GB          | 2         | 1.14%   |
| Intel SSDSC2BW240A4 240GB            | 2         | 1.14%   |
| Hoodisk SSD 32GB                     | 2         | 1.14%   |
| Hoodisk SSD 16GB                     | 2         | 1.14%   |
| HP RAID 1(1+0) 119GB                 | 2         | 1.14%   |
| Crucial CT256MX100SSD1 256GB         | 2         | 1.14%   |
| Apacer 64GB SATA Flash Drive         | 2         | 1.14%   |
| XrayDisk SSD 64GB                    | 1         | 0.57%   |
| WDC WDS250G2B0C-00PXH0 250GB         | 1         | 0.57%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.57%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.57%   |
| WDC WD82PURZ-85TEUY0 8TB             | 1         | 0.57%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.57%   |
| WDC WD6400AARS-00Y5B1 640GB          | 1         | 0.57%   |
| WDC WD5000AAKS-07V0A0 500GB          | 1         | 0.57%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1         | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.57%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 0.57%   |
| WDC WD2500AAJS-60B4A0 250GB          | 1         | 0.57%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 0.57%   |
| WDC WD20EARX-00ZUDB0 2TB             | 1         | 0.57%   |
| WDC WD2002FYPS-02W3B0 2TB            | 1         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.57%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.57%   |
| Transcend TS256GMSA452T 256GB        | 1         | 0.57%   |
| Transcend TS128GMTE110S 128GB        | 1         | 0.57%   |
| Toshiba KSG60ZMV256G 256GB           | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 41     | 37.5%   |
| WDC                 | 11        | 17     | 22.92%  |
| Toshiba             | 5         | 13     | 10.42%  |
| Samsung Electronics | 5         | 8      | 10.42%  |
| NVMe                | 3         | 4      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| HPE                 | 1         | 8      | 2.08%   |
| HGST                | 1         | 4      | 2.08%   |
| Hewlett-Packard     | 1         | 5      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 27     | 20.39%  |
| Kingston            | 15        | 17     | 14.56%  |
| Intel               | 12        | 25     | 11.65%  |
| Hoodisk             | 11        | 14     | 10.68%  |
| SanDisk             | 7         | 9      | 6.8%    |
| Crucial             | 5         | 13     | 4.85%   |
| Micron Technology   | 3         | 6      | 2.91%   |
| WDC                 | 2         | 4      | 1.94%   |
| Toshiba             | 2         | 3      | 1.94%   |
| SK hynix            | 2         | 2      | 1.94%   |
| Phison              | 2         | 2      | 1.94%   |
| NVMe                | 2         | 2      | 1.94%   |
| Innodisk            | 2         | 3      | 1.94%   |
| Hewlett-Packard     | 2         | 2      | 1.94%   |
| Apacer              | 2         | 2      | 1.94%   |
| XrayDisk            | 1         | 1      | 0.97%   |
| Transcend           | 1         | 1      | 0.97%   |
| Supermicro          | 1         | 1      | 0.97%   |
| Seagate             | 1         | 1      | 0.97%   |
| OCZ                 | 1         | 2      | 0.97%   |
| MARVELL             | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| LITEON              | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| HPE                 | 1         | 6      | 0.97%   |
| Fordisk             | 1         | 1      | 0.97%   |
| Dell                | 1         | 2      | 0.97%   |
| Corsair             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 90        | 151    | 65.22%  |
| HDD  | 37        | 103    | 26.81%  |
| NVMe | 11        | 11     | 7.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 254    | 91.13%  |
| NVMe | 11        | 11     | 8.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 154    | 69.93%  |
| 0.51-1.0   | 23        | 36     | 16.08%  |
| 3.01-4.0   | 8         | 24     | 5.59%   |
| 1.01-2.0   | 7         | 21     | 4.9%    |
| 4.01-10.0  | 5         | 19     | 3.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 43.08%  |
| 51-100         | 18        | 13.85%  |
| 21-50          | 17        | 13.08%  |
| 1-20           | 16        | 12.31%  |
| 251-500        | 12        | 9.23%   |
| 501-1000       | 6         | 4.62%   |
| 1001-2000      | 4         | 3.08%   |
| More than 3000 | 1         | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 111       | 85.38%  |
| 21-50   | 16        | 12.31%  |
| 251-500 | 2         | 1.54%   |
| 101-250 | 1         | 0.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB                  | 1         | 1      | 4.55%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 4.55%   |
| WDC WD2500AAJS-60B4A0 250GB                  | 1         | 2      | 4.55%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 4.55%   |
| WDC WD20EARX-00ZUDB0 2TB                     | 1         | 1      | 4.55%   |
| WDC WD2002FYPS-02W3B0 2TB                    | 1         | 1      | 4.55%   |
| SK hynix HFS128G32MND-2200A 128GB            | 1         | 1      | 4.55%   |
| Seagate ST9640320AS 640GB                    | 1         | 1      | 4.55%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 4.55%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 4.55%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 4.55%   |
| Seagate ST100FN0021 100GB                    | 1         | 1      | 4.55%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 4.55%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 4.55%   |
| Samsung Electronics HD321KJ 320GB            | 1         | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 4.55%   |
| Intel SSDSC2CT120A3 120GB                    | 1         | 1      | 4.55%   |
| Intel SSDSC2CT060A3 64GB                     | 1         | 1      | 4.55%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 4.55%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 35%     |
| WDC                 | 4         | 9      | 20%     |
| Samsung Electronics | 3         | 3      | 15%     |
| Intel               | 3         | 3      | 15%     |
| SK hynix            | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Hitachi             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| WDC                 | 4         | 9      | 33.33%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 17     | 57.89%  |
| SSD  | 7         | 7      | 36.84%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 101       | 221    | 76.52%  |
| Malfunc  | 19        | 25     | 14.39%  |
| Detected | 12        | 19     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 64%     |
| AMD                      | 20        | 13.33%  |
| Broadcom / LSI           | 7         | 4.67%   |
| Samsung Electronics      | 5         | 3.33%   |
| Marvell Technology Group | 4         | 2.67%   |
| SanDisk                  | 3         | 2%      |
| Hewlett-Packard          | 3         | 2%      |
| KIOXIA                   | 2         | 1.33%   |
| ASMedia Technology       | 2         | 1.33%   |
| VIA Technologies         | 1         | 0.67%   |
| Silicon Motion           | 1         | 0.67%   |
| Seagate Technology       | 1         | 0.67%   |
| Realtek Semiconductor    | 1         | 0.67%   |
| Nvidia                   | 1         | 0.67%   |
| Dell                     | 1         | 0.67%   |
| Adaptec                  | 1         | 0.67%   |
| 3ware                    | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 8.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 3.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 3.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.67%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.67%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 1.67%   |
| AMD FCH IDE Controller                                                                  | 3         | 1.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.11%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 1.11%   |
| Intel SSD 660P Series                                                                   | 2         | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.11%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 1.11%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 1.11%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.11%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.11%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                     | 2         | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.11%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 100       | 63.69%  |
| IDE  | 22        | 14.01%  |
| NVMe | 16        | 10.19%  |
| RAID | 12        | 7.64%   |
| SAS  | 7         | 4.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 104       | 81.25%  |
| AMD     | 23        | 17.97%  |
| Unknown | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 6         | 4.65%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 4         | 3.1%    |
| Intel Core i7-4770K CPU @ 3.50GHz        | 3         | 2.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 3         | 2.33%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 2.33%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz      | 2         | 1.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 1.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 1.55%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz       | 2         | 1.55%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 1.55%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2         | 1.55%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 2         | 1.55%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.55%   |
| AMD Ryzen 7 1700 Eight-Core Processor    | 2         | 1.55%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz     | 1         | 0.78%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz     | 1         | 0.78%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz     | 1         | 0.78%   |
| Intel Xeon E-2224 CPU @ 3.40GHz          | 1         | 0.78%   |
| Intel Xeon CPU X5680 @ 3.33GHz           | 1         | 0.78%   |
| Intel Xeon CPU X3470 @ 2.93GHz           | 1         | 0.78%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 1         | 0.78%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.78%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.78%   |
| Intel Xeon CPU E5450 @ 3.00GHz           | 1         | 0.78%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz       | 1         | 0.78%   |
| Intel Xeon CPU E5-2623 v4 @ 2.60GHz      | 1         | 0.78%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz      | 1         | 0.78%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz       | 1         | 0.78%   |
| Intel Xeon CPU E31240 @ 3.30GHz          | 1         | 0.78%   |
| Intel Xeon CPU E31220 @ 3.10GHz          | 1         | 0.78%   |
| Intel Xeon CPU E3-1515M v5 @ 2.80GHz     | 1         | 0.78%   |
| Intel Xeon CPU E3-1230L v3 @ 1.80GHz     | 1         | 0.78%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz      | 1         | 0.78%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz      | 1         | 0.78%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 1         | 0.78%   |
| Intel Xeon CPU 5140 @ 2.33GHz            | 1         | 0.78%   |
| Intel Xeon                               | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU E5700        | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 26.36%  |
| Intel Xeon              | 22        | 17.05%  |
| Intel Core i7           | 17        | 13.18%  |
| Intel Celeron           | 11        | 8.53%   |
| AMD GX                  | 8         | 6.2%    |
| Other                   | 6         | 4.65%   |
| Intel Core i3           | 4         | 3.1%    |
| Intel Xeon Silver       | 3         | 2.33%   |
| Intel Core 2 Duo        | 3         | 2.33%   |
| AMD Ryzen 7             | 3         | 2.33%   |
| Intel Pentium           | 2         | 1.55%   |
| Intel Core 2 Quad       | 2         | 1.55%   |
| Intel Atom              | 2         | 1.55%   |
| AMD Ryzen 9             | 2         | 1.55%   |
| Intel Pentium Dual-Core | 1         | 0.78%   |
| Intel Core m3           | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| AMD Ryzen Threadripper  | 1         | 0.78%   |
| AMD Ryzen 5 PRO         | 1         | 0.78%   |
| AMD G                   | 1         | 0.78%   |
| AMD FX                  | 1         | 0.78%   |
| AMD Athlon 64 X2        | 1         | 0.78%   |
| AMD Athlon              | 1         | 0.78%   |
| AMD A4                  | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 67        | 51.94%  |
| 2       | 35        | 27.13%  |
| Unknown | 7         | 5.43%   |
| 6       | 6         | 4.65%   |
| 8       | 5         | 3.88%   |
| 24      | 4         | 3.1%    |
| 16      | 3         | 2.33%   |
| 12      | 1         | 0.78%   |
| 10      | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 118       | 92.91%  |
| 2       | 6         | 4.72%   |
| Unknown | 3         | 2.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 65        | 50.39%  |
| 2       | 57        | 44.19%  |
| Unknown | 7         | 5.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Skylake       | 18        | 13.95%  |
| Haswell       | 18        | 13.95%  |
| Silvermont    | 10        | 7.75%   |
| SandyBridge   | 10        | 7.75%   |
| KabyLake      | 8         | 6.2%    |
| Puma          | 7         | 5.43%   |
| Penryn        | 7         | 5.43%   |
| IvyBridge     | 7         | 5.43%   |
| Broadwell     | 6         | 4.65%   |
| Westmere      | 5         | 3.88%   |
| Nehalem       | 5         | 3.88%   |
| Core          | 4         | 3.1%    |
| Zen           | 3         | 2.33%   |
| Steamroller   | 3         | 2.33%   |
| IceLake       | 3         | 2.33%   |
| Unknown       | 3         | 2.33%   |
| Zen 2         | 2         | 1.55%   |
| Jaguar        | 2         | 1.55%   |
| Goldmont plus | 2         | 1.55%   |
| Zen+          | 1         | 0.78%   |
| Piledriver    | 1         | 0.78%   |
| K8 Hammer     | 1         | 0.78%   |
| Goldmont      | 1         | 0.78%   |
| Excavator     | 1         | 0.78%   |
| Bobcat        | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 69        | 56.56%  |
| Nvidia                     | 18        | 14.75%  |
| Matrox Electronics Systems | 17        | 13.93%  |
| AMD                        | 15        | 12.3%   |
| ASPEED Technology          | 3         | 2.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 5.65%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 6         | 4.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 4.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 4.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 3.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 3.23%   |
| Intel HD Graphics 530                                                                    | 4         | 3.23%   |
| Matrox Electronics Systems MGA G200EH                                                    | 3         | 2.42%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 2.42%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 2.42%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 2.42%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1.61%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 1.61%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 1.61%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.61%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.61%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 2         | 1.61%   |
| Intel HD Graphics 620                                                                    | 2         | 1.61%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.61%   |
| AMD ES1000                                                                               | 2         | 1.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.81%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.81%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.81%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.81%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.81%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 48.06%  |
| 1 x Matrox     | 17        | 13.18%  |
| 1 x Nvidia     | 16        | 12.4%   |
| 1 x AMD        | 14        | 10.85%  |
| Other          | 10        | 7.75%   |
| 2 x Intel      | 3         | 2.33%   |
| 1 x ASPEED     | 3         | 2.33%   |
| Intel + Nvidia | 2         | 1.55%   |
| Intel + AMD    | 2         | 1.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 103       | 80.47%  |
| Unknown     | 14        | 10.94%  |
| Proprietary | 11        | 8.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 88.98%  |
| 1.01-2.0   | 5         | 3.94%   |
| 0.51-1.0   | 3         | 2.36%   |
| 5.01-6.0   | 2         | 1.57%   |
| 3.01-4.0   | 2         | 1.57%   |
| 7.01-8.0   | 1         | 0.79%   |
| 8.01-16.0  | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 16.67%  |
| Samsung Electronics     | 7         | 14.58%  |
| Hewlett-Packard         | 6         | 12.5%   |
| Chimei Innolux          | 6         | 12.5%   |
| Dell                    | 4         | 8.33%   |
| Philips                 | 3         | 6.25%   |
| Iiyama                  | 2         | 4.17%   |
| AOC                     | 2         | 4.17%   |
| Panasonic               | 1         | 2.08%   |
| LG Electronics          | 1         | 2.08%   |
| Lenovo Group Limited    | 1         | 2.08%   |
| Lenovo                  | 1         | 2.08%   |
| InfoVision              | 1         | 2.08%   |
| Gigabyte Technology     | 1         | 2.08%   |
| Chi Mei Optoelectronics | 1         | 2.08%   |
| BOE                     | 1         | 2.08%   |
| AU Optronics            | 1         | 2.08%   |
| Ancor Communications    | 1         | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch    | 2         | 3.85%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch         | 2         | 3.85%   |
| Iiyama PL2779QQ IVM6641 3840x2160 600x330mm 27.0-inch                | 2         | 3.85%   |
| Dell UP2715K DEL40B6 848x480 600x340mm 27.2-inch                     | 2         | 3.85%   |
| AOC 2350 AOC2350 1920x1080 510x290mm 23.1-inch                       | 2         | 3.85%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch    | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor S23E650 3840x1080                    | 1         | 1.92%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 1         | 1.92%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 710x400mm 32.1-inch            | 1         | 1.92%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 1         | 1.92%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 480x270mm 21.7-inch             | 1         | 1.92%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 1         | 1.92%   |
| LG Electronics LCD Monitor LX20D 1600x1200                           | 1         | 1.92%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch          | 1         | 1.92%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch          | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 1.92%   |
| Lenovo Group Limited LCD Monitor 1920x1080                           | 1         | 1.92%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch          | 1         | 1.92%   |
| Iiyama PL2888UH IVM7104 3840x2160 620x340mm 27.8-inch                | 1         | 1.92%   |
| Hewlett-Packard Z27n G2 HPN348A 2560x1440 600x340mm 27.2-inch        | 1         | 1.92%   |
| Hewlett-Packard w2216 HWP280C 1680x1050 470x290mm 21.7-inch          | 1         | 1.92%   |
| Hewlett-Packard LCD Monitor Z24n 1920x1200                           | 1         | 1.92%   |
| Hewlett-Packard LCD Monitor E241i 1920x1200                          | 1         | 1.92%   |
| Hewlett-Packard L2335 HWP2615 1920x1200 500x310mm 23.2-inch          | 1         | 1.92%   |
| Hewlett-Packard E243i HPN3463 1920x1200 520x320mm 24.0-inch          | 1         | 1.92%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch           | 1         | 1.92%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch       | 1         | 1.92%   |
| Dell UP2715K DEL40B8 3840x2160 600x340mm 27.2-inch                   | 1         | 1.92%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                    | 1         | 1.92%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                    | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch      | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch     | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 27.08%  |
| 1920x1200 (WUXGA)  | 6         | 12.5%   |
| 1366x768 (WXGA)    | 6         | 12.5%   |
| 3840x2160 (4K)     | 5         | 10.42%  |
| 2560x1440 (QHD)    | 4         | 8.33%   |
| 1600x900 (HD+)     | 3         | 6.25%   |
| 3440x1440          | 2         | 4.17%   |
| 2736x1824          | 2         | 4.17%   |
| 3840x1080          | 1         | 2.08%   |
| 2880x1620          | 1         | 2.08%   |
| 1920x1280          | 1         | 2.08%   |
| 1680x1050 (WSXGA+) | 1         | 2.08%   |
| 1600x1200          | 1         | 2.08%   |
| 1440x900 (WXGA+)   | 1         | 2.08%   |
| Unknown            | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 20%     |
| Unknown | 6         | 13.33%  |
| 27      | 5         | 11.11%  |
| 24      | 4         | 8.89%   |
| 23      | 4         | 8.89%   |
| 13      | 4         | 8.89%   |
| 12      | 3         | 6.67%   |
| 21      | 2         | 4.44%   |
| 14      | 2         | 4.44%   |
| 34      | 1         | 2.22%   |
| 32      | 1         | 2.22%   |
| 28      | 1         | 2.22%   |
| 17      | 1         | 2.22%   |
| 11      | 1         | 2.22%   |
| 10      | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 26.67%  |
| 501-600     | 11        | 24.44%  |
| 201-300     | 8         | 17.78%  |
| Unknown     | 6         | 13.33%  |
| 601-700     | 3         | 6.67%   |
| 701-800     | 2         | 4.44%   |
| 401-500     | 2         | 4.44%   |
| 351-400     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 25        | 60.98%  |
| 16/10   | 6         | 14.63%  |
| Unknown | 6         | 14.63%  |
| 3/2     | 3         | 7.32%   |
| 21/9    | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 20.45%  |
| 201-250        | 6         | 13.64%  |
| Unknown        | 6         | 13.64%  |
| 81-90          | 5         | 11.36%  |
| 301-350        | 5         | 11.36%  |
| 61-70          | 3         | 6.82%   |
| 351-500        | 3         | 6.82%   |
| 251-300        | 3         | 6.82%   |
| 51-60          | 2         | 4.55%   |
| 71-80          | 1         | 2.27%   |
| 121-130        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 28.26%  |
| 51-100        | 9         | 19.57%  |
| 101-120       | 8         | 17.39%  |
| 161-240       | 6         | 13.04%  |
| Unknown       | 6         | 13.04%  |
| More than 240 | 2         | 4.35%   |
| 1-50          | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 87        | 66.92%  |
| 1     | 34        | 26.15%  |
| 2     | 8         | 6.15%   |
| 3     | 1         | 0.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 54.24%  |
| Realtek Semiconductor    | 37        | 20.9%   |
| Broadcom                 | 22        | 12.43%  |
| Qualcomm Atheros         | 6         | 3.39%   |
| TP-Link                  | 2         | 1.13%   |
| Ralink Technology        | 2         | 1.13%   |
| Sierra Wireless          | 1         | 0.56%   |
| NetXen Incorporated      | 1         | 0.56%   |
| Microsoft                | 1         | 0.56%   |
| Mellanox Technologies    | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| JMicron Technology       | 1         | 0.56%   |
| IMC Networks             | 1         | 0.56%   |
| Hewlett-Packard          | 1         | 0.56%   |
| Edimax Technology        | 1         | 0.56%   |
| Chelsio Communications   | 1         | 0.56%   |
| Apple                    | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 14.86%  |
| Intel I210 Gigabit Network Connection                                         | 17        | 7.66%   |
| Intel I211 Gigabit Network Connection                                         | 14        | 6.31%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 3.6%    |
| Intel 82580 Gigabit Network Connection                                        | 7         | 3.15%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 3.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 2.7%    |
| Intel Ethernet Connection I217-LM                                             | 5         | 2.25%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.25%   |
| Intel Wireless 7260                                                           | 4         | 1.8%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 1.8%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 1.8%    |
| Intel Wireless 8260                                                           | 3         | 1.35%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.35%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.9%    |
| Intel Wireless 7265                                                           | 2         | 0.9%    |
| Intel Wi-Fi 6 AX200                                                           | 2         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.9%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.9%    |
| Intel 82583V Gigabit Network Connection                                       | 2         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.9%    |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 0.9%    |
| Intel 82576 Gigabit Network Connection                                        | 2         | 0.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 0.9%    |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 0.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.45%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                 | 1         | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 55.56%  |
| Realtek Semiconductor | 5         | 11.11%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Broadcom              | 4         | 8.89%   |
| TP-Link               | 2         | 4.44%   |
| Ralink Technology     | 2         | 4.44%   |
| Sierra Wireless       | 1         | 2.22%   |
| IMC Networks          | 1         | 2.22%   |
| Edimax Technology     | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 4         | 8.7%    |
| Intel Wireless 8260                                            | 3         | 6.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 6.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.35%   |
| Intel Wireless 7265                                            | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 4.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.35%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 2.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 2.17%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 2.17%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.17%   |
| Intel Wireless-AC 9260                                         | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.17%   |
| Intel Wireless 3165                                            | 1         | 2.17%   |
| Intel WiFi Link 5100                                           | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.17%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 2.17%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 84        | 57.93%  |
| Realtek Semiconductor    | 37        | 25.52%  |
| Broadcom                 | 18        | 12.41%  |
| Qualcomm Atheros         | 2         | 1.38%   |
| Microsoft                | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| JMicron Technology       | 1         | 0.69%   |
| Apple                    | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 33        | 19.3%   |
| Intel I210 Gigabit Network Connection                                         | 17        | 9.94%   |
| Intel I211 Gigabit Network Connection                                         | 14        | 8.19%   |
| Intel I350 Gigabit Network Connection                                         | 8         | 4.68%   |
| Intel 82580 Gigabit Network Connection                                        | 7         | 4.09%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 4.09%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 6         | 3.51%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 2.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 2.92%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 4         | 2.34%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 2.34%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 2.34%   |
| Intel Ethernet Connection I217-V                                              | 3         | 1.75%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.17%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 1.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 1.17%   |
| Intel 82583V Gigabit Network Connection                                       | 2         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.17%   |
| Intel 82576NS Gigabit Network Connection                                      | 2         | 1.17%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 1.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2         | 1.17%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 2         | 1.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.58%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1         | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.58%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 1         | 0.58%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.58%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.58%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.58%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 120       | 71.86%  |
| WiFi     | 42        | 25.15%  |
| Unknown  | 4         | 2.4%    |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 82.22%  |
| WiFi     | 24        | 17.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 34.35%  |
| 1     | 21        | 16.03%  |
| 4     | 19        | 14.5%   |
| 3     | 16        | 12.21%  |
| 6     | 12        | 9.16%   |
| 5     | 8         | 6.11%   |
| 8     | 4         | 3.05%   |
| 7     | 3         | 2.29%   |
| 13    | 1         | 0.76%   |
| 9     | 1         | 0.76%   |
| 0     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 121       | 93.8%   |
| Yes  | 8         | 6.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 14        | 48.28%  |
| Cambridge Silicon Radio | 4         | 13.79%  |
| Broadcom                | 3         | 10.34%  |
| IMC Networks            | 2         | 6.9%    |
| Hewlett-Packard         | 2         | 6.9%    |
| Dell                    | 2         | 6.9%    |
| Lite-On Technology      | 1         | 3.45%   |
| Apple                   | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 8         | 27.59%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 4         | 13.79%  |
| Intel AX201 Bluetooth                                   | 2         | 6.9%    |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 6.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 3.45%   |
| Intel AX200 Bluetooth                                   | 1         | 3.45%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip    | 1         | 3.45%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 3.45%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 3.45%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 3.45%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 3.45%   |
| Dell Dell Wireless 355C Bluetooth 2.0 + EDR module      | 1         | 3.45%   |
| Broadcom Broadcom Bluetooth 4.0 Adapter                 | 1         | 3.45%   |
| Apple Apple Broadcom Built-in Bluetooth                 | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 67        | 64.42%  |
| AMD                     | 17        | 16.35%  |
| Nvidia                  | 16        | 15.38%  |
| Philips (or NXP)        | 1         | 0.96%   |
| Lenovo                  | 1         | 0.96%   |
| GN Netcom               | 1         | 0.96%   |
| BEHRINGER International | 1         | 0.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 6.3%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 5.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 5.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 4.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 3.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.94%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.94%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.15%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 2.36%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 2.36%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 2.36%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 2.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.57%   |
| Philips (or NXP) Philips SHG7980                                                                  | 1         | 0.79%   |
| Nvidia MCP65 High Definition Audio                                                                | 1         | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.79%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 18.25%  |
| SK hynix            | 20        | 15.87%  |
| Corsair             | 18        | 14.29%  |
| Unknown             | 15        | 11.9%   |
| Kingston            | 13        | 10.32%  |
| Micron Technology   | 12        | 9.52%   |
| Crucial             | 4         | 3.17%   |
| Hewlett-Packard     | 3         | 2.38%   |
| G.Skill             | 3         | 2.38%   |
| Elpida              | 3         | 2.38%   |
| Unknown             | 3         | 2.38%   |
| Kimtigo             | 2         | 1.59%   |
| HPE                 | 2         | 1.59%   |
| Toshiba             | 1         | 0.79%   |
| Tigo                | 1         | 0.79%   |
| Smart Modular       | 1         | 0.79%   |
| ASint Technology    | 1         | 0.79%   |
| Apacer              | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 5         | 3.68%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s         | 4         | 2.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 3         | 2.21%   |
| Unknown                                                     | 3         | 2.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.47%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s        | 2         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.47%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                   | 2         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.47%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s              | 2         | 1.47%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                  | 1         | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1332MT/s                | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 1332MT/s                | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                  | 1         | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR3 1332MT/s                | 1         | 0.74%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s        | 1         | 0.74%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s         | 1         | 0.74%   |
| Tigo RAM 1600Mhz-4G 4GB DIMM DDR3 1600MT/s                  | 1         | 0.74%   |
| Smart Modular RAM Module 4GB DIMM DDR3 1333MT/s             | 1         | 0.74%   |
| SK hynix RAM HYMP151F72CP4N3-Y5 4096MB FB-DIMM DDR2 667MT/s | 1         | 0.74%   |
| SK hynix RAM HMT451U7AFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT41GU7AFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT351U7EFR8C-RD 4GB DIMM DDR3                 | 1         | 0.74%   |
| SK hynix RAM HMT351U7CFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB DIMM DDR3 1600MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 0.74%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 0.74%   |
| SK hynix RAM HMA84GR7AFR4N-VK 32GB DIMM DDR4 2666MT/s       | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 67        | 59.82%  |
| DDR4    | 31        | 27.68%  |
| DDR2    | 7         | 6.25%   |
| Unknown | 3         | 2.68%   |
| SDRAM   | 2         | 1.79%   |
| LPDDR3  | 1         | 0.89%   |
| DRAM    | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 68        | 60.71%  |
| SODIMM  | 41        | 36.61%  |
| FB-DIMM | 2         | 1.79%   |
| Chip    | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 47        | 39.17%  |
| 8192  | 33        | 27.5%   |
| 16384 | 16        | 13.33%  |
| 2048  | 14        | 11.67%  |
| 1024  | 7         | 5.83%   |
| 32768 | 3         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 32.76%  |
| 1333    | 28        | 24.14%  |
| 2667    | 10        | 8.62%   |
| 2133    | 9         | 7.76%   |
| 800     | 6         | 5.17%   |
| 2400    | 5         | 4.31%   |
| 3200    | 4         | 3.45%   |
| 2666    | 4         | 3.45%   |
| 667     | 4         | 3.45%   |
| Unknown | 4         | 3.45%   |
| 1867    | 1         | 0.86%   |
| 1334    | 1         | 0.86%   |
| 1332    | 1         | 0.86%   |
| 333     | 1         | 0.86%   |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 8         | 40%     |
| Acer                  | 3         | 15%     |
| Realtek Semiconductor | 2         | 10%     |
| IMC Networks          | 2         | 10%     |
| Suyin                 | 1         | 5%      |
| Quanta                | 1         | 5%      |
| Microdia              | 1         | 5%      |
| Logitech              | 1         | 5%      |
| Lenovo                | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Suyin Asus Integrated Webcam             | 1         | 5%      |
| Realtek Integrated_Webcam_HD             | 1         | 5%      |
| Realtek Front Camera                     | 1         | 5%      |
| Quanta VGA WebCam                        | 1         | 5%      |
| Microdia Integrated Webcam               | 1         | 5%      |
| Logitech Webcam C270                     | 1         | 5%      |
| Lenovo Integrated Webcam                 | 1         | 5%      |
| IMC Networks HP TrueVision HD Camera     | 1         | 5%      |
| IMC Networks EasyCamera                  | 1         | 5%      |
| Chicony USB2.0 HD UVC WebCam             | 1         | 5%      |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 5%      |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 5%      |
| Chicony ThinkPad T490 Webcam             | 1         | 5%      |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5%      |
| Chicony Integrated HP HD Webcam          | 1         | 5%      |
| Chicony Integrated Camera                | 1         | 5%      |
| Chicony Camera                           | 1         | 5%      |
| Acer ThinkPad P50 Integrated Camera      | 1         | 5%      |
| Acer Integrated Camera                   | 1         | 5%      |
| Acer EasyCamera                          | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 33.33%  |
| Upek             | 2         | 22.22%  |
| AuthenTec        | 2         | 22.22%  |
| Synaptics        | 1         | 11.11%  |
| Broadcom         | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| AuthenTec AES2810                                                            | 1         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 11.11%  |

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
| 1     | 51        | 39.53%  |
| 0     | 44        | 34.11%  |
| 2     | 23        | 17.83%  |
| 3     | 6         | 4.65%   |
| 4     | 3         | 2.33%   |
| 5     | 2         | 1.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 74        | 66.67%  |
| Net/wireless             | 9         | 8.11%   |
| Fingerprint reader       | 7         | 6.31%   |
| Card reader              | 6         | 5.41%   |
| Firewire controller      | 4         | 3.6%    |
| Graphics card            | 3         | 2.7%    |
| Storage/ata              | 2         | 1.8%    |
| Sound                    | 2         | 1.8%    |
| Network                  | 2         | 1.8%    |
| Net/ethernet             | 1         | 0.9%    |
| Bluetooth                | 1         | 0.9%    |

